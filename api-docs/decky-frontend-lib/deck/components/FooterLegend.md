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

> `5`

Defined in:  [src/deck-components/FooterLegend.ts:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L9)

##### BUMPER\_RIGHT

> `6`

Defined in:  [src/deck-components/FooterLegend.ts:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L10)

##### CANCEL

> `2`

Defined in:  [src/deck-components/FooterLegend.ts:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L6)

##### DIR\_DOWN

> `10`

Defined in:  [src/deck-components/FooterLegend.ts:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L14)

##### DIR\_LEFT

> `11`

Defined in:  [src/deck-components/FooterLegend.ts:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L15)

##### DIR\_RIGHT

> `12`

Defined in:  [src/deck-components/FooterLegend.ts:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L16)

##### DIR\_UP

> `9`

Defined in:  [src/deck-components/FooterLegend.ts:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L13)

##### INVALID

> `0`

Defined in:  [src/deck-components/FooterLegend.ts:4](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L4)

##### LPAD\_CLICK

> `20`

Defined in:  [src/deck-components/FooterLegend.ts:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L24)

##### LPAD\_TOUCH

> `19`

Defined in:  [src/deck-components/FooterLegend.ts:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L23)

##### LSTICK\_CLICK

> `15`

Defined in:  [src/deck-components/FooterLegend.ts:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L19)

##### LSTICK\_TOUCH

> `17`

Defined in:  [src/deck-components/FooterLegend.ts:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L21)

##### OK

> `1`

Defined in:  [src/deck-components/FooterLegend.ts:5](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L5)

##### OPTIONS

> `4`

Defined in:  [src/deck-components/FooterLegend.ts:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L8)

##### REAR\_LEFT\_LOWER

> `24`

Defined in:  [src/deck-components/FooterLegend.ts:28](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L28)

##### REAR\_LEFT\_UPPER

> `23`

Defined in:  [src/deck-components/FooterLegend.ts:27](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L27)

##### REAR\_RIGHT\_LOWER

> `26`

Defined in:  [src/deck-components/FooterLegend.ts:30](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L30)

##### REAR\_RIGHT\_UPPER

> `25`

Defined in:  [src/deck-components/FooterLegend.ts:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L29)

##### RPAD\_CLICK

> `22`

Defined in:  [src/deck-components/FooterLegend.ts:26](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L26)

##### RPAD\_TOUCH

> `21`

Defined in:  [src/deck-components/FooterLegend.ts:25](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L25)

##### RSTICK\_CLICK

> `16`

Defined in:  [src/deck-components/FooterLegend.ts:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L20)

##### RSTICK\_TOUCH

> `18`

Defined in:  [src/deck-components/FooterLegend.ts:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L22)

##### SECONDARY

> `3`

Defined in:  [src/deck-components/FooterLegend.ts:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L7)

##### SELECT

> `13`

Defined in:  [src/deck-components/FooterLegend.ts:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L17)

##### START

> `14`

Defined in:  [src/deck-components/FooterLegend.ts:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L18)

##### STEAM\_GUIDE

> `27`

Defined in:  [src/deck-components/FooterLegend.ts:31](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L31)

##### STEAM\_QUICK\_MENU

> `28`

Defined in:  [src/deck-components/FooterLegend.ts:32](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L32)

##### TRIGGER\_LEFT

> `7`

Defined in:  [src/deck-components/FooterLegend.ts:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L11)

##### TRIGGER\_RIGHT

> `8`

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

> `number`

Defined in:  [src/deck-components/FooterLegend.ts:35](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L35)

##### LAST

> `number`

Defined in:  [src/deck-components/FooterLegend.ts:36](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L36)

##### MAINTAIN\_X

> `number`

Defined in:  [src/deck-components/FooterLegend.ts:37](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L37)

##### MAINTAIN\_Y

> `number`

Defined in:  [src/deck-components/FooterLegend.ts:38](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L38)

##### PREFERRED\_CHILD

> `number`

Defined in:  [src/deck-components/FooterLegend.ts:39](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L39)

## Interfaces

### FooterLegendProps

#### Hierarchy

- [`DialogButtonProps`](Dialog#dialogbuttonprops)
- [`DialogCheckboxProps`](DialogCheckbox#dialogcheckboxprops)
- [`FieldProps`](Field#fieldprops)
- [`FocusableProps`](Focusable#focusableprops)
- [`MenuProps`](Menu#menuprops)
- [`MenuItemProps`](Menu#menuitemprops)

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

##### actionDescriptionMap?

> [`ActionDescriptionMap`](FooterLegend#actiondescriptionmap)

Defined in:  [src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L51)

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

Defined in:  [src/deck-components/FooterLegend.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L58)

##### onCancelActionDescription?

> `ReactNode`

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

Defined in:  [src/deck-components/FooterLegend.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L64)

##### onMenuActionDescription?

> `ReactNode`

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

Defined in:  [src/deck-components/FooterLegend.ts:66](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L66)

##### onOKActionDescription?

> `ReactNode`

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

Defined in:  [src/deck-components/FooterLegend.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L59)

##### onOptionsActionDescription?

> `ReactNode`

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

Defined in:  [src/deck-components/FooterLegend.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L62)

##### onSecondaryActionDescription?

> `ReactNode`

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

> `number`

Defined in:  [src/deck-components/FooterLegend.ts:42](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L42)

##### is\_repeat?

> `boolean`

Defined in:  [src/deck-components/FooterLegend.ts:43](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L43)

##### source

> `number`

Defined in:  [src/deck-components/FooterLegend.ts:44](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L44)

## Type Aliases

### ActionDescriptionMap

> `{ [key in GamepadButton]?: ReactNode }`

Defined in:  [src/deck-components/FooterLegend.ts:46](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L46)

---

### GamepadEvent

> [`CustomEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/CustomEvent )\<[`GamepadEventDetail`](FooterLegend#gamepadeventdetail)\>

Defined in:  [src/deck-components/FooterLegend.ts:49](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L49)
