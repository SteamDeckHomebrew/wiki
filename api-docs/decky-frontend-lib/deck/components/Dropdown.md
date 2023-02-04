---
title: "deck-components/Dropdown"
editor: "markdown"
published: true
---

# deck-components/Dropdown

## Index

### Interfaces

- DropdownItemProps
- DropdownProps
- MultiDropdownOption
- SingleDropdownOption

### Type Aliases

- DropdownOption

### Functions

- Dropdown
- DropdownItem

## Interfaces

### DropdownItemProps

#### Hierarchy

- [DropdownProps](deck/components/Dropdown#dropdownprops).[ItemProps](deck/components/Item#itemprops).**DropdownItemProps**

#### Index

##### Properties

- bottomSeparator
- contextMenuPositionOptions
- description
- disabled
- focusable
- icon
- indentLevel
- label
- layout
- menuLabel
- rgOptions
- selectedOption
- strDefaultLabel
- tooltip

##### Methods

- onChange
- onMenuOpened
- onMenuWillOpen
- renderButtonValue

#### Properties

##### bottomSeparator

```ts
bottomSeparator?: "standard" | "thick" | "none"
```

Inherited from: [ItemProps](deck/components/Item#itemprops).[bottomSeparator](deck/components/Item#bottomseparator)

Defined in:  [src/deck-components/Item.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L8)

##### contextMenuPositionOptions

```ts
contextMenuPositionOptions?: any
```

Inherited from: [DropdownProps](deck/components/Dropdown#dropdownprops).[contextMenuPositionOptions](deck/components/Dropdown#contextmenupositionoptions)

Defined in:  [src/deck-components/Dropdown.tsx:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L29)

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

Inherited from: [DropdownProps](deck/components/Dropdown#dropdownprops).[disabled](deck/components/Dropdown#disabled)

Defined in:  [src/deck-components/Dropdown.tsx:25](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L25)

##### focusable

```ts
focusable?: boolean
```

Inherited from: [DropdownProps](deck/components/Dropdown#dropdownprops).[focusable](deck/components/Dropdown#focusable)

Defined in:  [src/deck-components/Dropdown.tsx:33](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L33)

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

##### menuLabel

```ts
menuLabel?: string
```

Inherited from: [DropdownProps](deck/components/Dropdown#dropdownprops).[menuLabel](deck/components/Dropdown#menulabel)

Defined in:  [src/deck-components/Dropdown.tsx:30](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L30)

##### rgOptions

```ts
rgOptions: DropdownOption[]
```

Inherited from: [DropdownProps](deck/components/Dropdown#dropdownprops).[rgOptions](deck/components/Dropdown#rgoptions)

Defined in:  [src/deck-components/Dropdown.tsx:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L23)

##### selectedOption

```ts
selectedOption: any
```

Inherited from: [DropdownProps](deck/components/Dropdown#dropdownprops).[selectedOption](deck/components/Dropdown#selectedoption)

Defined in:  [src/deck-components/Dropdown.tsx:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L24)

##### strDefaultLabel

```ts
strDefaultLabel?: string
```

Inherited from: [DropdownProps](deck/components/Dropdown#dropdownprops).[strDefaultLabel](deck/components/Dropdown#strdefaultlabel)

Defined in:  [src/deck-components/Dropdown.tsx:31](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L31)

##### tooltip

```ts
tooltip?: string
```

Inherited from: [ItemProps](deck/components/Item#itemprops).[tooltip](deck/components/Item#tooltip)

Defined in:  [src/deck-components/Item.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L10)

#### Methods

##### onChange()

###### Signature

```ts
Optional onChange(data: SingleDropdownOption): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `data` | [SingleDropdownOption](deck/components/Dropdown#singledropdownoption) |

###### Returns

`void`

Inherited from: [DropdownProps](deck/components/Dropdown#dropdownprops).[onChange](deck/components/Dropdown#onchange)

Defined in:  [src/deck-components/Dropdown.tsx:28](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L28)

##### onMenuOpened()

###### Signature

```ts
Optional onMenuOpened(): void
```

###### Returns

`void`

Inherited from: [DropdownProps](deck/components/Dropdown#dropdownprops).[onMenuOpened](deck/components/Dropdown#onmenuopened)

Defined in:  [src/deck-components/Dropdown.tsx:27](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L27)

##### onMenuWillOpen()

###### Signature

```ts
Optional onMenuWillOpen(showMenu: Function): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `showMenu` | () => `void` |

###### Returns

`void`

Inherited from: [DropdownProps](deck/components/Dropdown#dropdownprops).[onMenuWillOpen](deck/components/Dropdown#onmenuwillopen)

Defined in:  [src/deck-components/Dropdown.tsx:26](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L26)

##### renderButtonValue()

###### Signature

```ts
Optional renderButtonValue(element: ReactNode): ReactNode
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `ReactNode` |

###### Returns

`ReactNode`

Inherited from: [DropdownProps](deck/components/Dropdown#dropdownprops).[renderButtonValue](deck/components/Dropdown#renderbuttonvalue)

Defined in:  [src/deck-components/Dropdown.tsx:32](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L32)

---

### DropdownProps

#### Hierarchy

- [DropdownItemProps](deck/components/Dropdown#dropdownitemprops)

#### Index

##### Properties

- contextMenuPositionOptions
- disabled
- focusable
- menuLabel
- rgOptions
- selectedOption
- strDefaultLabel

##### Methods

- onChange
- onMenuOpened
- onMenuWillOpen
- renderButtonValue

#### Properties

##### contextMenuPositionOptions

```ts
contextMenuPositionOptions?: any
```

Defined in:  [src/deck-components/Dropdown.tsx:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L29)

##### disabled

```ts
disabled?: boolean
```

Defined in:  [src/deck-components/Dropdown.tsx:25](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L25)

##### focusable

```ts
focusable?: boolean
```

Defined in:  [src/deck-components/Dropdown.tsx:33](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L33)

##### menuLabel

```ts
menuLabel?: string
```

Defined in:  [src/deck-components/Dropdown.tsx:30](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L30)

##### rgOptions

```ts
rgOptions: DropdownOption[]
```

Defined in:  [src/deck-components/Dropdown.tsx:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L23)

##### selectedOption

```ts
selectedOption: any
```

Defined in:  [src/deck-components/Dropdown.tsx:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L24)

##### strDefaultLabel

```ts
strDefaultLabel?: string
```

Defined in:  [src/deck-components/Dropdown.tsx:31](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L31)

#### Methods

##### onChange()

###### Signature

```ts
Optional onChange(data: SingleDropdownOption): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `data` | [SingleDropdownOption](deck/components/Dropdown#singledropdownoption) |

###### Returns

`void`

Defined in:  [src/deck-components/Dropdown.tsx:28](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L28)

##### onMenuOpened()

###### Signature

```ts
Optional onMenuOpened(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Dropdown.tsx:27](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L27)

##### onMenuWillOpen()

###### Signature

```ts
Optional onMenuWillOpen(showMenu: Function): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `showMenu` | () => `void` |

###### Returns

`void`

Defined in:  [src/deck-components/Dropdown.tsx:26](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L26)

##### renderButtonValue()

###### Signature

```ts
Optional renderButtonValue(element: ReactNode): ReactNode
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `ReactNode` |

###### Returns

`ReactNode`

Defined in:  [src/deck-components/Dropdown.tsx:32](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L32)

---

### MultiDropdownOption

#### Index

##### Properties

- data
- label
- options

#### Properties

##### data

```ts
data?: undefined
```

Defined in:  [src/deck-components/Dropdown.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L17)

##### label

```ts
label: ReactNode
```

Defined in:  [src/deck-components/Dropdown.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L14)

##### options

```ts
options: DropdownOption[]
```

Defined in:  [src/deck-components/Dropdown.tsx:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L15)

---

### SingleDropdownOption

#### Index

##### Properties

- data
- label
- options

#### Properties

##### data

```ts
data: any
```

Defined in:  [src/deck-components/Dropdown.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L7)

##### label

```ts
label: ReactNode
```

Defined in:  [src/deck-components/Dropdown.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L8)

##### options

```ts
options?: undefined
```

Defined in:  [src/deck-components/Dropdown.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L10)

## Type Aliases

### DropdownOption

```ts
DropdownOption: SingleDropdownOption | MultiDropdownOption
```

Defined in:  [src/deck-components/Dropdown.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L20)

## Functions

### Dropdown()

#### Signature

```ts
Dropdown(props: DropdownProps, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [DropdownProps](deck/components/Dropdown#dropdownprops) |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:554

---

### DropdownItem()

#### Signature

```ts
DropdownItem(props: DropdownItemProps, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [DropdownItemProps](deck/components/Dropdown#dropdownitemprops) |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:554
