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

##### children?

> `ReactNode`

Defined in:  [src/deck-components/Menu.tsx:36](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L36)

##### disabled?

> `boolean`

Defined in:  [src/deck-components/Menu.tsx:35](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L35)

##### label

> `string`

Defined in:  [src/deck-components/Menu.tsx:34](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L34)

---

### MenuItemProps

#### Hierarchy

- [`FooterLegendProps`](FooterLegend#footerlegendprops).**MenuItemProps**

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

##### actionDescriptionMap?

> [`ActionDescriptionMap`](FooterLegend#actiondescriptionmap)

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[actionDescriptionMap](FooterLegend#actiondescriptionmap)

Defined in:  [src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L51)

##### bInteractableItem?

> `boolean`

Defined in:  [src/deck-components/Menu.tsx:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L54)

##### bPlayAudio?

> `boolean`

Defined in:  [src/deck-components/Menu.tsx:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L61)

##### children?

> `ReactNode`

Defined in:  [src/deck-components/Menu.tsx:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L63)

##### disabled?

> `boolean`

Defined in:  [src/deck-components/Menu.tsx:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L60)

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

##### selected?

> `boolean`

Defined in:  [src/deck-components/Menu.tsx:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L59)

##### tone?

> `"positive"` \| `"emphasis"` \| `"destructive"`

Defined in:  [src/deck-components/Menu.tsx:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L62)

#### Methods

##### onClick()?

###### Signature

```ts
Optional onClick(evt: Event): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`Event`]( https://developer.mozilla.org/en-US/docs/Web/API/Event ) |

###### Returns

`void`

Defined in:  [src/deck-components/Menu.tsx:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L55)

##### onMouseEnter()?

###### Signature

```ts
Optional onMouseEnter(evt: MouseEvent): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`MouseEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent ) |

###### Returns

`void`

Defined in:  [src/deck-components/Menu.tsx:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L57)

##### onMoveRight()?

###### Signature

```ts
Optional onMoveRight(): void;
```

###### Returns

`void`

Defined in:  [src/deck-components/Menu.tsx:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L58)

##### onSelected()?

###### Signature

```ts
Optional onSelected(evt: Event): void;
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `evt` | [`Event`]( https://developer.mozilla.org/en-US/docs/Web/API/Event ) |

###### Returns

`void`

Defined in:  [src/deck-components/Menu.tsx:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L56)

---

### MenuProps

#### Hierarchy

- [`FooterLegendProps`](FooterLegend#footerlegendprops).**MenuProps**

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

##### actionDescriptionMap?

> [`ActionDescriptionMap`](FooterLegend#actiondescriptionmap)

Inherited from: [FooterLegendProps](FooterLegend#footerlegendprops).[actionDescriptionMap](FooterLegend#actiondescriptionmap)

Defined in:  [src/deck-components/FooterLegend.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/FooterLegend.ts#L51)

##### cancelText?

> `string`

Defined in:  [src/deck-components/Menu.tsx:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L19)

##### children?

> `ReactNode`

Defined in:  [src/deck-components/Menu.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L20)

##### label

> `string`

Defined in:  [src/deck-components/Menu.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L17)

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

#### Methods

##### onCancel()?

###### Signature

```ts
Optional onCancel(): void;
```

###### Returns

`void`

Defined in:  [src/deck-components/Menu.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L18)

## Functions

### Menu()

#### Signature

```ts
Menu(props: PropsWithChildren<MenuProps>, context?: any): null | ReactElement<any, any>;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[`MenuProps`](Menu#menuprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### MenuGroup()

#### Signature

```ts
MenuGroup(props: PropsWithChildren<MenuGroupProps>, context?: any): null | ReactElement<any, any>;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[`MenuGroupProps`](Menu#menugroupprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### MenuItem()

#### Signature

```ts
MenuItem(props: PropsWithChildren<MenuItemProps>, context?: any): null | ReactElement<any, any>;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[`MenuItemProps`](Menu#menuitemprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### showContextMenu()

#### Signature

```ts
showContextMenu(children: ReactNode, parent?: EventTarget): void;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `children` | `ReactNode` |
| `parent?` | [`EventTarget`]( https://developer.mozilla.org/en-US/docs/Web/API/EventTarget ) |

#### Returns

`void`

Defined in:  [src/deck-components/Menu.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Menu.tsx#L7)
