[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [deck-components/Menu](../modules/deck_components_Menu.md) / MenuItemProps

# Interface: MenuItemProps

[deck-components/Menu](../modules/deck_components_Menu.md).MenuItemProps

## Hierarchy

- [`FooterLegendProps`](deck_components_FooterLegend.FooterLegendProps.md)

  ↳ **`MenuItemProps`**

## Table of contents

### Properties

- [actionDescriptionMap](deck_components_Menu.MenuItemProps.md#actiondescriptionmap)
- [bInteractableItem](deck_components_Menu.MenuItemProps.md#binteractableitem)
- [bPlayAudio](deck_components_Menu.MenuItemProps.md#bplayaudio)
- [children](deck_components_Menu.MenuItemProps.md#children)
- [disabled](deck_components_Menu.MenuItemProps.md#disabled)
- [onButtonDown](deck_components_Menu.MenuItemProps.md#onbuttondown)
- [onButtonUp](deck_components_Menu.MenuItemProps.md#onbuttonup)
- [onCancelActionDescription](deck_components_Menu.MenuItemProps.md#oncancelactiondescription)
- [onCancelButton](deck_components_Menu.MenuItemProps.md#oncancelbutton)
- [onGamepadBlur](deck_components_Menu.MenuItemProps.md#ongamepadblur)
- [onGamepadDirection](deck_components_Menu.MenuItemProps.md#ongamepaddirection)
- [onGamepadFocus](deck_components_Menu.MenuItemProps.md#ongamepadfocus)
- [onMenuActionDescription](deck_components_Menu.MenuItemProps.md#onmenuactiondescription)
- [onMenuButton](deck_components_Menu.MenuItemProps.md#onmenubutton)
- [onOKActionDescription](deck_components_Menu.MenuItemProps.md#onokactiondescription)
- [onOKButton](deck_components_Menu.MenuItemProps.md#onokbutton)
- [onOptionsActionDescription](deck_components_Menu.MenuItemProps.md#onoptionsactiondescription)
- [onOptionsButton](deck_components_Menu.MenuItemProps.md#onoptionsbutton)
- [onSecondaryActionDescription](deck_components_Menu.MenuItemProps.md#onsecondaryactiondescription)
- [onSecondaryButton](deck_components_Menu.MenuItemProps.md#onsecondarybutton)
- [selected](deck_components_Menu.MenuItemProps.md#selected)
- [tone](deck_components_Menu.MenuItemProps.md#tone)

### Methods

- [onClick](deck_components_Menu.MenuItemProps.md#onclick)
- [onMouseEnter](deck_components_Menu.MenuItemProps.md#onmouseenter)
- [onMoveRight](deck_components_Menu.MenuItemProps.md#onmoveright)
- [onSelected](deck_components_Menu.MenuItemProps.md#onselected)

## Properties

### actionDescriptionMap

• `Optional` **actionDescriptionMap**: [`ActionDescriptionMap`](../modules/deck_components_FooterLegend.md#actiondescriptionmap)

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[actionDescriptionMap](deck_components_FooterLegend.FooterLegendProps.md#actiondescriptionmap)

#### Defined in

[src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L51)

___

### bInteractableItem

• `Optional` **bInteractableItem**: `boolean`

#### Defined in

[src/deck-components/Menu.tsx:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/Menu.tsx#L54)

___

### bPlayAudio

• `Optional` **bPlayAudio**: `boolean`

#### Defined in

[src/deck-components/Menu.tsx:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/Menu.tsx#L61)

___

### children

• `Optional` **children**: `ReactNode`

#### Defined in

[src/deck-components/Menu.tsx:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/Menu.tsx#L63)

___

### disabled

• `Optional` **disabled**: `boolean`

#### Defined in

[src/deck-components/Menu.tsx:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/Menu.tsx#L60)

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

[src/deck-components/FooterLegend.ts:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L57)

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

[src/deck-components/FooterLegend.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L58)

___

### onCancelActionDescription

• `Optional` **onCancelActionDescription**: `ReactNode`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onCancelActionDescription](deck_components_FooterLegend.FooterLegendProps.md#oncancelactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:53](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L53)

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

[src/deck-components/FooterLegend.ts:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L60)

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

[src/deck-components/FooterLegend.ts:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L65)

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

[src/deck-components/FooterLegend.ts:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L63)

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

[src/deck-components/FooterLegend.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L64)

___

### onMenuActionDescription

• `Optional` **onMenuActionDescription**: `ReactNode`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onMenuActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onmenuactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L56)

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

[src/deck-components/FooterLegend.ts:66](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L66)

___

### onOKActionDescription

• `Optional` **onOKActionDescription**: `ReactNode`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onOKActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onokactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L52)

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

[src/deck-components/FooterLegend.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L59)

___

### onOptionsActionDescription

• `Optional` **onOptionsActionDescription**: `ReactNode`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onOptionsActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onoptionsactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L55)

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

[src/deck-components/FooterLegend.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L62)

___

### onSecondaryActionDescription

• `Optional` **onSecondaryActionDescription**: `ReactNode`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onSecondaryActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onsecondaryactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L54)

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

[src/deck-components/FooterLegend.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/FooterLegend.ts#L61)

___

### selected

• `Optional` **selected**: `boolean`

#### Defined in

[src/deck-components/Menu.tsx:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/Menu.tsx#L59)

___

### tone

• `Optional` **tone**: ``"positive"`` \| ``"emphasis"`` \| ``"destructive"``

#### Defined in

[src/deck-components/Menu.tsx:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/Menu.tsx#L62)

## Methods

### onClick

▸ `Optional` **onClick**(`evt`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`Event`]( https://developer.mozilla.org/en-US/docs/Web/API/Event ) |

#### Returns

`void`

#### Defined in

[src/deck-components/Menu.tsx:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/Menu.tsx#L55)

___

### onMouseEnter

▸ `Optional` **onMouseEnter**(`evt`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | `MouseEvent` |

#### Returns

`void`

#### Defined in

[src/deck-components/Menu.tsx:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/Menu.tsx#L57)

___

### onMoveRight

▸ `Optional` **onMoveRight**(): `void`

#### Returns

`void`

#### Defined in

[src/deck-components/Menu.tsx:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/Menu.tsx#L58)

___

### onSelected

▸ `Optional` **onSelected**(`evt`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`Event`]( https://developer.mozilla.org/en-US/docs/Web/API/Event ) |

#### Returns

`void`

#### Defined in

[src/deck-components/Menu.tsx:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/88f245d/src/deck-components/Menu.tsx#L56)
