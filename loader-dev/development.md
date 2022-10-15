---
title: Developing for and Contributing to PluginLoader
description: How to run the contribution install scripts and run development versions of Plugin Loader
published: true
date: 2022-10-15T17:37:22.562Z
tags: loader-dev
editor: markdown
dateCreated: 2022-06-02T20:18:49.956Z
---

# Development for PluginLoader

Here's how to install an in-development version of PluginLoader for contribution and testing your plugins with in-development versions of PluginLoader

## Development Enviroment

Currently development tools assume you're using a Linux based enviroment.
If you are using Windows we advise you use a Arch WSL.
Make sure to update to the latest packages via ``sudo pacman -Syu``.
The latest Ubuntu WSL on Windows being extremely out of date (*sigh*).

--- 

## Download Options

**These scripts are ran on your local development enviroment and not on the Deck!**

Contributors can install development versions a few ways.

1. From scripts found in the ``contrib`` directory of the repository.
   - These can be ran locally or by using a remote version of the scripts from the repository.
2. From VSCode/Code/Codium Tasks found in ``.vscode``.
   - These require the user to be working with a cloned repository.
   - e.g ``git clone https://github.com/SteamDeckHomebrew/decky-loader``

----

### Build Tasks

WIP, come back later!

---

### Contrib Scripts

#### Location

Both scripts can be invoked remotely or locally like so:

Locally:
  - ``bash /path/to/repo/contrib/deck.sh``
  - ``bash /path/to/repo/contrib/nodeck.sh``

Github:
  - ``bash <(curl -s https://github.com/SteamDeckHomebrew/decky-loader/raw/main/contrib/deck.sh)``
  - ``bash <(curl -s https://github.com/SteamDeckHomebrew/decky-loader/raw/main/contrib/nodeck.sh)``
(If any of these URLs are out of date please alert a maintainer!)

#### Examples

You will find examples for different install scenarios below.

You can also add parameters to skip prompting (We :heart: developers).

Note: ``nodeck.sh`` has similair but differently ordered arguments compared to ``deck.sh``.

##### Deck Install

- ``bash /path/to/repo/contrib/deck.sh clonefolder installfolder ip.address.goes.here port password "/path/to/.ssh/key_name" loaderbranch librarybranch templatebranch latest``
- ``bash <(curl -s https://github.com/SteamDeckHomebrew/decky-loader/raw/main/contrib/deck.sh) clonefolder installfolder ip.address.goes.here port password "/path/to/.ssh/key_name" loaderbranch librarybranch templatebranch latest``

###### Arguments

Arguments in order for `deck.sh`.

1. `clonefolder` where the git repositories will be cloned to (on your PC).
   - ex: `git`, which would become ``/home/username/git``
2. `installfolder` where the git repositories will be cloned to (on your Deck).
   - ex: `loaderdev`, which would become ``/home/username/loaderdev``
3. `ip.address.goes.here` the ip address of your Steam Deck (hostnames not supported).
   - ex: `192.168.0.10`.
4. `port` the open ssh port of your Steam Deck.
   - ex: `22` (highly recommend you do not use the standard port `22`)
5. `password` the password for your Steam Deck's `deck` account.
   - ex: `wordpass` (don't use this as a password... :disappointed:)
6. `"/path/to/.ssh/key_name"` path to an ssh key shared between your PC and Deck.
   - ex: `/home/username/.ssh/id_rsa` 
   - If you don't know how to setup an ssh key on Linux then you can skip this parameter but it is highly suggested you use one for easy of use/development etc.
7. `loaderbranch` the branch you want to clone for PluginLoader.
    - ex: `react-frontend-plugins` or `aa/react-plugin-store`
8. `librarybranch` the branch you want to clone for decky-frontend-library.
    - ex: `main`
9. `templatebranch` the branch you want to clone for decky-plugin-template.
    - ex: `main`
10. `latest` true/false to pull latest commits to repositories.
     - ex: `true` or `false`

##### No Deck Install

- ``bash /path/to/repo/contrib/nodeck.sh clonefolder``
- ``bash <(curl -s https://github.com/SteamDeckHomebrew/PluginLoader/raw/main/contrib/nodeck.sh) clonefolder loaderbranch librarybranch templatebranch latest``

###### Arguments

Arguments in order for `nodeck.sh`.

1. `clonefolder` where the git repositories will be cloned to (on your PC).
   - ex: `git`, which would become ``/home/username/git``
2. `loaderbranch` the branch you want to clone for PluginLoader.
    - ex: `main`
3. `librarybranch` the branch you want to clone for decky-frontend-library.
    - ex: `main`
4. `templatebranch` the branch you want to clone for decky-plugin-template.
    - ex: `main`
5. `latest` true/false to pull latest commits to repositories.
     - ex: `true` or `false`)

----