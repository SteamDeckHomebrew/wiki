[decky-frontend-lib](../README.md) / [Modules](../modules.md) / deck-components/Modal

# Module: deck-components/Modal

## Table of contents

### Interfaces

- [ConfirmModalProps](../interfaces/deck_components_Modal.ConfirmModalProps.md)
- [ModalRootProps](../interfaces/deck_components_Modal.ModalRootProps.md)
- [ShowModalProps](../interfaces/deck_components_Modal.ShowModalProps.md)
- [ShowModalResult](../interfaces/deck_components_Modal.ShowModalResult.md)

### Functions

- [ConfirmModal](deck_components_Modal.md#confirmmodal)
- [ModalRoot](deck_components_Modal.md#modalroot)
- [showModal](deck_components_Modal.md#showmodal)

## Functions

### ConfirmModal

▸ **ConfirmModal**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`ConfirmModalProps`](../interfaces/deck_components_Modal.ConfirmModalProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/.pnpm/@types+react@16.14.0/node_modules/@types/react/index.d.ts:544

___

### ModalRoot

▸ **ModalRoot**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`ModalRootProps`](../interfaces/deck_components_Modal.ModalRootProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/.pnpm/@types+react@16.14.0/node_modules/@types/react/index.d.ts:544

___

### showModal

▸ **showModal**(`modal`, `parent?`, `props?`): [`ShowModalResult`](../interfaces/deck_components_Modal.ShowModalResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `modal` | `ReactNode` |
| `parent?` | [`EventTarget`]( https://developer.mozilla.org/en-US/docs/Web/API/EventTarget ) |
| `props` | [`ShowModalProps`](../interfaces/deck_components_Modal.ShowModalProps.md) |

#### Returns

[`ShowModalResult`](../interfaces/deck_components_Modal.ShowModalResult.md)

#### Defined in

[src/deck-components/Modal.tsx:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/727fcc8/src/deck-components/Modal.tsx#L65)
