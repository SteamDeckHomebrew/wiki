---
title: "deck-components/ButtonItem"
editor: "markdown"
published: true
---

# deck-components/ButtonItem

## Index

### Interfaces

- ButtonItemProps

### Functions

- ButtonItem

## Interfaces

### ButtonItemProps

#### Hierarchy

- [ItemProps](deck/components/Item#itemprops).**ButtonItemProps**

#### Index

##### Properties

- bottomSeparator
- description
- disabled
- icon
- indentLevel
- label
- layout
- tooltip

##### Methods

- onClick

#### Properties

##### bottomSeparator

```ts
bottomSeparator?: "standard" | "thick" | "none"
```

Inherited from: [ItemProps](deck/components/Item#itemprops).[bottomSeparator](deck/components/Item#bottomseparator)

Defined in:  [src/deck-components/Item.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L8)

##### description

```ts
description?: ReactNode
```

Inherited from: [ItemProps](deck/components/Item#itemprops).[description](deck/components/Item#description)

Defined in:  [src/deck-components/Item.tsx:5](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L5)

##### disabled

```ts
disabled?: boolean
```

Defined in:  [src/deck-components/ButtonItem.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ButtonItem.tsx#L8)

##### icon

```ts
icon?: ReactNode
```

Inherited from: [ItemProps](deck/components/Item#itemprops).[icon](deck/components/Item#icon)

Defined in:  [src/deck-components/Item.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L7)

##### indentLevel

```ts
indentLevel?: number
```

Inherited from: [ItemProps](deck/components/Item#itemprops).[indentLevel](deck/components/Item#indentlevel)

Defined in:  [src/deck-components/Item.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L9)

##### label

```ts
label?: ReactNode
```

Inherited from: [ItemProps](deck/components/Item#itemprops).[label](deck/components/Item#label)

Defined in:  [src/deck-components/Item.tsx:4](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L4)

##### layout

```ts
layout?: "below" | "inline"
```

Inherited from: [ItemProps](deck/components/Item#itemprops).[layout](deck/components/Item#layout)

Defined in:  [src/deck-components/Item.tsx:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L6)

##### tooltip

```ts
tooltip?: string
```

Inherited from: [ItemProps](deck/components/Item#itemprops).[tooltip](deck/components/Item#tooltip)

Defined in:  [src/deck-components/Item.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L10)

#### Methods

##### onClick()

###### Signature

```ts
Optional onClick(e: MouseEvent): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `MouseEvent` |

###### Returns

`void`

Defined in:  [src/deck-components/ButtonItem.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ButtonItem.tsx#L7)

## Functions

### ButtonItem()

#### Signature

```ts
ButtonItem(props: PropsWithChildren<ButtonItemProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[ButtonItemProps](deck/components/ButtonItem#buttonitemprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544
