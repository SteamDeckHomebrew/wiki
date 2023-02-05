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

- [`DropdownProps`](Dropdown#dropdownprops).[`ItemProps`](Item#itemprops).**DropdownItemProps**

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

##### bottomSeparator?

> `"standard"` \| `"thick"` \| `"none"`

Inherited from: [ItemProps](Item#itemprops).[bottomSeparator](Item#bottomseparator)

Defined in:  [src/deck-components/Item.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L8)

##### contextMenuPositionOptions?

> `any`

Inherited from: [DropdownProps](Dropdown#dropdownprops).[contextMenuPositionOptions](Dropdown#contextmenupositionoptions)

Defined in:  [src/deck-components/Dropdown.tsx:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L29)

##### description?

> `ReactNode`

Inherited from: [ItemProps](Item#itemprops).[description](Item#description)

Defined in:  [src/deck-components/Item.tsx:5](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L5)

##### disabled?

> `boolean`

Inherited from: [DropdownProps](Dropdown#dropdownprops).[disabled](Dropdown#disabled)

Defined in:  [src/deck-components/Dropdown.tsx:25](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L25)

##### focusable?

> `boolean`

Inherited from: [DropdownProps](Dropdown#dropdownprops).[focusable](Dropdown#focusable)

Defined in:  [src/deck-components/Dropdown.tsx:33](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L33)

##### icon?

> `ReactNode`

Inherited from: [ItemProps](Item#itemprops).[icon](Item#icon)

Defined in:  [src/deck-components/Item.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L7)

##### indentLevel?

> `number`

Inherited from: [ItemProps](Item#itemprops).[indentLevel](Item#indentlevel)

Defined in:  [src/deck-components/Item.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L9)

##### label?

> `ReactNode`

Inherited from: [ItemProps](Item#itemprops).[label](Item#label)

Defined in:  [src/deck-components/Item.tsx:4](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L4)

##### layout?

> `"below"` \| `"inline"`

Inherited from: [ItemProps](Item#itemprops).[layout](Item#layout)

Defined in:  [src/deck-components/Item.tsx:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L6)

##### menuLabel?

> `string`

Inherited from: [DropdownProps](Dropdown#dropdownprops).[menuLabel](Dropdown#menulabel)

Defined in:  [src/deck-components/Dropdown.tsx:30](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L30)

##### rgOptions

> [`DropdownOption`](Dropdown#dropdownoption)[]

Inherited from: [DropdownProps](Dropdown#dropdownprops).[rgOptions](Dropdown#rgoptions)

Defined in:  [src/deck-components/Dropdown.tsx:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L23)

##### selectedOption

> `any`

Inherited from: [DropdownProps](Dropdown#dropdownprops).[selectedOption](Dropdown#selectedoption)

Defined in:  [src/deck-components/Dropdown.tsx:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L24)

##### strDefaultLabel?

> `string`

Inherited from: [DropdownProps](Dropdown#dropdownprops).[strDefaultLabel](Dropdown#strdefaultlabel)

Defined in:  [src/deck-components/Dropdown.tsx:31](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L31)

##### tooltip?

> `string`

Inherited from: [ItemProps](Item#itemprops).[tooltip](Item#tooltip)

Defined in:  [src/deck-components/Item.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Item.tsx#L10)

#### Methods

##### onChange()?

###### Signature

```ts
Optional onChange(data: SingleDropdownOption): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `data` | [`SingleDropdownOption`](Dropdown#singledropdownoption) |

###### Returns

`void`

Inherited from: [DropdownProps](Dropdown#dropdownprops).[onChange](Dropdown#onchange)

Defined in:  [src/deck-components/Dropdown.tsx:28](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L28)

##### onMenuOpened()?

###### Signature

```ts
Optional onMenuOpened(): void;
```

###### Returns

`void`

Inherited from: [DropdownProps](Dropdown#dropdownprops).[onMenuOpened](Dropdown#onmenuopened)

Defined in:  [src/deck-components/Dropdown.tsx:27](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L27)

##### onMenuWillOpen()?

###### Signature

```ts
Optional onMenuWillOpen(showMenu: Function): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `showMenu` | () => `void` |

###### Returns

`void`

Inherited from: [DropdownProps](Dropdown#dropdownprops).[onMenuWillOpen](Dropdown#onmenuwillopen)

Defined in:  [src/deck-components/Dropdown.tsx:26](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L26)

##### renderButtonValue()?

###### Signature

```ts
Optional renderButtonValue(element: ReactNode): ReactNode;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `ReactNode` |

###### Returns

`ReactNode`

Inherited from: [DropdownProps](Dropdown#dropdownprops).[renderButtonValue](Dropdown#renderbuttonvalue)

Defined in:  [src/deck-components/Dropdown.tsx:32](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L32)

---

### DropdownProps

#### Hierarchy

- [`DropdownItemProps`](Dropdown#dropdownitemprops)

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

##### contextMenuPositionOptions?

> `any`

Defined in:  [src/deck-components/Dropdown.tsx:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L29)

##### disabled?

> `boolean`

Defined in:  [src/deck-components/Dropdown.tsx:25](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L25)

##### focusable?

> `boolean`

Defined in:  [src/deck-components/Dropdown.tsx:33](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L33)

##### menuLabel?

> `string`

Defined in:  [src/deck-components/Dropdown.tsx:30](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L30)

##### rgOptions

> [`DropdownOption`](Dropdown#dropdownoption)[]

Defined in:  [src/deck-components/Dropdown.tsx:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L23)

##### selectedOption

> `any`

Defined in:  [src/deck-components/Dropdown.tsx:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L24)

##### strDefaultLabel?

> `string`

Defined in:  [src/deck-components/Dropdown.tsx:31](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L31)

#### Methods

##### onChange()?

###### Signature

```ts
Optional onChange(data: SingleDropdownOption): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `data` | [`SingleDropdownOption`](Dropdown#singledropdownoption) |

###### Returns

`void`

Defined in:  [src/deck-components/Dropdown.tsx:28](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L28)

##### onMenuOpened()?

###### Signature

```ts
Optional onMenuOpened(): void;
```

###### Returns

`void`

Defined in:  [src/deck-components/Dropdown.tsx:27](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L27)

##### onMenuWillOpen()?

###### Signature

```ts
Optional onMenuWillOpen(showMenu: Function): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `showMenu` | () => `void` |

###### Returns

`void`

Defined in:  [src/deck-components/Dropdown.tsx:26](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L26)

##### renderButtonValue()?

###### Signature

```ts
Optional renderButtonValue(element: ReactNode): ReactNode;
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

##### data?

> `undefined`

Defined in:  [src/deck-components/Dropdown.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L17)

##### label

> `ReactNode`

Defined in:  [src/deck-components/Dropdown.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L14)

##### options

> [`DropdownOption`](Dropdown#dropdownoption)[]

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

> `any`

Defined in:  [src/deck-components/Dropdown.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L7)

##### label

> `ReactNode`

Defined in:  [src/deck-components/Dropdown.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L8)

##### options?

> `undefined`

Defined in:  [src/deck-components/Dropdown.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L10)

## Type Aliases

### DropdownOption

> [`SingleDropdownOption`](Dropdown#singledropdownoption) \| [`MultiDropdownOption`](Dropdown#multidropdownoption)

Defined in:  [src/deck-components/Dropdown.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dropdown.tsx#L20)

## Functions

### Dropdown()

#### Signature

```ts
Dropdown(props: DropdownProps, context?: any): null | ReactElement<any, any>;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`DropdownProps`](Dropdown#dropdownprops) |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:554

---

### DropdownItem()

#### Signature

```ts
DropdownItem(props: DropdownItemProps, context?: any): null | ReactElement<any, any>;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`DropdownItemProps`](Dropdown#dropdownitemprops) |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:554
