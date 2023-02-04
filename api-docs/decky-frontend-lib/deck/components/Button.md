---
title: "deck-components/Button"
editor: "markdown"
published: true
---

# deck-components/Button

## Index

### Interfaces

- ButtonProps

### Functions

- Button

## Interfaces

### ButtonProps

#### Hierarchy

- [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).**ButtonProps**

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[actionDescriptionMap](deck/components/Dialog#actiondescriptionmap)

Defined in:  [src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L51)

##### className

```ts
className?: string
```

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[className](deck/components/Dialog#classname)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[disabled](deck/components/Dialog#disabled)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[focusable](deck/components/Dialog#focusable)

Defined in:  [src/deck-components/Dialog.tsx:39](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L39)

##### noFocusRing

```ts
noFocusRing?: boolean
```

Enables/disables the focus around the button.

###### Note

Default value depends on context, so setting it to `false` will enable it.

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[noFocusRing](deck/components/Dialog#nofocusring)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onButtonDown](deck/components/Dialog#onbuttondown)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onButtonUp](deck/components/Dialog#onbuttonup)

Defined in:  [src/deck-components/FooterLegend.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L58)

##### onCancelActionDescription

```ts
onCancelActionDescription?: ReactNode
```

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onCancelActionDescription](deck/components/Dialog#oncancelactiondescription)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onCancelButton](deck/components/Dialog#oncancelbutton)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onGamepadBlur](deck/components/Dialog#ongamepadblur)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onGamepadDirection](deck/components/Dialog#ongamepaddirection)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onGamepadFocus](deck/components/Dialog#ongamepadfocus)

Defined in:  [src/deck-components/FooterLegend.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L64)

##### onMenuActionDescription

```ts
onMenuActionDescription?: ReactNode
```

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onMenuActionDescription](deck/components/Dialog#onmenuactiondescription)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onMenuButton](deck/components/Dialog#onmenubutton)

Defined in:  [src/deck-components/FooterLegend.ts:66](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L66)

##### onOKActionDescription

```ts
onOKActionDescription?: ReactNode
```

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onOKActionDescription](deck/components/Dialog#onokactiondescription)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onOKButton](deck/components/Dialog#onokbutton)

Defined in:  [src/deck-components/FooterLegend.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L59)

##### onOptionsActionDescription

```ts
onOptionsActionDescription?: ReactNode
```

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onOptionsActionDescription](deck/components/Dialog#onoptionsactiondescription)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onOptionsButton](deck/components/Dialog#onoptionsbutton)

Defined in:  [src/deck-components/FooterLegend.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L62)

##### onSecondaryActionDescription

```ts
onSecondaryActionDescription?: ReactNode
```

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onSecondaryActionDescription](deck/components/Dialog#onsecondaryactiondescription)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onSecondaryButton](deck/components/Dialog#onsecondarybutton)

Defined in:  [src/deck-components/FooterLegend.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L61)

##### style

```ts
style?: CSSProperties
```

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[style](deck/components/Dialog#style)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onClick](deck/components/Dialog#onclick)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onMouseDown](deck/components/Dialog#onmousedown)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onMouseUp](deck/components/Dialog#onmouseup)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onPointerCancel](deck/components/Dialog#onpointercancel)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onPointerDown](deck/components/Dialog#onpointerdown)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onPointerUp](deck/components/Dialog#onpointerup)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onSubmit](deck/components/Dialog#onsubmit)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onTouchCancel](deck/components/Dialog#ontouchcancel)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onTouchEnd](deck/components/Dialog#ontouchend)

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

Inherited from: [DialogButtonProps](deck/components/Dialog#dialogbuttonprops).[onTouchStart](deck/components/Dialog#ontouchstart)

Defined in:  [src/deck-components/Dialog.tsx:47](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L47)

## Functions

### Button()

#### Signature

```ts
Button(props: PropsWithChildren<ButtonProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[ButtonProps](deck/components/Button#buttonprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544
