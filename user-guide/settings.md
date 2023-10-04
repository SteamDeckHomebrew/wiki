---
title: Settings Page
description: 
published: true
date: 2023-10-04T20:15:58.820Z
tags: 
editor: markdown
dateCreated: 2022-07-18T19:54:07.105Z
---

# Settings Page
When using Decky Loader you will be presented with a new gear icon in the top left.
This will take you to the "settings" for decky-loader which has a few sections.

## General
This menu provides you with the ability to update to the latest version of the loader, and in upcoming versions you will be able to choose between:
 - release builds (stable builds with extensive testing, for end-users)
 - pre-release builds (handmade pre-releases, curated usually for plugin developers)
 
## Plugins

This section is entirely dedicated to managing your plugins, primarily uninstalling plugins. If a plugin is installed but giving you trouble, this is where you go in the UI to cleanly remove it from within the UI.

## General cont.

### Manual Plugin Install
By entering a URL link to a .zip file, a user can install a plugin not from the store.
This currently works as a URL only because a file-picking dialog is not properly exposed in SteamOS for us to allow users to find a zip file on their local filesystem.

#### Word of Warning
All plugins we approve to the store have a specific file structure that looks similar to this when downloaded.
When downloading a plugin with files that don't match this [layout](/en/plugin-dev/getting-started#getting-started) means you are installing:

1. An improperly packaged plugin.
2. A link to a github repo's raw source as a zip.
3. A potentially malicious plugin.

In the case of the 1 and 2, these are largely harmless and won't hurt anything but are not supported as installation methods and might not install properly, forcing you to have to manually remove the files via ``sudo rm -r SomeFolderName/ somefilename.txt``.
This can be done in Desktop Mode but ssh access to the deck makes it far easier.

In the case of malicious plugins, these could do any number of things and simply by requesting root acess by having that access specified in plugin.json, have access to your entire system with no limitations.



