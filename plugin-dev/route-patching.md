---
title: Route Patching
description: Using Route Patching to insert new components into the deck UI or edit existing.
published: true
date: 2022-10-23T15:02:02.106Z
tags: route, patch, patching, component, react
editor: markdown
dateCreated: 2022-09-11T21:45:14.663Z
---

# Route Patching
We can use route patching to allow us to add new components to the Deck UI or edit existing ones.

To achieve this, [decky-frontend-lib](https://github.com/SteamDeckHomebrew/decky-frontend-lib) has some helper functions we can use. (`afterPatch`, `wrapReactType`, `wrapReactClass`)

This guide assumes you've followed the [Getting Started guide](/en/plugin-dev/getting-started) and have your basic plugin template setup.

## TLDR
Our workflow will be:
- Adding a new patch via `serverAPI` with `serverAPI.routerHook.addPatch` on our chosen route
- Make our way down the react tree with using `afterPatch` where neccessary to render child components.
- Use `wrapReactType` and `wrapReactClass` to make clones of the component before using `afterPatch`

For an example check out the ProtonDB Badges plugin on [GitHub](https://github.com/OMGDuke/protondb-decky)

## Step by Step guide

### Finding the route we want to patch

To start we'll need to turn on Remote CEF Debugging in our Decky Settings `Allow Remote CEF Debugging` and then opening `chrome://inspect` on your development machine.

Here you should see your remote targets. Find the one that has your decks IP. It should have various tabs to inspect such as `Toast`,`QuickAccess`,`MainMenu`,`SP`.

Navigate to the page you want to patch on your Steam Deck and then inspect the `SP` Tab in `chrome://inspect`

In the address bar of the chrome inspect window you should see something that looks like `https://steamloopback.host/routes/YOUR_ROUTE` with `YOUR_ROUTE` referring to the route you're currently on. The part we want is the address after `https://steamloopback.host/routes`

So for the homepage we would use `/library/home`, for a game page we would use `/library/app/:appId`

### Patching the route

Now that we have our route we'll jump into patching.

Within the `definePlugin` function we have access to `serverAPI`. So let's add a new patch to the app page with
```
const myPatch = serverAPI.routerHook.addPatch('/library/app/:appId',
  (props: { path: string; children: ReactElement }) => {
  	return props
  })
)
```
> Make sure you assign your patch to a variable so we can remove it in our `onDismount`
> `serverAPI.routerHook.removePatch('/library/app/:appid', myPatch)`
{.is-warning}

Now our App page is being patched (although nothing is being changed)

### Finding where we want to make the change

Within our `addPatch` function we now have access to the children of our route. This will contain the react tree for the page.

> React Devtools is a great way of viewing the React tree to find the component you want.
> This method is mostly trial and error!
{.is-info}

Using react devtools, (or console logging `props.children`) start searching for the component you want to add to or edit. Sometimes you'll have to drill down `props.children.props.children` a few times to hit a class or function that you'll need to render to continue.

If you hit a dead end you can run an `afterPatch`. Before running this you may need to clone the component you want to patch with `wrapReactType` for a memoized function and `wrapReactClass` for a class. If `type` is already a normal function, you do not need to wrap it.

```
wrapReactType(THE_COMPONENT_YOU_WANT_TO_RENDER)
```

Then

```
afterPatch(THE_COMPONENT_YOU_WANT_TO_RENDER, 'THE_FUNCTION_YOU_WANT_TO_CALL',
	(_: Record<string, unknown>[], ret: ReactElement) => {
  	return ret
  })
)
```
Where `ret` is the returned component of the function call. Normally your `THE_COMPONENT_YOU_WANT_TO_RENDER` will be something like `props.children.type` and your `'THE_FUNCTION_YOU_WANT_TO_CALL'` may be `'type'` or `'renderFunc'`. This will vary depending on route and where you're going within the react tree.

### Making your changes

Once you've found where you want to make your change you'll need to insert your react component.

To do this you can replace the children of your targetted component. (You can splice it in if `children` is an array).

```
ret.props.children?.[1]?.props.children.props.children.splice(
	1,
	0,
	<YourComponent />
)
```
> Make sure you remember to return `ret` in your `afterPatch`
{.is-warning}

Finally make sure you remove the patch in your `onDismount`
```
serverAPI.routerHook.removePatch('/library/app/:appid', myPatch)
```

An example of patching the App page can be found [here](https://github.com/OMGDuke/protondb-decky/blob/main/src/lib/patchLibraryApp.tsx)
