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

[src/utils/react.ts:68](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/ed0b92d/src/utils/react.ts#L68)

## Functions

### fakeRenderComponent

▸ **fakeRenderComponent**(`fun`, `customHooks?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `fun` | [`Function`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function ) |
| `customHooks` | `any` |

#### Returns

`any`

#### Defined in

[src/utils/react.ts:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/ed0b92d/src/utils/react.ts#L11)

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

[src/utils/react.ts:91](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/ed0b92d/src/utils/react.ts#L91)

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

[src/utils/react.ts:70](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/ed0b92d/src/utils/react.ts#L70)

___

### getReactInstance

▸ **getReactInstance**(`o`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `o` | [`HTMLElement`]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement ) \| [`Element`]( https://developer.mozilla.org/en-US/docs/Web/API/Element ) \| [`Node`]( https://developer.mozilla.org/en-US/docs/Web/API/Node ) |

#### Returns

`any`

#### Defined in

[src/utils/react.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/ed0b92d/src/utils/react.ts#L58)

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

[src/utils/react.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/ed0b92d/src/utils/react.ts#L52)

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

[src/utils/react.ts:48](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/ed0b92d/src/utils/react.ts#L48)
