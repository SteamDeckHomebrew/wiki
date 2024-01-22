# deck-components/Tabs

## Index

### Interfaces

- Tab
- TabsProps

### Functions

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

> `ReactNode`

Defined in:  [src/deck-components/Tabs.tsx:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L21)

##### footer?

> [`FooterLegendProps`](FooterLegend#footerlegendprops)

Defined in:  [src/deck-components/Tabs.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L22)

##### id

> `string`

Defined in:  [src/deck-components/Tabs.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L18)

##### renderTabAddon?

> `Function`

###### Type declaration

####### Signature

```ts
(): ReactNode;
```

####### Returns

`ReactNode`

Defined in:  [src/deck-components/Tabs.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L20)

##### title

> `string`

Defined in:  [src/deck-components/Tabs.tsx:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L19)

---

### TabsProps

Props for the [Tabs](Tabs#tabs)

`tabs` array of [Tab](Tabs#tab)
`activeTab` tab currently active, needs to be one of the tabs [id](Tabs#id), must be set using a `useState` in the `onShowTab` handler
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

> `string`

Defined in:  [src/deck-components/Tabs.tsx:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L63)

##### autoFocusContents?

> `boolean`

Defined in:  [src/deck-components/Tabs.tsx:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L65)

##### onShowTab

> `Function`

###### Type declaration

####### Signature

```ts
(tab: string): void;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `tab` | `string` |

####### Returns

`void`

Defined in:  [src/deck-components/Tabs.tsx:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L64)

##### tabs

> [`Tab`](Tabs#tab)[]

Defined in:  [src/deck-components/Tabs.tsx:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Tabs.tsx#L62)

## Functions

### Tabs()

Tabs component as used in the library and media tabs. See [TabsProps](Tabs#tabsprops).
Unlike other components in `decky-frontend-lib`, this requires Decky Loader to be running.

#### Signature

```ts
Tabs(props: PropsWithChildren<TabsProps>, context?: any): null | ReactElement<any, any>;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[`TabsProps`](Tabs#tabsprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544
