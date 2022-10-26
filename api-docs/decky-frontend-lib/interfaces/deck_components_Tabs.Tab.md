[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [deck-components/Tabs](../modules/deck_components_Tabs.md) / Tab

# Interface: Tab

[deck-components/Tabs](../modules/deck_components_Tabs.md).Tab

Individual tab objects for the Tabs component

`id` ID of this tab, can be used with activeTab to auto-focus a given tab
`title` Title shown in the header bar
`renderTabAddon` Return a ReactNode to render it next to the tab title, i.e. the counts for each tab on the Media page
`content` Content of the tab
`footer` Sets up button handlers and labels

## Table of contents

### Properties

- [content](deck_components_Tabs.Tab.md#content)
- [footer](deck_components_Tabs.Tab.md#footer)
- [id](deck_components_Tabs.Tab.md#id)
- [renderTabAddon](deck_components_Tabs.Tab.md#rendertabaddon)
- [title](deck_components_Tabs.Tab.md#title)

## Properties

### content

• **content**: `ReactNode`

#### Defined in

[src/deck-components/Tabs.tsx:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/cfef1dc/src/deck-components/Tabs.tsx#L21)

___

### footer

• `Optional` **footer**: [`FooterLegendProps`](deck_components_FooterLegend.FooterLegendProps.md)

#### Defined in

[src/deck-components/Tabs.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/cfef1dc/src/deck-components/Tabs.tsx#L22)

___

### id

• **id**: `string`

#### Defined in

[src/deck-components/Tabs.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/cfef1dc/src/deck-components/Tabs.tsx#L18)

___

### renderTabAddon

• `Optional` **renderTabAddon**: () => `ReactNode`

#### Type declaration

▸ (): `ReactNode`

##### Returns

`ReactNode`

#### Defined in

[src/deck-components/Tabs.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/cfef1dc/src/deck-components/Tabs.tsx#L20)

___

### title

• **title**: `string`

#### Defined in

[src/deck-components/Tabs.tsx:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/cfef1dc/src/deck-components/Tabs.tsx#L19)
