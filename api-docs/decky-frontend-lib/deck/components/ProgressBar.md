---
title: "deck-components/ProgressBar"
editor: "markdown"
published: true
---

# deck-components/ProgressBar

## Index

### Interfaces

- ProgressBarItemProps
- ProgressBarProps
- ProgressBarWithInfoProps

### Functions

- ProgressBar
- ProgressBarItem
- ProgressBarWithInfo

## Interfaces

### ProgressBarItemProps

#### Hierarchy

- [ItemProps](deck/components/Item#itemprops).**ProgressBarItemProps**

#### Index

##### Properties

- bottomSeparator
- description
- focusable
- icon
- indentLevel
- indeterminate
- label
- layout
- nProgress
- nTransitionSec
- tooltip

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

##### focusable

```ts
focusable?: boolean
```

Defined in:  [src/deck-components/ProgressBar.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ProgressBar.tsx#L10)

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

##### indeterminate

```ts
indeterminate?: boolean
```

Defined in:  [src/deck-components/ProgressBar.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ProgressBar.tsx#L7)

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

##### nProgress

```ts
nProgress?: number
```

Defined in:  [src/deck-components/ProgressBar.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ProgressBar.tsx#L9)

##### nTransitionSec

```ts
nTransitionSec?: number
```

Defined in:  [src/deck-components/ProgressBar.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ProgressBar.tsx#L8)

##### tooltip

```ts
tooltip?: string
```

Inherited from: [ItemProps](deck/components/Item#itemprops).[tooltip](deck/components/Item#tooltip)

Defined in:  [src/deck-components/Item.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L10)

---

### ProgressBarProps

#### Index

##### Properties

- focusable
- indeterminate
- nProgress
- nTransitionSec

#### Properties

##### focusable

```ts
focusable?: boolean
```

Defined in:  [src/deck-components/ProgressBar.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ProgressBar.tsx#L17)

##### indeterminate

```ts
indeterminate?: boolean
```

Defined in:  [src/deck-components/ProgressBar.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ProgressBar.tsx#L14)

##### nProgress

```ts
nProgress?: number
```

Defined in:  [src/deck-components/ProgressBar.tsx:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ProgressBar.tsx#L16)

##### nTransitionSec

```ts
nTransitionSec?: number
```

Defined in:  [src/deck-components/ProgressBar.tsx:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ProgressBar.tsx#L15)

---

### ProgressBarWithInfoProps

#### Hierarchy

- [ProgressBarItemProps](deck/components/ProgressBar#progressbaritemprops).**ProgressBarWithInfoProps**

#### Index

##### Properties

- bottomSeparator
- description
- focusable
- icon
- indentLevel
- indeterminate
- label
- layout
- nProgress
- nTransitionSec
- sOperationText
- sTimeRemaining
- tooltip

#### Properties

##### bottomSeparator

```ts
bottomSeparator?: "standard" | "thick" | "none"
```

Inherited from: [ProgressBarItemProps](deck/components/ProgressBar#progressbaritemprops).[bottomSeparator](deck/components/ProgressBar#bottomseparator)

Defined in:  [src/deck-components/Item.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L8)

##### description

```ts
description?: ReactNode
```

Inherited from: [ProgressBarItemProps](deck/components/ProgressBar#progressbaritemprops).[description](deck/components/ProgressBar#description)

Defined in:  [src/deck-components/Item.tsx:5](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L5)

##### focusable

```ts
focusable?: boolean
```

Inherited from: [ProgressBarItemProps](deck/components/ProgressBar#progressbaritemprops).[focusable](deck/components/ProgressBar#focusable)

Defined in:  [src/deck-components/ProgressBar.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ProgressBar.tsx#L10)

##### icon

```ts
icon?: ReactNode
```

Inherited from: [ProgressBarItemProps](deck/components/ProgressBar#progressbaritemprops).[icon](deck/components/ProgressBar#icon)

Defined in:  [src/deck-components/Item.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L7)

##### indentLevel

```ts
indentLevel?: number
```

Inherited from: [ProgressBarItemProps](deck/components/ProgressBar#progressbaritemprops).[indentLevel](deck/components/ProgressBar#indentlevel)

Defined in:  [src/deck-components/Item.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L9)

##### indeterminate

```ts
indeterminate?: boolean
```

Inherited from: [ProgressBarItemProps](deck/components/ProgressBar#progressbaritemprops).[indeterminate](deck/components/ProgressBar#indeterminate)

Defined in:  [src/deck-components/ProgressBar.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ProgressBar.tsx#L7)

##### label

```ts
label?: ReactNode
```

Inherited from: [ProgressBarItemProps](deck/components/ProgressBar#progressbaritemprops).[label](deck/components/ProgressBar#label)

Defined in:  [src/deck-components/Item.tsx:4](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L4)

##### layout

```ts
layout?: "below" | "inline"
```

Inherited from: [ProgressBarItemProps](deck/components/ProgressBar#progressbaritemprops).[layout](deck/components/ProgressBar#layout)

Defined in:  [src/deck-components/Item.tsx:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L6)

##### nProgress

```ts
nProgress?: number
```

Inherited from: [ProgressBarItemProps](deck/components/ProgressBar#progressbaritemprops).[nProgress](deck/components/ProgressBar#nprogress)

Defined in:  [src/deck-components/ProgressBar.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ProgressBar.tsx#L9)

##### nTransitionSec

```ts
nTransitionSec?: number
```

Inherited from: [ProgressBarItemProps](deck/components/ProgressBar#progressbaritemprops).[nTransitionSec](deck/components/ProgressBar#ntransitionsec)

Defined in:  [src/deck-components/ProgressBar.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ProgressBar.tsx#L8)

##### sOperationText

```ts
sOperationText?: ReactNode
```

Defined in:  [src/deck-components/ProgressBar.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ProgressBar.tsx#L22)

##### sTimeRemaining

```ts
sTimeRemaining?: ReactNode
```

Defined in:  [src/deck-components/ProgressBar.tsx:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/ProgressBar.tsx#L21)

##### tooltip

```ts
tooltip?: string
```

Inherited from: [ProgressBarItemProps](deck/components/ProgressBar#progressbaritemprops).[tooltip](deck/components/ProgressBar#tooltip)

Defined in:  [src/deck-components/Item.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L10)

## Functions

### ProgressBar()

#### Signature

```ts
ProgressBar(props: ProgressBarProps, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [ProgressBarProps](deck/components/ProgressBar#progressbarprops) |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:554

---

### ProgressBarItem()

#### Signature

```ts
ProgressBarItem(props: ProgressBarItemProps, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [ProgressBarItemProps](deck/components/ProgressBar#progressbaritemprops) |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:554

---

### ProgressBarWithInfo()

#### Signature

```ts
ProgressBarWithInfo(props: ProgressBarWithInfoProps, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [ProgressBarWithInfoProps](deck/components/ProgressBar#progressbarwithinfoprops) |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:554
