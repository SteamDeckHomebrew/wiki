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

Re-exports [Patch](utils/patcher#patch)

### PatchOptions

Re-exports [PatchOptions](utils/patcher#patchoptions)

### afterPatch

Re-exports [afterPatch](utils/patcher#afterpatch)

### beforePatch

Re-exports [beforePatch](utils/patcher#beforepatch)

### callOriginal

Re-exports [callOriginal](utils/patcher#calloriginal)

### fakeRenderComponent

Re-exports [fakeRenderComponent](utils/react#fakerendercomponent)

### findInReactTree

Re-exports [findInReactTree](utils/react#findinreacttree)

### findInTree

Re-exports [findInTree](utils/react#findintree)

### findInTreeFilter

Re-exports [findInTreeFilter](utils/react#findintreefilter)

### findInTreeOpts

Re-exports [findInTreeOpts](utils/react#findintreeopts)

### getReactInstance

Re-exports [getReactInstance](utils/react#getreactinstance)

### replacePatch

Re-exports [replacePatch](utils/patcher#replacepatch)

### wrapReactClass

Re-exports [wrapReactClass](utils/react#wrapreactclass)

### wrapReactType

Re-exports [wrapReactType](utils/react#wrapreacttype)

## Functions

### findSP()

#### Signature

```ts
findSP(): Window
```

Finds the SP window, since it is a render target as of 10-19-2022's beta

#### Returns

[Window]( https://developer.mozilla.org/en-US/docs/Web/API/Window )

Defined in:  [src/utils/index.ts:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/index.ts#L15)

---

### joinClassNames()

#### Signature

```ts
joinClassNames(...classes: string[]): string
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
sleep(ms: number): Promise<unknown>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `ms` | `number` |

#### Returns

[Promise]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )\<`unknown`\>

Defined in:  [src/utils/index.ts:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/index.ts#L8)
