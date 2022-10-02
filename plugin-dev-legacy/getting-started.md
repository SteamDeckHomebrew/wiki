---
title: Getting Started
description: How to write your first plugin
published: true
date: 2022-07-03T19:06:53.897Z
tags: plugin-dev-legacy
editor: markdown
dateCreated: 2022-04-08T14:39:05.332Z
---

# Getting Started

A typical Plugin is structured like this:

```bash
├── plugin.json       # Metadata
├── main.py           # Python backend executable
├── main_view.html    # HTML loaded when the plugin is opened
├── tile_view.html    # HTML loaded in the selection menu
├── LICENSE           # Project license
└── README.md         # Project readme
```

## Metadata

The `plugin.json` file contains metadata information used by the plugin loader to load the plugin.
The following fields can be specified:

- `"name"`: The name of the plugin. This will be used to generate a button if `tile_view_html` is not specified
- `"author"`: The author of the plugin. Currently only used for reference
- `"main_view_html"`: The path to the html file which will be rendered when selecting the plugin from the main menu
- `"tile_view_html"` **(optional)**: The path to the html file which will be rendered in the main plugin menu instead of the default button. If not specified, a default button will be displayed
- `"flags"`: An array of flags that apply for this plugin
   - `"debug"`: Enables various debug features helpful for development. **This flag needs to be removed before being able to publish the plugin**
   - `"root"`: Allow functions in this plugin to be run as root
- `"publish"` **(optional)**: Metadata for publishing, required to submit to **[plugins.deckbrew.xyz](https://plugins.deckbrew.xyz/)**
   - `"discord_id"`: The Discord user ID of the submitter/developer
   - `"description"`: The description of the plugin
   - `"tags"`: An array of categories for this plugin. Any string is a valid tag, except `"root"`
   

## Frontend

The frontend is a typical HTML file. 

### Resources

The following built-in resources are available:

- `/static/styles.css`: Contains css files loaded from Steam so the same look and feel can be applied to the plugin code
- `/static/library.js`: Contains library wrappers to allow interacting with the plugin loader and the backend

Additionally, the `/steam_resource` route can be used to access other files that are loaded by Steam

### Library

```js
async function fetch_nocors(url, request={});
```
This function allows fetching files from external sources circumventing Steam's CORS protection.
It works the same as normal `fetch()`

---

```js
async function call_plugin_method(method_name, arg_object={});
```
This function allows calling a function inside of the python backend. 
- `method_name` specifies the name of the method to call
- `arg_object` allows passing arguments to the python function. 
    - e.g `{ "some_param_1": 123", "some_param_2": True }`

---

```js
async function execute_in_tab(tab, run_async, code);
```
This functions allows executing JavaScript in another steam tab. This is useful because not all Steam library functions can be accessed from the QuickAccess tab.
- `tab` specifies the name of the tab where code should be executed in
    - Can be one of `QuickAccess`, `MainMenu`, `Toast`, `SP`
- `run_async` specifies if any promise returned by the code should be awaited before returning it back
- `code` specifies the JavaScript code that will be executed in the other tab

---

```js
async function inject_css_into_tab(tab, style);
```
This function allows injecting CSS into a tab. Useful for custom themes
- `tab` specifies the name of the tab where code should be executed in
    - Can be one of `QuickAccess`, `MainMenu`, `Toast`, `SP`
- `style` specifies the CSS that will be injected

This function returns a UUID that refers to the created `<style>` element

---

```js
async function remove_css_from_tab(tab, css_id);
```
This function allows removing previously injected CSS from a tab
- `tab` specifies the name of the tab where code should be executed in
    - Can be one of `QuickAccess`, `MainMenu`, `Toast`, `SP`
- `css_id` specifies the UUID that was previously returned by `inject_css_into_tab`

## Backend

A typical python backend file looks like this:

```py
class Plugin:
    async def method_1(self, *args):
        return getuid()

    async def method_2(self, *args):
        pass
        
    async def __private_method(self):
    		pass

    async def _main(self):
        pass
```

> Do not rename the class to anything else as the loader won't find it then.
{.is-warning}

- Every plugin can have a `_main` method which will be executed in its own loop when the plugin is loaded. In there, long running code can be executed such as hosting a service or opening a connection to another program. It will run from the moment the plugin gets loaded by the loader until the loader stops or the plugin gets reloaded
- Every plugin can have zero or more other methods. These methods can be called from JavaScript using their name. When prefixed with `__`, the method is marked as private and can't be called from JavaScript anymore.