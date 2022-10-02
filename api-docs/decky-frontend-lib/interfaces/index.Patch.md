[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [index](../modules/index.md) / Patch

# Interface: Patch

[index](../modules/index.md).Patch

## Table of contents

### Properties

- [handler](index.Patch.md#handler)
- [hasUnpatched](index.Patch.md#hasunpatched)
- [object](index.Patch.md#object)
- [original](index.Patch.md#original)
- [patchedFunction](index.Patch.md#patchedfunction)
- [property](index.Patch.md#property)
- [unpatch](index.Patch.md#unpatch)

## Properties

### handler

• **handler**: [`GenericPatchHandler`](../modules/index._internal_.md#genericpatchhandler)

#### Defined in

[src/utils/patcher.ts:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/utils/patcher.ts#L17)

___

### hasUnpatched

• **hasUnpatched**: `boolean`

#### Defined in

[src/utils/patcher.ts:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/utils/patcher.ts#L16)

___

### object

• **object**: `any`

#### Defined in

[src/utils/patcher.ts:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/utils/patcher.ts#L14)

___

### original

• **original**: [`Function`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function )

#### Defined in

[src/utils/patcher.ts:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/utils/patcher.ts#L12)

___

### patchedFunction

• **patchedFunction**: `any`

#### Defined in

[src/utils/patcher.ts:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/utils/patcher.ts#L15)

___

### property

• **property**: `string`

#### Defined in

[src/utils/patcher.ts:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/utils/patcher.ts#L13)

___

### unpatch

• **unpatch**: () => `void`

#### Type declaration

▸ (): `void`

##### Returns

`void`

#### Defined in

[src/utils/patcher.ts:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/utils/patcher.ts#L19)
