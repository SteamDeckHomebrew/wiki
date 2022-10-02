[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [deck-components](../modules/deck_components.md) / DialogButtonProps

# Interface: DialogButtonProps

[deck-components](../modules/deck_components.md).DialogButtonProps

## Hierarchy

- [`DialogCommonProps`](deck_components.DialogCommonProps.md)

- [`FooterLegendProps`](deck_components.FooterLegendProps.md)

  ↳ **`DialogButtonProps`**

  ↳↳ [`ButtonProps`](deck_components.ButtonProps.md)

## Table of contents

### Properties

- [actionDescriptionMap](deck_components.DialogButtonProps.md#actiondescriptionmap)
- [className](deck_components.DialogButtonProps.md#classname)
- [disabled](deck_components.DialogButtonProps.md#disabled)
- [noFocusRing](deck_components.DialogButtonProps.md#nofocusring)
- [onButtonDown](deck_components.DialogButtonProps.md#onbuttondown)
- [onButtonUp](deck_components.DialogButtonProps.md#onbuttonup)
- [onCancelActionDescription](deck_components.DialogButtonProps.md#oncancelactiondescription)
- [onCancelButton](deck_components.DialogButtonProps.md#oncancelbutton)
- [onGamepadBlur](deck_components.DialogButtonProps.md#ongamepadblur)
- [onGamepadDirection](deck_components.DialogButtonProps.md#ongamepaddirection)
- [onGamepadFocus](deck_components.DialogButtonProps.md#ongamepadfocus)
- [onMenuActionDescription](deck_components.DialogButtonProps.md#onmenuactiondescription)
- [onMenuButton](deck_components.DialogButtonProps.md#onmenubutton)
- [onOKActionDescription](deck_components.DialogButtonProps.md#onokactiondescription)
- [onOKButton](deck_components.DialogButtonProps.md#onokbutton)
- [onOptionsActionDescription](deck_components.DialogButtonProps.md#onoptionsactiondescription)
- [onOptionsButton](deck_components.DialogButtonProps.md#onoptionsbutton)
- [onSecondaryActionDescription](deck_components.DialogButtonProps.md#onsecondaryactiondescription)
- [onSecondaryButton](deck_components.DialogButtonProps.md#onsecondarybutton)
- [style](deck_components.DialogButtonProps.md#style)

### Methods

- [onClick](deck_components.DialogButtonProps.md#onclick)
- [onMouseDown](deck_components.DialogButtonProps.md#onmousedown)
- [onMouseUp](deck_components.DialogButtonProps.md#onmouseup)
- [onPointerCancel](deck_components.DialogButtonProps.md#onpointercancel)
- [onPointerDown](deck_components.DialogButtonProps.md#onpointerdown)
- [onPointerUp](deck_components.DialogButtonProps.md#onpointerup)
- [onSubmit](deck_components.DialogButtonProps.md#onsubmit)
- [onTouchCancel](deck_components.DialogButtonProps.md#ontouchcancel)
- [onTouchEnd](deck_components.DialogButtonProps.md#ontouchend)
- [onTouchStart](deck_components.DialogButtonProps.md#ontouchstart)

## Properties

### actionDescriptionMap

• `Optional` **actionDescriptionMap**: `unknown`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[actionDescriptionMap](deck_components.FooterLegendProps.md#actiondescriptionmap)

#### Defined in

[src/deck-components/FooterLegend.ts:50](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L50)

___

### className

• `Optional` **className**: `string`

#### Inherited from

[DialogCommonProps](deck_components.DialogCommonProps.md).[className](deck_components.DialogCommonProps.md#classname)

#### Defined in

[src/deck-components/Dialog.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/Dialog.tsx#L7)

___

### disabled

• `Optional` **disabled**: `boolean`

#### Defined in

[src/deck-components/Dialog.tsx:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/Dialog.tsx#L12)

___

### noFocusRing

• `Optional` **noFocusRing**: `boolean`

#### Defined in

[src/deck-components/Dialog.tsx:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/Dialog.tsx#L11)

___

### onButtonDown

• `Optional` **onButtonDown**: (`evt`: [`GamepadEvent`](../modules/deck_components.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[onButtonDown](deck_components.FooterLegendProps.md#onbuttondown)

#### Defined in

[src/deck-components/FooterLegend.ts:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L56)

___

### onButtonUp

• `Optional` **onButtonUp**: (`evt`: [`GamepadEvent`](../modules/deck_components.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[onButtonUp](deck_components.FooterLegendProps.md#onbuttonup)

#### Defined in

[src/deck-components/FooterLegend.ts:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L57)

___

### onCancelActionDescription

• `Optional` **onCancelActionDescription**: `string`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[onCancelActionDescription](deck_components.FooterLegendProps.md#oncancelactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L52)

___

### onCancelButton

• `Optional` **onCancelButton**: (`evt`: [`GamepadEvent`](../modules/deck_components.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[onCancelButton](deck_components.FooterLegendProps.md#oncancelbutton)

#### Defined in

[src/deck-components/FooterLegend.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L59)

___

### onGamepadBlur

• `Optional` **onGamepadBlur**: (`evt`: [`GamepadEvent`](../modules/deck_components.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[onGamepadBlur](deck_components.FooterLegendProps.md#ongamepadblur)

#### Defined in

[src/deck-components/FooterLegend.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L64)

___

### onGamepadDirection

• `Optional` **onGamepadDirection**: (`evt`: [`GamepadEvent`](../modules/deck_components.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[onGamepadDirection](deck_components.FooterLegendProps.md#ongamepaddirection)

#### Defined in

[src/deck-components/FooterLegend.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L62)

___

### onGamepadFocus

• `Optional` **onGamepadFocus**: (`evt`: [`GamepadEvent`](../modules/deck_components.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[onGamepadFocus](deck_components.FooterLegendProps.md#ongamepadfocus)

#### Defined in

[src/deck-components/FooterLegend.ts:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L63)

___

### onMenuActionDescription

• `Optional` **onMenuActionDescription**: `string`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[onMenuActionDescription](deck_components.FooterLegendProps.md#onmenuactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L55)

___

### onMenuButton

• `Optional` **onMenuButton**: (`evt`: [`GamepadEvent`](../modules/deck_components.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[onMenuButton](deck_components.FooterLegendProps.md#onmenubutton)

#### Defined in

[src/deck-components/FooterLegend.ts:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L65)

___

### onOKActionDescription

• `Optional` **onOKActionDescription**: `string`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[onOKActionDescription](deck_components.FooterLegendProps.md#onokactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L51)

___

### onOKButton

• `Optional` **onOKButton**: (`evt`: [`GamepadEvent`](../modules/deck_components.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[onOKButton](deck_components.FooterLegendProps.md#onokbutton)

#### Defined in

[src/deck-components/FooterLegend.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L58)

___

### onOptionsActionDescription

• `Optional` **onOptionsActionDescription**: `string`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[onOptionsActionDescription](deck_components.FooterLegendProps.md#onoptionsactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L54)

___

### onOptionsButton

• `Optional` **onOptionsButton**: (`evt`: [`GamepadEvent`](../modules/deck_components.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[onOptionsButton](deck_components.FooterLegendProps.md#onoptionsbutton)

#### Defined in

[src/deck-components/FooterLegend.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L61)

___

### onSecondaryActionDescription

• `Optional` **onSecondaryActionDescription**: `string`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[onSecondaryActionDescription](deck_components.FooterLegendProps.md#onsecondaryactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:53](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L53)

___

### onSecondaryButton

• `Optional` **onSecondaryButton**: (`evt`: [`GamepadEvent`](../modules/deck_components.md#gamepadevent)) => `void`

#### Type declaration

▸ (`evt`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](../modules/deck_components.md#gamepadevent) |

##### Returns

`void`

#### Inherited from

[FooterLegendProps](deck_components.FooterLegendProps.md).[onSecondaryButton](deck_components.FooterLegendProps.md#onsecondarybutton)

#### Defined in

[src/deck-components/FooterLegend.ts:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/FooterLegend.ts#L60)

___

### style

• `Optional` **style**: `CSSProperties`

#### Inherited from

[DialogCommonProps](deck_components.DialogCommonProps.md).[style](deck_components.DialogCommonProps.md#style)

#### Defined in

[src/deck-components/Dialog.tsx:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/Dialog.tsx#L6)

## Methods

### onClick

▸ `Optional` **onClick**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `MouseEvent` |

#### Returns

`void`

#### Defined in

[src/deck-components/Dialog.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/Dialog.tsx#L13)

___

### onMouseDown

▸ `Optional` **onMouseDown**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `MouseEvent` |

#### Returns

`void`

#### Defined in

[src/deck-components/Dialog.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/Dialog.tsx#L17)

___

### onMouseUp

▸ `Optional` **onMouseUp**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `MouseEvent` |

#### Returns

`void`

#### Defined in

[src/deck-components/Dialog.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/Dialog.tsx#L18)

___

### onPointerCancel

▸ `Optional` **onPointerCancel**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `PointerEvent` |

#### Returns

`void`

#### Defined in

[src/deck-components/Dialog.tsx:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/Dialog.tsx#L16)

___

### onPointerDown

▸ `Optional` **onPointerDown**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `PointerEvent` |

#### Returns

`void`

#### Defined in

[src/deck-components/Dialog.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/Dialog.tsx#L14)

___

### onPointerUp

▸ `Optional` **onPointerUp**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `PointerEvent` |

#### Returns

`void`

#### Defined in

[src/deck-components/Dialog.tsx:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/Dialog.tsx#L15)

___

### onSubmit

▸ `Optional` **onSubmit**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `SubmitEvent` |

#### Returns

`void`

#### Defined in

[src/deck-components/Dialog.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/Dialog.tsx#L22)

___

### onTouchCancel

▸ `Optional` **onTouchCancel**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `TouchEvent` |

#### Returns

`void`

#### Defined in

[src/deck-components/Dialog.tsx:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/Dialog.tsx#L21)

___

### onTouchEnd

▸ `Optional` **onTouchEnd**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `TouchEvent` |

#### Returns

`void`

#### Defined in

[src/deck-components/Dialog.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/Dialog.tsx#L20)

___

### onTouchStart

▸ `Optional` **onTouchStart**(`e`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `TouchEvent` |

#### Returns

`void`

#### Defined in

[src/deck-components/Dialog.tsx:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/33dd4e5/src/deck-components/Dialog.tsx#L19)
