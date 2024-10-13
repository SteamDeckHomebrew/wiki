---
title: Review and Testing Process
description: More information on how we review your plugin before it can make it to users.
published: true
date: 2024-10-13T18:23:39.007Z
tags: plugin-dev, testing
editor: markdown
dateCreated: 2022-11-13T21:56:22.344Z
---

# Review Process

Upon initial PR to the [Decky Plugin Database](https://github.com/SteamDeckHomebrew/decky-plugin-database), we go through these steps to review your plugin.
Please go through them yourself as well to make sure that we don't have to flag any issues and so your plugin can make it to the testing server quickly.


> 1. Verify that submodule added in .gitmodules and actual folder containing submodule in plugins/plugin-name exists
> 2. Check package.json for usage of remote-binary tag. If used, follow the link to determine legitimacy third-party binary that's being used. Also check NPM depedencies and package name conforms to the npm standard.
> 3. Ensure your pnpm-lock.yaml file is on `lockfileVersion: 9.0` to meet CI requirements. [pnpm docs](https://pnpm.io/)
> 4. Go through a plugin's code, a cursory glance for remote code and usage of external resources. Note any of these for step 4 but continue through the code looking for general malicious behavior or potential un-intended behavior that could harm users.
> 5. From your notes in #3 on remote code or just the presence of a URL, follow that URL or analyze it if you suspect it to be a problem and then proceed if malicious code, references to potentially malicious remote code etc are not found.
> 6. Look for any files like configurations etc in their repo that are needed for the addon but are not found in the default folder. If you find items like this, in your review; include that they need to move any needed configuration files/folders containing such files into the defaults folder.
> 7. Check to see if they're addon still has the "backend", "assets" or "defaults" directories. If these directories exist and are not used by the addon, they need to be removed. In the case of the assets folder, unless the developer is using the icon.png file, they should be requested to delete it in your review. If the defaults directory has a simple defaults.txt file in it, it needs to be deleted. If this is not caught in first review the CI will alert you that it still exists when bundling the addon. backend folder is to be deleted no matter what if not utilized.
> 8. Submit your review with the feedback you have determined based on the above steps. If you noticed any intentionally malicious elements, tag us in the private channel and that user will be banned from submissions from then on.

Once your plugin makes it to the testing store, testers can provide comments, approvals or request for changes on your plugin and let you know of any issues they encounter.

There are two variants for testing required for plugins depending upon the use of custom backends and or pre-built binaries both of which can have depedencies that cannot be statically linked.

There's a bit more you need to know.

> ---
> ### A
>Plugins utilizing a custom backend or pre-built binaries that have depdencies which cannot be statically linked (an example of such a depedency is glibc) must be tested and encounter no functionality breaking issues on SteamOS preview as the minimum. Testing can and should be done on other branches but only preview is required.
{.is-success}

> ---
> ### B
> Plugins utilizing a python backend and the react frontend (using Decky Frontend Library) that do not utilize a custom backend or pre-built binaries which could have depedency issues must be tested and encounter no functionality breaking issues on either the latest Stable or Beta branches.
{.is-success}

If a plugin/plugin update is approved to go onto the testing store and the plugin developer(s) demonstrates no forward momentum towards completing testing, then steps will be taken. Specifically, if we do not see any movement towards making sure the plugin/plugin update is being tested and a testing review is/will be submitted we will:

> ---
> ### 1st
> Contact the plugin developer and offer to help find testers for them.
> If we receive no response or a response that the team understands as moving forward with testing, we reserve the right to close the PR and pull the plugin/plugin update after 2 weeks.
{.is-warning}

> ---
> ### 2nd
> Contact the plugin developer again and more directly determine a firm timeline on testing.
> This should only occur around 3 weeks after submission, at this point if we have not exercised our right to close the PR after 2 weeks, you can expect the PR will be closed and the plugin/plugin update will be pulled from the testing store.
{.is-warning}

Any cosmetic issues that don't prevent proper usage will be asked to be fixed. When a plugin has comments from unoffical/offical testers for each branch, then a member of the core Decky Loader team will approve the plugin to be merged into the Plugin Database, and the CI will upload it to the main store.

**Congrats, you now have a submitted plugin!**

