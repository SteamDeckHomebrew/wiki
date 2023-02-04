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

- [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).**FieldProps**

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

Defined in:  [src/deck-components/Field.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L8)

##### childrenContainerWidth

```ts
childrenContainerWidth?: "min" | "max" | "fixed"
```

Defined in:  [src/deck-components/Field.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L14)

##### childrenLayout

```ts
childrenLayout?: "below" | "inline"
```

Defined in:  [src/deck-components/Field.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L13)

##### className

```ts
className?: string
```

Defined in:  [src/deck-components/Field.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L17)

##### description

```ts
description?: ReactNode
```

Defined in:  [src/deck-components/Field.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L9)

##### disabled

```ts
disabled?: boolean
```

Defined in:  [src/deck-components/Field.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L10)

##### focusable

```ts
focusable?: boolean
```

Defined in:  [src/deck-components/Field.tsx:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L21)

##### highlightOnFocus

```ts
highlightOnFocus?: boolean
```

Defined in:  [src/deck-components/Field.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L18)

##### icon

```ts
icon?: ReactNode
```

Defined in:  [src/deck-components/Field.tsx:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L11)

##### indentLevel

```ts
indentLevel?: number
```

Defined in:  [src/deck-components/Field.tsx:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L19)

##### inlineWrap

```ts
inlineWrap?: "keep-inline" | "shift-children-below"
```

Defined in:  [src/deck-components/Field.tsx:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L12)

##### label

```ts
label?: ReactNode
```

Defined in:  [src/deck-components/Field.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L7)

##### onActivate

```ts
onActivate?: Function
```

###### Type declaration

####### Signature

```ts
(e: MouseEvent | CustomEvent<any>): void
```

> ####### Parameters
>
> | Name | Type |
> | :------ | :------ |
> | `e` | `MouseEvent` \| [CustomEvent]( https://developer.mozilla.org/en-US/docs/Web/API/CustomEvent )\<`any`\> |
>
> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/Field.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L22)
>

Defined in:  [src/deck-components/Field.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L22)

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

##### onClick

```ts
onClick?: Function
```

###### Type declaration

####### Signature

```ts
(e: MouseEvent | CustomEvent<any>): void
```

> ####### Parameters
>
> | Name | Type |
> | :------ | :------ |
> | `e` | `MouseEvent` \| [CustomEvent]( https://developer.mozilla.org/en-US/docs/Web/API/CustomEvent )\<`any`\> |
>
> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/Field.tsx:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L23)
>

Defined in:  [src/deck-components/Field.tsx:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L23)

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

##### padding

```ts
padding?: "standard" | "none" | "compact"
```

Defined in:  [src/deck-components/Field.tsx:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L16)

##### spacingBetweenLabelAndChild

```ts
spacingBetweenLabelAndChild?: "none"
```

Defined in:  [src/deck-components/Field.tsx:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L15)

##### verticalAlignment

```ts
verticalAlignment?: "none" | "center"
```

Defined in:  [src/deck-components/Field.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Field.tsx#L20)

## Functions

### Field()

#### Signature

```ts
Field(props: PropsWithChildren<FieldProps & RefAttributes<HTMLDivElement>>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[FieldProps](deck/components/Field#fieldprops) & `RefAttributes`\<[HTMLDivElement]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLDivElement )\>\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544
