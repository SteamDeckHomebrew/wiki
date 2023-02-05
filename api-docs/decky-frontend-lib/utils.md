---
title: "utils"
editor: "markdown"
published: true
---

# utils

## Index

### References

- Patch
- PatchOptions
- afterPatch
- beforePatch
- callOriginal
- fakeRenderComponent
- findInReactTree
- findInTree
- findInTreeFilter
- findInTreeOpts
- getReactInstance
- replacePatch
- wrapReactClass
- wrapReactType

### Functions

- findSP
- joinClassNames
- sleep

## References

### Patch

Re-exports [Patch](patcher#patch)

Defined in:  [src/utils/patcher.ts:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L11)

### PatchOptions

Re-exports [PatchOptions](patcher#patchoptions)

Defined in:  [src/utils/patcher.ts:5](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L5)

### afterPatch

Re-exports [afterPatch](patcher#afterpatch)

Defined in:  [src/utils/patcher.ts:43](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L43)

### beforePatch

Re-exports [beforePatch](patcher#beforepatch)

Defined in:  [src/utils/patcher.ts:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L24)

### callOriginal

Re-exports [callOriginal](patcher#calloriginal)

Defined in:  [src/utils/patcher.ts:3](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L3)

### fakeRenderComponent

Re-exports [fakeRenderComponent](react#fakerendercomponent)

Defined in:  [src/utils/react.ts:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L11)

### findInReactTree

Re-exports [findInReactTree](react#findinreacttree)

Defined in:  [src/utils/react.ts:91](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L91)

### findInTree

Re-exports [findInTree](react#findintree)

Defined in:  [src/utils/react.ts:70](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L70)

### findInTreeFilter

Re-exports [findInTreeFilter](react#findintreefilter)

Defined in:  [src/utils/react.ts:68](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L68)

### findInTreeOpts

Re-exports [findInTreeOpts](react#findintreeopts)

Defined in:  [src/utils/react.ts:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L63)

### getReactInstance

Re-exports [getReactInstance](react#getreactinstance)

Defined in:  [src/utils/react.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L58)

### replacePatch

Re-exports [replacePatch](patcher#replacepatch)

Defined in:  [src/utils/patcher.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L62)

### wrapReactClass

Re-exports [wrapReactClass](react#wrapreactclass)

Defined in:  [src/utils/react.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L52)

### wrapReactType

Re-exports [wrapReactType](react#wrapreacttype)

Defined in:  [src/utils/react.ts:48](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L48)

## Functions

### findSP()

Finds the SP window, since it is a render target as of 10-19-2022's beta

#### Signature

```ts
findSP(): Window;
```

#### Returns

[`Window`]( https://developer.mozilla.org/en-US/docs/Web/API/Window )

Defined in:  [src/utils/index.ts:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/index.ts#L15)

---

### joinClassNames()

#### Signature

```ts
joinClassNames(...classes: string[]): string;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `...classes` | `string`[] |

#### Returns

`string`

Defined in:  [src/utils/index.ts:4](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/index.ts#L4)

---

### sleep()

#### Signature

```ts
sleep(ms: number): Promise<unknown>;
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `ms` | `number` |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )\<`unknown`\>

Defined in:  [src/utils/index.ts:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/index.ts#L8)
