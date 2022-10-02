---
title: Submitting Plugins
description: Guide on how to get your Plugin onto the Store
published: true
date: 2022-07-18T23:11:48.112Z
tags: plugin-dev, store
editor: markdown
dateCreated: 2022-07-03T19:53:34.932Z
---

# Submitting Plugins

The project-curated "store" for plugins is located at https://beta.deckbrew.xyz. 
You can submit your own plugins there by following the instructions below. Keep in mind that plugins listed on the store must be approved by one of the Loader Team Members. This is done to ensure that plugins do not break the Deck or the Loader or are outright malicious, and is mostly done to protect the less tech-savvy users, who don't have the knowledge to audit plugins. You can obviously still install whatever you want, by copying folders to your plugin path or by using the `Manual plugin install` functionality in the [Loader Settings](/en/user-guide/settings).
Manual install is completely fine, but not recommended for security reasons.

## Submission 

First, head over to the [Decky Plugin Database Repository](https://github.com/SteamDeckHomebrew/decky-plugin-database). All submitted plugins can be found in the `plugins` subfolder of the repo.

In order to add your own plugin to the database, simply create a Fork of the repository, add a submodule pointing to the commit you'd like to submit to the `/plugins` folder. Once that's done, create a Pull Request with your changes to the Database Repository. This starts the review process. One of the Team Members will take a look at your Plugin and if it's deemed to be okay, the Pull Request will be approved and subsequentially merged

### Submitting an Update

To update your plugin, follow the same process as above and just make the submodule of your repository point to the new commit you want to submit.