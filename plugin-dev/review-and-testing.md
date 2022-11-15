---
title: Review and Testing Process
description: More information on how we review your plugin before it can make it to users.
published: false
date: 2022-11-15T23:20:38.147Z
tags: plugin-dev, testing
editor: markdown
dateCreated: 2022-11-13T21:56:22.344Z
---

# Review Process

Upon initial PR to the Decky Plugin Database, we go through these steps to review your plugin.
Please go through them yourself as well to make sure that we don't have to flag any issues and so your plugin can make it to the testing server quickly.


> 1. Verify that submodule added in .gitmodules and actual folder containing submodule in plugins/plugin-name exists
> 2. Check package.json for usage of remote-binary tag. If used, follow the link to determine legitimacy third-party binary that's being used. Also check NPM depedencies and package name conforms to the npm standard.
> 3. Go through a plugin's code, a cursory glance for remote code and usage of external resources. Note any of these for step 4 but continue through the code looking for general malicious behavior or potential un-intended behavior that could harm users.
> 4. From your notes in #3 on remote code or just the presence of a URL, follow that URL or analyze it if you suspect it to be a problem and then proceed if malicious code, references to potentially malicious remote code etc are not found.
> 5. Look for any files like configurations etc in their repo that are needed for the addon but are not found in the default folder. If you find items like this, in your review; include that they need to move any needed configuration files/folders containing such files into the defaults folder.
> 6. Check to see if they're addon still has the "backend", "assets" or "defaults" directories. If these directories exist and are not used by the addon, they need to be removed. In the case of the assets folder, unless the developer is using the icon.png file, they should be requested to delete it in your review. If the defaults directory has a simple defaults.txt file in it, it needs to be deleted. If this is not caught in first review the CI will alert you that it still exists when bundling the addon. backend folder is to be deleted no matter what if not utilized.
> 7. Submit your review with the feedback you have determined based on the above steps. If you noticed any intentionally malicious elements, tag us in the private channel and that user will be banned from submissions from then on.

Once your plugin makes it to the testing store, unoffical testers can provide comments on your plugin and let you know of any issues they encounter. Offical testers (those in the decky-testers group on github) can provide feedback via comments or reviews requesting changes or approving. Plugins must be tested and encounter no functionality breaking issues on all 3 branches. Any cosmetic issues that don't prevent proper usage will be asked to be fixed. When a plugin has comments from unoffical/offical testers for each branch, then a member of the core Decky Loader team will approve the plugin to be merged into the Plugin Database, and the CI will upload it to the main store.

Congrats, you now have a submitted and uploaded plugin!