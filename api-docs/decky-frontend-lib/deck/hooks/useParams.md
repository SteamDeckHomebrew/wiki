---
title: useParams
description: 
published: true
date: 2023-02-05T01:15:38.955Z
tags: 
editor: markdown
dateCreated: 2023-02-05T01:15:37.027Z
---

# deck-hooks/useParams

## Index

### Functions

- useParams

## Functions

### useParams()

Get the current params from ReactRouter

#### Example

```ts
import { useParams } from "decky-frontend-lib";

const { appid } = useParams<{ appid: string }>()
```

#### Signature

```ts
useParams<T>(): T;
```

#### Type parameters

- `T`

#### Returns

`T`

an object with the current ReactRouter params

Defined in:  [src/deck-hooks/useParams.ts:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-hooks/useParams.ts#L13)
