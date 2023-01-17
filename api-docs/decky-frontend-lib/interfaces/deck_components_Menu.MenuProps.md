[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [deck-components/Menu](../modules/deck_components_Menu.md) / MenuProps

# Interface: MenuProps

[deck-components/Menu](../modules/deck_components_Menu.md).MenuProps

## Hierarchy

- [`FooterLegendProps`](deck_components_FooterLegend.FooterLegendProps.md)

  ↳ **`MenuProps`**

## Table of contents

### Properties

- [actionDescriptionMap](deck_components_Menu.MenuProps.md#actiondescriptionmap)
- [cancelText](deck_components_Menu.MenuProps.md#canceltext)
- [children](deck_components_Menu.MenuProps.md#children)
- [label](deck_components_Menu.MenuProps.md#label)
- [onButtonDown](deck_components_Menu.MenuProps.md#onbuttondown)
- [onButtonUp](deck_components_Menu.MenuProps.md#onbuttonup)
- [onCancelActionDescription](deck_components_Menu.MenuProps.md#oncancelactiondescription)
- [onCancelButton](deck_components_Menu.MenuProps.md#oncancelbutton)
- [onGamepadBlur](deck_components_Menu.MenuProps.md#ongamepadblur)
- [onGamepadDirection](deck_components_Menu.MenuProps.md#ongamepaddirection)
- [onGamepadFocus](deck_components_Menu.MenuProps.md#ongamepadfocus)
- [onMenuActionDescription](deck_components_Menu.MenuProps.md#onmenuactiondescription)
- [onMenuButton](deck_components_Menu.MenuProps.md#onmenubutton)
- [onOKActionDescription](deck_components_Menu.MenuProps.md#onokactiondescription)
- [onOKButton](deck_components_Menu.MenuProps.md#onokbutton)
- [onOptionsActionDescription](deck_components_Menu.MenuProps.md#onoptionsactiondescription)
- [onOptionsButton](deck_components_Menu.MenuProps.md#onoptionsbutton)
- [onSecondaryActionDescription](deck_components_Menu.MenuProps.md#onsecondaryactiondescription)
- [onSecondaryButton](deck_components_Menu.MenuProps.md#onsecondarybutton)

### Methods

- [onCancel](deck_components_Menu.MenuProps.md#oncancel)

## Properties

### actionDescriptionMap

• `Optional` **actionDescriptionMap**: [`ActionDescriptionMap`](../modules/deck_components_FooterLegend.md#actiondescriptionmap)

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[actionDescriptionMap](deck_components_FooterLegend.FooterLegendProps.md#actiondescriptionmap)

#### Defined in

[src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L51)

___

### cancelText

• `Optional` **cancelText**: `string`

#### Defined in

[src/deck-components/Menu.tsx:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/Menu.tsx#L19)

___

### children

• `Optional` **children**: `ReactNode`

#### Defined in

[src/deck-components/Menu.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/Menu.tsx#L20)

___

### label

• **label**: `string`

#### Defined in

[src/deck-components/Menu.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/Menu.tsx#L17)

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

[src/deck-components/FooterLegend.ts:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L57)

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

[src/deck-components/FooterLegend.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L58)

___

### onCancelActionDescription

• `Optional` **onCancelActionDescription**: `ReactNode`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onCancelActionDescription](deck_components_FooterLegend.FooterLegendProps.md#oncancelactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:53](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L53)

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

[src/deck-components/FooterLegend.ts:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L60)

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

[src/deck-components/FooterLegend.ts:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L65)

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

[src/deck-components/FooterLegend.ts:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L63)

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

[src/deck-components/FooterLegend.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L64)

___

### onMenuActionDescription

• `Optional` **onMenuActionDescription**: `ReactNode`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onMenuActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onmenuactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L56)

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

[src/deck-components/FooterLegend.ts:66](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L66)

___

### onOKActionDescription

• `Optional` **onOKActionDescription**: `ReactNode`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onOKActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onokactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L52)

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

[src/deck-components/FooterLegend.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L59)

___

### onOptionsActionDescription

• `Optional` **onOptionsActionDescription**: `ReactNode`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onOptionsActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onoptionsactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L55)

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

[src/deck-components/FooterLegend.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L62)

___

### onSecondaryActionDescription

• `Optional` **onSecondaryActionDescription**: `ReactNode`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onSecondaryActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onsecondaryactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L54)

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

[src/deck-components/FooterLegend.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/FooterLegend.ts#L61)

## Methods

### onCancel

▸ `Optional` **onCancel**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Menu.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/9723854/src/deck-components/Menu.tsx#L18)
