---
title: Frontend/Backend Communication
description: How to communicate between the frontend and backend.
published: true
date: 2024-06-27T10:34:41.538Z
tags: 
editor: markdown
dateCreated: 2024-06-12T11:51:10.773Z
---

## Frontend -> Backend Communication

First, you have to write a backend function.
This is done by just adding a new method to your `Plugin` class:
```python
class Plugin:
    async def my_backend_function(self) -> int:
        return 5

    async def backend_addition(self, parameter_a: int, parameter_b: int) -> str:
        return str(parameter_a + parameter_b)
```
You can have as many parameters as you like, and \*args should (TODO: check this) also work, but \*\*kwargs will not.
You do not *need* to provide types for the parameters.
You can return any data that is serializable to JSON, so dictionaries, lists, ints, floats, strings, etc.

Then, in the frontend, `@decky/api` provides two functions for calling backend methods. Just like for returning values, you can send any JSON serializable data as parameters, like plain objects, arrays, numbers, strings, etc.

### call()

`call` runs a backend function and asynchronously returns the result.
It takes in the name of the backend function, and then all of the parameters to pass in.
If the backend function errors then `call` will raise an error, and will include the python traceback. (TODO: this might not actually work for plugins)
It must be awaited if you want the returned data, but if you don't need the result you do not need to await it, it will still run.

```typescript
import { call } from '@decky/api';

// data1 = 5;
let data1 = await call('my_backend_function');

// data2 = "10"
let data2 = await call('backend_addition', 5, 5);

```

It can also be given types, if you know the types for the data going in and out.
In this example, you pass `backend_addition` two numbers (a and b) and it returns a string.
```typescript
import { call } from '@decky/api';

// data1 = 5;
let data1 = await call<[], number>('my_backend_function');

// data2 = "10"
let data2 = await call<[a: number, b: number], string>('backend_addition', 5, 5);
```


### callable()

`callable` gives you a JS handle to a backend function, which acts the same as `call`.
`callable` is synchronous so does not need to be awaited, but the function it returns is asynchronous.

```typescript
import { callable } from '@decky/api';

const adder = callable('backend_addition');
// data = "10";
let data = await adder(5, 5);
```

Like `call` it can also be given types.
In this example, you give it two numbers (a and b) and it returns a string.
```typescript
import { callable } from '@decky/api';

const adder = callable<[a: number, b: number], string>('backend_addition');
// data = "10";
let data = await adder(5, 5);
```

---

## Backend -> Frontend Communication

Sometimes, data from the backend needs to be delivered to the frontend, like the percentage for a progress bar.
These can be sent using events. The primary differences between events and calling functions are: 
- Events can trigger multiple functions run that are totally separate from each other.
- Events do not return any information to the caller.

### Frontend

First, you set up the event listener in the frontend. You can use `addEventListener` to register a function that will run every time that event is fired, and use `removeEventListener` to unregister it.
```typescript
import { addEventListener, removeEventListener } from '@decky/api';

let progress = 0;
function updateProgress(new_progress: int) {
    progress = new_progress;
};

addEventListener('progress_update', updateProgress);

// .. later in the code, to remove the listener

removeEventListener('progress_update', updateProgress);
```

If using this in react code, then a useEffect is the best way to make sure to unregister your event listeners.

```typescript
import { addEventListener, removeEventListener } from '@decky/api';
import { useEffect, useState } from 'react';

function Component() {
    const [progress, setProgress] = useState(0);

    function updateProgress(new_progress: number, information: string) {
        setProgress(new_progress);
        console.log("progress info: ", information);
    };

    useEffect(() => {
        addEventListener('progress_update', updateProgress);

				// this function runs on component unmount
        return () => {
            removeEventListener('progress_update', updateProgress);
				}
    }, [])

		// ...
};
```

### Backend

Events can be fired from the backend using `emit`. It is an asynchronous function, and unlike javascript, it must be awaited to run. If you want to run it in a synchronous function, then `asyncio.run(emit("event"))` or something similar should work.

For example, if you wanted to emit an event with no data, then you can just do:
```python
await emit("event_name")
```
And if you wanted to pass some data along with the event, like for the progress bar above:
```python
await emit("progress_update", 50, "half way there!")
```
`emit` is similar to `call`, the first parameter is the event name, and all other parameters are passed to the frontend. And again, data sent along with events must be JSON serializable.