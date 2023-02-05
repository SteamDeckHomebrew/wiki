---
title: "deck-components/Focusable"
editor: "markdown"
published: true
---

# deck-components/Focusable

## Index

### Interfaces

- FocusableProps

### Functions

- Focusable

## Interfaces

### FocusableProps

#### Hierarchy

- `HTMLAttributes`\<[`HTMLDivElement`]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLDivElement )\>.[`FooterLegendProps`](FooterLegend#footerlegendprops).**FocusableProps**

#### Index

##### Properties

- actionDescriptionMap
- children
- flow-children
- focusClassName
- focusWithinClassName
- noFocusRing
- onActivate
- onButtonDown
- onButtonUp
- onCancel
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

#### Properties

##### actionDescriptionMap?

> [`ActionDescriptionMap`](FooterLegend#actiondescriptionmap)

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[actionDescriptionMap](FooterLegend#actiondescriptionmap)

Defined in:  [src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L51)

##### children

> `ReactNode`

Overrides: HTMLAttributes.children

Defined in:  [src/deck-components/Focusable.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Focusable.tsx#L7)

##### flow-children?

> `string`

Defined in:  [src/deck-components/Focusable.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Focusable.tsx#L8)

##### focusClassName?

> `string`

Defined in:  [src/deck-components/Focusable.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Focusable.tsx#L9)

##### focusWithinClassName?

> `string`

Defined in:  [src/deck-components/Focusable.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Focusable.tsx#L10)

##### noFocusRing?

> `boolean`

Defined in:  [src/deck-components/Focusable.tsx:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Focusable.tsx#L11)

##### onActivate?

> `Function`

###### Type declaration

####### Signature

```ts
(e: CustomEvent<any>): void;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `e` | [`CustomEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/CustomEvent )\<`any`\> |

####### Returns

`void`

Defined in:  [src/deck-components/Focusable.tsx:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Focusable.tsx#L12)

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

##### onCancel?

> `Function`

###### Type declaration

####### Signature

```ts
(e: CustomEvent<any>): void;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `e` | [`CustomEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/CustomEvent )\<`any`\> |

####### Returns

`void`

Defined in:  [src/deck-components/Focusable.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Focusable.tsx#L13)

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

## Functions

### Focusable()

#### Signature

```ts
Focusable(props: FocusableProps & RefAttributes<HTMLDivElement>, context?: any): null | ReactElement<any, any>;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`FocusableProps`](Focusable#focusableprops) & `RefAttributes`\<[`HTMLDivElement`]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLDivElement )\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:554
