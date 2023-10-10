# deck-components/DialogCheckbox

## Index

### Interfaces

- DialogCheckboxProps

### Functions

- DialogCheckbox

## Interfaces

### DialogCheckboxProps

#### Hierarchy

- [`DialogCommonProps`](Dialog#dialogcommonprops).[`FooterLegendProps`](FooterLegend#footerlegendprops).**DialogCheckboxProps**

#### Index

##### Properties

- actionDescriptionMap
- bottomSeparator
- checked
- className
- color
- controlled
- description
- disabled
- highlightColor
- label
- onButtonDown
- onButtonUp
- onCancelActionDescription
- onCancelButton
- onGamepadBlur
- onGamepadDirection
- onGamepadFocus
- onMenuActionDescription
- onMenuButton
- onOKActionDescription
- onOKButton
- onOptionsActionDescription
- onOptionsButton
- onSecondaryActionDescription
- onSecondaryButton
- style
- tooltip

##### Methods

- onChange
- onClick

#### Properties

##### actionDescriptionMap?

> [`ActionDescriptionMap`](FooterLegend#actiondescriptionmap)

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[actionDescriptionMap](FooterLegend#actiondescriptionmap)

Defined in:  [src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L51)

##### bottomSeparator?

> `"standard"` \| `"thick"` \| `"none"`

Defined in:  [src/deck-components/DialogCheckbox.tsx:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L15)

##### checked?

> `boolean`

Defined in:  [src/deck-components/DialogCheckbox.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L17)

##### className?

> `string`

Inherited from: [DialogCommonProps](Dialog#dialogcommonprops).[className](Dialog#classname)

Defined in:  [src/deck-components/Dialog.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L8)

##### color?

> `string`

Defined in:  [src/deck-components/DialogCheckbox.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L13)

##### controlled?

> `boolean`

Defined in:  [src/deck-components/DialogCheckbox.tsx:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L16)

##### description?

> `ReactNode`

Defined in:  [src/deck-components/DialogCheckbox.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L10)

##### disabled?

> `boolean`

Defined in:  [src/deck-components/DialogCheckbox.tsx:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L11)

##### highlightColor?

> `string`

Defined in:  [src/deck-components/DialogCheckbox.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L14)

##### label?

> `ReactNode`

Defined in:  [src/deck-components/DialogCheckbox.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L9)

##### onButtonDown?

> `Function`

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](FooterLegend#gamepadevent) |

####### Returns

`void`

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[onButtonDown](FooterLegend#onbuttondown)

Defined in:  [src/deck-components/FooterLegend.ts:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L57)

##### onButtonUp?

> `Function`

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](FooterLegend#gamepadevent) |

####### Returns

`void`

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[onButtonUp](FooterLegend#onbuttonup)

Defined in:  [src/deck-components/FooterLegend.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L58)

##### onCancelActionDescription?

> `ReactNode`

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[onCancelActionDescription](FooterLegend#oncancelactiondescription)

Defined in:  [src/deck-components/FooterLegend.ts:53](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L53)

##### onCancelButton?

> `Function`

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](FooterLegend#gamepadevent) |

####### Returns

`void`

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[onCancelButton](FooterLegend#oncancelbutton)

Defined in:  [src/deck-components/FooterLegend.ts:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L60)

##### onGamepadBlur?

> `Function`

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](FooterLegend#gamepadevent) |

####### Returns

`void`

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[onGamepadBlur](FooterLegend#ongamepadblur)

Defined in:  [src/deck-components/FooterLegend.ts:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L65)

##### onGamepadDirection?

> `Function`

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](FooterLegend#gamepadevent) |

####### Returns

`void`

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[onGamepadDirection](FooterLegend#ongamepaddirection)

Defined in:  [src/deck-components/FooterLegend.ts:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L63)

##### onGamepadFocus?

> `Function`

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](FooterLegend#gamepadevent) |

####### Returns

`void`

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[onGamepadFocus](FooterLegend#ongamepadfocus)

Defined in:  [src/deck-components/FooterLegend.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L64)

##### onMenuActionDescription?

> `ReactNode`

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[onMenuActionDescription](FooterLegend#onmenuactiondescription)

Defined in:  [src/deck-components/FooterLegend.ts:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L56)

##### onMenuButton?

> `Function`

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](FooterLegend#gamepadevent) |

####### Returns

`void`

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[onMenuButton](FooterLegend#onmenubutton)

Defined in:  [src/deck-components/FooterLegend.ts:66](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L66)

##### onOKActionDescription?

> `ReactNode`

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[onOKActionDescription](FooterLegend#onokactiondescription)

Defined in:  [src/deck-components/FooterLegend.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L52)

##### onOKButton?

> `Function`

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](FooterLegend#gamepadevent) |

####### Returns

`void`

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[onOKButton](FooterLegend#onokbutton)

Defined in:  [src/deck-components/FooterLegend.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L59)

##### onOptionsActionDescription?

> `ReactNode`

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[onOptionsActionDescription](FooterLegend#onoptionsactiondescription)

Defined in:  [src/deck-components/FooterLegend.ts:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L55)

##### onOptionsButton?

> `Function`

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](FooterLegend#gamepadevent) |

####### Returns

`void`

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[onOptionsButton](FooterLegend#onoptionsbutton)

Defined in:  [src/deck-components/FooterLegend.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L62)

##### onSecondaryActionDescription?

> `ReactNode`

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[onSecondaryActionDescription](FooterLegend#onsecondaryactiondescription)

Defined in:  [src/deck-components/FooterLegend.ts:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L54)

##### onSecondaryButton?

> `Function`

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`GamepadEvent`](FooterLegend#gamepadevent) |

####### Returns

`void`

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[onSecondaryButton](FooterLegend#onsecondarybutton)

Defined in:  [src/deck-components/FooterLegend.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L61)

##### style?

> `CSSProperties`

Inherited from: [DialogCommonProps](Dialog#dialogcommonprops).[style](Dialog#style)

Defined in:  [src/deck-components/Dialog.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L7)

##### tooltip?

> `string`

Defined in:  [src/deck-components/DialogCheckbox.tsx:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L12)

#### Methods

##### onChange()?

###### Signature

```ts
Optional onChange(checked: boolean): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `checked` | `boolean` |

###### Returns

`void`

Defined in:  [src/deck-components/DialogCheckbox.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L8)

##### onClick()?

###### Signature

```ts
Optional onClick(evt: Event): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`Event`]( https://developer.mozilla.org/en-US/docs/Web/API/Event ) |

###### Returns

`void`

Defined in:  [src/deck-components/DialogCheckbox.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L18)

## Functions

### DialogCheckbox()

#### Signature

```ts
DialogCheckbox(props: PropsWithChildren<DialogCheckboxProps>, context?: any): null | ReactElement<any, any>;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[`DialogCheckboxProps`](DialogCheckbox#dialogcheckboxprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544
