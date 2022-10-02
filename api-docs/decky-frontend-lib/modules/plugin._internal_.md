[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [plugin](plugin.md) / <internal\>

# Module: <internal\>

## Table of contents

### Interfaces

- [ServerResponseError](../interfaces/plugin._internal_.ServerResponseError.md)
- [ServerResponseSuccess](../interfaces/plugin._internal_.ServerResponseSuccess.md)

### Type Aliases

- [DefinePluginFn](plugin._internal_.md#definepluginfn)
- [RoutePatch](plugin._internal_.md#routepatch)

## Type Aliases

### DefinePluginFn

Ƭ **DefinePluginFn**: (`serverAPI`: [`ServerAPI`](../interfaces/plugin.ServerAPI.md)) => [`Plugin`](../interfaces/plugin.Plugin.md)

#### Type declaration

▸ (`serverAPI`): [`Plugin`](../interfaces/plugin.Plugin.md)

##### Parameters

| Name | Type |
| :------ | :------ |
| `serverAPI` | [`ServerAPI`](../interfaces/plugin.ServerAPI.md) |

##### Returns

[`Plugin`](../interfaces/plugin.Plugin.md)

#### Defined in

[src/plugin.tsx:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/plugin.tsx#L65)

___

### RoutePatch

Ƭ **RoutePatch**: (`route`: `RouteProps`) => `RouteProps`

#### Type declaration

▸ (`route`): `RouteProps`

##### Parameters

| Name | Type |
| :------ | :------ |
| `route` | `RouteProps` |

##### Returns

`RouteProps`

#### Defined in

[src/plugin.tsx:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/plugin.tsx#L23)
