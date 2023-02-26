---
title: Environment Variables
description: Environment Variables Decky provides for as plugins running as subprocesses.
published: true
date: 2023-02-26T03:05:04.104Z
tags: plugin-dev, env-vars
editor: markdown
dateCreated: 2023-01-23T00:49:40.156Z
---

# Environment Variables

From Pre-Release 2.5.2-pre1 onward, decky provides these environment variables to each plugin and any other subprocesses it runs from python. These variables can be accessed by using the built-in `os` python module.
- e.g: `homeDir = os.environ['HOME']` or `homeDir = os.environ.get('HOME')`

|---|---|---|
| Environment Variable | Description | Example Return |
|`HOME`|The home directory of the effective user running the process.[^1]|`/root` or `/home/deck`|
|`USER`|The username of the effective user running the process.[^1]|`root` or `deck`|
|`DECKY_VERSION`|The running version of the decky loader.|`v2.5.0-pre1`|
|`DECKY_USER`|The username of the user whose home decky resides in.|`deck`|
|`DECKY_USER_HOME`[^2]|The home of the user where decky resides in.|`/home/deck`|
|`DECKY_HOME`|The root of the decky folder|`/home/deck/homebrew`|
|`DECKY_PLUGIN_SETTINGS_DIR`|The recommended path in which to store configuration files (created automatically)|`/home/deck/homebrew/settings/<plugin-name>`|
|`DECKY_PLUGIN_RUNTIME_DIR`|The recommended path in which to store runtime data (created automatically)|`/home/deck/homebrew/data/<plugin-name>`|
|`DECKY_PLUGIN_LOG_DIR`|The recommended path in which to store persistent logs (created automatically)|`/home/deck/homebrew/logs/<plugin-name>`|
|`DECKY_PLUGIN_DIR`|The root of the plugin's directory|`/home/deck/homebrew/plugins/<plugin-name>`|
|`DECKY_PLUGIN_NAME`|The name of the plugin as specified in the `plugin.json`|`Example Plugin`|
|`DECKY_PLUGIN_AUTHOR`|The author of the plugin as specified in the `plugin.json`|`John Doe`|
|`DECKY_PLUGIN_VERSION`|The version of the plugin as specified in the `package.json`|`0.0.1`|
[^1]: If `root` is specified in the plugin's flags, this returns the root user's information, otherwise the user whose home decky resides in.
[^2]: Only available from Pre-Release 2.6.0-pre1 onward