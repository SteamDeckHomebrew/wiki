---
title: "deck-components/Modal"
editor: "markdown"
published: true
---

# deck-components/Modal

## Index

### Interfaces

- ConfirmModalProps
- ModalRootProps
- ShowModalProps
- ShowModalResult

### Functions

- ConfirmModal
- ModalRoot
- showModal

## Interfaces

### ConfirmModalProps

#### Hierarchy

- [ModalRootProps](deck/components/Modal#modalrootprops).**ConfirmModalProps**

#### Index

##### Properties

- bAlertDialog
- bAllowFullSize
- bCancelDisabled
- bDestructiveWarning
- bDisableBackgroundDismiss
- bHideCloseIcon
- bMiddleDisabled
- bOKDisabled
- children
- className
- modalClassName
- strCancelButtonText
- strDescription
- strMiddleButtonText
- strOKButtonText
- strTitle

##### Methods

- closeModal
- onCancel
- onEscKeypress
- onMiddleButton
- onOK

#### Properties

##### bAlertDialog

```ts
bAlertDialog?: boolean
```

Defined in:  [src/deck-components/Modal.tsx:107](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L107)

##### bAllowFullSize

```ts
bAllowFullSize?: boolean
```

Inherited from: [ModalRootProps](deck/components/Modal#modalrootprops).[bAllowFullSize](deck/components/Modal#ballowfullsize)

Defined in:  [src/deck-components/Modal.tsx:92](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L92)

##### bCancelDisabled

```ts
bCancelDisabled?: boolean
```

Inherited from: [ModalRootProps](deck/components/Modal#modalrootprops).[bCancelDisabled](deck/components/Modal#bcanceldisabled)

Defined in:  [src/deck-components/Modal.tsx:97](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L97)

##### bDestructiveWarning

```ts
bDestructiveWarning?: boolean
```

Inherited from: [ModalRootProps](deck/components/Modal#modalrootprops).[bDestructiveWarning](deck/components/Modal#bdestructivewarning)

Defined in:  [src/deck-components/Modal.tsx:93](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L93)

##### bDisableBackgroundDismiss

```ts
bDisableBackgroundDismiss?: boolean
```

Inherited from: [ModalRootProps](deck/components/Modal#modalrootprops).[bDisableBackgroundDismiss](deck/components/Modal#bdisablebackgrounddismiss)

Defined in:  [src/deck-components/Modal.tsx:94](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L94)

##### bHideCloseIcon

```ts
bHideCloseIcon?: boolean
```

Inherited from: [ModalRootProps](deck/components/Modal#modalrootprops).[bHideCloseIcon](deck/components/Modal#bhidecloseicon)

Defined in:  [src/deck-components/Modal.tsx:95](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L95)

##### bMiddleDisabled

```ts
bMiddleDisabled?: boolean
```

Defined in:  [src/deck-components/Modal.tsx:108](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L108)

##### bOKDisabled

```ts
bOKDisabled?: boolean
```

Inherited from: [ModalRootProps](deck/components/Modal#modalrootprops).[bOKDisabled](deck/components/Modal#bokdisabled)

Defined in:  [src/deck-components/Modal.tsx:96](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L96)

##### children

```ts
children?: ReactNode
```

Inherited from: [ModalRootProps](deck/components/Modal#modalrootprops).[children](deck/components/Modal#children)

Defined in:  [src/deck-components/Modal.tsx:85](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L85)

##### className

```ts
className?: string
```

Inherited from: [ModalRootProps](deck/components/Modal#modalrootprops).[className](deck/components/Modal#classname)

Defined in:  [src/deck-components/Modal.tsx:90](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L90)

##### modalClassName

```ts
modalClassName?: string
```

Inherited from: [ModalRootProps](deck/components/Modal#modalrootprops).[modalClassName](deck/components/Modal#modalclassname)

Defined in:  [src/deck-components/Modal.tsx:91](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L91)

##### strCancelButtonText

```ts
strCancelButtonText?: ReactNode
```

Defined in:  [src/deck-components/Modal.tsx:105](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L105)

##### strDescription

```ts
strDescription?: ReactNode
```

Defined in:  [src/deck-components/Modal.tsx:103](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L103)

##### strMiddleButtonText

```ts
strMiddleButtonText?: ReactNode
```

Defined in:  [src/deck-components/Modal.tsx:106](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L106)

##### strOKButtonText

```ts
strOKButtonText?: ReactNode
```

Defined in:  [src/deck-components/Modal.tsx:104](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L104)

##### strTitle

```ts
strTitle?: ReactNode
```

Defined in:  [src/deck-components/Modal.tsx:102](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L102)

#### Methods

##### closeModal()

###### Signature

```ts
Optional closeModal(): void
```

###### Returns

`void`

Inherited from: [ModalRootProps](deck/components/Modal#modalrootprops).[closeModal](deck/components/Modal#closemodal)

Defined in:  [src/deck-components/Modal.tsx:87](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L87)

##### onCancel()

###### Signature

```ts
Optional onCancel(): void
```

###### Returns

`void`

Inherited from: [ModalRootProps](deck/components/Modal#modalrootprops).[onCancel](deck/components/Modal#oncancel)

Defined in:  [src/deck-components/Modal.tsx:86](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L86)

##### onEscKeypress()

###### Signature

```ts
Optional onEscKeypress(): void
```

###### Returns

`void`

Inherited from: [ModalRootProps](deck/components/Modal#modalrootprops).[onEscKeypress](deck/components/Modal#onesckeypress)

Defined in:  [src/deck-components/Modal.tsx:89](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L89)

##### onMiddleButton()

###### Signature

```ts
Optional onMiddleButton(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Modal.tsx:101](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L101)

##### onOK()

###### Signature

```ts
Optional onOK(): void
```

###### Returns

`void`

Inherited from: [ModalRootProps](deck/components/Modal#modalrootprops).[onOK](deck/components/Modal#onok)

Defined in:  [src/deck-components/Modal.tsx:88](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L88)

---

### ModalRootProps

#### Hierarchy

- [ConfirmModalProps](deck/components/Modal#confirmmodalprops)

#### Index

##### Properties

- bAllowFullSize
- bCancelDisabled
- bDestructiveWarning
- bDisableBackgroundDismiss
- bHideCloseIcon
- bOKDisabled
- children
- className
- modalClassName

##### Methods

- closeModal
- onCancel
- onEscKeypress
- onOK

#### Properties

##### bAllowFullSize

```ts
bAllowFullSize?: boolean
```

Defined in:  [src/deck-components/Modal.tsx:92](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L92)

##### bCancelDisabled

```ts
bCancelDisabled?: boolean
```

Defined in:  [src/deck-components/Modal.tsx:97](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L97)

##### bDestructiveWarning

```ts
bDestructiveWarning?: boolean
```

Defined in:  [src/deck-components/Modal.tsx:93](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L93)

##### bDisableBackgroundDismiss

```ts
bDisableBackgroundDismiss?: boolean
```

Defined in:  [src/deck-components/Modal.tsx:94](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L94)

##### bHideCloseIcon

```ts
bHideCloseIcon?: boolean
```

Defined in:  [src/deck-components/Modal.tsx:95](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L95)

##### bOKDisabled

```ts
bOKDisabled?: boolean
```

Defined in:  [src/deck-components/Modal.tsx:96](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L96)

##### children

```ts
children?: ReactNode
```

Defined in:  [src/deck-components/Modal.tsx:85](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L85)

##### className

```ts
className?: string
```

Defined in:  [src/deck-components/Modal.tsx:90](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L90)

##### modalClassName

```ts
modalClassName?: string
```

Defined in:  [src/deck-components/Modal.tsx:91](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L91)

#### Methods

##### closeModal()

###### Signature

```ts
Optional closeModal(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Modal.tsx:87](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L87)

##### onCancel()

###### Signature

```ts
Optional onCancel(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Modal.tsx:86](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L86)

##### onEscKeypress()

###### Signature

```ts
Optional onEscKeypress(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Modal.tsx:89](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L89)

##### onOK()

###### Signature

```ts
Optional onOK(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Modal.tsx:88](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L88)

---

### ShowModalProps

#### Index

##### Properties

- bForcePopOut
- bHideActionIcons
- bHideMainWindowForPopouts
- bNeverPopOut
- browserContext
- fnOnClose
- popupHeight
- popupWidth
- promiseRenderComplete
- strTitle

#### Properties

##### bForcePopOut

```ts
bForcePopOut?: boolean
```

Defined in:  [src/deck-components/Modal.tsx:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L9)

##### bHideActionIcons

```ts
bHideActionIcons?: boolean
```

Defined in:  [src/deck-components/Modal.tsx:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L10)

##### bHideMainWindowForPopouts

```ts
bHideMainWindowForPopouts?: boolean
```

Defined in:  [src/deck-components/Modal.tsx:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L11)

##### bNeverPopOut

```ts
bNeverPopOut?: boolean
```

Defined in:  [src/deck-components/Modal.tsx:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L12)

##### browserContext

```ts
browserContext?: unknown
```

Defined in:  [src/deck-components/Modal.tsx:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L8)

##### fnOnClose

```ts
fnOnClose?: Function
```

###### Type declaration

####### Signature

```ts
(): void
```

> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/Modal.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L13)
>

Defined in:  [src/deck-components/Modal.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L13)

##### popupHeight

```ts
popupHeight?: number
```

Defined in:  [src/deck-components/Modal.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L14)

##### popupWidth

```ts
popupWidth?: number
```

Defined in:  [src/deck-components/Modal.tsx:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L15)

##### promiseRenderComplete

```ts
promiseRenderComplete?: Promise<void>
```

Defined in:  [src/deck-components/Modal.tsx:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L16)

##### strTitle

```ts
strTitle?: string
```

Defined in:  [src/deck-components/Modal.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L17)

---

### ShowModalResult

#### Index

##### Properties

- Close
- Update

#### Properties

##### Close

```ts
Close: Function
```

###### Type declaration

####### Signature

```ts
(): void
```

> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/Modal.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L22)
>

Defined in:  [src/deck-components/Modal.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L22)

##### Update

```ts
Update: Function
```

###### Type declaration

####### Signature

```ts
(modal: ReactNode): void
```

> ####### Parameters
>
> | Name | Type |
> | :------ | :------ |
> | `modal` | `ReactNode` |
>
> ####### Returns
>
> `void`
>
> Defined in:  [src/deck-components/Modal.tsx:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L29)
>

Defined in:  [src/deck-components/Modal.tsx:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L29)

## Functions

### ConfirmModal()

#### Signature

```ts
ConfirmModal(props: PropsWithChildren<ConfirmModalProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[ConfirmModalProps](deck/components/Modal#confirmmodalprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### ModalRoot()

#### Signature

```ts
ModalRoot(props: PropsWithChildren<ModalRootProps>, context?: any): null | ReactElement<any, any>
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`\<[ModalRootProps](deck/components/Modal#modalrootprops)\> |
| `context?` | `any` |

#### Returns

`null` \| `ReactElement`\<`any`, `any`\>

Defined in:  node\_modules/.pnpm/@types+react@16.14.0/node\_modules/@types/react/index.d.ts:544

---

### showModal()

#### Signature

```ts
showModal(modal: ReactNode, parent?: EventTarget, props: ShowModalProps = ...): ShowModalResult
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `modal` | `ReactNode` |
| `parent?` | [EventTarget]( https://developer.mozilla.org/en-US/docs/Web/API/EventTarget ) |
| `props` | [ShowModalProps](deck/components/Modal#showmodalprops) |

#### Returns

[ShowModalResult](deck/components/Modal#showmodalresult)

Defined in:  [src/deck-components/Modal.tsx:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Modal.tsx#L65)
