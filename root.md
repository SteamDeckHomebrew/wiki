---
title: Root Access
description: What root access means for plugins
published: true
date: 2023-01-17T04:56:52.092Z
tags: 
editor: markdown
dateCreated: 2023-01-17T00:40:18.024Z
---

# Summary
Root access is an important part of some Decky plugins. They may have a warning like the one below.

> *This plugin has full access to your Steam Deck.* deckbrew.xyz/root

This page explains what root access is and why certain plugins need it.

# Definition

> Root is the highest permission elevation on a computer system. Root permission is typically reserved for those who are authorized to make operating system level changes. A given system’s root has default access to all directories, makes any kind of command, and can make permanent alterations to software. — [HYPR](https://www.hypr.com/security-encyclopedia/root)

# Usage

Many Decky plugins modify your system in ways that cannot be done using typical user permission. For example, PowerTools by NGnius would not be able to tweak the settings of Steam Deck components without using root permission.

# Security

The Decky Loader team have reviewed all plugins that use root permission on the Decky Plugin Store. Using these plugins should be safe, but you should always be careful installing software from the internet. You can view the source code of all plugins by visiting the [Decky Plugin Database](https://github.com/SteamDeckHomebrew/decky-plugin-database).

You are responsible for the security of your Steam Deck. The Decky Loader Team offers no guarantees regarding the safety of Decky plugins.