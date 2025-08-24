---
title: Environment Variables
description: Environment Variables Decky provides for as plugins running as subprocesses.
published: true
date: 2025-08-24T01:28:49.072Z
tags: plugin-dev, env-vars
editor: markdown
dateCreated: 2023-01-23T00:49:40.156Z
---

# Environment Variables

From Pre-Release 2.5.2-pre1 onward, decky provides these environment variables to each plugin and any other subprocesses it runs from python. These variables can be accessed by using the built-in `os` python module or the decky_plugin interface available in the [plugin template](https://github.com/SteamDeckHomebrew/decky-plugin-template).
```
	# Examples:
  import os
  homeDir = os.environ['HOME']
  homeDir = os.environ.get('HOME')
  
  import decky_plugin
  homeDir = decky_plugin.HOME
 ```

|---|---|---|
| Environment Variable | Description | Decky Version | Example Return |
|`USER`|The username of the effective user running the process.[^1]|v2.5.2-pre1+|`root` or `deck`|
|~~`USER_ID`~~|~~The UID of the effective user running the process.[^1]~~|~~v2.6.3-pre3+~~|~~`0` or `1000`~~|
|`HOME`|The home directory of the effective user running the process.[^1]|v2.5.2-pre1+|`/root` or `/home/deck`|
|`DECKY_USER`|The username of the user whose home decky resides in.|v2.5.2-pre1+|`deck`|
|~~`DECKY_USER_ID`~~|~~The UID of the user whose home decky resides in.~~|~~v2.6.3-pre3+~~|~~`1000`~~|
|`DECKY_USER_HOME`|The home of the user where decky resides in.|v2.6.0-pre1+|`/home/deck`|
|`DECKY_VERSION`|The running version of the decky loader.|v2.5.2-pre1+|`v2.5.0-pre1`|
|`DECKY_HOME`|The root of the decky folder|v2.5.2-pre1+|`/home/deck/homebrew`|
|`DECKY_PLUGIN_SETTINGS_DIR`|The recommended path in which to store configuration files (created automatically)|v2.5.2-pre1+|`/home/deck/homebrew/settings/<plugin-name>`|
|`DECKY_PLUGIN_RUNTIME_DIR`|The recommended path in which to store runtime data (created automatically)|v2.5.2-pre1+|`/home/deck/homebrew/data/<plugin-name>`|
|`DECKY_PLUGIN_LOG_DIR`|The recommended path in which to store persistent logs (created automatically)|v2.5.2-pre1+|`/home/deck/homebrew/logs/<plugin-name>`|
|`DECKY_PLUGIN_DIR`|The root of the plugin's directory (created automatically on plugin install) |v2.5.2-pre1+ |`/home/deck/homebrew/plugins/<plugin-name>` |
|`DECKY_PLUGIN_NAME`|The name of the plugin as specified in the `plugin.json`|v2.5.2-pre1+|`Example Plugin`|
|`DECKY_PLUGIN_AUTHOR`|The author of the plugin as specified in the `plugin.json`|v2.5.2-pre1+|`John Doe`|
|`DECKY_PLUGIN_VERSION`|The version of the plugin as specified in the `package.json`|v2.5.2-pre1+|`0.0.1`|
[^1]: If `root` is specified in the plugin's flags, this returns the root user's information, otherwise the user whose home decky resides in.

Decky can be given various environment variables on startup which are used to overwrite various settings. On a standard install you'd do this by editing the .service file. For more info, the code for these can be viewed in the 3 localplatform python files in the backend folder.

|---|---|---|
| Environment Variable | Description | Default Value |
|String options|||
|`PRIVILEGED_PATH`|The root of the decky folder|`/home/deck/homebrew`[^1]|
|`UNPRIVILEGED_PATH`|The root of the decky folder|`/home/deck/homebrew`[^1]|
|`SERVER_HOST`|The host for decky's server|`127.0.0.1`|
|`SERVER_PORT`|Which port decky runs the server on|`1337`|
|`LOG_LEVEL`|The level of logging|`INFO`[^2]|
|Boolean Options|||
|`CHOWN_PLUGIN_PATH`|Is the plugin path chowned|`1`|
|`LIVE_RELOAD`|Should plugins automatically reload when changes are detected|`1`|
|`KEEP_SYSTEMD_SERVICE`|Should the systemd service be kept on decky updates|`0`|
[^1]: The default values are a little more complex, check the python for more info
[^2]: The valid options are `CRITICAL`, `ERROR`, `WARNING`, `INFO` and `DEBUG`