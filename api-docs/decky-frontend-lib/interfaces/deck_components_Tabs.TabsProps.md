[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [deck-components/Tabs](../modules/deck_components_Tabs.md) / TabsProps

# Interface: TabsProps

[deck-components/Tabs](../modules/deck_components_Tabs.md).TabsProps

Props for the [Tabs](../modules/deck_components_Tabs.md#tabs)

**`Property`**

array of [Tab](deck_components_Tabs.Tab.md)

**`Property`**

tab to automatically focus, [id](deck_components_Tabs.Tab.md#id)

**`Property`**

Currently unknown, but required.

**`Property`**

Whether to automatically focus the tab contents or not.

**`Property`**

Sets up button handlers and labels

## Table of contents

### Properties

- [activeTab](deck_components_Tabs.TabsProps.md#activetab)
- [autoFocusContents](deck_components_Tabs.TabsProps.md#autofocuscontents)
- [onShowTab](deck_components_Tabs.TabsProps.md#onshowtab)
- [tabs](deck_components_Tabs.TabsProps.md#tabs)

## Properties

### activeTab

• `Optional` **activeTab**: `string`

#### Defined in

[src/deck-components/Tabs.tsx:33](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/7161e75/src/deck-components/Tabs.tsx#L33)

___

### autoFocusContents

• `Optional` **autoFocusContents**: `boolean`

#### Defined in

[src/deck-components/Tabs.tsx:35](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/7161e75/src/deck-components/Tabs.tsx#L35)

___

### onShowTab

• **onShowTab**: (...`args`: `unknown`[]) => `void`

#### Type declaration

▸ (...`args`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `...args` | `unknown`[] |

##### Returns

`void`

#### Defined in

[src/deck-components/Tabs.tsx:34](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/7161e75/src/deck-components/Tabs.tsx#L34)

___

### tabs

• **tabs**: [`Tab`](deck_components_Tabs.Tab.md)[]

#### Defined in

[src/deck-components/Tabs.tsx:32](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/7161e75/src/deck-components/Tabs.tsx#L32)
