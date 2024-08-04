---
title: Windows Installation
description: UNSTABLE, MAY BRAKE
published: true
date: 2024-08-04T23:15:05.659Z
tags: 
editor: markdown
dateCreated: 2024-08-04T22:47:16.479Z
---

> Decky is not supported on windows, so some features may not work and it may be unstable or break at any time. We appreciate bug reports from our windows users, but issues will not get fixed with urgency, as it is not our target platform.
{.is-danger}

> As plugins are not tested for windows before going onto the store, many may be completely non-functional on windows. Please do not complain to plugin developers if their plugins don't work on windows, and be understanding if they do not wish to support windows.
{.is-danger}

> You must be logged in on github to download the exe.
{.is-warning}


# Installation on windows
1. Read the warnings above before installing and understand you may experience instability.
0. Put an empty text file called `.cef-enable-debugging` in `C:\Program Files (x86)\Steam` (this enables [cef debugging](/plugin-dev/cef-debugging) which decky needs to work).
0. Visit the [build-win/main](https://github.com/SteamDeckHomebrew/decky-loader/actions/workflows/build-win.yml?query=branch%3Amain++) page.
0. Click on the first link.
![builder-win.jpg](/wiki/builder-win.jpg)
0. Download the `PluginLoader Win` zip file and open it.
![builder-win2.jpg](/wiki/builder-win2.jpg)

0. Run the `PluginLoader.exe` (or `PluginLoader_noconsole.exe`, which is the same but does not open a console window) file.
0. Restart steam and decky should now show up until you close `PluginLoader.exe`. If you want decky available permanently, you will need to set it to load on boot however you prefer.

### Alternative download
If downloading from github does not work for you, there is an alternative download available from [nightly.link](https://nightly.link/SteamDeckHomebrew/decky-loader/workflows/build-win/main/PluginLoader%20Win.zip).

# Using plugins
Plugins are downloaded as normal (through the plugin store), but many will not work as they are not tested on windows.