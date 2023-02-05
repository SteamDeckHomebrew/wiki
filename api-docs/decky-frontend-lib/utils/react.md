---
title: "utils/react"
editor: "markdown"
published: true
---

# utils/react

## Index

### Modules

- <internal>

### Interfaces

- findInTreeOpts

### Type Aliases

- findInTreeFilter

### Functions

- fakeRenderComponent
- findInReactTree
- findInTree
- getReactInstance
- wrapReactClass
- wrapReactType

## Interfaces

### findInTreeOpts

#### Index

##### Properties

- ignore
- walkable

#### Properties

##### ignore?

> `string`[]

Defined in:  [src/utils/react.ts:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L65)

##### walkable?

> `string`[]

Defined in:  [src/utils/react.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L64)

## Type Aliases

### findInTreeFilter

> `Function`

#### Type declaration

##### Signature

```ts
(element: any): boolean;
```

##### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `any` |

##### Returns

`boolean`

Defined in:  [src/utils/react.ts:68](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L68)

## Functions

### fakeRenderComponent()

#### Signature

```ts
fakeRenderComponent(fun: Function, customHooks: any = {}): any;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `fun` | [`Function`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function ) |
| `customHooks` | `any` |

#### Returns

`any`

Defined in:  [src/utils/react.ts:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L11)

---

### findInReactTree()

#### Signature

```ts
findInReactTree(node: any, filter: findInTreeFilter): any;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | `any` |
| `filter` | [`findInTreeFilter`](react#findintreefilter) |

#### Returns

`any`

Defined in:  [src/utils/react.ts:91](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L91)

---

### findInTree()

#### Signature

```ts
findInTree(parent: any, filter: findInTreeFilter, opts: findInTreeOpts): any;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `parent` | `any` |
| `filter` | [`findInTreeFilter`](react#findintreefilter) |
| `opts` | [`findInTreeOpts`](react#findintreeopts) |

#### Returns

`any`

Defined in:  [src/utils/react.ts:70](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L70)

---

### getReactInstance()

#### Signature

```ts
getReactInstance(o: Node | Element | HTMLElement): any;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `o` | [`Node`]( https://developer.mozilla.org/en-US/docs/Web/API/Node ) \| [`Element`]( https://developer.mozilla.org/en-US/docs/Web/API/Element ) \| [`HTMLElement`]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement ) |

#### Returns

`any`

Defined in:  [src/utils/react.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L58)

---

### wrapReactClass()

#### Signature

```ts
wrapReactClass(node: any, prop: any = 'type'): typeof __class;
```

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `node` | `any` | `undefined` |
| `prop` | `any` | `'type'` |

#### Returns

*typeof* [`__class`](class)

Defined in:  [src/utils/react.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L52)

---

### wrapReactType()

#### Signature

```ts
wrapReactType(node: any, prop: any = 'type'): any;
```

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `node` | `any` | `undefined` |
| `prop` | `any` | `'type'` |

#### Returns

`any`

Defined in:  [src/utils/react.ts:48](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L48)
