[decky-frontend-lib](../README.md) / [Modules](../modules.md) / utils

# Module: utils

## Table of contents

### References

- [Patch](utils.md#patch)
- [PatchOptions](utils.md#patchoptions)
- [afterPatch](utils.md#afterpatch)
- [beforePatch](utils.md#beforepatch)
- [callOriginal](utils.md#calloriginal)
- [fakeRenderComponent](utils.md#fakerendercomponent)
- [findInReactTree](utils.md#findinreacttree)
- [findInTree](utils.md#findintree)
- [findInTreeFilter](utils.md#findintreefilter)
- [findInTreeOpts](utils.md#findintreeopts)
- [getReactInstance](utils.md#getreactinstance)
- [replacePatch](utils.md#replacepatch)
- [wrapReactClass](utils.md#wrapreactclass)
- [wrapReactType](utils.md#wrapreacttype)

### Functions

- [findSP](utils.md#findsp)
- [joinClassNames](utils.md#joinclassnames)
- [sleep](utils.md#sleep)

## References

### Patch

Re-exports [Patch](../interfaces/utils_patcher.Patch.md)

___

### PatchOptions

Re-exports [PatchOptions](../interfaces/utils_patcher.PatchOptions.md)

___

### afterPatch

Re-exports [afterPatch](utils_patcher.md#afterpatch)

___

### beforePatch

Re-exports [beforePatch](utils_patcher.md#beforepatch)

___

### callOriginal

Re-exports [callOriginal](utils_patcher.md#calloriginal)

___

### fakeRenderComponent

Re-exports [fakeRenderComponent](utils_react.md#fakerendercomponent)

___

### findInReactTree

Re-exports [findInReactTree](utils_react.md#findinreacttree)

___

### findInTree

Re-exports [findInTree](utils_react.md#findintree)

___

### findInTreeFilter

Re-exports [findInTreeFilter](utils_react.md#findintreefilter)

___

### findInTreeOpts

Re-exports [findInTreeOpts](../interfaces/utils_react.findInTreeOpts.md)

___

### getReactInstance

Re-exports [getReactInstance](utils_react.md#getreactinstance)

___

### replacePatch

Re-exports [replacePatch](utils_patcher.md#replacepatch)

___

### wrapReactClass

Re-exports [wrapReactClass](utils_react.md#wrapreactclass)

___

### wrapReactType

Re-exports [wrapReactType](utils_react.md#wrapreacttype)

## Functions

### findSP

▸ **findSP**(): [`Window`]( https://developer.mozilla.org/en-US/docs/Web/API/Window )

Finds the SP window, since it is a render target as of 10-19-2022's beta

#### Returns

[`Window`]( https://developer.mozilla.org/en-US/docs/Web/API/Window )

#### Defined in

[src/utils/index.ts:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/37a6658/src/utils/index.ts#L15)

___

### joinClassNames

▸ **joinClassNames**(...`classes`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `...classes` | `string`[] |

#### Returns

`string`

#### Defined in

[src/utils/index.ts:4](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/37a6658/src/utils/index.ts#L4)

___

### sleep

▸ **sleep**(`ms`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`unknown`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ms` | `number` |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<`unknown`\>

#### Defined in

[src/utils/index.ts:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/37a6658/src/utils/index.ts#L8)
