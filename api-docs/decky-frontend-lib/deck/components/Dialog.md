---
title: "deck-components/Dialog"
editor: "markdown"
published: true
---

# deck-components/Dialog

## Index

### Interfaces

- DialogButtonProps
- DialogCommonProps

### Functions

- DialogBody
- DialogBodyText
- DialogButton
- DialogButtonPrimary
- DialogButtonSecondary
- DialogControlsSection
- DialogControlsSectionHeader
- DialogFooter
- DialogHeader
- DialogLabel
- DialogSubHeader

## Interfaces

### DialogButtonProps

#### Hierarchy

- [DialogCommonProps](deck/components/Dialog#dialogcommonprops).[FooterLegendProps](deck/components/FooterLegend#footerlegendprops).**DialogButtonProps**

#### Index

##### Properties

- actionDescriptionMap
- className
- disabled
- focusable
- noFocusRing
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

##### Methods

- onClick
- onMouseDown
- onMouseUp
- onPointerCancel
- onPointerDown
- onPointerUp
- onSubmit
- onTouchCancel
- onTouchEnd
- onTouchStart

#### Properties

##### actionDescriptionMap

```ts
actionDescriptionMap?: ActionDescriptionMap
```

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[actionDescriptionMap](deck/components/FooterLegend#actiondescriptionmap)

Defined in:  [src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L51)

##### className

```ts
className?: string
```

Inherited from: [DialogCommonProps](deck/components/Dialog#dialogcommonprops).[className](deck/components/Dialog#classname)

Defined in:  [src/deck-components/Dialog.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L8)

##### disabled

```ts
disabled?: boolean
```

Disables the button - assigned `on*` methods will not be invoked if clicked.

###### Note

Depending on where it is, it might still get focus. In such case it can be 
partially disabled separately.

###### See

focusable.

Defined in:  [src/deck-components/Dialog.tsx:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L29)

##### focusable

```ts
focusable?: boolean
```

Enables/disables the navigation based focus on button - you won't be able to navigate to
it via the gamepad or keyboard.

###### Note

If set to `false`, it still can be clicked and **WILL** become focused until navigated away.
Depending on the context of where the button is, even a disabled button can focused.

Defined in:  [src/deck-components/Dialog.tsx:39](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L39)

##### noFocusRing

```ts
noFocusRing?: boolean
```

Enables/disables the focus around the button.

###### Note

Default value depends on context, so setting it to `false` will enable it.

Defined in:  [src/deck-components/Dialog.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L18)

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

#### Methods

##### onClick()

###### Signature

```ts
Optional onClick(e: MouseEvent): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `MouseEvent` |

###### Returns

`void`

Defined in:  [src/deck-components/Dialog.tsx:41](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L41)

##### onMouseDown()

###### Signature

```ts
Optional onMouseDown(e: MouseEvent): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `MouseEvent` |

###### Returns

`void`

Defined in:  [src/deck-components/Dialog.tsx:45](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L45)

##### onMouseUp()

###### Signature

```ts
Optional onMouseUp(e: MouseEvent): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `MouseEvent` |

###### Returns

`void`

Defined in:  [src/deck-components/Dialog.tsx:46](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L46)

##### onPointerCancel()

###### Signature

```ts
Optional onPointerCancel(e: PointerEvent): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `PointerEvent` |

###### Returns

`void`

Defined in:  [src/deck-components/Dialog.tsx:44](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L44)

##### onPointerDown()

###### Signature

```ts
Optional onPointerDown(e: PointerEvent): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `PointerEvent` |

###### Returns

`void`

Defined in:  [src/deck-components/Dialog.tsx:42](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L42)

##### onPointerUp()

###### Signature

```ts
Optional onPointerUp(e: PointerEvent): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `PointerEvent` |

###### Returns

`void`

Defined in:  [src/deck-components/Dialog.tsx:43](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L43)

##### onSubmit()

###### Signature

```ts
Optional onSubmit(e: SubmitEvent): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `SubmitEvent` |

###### Returns

`void`

Defined in:  [src/deck-components/Dialog.tsx:50](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L50)

##### onTouchCancel()

###### Signature

```ts
Optional onTouchCancel(e: TouchEvent): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `TouchEvent` |

###### Returns

`void`

Defined in:  [src/deck-components/Dialog.tsx:49](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L49)

##### onTouchEnd()

###### Signature

```ts
Optional onTouchEnd(e: TouchEvent): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `TouchEvent` |

###### Returns

`void`

Defined in:  [src/deck-components/Dialog.tsx:48](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L48)

##### onTouchStart()

###### Signature

```ts
Optional onTouchStart(e: TouchEvent): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `TouchEvent` |

###### Returns

`void`

Defined in:  [src/deck-components/Dialog.tsx:47](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L47)

---

### DialogCommonProps

#### Hierarchy

- `RefAttributes`\<[HTMLDivElement]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLDivElement )\>.**DialogCommonProps**

#### Index

##### Properties

- className
- style

#### Properties

##### className

```ts
className?: string
```

Defined in:  [src/deck-components/Dialog.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L8)

##### style

```ts
style?: CSSProperties
```

Defined in:  [src/deck-components/Dialog.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L7)

## Functions

### DialogBody()

#### Signature

```ts
DialogBody(props: PropsWithChildren<DialogCommonProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[DialogCommonProps](deck/components/Dialog#dialogcommonprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### DialogBodyText()

#### Signature

```ts
DialogBodyText(props: PropsWithChildren<DialogCommonProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[DialogCommonProps](deck/components/Dialog#dialogcommonprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### DialogButton()

#### Signature

```ts
DialogButton(props: PropsWithChildren<DialogButtonProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[DialogButtonProps](deck/components/Dialog#dialogbuttonprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### DialogButtonPrimary()

#### Signature

```ts
DialogButtonPrimary(props: PropsWithChildren<DialogButtonProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[DialogButtonProps](deck/components/Dialog#dialogbuttonprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### DialogButtonSecondary()

#### Signature

```ts
DialogButtonSecondary(props: PropsWithChildren<DialogButtonProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[DialogButtonProps](deck/components/Dialog#dialogbuttonprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### DialogControlsSection()

#### Signature

```ts
DialogControlsSection(props: PropsWithChildren<DialogCommonProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[DialogCommonProps](deck/components/Dialog#dialogcommonprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### DialogControlsSectionHeader()

#### Signature

```ts
DialogControlsSectionHeader(props: PropsWithChildren<DialogCommonProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[DialogCommonProps](deck/components/Dialog#dialogcommonprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### DialogFooter()

#### Signature

```ts
DialogFooter(props: PropsWithChildren<DialogCommonProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[DialogCommonProps](deck/components/Dialog#dialogcommonprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### DialogHeader()

#### Signature

```ts
DialogHeader(props: PropsWithChildren<DialogCommonProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[DialogCommonProps](deck/components/Dialog#dialogcommonprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### DialogLabel()

#### Signature

```ts
DialogLabel(props: PropsWithChildren<DialogCommonProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[DialogCommonProps](deck/components/Dialog#dialogcommonprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### DialogSubHeader()

#### Signature

```ts
DialogSubHeader(props: PropsWithChildren<DialogCommonProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[DialogCommonProps](deck/components/Dialog#dialogcommonprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544
