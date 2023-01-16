[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [deck-components/DialogCheckbox](../modules/deck_components_DialogCheckbox.md) / DialogCheckboxProps

# Interface: DialogCheckboxProps

[deck-components/DialogCheckbox](../modules/deck_components_DialogCheckbox.md).DialogCheckboxProps

## Hierarchy

- [`DialogCommonProps`](deck_components_Dialog.DialogCommonProps.md)

- [`FooterLegendProps`](deck_components_FooterLegend.FooterLegendProps.md)

  ↳ **`DialogCheckboxProps`**

## Table of contents

### Properties

- [actionDescriptionMap](deck_components_DialogCheckbox.DialogCheckboxProps.md#actiondescriptionmap)
- [bottomSeparator](deck_components_DialogCheckbox.DialogCheckboxProps.md#bottomseparator)
- [checked](deck_components_DialogCheckbox.DialogCheckboxProps.md#checked)
- [className](deck_components_DialogCheckbox.DialogCheckboxProps.md#classname)
- [color](deck_components_DialogCheckbox.DialogCheckboxProps.md#color)
- [controlled](deck_components_DialogCheckbox.DialogCheckboxProps.md#controlled)
- [description](deck_components_DialogCheckbox.DialogCheckboxProps.md#description)
- [disabled](deck_components_DialogCheckbox.DialogCheckboxProps.md#disabled)
- [highlightColor](deck_components_DialogCheckbox.DialogCheckboxProps.md#highlightcolor)
- [label](deck_components_DialogCheckbox.DialogCheckboxProps.md#label)
- [onButtonDown](deck_components_DialogCheckbox.DialogCheckboxProps.md#onbuttondown)
- [onButtonUp](deck_components_DialogCheckbox.DialogCheckboxProps.md#onbuttonup)
- [onCancelActionDescription](deck_components_DialogCheckbox.DialogCheckboxProps.md#oncancelactiondescription)
- [onCancelButton](deck_components_DialogCheckbox.DialogCheckboxProps.md#oncancelbutton)
- [onGamepadBlur](deck_components_DialogCheckbox.DialogCheckboxProps.md#ongamepadblur)
- [onGamepadDirection](deck_components_DialogCheckbox.DialogCheckboxProps.md#ongamepaddirection)
- [onGamepadFocus](deck_components_DialogCheckbox.DialogCheckboxProps.md#ongamepadfocus)
- [onMenuActionDescription](deck_components_DialogCheckbox.DialogCheckboxProps.md#onmenuactiondescription)
- [onMenuButton](deck_components_DialogCheckbox.DialogCheckboxProps.md#onmenubutton)
- [onOKActionDescription](deck_components_DialogCheckbox.DialogCheckboxProps.md#onokactiondescription)
- [onOKButton](deck_components_DialogCheckbox.DialogCheckboxProps.md#onokbutton)
- [onOptionsActionDescription](deck_components_DialogCheckbox.DialogCheckboxProps.md#onoptionsactiondescription)
- [onOptionsButton](deck_components_DialogCheckbox.DialogCheckboxProps.md#onoptionsbutton)
- [onSecondaryActionDescription](deck_components_DialogCheckbox.DialogCheckboxProps.md#onsecondaryactiondescription)
- [onSecondaryButton](deck_components_DialogCheckbox.DialogCheckboxProps.md#onsecondarybutton)
- [style](deck_components_DialogCheckbox.DialogCheckboxProps.md#style)
- [tooltip](deck_components_DialogCheckbox.DialogCheckboxProps.md#tooltip)

### Methods

- [onChange](deck_components_DialogCheckbox.DialogCheckboxProps.md#onchange)
- [onClick](deck_components_DialogCheckbox.DialogCheckboxProps.md#onclick)

## Properties

### actionDescriptionMap

• `Optional` **actionDescriptionMap**: [`ActionDescriptionMap`](../modules/deck_components_FooterLegend.md#actiondescriptionmap)

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[actionDescriptionMap](deck_components_FooterLegend.FooterLegendProps.md#actiondescriptionmap)

#### Defined in

[src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L51)

___

### bottomSeparator

• `Optional` **bottomSeparator**: ``"standard"`` \| ``"thick"`` \| ``"none"``

#### Defined in

[src/deck-components/DialogCheckbox.tsx:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/DialogCheckbox.tsx#L15)

___

### checked

• `Optional` **checked**: `boolean`

#### Defined in

[src/deck-components/DialogCheckbox.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/DialogCheckbox.tsx#L17)

___

### className

• `Optional` **className**: `string`

#### Inherited from

[DialogCommonProps](deck_components_Dialog.DialogCommonProps.md).[className](deck_components_Dialog.DialogCommonProps.md#classname)

#### Defined in

[src/deck-components/Dialog.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/Dialog.tsx#L8)

___

### color

• `Optional` **color**: `string`

#### Defined in

[src/deck-components/DialogCheckbox.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/DialogCheckbox.tsx#L13)

___

### controlled

• `Optional` **controlled**: `boolean`

#### Defined in

[src/deck-components/DialogCheckbox.tsx:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/DialogCheckbox.tsx#L16)

___

### description

• `Optional` **description**: `ReactNode`

#### Defined in

[src/deck-components/DialogCheckbox.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/DialogCheckbox.tsx#L10)

___

### disabled

• `Optional` **disabled**: `boolean`

#### Defined in

[src/deck-components/DialogCheckbox.tsx:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/DialogCheckbox.tsx#L11)

___

### highlightColor

• `Optional` **highlightColor**: `string`

#### Defined in

[src/deck-components/DialogCheckbox.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/DialogCheckbox.tsx#L14)

___

### label

• `Optional` **label**: `ReactNode`

#### Defined in

[src/deck-components/DialogCheckbox.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/DialogCheckbox.tsx#L9)

___

### onButtonDown

• `Optional` **onButtonDown**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onButtonDown](deck_components_FooterLegend.FooterLegendProps.md#onbuttondown)

#### Defined in

[src/deck-components/FooterLegend.ts:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L57)

___

### onButtonUp

• `Optional` **onButtonUp**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onButtonUp](deck_components_FooterLegend.FooterLegendProps.md#onbuttonup)

#### Defined in

[src/deck-components/FooterLegend.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L58)

___

### onCancelActionDescription

• `Optional` **onCancelActionDescription**: `ReactNode`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onCancelActionDescription](deck_components_FooterLegend.FooterLegendProps.md#oncancelactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:53](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L53)

___

### onCancelButton

• `Optional` **onCancelButton**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onCancelButton](deck_components_FooterLegend.FooterLegendProps.md#oncancelbutton)

#### Defined in

[src/deck-components/FooterLegend.ts:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L60)

___

### onGamepadBlur

• `Optional` **onGamepadBlur**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onGamepadBlur](deck_components_FooterLegend.FooterLegendProps.md#ongamepadblur)

#### Defined in

[src/deck-components/FooterLegend.ts:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L65)

___

### onGamepadDirection

• `Optional` **onGamepadDirection**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onGamepadDirection](deck_components_FooterLegend.FooterLegendProps.md#ongamepaddirection)

#### Defined in

[src/deck-components/FooterLegend.ts:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L63)

___

### onGamepadFocus

• `Optional` **onGamepadFocus**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onGamepadFocus](deck_components_FooterLegend.FooterLegendProps.md#ongamepadfocus)

#### Defined in

[src/deck-components/FooterLegend.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L64)

___

### onMenuActionDescription

• `Optional` **onMenuActionDescription**: `ReactNode`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onMenuActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onmenuactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L56)

___

### onMenuButton

• `Optional` **onMenuButton**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onMenuButton](deck_components_FooterLegend.FooterLegendProps.md#onmenubutton)

#### Defined in

[src/deck-components/FooterLegend.ts:66](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L66)

___

### onOKActionDescription

• `Optional` **onOKActionDescription**: `ReactNode`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onOKActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onokactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L52)

___

### onOKButton

• `Optional` **onOKButton**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onOKButton](deck_components_FooterLegend.FooterLegendProps.md#onokbutton)

#### Defined in

[src/deck-components/FooterLegend.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L59)

___

### onOptionsActionDescription

• `Optional` **onOptionsActionDescription**: `ReactNode`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onOptionsActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onoptionsactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L55)

___

### onOptionsButton

• `Optional` **onOptionsButton**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onOptionsButton](deck_components_FooterLegend.FooterLegendProps.md#onoptionsbutton)

#### Defined in

[src/deck-components/FooterLegend.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L62)

___

### onSecondaryActionDescription

• `Optional` **onSecondaryActionDescription**: `ReactNode`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onSecondaryActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onsecondaryactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L54)

___

### onSecondaryButton

• `Optional` **onSecondaryButton**: (`evt`: [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components_FooterLegend.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onSecondaryButton](deck_components_FooterLegend.FooterLegendProps.md#onsecondarybutton)

#### Defined in

[src/deck-components/FooterLegend.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/FooterLegend.ts#L61)

___

### style

• `Optional` **style**: `CSSProperties`

#### Inherited from

[DialogCommonProps](deck_components_Dialog.DialogCommonProps.md).[style](deck_components_Dialog.DialogCommonProps.md#style)

#### Defined in

[src/deck-components/Dialog.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/Dialog.tsx#L7)

___

### tooltip

• `Optional` **tooltip**: `string`

#### Defined in

[src/deck-components/DialogCheckbox.tsx:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/DialogCheckbox.tsx#L12)

## Methods

### onChange

▸ `Optional` **onChange**(`checked`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `checked` | `boolean` |

#### Returns

`void`

#### Defined in

[src/deck-components/DialogCheckbox.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/DialogCheckbox.tsx#L8)

___

### onClick

▸ `Optional` **onClick**(`evt`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`Event`]( https://developer.mozilla.org/en-US/docs/Web/API/Event ) |

#### Returns

`void`

#### Defined in

[src/deck-components/DialogCheckbox.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/2e66e5a/src/deck-components/DialogCheckbox.tsx#L18)
