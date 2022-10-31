[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [deck-components/Focusable](../modules/deck_components_Focusable.md) / FocusableProps

# Interface: FocusableProps

[deck-components/Focusable](../modules/deck_components_Focusable.md).FocusableProps

## Hierarchy

- `HTMLAttributes`<[`HTMLDivElement`]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLDivElement )\>

- [`FooterLegendProps`](deck_components_FooterLegend.FooterLegendProps.md)

  ↳ **`FocusableProps`**

## Table of contents

### Properties

- [actionDescriptionMap](deck_components_Focusable.FocusableProps.md#actiondescriptionmap)
- [children](deck_components_Focusable.FocusableProps.md#children)
- [flow-children](deck_components_Focusable.FocusableProps.md#flow-children)
- [focusClassName](deck_components_Focusable.FocusableProps.md#focusclassname)
- [focusWithinClassName](deck_components_Focusable.FocusableProps.md#focuswithinclassname)
- [onActivate](deck_components_Focusable.FocusableProps.md#onactivate)
- [onButtonDown](deck_components_Focusable.FocusableProps.md#onbuttondown)
- [onButtonUp](deck_components_Focusable.FocusableProps.md#onbuttonup)
- [onCancel](deck_components_Focusable.FocusableProps.md#oncancel)
- [onCancelActionDescription](deck_components_Focusable.FocusableProps.md#oncancelactiondescription)
- [onCancelButton](deck_components_Focusable.FocusableProps.md#oncancelbutton)
- [onGamepadBlur](deck_components_Focusable.FocusableProps.md#ongamepadblur)
- [onGamepadDirection](deck_components_Focusable.FocusableProps.md#ongamepaddirection)
- [onGamepadFocus](deck_components_Focusable.FocusableProps.md#ongamepadfocus)
- [onMenuActionDescription](deck_components_Focusable.FocusableProps.md#onmenuactiondescription)
- [onMenuButton](deck_components_Focusable.FocusableProps.md#onmenubutton)
- [onOKActionDescription](deck_components_Focusable.FocusableProps.md#onokactiondescription)
- [onOKButton](deck_components_Focusable.FocusableProps.md#onokbutton)
- [onOptionsActionDescription](deck_components_Focusable.FocusableProps.md#onoptionsactiondescription)
- [onOptionsButton](deck_components_Focusable.FocusableProps.md#onoptionsbutton)
- [onSecondaryActionDescription](deck_components_Focusable.FocusableProps.md#onsecondaryactiondescription)
- [onSecondaryButton](deck_components_Focusable.FocusableProps.md#onsecondarybutton)

## Properties

### actionDescriptionMap

• `Optional` **actionDescriptionMap**: `unknown`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[actionDescriptionMap](deck_components_FooterLegend.FooterLegendProps.md#actiondescriptionmap)

#### Defined in

[src/deck-components/FooterLegend.ts:50](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L50)

___

### children

• **children**: `ReactNode`

#### Overrides

HTMLAttributes.children

#### Defined in

[src/deck-components/Focusable.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/Focusable.tsx#L7)

___

### flow-children

• `Optional` **flow-children**: `string`

#### Defined in

[src/deck-components/Focusable.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/Focusable.tsx#L8)

___

### focusClassName

• `Optional` **focusClassName**: `string`

#### Defined in

[src/deck-components/Focusable.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/Focusable.tsx#L9)

___

### focusWithinClassName

• `Optional` **focusWithinClassName**: `string`

#### Defined in

[src/deck-components/Focusable.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/Focusable.tsx#L10)

___

### onActivate

• `Optional` **onActivate**: (`e`: [`CustomEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/CustomEvent )<`any`\>) => `void`

#### Type declaration

▸ (`e`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `e` | [`CustomEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/CustomEvent )<`any`\> |

##### Returns

`void`

#### Defined in

[src/deck-components/Focusable.tsx:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/Focusable.tsx#L11)

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

[src/deck-components/FooterLegend.ts:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L56)

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

[src/deck-components/FooterLegend.ts:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L57)

___

### onCancel

• `Optional` **onCancel**: (`e`: [`CustomEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/CustomEvent )<`any`\>) => `void`

#### Type declaration

▸ (`e`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `e` | [`CustomEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/CustomEvent )<`any`\> |

##### Returns

`void`

#### Defined in

[src/deck-components/Focusable.tsx:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/Focusable.tsx#L12)

___

### onCancelActionDescription

• `Optional` **onCancelActionDescription**: `string`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onCancelActionDescription](deck_components_FooterLegend.FooterLegendProps.md#oncancelactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L52)

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

[src/deck-components/FooterLegend.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L59)

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

[src/deck-components/FooterLegend.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L64)

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

[src/deck-components/FooterLegend.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L62)

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

[src/deck-components/FooterLegend.ts:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L63)

___

### onMenuActionDescription

• `Optional` **onMenuActionDescription**: `string`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onMenuActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onmenuactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L55)

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

[src/deck-components/FooterLegend.ts:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L65)

___

### onOKActionDescription

• `Optional` **onOKActionDescription**: `string`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onOKActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onokactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L51)

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

[src/deck-components/FooterLegend.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L58)

___

### onOptionsActionDescription

• `Optional` **onOptionsActionDescription**: `string`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onOptionsActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onoptionsactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L54)

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

[src/deck-components/FooterLegend.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L61)

___

### onSecondaryActionDescription

• `Optional` **onSecondaryActionDescription**: `string`

#### Inherited from

[FooterLegendProps](deck_components_FooterLegend.FooterLegendProps.md).[onSecondaryActionDescription](deck_components_FooterLegend.FooterLegendProps.md#onsecondaryactiondescription)

#### Defined in

[src/deck-components/FooterLegend.ts:53](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L53)

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

[src/deck-components/FooterLegend.ts:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/FooterLegend.ts#L60)
