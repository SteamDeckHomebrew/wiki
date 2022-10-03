---
title: Installation
description: How to install the Steam Deck Plugin Loader
published: true
date: 2022-10-03T18:42:56.513Z
tags: user-guide
editor: markdown
dateCreated: 2022-04-08T14:18:43.906Z
---

# Loader Installation
1. Go into the Steam Deck Settings
2. Under System -> System Settings toggle `Enable Developer Mode`
3. Scroll the sidebar all the way down and click on `Developer`
4. Under Miscellaneous, enable `CEF Remote Debugging`
5. Click on the <kbd>STEAM</kbd> button and select `Power` -> `Switch to Desktop`
6. Open a terminal and paste the following command into it: 
- For users (**RECOMMENDED** release version):
```console
curl -L https://github.com/SteamDeckHomebrew/decky-loader/raw/main/dist/install_release.sh | sh
```

- For developers and testers (pre-release version):
  - Please note, this script polls the Github API, and if done too often you will be rate-limited.

```console
curl -L https://github.com/SteamDeckHomebrew/decky-loader/raw/main/dist/install_prerelease.sh | sh
```
   
8. Done! Reboot back into Gaming mode and enjoy your plugins!

## Install Plugins
Plugins can be installed from **[plugins.deckbrew.xyz](https://plugins.deckbrew.xyz)**. For more information, read about the [plugin browser](https://deckbrew.xyz/en/user-guide/plugin-browser).