---
title: "deck-components/SidebarNavigation"
editor: "markdown"
published: true
---

# deck-components/SidebarNavigation

## Index

### Interfaces

- SidebarNavigationPage
- SidebarNavigationProps

### Functions

- SidebarNavigation

## Interfaces

### SidebarNavigationPage

#### Index

##### Properties

- content
- hideTitle
- icon
- identifier
- link
- padding
- route
- title
- visible

#### Properties

##### content

```ts
content: ReactNode
```

Defined in:  [src/deck-components/SidebarNavigation.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L7)

##### hideTitle

```ts
hideTitle?: boolean
```

Defined in:  [src/deck-components/SidebarNavigation.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L10)

##### icon

```ts
icon?: ReactNode
```

Defined in:  [src/deck-components/SidebarNavigation.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L8)

##### identifier

```ts
identifier?: string
```

Defined in:  [src/deck-components/SidebarNavigation.tsx:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L11)

##### link

```ts
link?: string
```

Defined in:  [src/deck-components/SidebarNavigation.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L13)

##### padding

```ts
padding?: "none" | "compact"
```

Defined in:  [src/deck-components/SidebarNavigation.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L14)

##### route

```ts
route?: string
```

Defined in:  [src/deck-components/SidebarNavigation.tsx:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L12)

##### title

```ts
title: string
```

Defined in:  [src/deck-components/SidebarNavigation.tsx:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L6)

##### visible

```ts
visible?: boolean
```

Defined in:  [src/deck-components/SidebarNavigation.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L9)

---

### SidebarNavigationProps

#### Index

##### Properties

- disableRouteReporting
- onPageRequested
- page
- pages
- showTitle
- title

#### Properties

##### disableRouteReporting

```ts
disableRouteReporting?: boolean
```

Defined in:  [src/deck-components/SidebarNavigation.tsx:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L21)

##### onPageRequested

```ts
onPageRequested?: Function
```

###### Type declaration

####### Signature

```ts
(page: string): void
```

> ####### Parameters
>
> | Name | Type |
> | :------ | :------ |
> | `page` | `string` |
>
> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/SidebarNavigation.tsx:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L23)
>

Defined in:  [src/deck-components/SidebarNavigation.tsx:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L23)

##### page

```ts
page?: string
```

Defined in:  [src/deck-components/SidebarNavigation.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L22)

##### pages

```ts
pages: SidebarNavigationPage[]
```

Defined in:  [src/deck-components/SidebarNavigation.tsx:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L19)

##### showTitle

```ts
showTitle?: boolean
```

Defined in:  [src/deck-components/SidebarNavigation.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L20)

##### title

```ts
title?: string
```

Defined in:  [src/deck-components/SidebarNavigation.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SidebarNavigation.tsx#L18)

## Functions

### SidebarNavigation()

#### Signature

```ts
SidebarNavigation(props: SidebarNavigationProps, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [SidebarNavigationProps](deck/components/SidebarNavigation#sidebarnavigationprops) |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:554
