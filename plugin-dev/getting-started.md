---
title: Getting Started
description: How-To guide about developing a plugin
published: true
date: 2023-02-15T20:55:28.799Z
tags: plugin-dev
editor: markdown
dateCreated: 2022-07-03T19:33:01.141Z
---

# Getting Started

A typical Plugin is structured like this: 

```
├── assets/           # Assets such as images and other resources
├── defaults/				 # Plain-text configs and templates (not required)
├── main.py           # Backend Python code
├── plugin.json       # Metadata file
├── README.md         # Project Readme
├── LICENSE           # License
├── src/              # Frontend TypeScript code
    ├── index.tsx
```

The easiest way to get this structure and get started with development is by visiting the [Decky Plugin Template Repository](https://github.com/SteamDeckHomebrew/decky-plugin-template) and clicking on `Use this Template`.

Afterwards you can clone your newly created repository and get started.

## Metadata

The plugin.json file is used by decky and the store to determine how things are being displayed and how the plugin behaves. It's required for every plugin.

The following fields can be specified:
- `"name"`: The name of the Plugin as it will be displayed in the Decky menu
- `"author"`: The author of the Plugin. That's you!
- `"flags"`: An array of flags that get used to configure various behaviour for your plugin
    - `"debug"`: Enable various debug capabilities such as auto reload for your plugin
    - `"root"`: Tells decky to run your plugin as root. **ONLY DO THIS WHEN ACTUALLY REQUIRED**
- `"publish"`: A object containing various information used by the Decky Store
    - `"tags"`: A list of tags that describe your plugin
    - `"description"`: A short description that will be displayed with your Plugin on the store
    - `"image"`: A link to an image that will be embedded in the store page
    
## Frontend

The frontend is a collection of TypeScript files where `index.tsx` is the main entry point.
In there you can find a `definePlugin` method that returns an object containing the plugin name, content and icon for your plugin.

In the `Content` object, the interface of the Plugin and various init code can be defined.

### API

To talk to the backend, simply use the `ServerAPI` object passed in with the `Content` variable.

The following code with call a method called `my_backend_function` in your backend and passes two parameters `parameter_a` and `parameter_b` with the values `"Hello"` and `"World"` to it.
```ts
serverAPI!.callPluginMethod("my_backend_function", { "parameter_a": "Hello", "parameter_b": "World" });
```

## Backend

### Python

In a python backend, all your plugin functions can be defined like this:
```python
class Plugin:
		# The backend function that we called above
    async def my_backend_function(self, parameter_a, parameter_b):
        print(f"{parameter_a} {parameter_b}")

		# Function that can contain long-running code that will stay alive for the entire duration of your plugin
    async def _main(self):
        pass
        
     # Function used to clean up a plugin when it's told to unload by Decky-Loader
    async def _unload(self):
        pass

```

### SettingsManager

Decky exposes a python class called SettingsManager from the ``settings.py`` in Decky Loader to save settings/configurations etc in local json files as opposed to the usage of localStorage directly within React.

Here's a snippet from [``decky-autosuspend``](https://github.com/jurassicplayer/decky-autosuspend/blob/79ba909f8fe3575a46005a312d0cff0009f32b92/main.py) which utilizes SettingsManager to commit settings to local json file:
```py
# Initialize decky-loader settings manager
from settings import SettingsManager
from helpers import get_home_path, get_homebrew_path, get_user

import os
logger.info('Settings path: {}{}settings'.format(get_homebrew_path(get_home_path(get_user())), os.sep))
settings = SettingsManager(name="autosuspend", settings_directory='{}{}settings'.format(get_homebrew_path(get_home_path(get_user())), os.sep))
settings.read()

class Plugin:
  async def settings_read(self):
    logger.info('Reading settings')
    return settings.read()
  async def settings_commit(self):
    logger.info('Saving settings')
    return settings.commit()
  async def settings_getSetting(self, key: str, defaults):
    logger.info('Get {}'.format(key))
    return settings.getSetting(key, defaults)
  async def settings_setSetting(self, key: str, value):
    logger.info('Set {}: {}'.format(key, value))
    return settings.setSetting(key, value)
```

If you would like to better understand how SettingsManager works and how to utilize it in your own plugin, you can reference it's source code [here](https://github.com/SteamDeckHomebrew/decky-loader/blob/main/backend/settings.py).

Please note that there is logic in SettingsManager that runs when an instance of SettingsManager is intialized. This logic accomodates older plugins who effected by important adjustments to SettingsManager. The ``wrong_dir`` variable, and some other sections commented along the same lines are your relevant lines. Unless you are using a [custom directory](https://github.com/SteamDeckHomebrew/decky-loader/blob/main/backend/settings.py#L9) to save these files, this logic shouldn't effect you.
