[decky-frontend-lib](../README.md) / [Modules](../modules.md) / plugin

# Module: plugin

## Table of contents

### Modules

- [&lt;internal\&gt;](plugin._internal_.md)

### Interfaces

- [FilePickerRes](../interfaces/plugin.FilePickerRes.md)
- [Plugin](../interfaces/plugin.Plugin.md)
- [RouterHook](../interfaces/plugin.RouterHook.md)
- [ServerAPI](../interfaces/plugin.ServerAPI.md)
- [ToastData](../interfaces/plugin.ToastData.md)
- [Toaster](../interfaces/plugin.Toaster.md)

### Type Aliases

- [ServerResponse](plugin.md#serverresponse)

### Functions

- [definePlugin](plugin.md#defineplugin)

## Type Aliases

### ServerResponse

Ƭ **ServerResponse**<`TRes`\>: [`ServerResponseSuccess`](../interfaces/plugin._internal_.ServerResponseSuccess.md)<`TRes`\> \| [`ServerResponseError`](../interfaces/plugin._internal_.ServerResponseError.md)

#### Type parameters

| Name |
| :------ |
| `TRes` |

#### Defined in

[src/plugin.tsx:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/plugin.tsx#L21)

## Functions

### definePlugin

▸ **definePlugin**(`fn`): [`DefinePluginFn`](plugin._internal_.md#definepluginfn)

#### Parameters

| Name | Type |
| :------ | :------ |
| `fn` | [`DefinePluginFn`](plugin._internal_.md#definepluginfn) |

#### Returns

[`DefinePluginFn`](plugin._internal_.md#definepluginfn)

#### Defined in

[src/plugin.tsx:68](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/plugin.tsx#L68)
