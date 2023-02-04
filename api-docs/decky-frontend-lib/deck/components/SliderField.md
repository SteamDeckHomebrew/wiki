---
title: "deck-components/SliderField"
editor: "markdown"
published: true
---

# deck-components/SliderField

## Index

### Interfaces

- NotchLabel
- SliderFieldProps

### Functions

- SliderField

## Interfaces

### NotchLabel

#### Index

##### Properties

- label
- notchIndex
- value

#### Properties

##### label

```ts
label: string
```

Defined in:  [src/deck-components/SliderField.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L8)

##### notchIndex

```ts
notchIndex: number
```

Defined in:  [src/deck-components/SliderField.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L7)

##### value

```ts
value?: number
```

Defined in:  [src/deck-components/SliderField.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L9)

---

### SliderFieldProps

#### Hierarchy

- [ItemProps](deck/components/Item#itemprops).**SliderFieldProps**

#### Index

##### Properties

- bottomSeparator
- description
- disabled
- editableValue
- icon
- indentLevel
- label
- layout
- max
- min
- minimumDpadGranularity
- notchCount
- notchLabels
- notchTicksVisible
- resetValue
- showValue
- step
- tooltip
- validValues
- value
- valueSuffix

##### Methods

- onChange

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

Defined in:  [src/deck-components/SliderField.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L22)

##### editableValue

```ts
editableValue?: boolean
```

Defined in:  [src/deck-components/SliderField.tsx:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L23)

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

##### max

```ts
max?: number
```

Defined in:  [src/deck-components/SliderField.tsx:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L15)

##### min

```ts
min?: number
```

Defined in:  [src/deck-components/SliderField.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L14)

##### minimumDpadGranularity

```ts
minimumDpadGranularity?: number
```

Defined in:  [src/deck-components/SliderField.tsx:26](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L26)

##### notchCount

```ts
notchCount?: number
```

Defined in:  [src/deck-components/SliderField.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L17)

##### notchLabels

```ts
notchLabels?: NotchLabel[]
```

Defined in:  [src/deck-components/SliderField.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L18)

##### notchTicksVisible

```ts
notchTicksVisible?: boolean
```

Defined in:  [src/deck-components/SliderField.tsx:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L19)

##### resetValue

```ts
resetValue?: number
```

Defined in:  [src/deck-components/SliderField.tsx:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L21)

##### showValue

```ts
showValue?: boolean
```

Defined in:  [src/deck-components/SliderField.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L20)

##### step

```ts
step?: number
```

Defined in:  [src/deck-components/SliderField.tsx:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L16)

##### tooltip

```ts
tooltip?: string
```

Inherited from: [ItemProps](deck/components/Item#itemprops).[tooltip](deck/components/Item#tooltip)

Defined in:  [src/deck-components/Item.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L10)

##### validValues

```ts
validValues?: "steps" | "range" | (value: number) => boolean
```

Defined in:  [src/deck-components/SliderField.tsx:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L24)

##### value

```ts
value: number
```

Defined in:  [src/deck-components/SliderField.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L13)

##### valueSuffix

```ts
valueSuffix?: string
```

Defined in:  [src/deck-components/SliderField.tsx:25](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L25)

#### Methods

##### onChange()

###### Signature

```ts
Optional onChange(value: number): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `number` |

###### Returns

`void`

Defined in:  [src/deck-components/SliderField.tsx:27](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SliderField.tsx#L27)

## Functions

### SliderField()

#### Signature

```ts
SliderField(props: PropsWithChildren<SliderFieldProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[SliderFieldProps](deck/components/SliderField#sliderfieldprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544
