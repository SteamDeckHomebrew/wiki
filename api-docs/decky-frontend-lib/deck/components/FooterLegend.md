---
title: "deck-components/FooterLegend"
editor: "markdown"
published: true
---

# deck-components/FooterLegend

## Index

### Enumerations

- GamepadButton
- NavEntryPositionPreferences

### Interfaces

- FooterLegendProps
- GamepadEventDetail

### Type Aliases

- ActionDescriptionMap
- GamepadEvent

## Enumerations

### GamepadButton

#### Index

##### Enumeration Members

- BUMPER_LEFT
- BUMPER_RIGHT
- CANCEL
- DIR_DOWN
- DIR_LEFT
- DIR_RIGHT
- DIR_UP
- INVALID
- LPAD_CLICK
- LPAD_TOUCH
- LSTICK_CLICK
- LSTICK_TOUCH
- OK
- OPTIONS
- REAR_LEFT_LOWER
- REAR_LEFT_UPPER
- REAR_RIGHT_LOWER
- REAR_RIGHT_UPPER
- RPAD_CLICK
- RPAD_TOUCH
- RSTICK_CLICK
- RSTICK_TOUCH
- SECONDARY
- SELECT
- START
- STEAM_GUIDE
- STEAM_QUICK_MENU
- TRIGGER_LEFT
- TRIGGER_RIGHT

#### Enumeration Members

##### BUMPER\_LEFT

```ts
BUMPER_LEFT = 5
```

Defined in:  [src/deck-components/FooterLegend.ts:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L9)

##### BUMPER\_RIGHT

```ts
BUMPER_RIGHT = 6
```

Defined in:  [src/deck-components/FooterLegend.ts:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L10)

##### CANCEL

```ts
CANCEL = 2
```

Defined in:  [src/deck-components/FooterLegend.ts:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L6)

##### DIR\_DOWN

```ts
DIR_DOWN = 10
```

Defined in:  [src/deck-components/FooterLegend.ts:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L14)

##### DIR\_LEFT

```ts
DIR_LEFT = 11
```

Defined in:  [src/deck-components/FooterLegend.ts:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L15)

##### DIR\_RIGHT

```ts
DIR_RIGHT = 12
```

Defined in:  [src/deck-components/FooterLegend.ts:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L16)

##### DIR\_UP

```ts
DIR_UP = 9
```

Defined in:  [src/deck-components/FooterLegend.ts:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L13)

##### INVALID

```ts
INVALID = 0
```

Defined in:  [src/deck-components/FooterLegend.ts:4](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L4)

##### LPAD\_CLICK

```ts
LPAD_CLICK = 20
```

Defined in:  [src/deck-components/FooterLegend.ts:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L24)

##### LPAD\_TOUCH

```ts
LPAD_TOUCH = 19
```

Defined in:  [src/deck-components/FooterLegend.ts:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L23)

##### LSTICK\_CLICK

```ts
LSTICK_CLICK = 15
```

Defined in:  [src/deck-components/FooterLegend.ts:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L19)

##### LSTICK\_TOUCH

```ts
LSTICK_TOUCH = 17
```

Defined in:  [src/deck-components/FooterLegend.ts:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L21)

##### OK

```ts
OK = 1
```

Defined in:  [src/deck-components/FooterLegend.ts:5](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L5)

##### OPTIONS

```ts
OPTIONS = 4
```

Defined in:  [src/deck-components/FooterLegend.ts:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L8)

##### REAR\_LEFT\_LOWER

```ts
REAR_LEFT_LOWER = 24
```

Defined in:  [src/deck-components/FooterLegend.ts:28](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L28)

##### REAR\_LEFT\_UPPER

```ts
REAR_LEFT_UPPER = 23
```

Defined in:  [src/deck-components/FooterLegend.ts:27](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L27)

##### REAR\_RIGHT\_LOWER

```ts
REAR_RIGHT_LOWER = 26
```

Defined in:  [src/deck-components/FooterLegend.ts:30](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L30)

##### REAR\_RIGHT\_UPPER

```ts
REAR_RIGHT_UPPER = 25
```

Defined in:  [src/deck-components/FooterLegend.ts:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L29)

##### RPAD\_CLICK

```ts
RPAD_CLICK = 22
```

Defined in:  [src/deck-components/FooterLegend.ts:26](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L26)

##### RPAD\_TOUCH

```ts
RPAD_TOUCH = 21
```

Defined in:  [src/deck-components/FooterLegend.ts:25](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L25)

##### RSTICK\_CLICK

```ts
RSTICK_CLICK = 16
```

Defined in:  [src/deck-components/FooterLegend.ts:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L20)

##### RSTICK\_TOUCH

```ts
RSTICK_TOUCH = 18
```

Defined in:  [src/deck-components/FooterLegend.ts:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L22)

##### SECONDARY

```ts
SECONDARY = 3
```

Defined in:  [src/deck-components/FooterLegend.ts:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L7)

##### SELECT

```ts
SELECT = 13
```

Defined in:  [src/deck-components/FooterLegend.ts:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L17)

##### START

```ts
START = 14
```

Defined in:  [src/deck-components/FooterLegend.ts:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L18)

##### STEAM\_GUIDE

```ts
STEAM_GUIDE = 27
```

Defined in:  [src/deck-components/FooterLegend.ts:31](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L31)

##### STEAM\_QUICK\_MENU

```ts
STEAM_QUICK_MENU = 28
```

Defined in:  [src/deck-components/FooterLegend.ts:32](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L32)

##### TRIGGER\_LEFT

```ts
TRIGGER_LEFT = 7
```

Defined in:  [src/deck-components/FooterLegend.ts:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L11)

##### TRIGGER\_RIGHT

```ts
TRIGGER_RIGHT = 8
```

Defined in:  [src/deck-components/FooterLegend.ts:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L12)

---

### NavEntryPositionPreferences

#### Index

##### Enumeration Members

- FIRST
- LAST
- MAINTAIN_X
- MAINTAIN_Y
- PREFERRED_CHILD

#### Enumeration Members

##### FIRST

```ts
FIRST = number
```

Defined in:  [src/deck-components/FooterLegend.ts:35](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L35)

##### LAST

```ts
LAST = number
```

Defined in:  [src/deck-components/FooterLegend.ts:36](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L36)

##### MAINTAIN\_X

```ts
MAINTAIN_X = number
```

Defined in:  [src/deck-components/FooterLegend.ts:37](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L37)

##### MAINTAIN\_Y

```ts
MAINTAIN_Y = number
```

Defined in:  [src/deck-components/FooterLegend.ts:38](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L38)

##### PREFERRED\_CHILD

```ts
PREFERRED_CHILD = number
```

Defined in:  [src/deck-components/FooterLegend.ts:39](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L39)

## Interfaces

### FooterLegendProps

#### Hierarchy

- [DialogButtonProps](deck/components/Dialog#dialogbuttonprops)
- [DialogCheckboxProps](deck/components/DialogCheckbox#dialogcheckboxprops)
- [FieldProps](deck/components/Field#fieldprops)
- [FocusableProps](deck/components/Focusable#focusableprops)
- [MenuProps](deck/components/Menu#menuprops)
- [MenuItemProps](deck/components/Menu#menuitemprops)

#### Index

##### Properties

- actionDescriptionMap
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

#### Properties

##### actionDescriptionMap

```ts
actionDescriptionMap?: ActionDescriptionMap
```

Defined in:  [src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L51)

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

Defined in:  [src/deck-components/FooterLegend.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L58)

##### onCancelActionDescription

```ts
onCancelActionDescription?: ReactNode
```

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

Defined in:  [src/deck-components/FooterLegend.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L64)

##### onMenuActionDescription

```ts
onMenuActionDescription?: ReactNode
```

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

Defined in:  [src/deck-components/FooterLegend.ts:66](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L66)

##### onOKActionDescription

```ts
onOKActionDescription?: ReactNode
```

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

Defined in:  [src/deck-components/FooterLegend.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L59)

##### onOptionsActionDescription

```ts
onOptionsActionDescription?: ReactNode
```

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

Defined in:  [src/deck-components/FooterLegend.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L62)

##### onSecondaryActionDescription

```ts
onSecondaryActionDescription?: ReactNode
```

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

Defined in:  [src/deck-components/FooterLegend.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L61)

---

### GamepadEventDetail

#### Index

##### Properties

- button
- is_repeat
- source

#### Properties

##### button

```ts
button: number
```

Defined in:  [src/deck-components/FooterLegend.ts:42](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L42)

##### is\_repeat

```ts
is_repeat?: boolean
```

Defined in:  [src/deck-components/FooterLegend.ts:43](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L43)

##### source

```ts
source: number
```

Defined in:  [src/deck-components/FooterLegend.ts:44](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L44)

## Type Aliases

### ActionDescriptionMap

```ts
ActionDescriptionMap: { [key in GamepadButton]?: ReactNode }
```

Defined in:  [src/deck-components/FooterLegend.ts:46](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L46)

---

### GamepadEvent

```ts
GamepadEvent: CustomEvent<GamepadEventDetail>
```

Defined in:  [src/deck-components/FooterLegend.ts:49](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L49)
