# deck-components/Button

## Index

### Interfaces

- ButtonProps

### Functions

- Button

## Interfaces

### ButtonProps

#### Hierarchy

- [`DialogButtonProps`](Dialog#dialogbuttonprops).**ButtonProps**

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

##### actionDescriptionMap?

> [`ActionDescriptionMap`](FooterLegend#actiondescriptionmap)

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[actionDescriptionMap](Dialog#actiondescriptionmap)

Defined in:  [src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L51)

##### className?

> `string`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[className](Dialog#classname)

Defined in:  [src/deck-components/Dialog.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L8)

##### disabled?

> `boolean`

Disables the button - assigned `on*` methods will not be invoked if clicked.

###### Note

Depending on where it is, it might still get focus. In such case it can be 
partially disabled separately.

###### See

focusable.

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[disabled](Dialog#disabled)

Defined in:  [src/deck-components/Dialog.tsx:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L29)

##### focusable?

> `boolean`

Enables/disables the navigation based focus on button - you won't be able to navigate to
it via the gamepad or keyboard.

###### Note

If set to `false`, it still can be clicked and **WILL** become focused until navigated away.
Depending on the context of where the button is, even a disabled button can focused.

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[focusable](Dialog#focusable)

Defined in:  [src/deck-components/Dialog.tsx:39](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L39)

##### noFocusRing?

> `boolean`

Enables/disables the focus around the button.

###### Note

Default value depends on context, so setting it to `false` will enable it.

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[noFocusRing](Dialog#nofocusring)

Defined in:  [src/deck-components/Dialog.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L18)

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

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onButtonDown](Dialog#onbuttondown)

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

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onButtonUp](Dialog#onbuttonup)

Defined in:  [src/deck-components/FooterLegend.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L58)

##### onCancelActionDescription?

> `ReactNode`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onCancelActionDescription](Dialog#oncancelactiondescription)

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

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onCancelButton](Dialog#oncancelbutton)

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

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onGamepadBlur](Dialog#ongamepadblur)

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

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onGamepadDirection](Dialog#ongamepaddirection)

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

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onGamepadFocus](Dialog#ongamepadfocus)

Defined in:  [src/deck-components/FooterLegend.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L64)

##### onMenuActionDescription?

> `ReactNode`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onMenuActionDescription](Dialog#onmenuactiondescription)

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

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onMenuButton](Dialog#onmenubutton)

Defined in:  [src/deck-components/FooterLegend.ts:66](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L66)

##### onOKActionDescription?

> `ReactNode`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onOKActionDescription](Dialog#onokactiondescription)

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

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onOKButton](Dialog#onokbutton)

Defined in:  [src/deck-components/FooterLegend.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L59)

##### onOptionsActionDescription?

> `ReactNode`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onOptionsActionDescription](Dialog#onoptionsactiondescription)

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

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onOptionsButton](Dialog#onoptionsbutton)

Defined in:  [src/deck-components/FooterLegend.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L62)

##### onSecondaryActionDescription?

> `ReactNode`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onSecondaryActionDescription](Dialog#onsecondaryactiondescription)

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

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onSecondaryButton](Dialog#onsecondarybutton)

Defined in:  [src/deck-components/FooterLegend.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L61)

##### style?

> `CSSProperties`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[style](Dialog#style)

Defined in:  [src/deck-components/Dialog.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L7)

#### Methods

##### onClick()?

###### Signature

```ts
Optional onClick(e: MouseEvent): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | [`MouseEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent ) |

###### Returns

`void`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onClick](Dialog#onclick)

Defined in:  [src/deck-components/Dialog.tsx:41](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L41)

##### onMouseDown()?

###### Signature

```ts
Optional onMouseDown(e: MouseEvent): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | [`MouseEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent ) |

###### Returns

`void`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onMouseDown](Dialog#onmousedown)

Defined in:  [src/deck-components/Dialog.tsx:45](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L45)

##### onMouseUp()?

###### Signature

```ts
Optional onMouseUp(e: MouseEvent): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | [`MouseEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent ) |

###### Returns

`void`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onMouseUp](Dialog#onmouseup)

Defined in:  [src/deck-components/Dialog.tsx:46](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L46)

##### onPointerCancel()?

###### Signature

```ts
Optional onPointerCancel(e: PointerEvent): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | [`PointerEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/PointerEvent ) |

###### Returns

`void`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onPointerCancel](Dialog#onpointercancel)

Defined in:  [src/deck-components/Dialog.tsx:44](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L44)

##### onPointerDown()?

###### Signature

```ts
Optional onPointerDown(e: PointerEvent): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | [`PointerEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/PointerEvent ) |

###### Returns

`void`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onPointerDown](Dialog#onpointerdown)

Defined in:  [src/deck-components/Dialog.tsx:42](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L42)

##### onPointerUp()?

###### Signature

```ts
Optional onPointerUp(e: PointerEvent): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | [`PointerEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/PointerEvent ) |

###### Returns

`void`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onPointerUp](Dialog#onpointerup)

Defined in:  [src/deck-components/Dialog.tsx:43](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L43)

##### onSubmit()?

###### Signature

```ts
Optional onSubmit(e: SubmitEvent): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | [`SubmitEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/SubmitEvent ) |

###### Returns

`void`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onSubmit](Dialog#onsubmit)

Defined in:  [src/deck-components/Dialog.tsx:50](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L50)

##### onTouchCancel()?

###### Signature

```ts
Optional onTouchCancel(e: TouchEvent): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | [`TouchEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/TouchEvent ) |

###### Returns

`void`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onTouchCancel](Dialog#ontouchcancel)

Defined in:  [src/deck-components/Dialog.tsx:49](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L49)

##### onTouchEnd()?

###### Signature

```ts
Optional onTouchEnd(e: TouchEvent): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | [`TouchEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/TouchEvent ) |

###### Returns

`void`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onTouchEnd](Dialog#ontouchend)

Defined in:  [src/deck-components/Dialog.tsx:48](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L48)

##### onTouchStart()?

###### Signature

```ts
Optional onTouchStart(e: TouchEvent): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | [`TouchEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/TouchEvent ) |

###### Returns

`void`

Inherited from: [DialogButtonProps](Dialog#dialogbuttonprops).[onTouchStart](Dialog#ontouchstart)

Defined in:  [src/deck-components/Dialog.tsx:47](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Dialog.tsx#L47)

## Functions

### Button()

#### Signature

```ts
Button(props: PropsWithChildren<ButtonProps>, context?: any): null | ReactElement<any, any>;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[`ButtonProps`](Button#buttonprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544
