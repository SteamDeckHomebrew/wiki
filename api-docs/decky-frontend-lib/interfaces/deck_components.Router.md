[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [deck-components](../modules/deck_components.md) / Router

# Interface: Router

[deck-components](../modules/deck_components.md).Router

## Table of contents

### Accessors

- [MainRunningApp](deck_components.Router.md#mainrunningapp)
- [RunningApps](deck_components.Router.md#runningapps)

### Methods

- [CloseSideMenus](deck_components.Router.md#closesidemenus)
- [GetQuickAccessTab](deck_components.Router.md#getquickaccesstab)
- [Navigate](deck_components.Router.md#navigate)
- [NavigateBackOrOpenMenu](deck_components.Router.md#navigatebackoropenmenu)
- [NavigateToAppProperties](deck_components.Router.md#navigatetoappproperties)
- [NavigateToBugForum](deck_components.Router.md#navigatetobugforum)
- [NavigateToExternalWeb](deck_components.Router.md#navigatetoexternalweb)
- [NavigateToHelp](deck_components.Router.md#navigatetohelp)
- [NavigateToInvites](deck_components.Router.md#navigatetoinvites)
- [NavigateToRunningApp](deck_components.Router.md#navigatetorunningapp)
- [NavigateToStorage](deck_components.Router.md#navigatetostorage)
- [NavigateToStore](deck_components.Router.md#navigatetostore)
- [NavigateToStoreApp](deck_components.Router.md#navigatetostoreapp)
- [NavigateToStoreFreeToPlay](deck_components.Router.md#navigatetostorefreetoplay)
- [NavigateToStoreManual](deck_components.Router.md#navigatetostoremanual)
- [NavigateToStoreNewReleases](deck_components.Router.md#navigatetostorenewreleases)
- [NavigateToStoreOnSale](deck_components.Router.md#navigatetostoreonsale)
- [OpenPowerMenu](deck_components.Router.md#openpowermenu)
- [OpenQuickAccessMenu](deck_components.Router.md#openquickaccessmenu)
- [OpenSideMenu](deck_components.Router.md#opensidemenu)
- [ToggleSideMenu](deck_components.Router.md#togglesidemenu)

## Accessors

### MainRunningApp

• `get` **MainRunningApp**(): `undefined` \| [`AppOverview`](../modules/deck_components.md#appoverview)

#### Returns

`undefined` \| [`AppOverview`](../modules/deck_components.md#appoverview)

#### Defined in

[src/deck-components/Router.tsx:90](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L90)

___

### RunningApps

• `get` **RunningApps**(): [`AppOverview`](../modules/deck_components.md#appoverview)[]

#### Returns

[`AppOverview`](../modules/deck_components.md#appoverview)[]

#### Defined in

[src/deck-components/Router.tsx:89](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L89)

## Methods

### CloseSideMenus

▸ **CloseSideMenus**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:67](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L67)

▸ **CloseSideMenus**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:86](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L86)

___

### GetQuickAccessTab

▸ **GetQuickAccessTab**(): [`QuickAccessTab`](../enums/deck_components.QuickAccessTab.md)

#### Returns

[`QuickAccessTab`](../enums/deck_components.QuickAccessTab.md)

#### Defined in

[src/deck-components/Router.tsx:69](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L69)

___

### Navigate

▸ **Navigate**(`path`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:70](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L70)

___

### NavigateBackOrOpenMenu

▸ **NavigateBackOrOpenMenu**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:71](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L71)

___

### NavigateToAppProperties

▸ **NavigateToAppProperties**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:72](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L72)

___

### NavigateToBugForum

▸ **NavigateToBugForum**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:73](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L73)

___

### NavigateToExternalWeb

▸ **NavigateToExternalWeb**(`url`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` |

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:74](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L74)

___

### NavigateToHelp

▸ **NavigateToHelp**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:75](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L75)

___

### NavigateToInvites

▸ **NavigateToInvites**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:76](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L76)

___

### NavigateToRunningApp

▸ **NavigateToRunningApp**(`replace?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `replace?` | `boolean` |

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:77](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L77)

___

### NavigateToStorage

▸ **NavigateToStorage**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:78](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L78)

___

### NavigateToStore

▸ **NavigateToStore**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:79](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L79)

___

### NavigateToStoreApp

▸ **NavigateToStoreApp**(`appId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `appId` | `string` \| `number` |

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:80](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L80)

___

### NavigateToStoreFreeToPlay

▸ **NavigateToStoreFreeToPlay**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:81](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L81)

___

### NavigateToStoreManual

▸ **NavigateToStoreManual**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:82](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L82)

___

### NavigateToStoreNewReleases

▸ **NavigateToStoreNewReleases**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:83](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L83)

___

### NavigateToStoreOnSale

▸ **NavigateToStoreOnSale**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:84](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L84)

___

### OpenPowerMenu

▸ **OpenPowerMenu**(`unknown?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `unknown?` | `any` |

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:88](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L88)

___

### OpenQuickAccessMenu

▸ **OpenQuickAccessMenu**(`quickAccessTab?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `quickAccessTab?` | [`QuickAccessTab`](../enums/deck_components.QuickAccessTab.md) |

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:68](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L68)

___

### OpenSideMenu

▸ **OpenSideMenu**(`sideMenu`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `sideMenu` | [`SideMenu`](../enums/deck_components.SideMenu.md) |

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:87](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L87)

___

### ToggleSideMenu

▸ **ToggleSideMenu**(`sideMenu`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `sideMenu` | [`SideMenu`](../enums/deck_components.SideMenu.md) |

#### Returns

`void`

#### Defined in

[src/deck-components/Router.tsx:85](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L85)
