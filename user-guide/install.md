---
title: Installation
description: How to install the Steam Deck Plugin Loader
published: true
date: 2024-03-16T18:53:36.244Z
tags: user-guide
editor: markdown
dateCreated: 2022-04-08T14:18:43.906Z
---

# Loader Installation
> This installation can be done without an admin/sudo password set.
{.is-info}

1. Prepare a mouse and keyboard if possible.
   - Keyboards and mice can be connected to the Steam Deck via USB-C or Bluetooth.
   - Many Bluetooth keyboard and mouse apps are available for iOS and Android. (KDE connect is preinstalled on the steam deck)
   - The Steam Link app is available on [Windows](https://media.steampowered.com/steamlink/windows/latest/SteamLink.zip), [macOS](https://apps.apple.com/us/app/steam-link/id1246969117), and [Linux](https://flathub.org/apps/details/com.valvesoftware.SteamLink). It works well as a remote desktop substitute.
   - If you have no other options, use the right trackpad as a mouse and press <img src="/wiki/controller-glyphs/steam.svg" height=16>+<img src="/wiki/controller-glyphs/x.svg" height=16> to open the on-screen keyboard as needed.
1. Press the <img src="/wiki/controller-glyphs/steam.svg" height=16> button and open the Power menu.
1. Select "Switch to Desktop".
1. Navigate to this Github page on a browser of your choice.
1. Download the [installer file](https://github.com/SteamDeckHomebrew/decky-installer/releases/latest/download/decky_installer.desktop). (If using firefox, it will be named `decky_installer.desktop.download`. Rename it to `decky_installer.desktop` before running it)
1. Drag the file onto your desktop and double click it to run it.
1. Either type your admin password or allow Decky to temporarily set your admin password to `Decky!` (this password will be removed after the installer finishes)
1. Choose the version of Decky Loader you want to install.
   - **Latest Release**  
     Intended for most users. This is the latest stable version of Decky Loader.  
   - **Latest Pre-Release**  
     Intended for plugin developers. Pre-releases are unlikely to be fully stable but contain the latest changes. For more information on plugin development, please consult [the wiki page](https://wiki.deckbrew.xyz/en/loader-dev/development).
1. Open the Return to Gaming Mode shortcut on your desktop.
1. Decky's plugin icon <img src="/wiki/controller-glyphs/plug.svg" height=16> will now appear in the Quick Access Menu.

- There is also a fast install for those who can use Konsole:
```
curl -L https://github.com/SteamDeckHomebrew/decky-installer/releases/latest/download/install_release.sh | sh
``` 

## Manual Installation
> This should only be done if the cli and gui installers above do not work.
{.is-info}

1. Turn on CEF debugging either by enabling the setting in steam developer settings or making a `~/.steam/steam/.cef-enable-remote-debugging` file.
1. Download the most recent PluginLoader binary from [the github releases page](https://github.com/SteamDeckHomebrew/decky-loader/releases). (or download a build from [github actions](https://github.com/SteamDeckHomebrew/decky-loader/actions/workflows/build.yml) if you want an extremely unstable version)

1. Place the binary in `~/homebrew/services` (making the folder if it does not exist) and mark it as executable `chmod +x ~/homebrew/services`.
1. Make a script to start decky up on boot. There's a [premade one for systemd in the repo](https://github.com/SteamDeckHomebrew/decky-loader/blob/main/dist/plugin_loader-release.service).



## Install Plugins
Plugins can be installed from the included plugin store <img src="/wiki/controller-glyphs/store.svg" height=16>
