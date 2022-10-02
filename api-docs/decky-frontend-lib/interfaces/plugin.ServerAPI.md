[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [plugin](../modules/plugin.md) / ServerAPI

# Interface: ServerAPI

[plugin](../modules/plugin.md).ServerAPI

## Table of contents

### Properties

- [routerHook](plugin.ServerAPI.md#routerhook)
- [toaster](plugin.ServerAPI.md#toaster)

### Methods

- [callPluginMethod](plugin.ServerAPI.md#callpluginmethod)
- [callServerMethod](plugin.ServerAPI.md#callservermethod)
- [executeInTab](plugin.ServerAPI.md#executeintab)
- [fetchNoCors](plugin.ServerAPI.md#fetchnocors)
- [injectCssIntoTab](plugin.ServerAPI.md#injectcssintotab)
- [openFilePicker](plugin.ServerAPI.md#openfilepicker)
- [removeCssFromTab](plugin.ServerAPI.md#removecssfromtab)

## Properties

### routerHook

• **routerHook**: [`RouterHook`](plugin.RouterHook.md)

#### Defined in

[src/plugin.tsx:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/plugin.tsx#L54)

___

### toaster

• **toaster**: [`Toaster`](plugin.Toaster.md)

#### Defined in

[src/plugin.tsx:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/plugin.tsx#L55)

## Methods

### callPluginMethod

▸ **callPluginMethod**<`TArgs`, `TRes`\>(`methodName`, `args`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`ServerResponse`](../modules/plugin.md#serverresponse)<`TRes`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TArgs` | {} |
| `TRes` | {} |

#### Parameters

| Name | Type |
| :------ | :------ |
| `methodName` | `string` |
| `args` | `TArgs` |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`ServerResponse`](../modules/plugin.md#serverresponse)<`TRes`\>\>

#### Defined in

[src/plugin.tsx:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/plugin.tsx#L57)

___

### callServerMethod

▸ **callServerMethod**<`TArgs`, `TRes`\>(`methodName`, `args`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`ServerResponse`](../modules/plugin.md#serverresponse)<`TRes`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TArgs` | {} |
| `TRes` | {} |

#### Parameters

| Name | Type |
| :------ | :------ |
| `methodName` | `string` |
| `args` | `TArgs` |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`ServerResponse`](../modules/plugin.md#serverresponse)<`TRes`\>\>

#### Defined in

[src/plugin.tsx:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/plugin.tsx#L58)

___

### executeInTab

▸ **executeInTab**(`tab`, `runAsync`, `code`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `tab` | `string` |
| `runAsync` | `boolean` |
| `code` | `string` |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`unknown`\>

#### Defined in

[src/plugin.tsx:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/plugin.tsx#L60)

___

### fetchNoCors

▸ **fetchNoCors**<`TRes`\>(`url`, `request?`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`ServerResponse`](../modules/plugin.md#serverresponse)<`TRes`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TRes` | {} |

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `RequestInfo` |
| `request?` | `RequestInit` |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`ServerResponse`](../modules/plugin.md#serverresponse)<`TRes`\>\>

#### Defined in

[src/plugin.tsx:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/plugin.tsx#L59)

___

### injectCssIntoTab

▸ **injectCssIntoTab**<`TRes`\>(`tab`, `style`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`ServerResponse`](../modules/plugin.md#serverresponse)<`TRes`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TRes` | `string` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `tab` | `string` |
| `style` | `string` |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`ServerResponse`](../modules/plugin.md#serverresponse)<`TRes`\>\>

#### Defined in

[src/plugin.tsx:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/plugin.tsx#L61)

___

### openFilePicker

▸ **openFilePicker**(`startPath`, `includeFiles?`, `regex?`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`FilePickerRes`](plugin.FilePickerRes.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `startPath` | `string` |
| `includeFiles?` | `boolean` |
| `regex?` | [`RegExp`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp ) |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`FilePickerRes`](plugin.FilePickerRes.md)\>

#### Defined in

[src/plugin.tsx:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/plugin.tsx#L56)

___

### removeCssFromTab

▸ **removeCssFromTab**(`tab`, `cssId`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `tab` | `string` |
| `cssId` | `string` |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`unknown`\>

#### Defined in

[src/plugin.tsx:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/plugin.tsx#L62)
