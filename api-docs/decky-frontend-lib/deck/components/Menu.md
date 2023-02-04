---
title: "deck-components/Menu"
editor: "markdown"
published: true
---

# deck-components/Menu

## Index

### Interfaces

- MenuGroupProps
- MenuItemProps
- MenuProps

### Functions

- Menu
- MenuGroup
- MenuItem
- showContextMenu

## Interfaces

### MenuGroupProps

#### Index

##### Properties

- children
- disabled
- label

#### Properties

##### children

```ts
children?: ReactNode
```

Defined in:  [src/deck-components/Menu.tsx:36](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L36)

##### disabled

```ts
disabled?: boolean
```

Defined in:  [src/deck-components/Menu.tsx:35](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L35)

##### label

```ts
label: string
```

Defined in:  [src/deck-components/Menu.tsx:34](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L34)

---

### MenuItemProps

#### Hierarchy

- [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).**MenuItemProps**

#### Index

##### Properties

- actionDescriptionMap
- bInteractableItem
- bPlayAudio
- children
- disabled
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
- selected
- tone

##### Methods

- onClick
- onMouseEnter
- onMoveRight
- onSelected

#### Properties

##### actionDescriptionMap

```ts
actionDescriptionMap?: ActionDescriptionMap
```

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[actionDescriptionMap](deck/components/FooterLegend#actiondescriptionmap)

Defined in:  [src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L51)

##### bInteractableItem

```ts
bInteractableItem?: boolean
```

Defined in:  [src/deck-components/Menu.tsx:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L54)

##### bPlayAudio

```ts
bPlayAudio?: boolean
```

Defined in:  [src/deck-components/Menu.tsx:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L61)

##### children

```ts
children?: ReactNode
```

Defined in:  [src/deck-components/Menu.tsx:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L63)

##### disabled

```ts
disabled?: boolean
```

Defined in:  [src/deck-components/Menu.tsx:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L60)

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

##### selected

```ts
selected?: boolean
```

Defined in:  [src/deck-components/Menu.tsx:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L59)

##### tone

```ts
tone?: "positive" | "emphasis" | "destructive"
```

Defined in:  [src/deck-components/Menu.tsx:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L62)

#### Methods

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

Defined in:  [src/deck-components/Menu.tsx:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L55)

##### onMouseEnter()

###### Signature

```ts
Optional onMouseEnter(evt: MouseEvent): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | `MouseEvent` |

###### Returns

`void`

Defined in:  [src/deck-components/Menu.tsx:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L57)

##### onMoveRight()

###### Signature

```ts
Optional onMoveRight(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Menu.tsx:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L58)

##### onSelected()

###### Signature

```ts
Optional onSelected(evt: Event): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [Event]( https://developer.mozilla.org/en-US/docs/Web/API/Event ) |

###### Returns

`void`

Defined in:  [src/deck-components/Menu.tsx:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L56)

---

### MenuProps

#### Hierarchy

- [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).**MenuProps**

#### Index

##### Properties

- actionDescriptionMap
- cancelText
- children
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

##### Methods

- onCancel

#### Properties

##### actionDescriptionMap

```ts
actionDescriptionMap?: ActionDescriptionMap
```

Inherited from: [FooterLegendProps](deck/components/FooterLegend#footerlegendprops).[actionDescriptionMap](deck/components/FooterLegend#actiondescriptionmap)

Defined in:  [src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L51)

##### cancelText

```ts
cancelText?: string
```

Defined in:  [src/deck-components/Menu.tsx:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L19)

##### children

```ts
children?: ReactNode
```

Defined in:  [src/deck-components/Menu.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L20)

##### label

```ts
label: string
```

Defined in:  [src/deck-components/Menu.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L17)

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

#### Methods

##### onCancel()

###### Signature

```ts
Optional onCancel(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Menu.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L18)

## Functions

### Menu()

#### Signature

```ts
Menu(props: PropsWithChildren<MenuProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[MenuProps](deck/components/Menu#menuprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### MenuGroup()

#### Signature

```ts
MenuGroup(props: PropsWithChildren<MenuGroupProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[MenuGroupProps](deck/components/Menu#menugroupprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### MenuItem()

#### Signature

```ts
MenuItem(props: PropsWithChildren<MenuItemProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[MenuItemProps](deck/components/Menu#menuitemprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### showContextMenu()

#### Signature

```ts
showContextMenu(children: ReactNode, parent?: EventTarget): void
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `children` | `ReactNode` |
| `parent?` | [EventTarget]( https://developer.mozilla.org/en-US/docs/Web/API/EventTarget ) |

#### Returns

`void`

Defined in:  [src/deck-components/Menu.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L7)
