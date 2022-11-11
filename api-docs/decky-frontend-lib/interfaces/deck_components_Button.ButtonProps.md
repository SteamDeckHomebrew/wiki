[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [deck-components/Button](../modules/deck_components_Button.md) / ButtonProps

# Interface: ButtonProps

[deck-components/Button](../modules/deck_components_Button.md).ButtonProps

## Hierarchy

- [`DialogButtonProps`](deck_components_Dialog.DialogButtonProps.md)

  ↳ **`ButtonProps`**

## Table of contents

### Properties

- [actionDescriptionMap](deck_components_Button.ButtonProps.md#actiondescriptionmap)
- [className](deck_components_Button.ButtonProps.md#classname)
- [disabled](deck_components_Button.ButtonProps.md#disabled)
- [noFocusRing](deck_components_Button.ButtonProps.md#nofocusring)
- [onButtonDown](deck_components_Button.ButtonProps.md#onbuttondown)
- [onButtonUp](deck_components_Button.ButtonProps.md#onbuttonup)
- [onCancelActionDescription](deck_components_Button.ButtonProps.md#oncancelactiondescription)
- [onCancelButton](deck_components_Button.ButtonProps.md#oncancelbutton)
- [onGamepadBlur](deck_components_Button.ButtonProps.md#ongamepadblur)
- [onGamepadDirection](deck_components_Button.ButtonProps.md#ongamepaddirection)
- [onGamepadFocus](deck_components_Button.ButtonProps.md#ongamepadfocus)
- [onMenuActionDescription](deck_components_Button.ButtonProps.md#onmenuactiondescription)
- [onMenuButton](deck_components_Button.ButtonProps.md#onmenubutton)
- [onOKActionDescription](deck_components_Button.ButtonProps.md#onokactiondescription)
- [onOKButton](deck_components_Button.ButtonProps.md#onokbutton)
- [onOptionsActionDescription](deck_components_Button.ButtonProps.md#onoptionsactiondescription)
- [onOptionsButton](deck_components_Button.ButtonProps.md#onoptionsbutton)
- [onSecondaryActionDescription](deck_components_Button.ButtonProps.md#onsecondaryactiondescription)
- [onSecondaryButton](deck_components_Button.ButtonProps.md#onsecondarybutton)
- [style](deck_components_Button.ButtonProps.md#style)

### Methods

- [onClick](deck_components_Button.ButtonProps.md#onclick)
- [onMouseDown](deck_components_Button.ButtonProps.md#onmousedown)
- [onMouseUp](deck_components_Button.ButtonProps.md#onmouseup)
- [onPointerCancel](deck_components_Button.ButtonProps.md#onpointercancel)
- [onPointerDown](deck_components_Button.ButtonProps.md#onpointerdown)
- [onPointerUp](deck_components_Button.ButtonProps.md#onpointerup)
- [onSubmit](deck_components_Button.ButtonProps.md#onsubmit)
- [onTouchCancel](deck_components_Button.ButtonProps.md#ontouchcancel)
- [onTouchEnd](deck_components_Button.ButtonProps.md#ontouchend)
- [onTouchStart](deck_components_Button.ButtonProps.md#ontouchstart)

## Properties

### actionDescriptionMap

• `Optional` **actionDescriptionMap**: `unknown`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[actionDescriptionMap](deck_components_Dialog.DialogButtonProps.md#actiondescriptionmap)

#### Defined in

[src/deck-components/FooterLegend.ts:50](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L50)

___

### className

• `Optional` **className**: `string`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[className](deck_components_Dialog.DialogButtonProps.md#classname)

#### Defined in

[src/deck-components/Dialog.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/Dialog.tsx#L8)

___

### disabled

• `Optional` **disabled**: `boolean`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[disabled](deck_components_Dialog.DialogButtonProps.md#disabled)

#### Defined in

[src/deck-components/Dialog.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/Dialog.tsx#L13)

___

### noFocusRing

• `Optional` **noFocusRing**: `boolean`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[noFocusRing](deck_components_Dialog.DialogButtonProps.md#nofocusring)

#### Defined in

[src/deck-components/Dialog.tsx:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/Dialog.tsx#L12)

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

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onButtonDown](deck_components_Dialog.DialogButtonProps.md#onbuttondown)

#### Defined in

[src/deck-components/FooterLegend.ts:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L56)

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

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onButtonUp](deck_components_Dialog.DialogButtonProps.md#onbuttonup)

#### Defined in

[src/deck-components/FooterLegend.ts:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L57)

___

### onCancelActionDescription

• `Optional` **onCancelActionDescription**: `string`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onCancelActionDescription](deck_components_Dialog.DialogButtonProps.md#oncancelactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L52)

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

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onCancelButton](deck_components_Dialog.DialogButtonProps.md#oncancelbutton)

#### Defined in

[src/deck-components/FooterLegend.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L59)

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

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onGamepadBlur](deck_components_Dialog.DialogButtonProps.md#ongamepadblur)

#### Defined in

[src/deck-components/FooterLegend.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L64)

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

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onGamepadDirection](deck_components_Dialog.DialogButtonProps.md#ongamepaddirection)

#### Defined in

[src/deck-components/FooterLegend.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L62)

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

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onGamepadFocus](deck_components_Dialog.DialogButtonProps.md#ongamepadfocus)

#### Defined in

[src/deck-components/FooterLegend.ts:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L63)

___

### onMenuActionDescription

• `Optional` **onMenuActionDescription**: `string`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onMenuActionDescription](deck_components_Dialog.DialogButtonProps.md#onmenuactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L55)

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

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onMenuButton](deck_components_Dialog.DialogButtonProps.md#onmenubutton)

#### Defined in

[src/deck-components/FooterLegend.ts:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L65)

___

### onOKActionDescription

• `Optional` **onOKActionDescription**: `string`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onOKActionDescription](deck_components_Dialog.DialogButtonProps.md#onokactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L51)

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

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onOKButton](deck_components_Dialog.DialogButtonProps.md#onokbutton)

#### Defined in

[src/deck-components/FooterLegend.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L58)

___

### onOptionsActionDescription

• `Optional` **onOptionsActionDescription**: `string`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onOptionsActionDescription](deck_components_Dialog.DialogButtonProps.md#onoptionsactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L54)

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

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onOptionsButton](deck_components_Dialog.DialogButtonProps.md#onoptionsbutton)

#### Defined in

[src/deck-components/FooterLegend.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L61)

___

### onSecondaryActionDescription

• `Optional` **onSecondaryActionDescription**: `string`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onSecondaryActionDescription](deck_components_Dialog.DialogButtonProps.md#onsecondaryactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:53](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L53)

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

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onSecondaryButton](deck_components_Dialog.DialogButtonProps.md#onsecondarybutton)

#### Defined in

[src/deck-components/FooterLegend.ts:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/FooterLegend.ts#L60)

___

### style

• `Optional` **style**: `CSSProperties`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[style](deck_components_Dialog.DialogButtonProps.md#style)

#### Defined in

[src/deck-components/Dialog.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/Dialog.tsx#L7)

## Methods

### onClick

▸ `Optional` **onClick**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `MouseEvent` |

#### Returns

`void`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onClick](deck_components_Dialog.DialogButtonProps.md#onclick)

#### Defined in

[src/deck-components/Dialog.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/Dialog.tsx#L14)

___

### onMouseDown

▸ `Optional` **onMouseDown**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `MouseEvent` |

#### Returns

`void`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onMouseDown](deck_components_Dialog.DialogButtonProps.md#onmousedown)

#### Defined in

[src/deck-components/Dialog.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/Dialog.tsx#L18)

___

### onMouseUp

▸ `Optional` **onMouseUp**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `MouseEvent` |

#### Returns

`void`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onMouseUp](deck_components_Dialog.DialogButtonProps.md#onmouseup)

#### Defined in

[src/deck-components/Dialog.tsx:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/Dialog.tsx#L19)

___

### onPointerCancel

▸ `Optional` **onPointerCancel**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `PointerEvent` |

#### Returns

`void`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onPointerCancel](deck_components_Dialog.DialogButtonProps.md#onpointercancel)

#### Defined in

[src/deck-components/Dialog.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/Dialog.tsx#L17)

___

### onPointerDown

▸ `Optional` **onPointerDown**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `PointerEvent` |

#### Returns

`void`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onPointerDown](deck_components_Dialog.DialogButtonProps.md#onpointerdown)

#### Defined in

[src/deck-components/Dialog.tsx:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/Dialog.tsx#L15)

___

### onPointerUp

▸ `Optional` **onPointerUp**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `PointerEvent` |

#### Returns

`void`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onPointerUp](deck_components_Dialog.DialogButtonProps.md#onpointerup)

#### Defined in

[src/deck-components/Dialog.tsx:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/Dialog.tsx#L16)

___

### onSubmit

▸ `Optional` **onSubmit**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `SubmitEvent` |

#### Returns

`void`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onSubmit](deck_components_Dialog.DialogButtonProps.md#onsubmit)

#### Defined in

[src/deck-components/Dialog.tsx:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/Dialog.tsx#L23)

___

### onTouchCancel

▸ `Optional` **onTouchCancel**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `TouchEvent` |

#### Returns

`void`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onTouchCancel](deck_components_Dialog.DialogButtonProps.md#ontouchcancel)

#### Defined in

[src/deck-components/Dialog.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/Dialog.tsx#L22)

___

### onTouchEnd

▸ `Optional` **onTouchEnd**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `TouchEvent` |

#### Returns

`void`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onTouchEnd](deck_components_Dialog.DialogButtonProps.md#ontouchend)

#### Defined in

[src/deck-components/Dialog.tsx:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/Dialog.tsx#L21)

___

### onTouchStart

▸ `Optional` **onTouchStart**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `TouchEvent` |

#### Returns

`void`

#### Inherited from

[DialogButtonProps](deck_components_Dialog.DialogButtonProps.md).[onTouchStart](deck_components_Dialog.DialogButtonProps.md#ontouchstart)

#### Defined in

[src/deck-components/Dialog.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/215156d/src/deck-components/Dialog.tsx#L20)
