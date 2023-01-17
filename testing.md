---
title: Testing
description: Instructions for testing new plugins
published: true
date: 2023-01-17T16:56:08.923Z
tags: 
editor: markdown
dateCreated: 2023-01-17T15:59:00.047Z
---

# Summary

This page details how to test new Decky Loader builds and Decky plugins. Make sure you have joined our Discord server for easy communication with other testers. https://discord.gg/ZU74G2NJzk

# Decky Loader

New Decky Loader updates require review from a Decky Loader developer and an unaffiliated tester. This allows us to easily check both the code and functionality respectively. To get started testing new features, here's a basic walkthrough.

## Installing

1. On your Steam Deck, enter Desktop Mode.
1. Open Konsole and run the command `sudo systemctl stop plugin_loader` to disable Decky Loader until restart.
1. Go to /home/deck/homebrew/services and delete the PluginLoader file to another name (ex. PluginLoader_old).
1. Open a browser of your choice.
1. Go to the Pull Requests tab of the Decky Loader. https://github.com/SteamDeckHomebrew/decky-loader/pulls
1. Click on an active Pull Request. Look for Pull Requests with this symbol. <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" fill="currentColor" style="color: #3fb950"><path fill-rule="evenodd" d="M7.177 3.073L9.573.677A.25.25 0 0110 .854v4.792a.25.25 0 01-.427.177L7.177 3.427a.25.25 0 010-.354zM3.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122v5.256a2.251 2.251 0 11-1.5 0V5.372A2.25 2.25 0 011.5 3.25zM11 2.5h-1V4h1a1 1 0 011 1v5.628a2.251 2.251 0 101.5 0V5A2.5 2.5 0 0011 2.5zm1 10.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0zM3.75 12a.75.75 0 100 1.5.75.75 0 000-1.5z"></path></svg>
1. Click the Checks tab just below the title.
1. In the Checks tab, look at the top-right corner for an Artifacts button. Click it and click the PluginLoader link.
1. Extract the ZIP file so the new PluginLoader file is in /home/deck/homebrew/services.
1. Open Konsole and run the command `chmod 777 ~/homebrew/services/PluginLoader` to make sure your Decky Loader runs correctly.
1. Click the Deck icon at the bottom-left of your screen and restart. This should put you back in Gaming Mode.

## Reviewing

1. Make sure to thoroughly test all new features implemented in the PR. For example, if the store is updated with a new search functionality, try all sorts of search terms to make sure it works.
1. Once you are done with your review, open the pull request on GitHub.
1. Click the Files changed tab just below the title.
1. In the Files changed tab, look at the top-right corner for a Review changes dropdown. Click it and write your review. **Make sure to include your SteamOS branch (ex. Main, Beta)!**
1. Submit your review. Feel free to change your SteamOS branch and make another review if you would like to do so.

# Decky Plugins