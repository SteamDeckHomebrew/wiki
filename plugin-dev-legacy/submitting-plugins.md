---
title: Submitting plugins
description: 
published: true
date: 2022-07-03T19:07:25.072Z
tags: plugin-dev-legacy
editor: markdown
dateCreated: 2022-04-08T23:41:09.102Z
---

# Submitting plugins

The project-curated "store" for plugins is located at [plugins.deckbrew.xyz](https://plugins.deckbrew.xyz). You can submit your own plugins there by following the instructions below. Bear in mind that plugins listed on the store have to be approved by either me or WerWolv, or quite possibly a dedicated team of plugin approvers, in the future. This is done to ensure that plugins do not exhibit break-y or outright malicious behaviour, and is mostly done to protect the less tech-savvy users, who don't have the knowledge to audit plugins. You can obviously still install whatever you want, by copying folders to your plugin path.

## Preparing the repo
In your `plugin.json` file add a key called `publish` with the following fields:
```json
{
  "discord_id": "The Discord ID, under which you're submitting.",
  "description": "A quick rundown of what your plugin does.",
  "tags": ["media", "utility", "or", "anything", "really"]
}
```

Example `plugin.json` file
```json
{
    "name": "Plugin name",
    "author": "Plugin author",
    "main_view_html": "main_view.html",
    "tile_view_html": "",
    "flags": ["_hot_reload", "_root"],
    "publish": {
  			"discord_id": "The Discord ID, under which you're submitting.",
  			"description": "A quick rundown of what your plugin does.",
  			"tags": ["media", "utility", "or", "anything", "really"]
		}
}
```

After doing this, you should go to **Releases** and create the tag you're going to submit.

>  It is highly recommended you do ***NOT*** alter the release after submitting (eg by deleting and re-creating the same tag). The server will hash the contents of the release on submission, and the PluginLoader will refuse to install it if there is a mismatch.
{.is-warning}

## Submitting on Discord
Submissions are filed through the PluginBot on our Discord server ([![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://discord.gg/ZU74G2NJzk)).
The submission command is: `$submit GITHUB_USER/GITHUB_REPO RELEASE_TAG`. The first argument is refered to as the **artifact** whereas the second argument is the **version**. After this we will be notified of the submission and review it asap. Once we've verified everything is ok, your plugin will appear on [plugins.deckbrew.xyz](beta.deckbrew.xyz).