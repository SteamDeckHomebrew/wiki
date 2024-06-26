---
title: Migrating to the new decky API
description: Steps for migrating an existing plugin to the new websocket-based system.
published: true
date: 2024-06-27T00:09:26.295Z
tags: 
editor: markdown
dateCreated: 2024-06-14T00:00:11.855Z
---

> Migration is totally optional, and backwards compatibility is intended to be kept for a long time to come. It is recommended, as the new api is easier to use and adds new features, but there is no major rush to get this done.
{.is-info}

# Migration
You can see a full migration example [here](https://github.com/SteamDeckHomebrew/decky-plugin-template/compare/main...aa/websockets) (although this also makes some actual functional changes as well). REMEMBER TO CHANGE THIS TO POINT TO COMMITS LATER (:

The python library `decky_plugin` has been renamed to `decky`, but all pre-existing methods are unchanged there and the old `decky_plugin` name is still provided for convenience, so no changes should be required on the python end.

In the frontend, `decky-frontend-lib` has been split into two libraries, `@decky/api` and `@decky/ui`. DFL's *ServerAPI* has been completely removed, and replaced by new functions in `@decky/api`.

## @decky/ui

`@decky/ui` contains all the react components and similar from DFL, largely unchanged. Aside from replacing all *ServerAPI* usage and a couple other functions, a simple rename should work.

## @decky/api

`@decky/api` contains all the other functions that aren't just react elements. 

For calling the backend, *ServerAPI.callPluginMethod* has been replaced by *call* which has a very similar interface, but it returns its result directly, instead of through an intermediary interface. Any backend errors will be raised and bubble up as JS errors.

```typescript
// before
import { ServerAPI } from "decky-frontend-lib";
interface AddMethodArgs { a: number; b: number; }
const res = await serverAPI.callPluginMethod<AddMethodArgs, number>("add", {a: 1, b: 2});
if (res.success) {
	console.log(res.result);
}

// after
import { call } from "@decky/api";
const res = await call<[a: number, b: number], number>("add", 1, 2);
console.log(res);
``` 

Various methods like *toaster*, *routerHook*, *openFilePicker*, *executeInTab*, *injectCssIntoTab*, *removeCssFromTab*, *fetchNoCors*, *getExternalResourceURL* and *definePlugin* have been moved to `@decky/api`. They are unchanged so you will just need to change where you import them from.

> You can read more information about the new api [here](/plugin-dev/backend-frontend-communication).
{.is-info}

## Important file changes

### plugin.json
You need to add `"api_version": 1`

### package.json / pnpm-lock.yaml
As mentioned above, you need to replace `decky-frontend-lib` with `@decky/api` and `@decky/ui`. You also need to add `"type": "module"`.

### decky_plugin.pyi → decky.pyi
The file has been renamed, and has extra fields. Copy it in from the template.

### rollup.config.js
The file has changed, and the changes are needed for the plugin to build properly. Copy it in from the template.