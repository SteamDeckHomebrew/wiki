---
title: "deck-components/Field"
editor: "markdown"
published: true
---

# deck-components/Field

## Index

### Interfaces

- FieldProps

### Functions

- Field

## Interfaces

### FieldProps

#### Hierarchy

- [`FooterLegendProps`](FooterLegend#footerlegendprops).**FieldProps**

#### Index

##### Properties

- actionDescriptionMap
- bottomSeparator
- childrenContainerWidth
- childrenLayout
- className
- description
- disabled
- focusable
- highlightOnFocus
- icon
- indentLevel
- inlineWrap
- label
- onActivate
- onButtonDown
- onButtonUp
- onCancelActionDescription
- onCancelButton
- onClick
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
- padding
- spacingBetweenLabelAndChild
- verticalAlignment

#### Properties

##### actionDescriptionMap?

> [`ActionDescriptionMap`](FooterLegend#actiondescriptionmap)

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[actionDescriptionMap](FooterLegend#actiondescriptionmap)

Defined in:  [src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L51)

##### bottomSeparator?

> `"standard"` \| `"thick"` \| `"none"`

Defined in:  [src/deck-components/Field.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L8)

##### childrenContainerWidth?

> `"min"` \| `"max"` \| `"fixed"`

Defined in:  [src/deck-components/Field.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L14)

##### childrenLayout?

> `"below"` \| `"inline"`

Defined in:  [src/deck-components/Field.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L13)

##### className?

> `string`

Defined in:  [src/deck-components/Field.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L17)

##### description?

> `ReactNode`

Defined in:  [src/deck-components/Field.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L9)

##### disabled?

> `boolean`

Defined in:  [src/deck-components/Field.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L10)

##### focusable?

> `boolean`

Defined in:  [src/deck-components/Field.tsx:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L21)

##### highlightOnFocus?

> `boolean`

Defined in:  [src/deck-components/Field.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L18)

##### icon?

> `ReactNode`

Defined in:  [src/deck-components/Field.tsx:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L11)

##### indentLevel?

> `number`

Defined in:  [src/deck-components/Field.tsx:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L19)

##### inlineWrap?

> `"keep-inline"` \| `"shift-children-below"`

Defined in:  [src/deck-components/Field.tsx:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L12)

##### label?

> `ReactNode`

Defined in:  [src/deck-components/Field.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L7)

##### onActivate?

> `Function`

###### Type declaration

####### Signature

```ts
(e: MouseEvent | CustomEvent<any>): void;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `MouseEvent` \| [`CustomEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/CustomEvent )\<`any`\> |

####### Returns

`void`

Defined in:  [src/deck-components/Field.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L22)

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

##### onClick?

> `Function`

###### Type declaration

####### Signature

```ts
(e: MouseEvent | CustomEvent<any>): void;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `MouseEvent` \| [`CustomEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/CustomEvent )\<`any`\> |

####### Returns

`void`

Defined in:  [src/deck-components/Field.tsx:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L23)

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

##### padding?

> `"standard"` \| `"none"` \| `"compact"`

Defined in:  [src/deck-components/Field.tsx:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L16)

##### spacingBetweenLabelAndChild?

> `"none"`

Defined in:  [src/deck-components/Field.tsx:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L15)

##### verticalAlignment?

> `"none"` \| `"center"`

Defined in:  [src/deck-components/Field.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L20)

## Functions

### Field()

#### Signature

```ts
Field(props: PropsWithChildren<FieldProps & RefAttributes<HTMLDivElement>>, context?: any): null | ReactElement<any, any>;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[`FieldProps`](Field#fieldprops) & `RefAttributes`\<[`HTMLDivElement`]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLDivElement )\>\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544
