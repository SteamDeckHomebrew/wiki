---
title: "utils/patcher"
editor: "markdown"
published: true
---

# utils/patcher

## Index

### Modules

- <internal>

### Interfaces

- Patch
- PatchOptions

### Variables

- callOriginal

### Functions

- afterPatch
- beforePatch
- replacePatch

## Interfaces

### Patch

#### Index

##### Properties

- handler
- hasUnpatched
- object
- original
- patchedFunction
- property
- unpatch

#### Properties

##### handler

```ts
handler: GenericPatchHandler
```

Defined in:  [src/utils/patcher.ts:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L17)

##### hasUnpatched

```ts
hasUnpatched: boolean
```

Defined in:  [src/utils/patcher.ts:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L16)

##### object

```ts
object: any
```

Defined in:  [src/utils/patcher.ts:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L14)

##### original

```ts
original: Function
```

Defined in:  [src/utils/patcher.ts:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L12)

##### patchedFunction

```ts
patchedFunction: any
```

Defined in:  [src/utils/patcher.ts:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L15)

##### property

```ts
property: string
```

Defined in:  [src/utils/patcher.ts:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L13)

##### unpatch

```ts
unpatch: Function
```

###### Type declaration

####### Signature

```ts
(): void
```

> ####### Returns
>
> `void`
>
> Defined in:  [src/utils/patcher.ts:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L19)
>

Defined in:  [src/utils/patcher.ts:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L19)

---

### PatchOptions

#### Index

##### Properties

- singleShot

#### Properties

##### singleShot

```ts
singleShot?: boolean
```

Defined in:  [src/utils/patcher.ts:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L6)

## Variables

### callOriginal

```ts
callOriginal: symbol
```

Defined in:  [src/utils/patcher.ts:3](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L3)

## Functions

### afterPatch()

#### Signature

```ts
afterPatch(
  object: any, 
  property: string, 
  handler: Function, 
  options: PatchOptions = {}): Patch
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `object` | `any` |
| `property` | `string` |
| `handler` | (`args`: `any`[], `ret`: `any`) => `any` |
| `options` | [PatchOptions](utils/patcher#patchoptions) |

#### Returns

[Patch](utils/patcher#patch)

Defined in:  [src/utils/patcher.ts:43](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L43)

---

### beforePatch()

#### Signature

```ts
beforePatch(
  object: any, 
  property: string, 
  handler: Function, 
  options: PatchOptions = {}): Patch
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `object` | `any` |
| `property` | `string` |
| `handler` | (`args`: `any`[]) => `any` |
| `options` | [PatchOptions](utils/patcher#patchoptions) |

#### Returns

[Patch](utils/patcher#patch)

Defined in:  [src/utils/patcher.ts:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L24)

---

### replacePatch()

#### Signature

```ts
replacePatch(
  object: any, 
  property: string, 
  handler: Function, 
  options: PatchOptions = {}): Patch
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `object` | `any` |
| `property` | `string` |
| `handler` | (`args`: `any`[]) => `any` |
| `options` | [PatchOptions](utils/patcher#patchoptions) |

#### Returns

[Patch](utils/patcher#patch)

Defined in:  [src/utils/patcher.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L62)
