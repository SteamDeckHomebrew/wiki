---
title: Environment Variables
description: User configurable environment variables
published: true
date: 2023-07-28T21:54:00.067Z
tags: user-guide, env-vars
editor: markdown
dateCreated: 2023-07-28T20:27:21.135Z
---

# Environment Variables
> This is an advanced feature, only use if you know what you are doing.
{.is-warning}

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