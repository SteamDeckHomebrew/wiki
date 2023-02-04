---
title: "deck-components/Tabs"
editor: "markdown"
published: true
---

# deck-components/Tabs

## Index

### Interfaces

- Tab
- TabsProps

### Variables

- Tabs

## Interfaces

### Tab

Individual tab objects for the Tabs component

`id` ID of this tab, can be used with activeTab to auto-focus a given tab
`title` Title shown in the header bar
`renderTabAddon` Return a ReactNode to render it next to the tab title, i.e. the counts for each tab on the Media page
`content` Content of the tab
`footer` Sets up button handlers and labels

#### Index

##### Properties

- content
- footer
- id
- renderTabAddon
- title

#### Properties

##### content

```ts
content: ReactNode
```

Defined in:  [src/deck-components/Tabs.tsx:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L21)

##### footer

```ts
footer?: FooterLegendProps
```

Defined in:  [src/deck-components/Tabs.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L22)

##### id

```ts
id: string
```

Defined in:  [src/deck-components/Tabs.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L18)

##### renderTabAddon

```ts
renderTabAddon?: Function
```

###### Type declaration

####### Signature

```ts
(): ReactNode
```

> ####### Returns
>
> `ReactNode`
>
> Defined in:  [src/deck-components/Tabs.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L20)
>

Defined in:  [src/deck-components/Tabs.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L20)

##### title

```ts
title: string
```

Defined in:  [src/deck-components/Tabs.tsx:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L19)

---

### TabsProps

Props for the [Tabs](deck/components/Tabs#tabs)

`tabs` array of [Tab](deck/components/Tabs#tab)
`activeTab` tab currently active, needs to be one of the tabs [id](deck/components/Tabs#id), must be set using a `useState` in the `onShowTab` handler
`onShowTab` Called when the active tab should change, needs to set `activeTab`. See example.
`autoFocusContents` Whether to automatically focus the tab contents or not.
`footer` Sets up button handlers and labels

#### Example

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

#### Index

##### Properties

- activeTab
- autoFocusContents
- onShowTab
- tabs

#### Properties

##### activeTab

```ts
activeTab: string
```

Defined in:  [src/deck-components/Tabs.tsx:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L63)

##### autoFocusContents

```ts
autoFocusContents?: boolean
```

Defined in:  [src/deck-components/Tabs.tsx:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L65)

##### onShowTab

```ts
onShowTab: Function
```

###### Type declaration

####### Signature

```ts
(tab: string): void
```

> ####### Parameters
>
> | Name | Type |
> | :------ | :------ |
> | `tab` | `string` |
>
> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/Tabs.tsx:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L64)
>

Defined in:  [src/deck-components/Tabs.tsx:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L64)

##### tabs

```ts
tabs: Tab[]
```

Defined in:  [src/deck-components/Tabs.tsx:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L62)

## Variables

### Tabs

```ts
const Tabs: any
```

Tabs component as used in the library and media tabs. See [TabsProps](deck/components/Tabs#tabsprops)
Unlike other components in `decky-frontend-lib`, this requires Decky Loader to be running.

Defined in:  [src/deck-components/Tabs.tsx:118](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L118)
