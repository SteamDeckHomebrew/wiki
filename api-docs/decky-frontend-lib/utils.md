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
- getReactRoot
- replacePatch
- wrapReactClass
- wrapReactType

### Functions

- findSP
- getFocusNavController
- getGamepadNavigationTrees
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

Defined in:  [src/utils/react.ts:111](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L111)

### findInTree

Re-exports [findInTree](react#findintree)

Defined in:  [src/utils/react.ts:90](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L90)

### findInTreeFilter

Re-exports [findInTreeFilter](react#findintreefilter)

Defined in:  [src/utils/react.ts:88](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L88)

### findInTreeOpts

Re-exports [findInTreeOpts](react#findintreeopts)

Defined in:  [src/utils/react.ts:83](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L83)

### getReactInstance

Re-exports [getReactInstance](react#getreactinstance)

Defined in:  [src/utils/react.ts:75](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L75)

### getReactRoot

Re-exports [getReactRoot](react#getreactroot)

Defined in:  [src/utils/react.ts:68](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L68)

### replacePatch

Re-exports [replacePatch](patcher#replacepatch)

Defined in:  [src/utils/patcher.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/patcher.ts#L62)

### wrapReactClass

Re-exports [wrapReactClass](react#wrapreactclass)

Defined in:  [src/utils/react.ts:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/react.ts#L56)

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

Defined in:  [src/utils/index.ts:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/index.ts#L20)

---

### getFocusNavController()

Gets the correct FocusNavController, as the Feb 22 2023 beta has two for some reason.

#### Signature

```ts
getFocusNavController(): any;
```

#### Returns

`any`

Defined in:  [src/utils/index.ts:31](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/index.ts#L31)

---

### getGamepadNavigationTrees()

Gets the gamepad navigation trees as Valve seems to be moving them.

#### Signature

```ts
getGamepadNavigationTrees(): any;
```

#### Returns

`any`

Defined in:  [src/utils/index.ts:38](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/index.ts#L38)

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

Defined in:  [src/utils/index.ts:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/index.ts#L9)

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

Defined in:  [src/utils/index.ts:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/utils/index.ts#L13)
