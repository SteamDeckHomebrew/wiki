---
title: "deck-components/Carousel"
editor: "markdown"
published: true
---

# deck-components/Carousel

## Index

### Interfaces

- CarouselProps

### Functions

- Carousel

## Interfaces

### CarouselProps

#### Hierarchy

- `HTMLAttributes`\<[`HTMLDivElement`]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLDivElement )\>.**CarouselProps**

#### Index

##### Properties

- autoFocus
- enableBumperPaging
- fnDoesItemTakeFocus
- fnGetColumnWidth
- fnGetId
- fnItemRenderer
- fnUpdateArrows
- initialColumn
- nHeight
- nIndexLeftmost
- nItemHeight
- nItemMarginX
- nNumItems
- name
- scrollToAlignment

#### Properties

##### autoFocus?

> `boolean`

Defined in:  [src/deck-components/Carousel.ts:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Carousel.ts#L6)

##### enableBumperPaging?

> `boolean`

Defined in:  [src/deck-components/Carousel.ts:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Carousel.ts#L7)

##### fnDoesItemTakeFocus?

> `Function`

###### Type declaration

####### Signature

```ts
(...unknown: any[]): boolean;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `...unknown` | `any`[] |

####### Returns

`boolean`

Defined in:  [src/deck-components/Carousel.ts:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Carousel.ts#L8)

##### fnGetColumnWidth?

> `Function`

###### Type declaration

####### Signature

```ts
(...unknown: any[]): number;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `...unknown` | `any`[] |

####### Returns

`number`

Defined in:  [src/deck-components/Carousel.ts:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Carousel.ts#L9)

##### fnGetId?

> `Function`

###### Type declaration

####### Signature

```ts
(id: number): number;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `number` |

####### Returns

`number`

Defined in:  [src/deck-components/Carousel.ts:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Carousel.ts#L10)

##### fnItemRenderer?

> `Function`

###### Type declaration

####### Signature

```ts
(id: number, ...unknown: any[]): ReactNode;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `id` | `number` |
| `...unknown` | `any`[] |

####### Returns

`ReactNode`

Defined in:  [src/deck-components/Carousel.ts:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Carousel.ts#L11)

##### fnUpdateArrows?

> `Function`

###### Type declaration

####### Signature

```ts
(...unknown: any[]): any;
```

####### Parameters

| Name | Type |
| :------ | :------ |
| `...unknown` | `any`[] |

####### Returns

`any`

Defined in:  [src/deck-components/Carousel.ts:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Carousel.ts#L12)

##### initialColumn?

> `number`

Defined in:  [src/deck-components/Carousel.ts:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Carousel.ts#L13)

##### nHeight?

> `number`

Defined in:  [src/deck-components/Carousel.ts:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Carousel.ts#L14)

##### nIndexLeftmost?

> `number`

Defined in:  [src/deck-components/Carousel.ts:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Carousel.ts#L15)

##### nItemHeight?

> `number`

Defined in:  [src/deck-components/Carousel.ts:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Carousel.ts#L16)

##### nItemMarginX?

> `number`

Defined in:  [src/deck-components/Carousel.ts:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Carousel.ts#L17)

##### nNumItems?

> `number`

Defined in:  [src/deck-components/Carousel.ts:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Carousel.ts#L18)

##### name?

> `string`

Defined in:  [src/deck-components/Carousel.ts:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Carousel.ts#L19)

##### scrollToAlignment?

> `"center"`

Defined in:  [src/deck-components/Carousel.ts:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Carousel.ts#L20)

## Functions

### Carousel()

#### Signature

```ts
Carousel(props: CarouselProps & RefAttributes<HTMLDivElement>, context?: any): null | ReactElement<any, any>;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`CarouselProps`](Carousel#carouselprops) & `RefAttributes`\<[`HTMLDivElement`]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLDivElement )\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:554
