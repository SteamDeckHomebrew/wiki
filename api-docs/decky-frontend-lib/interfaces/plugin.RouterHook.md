[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [plugin](../modules/plugin.md) / RouterHook

# Interface: RouterHook

[plugin](../modules/plugin.md).RouterHook

## Table of contents

### Methods

- [addPatch](plugin.RouterHook.md#addpatch)
- [addRoute](plugin.RouterHook.md#addroute)
- [removePatch](plugin.RouterHook.md#removepatch)
- [removeRoute](plugin.RouterHook.md#removeroute)

## Methods

### addPatch

▸ **addPatch**(`path`, `patch`): [`RoutePatch`](../modules/plugin._internal_.md#routepatch)

#### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |
| `patch` | [`RoutePatch`](../modules/plugin._internal_.md#routepatch) |

#### Returns

[`RoutePatch`](../modules/plugin._internal_.md#routepatch)

#### Defined in

[src/plugin.tsx:27](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/plugin.tsx#L27)

___

### addRoute

▸ **addRoute**(`path`, `component`, `props?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |
| `component` | `ComponentType`<{}\> |
| `props?` | `Omit`<`RouteProps`<`string`, {}\>, ``"children"`` \| ``"path"``\> |

#### Returns

`void`

#### Defined in

[src/plugin.tsx:26](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/plugin.tsx#L26)

___

### removePatch

▸ **removePatch**(`path`, `patch`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |
| `patch` | [`RoutePatch`](../modules/plugin._internal_.md#routepatch) |

#### Returns

`void`

#### Defined in

[src/plugin.tsx:28](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/plugin.tsx#L28)

___

### removeRoute

▸ **removeRoute**(`path`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |

#### Returns

`void`

#### Defined in

[src/plugin.tsx:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/plugin.tsx#L29)
