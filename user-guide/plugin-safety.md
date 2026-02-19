---
title: Plugin Safety
description: A brief guide on recommended safety steps when installing plugins
published: true
date: 2026-02-19T19:59:37.020Z
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

## NonSteamLaunchers
> The following statement is a work-in-progress and may not represent the views of the entire Steam Deck Homebrew team.
{.is-info}

[NonSteamLaunchers](https://github.com/moraroy/NonSteamLaunchersDecky) (NSL) uses a single Wine prefix (virtualized Windows environment) for all launchers or for all games associated with a launcher unlike Valve's Proton, which uses a separate prefix for each game. This allows launchers and games to interact with eachother's files, meaning one mistake could require you to reinstall your entire library and any software installed (e.g. a virus) could easily interact with other launchers. This also has its benefits, such as GOG being able to launch games from other launchers, but we believe that the cons outweigh the pros. Its creator is aware of the issues of using a single prefix and does not wish to change their approach ([see their GitHub for more info](https://github.com/moraroy/NonSteamLaunchers-On-Steam-Deck/issues/393#issuecomment-2292534509)).

NSL was originally removed from the plugin store due to a report of harassment by its creator in Steam Deck-related communities ([see SteamDeckHQ for more info](https://steamdeckhq.com/news/nonsteamlaunchers-plugin-removed/)). Its creator has also continued to discuss NSL in communities where they've respectfully been asked to not endorse using it, such as the Bazzite subreddit. These are no longer factors in its removal.

Some unaffiliated alternatives include:
- [Heroic Games Launcher](https://heroicgameslauncher.com/) (Linux software)
- [Junk Store](https://github.com/ebenbruyns/junkstore) (Decky plugin)