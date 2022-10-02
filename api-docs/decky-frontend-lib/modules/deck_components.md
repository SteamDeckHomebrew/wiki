[decky-frontend-lib](../README.md) / [Modules](../modules.md) / deck-components

# Module: deck-components

## Table of contents

### Modules

- [&lt;internal\&gt;](deck_components._internal_.md)

### Enumerations

- [DisplayStatus](../enums/deck_components.DisplayStatus.md)
- [GamepadButton](../enums/deck_components.GamepadButton.md)
- [NavEntryPositionPreferences](../enums/deck_components.NavEntryPositionPreferences.md)
- [QuickAccessTab](../enums/deck_components.QuickAccessTab.md)
- [SideMenu](../enums/deck_components.SideMenu.md)

### Interfaces

- [ButtonItemProps](../interfaces/deck_components.ButtonItemProps.md)
- [ButtonProps](../interfaces/deck_components.ButtonProps.md)
- [CarouselProps](../interfaces/deck_components.CarouselProps.md)
- [ConfirmModalProps](../interfaces/deck_components.ConfirmModalProps.md)
- [DialogButtonProps](../interfaces/deck_components.DialogButtonProps.md)
- [DialogCommonProps](../interfaces/deck_components.DialogCommonProps.md)
- [DropdownItemProps](../interfaces/deck_components.DropdownItemProps.md)
- [DropdownProps](../interfaces/deck_components.DropdownProps.md)
- [FieldProps](../interfaces/deck_components.FieldProps.md)
- [FocusRingProps](../interfaces/deck_components.FocusRingProps.md)
- [FocusableProps](../interfaces/deck_components.FocusableProps.md)
- [FooterLegendProps](../interfaces/deck_components.FooterLegendProps.md)
- [GamepadEventDetail](../interfaces/deck_components.GamepadEventDetail.md)
- [MenuGroupProps](../interfaces/deck_components.MenuGroupProps.md)
- [MenuItemProps](../interfaces/deck_components.MenuItemProps.md)
- [MenuProps](../interfaces/deck_components.MenuProps.md)
- [ModalRootProps](../interfaces/deck_components.ModalRootProps.md)
- [MultiDropdownOption](../interfaces/deck_components.MultiDropdownOption.md)
- [NotchLabel](../interfaces/deck_components.NotchLabel.md)
- [PanelSectionProps](../interfaces/deck_components.PanelSectionProps.md)
- [ProgressBarItemProps](../interfaces/deck_components.ProgressBarItemProps.md)
- [ProgressBarProps](../interfaces/deck_components.ProgressBarProps.md)
- [ProgressBarWithInfoProps](../interfaces/deck_components.ProgressBarWithInfoProps.md)
- [Router](../interfaces/deck_components.Router.md)
- [ShowModalProps](../interfaces/deck_components.ShowModalProps.md)
- [ShowModalResult](../interfaces/deck_components.ShowModalResult.md)
- [SidebarNavigationPages](../interfaces/deck_components.SidebarNavigationPages.md)
- [SidebarNavigationProps](../interfaces/deck_components.SidebarNavigationProps.md)
- [SingleDropdownOption](../interfaces/deck_components.SingleDropdownOption.md)
- [SliderFieldProps](../interfaces/deck_components.SliderFieldProps.md)
- [TextFieldProps](../interfaces/deck_components.TextFieldProps.md)
- [ToggleFieldProps](../interfaces/deck_components.ToggleFieldProps.md)
- [ToggleProps](../interfaces/deck_components.ToggleProps.md)

### Type Aliases

- [AppOverview](deck_components.md#appoverview)
- [DropdownOption](deck_components.md#dropdownoption)
- [GamepadEvent](deck_components.md#gamepadevent)

### Variables

- [Router](deck_components.md#router)
- [gamepadDialogClasses](deck_components.md#gamepaddialogclasses)
- [gamepadSliderClasses](deck_components.md#gamepadsliderclasses)
- [playSectionClasses](deck_components.md#playsectionclasses)
- [quickAccessControlsClasses](deck_components.md#quickaccesscontrolsclasses)
- [quickAccessMenuClasses](deck_components.md#quickaccessmenuclasses)
- [scrollClasses](deck_components.md#scrollclasses)
- [scrollPanelClasses](deck_components.md#scrollpanelclasses)
- [staticClasses](deck_components.md#staticclasses)
- [updaterFieldClasses](deck_components.md#updaterfieldclasses)

### Functions

- [Button](deck_components.md#button)
- [ButtonItem](deck_components.md#buttonitem)
- [Carousel](deck_components.md#carousel)
- [ConfirmModal](deck_components.md#confirmmodal)
- [DialogBody](deck_components.md#dialogbody)
- [DialogBodyText](deck_components.md#dialogbodytext)
- [DialogButton](deck_components.md#dialogbutton)
- [DialogButtonPrimary](deck_components.md#dialogbuttonprimary)
- [DialogButtonSecondary](deck_components.md#dialogbuttonsecondary)
- [DialogButtonSmall](deck_components.md#dialogbuttonsmall)
- [DialogControlsSection](deck_components.md#dialogcontrolssection)
- [DialogControlsSectionHeader](deck_components.md#dialogcontrolssectionheader)
- [DialogFooter](deck_components.md#dialogfooter)
- [DialogHeader](deck_components.md#dialogheader)
- [DialogLabel](deck_components.md#dialoglabel)
- [DialogSubHeader](deck_components.md#dialogsubheader)
- [Dropdown](deck_components.md#dropdown)
- [DropdownItem](deck_components.md#dropdownitem)
- [Field](deck_components.md#field)
- [FocusRing](deck_components.md#focusring)
- [Focusable](deck_components.md#focusable)
- [Menu](deck_components.md#menu)
- [MenuGroup](deck_components.md#menugroup)
- [MenuItem](deck_components.md#menuitem)
- [ModalRoot](deck_components.md#modalroot)
- [PanelSection](deck_components.md#panelsection)
- [PanelSectionRow](deck_components.md#panelsectionrow)
- [ProgressBar](deck_components.md#progressbar)
- [ProgressBarItem](deck_components.md#progressbaritem)
- [ProgressBarWithInfo](deck_components.md#progressbarwithinfo)
- [SidebarNavigation](deck_components.md#sidebarnavigation)
- [SliderField](deck_components.md#sliderfield)
- [Spinner](deck_components.md#spinner)
- [SteamSpinner](deck_components.md#steamspinner)
- [TextField](deck_components.md#textfield)
- [Toggle](deck_components.md#toggle)
- [ToggleField](deck_components.md#togglefield)
- [showContextMenu](deck_components.md#showcontextmenu)
- [showModal](deck_components.md#showmodal)

## Type Aliases

### AppOverview

Ƭ **AppOverview**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `appid` | `string` |
| `display_name` | `string` |
| `display_status` | [`DisplayStatus`](../enums/deck_components.DisplayStatus.md) |
| `sort_as` | `string` |

#### Defined in

[src/deck-components/Router.tsx:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L59)

___

### DropdownOption

Ƭ **DropdownOption**: [`SingleDropdownOption`](../interfaces/deck_components.SingleDropdownOption.md) \| [`MultiDropdownOption`](../interfaces/deck_components.MultiDropdownOption.md)

#### Defined in

[src/deck-components/Dropdown.tsx:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Dropdown.tsx#L20)

___

### GamepadEvent

Ƭ **GamepadEvent**: [`CustomEvent`]( https://developer.mozilla.org/en-US/docs/Web/API/CustomEvent )<[`GamepadEventDetail`](../interfaces/deck_components.GamepadEventDetail.md)\>

#### Defined in

[src/deck-components/FooterLegend.ts:47](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/FooterLegend.ts#L47)

## Variables

### Router

• **Router**: [`Router`](deck_components.md#router)

#### Defined in

[src/deck-components/Router.tsx:66](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L66)

[src/deck-components/Router.tsx:93](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Router.tsx#L93)

___

### gamepadDialogClasses

• `Const` **gamepadDialogClasses**: [`GamepadDialogClasses`](deck_components._internal_.md#gamepaddialogclasses)

#### Defined in

[src/deck-components/static-classes.ts:368](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/static-classes.ts#L368)

___

### gamepadSliderClasses

• `Const` **gamepadSliderClasses**: [`GamepadSliderClasses`](deck_components._internal_.md#gamepadsliderclasses)

#### Defined in

[src/deck-components/static-classes.ts:372](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/static-classes.ts#L372)

___

### playSectionClasses

• `Const` **playSectionClasses**: [`PlaySectionClasses`](deck_components._internal_.md#playsectionclasses)

#### Defined in

[src/deck-components/static-classes.ts:371](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/static-classes.ts#L371)

___

### quickAccessControlsClasses

• `Const` **quickAccessControlsClasses**: [`QuickAccessControlsClasses`](deck_components._internal_.md#quickaccesscontrolsclasses)

#### Defined in

[src/deck-components/static-classes.ts:369](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/static-classes.ts#L369)

___

### quickAccessMenuClasses

• `Const` **quickAccessMenuClasses**: [`QuickAccessMenuClasses`](deck_components._internal_.md#quickaccessmenuclasses)

#### Defined in

[src/deck-components/static-classes.ts:358](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/static-classes.ts#L358)

___

### scrollClasses

• `Const` **scrollClasses**: [`ScrollPanelClasses`](deck_components._internal_.md#scrollpanelclasses) = `scrollPanelClasses`

**`Depreciated`**

please use scrollPanelClasses instead

#### Defined in

[src/deck-components/static-classes.ts:367](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/static-classes.ts#L367)

___

### scrollPanelClasses

• `Const` **scrollPanelClasses**: [`ScrollPanelClasses`](deck_components._internal_.md#scrollpanelclasses)

#### Defined in

[src/deck-components/static-classes.ts:363](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/static-classes.ts#L363)

___

### staticClasses

• `Const` **staticClasses**: [`QuickAccessMenuClasses`](deck_components._internal_.md#quickaccessmenuclasses) = `quickAccessMenuClasses`

**`Depreciated`**

please use quickAccessMenuClasses instead

#### Defined in

[src/deck-components/static-classes.ts:362](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/static-classes.ts#L362)

___

### updaterFieldClasses

• `Const` **updaterFieldClasses**: [`UpdaterFieldClasses`](deck_components._internal_.md#updaterfieldclasses)

#### Defined in

[src/deck-components/static-classes.ts:370](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/static-classes.ts#L370)

## Functions

### Button

▸ **Button**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`ButtonProps`](../interfaces/deck_components.ButtonProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### ButtonItem

▸ **ButtonItem**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`ButtonItemProps`](../interfaces/deck_components.ButtonItemProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### Carousel

▸ **Carousel**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`CarouselProps`](../interfaces/deck_components.CarouselProps.md) & `RefAttributes`<[`HTMLDivElement`]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLDivElement )\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:554

___

### ConfirmModal

▸ **ConfirmModal**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`ConfirmModalProps`](../interfaces/deck_components.ConfirmModalProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### DialogBody

▸ **DialogBody**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`DialogCommonProps`](../interfaces/deck_components.DialogCommonProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### DialogBodyText

▸ **DialogBodyText**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`DialogCommonProps`](../interfaces/deck_components.DialogCommonProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### DialogButton

▸ **DialogButton**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`DialogButtonProps`](../interfaces/deck_components.DialogButtonProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### DialogButtonPrimary

▸ **DialogButtonPrimary**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`DialogButtonProps`](../interfaces/deck_components.DialogButtonProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### DialogButtonSecondary

▸ **DialogButtonSecondary**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`DialogButtonProps`](../interfaces/deck_components.DialogButtonProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### DialogButtonSmall

▸ **DialogButtonSmall**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`DialogButtonProps`](../interfaces/deck_components.DialogButtonProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### DialogControlsSection

▸ **DialogControlsSection**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`DialogCommonProps`](../interfaces/deck_components.DialogCommonProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### DialogControlsSectionHeader

▸ **DialogControlsSectionHeader**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`DialogCommonProps`](../interfaces/deck_components.DialogCommonProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### DialogFooter

▸ **DialogFooter**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`DialogCommonProps`](../interfaces/deck_components.DialogCommonProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### DialogHeader

▸ **DialogHeader**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`DialogCommonProps`](../interfaces/deck_components.DialogCommonProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### DialogLabel

▸ **DialogLabel**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`DialogCommonProps`](../interfaces/deck_components.DialogCommonProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### DialogSubHeader

▸ **DialogSubHeader**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`DialogCommonProps`](../interfaces/deck_components.DialogCommonProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### Dropdown

▸ **Dropdown**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`DropdownProps`](../interfaces/deck_components.DropdownProps.md) |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:554

___

### DropdownItem

▸ **DropdownItem**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`DropdownItemProps`](../interfaces/deck_components.DropdownItemProps.md) |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:554

___

### Field

▸ **Field**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`FieldProps`](../interfaces/deck_components.FieldProps.md) & `RefAttributes`<[`HTMLDivElement`]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLDivElement )\>\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### FocusRing

▸ **FocusRing**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`FocusRingProps`](../interfaces/deck_components.FocusRingProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### Focusable

▸ **Focusable**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`FocusableProps`](../interfaces/deck_components.FocusableProps.md) & `RefAttributes`<[`HTMLDivElement`]( https://developer.mozilla.org/en-US/docs/Web/API/HTMLDivElement )\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:554

___

### Menu

▸ **Menu**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`MenuProps`](../interfaces/deck_components.MenuProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### MenuGroup

▸ **MenuGroup**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`MenuGroupProps`](../interfaces/deck_components.MenuGroupProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### MenuItem

▸ **MenuItem**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`MenuItemProps`](../interfaces/deck_components.MenuItemProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### ModalRoot

▸ **ModalRoot**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`ModalRootProps`](../interfaces/deck_components.ModalRootProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### PanelSection

▸ **PanelSection**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`PanelSectionProps`](../interfaces/deck_components.PanelSectionProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### PanelSectionRow

▸ **PanelSectionRow**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `Object` |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### ProgressBar

▸ **ProgressBar**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`ProgressBarProps`](../interfaces/deck_components.ProgressBarProps.md) |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:554

___

### ProgressBarItem

▸ **ProgressBarItem**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`ProgressBarItemProps`](../interfaces/deck_components.ProgressBarItemProps.md) |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:554

___

### ProgressBarWithInfo

▸ **ProgressBarWithInfo**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`ProgressBarWithInfoProps`](../interfaces/deck_components.ProgressBarWithInfoProps.md) |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:554

___

### SidebarNavigation

▸ **SidebarNavigation**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`SidebarNavigationProps`](../interfaces/deck_components.SidebarNavigationProps.md) |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:554

___

### SliderField

▸ **SliderField**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`SliderFieldProps`](../interfaces/deck_components.SliderFieldProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### Spinner

▸ **Spinner**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<`SVGAttributes`<[`SVGElement`]( https://developer.mozilla.org/en-US/docs/Web/API/SVGElement )\>\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### SteamSpinner

▸ **SteamSpinner**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<`SVGAttributes`<[`SVGElement`]( https://developer.mozilla.org/en-US/docs/Web/API/SVGElement )\>\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### TextField

▸ **TextField**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | [`TextFieldProps`](../interfaces/deck_components.TextFieldProps.md) |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:554

___

### Toggle

▸ **Toggle**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`ToggleProps`](../interfaces/deck_components.ToggleProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### ToggleField

▸ **ToggleField**(`props`, `context?`): ``null`` \| `ReactElement`<`any`, `any`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `props` | `PropsWithChildren`<[`ToggleFieldProps`](../interfaces/deck_components.ToggleFieldProps.md)\> |
| `context?` | `any` |

#### Returns

``null`` \| `ReactElement`<`any`, `any`\>

#### Defined in

node_modules/@types/react/index.d.ts:544

___

### showContextMenu

▸ **showContextMenu**(`children`, `parent?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `children` | `ReactNode` |
| `parent?` | [`EventTarget`]( https://developer.mozilla.org/en-US/docs/Web/API/EventTarget ) |

#### Returns

`void`

#### Defined in

[src/deck-components/Menu.tsx:5](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Menu.tsx#L5)

___

### showModal

▸ **showModal**(`modal`, `parent?`, `props?`): [`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`ShowModalResult`](../interfaces/deck_components.ShowModalResult.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `modal` | `ReactNode` |
| `parent?` | [`EventTarget`]( https://developer.mozilla.org/en-US/docs/Web/API/EventTarget ) |
| `props?` | [`ShowModalProps`](../interfaces/deck_components.ShowModalProps.md) |

#### Returns

[`Promise`]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise )<[`ShowModalResult`](../interfaces/deck_components.ShowModalResult.md)\>

#### Defined in

[src/deck-components/Modal.tsx:30](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82f604a/src/deck-components/Modal.tsx#L30)
