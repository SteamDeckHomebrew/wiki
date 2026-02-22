---
title: Plugin Safety
description: A brief guide on recommended safety steps when installing plugins
published: true
date: 2026-02-22T17:03:28.342Z
tags: 
editor: markdown
dateCreated: 2026-02-19T19:59:37.020Z
---

# Overview
This page describes why you should be cautious when installing plugins from outside of the store, common reasons we deny plugins, commonly installed plugins which have been denied, and how to install plugins safely.

# Why to use the plugin store
Steam Deck Homebrew (the creators of Decky Loader) have a detailed code review and testing process to ensure the safety of plugins installed on your Steam Deck. This includes, but is not limited to:

- Reviewing the code of plugins
- Checksum verification for executables downloaded by plugins, ensuring remotely-hosted binaries are as-tested
- Quality assurance testing from other plugin developers and Decky users

Plugins from outside of the plugin store could contain viruses, code which downloads software that contains viruses, bugs, or other issues. We highly recommend only installing plugins from the main plugin store which have been reviewed and tested. If you want the latest plugin updates which may have some bugs, you can also use the testing plugin store.

# Denied plugins
Plugins are denied for a variety of reasons, including:
- Not using the checksum verification system to prevent viruses
- Including a self-update system, allowing the developer to install arbitrary code without review by our team
- Hijacking controller inputs (e.g. using an existing Steam button shortcut to activate the plugin)
- Code which could easily delete or corrupt data, related or unrelated to the plugin
- Excessive use of generative AI to develop the plugin, typically leading to bugs and untested code
- Unwillingness to work with code reviewers or the wider Steam Deck Homebrew community

Below are some commonly installed plugins which have been previously denied or removed from the Decky Plugin Store.

> The following summaries are written by individual members of the team with the intent of providing an impartial. They may not represent the views of the entire Steam Deck Homebrew team.
{.is-info}

## NonSteamLaunchers

[NonSteamLaunchers](https://github.com/moraroy/NonSteamLaunchersDecky) (NSL) uses a single Wine prefix (virtualized Windows environment) for all launchers or for all games associated with a launcher unlike Valve's Proton, which uses a separate prefix for each game. This allows launchers and games to interact with eachother's files, meaning ***one mistake could require you to reinstall your entire library and any software installed (e.g. a virus) could easily interact with other launchers***. This also has its benefits, such as GOG being able to launch games from other launchers. Its creator is aware of the issues of using a single prefix and does not wish to change their approach ([see their GitHub](https://github.com/moraroy/NonSteamLaunchers-On-Steam-Deck/issues/393)). This is the primary reason NSL has not been re-allowed on the plugin store, but the original removal reason and surrounding context are provided below for context.

NSL was originally removed from the plugin store due to a report of harassment by its creator in Steam Deck-related communities ([see SteamDeckHQ](https://steamdeckhq.com/news/nonsteamlaunchers-plugin-removed/)). Its creator has also continued to discuss NSL in communities where they've respectfully been asked to not endorse using it, such as the Bazzite subreddit ([see a statement from a Bazzite developer](https://www.reddit.com/r/SteamDeck/comments/1qofvgo/comment/o24rtzb/)). This has led to them being banned from many Steam Deck-adjacent communities and complaining about said bans, including the Steam Deck Homebrew Discord server, r/Bazzite, r/JunkStore, the Steam Deck Discord server, and r/SteamDeck ([see r/SteamDeckBro](https://www.reddit.com/r/SteamDeckBro/)).

Outside of using Steam directly, some unaffiliated alternatives include:
- [Faugus Launcher](https://github.com/Faugus/faugus-launcher) (software)
- [Heroic Games Launcher](https://heroicgameslauncher.com/) (software)
- [Junk Store](https://github.com/ebenbruyns/junkstore) (Decky plugin)
- [Lutris](https://lutris.net/) (software)

# Installing non-plugin store plugins
> As previously stated, installing from a ZIP file or URL is a developer setting for a reason. We do not recommend installing a plugin using these methods for any other reason, including plugin testing (use the testing plugin store).
{.is-warning}

If you are absolutely sure you want to install a plugin from outside of the plugin store, we recommend taking the following steps first. We will not provide further support regarding plugins installed from outside of the Decky Plugin Store.
- Ensure the plugin is open-source and accessible via GitHub, GitLab, or another Git host
- Download the plugin from somewhere reputable, like GitHub releases and not a website specific to the plugin
- If you have lag or other issues after installing the plugin, uninstall it immediately