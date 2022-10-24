[decky-frontend-lib](../README.md) / [Modules](../modules.md) / utils/react

# Module: utils/react

## Table of contents

### Modules

- [&lt;internal\&gt;](utils_react._internal_.md)

### Interfaces

- [findInTreeOpts](../interfaces/utils_react.findInTreeOpts.md)

### Type Aliases

- [findInTreeFilter](utils_react.md#findintreefilter)

### Functions

- [fakeRenderComponent](utils_react.md#fakerendercomponent)
- [findInReactTree](utils_react.md#findinreacttree)
- [findInTree](utils_react.md#findintree)
- [getReactInstance](utils_react.md#getreactinstance)
- [wrapReactClass](utils_react.md#wrapreactclass)
- [wrapReactType](utils_react.md#wrapreacttype)

## Type Aliases

### findInTreeFilter

Ƭ **findInTreeFilter**: (`element`: `any`) => `boolean`

#### Type declaration

▸ (`element`): `boolean`

##### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `any` |

##### Returns

`boolean`

#### Defined in

[src/utils/react.ts:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/utils/react.ts#L65)

## Functions

### fakeRenderComponent

▸ **fakeRenderComponent**(`fun`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `fun` | [`Function`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function ) |

#### Returns

`any`

#### Defined in

[src/utils/react.ts:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/utils/react.ts#L11)

___

### findInReactTree

▸ **findInReactTree**(`node`, `filter`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `node` | `any` |
| `filter` | [`findInTreeFilter`](utils_react.md#findintreefilter) |

#### Returns

`any`

#### Defined in

[src/utils/react.ts:84](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/utils/react.ts#L84)

___

### findInTree

▸ **findInTree**(`parent`, `filter`, `opts`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `parent` | `any` |
| `filter` | [`findInTreeFilter`](utils_react.md#findintreefilter) |
| `opts` | [`findInTreeOpts`](../interfaces/utils_react.findInTreeOpts.md) |

#### Returns

`any`

#### Defined in

[src/utils/react.ts:67](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/utils/react.ts#L67)

___

### getReactInstance

▸ **getReactInstance**(`o`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `o` | [`Node`]( https://developer.mozilla.org/en-US/docs/Web/API/Node ) \| [`Element`]( https://developer.mozilla.org/en-US/docs/Web/API/Element ) \| [`HTMLElement`]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement ) |

#### Returns

`any`

#### Defined in

[src/utils/react.ts:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/utils/react.ts#L55)

___

### wrapReactClass

▸ **wrapReactClass**(`node`, `prop?`): typeof [`__class`](../classes/utils_react._internal_.__class.md)

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `node` | `any` | `undefined` |
| `prop` | `any` | `'type'` |

#### Returns

typeof [`__class`](../classes/utils_react._internal_.__class.md)

#### Defined in

[src/utils/react.ts:49](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/utils/react.ts#L49)

___

### wrapReactType

▸ **wrapReactType**(`node`, `prop?`): `any`

#### Parameters

| Name | Type | Default value |
| :------ | :------ | :------ |
| `node` | `any` | `undefined` |
| `prop` | `any` | `'type'` |

#### Returns

`any`

#### Defined in

[src/utils/react.ts:45](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/5f0470c/src/utils/react.ts#L45)
