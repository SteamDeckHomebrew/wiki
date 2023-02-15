---
title: Submitting Plugins
description: Guide on how to get your Plugin onto the Store
published: true
date: 2023-02-15T21:10:32.233Z
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

In order to add your own plugin to the database, simply create a Fork of the repository, add a submodule pointing to the commit you'd like to submit to the `/plugins` folder. Once that's done, create a Pull Request with your changes to the Database Repository. This starts the review process. One of the Team Members will take a look at your Plugin and if it's deemed to be okay, the Pull Request will be approved and subsequentially merged.
> 
> Please be aware that we do not allow private repositories, "black-box" binaries, deliberately obfuscated code and any other items, processes etc that would undermine the team's ability to verify the functionality of the plugin and or any underlying software etc.
{.is-danger}

> - "Black-box" meaning binaries generated from either FOSS or proprietary source code with no link back to source code and or documentation of any changes made.
> - In terms of obfuscation, minimized JS will be handled on a case by case basis.
> 
>In some situations, binary blobs for firmware and other similair items provided by companies/organizations may be the only way to provide functionality or features. This will be handled similairly to minimized JS, on a case by case basis.

All plugins submitted must include a license, provided as either ``LICENSE`` or ``LICENSE.MD``.

> If your plugin is based on the plugin template, copy your desired license to the top of the original LICENSE file that already exists in the repo. The original license must be included as per the terms of the template's license and is required for distribution on the store.
{.is-warning}


Your plugin will undergo a review process specified in [Review Process](/en/plugin-dev/review-and-testing). Please review the steps to make sure you are in compliance already which will make the review process far quicker for you.

### Submitting an Update

To update your plugin, follow the same process as above and just make the submodule of your repository point to the new commit you want to submit.