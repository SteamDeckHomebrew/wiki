# utils/react

## Index

### Interfaces

- findInTreeOpts

### Type Aliases

- findInTreeFilter

### Functions

- fakeRenderComponent
- findInReactTree
- findInTree
- getReactInstance
- getReactRoot
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

Defined in:  [src/utils/react.ts:85](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L85)

##### walkable?

> `string`[]

Defined in:  [src/utils/react.ts:84](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L84)

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

Defined in:  [src/utils/react.ts:88](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L88)

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

Defined in:  [src/utils/react.ts:111](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L111)

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

Defined in:  [src/utils/react.ts:90](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L90)

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

Defined in:  [src/utils/react.ts:75](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L75)

---

### getReactRoot()

#### Signature

```ts
getReactRoot(o: Node | Element | HTMLElement): any;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `o` | [`Node`]( https://developer.mozilla.org/en-US/docs/Web/API/Node ) \| [`Element`]( https://developer.mozilla.org/en-US/docs/Web/API/Element ) \| [`HTMLElement`]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement ) |

#### Returns

`any`

Defined in:  [src/utils/react.ts:68](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L68)

---

### wrapReactClass()

#### Signature

```ts
wrapReactClass(node: any, prop: any = 'type'): any;
```

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `node` | `any` | `undefined` |
| `prop` | `any` | `'type'` |

#### Returns

`any`

Defined in:  [src/utils/react.ts:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L56)

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
