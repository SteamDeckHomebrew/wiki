---
title: "deck-components/Router"
editor: "markdown"
published: true
---

# deck-components/Router

## Index

### Enumerations

- DisplayStatus
- QuickAccessTab
- SideMenu

### Interfaces

- MenuStore
- Navigation
- Router
- WindowRouter
- WindowStore

### Type Aliases

- AppOverview

### Variables

- Navigation
- Router

## Enumerations

### DisplayStatus

#### Index

##### Enumeration Members

- AvailForFree
- AvailGuestPass
- AvailToBorrow
- BorrowerLocked
- CloudError
- CloudOutOfDate
- DownloadDisabled
- DownloadPaused
- DownloadQueued
- DownloadRequired
- Downloading
- Installing
- Invalid
- InvalidPlatform
- Launching
- LicenseExpired
- LicensePending
- NotLaunchable
- PreloadComplete
- PresaleOnly
- Purchase
- ReadyToInstall
- ReadyToLaunch
- ReadyToPreload
- RegionRestricted
- Running
- Synchronizing
- Terminating
- Unavailable
- Uninstalling
- UpdateDisabled
- UpdatePaused
- UpdateQueued
- UpdateRequired
- Updating
- Validating

#### Enumeration Members

##### AvailForFree

```ts
AvailForFree = 28
```

Defined in:  [src/deck-components/Router.tsx:49](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L49)

##### AvailGuestPass

```ts
AvailGuestPass = 30
```

Defined in:  [src/deck-components/Router.tsx:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L51)

##### AvailToBorrow

```ts
AvailToBorrow = 29
```

Defined in:  [src/deck-components/Router.tsx:50](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L50)

##### BorrowerLocked

```ts
BorrowerLocked = 17
```

Defined in:  [src/deck-components/Router.tsx:38](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L38)

##### CloudError

```ts
CloudError = 34
```

Defined in:  [src/deck-components/Router.tsx:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L55)

##### CloudOutOfDate

```ts
CloudOutOfDate = 35
```

Defined in:  [src/deck-components/Router.tsx:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L56)

##### DownloadDisabled

```ts
DownloadDisabled = 25
```

Defined in:  [src/deck-components/Router.tsx:46](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L46)

##### DownloadPaused

```ts
DownloadPaused = 22
```

Defined in:  [src/deck-components/Router.tsx:43](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L43)

##### DownloadQueued

```ts
DownloadQueued = 23
```

Defined in:  [src/deck-components/Router.tsx:44](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L44)

##### DownloadRequired

```ts
DownloadRequired = 24
```

Defined in:  [src/deck-components/Router.tsx:45](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L45)

##### Downloading

```ts
Downloading = 7
```

Defined in:  [src/deck-components/Router.tsx:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L29)

##### Installing

```ts
Installing = 3
```

Defined in:  [src/deck-components/Router.tsx:25](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L25)

##### Invalid

```ts
Invalid = 0
```

Defined in:  [src/deck-components/Router.tsx:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L22)

##### InvalidPlatform

```ts
InvalidPlatform = 14
```

Defined in:  [src/deck-components/Router.tsx:36](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L36)

##### Launching

```ts
Launching = 1
```

Defined in:  [src/deck-components/Router.tsx:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L23)

##### LicenseExpired

```ts
LicenseExpired = 27
```

Defined in:  [src/deck-components/Router.tsx:48](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L48)

##### LicensePending

```ts
LicensePending = 26
```

Defined in:  [src/deck-components/Router.tsx:47](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L47)

##### NotLaunchable

```ts
NotLaunchable = 33
```

Defined in:  [src/deck-components/Router.tsx:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L54)

##### PreloadComplete

```ts
PreloadComplete = 16
```

Defined in:  [src/deck-components/Router.tsx:37](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L37)

##### PresaleOnly

```ts
PresaleOnly = 13
```

Defined in:  [src/deck-components/Router.tsx:35](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L35)

##### Purchase

```ts
Purchase = 31
```

Defined in:  [src/deck-components/Router.tsx:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L52)

##### ReadyToInstall

```ts
ReadyToInstall = 9
```

Defined in:  [src/deck-components/Router.tsx:31](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L31)

##### ReadyToLaunch

```ts
ReadyToLaunch = 11
```

Defined in:  [src/deck-components/Router.tsx:33](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L33)

##### ReadyToPreload

```ts
ReadyToPreload = 10
```

Defined in:  [src/deck-components/Router.tsx:32](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L32)

##### RegionRestricted

```ts
RegionRestricted = 12
```

Defined in:  [src/deck-components/Router.tsx:34](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L34)

##### Running

```ts
Running = 4
```

Defined in:  [src/deck-components/Router.tsx:26](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L26)

##### Synchronizing

```ts
Synchronizing = 8
```

Defined in:  [src/deck-components/Router.tsx:30](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L30)

##### Terminating

```ts
Terminating = 36
```

Defined in:  [src/deck-components/Router.tsx:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L57)

##### Unavailable

```ts
Unavailable = 32
```

Defined in:  [src/deck-components/Router.tsx:53](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L53)

##### Uninstalling

```ts
Uninstalling = 2
```

Defined in:  [src/deck-components/Router.tsx:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L24)

##### UpdateDisabled

```ts
UpdateDisabled = 21
```

Defined in:  [src/deck-components/Router.tsx:42](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L42)

##### UpdatePaused

```ts
UpdatePaused = 18
```

Defined in:  [src/deck-components/Router.tsx:39](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L39)

##### UpdateQueued

```ts
UpdateQueued = 19
```

Defined in:  [src/deck-components/Router.tsx:40](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L40)

##### UpdateRequired

```ts
UpdateRequired = 20
```

Defined in:  [src/deck-components/Router.tsx:41](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L41)

##### Updating

```ts
Updating = 6
```

Defined in:  [src/deck-components/Router.tsx:28](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L28)

##### Validating

```ts
Validating = 5
```

Defined in:  [src/deck-components/Router.tsx:27](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L27)

---

### QuickAccessTab

#### Index

##### Enumeration Members

- Decky
- Friends
- Help
- Notifications
- Perf
- RemotePlayTogetherControls
- Settings
- VoiceChat

#### Enumeration Members

##### Decky

```ts
Decky = 7
```

Defined in:  [src/deck-components/Router.tsx:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L18)

##### Friends

```ts
Friends = 3
```

Defined in:  [src/deck-components/Router.tsx:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L14)

##### Help

```ts
Help = 6
```

Defined in:  [src/deck-components/Router.tsx:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L17)

##### Notifications

```ts
Notifications = 0
```

Defined in:  [src/deck-components/Router.tsx:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L11)

##### Perf

```ts
Perf = 5
```

Defined in:  [src/deck-components/Router.tsx:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L16)

##### RemotePlayTogetherControls

```ts
RemotePlayTogetherControls = 1
```

Defined in:  [src/deck-components/Router.tsx:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L12)

##### Settings

```ts
Settings = 4
```

Defined in:  [src/deck-components/Router.tsx:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L15)

##### VoiceChat

```ts
VoiceChat = 2
```

Defined in:  [src/deck-components/Router.tsx:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L13)

---

### SideMenu

#### Index

##### Enumeration Members

- Main
- None
- QuickAccess

#### Enumeration Members

##### Main

```ts
Main = 1
```

Defined in:  [src/deck-components/Router.tsx:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L6)

##### None

```ts
None = 0
```

Defined in:  [src/deck-components/Router.tsx:5](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L5)

##### QuickAccess

```ts
QuickAccess = 2
```

Defined in:  [src/deck-components/Router.tsx:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L7)

## Interfaces

### MenuStore

#### Index

##### Methods

- OpenMainMenu
- OpenQuickAccessMenu
- OpenSideMenu

#### Methods

##### OpenMainMenu()

###### Signature

```ts
OpenMainMenu(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:70](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L70)

##### OpenQuickAccessMenu()

###### Signature

```ts
OpenQuickAccessMenu(quickAccessTab?: QuickAccessTab): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `quickAccessTab?` | [QuickAccessTab](deck/components/Router#quickaccesstab) |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:69](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L69)

##### OpenSideMenu()

###### Signature

```ts
OpenSideMenu(sideMenu: SideMenu): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `sideMenu` | [SideMenu](deck/components/Router#sidemenu) |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:68](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L68)

---

### Navigation

#### Index

##### Methods

- CloseSideMenus
- Navigate
- NavigateBack
- NavigateToAppProperties
- NavigateToChat
- NavigateToExternalWeb
- NavigateToInvites
- NavigateToLayoutPreview
- NavigateToLibraryTab
- NavigateToSteamWeb
- NavigateToWebRoute
- OpenMainMenu
- OpenPowerMenu
- OpenQuickAccessMenu
- OpenSideMenu

#### Methods

##### CloseSideMenus()

###### Signature

```ts
CloseSideMenus(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:126](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L126)

##### Navigate()

###### Signature

```ts
Navigate(path: string): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:112](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L112)

##### NavigateBack()

###### Signature

```ts
NavigateBack(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:113](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L113)

##### NavigateToAppProperties()

###### Signature

```ts
NavigateToAppProperties(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:114](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L114)

##### NavigateToChat()

###### Signature

```ts
NavigateToChat(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:117](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L117)

##### NavigateToExternalWeb()

###### Signature

```ts
NavigateToExternalWeb(url: string): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:115](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L115)

##### NavigateToInvites()

###### Signature

```ts
NavigateToInvites(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:116](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L116)

##### NavigateToLayoutPreview()

###### Signature

```ts
NavigateToLayoutPreview(e: unknown): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `unknown` |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:119](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L119)

##### NavigateToLibraryTab()

###### Signature

```ts
NavigateToLibraryTab(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:118](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L118)

##### NavigateToSteamWeb()

###### Signature

```ts
NavigateToSteamWeb(url: string): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:120](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L120)

##### NavigateToWebRoute()

###### Signature

```ts
NavigateToWebRoute(unknown?: any, unknown2?: any): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `unknown?` | `any` |
| `unknown2?` | `any` |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:121](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L121)

##### OpenMainMenu()

###### Signature

```ts
OpenMainMenu(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:124](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L124)

##### OpenPowerMenu()

###### Signature

```ts
OpenPowerMenu(unknown?: any): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `unknown?` | `any` |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:125](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L125)

##### OpenQuickAccessMenu()

###### Signature

```ts
OpenQuickAccessMenu(quickAccessTab?: QuickAccessTab): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `quickAccessTab?` | [QuickAccessTab](deck/components/Router#quickaccesstab) |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:123](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L123)

##### OpenSideMenu()

###### Signature

```ts
OpenSideMenu(sideMenu: SideMenu): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `sideMenu` | [SideMenu](deck/components/Router#sidemenu) |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:122](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L122)

---

### Router

#### Index

##### Properties

- WindowStore

##### Accessors

- MainRunningApp
- RunningApps

##### Methods

- CloseSideMenus
- Navigate
- NavigateToAppProperties
- NavigateToChat
- NavigateToExternalWeb
- NavigateToInvites
- NavigateToLayoutPreview
- NavigateToLibraryTab
- OpenPowerMenu

#### Properties

##### WindowStore

```ts
WindowStore?: WindowStore
```

Defined in:  [src/deck-components/Router.tsx:90](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L90)

#### Accessors

##### MainRunningApp

###### Signature

```ts
MainRunningApp(): undefined | AppOverview
```

###### Returns

`undefined` \| [AppOverview](deck/components/Router#appoverview)

Defined in:  [src/deck-components/Router.tsx:101](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L101)

##### RunningApps

###### Signature

```ts
RunningApps(): AppOverview[]
```

###### Returns

[AppOverview](deck/components/Router#appoverview)[]

Defined in:  [src/deck-components/Router.tsx:100](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L100)

#### Methods

##### CloseSideMenus()

###### Signature

```ts
CloseSideMenus(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:91](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L91)

##### Navigate()

###### Signature

```ts
Navigate(path: string): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:92](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L92)

##### NavigateToAppProperties()

###### Signature

```ts
NavigateToAppProperties(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:93](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L93)

##### NavigateToChat()

###### Signature

```ts
NavigateToChat(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:96](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L96)

##### NavigateToExternalWeb()

###### Signature

```ts
NavigateToExternalWeb(url: string): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:94](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L94)

##### NavigateToInvites()

###### Signature

```ts
NavigateToInvites(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:95](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L95)

##### NavigateToLayoutPreview()

###### Signature

```ts
NavigateToLayoutPreview(e: unknown): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `e` | `unknown` |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:98](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L98)

##### NavigateToLibraryTab()

###### Signature

```ts
NavigateToLibraryTab(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:97](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L97)

##### OpenPowerMenu()

###### Signature

```ts
OpenPowerMenu(unknown?: any): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `unknown?` | `any` |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:99](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L99)

---

### WindowRouter

#### Index

##### Properties

- BrowserWindow
- MenuStore

##### Methods

- Navigate
- NavigateBack
- NavigateToChat
- NavigateToSteamWeb
- NavigateToWebRoute

#### Properties

##### BrowserWindow

```ts
BrowserWindow: Window
```

Defined in:  [src/deck-components/Router.tsx:74](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L74)

##### MenuStore

```ts
MenuStore: MenuStore
```

Defined in:  [src/deck-components/Router.tsx:75](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L75)

#### Methods

##### Navigate()

###### Signature

```ts
Navigate(path: string): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `path` | `string` |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:76](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L76)

##### NavigateBack()

###### Signature

```ts
NavigateBack(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:79](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L79)

##### NavigateToChat()

###### Signature

```ts
NavigateToChat(): void
```

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:77](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L77)

##### NavigateToSteamWeb()

###### Signature

```ts
NavigateToSteamWeb(url: string): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:78](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L78)

##### NavigateToWebRoute()

###### Signature

```ts
NavigateToWebRoute(unknown?: any, unknown2?: any): void
```

###### Parameters

| Name | Type |
| :------ | :------ |
| `unknown?` | `any` |
| `unknown2?` | `any` |

###### Returns

`void`

Defined in:  [src/deck-components/Router.tsx:80](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L80)

---

### WindowStore

#### Index

##### Properties

- GamepadUIMainWindowInstance
- OverlayWindows
- SteamUIWindows

#### Properties

##### GamepadUIMainWindowInstance

```ts
GamepadUIMainWindowInstance?: WindowRouter
```

Defined in:  [src/deck-components/Router.tsx:84](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L84)

##### OverlayWindows

```ts
OverlayWindows: WindowRouter[]
```

Defined in:  [src/deck-components/Router.tsx:86](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L86)

##### SteamUIWindows

```ts
SteamUIWindows: WindowRouter[]
```

Defined in:  [src/deck-components/Router.tsx:85](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L85)

## Type Aliases

### AppOverview

```ts
AppOverview: Object
```

#### Type declaration

- `appid`: `string`

- `display_name`: `string`

- `display_status`: [DisplayStatus](deck/components/Router#displaystatus)

- `sort_as`: `string`

Defined in:  [src/deck-components/Router.tsx:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L60)

## Variables

### Navigation

```ts
Navigation: Navigation
```

Defined in:  [src/deck-components/Router.tsx:111](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L111) [src/deck-components/Router.tsx:129](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L129)

---

### Router

```ts
Router: Router
```

Defined in:  [src/deck-components/Router.tsx:89](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L89) [src/deck-components/Router.tsx:104](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/Router.tsx#L104)
