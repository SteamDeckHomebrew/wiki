[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [deck-components](../modules/deck_components.md) / DropdownProps

# Interface: DropdownProps

[deck-components](../modules/deck_components.md).DropdownProps

## Hierarchy

- **`DropdownProps`**

  ↳ [`DropdownItemProps`](deck_components.DropdownItemProps.md)

## Table of contents

### Properties

- [contextMenuPositionOptions](deck_components.DropdownProps.md#contextmenupositionoptions)
- [disabled](deck_components.DropdownProps.md#disabled)
- [focusable](deck_components.DropdownProps.md#focusable)
- [menuLabel](deck_components.DropdownProps.md#menulabel)
- [rgOptions](deck_components.DropdownProps.md#rgoptions)
- [selectedOption](deck_components.DropdownProps.md#selectedoption)
- [strDefaultLabel](deck_components.DropdownProps.md#strdefaultlabel)

### Methods

- [onChange](deck_components.DropdownProps.md#onchange)
- [onMenuOpened](deck_components.DropdownProps.md#onmenuopened)
- [onMenuWillOpen](deck_components.DropdownProps.md#onmenuwillopen)
- [renderButtonValue](deck_components.DropdownProps.md#renderbuttonvalue)

## Properties

### contextMenuPositionOptions

• `Optional` **contextMenuPositionOptions**: `any`

#### Defined in

[src/deck-components/Dropdown.tsx:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Dropdown.tsx#L29)

___

### disabled

• `Optional` **disabled**: `boolean`

#### Defined in

[src/deck-components/Dropdown.tsx:25](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Dropdown.tsx#L25)

___

### focusable

• `Optional` **focusable**: `boolean`

#### Defined in

[src/deck-components/Dropdown.tsx:33](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Dropdown.tsx#L33)

___

### menuLabel

• `Optional` **menuLabel**: `string`

#### Defined in

[src/deck-components/Dropdown.tsx:30](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Dropdown.tsx#L30)

___

### rgOptions

• **rgOptions**: [`DropdownOption`](../modules/deck_components.md#dropdownoption)[]

#### Defined in

[src/deck-components/Dropdown.tsx:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Dropdown.tsx#L23)

___

### selectedOption

• **selectedOption**: `any`

#### Defined in

[src/deck-components/Dropdown.tsx:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Dropdown.tsx#L24)

___

### strDefaultLabel

• `Optional` **strDefaultLabel**: `string`

#### Defined in

[src/deck-components/Dropdown.tsx:31](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Dropdown.tsx#L31)

## Methods

### onChange

▸ `Optional` **onChange**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | [`SingleDropdownOption`](deck_components.SingleDropdownOption.md) |

#### Returns

`void`

#### Defined in

[src/deck-components/Dropdown.tsx:28](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Dropdown.tsx#L28)

___

### onMenuOpened

▸ `Optional` **onMenuOpened**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Dropdown.tsx:27](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Dropdown.tsx#L27)

___

### onMenuWillOpen

▸ `Optional` **onMenuWillOpen**(`showMenu`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `showMenu` | () => `void` |

#### Returns

`void`

#### Defined in

[src/deck-components/Dropdown.tsx:26](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Dropdown.tsx#L26)

___

### renderButtonValue

▸ `Optional` **renderButtonValue**(`element`): `ReactNode`

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `ReactNode` |

#### Returns

`ReactNode`

#### Defined in

[src/deck-components/Dropdown.tsx:32](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Dropdown.tsx#L32)
