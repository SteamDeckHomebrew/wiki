---
title: Environment Variables
description: Environment Variables Decky provides for as plugins running as subprocesses.
published: true
date: 2023-02-24T22:26:10.558Z
tags: plugin-dev, env-vars
editor: markdown
dateCreated: 2023-01-23T00:49:40.156Z
---

# Environment Variables

From Pre-Release 2.5.2-pre1 onward, decky provides these environment variables to each plugin and any other subprocesses it runs from python.

- `HOME`: the home directory of the effective user running the process
  + e.g.: if `root` was specified in the plugin's flags it will be `/root` otherwise the user whose home decky resides in
- `USER`: the effective username running the process
  + e.g.: it would be `root` if `root` was specified in the plugin's flags otherwise the user whose home decky resides in
- `DECKY_VERSION`: the version of the decky loader
  + e.g.: `v2.5.0-pre1`
- `DECKY_USER`: the user whose home decky resides in
  + e.g.: `deck`
- `DECKY_USER_HOME`: the home of the user where decky resides in
	+ e.g.: `/home/deck`
- `DECKY_HOME`: the root of the decky folder
  + e.g.: `/home/deck/homebrew`
- `DECKY_PLUGIN_SETTINGS_DIR`: the recommended path in which to store configuration files (created automatically)
  + e.g.: `/home/deck/homebrew/settings/decky-plugin-template`
- `DECKY_PLUGIN_RUNTIME_DIR`: the recommended path in which to store runtime data (created automatically)
  + e.g.: `/home/deck/homebrew/data/decky-plugin-template`
- `DECKY_PLUGIN_LOG_DIR`: the recommended path in which to store persistent logs (created automatically)
  + e.g.: `/home/deck/homebrew/logs/decky-plugin-template`
- `DECKY_PLUGIN_DIR`: the root of the plugin's directory
  + e.g.: `/home/deck/homebrew/plugins/decky-plugin-template`
- `DECKY_PLUGIN_NAME`: the name of the plugin as specified in the `plugin.json`
  + e.g.: `Example Plugin`
- `DECKY_PLUGIN_VERSION`: the version of the plugin as specified in the `package.json`
  + e.g.: `0.0.1`
- `DECKY_PLUGIN_AUTHOR`: the author of the plugin as specified in the `plugin.json`
  + e.g.: `John Doe`

