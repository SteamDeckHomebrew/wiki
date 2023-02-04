---
title: "deck-components/DialogCheckbox"
editor: "markdown"
published: true
---

# deck-components/DialogCheckbox

## Index

### Interfaces

- DialogCheckboxProps

### Functions

- DialogCheckbox

## Interfaces

### DialogCheckboxProps

#### Hierarchy

- [DialogCommonProps](deck/components/Dialog#dialogcommonprops).[FooterLegendProps](deck/components/FooterLegend#footerlegendprops).**DialogCheckboxProps**

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

##### actionDescriptionMap

```ts
actionDescriptionMap?: ActionDescriptionMap
```

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[actionDescriptionMap](deck/components/FooterLegend#actiondescriptionmap)

Defined in:  [src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L51)

##### bottomSeparator

```ts
bottomSeparator?: "standard" | "thick" | "none"
```

Defined in:  [src/deck-components/DialogCheckbox.tsx:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L15)

##### checked

```ts
checked?: boolean
```

Defined in:  [src/deck-components/DialogCheckbox.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L17)

##### className

```ts
className?: string
```

Inherited from: [DialogCommonProps](deck/components/Dialog#dialogcommonprops).[className](deck/components/Dialog#classname)

Defined in:  [src/deck-components/Dialog.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L8)

##### color

```ts
color?: string
```

Defined in:  [src/deck-components/DialogCheckbox.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L13)

##### controlled

```ts
controlled?: boolean
```

Defined in:  [src/deck-components/DialogCheckbox.tsx:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L16)

##### description

```ts
description?: ReactNode
```

Defined in:  [src/deck-components/DialogCheckbox.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L10)

##### disabled

```ts
disabled?: boolean
```

Defined in:  [src/deck-components/DialogCheckbox.tsx:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L11)

##### highlightColor

```ts
highlightColor?: string
```

Defined in:  [src/deck-components/DialogCheckbox.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L14)

##### label

```ts
label?: ReactNode
```

Defined in:  [src/deck-components/DialogCheckbox.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L9)

##### onButtonDown

```ts
onButtonDown?: Function
```

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void
```

> ####### Parameters
>
> | Name | Type |
> | :------ | :------ |
> | `evt` | [GamepadEvent](deck/components/FooterLegend#gamepadevent) |
>
> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/FooterLegend.ts:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L57)
>

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[onButtonDown](deck/components/FooterLegend#onbuttondown)

Defined in:  [src/deck-components/FooterLegend.ts:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L57)

##### onButtonUp

```ts
onButtonUp?: Function
```

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void
```

> ####### Parameters
>
> | Name | Type |
> | :------ | :------ |
> | `evt` | [GamepadEvent](deck/components/FooterLegend#gamepadevent) |
>
> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/FooterLegend.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L58)
>

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[onButtonUp](deck/components/FooterLegend#onbuttonup)

Defined in:  [src/deck-components/FooterLegend.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L58)

##### onCancelActionDescription

```ts
onCancelActionDescription?: ReactNode
```

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[onCancelActionDescription](deck/components/FooterLegend#oncancelactiondescription)

Defined in:  [src/deck-components/FooterLegend.ts:53](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L53)

##### onCancelButton

```ts
onCancelButton?: Function
```

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void
```

> ####### Parameters
>
> | Name | Type |
> | :------ | :------ |
> | `evt` | [GamepadEvent](deck/components/FooterLegend#gamepadevent) |
>
> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/FooterLegend.ts:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L60)
>

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[onCancelButton](deck/components/FooterLegend#oncancelbutton)

Defined in:  [src/deck-components/FooterLegend.ts:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L60)

##### onGamepadBlur

```ts
onGamepadBlur?: Function
```

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void
```

> ####### Parameters
>
> | Name | Type |
> | :------ | :------ |
> | `evt` | [GamepadEvent](deck/components/FooterLegend#gamepadevent) |
>
> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/FooterLegend.ts:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L65)
>

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[onGamepadBlur](deck/components/FooterLegend#ongamepadblur)

Defined in:  [src/deck-components/FooterLegend.ts:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L65)

##### onGamepadDirection

```ts
onGamepadDirection?: Function
```

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void
```

> ####### Parameters
>
> | Name | Type |
> | :------ | :------ |
> | `evt` | [GamepadEvent](deck/components/FooterLegend#gamepadevent) |
>
> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/FooterLegend.ts:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L63)
>

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[onGamepadDirection](deck/components/FooterLegend#ongamepaddirection)

Defined in:  [src/deck-components/FooterLegend.ts:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L63)

##### onGamepadFocus

```ts
onGamepadFocus?: Function
```

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void
```

> ####### Parameters
>
> | Name | Type |
> | :------ | :------ |
> | `evt` | [GamepadEvent](deck/components/FooterLegend#gamepadevent) |
>
> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/FooterLegend.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L64)
>

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[onGamepadFocus](deck/components/FooterLegend#ongamepadfocus)

Defined in:  [src/deck-components/FooterLegend.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L64)

##### onMenuActionDescription

```ts
onMenuActionDescription?: ReactNode
```

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[onMenuActionDescription](deck/components/FooterLegend#onmenuactiondescription)

Defined in:  [src/deck-components/FooterLegend.ts:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L56)

##### onMenuButton

```ts
onMenuButton?: Function
```

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void
```

> ####### Parameters
>
> | Name | Type |
> | :------ | :------ |
> | `evt` | [GamepadEvent](deck/components/FooterLegend#gamepadevent) |
>
> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/FooterLegend.ts:66](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L66)
>

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[onMenuButton](deck/components/FooterLegend#onmenubutton)

Defined in:  [src/deck-components/FooterLegend.ts:66](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L66)

##### onOKActionDescription

```ts
onOKActionDescription?: ReactNode
```

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[onOKActionDescription](deck/components/FooterLegend#onokactiondescription)

Defined in:  [src/deck-components/FooterLegend.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L52)

##### onOKButton

```ts
onOKButton?: Function
```

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void
```

> ####### Parameters
>
> | Name | Type |
> | :------ | :------ |
> | `evt` | [GamepadEvent](deck/components/FooterLegend#gamepadevent) |
>
> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/FooterLegend.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L59)
>

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[onOKButton](deck/components/FooterLegend#onokbutton)

Defined in:  [src/deck-components/FooterLegend.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L59)

##### onOptionsActionDescription

```ts
onOptionsActionDescription?: ReactNode
```

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[onOptionsActionDescription](deck/components/FooterLegend#onoptionsactiondescription)

Defined in:  [src/deck-components/FooterLegend.ts:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L55)

##### onOptionsButton

```ts
onOptionsButton?: Function
```

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void
```

> ####### Parameters
>
> | Name | Type |
> | :------ | :------ |
> | `evt` | [GamepadEvent](deck/components/FooterLegend#gamepadevent) |
>
> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/FooterLegend.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L62)
>

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[onOptionsButton](deck/components/FooterLegend#onoptionsbutton)

Defined in:  [src/deck-components/FooterLegend.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L62)

##### onSecondaryActionDescription

```ts
onSecondaryActionDescription?: ReactNode
```

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[onSecondaryActionDescription](deck/components/FooterLegend#onsecondaryactiondescription)

Defined in:  [src/deck-components/FooterLegend.ts:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L54)

##### onSecondaryButton

```ts
onSecondaryButton?: Function
```

###### Type declaration

####### Signature

```ts
(evt: GamepadEvent): void
```

> ####### Parameters
>
> | Name | Type |
> | :------ | :------ |
> | `evt` | [GamepadEvent](deck/components/FooterLegend#gamepadevent) |
>
> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/FooterLegend.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L61)
>

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[onSecondaryButton](deck/components/FooterLegend#onsecondarybutton)

Defined in:  [src/deck-components/FooterLegend.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L61)

##### style

```ts
style?: CSSProperties
```

Inherited from: [DialogCommonProps](deck/components/Dialog#dialogcommonprops).[style](deck/components/Dialog#style)

Defined in:  [src/deck-components/Dialog.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L7)

##### tooltip

```ts
tooltip?: string
```

Defined in:  [src/deck-components/DialogCheckbox.tsx:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L12)

#### Methods

##### onChange()

###### Signature

```ts
Optional onChange(checked: boolean): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `checked` | `boolean` |

###### Returns

`void`

Defined in:  [src/deck-components/DialogCheckbox.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L8)

##### onClick()

###### Signature

```ts
Optional onClick(evt: Event): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [Event]( https://developer.mozilla.org/en-US/docs/Web/API/Event ) |

###### Returns

`void`

Defined in:  [src/deck-components/DialogCheckbox.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/DialogCheckbox.tsx#L18)

## Functions

### DialogCheckbox()

#### Signature

```ts
DialogCheckbox(props: PropsWithChildren<DialogCheckboxProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[DialogCheckboxProps](deck/components/DialogCheckbox#dialogcheckboxprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544
