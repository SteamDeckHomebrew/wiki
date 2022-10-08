[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [deck-components/Tabs](../modules/deck_components_Tabs.md) / TabsProps

# Interface: TabsProps

[deck-components/Tabs](../modules/deck_components_Tabs.md).TabsProps

Props for the [Tabs](../modules/deck_components_Tabs.md#tabs)

`tabs` array of [Tab](deck_components_Tabs.Tab.md)
`activeTab` tab currently active, needs to be one of the tabs [id](deck_components_Tabs.Tab.md#id), must be set using a `useState` in the `onShowTab` handler
`onShowTab` Called when the active tab should change, needs to set `activeTab`. See example.
`autoFocusContents` Whether to automatically focus the tab contents or not.
`footer` Sets up button handlers and labels

**`Example`**

```ts
const Component: FC = () => {
const [currentTab, setCurrentTab] = useState<string>("Tab1");

return (
  <Tabs
    title="Theme Manager"
    activeTab={currentTabRoute}
    onShowTab={(tabID: string) => {
       setCurrentTabRoute(tabID);
    }}
    tabs={[
      {
        title: "Tab 1",
        content: <Tab1Component />,
        id: "Tab1",
      },
      {
        title: "Tab 2",
        content: <Tab2Component />,
        id: "Tab2",
      },
    ]}
  />
 );
};
```

## Table of contents

### Properties

- [activeTab](deck_components_Tabs.TabsProps.md#activetab)
- [autoFocusContents](deck_components_Tabs.TabsProps.md#autofocuscontents)
- [onShowTab](deck_components_Tabs.TabsProps.md#onshowtab)
- [tabs](deck_components_Tabs.TabsProps.md#tabs)

## Properties

### activeTab

• **activeTab**: `string`

#### Defined in

[src/deck-components/Tabs.tsx:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/0ce1b54/src/deck-components/Tabs.tsx#L60)

___

### autoFocusContents

• `Optional` **autoFocusContents**: `boolean`

#### Defined in

[src/deck-components/Tabs.tsx:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/0ce1b54/src/deck-components/Tabs.tsx#L62)

___

### onShowTab

• **onShowTab**: (`tab`: `string`) => `void`

#### Type declaration

▸ (`tab`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `tab` | `string` |

##### Returns

`void`

#### Defined in

[src/deck-components/Tabs.tsx:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/0ce1b54/src/deck-components/Tabs.tsx#L61)

___

### tabs

• **tabs**: [`Tab`](deck_components_Tabs.Tab.md)[]

#### Defined in

[src/deck-components/Tabs.tsx:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/0ce1b54/src/deck-components/Tabs.tsx#L59)
