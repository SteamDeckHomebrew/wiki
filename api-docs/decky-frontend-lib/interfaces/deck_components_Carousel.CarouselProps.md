[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [deck-components/Carousel](../modules/deck_components_Carousel.md) / CarouselProps

# Interface: CarouselProps

[deck-components/Carousel](../modules/deck_components_Carousel.md).CarouselProps

## Hierarchy

- `HTMLAttributes`<[`HTMLDivElement`]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLDivElement )\>

  ↳ **`CarouselProps`**

## Table of contents

### Properties

- [autoFocus](deck_components_Carousel.CarouselProps.md#autofocus)
- [enableBumperPaging](deck_components_Carousel.CarouselProps.md#enablebumperpaging)
- [fnDoesItemTakeFocus](deck_components_Carousel.CarouselProps.md#fndoesitemtakefocus)
- [fnGetColumnWidth](deck_components_Carousel.CarouselProps.md#fngetcolumnwidth)
- [fnGetId](deck_components_Carousel.CarouselProps.md#fngetid)
- [fnItemRenderer](deck_components_Carousel.CarouselProps.md#fnitemrenderer)
- [fnUpdateArrows](deck_components_Carousel.CarouselProps.md#fnupdatearrows)
- [initialColumn](deck_components_Carousel.CarouselProps.md#initialcolumn)
- [nHeight](deck_components_Carousel.CarouselProps.md#nheight)
- [nIndexLeftmost](deck_components_Carousel.CarouselProps.md#nindexleftmost)
- [nItemHeight](deck_components_Carousel.CarouselProps.md#nitemheight)
- [nItemMarginX](deck_components_Carousel.CarouselProps.md#nitemmarginx)
- [nNumItems](deck_components_Carousel.CarouselProps.md#nnumitems)
- [name](deck_components_Carousel.CarouselProps.md#name)
- [scrollToAlignment](deck_components_Carousel.CarouselProps.md#scrolltoalignment)

## Properties

### autoFocus

• `Optional` **autoFocus**: `boolean`

#### Defined in

[src/deck-components/Carousel.ts:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/68d6302/src/deck-components/Carousel.ts#L6)

___

### enableBumperPaging

• `Optional` **enableBumperPaging**: `boolean`

#### Defined in

[src/deck-components/Carousel.ts:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/68d6302/src/deck-components/Carousel.ts#L7)

___

### fnDoesItemTakeFocus

• `Optional` **fnDoesItemTakeFocus**: (...`unknown`: `any`[]) => `boolean`

#### Type declaration

▸ (...`unknown`): `boolean`

##### Parameters

| Name | Type |
| :------ | :------ |
| `...unknown` | `any`[] |

##### Returns

`boolean`

#### Defined in

[src/deck-components/Carousel.ts:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/68d6302/src/deck-components/Carousel.ts#L8)

___

### fnGetColumnWidth

• `Optional` **fnGetColumnWidth**: (...`unknown`: `any`[]) => `number`

#### Type declaration

▸ (...`unknown`): `number`

##### Parameters

| Name | Type |
| :------ | :------ |
| `...unknown` | `any`[] |

##### Returns

`number`

#### Defined in

[src/deck-components/Carousel.ts:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/68d6302/src/deck-components/Carousel.ts#L9)

___

### fnGetId

• `Optional` **fnGetId**: (`id`: `number`) => `number`

#### Type declaration

▸ (`id`): `number`

##### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `number` |

##### Returns

`number`

#### Defined in

[src/deck-components/Carousel.ts:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/68d6302/src/deck-components/Carousel.ts#L10)

___

### fnItemRenderer

• `Optional` **fnItemRenderer**: (`id`: `number`, ...`unknown`: `any`[]) => `ReactNode`

#### Type declaration

▸ (`id`, ...`unknown`): `ReactNode`

##### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `number` |
| `...unknown` | `any`[] |

##### Returns

`ReactNode`

#### Defined in

[src/deck-components/Carousel.ts:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/68d6302/src/deck-components/Carousel.ts#L11)

___

### fnUpdateArrows

• `Optional` **fnUpdateArrows**: (...`unknown`: `any`[]) => `any`

#### Type declaration

▸ (...`unknown`): `any`

##### Parameters

| Name | Type |
| :------ | :------ |
| `...unknown` | `any`[] |

##### Returns

`any`

#### Defined in

[src/deck-components/Carousel.ts:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/68d6302/src/deck-components/Carousel.ts#L12)

___

### initialColumn

• `Optional` **initialColumn**: `number`

#### Defined in

[src/deck-components/Carousel.ts:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/68d6302/src/deck-components/Carousel.ts#L13)

___

### nHeight

• `Optional` **nHeight**: `number`

#### Defined in

[src/deck-components/Carousel.ts:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/68d6302/src/deck-components/Carousel.ts#L14)

___

### nIndexLeftmost

• `Optional` **nIndexLeftmost**: `number`

#### Defined in

[src/deck-components/Carousel.ts:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/68d6302/src/deck-components/Carousel.ts#L15)

___

### nItemHeight

• `Optional` **nItemHeight**: `number`

#### Defined in

[src/deck-components/Carousel.ts:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/68d6302/src/deck-components/Carousel.ts#L16)

___

### nItemMarginX

• `Optional` **nItemMarginX**: `number`

#### Defined in

[src/deck-components/Carousel.ts:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/68d6302/src/deck-components/Carousel.ts#L17)

___

### nNumItems

• `Optional` **nNumItems**: `number`

#### Defined in

[src/deck-components/Carousel.ts:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/68d6302/src/deck-components/Carousel.ts#L18)

___

### name

• `Optional` **name**: `string`

#### Defined in

[src/deck-components/Carousel.ts:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/68d6302/src/deck-components/Carousel.ts#L19)

___

### scrollToAlignment

• `Optional` **scrollToAlignment**: ``"center"``

#### Defined in

[src/deck-components/Carousel.ts:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/68d6302/src/deck-components/Carousel.ts#L20)
