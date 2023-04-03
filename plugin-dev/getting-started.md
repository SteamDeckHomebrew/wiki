---
title: Getting Started
description: How-To guide about developing a plugin
published: true
date: 2023-04-03T20:21:04.542Z
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

Here's a snippet from [``decky-autosuspend``](https://github.com/jurassicplayer/decky-autosuspend/blob/main/main.py)'s ``main.py`` which utilizes SettingsManager to commit settings to local json file:
```py
# THIS CODE IS LICENSED UNDER THE BSD 3-CLAUSE LICENSE
# PLEASE SEE THE RELEVANT REPOSITORY LINKED ABOVE FOR FURTHER DETAILS
# Initialize decky-loader settings manager
from settings import SettingsManager

# Get environment variable
settingsDir = os.environ["DECKY_PLUGIN_SETTINGS_DIR"]

import os
logger.info('Settings path: {}'.format(os.path.join(settingsDir, 'settings.json'))
settings = SettingsManager(name="settings", settings_directory=settingsDir)
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


## Other

### The "defaults" folder

Originally developed as a method for plugins to include default configuration files and other related items, this is now the defacto method for including files outside of those generated by the backend/frontend build processes or usage of remote binaries. The defaults folder is usually utilized  for including python libraries that a plugin is dependent upon etc.

This is extremely hacky but it is the "official" method that is needed for including items that are not a part of the scope of a plugin by default (enforced by CI).

Say you need to include python code that you seperated out into other files in a folder called ``py`` etc. This folder would be moved into the defaults folder and symlinked into the root of the directory for local code testing if that is needed etc.

We appreciate feedback on this topic, and a suggestion for a plugin's plugin.json including a whitelist of needed files is likely a future solution that will be adopted.

### pnpm
Frontend dependencies are managed by [pnpm](https://pnpm.io/). The CI for builds requires pnpm-lock.yaml to be on version 6.0. To ensure you're on the right version update your pnpm with `pnpm add -g pnpm` and run `pnpm i`. To verify, check that your pnpm-lock.yaml contains `lockfileVersion: '6.0'` at the top.
