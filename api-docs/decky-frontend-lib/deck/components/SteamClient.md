---
title: "deck-components/SteamClient"
editor: "markdown"
published: true
---

# deck-components/SteamClient

## Index

### Interfaces

- AppDetails
- Apps
- LifetimeNotification
- SteamAppOverview
- SteamClient
- SteamShortcut
- Window

### Type Aliases

- AppAchievements
- AppLanguages

## Interfaces

### AppDetails

#### Index

##### Properties

- achievements
- bCanMoveInstallFolder
- bCloudAvailable
- bCloudEnabledForAccount
- bCloudEnabledForApp
- bCloudSyncOnSuspendAvailable
- bCloudSyncOnSuspendEnabled
- bCommunityMarketPresence
- bEnableAllowDesktopConfiguration
- bFreeRemovableLicense
- bHasAllLegacyCDKeys
- bHasAnyLocalContent
- bHasLockedPrivateBetas
- bIsExcludedFromSharing
- bIsSubscribedTo
- bOverlayEnabled
- bOverrideInternalResolution
- bRequiresLegacyCDKey
- bShortcutIsVR
- bShowCDKeyInMenus
- bShowControllerConfig
- bSupportsCDKeyCopyToClipboard
- bVRGameTheatreEnabled
- bWorkshopVisible
- eAppOwnershipFlags
- eAutoUpdateValue
- eBackgroundDownloads
- eCloudSync
- eControllerRumblePreference
- eDisplayStatus
- eEnableThirdPartyControllerConfiguration
- eSteamInputControllerMask
- iInstallFolder
- lDiskUsageBytes
- lDlcUsageBytes
- nBuildID
- nCompatToolPriority
- nPlaytimeForever
- nScreenshots
- rtLastTimePlayed
- rtLastUpdated
- rtPurchased
- selectedLanguage
- strCloudBytesAvailable
- strCloudBytesUsed
- strCompatToolDisplayName
- strCompatToolName
- strDeveloperName
- strDeveloperURL
- strDisplayName
- strExternalSubscriptionURL
- strFlatpakAppID
- strHomepageURL
- strLaunchOptions
- strManualURL
- strOwnerSteamID
- strResolutionOverride
- strSelectedBeta
- strShortcutExe
- strShortcutLaunchOptions
- strShortcutStartDir
- strSteamDeckBlogURL
- unAppID
- vecBetas
- vecDLC
- vecDeckCompatTestResults
- vecLanguages
- vecLegacyCDKeys
- vecMusicAlbums
- vecPlatforms
- vecScreenShots

#### Properties

##### achievements

```ts
achievements: AppAchievements
```

Defined in:  [src/deck-components/SteamClient.ts:221](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L221)

##### bCanMoveInstallFolder

```ts
bCanMoveInstallFolder: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:222](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L222)

##### bCloudAvailable

```ts
bCloudAvailable: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:223](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L223)

##### bCloudEnabledForAccount

```ts
bCloudEnabledForAccount: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:224](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L224)

##### bCloudEnabledForApp

```ts
bCloudEnabledForApp: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:225](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L225)

##### bCloudSyncOnSuspendAvailable

```ts
bCloudSyncOnSuspendAvailable: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:226](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L226)

##### bCloudSyncOnSuspendEnabled

```ts
bCloudSyncOnSuspendEnabled: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:227](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L227)

##### bCommunityMarketPresence

```ts
bCommunityMarketPresence: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:228](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L228)

##### bEnableAllowDesktopConfiguration

```ts
bEnableAllowDesktopConfiguration: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:229](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L229)

##### bFreeRemovableLicense

```ts
bFreeRemovableLicense: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:230](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L230)

##### bHasAllLegacyCDKeys

```ts
bHasAllLegacyCDKeys: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:231](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L231)

##### bHasAnyLocalContent

```ts
bHasAnyLocalContent: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:232](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L232)

##### bHasLockedPrivateBetas

```ts
bHasLockedPrivateBetas: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:233](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L233)

##### bIsExcludedFromSharing

```ts
bIsExcludedFromSharing: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:234](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L234)

##### bIsSubscribedTo

```ts
bIsSubscribedTo: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:235](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L235)

##### bOverlayEnabled

```ts
bOverlayEnabled: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:236](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L236)

##### bOverrideInternalResolution

```ts
bOverrideInternalResolution: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:237](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L237)

##### bRequiresLegacyCDKey

```ts
bRequiresLegacyCDKey: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:238](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L238)

##### bShortcutIsVR

```ts
bShortcutIsVR: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:239](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L239)

##### bShowCDKeyInMenus

```ts
bShowCDKeyInMenus: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:240](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L240)

##### bShowControllerConfig

```ts
bShowControllerConfig: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:241](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L241)

##### bSupportsCDKeyCopyToClipboard

```ts
bSupportsCDKeyCopyToClipboard: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:242](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L242)

##### bVRGameTheatreEnabled

```ts
bVRGameTheatreEnabled: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:243](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L243)

##### bWorkshopVisible

```ts
bWorkshopVisible: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:244](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L244)

##### eAppOwnershipFlags

```ts
eAppOwnershipFlags: number
```

Defined in:  [src/deck-components/SteamClient.ts:245](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L245)

##### eAutoUpdateValue

```ts
eAutoUpdateValue: number
```

Defined in:  [src/deck-components/SteamClient.ts:246](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L246)

##### eBackgroundDownloads

```ts
eBackgroundDownloads: number
```

Defined in:  [src/deck-components/SteamClient.ts:247](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L247)

##### eCloudSync

```ts
eCloudSync: number
```

Defined in:  [src/deck-components/SteamClient.ts:248](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L248)

##### eControllerRumblePreference

```ts
eControllerRumblePreference: number
```

Defined in:  [src/deck-components/SteamClient.ts:249](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L249)

##### eDisplayStatus

```ts
eDisplayStatus: number
```

Defined in:  [src/deck-components/SteamClient.ts:250](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L250)

##### eEnableThirdPartyControllerConfiguration

```ts
eEnableThirdPartyControllerConfiguration: number
```

Defined in:  [src/deck-components/SteamClient.ts:251](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L251)

##### eSteamInputControllerMask

```ts
eSteamInputControllerMask: number
```

Defined in:  [src/deck-components/SteamClient.ts:252](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L252)

##### iInstallFolder

```ts
iInstallFolder: number
```

Defined in:  [src/deck-components/SteamClient.ts:253](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L253)

##### lDiskUsageBytes

```ts
lDiskUsageBytes: number
```

Defined in:  [src/deck-components/SteamClient.ts:254](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L254)

##### lDlcUsageBytes

```ts
lDlcUsageBytes: number
```

Defined in:  [src/deck-components/SteamClient.ts:255](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L255)

##### nBuildID

```ts
nBuildID: number
```

Defined in:  [src/deck-components/SteamClient.ts:256](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L256)

##### nCompatToolPriority

```ts
nCompatToolPriority: number
```

Defined in:  [src/deck-components/SteamClient.ts:257](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L257)

##### nPlaytimeForever

```ts
nPlaytimeForever: number
```

Defined in:  [src/deck-components/SteamClient.ts:258](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L258)

##### nScreenshots

```ts
nScreenshots: number
```

Defined in:  [src/deck-components/SteamClient.ts:259](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L259)

##### rtLastTimePlayed

```ts
rtLastTimePlayed: number
```

Defined in:  [src/deck-components/SteamClient.ts:260](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L260)

##### rtLastUpdated

```ts
rtLastUpdated: number
```

Defined in:  [src/deck-components/SteamClient.ts:261](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L261)

##### rtPurchased

```ts
rtPurchased: number
```

Defined in:  [src/deck-components/SteamClient.ts:262](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L262)

##### selectedLanguage

```ts
selectedLanguage: Object
```

###### Type declaration

- `strDisplayName`: `string`

- `strShortName`: `string`

Defined in:  [src/deck-components/SteamClient.ts:263](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L263)

##### strCloudBytesAvailable

```ts
strCloudBytesAvailable: string
```

Defined in:  [src/deck-components/SteamClient.ts:267](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L267)

##### strCloudBytesUsed

```ts
strCloudBytesUsed: string
```

Defined in:  [src/deck-components/SteamClient.ts:268](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L268)

##### strCompatToolDisplayName

```ts
strCompatToolDisplayName: string
```

Defined in:  [src/deck-components/SteamClient.ts:269](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L269)

##### strCompatToolName

```ts
strCompatToolName: string
```

Defined in:  [src/deck-components/SteamClient.ts:270](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L270)

##### strDeveloperName

```ts
strDeveloperName: string
```

Defined in:  [src/deck-components/SteamClient.ts:271](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L271)

##### strDeveloperURL

```ts
strDeveloperURL: string
```

Defined in:  [src/deck-components/SteamClient.ts:272](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L272)

##### strDisplayName

```ts
strDisplayName: string
```

Defined in:  [src/deck-components/SteamClient.ts:273](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L273)

##### strExternalSubscriptionURL

```ts
strExternalSubscriptionURL: string
```

Defined in:  [src/deck-components/SteamClient.ts:274](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L274)

##### strFlatpakAppID

```ts
strFlatpakAppID: string
```

Defined in:  [src/deck-components/SteamClient.ts:275](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L275)

##### strHomepageURL

```ts
strHomepageURL: string
```

Defined in:  [src/deck-components/SteamClient.ts:276](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L276)

##### strLaunchOptions

```ts
strLaunchOptions: string
```

Defined in:  [src/deck-components/SteamClient.ts:277](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L277)

##### strManualURL

```ts
strManualURL: string
```

Defined in:  [src/deck-components/SteamClient.ts:278](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L278)

##### strOwnerSteamID

```ts
strOwnerSteamID: string
```

Defined in:  [src/deck-components/SteamClient.ts:279](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L279)

##### strResolutionOverride

```ts
strResolutionOverride: string
```

Defined in:  [src/deck-components/SteamClient.ts:280](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L280)

##### strSelectedBeta

```ts
strSelectedBeta: string
```

Defined in:  [src/deck-components/SteamClient.ts:281](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L281)

##### strShortcutExe

```ts
strShortcutExe: string
```

Defined in:  [src/deck-components/SteamClient.ts:282](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L282)

##### strShortcutLaunchOptions

```ts
strShortcutLaunchOptions: string
```

Defined in:  [src/deck-components/SteamClient.ts:283](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L283)

##### strShortcutStartDir

```ts
strShortcutStartDir: string
```

Defined in:  [src/deck-components/SteamClient.ts:284](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L284)

##### strSteamDeckBlogURL

```ts
strSteamDeckBlogURL: string
```

Defined in:  [src/deck-components/SteamClient.ts:285](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L285)

##### unAppID

```ts
unAppID: number
```

Defined in:  [src/deck-components/SteamClient.ts:286](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L286)

##### vecBetas

```ts
vecBetas: any[]
```

Defined in:  [src/deck-components/SteamClient.ts:287](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L287)

##### vecDLC

```ts
vecDLC: any[]
```

Defined in:  [src/deck-components/SteamClient.ts:288](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L288)

##### vecDeckCompatTestResults

```ts
vecDeckCompatTestResults: any[]
```

Defined in:  [src/deck-components/SteamClient.ts:289](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L289)

##### vecLanguages

```ts
vecLanguages: AppLanguages[]
```

Defined in:  [src/deck-components/SteamClient.ts:290](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L290)

##### vecLegacyCDKeys

```ts
vecLegacyCDKeys: any[]
```

Defined in:  [src/deck-components/SteamClient.ts:291](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L291)

##### vecMusicAlbums

```ts
vecMusicAlbums: any[]
```

Defined in:  [src/deck-components/SteamClient.ts:292](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L292)

##### vecPlatforms

```ts
vecPlatforms: string[]
```

Defined in:  [src/deck-components/SteamClient.ts:293](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L293)

##### vecScreenShots

```ts
vecScreenShots: any[]
```

Defined in:  [src/deck-components/SteamClient.ts:294](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L294)

---

### Apps

#### Index

##### Properties

- AddShortcut
- AddUserTagToApps
- BackupFilesForApp
- BrowseLocalFilesForApp
- BrowseScreenshotForApp
- BrowseScreenshotsForApp
- CancelGameAction
- CancelLaunch
- ClearAndSetUserTagsOnApp
- ClearCustomArtworkForApp
- ClearCustomLogoPositionForApp
- ClearProton
- ClearUserTagsOnApps
- ContinueGameAction
- CreateDesktopShortcutForApp
- DeleteLocalScreenshot
- DownloadWorkshopItem
- FetchMarketingMessages
- GetAchievementsInTimeRange
- GetActiveGameActions
- GetAllShortcuts
- GetAvailableCompatTools
- GetCachedAppDetails
- GetCloudPendingRemoteOperations
- GetConflictingFileTimestamps
- GetDetailsForScreenshotUpload
- GetDownloadedWorkshopItems
- GetFriendAchievementsForApp
- GetFriendsWhoPlay
- GetGameActionDetails
- GetGameActionForApp
- GetLaunchOptionsForApp
- GetLibraryBootstrapData
- GetMyAchievementsForApp
- GetResolutionOverrideForApp
- GetScreenshotsInTimeRange
- GetShortcutData
- GetSoundtrackDetails
- GetStoreTagLocalization
- GetSubscribedWorkshopItems
- InstallApp
- InstallFlatpakAppAndCreateShortcut
- JoinAppContentBeta
- JoinAppContentBetaByPassword
- ListFlatpakApps
- LoadEula
- MarkEulaAccepted
- MarkEulaRejected
- MarkMarketingMessageSeen
- OpenAppSettingsDialog
- PromptToChangeShortcut
- PromptToSelectShortcutIcon
- RegisterForAchievementChanges
- RegisterForAppDetails
- RegisterForAppOverviewChanges
- RegisterForGameActionEnd
- RegisterForGameActionShowError
- RegisterForGameActionShowUI
- RegisterForGameActionStart
- RegisterForGameActionTaskChange
- RegisterForGameActionUserRequest
- RegisterForLocalizationChanges
- RegisterForMarketingMessages
- RegisterForWorkshopChanges
- RegisterForWorkshopItemDownloads
- RemoveShortcut
- RemoveUserTagFromApps
- ReportLibraryAssetCacheMiss
- ReportMarketingMessageSeen
- RequestIconDataForApp
- RequestLegacyCDKeysForApp
- ResetHiddenState
- RunGame
- SaveAchievementProgressCache
- ScanForShortcuts
- SetAppAutoUpdateBehavior
- SetAppBackgroundDownloadsBehavior
- SetAppCurrentLanguage
- SetAppHidden
- SetAppLaunchOptions
- SetAppResolutionOverride
- SetCachedAppDetails
- SetControllerRumblePreference
- SetCustomArtworkForApp
- SetCustomLogoPositionForApp
- SetDLCEnabled
- SetLocalScreenshotCaption
- SetLocalScreenshotSpoiler
- SetShortcutExe
- SetShortcutIsVR
- SetShortcutLaunchOptions
- SetShortcutName
- SetShortcutStartDir
- SetStreamingClientForApp
- SetThirdPartyControllerConfiguration
- ShowControllerConfigurator
- ShowStore
- SkipShaderProcessing
- SpecifyCompatTool
- StreamGame
- SubscribeWorkshopItem
- TerminateApp
- ToggleAllowDesktopConfiguration
- ToggleAppFamilyBlockedState
- ToggleAppSteamCloudEnabled
- ToggleAppSteamCloudSyncOnSuspendEnabled
- ToggleEnableDesktopTheatreForApp
- ToggleEnableSteamOverlayForApp
- ToggleOverrideResolutionForInternalDisplay
- UninstallApps
- UninstallFlatpakApp
- UploadLocalScreenshot
- VerifyApp
- VerifyFilesForApp

#### Properties

##### AddShortcut

```ts
AddShortcut: any
```

Defined in:  [src/deck-components/SteamClient.ts:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L56)

##### AddUserTagToApps

```ts
AddUserTagToApps: any
```

Defined in:  [src/deck-components/SteamClient.ts:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L11)

##### BackupFilesForApp

```ts
BackupFilesForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:31](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L31)

##### BrowseLocalFilesForApp

```ts
BrowseLocalFilesForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:28](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L28)

##### BrowseScreenshotForApp

```ts
BrowseScreenshotForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:30](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L30)

##### BrowseScreenshotsForApp

```ts
BrowseScreenshotsForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L29)

##### CancelGameAction

```ts
CancelGameAction: any
```

Defined in:  [src/deck-components/SteamClient.ts:94](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L94)

##### CancelLaunch

```ts
CancelLaunch: any
```

Defined in:  [src/deck-components/SteamClient.ts:88](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L88)

##### ClearAndSetUserTagsOnApp

```ts
ClearAndSetUserTagsOnApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L14)

##### ClearCustomArtworkForApp

```ts
ClearCustomArtworkForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:71](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L71)

##### ClearCustomLogoPositionForApp

```ts
ClearCustomLogoPositionForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:73](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L73)

##### ClearProton

```ts
ClearProton: any
```

Defined in:  [src/deck-components/SteamClient.ts:104](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L104)

##### ClearUserTagsOnApps

```ts
ClearUserTagsOnApps: any
```

Defined in:  [src/deck-components/SteamClient.ts:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L13)

##### ContinueGameAction

```ts
ContinueGameAction: any
```

Defined in:  [src/deck-components/SteamClient.ts:93](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L93)

##### CreateDesktopShortcutForApp

```ts
CreateDesktopShortcutForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:33](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L33)

##### DeleteLocalScreenshot

```ts
DeleteLocalScreenshot: any
```

Defined in:  [src/deck-components/SteamClient.ts:45](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L45)

##### DownloadWorkshopItem

```ts
DownloadWorkshopItem: any
```

Defined in:  [src/deck-components/SteamClient.ts:40](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L40)

##### FetchMarketingMessages

```ts
FetchMarketingMessages: any
```

Defined in:  [src/deck-components/SteamClient.ts:106](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L106)

##### GetAchievementsInTimeRange

```ts
GetAchievementsInTimeRange: any
```

Defined in:  [src/deck-components/SteamClient.ts:36](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L36)

##### GetActiveGameActions

```ts
GetActiveGameActions: any
```

Defined in:  [src/deck-components/SteamClient.ts:95](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L95)

##### GetAllShortcuts

```ts
GetAllShortcuts: any
```

Defined in:  [src/deck-components/SteamClient.ts:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L54)

##### GetAvailableCompatTools

```ts
GetAvailableCompatTools: any
```

Defined in:  [src/deck-components/SteamClient.ts:76](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L76)

##### GetCachedAppDetails

```ts
GetCachedAppDetails: any
```

Defined in:  [src/deck-components/SteamClient.ts:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L65)

##### GetCloudPendingRemoteOperations

```ts
GetCloudPendingRemoteOperations: any
```

Defined in:  [src/deck-components/SteamClient.ts:103](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L103)

##### GetConflictingFileTimestamps

```ts
GetConflictingFileTimestamps: any
```

Defined in:  [src/deck-components/SteamClient.ts:102](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L102)

##### GetDetailsForScreenshotUpload

```ts
GetDetailsForScreenshotUpload: any
```

Defined in:  [src/deck-components/SteamClient.ts:43](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L43)

##### GetDownloadedWorkshopItems

```ts
GetDownloadedWorkshopItems: any
```

Defined in:  [src/deck-components/SteamClient.ts:39](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L39)

##### GetFriendAchievementsForApp

```ts
GetFriendAchievementsForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L9)

##### GetFriendsWhoPlay

```ts
GetFriendsWhoPlay: any
```

Defined in:  [src/deck-components/SteamClient.ts:47](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L47)

##### GetGameActionDetails

```ts
GetGameActionDetails: any
```

Defined in:  [src/deck-components/SteamClient.ts:96](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L96)

##### GetGameActionForApp

```ts
GetGameActionForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:97](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L97)

##### GetLaunchOptionsForApp

```ts
GetLaunchOptionsForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L51)

##### GetLibraryBootstrapData

```ts
GetLibraryBootstrapData: any
```

Defined in:  [src/deck-components/SteamClient.ts:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L7)

##### GetMyAchievementsForApp

```ts
GetMyAchievementsForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L10)

##### GetResolutionOverrideForApp

```ts
GetResolutionOverrideForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L52)

##### GetScreenshotsInTimeRange

```ts
GetScreenshotsInTimeRange: any
```

Defined in:  [src/deck-components/SteamClient.ts:46](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L46)

##### GetShortcutData

```ts
GetShortcutData: any
```

Defined in:  [src/deck-components/SteamClient.ts:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L55)

##### GetSoundtrackDetails

```ts
GetSoundtrackDetails: any
```

Defined in:  [src/deck-components/SteamClient.ts:49](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L49)

##### GetStoreTagLocalization

```ts
GetStoreTagLocalization: any
```

Defined in:  [src/deck-components/SteamClient.ts:50](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L50)

##### GetSubscribedWorkshopItems

```ts
GetSubscribedWorkshopItems: any
```

Defined in:  [src/deck-components/SteamClient.ts:37](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L37)

##### InstallApp

```ts
InstallApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:84](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L84)

##### InstallFlatpakAppAndCreateShortcut

```ts
InstallFlatpakAppAndCreateShortcut: any
```

Defined in:  [src/deck-components/SteamClient.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L58)

##### JoinAppContentBeta

```ts
JoinAppContentBeta: any
```

Defined in:  [src/deck-components/SteamClient.ts:34](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L34)

##### JoinAppContentBetaByPassword

```ts
JoinAppContentBetaByPassword: any
```

Defined in:  [src/deck-components/SteamClient.ts:35](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L35)

##### ListFlatpakApps

```ts
ListFlatpakApps: any
```

Defined in:  [src/deck-components/SteamClient.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L59)

##### LoadEula

```ts
LoadEula: any
```

Defined in:  [src/deck-components/SteamClient.ts:101](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L101)

##### MarkEulaAccepted

```ts
MarkEulaAccepted: any
```

Defined in:  [src/deck-components/SteamClient.ts:99](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L99)

##### MarkEulaRejected

```ts
MarkEulaRejected: any
```

Defined in:  [src/deck-components/SteamClient.ts:100](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L100)

##### MarkMarketingMessageSeen

```ts
MarkMarketingMessageSeen: any
```

Defined in:  [src/deck-components/SteamClient.ts:107](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L107)

##### OpenAppSettingsDialog

```ts
OpenAppSettingsDialog: any
```

Defined in:  [src/deck-components/SteamClient.ts:115](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L115)

##### PromptToChangeShortcut

```ts
PromptToChangeShortcut: any
```

Defined in:  [src/deck-components/SteamClient.ts:82](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L82)

##### PromptToSelectShortcutIcon

```ts
PromptToSelectShortcutIcon: any
```

Defined in:  [src/deck-components/SteamClient.ts:83](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L83)

##### RegisterForAchievementChanges

```ts
RegisterForAchievementChanges: any
```

Defined in:  [src/deck-components/SteamClient.ts:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L8)

##### RegisterForAppDetails

```ts
RegisterForAppDetails: any
```

Defined in:  [src/deck-components/SteamClient.ts:3](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L3)

##### RegisterForAppOverviewChanges

```ts
RegisterForAppOverviewChanges: any
```

Defined in:  [src/deck-components/SteamClient.ts:2](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L2)

##### RegisterForGameActionEnd

```ts
RegisterForGameActionEnd: any
```

Defined in:  [src/deck-components/SteamClient.ts:110](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L110)

##### RegisterForGameActionShowError

```ts
RegisterForGameActionShowError: any
```

Defined in:  [src/deck-components/SteamClient.ts:113](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L113)

##### RegisterForGameActionShowUI

```ts
RegisterForGameActionShowUI: any
```

Defined in:  [src/deck-components/SteamClient.ts:114](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L114)

##### RegisterForGameActionStart

```ts
RegisterForGameActionStart: any
```

Defined in:  [src/deck-components/SteamClient.ts:109](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L109)

##### RegisterForGameActionTaskChange

```ts
RegisterForGameActionTaskChange: any
```

Defined in:  [src/deck-components/SteamClient.ts:111](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L111)

##### RegisterForGameActionUserRequest

```ts
RegisterForGameActionUserRequest: any
```

Defined in:  [src/deck-components/SteamClient.ts:112](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L112)

##### RegisterForLocalizationChanges

```ts
RegisterForLocalizationChanges: any
```

Defined in:  [src/deck-components/SteamClient.ts:4](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L4)

##### RegisterForMarketingMessages

```ts
RegisterForMarketingMessages: any
```

Defined in:  [src/deck-components/SteamClient.ts:105](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L105)

##### RegisterForWorkshopChanges

```ts
RegisterForWorkshopChanges: any
```

Defined in:  [src/deck-components/SteamClient.ts:5](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L5)

##### RegisterForWorkshopItemDownloads

```ts
RegisterForWorkshopItemDownloads: any
```

Defined in:  [src/deck-components/SteamClient.ts:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L6)

##### RemoveShortcut

```ts
RemoveShortcut: any
```

Defined in:  [src/deck-components/SteamClient.ts:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L57)

##### RemoveUserTagFromApps

```ts
RemoveUserTagFromApps: any
```

Defined in:  [src/deck-components/SteamClient.ts:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L12)

##### ReportLibraryAssetCacheMiss

```ts
ReportLibraryAssetCacheMiss: any
```

Defined in:  [src/deck-components/SteamClient.ts:67](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L67)

##### ReportMarketingMessageSeen

```ts
ReportMarketingMessageSeen: any
```

Defined in:  [src/deck-components/SteamClient.ts:108](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L108)

##### RequestIconDataForApp

```ts
RequestIconDataForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:74](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L74)

##### RequestLegacyCDKeysForApp

```ts
RequestLegacyCDKeysForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:48](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L48)

##### ResetHiddenState

```ts
ResetHiddenState: any
```

Defined in:  [src/deck-components/SteamClient.ts:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L16)

##### RunGame

```ts
RunGame: any
```

Defined in:  [src/deck-components/SteamClient.ts:85](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L85)

##### SaveAchievementProgressCache

```ts
SaveAchievementProgressCache: any
```

Defined in:  [src/deck-components/SteamClient.ts:68](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L68)

##### ScanForShortcuts

```ts
ScanForShortcuts: any
```

Defined in:  [src/deck-components/SteamClient.ts:53](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L53)

##### SetAppAutoUpdateBehavior

```ts
SetAppAutoUpdateBehavior: any
```

Defined in:  [src/deck-components/SteamClient.ts:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L20)

##### SetAppBackgroundDownloadsBehavior

```ts
SetAppBackgroundDownloadsBehavior: any
```

Defined in:  [src/deck-components/SteamClient.ts:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L21)

##### SetAppCurrentLanguage

```ts
SetAppCurrentLanguage: any
```

Defined in:  [src/deck-components/SteamClient.ts:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L19)

##### SetAppHidden

```ts
SetAppHidden: any
```

Defined in:  [src/deck-components/SteamClient.ts:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L15)

##### SetAppLaunchOptions

```ts
SetAppLaunchOptions: any
```

Defined in:  [src/deck-components/SteamClient.ts:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L17)

##### SetAppResolutionOverride

```ts
SetAppResolutionOverride: any
```

Defined in:  [src/deck-components/SteamClient.ts:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L18)

##### SetCachedAppDetails

```ts
SetCachedAppDetails: any
```

Defined in:  [src/deck-components/SteamClient.ts:66](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L66)

##### SetControllerRumblePreference

```ts
SetControllerRumblePreference: any
```

Defined in:  [src/deck-components/SteamClient.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L64)

##### SetCustomArtworkForApp

```ts
SetCustomArtworkForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:70](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L70)

##### SetCustomLogoPositionForApp

```ts
SetCustomLogoPositionForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:72](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L72)

##### SetDLCEnabled

```ts
SetDLCEnabled: any
```

Defined in:  [src/deck-components/SteamClient.ts:92](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L92)

##### SetLocalScreenshotCaption

```ts
SetLocalScreenshotCaption: any
```

Defined in:  [src/deck-components/SteamClient.ts:41](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L41)

##### SetLocalScreenshotSpoiler

```ts
SetLocalScreenshotSpoiler: any
```

Defined in:  [src/deck-components/SteamClient.ts:42](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L42)

##### SetShortcutExe

```ts
SetShortcutExe: any
```

Defined in:  [src/deck-components/SteamClient.ts:78](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L78)

##### SetShortcutIsVR

```ts
SetShortcutIsVR: any
```

Defined in:  [src/deck-components/SteamClient.ts:81](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L81)

##### SetShortcutLaunchOptions

```ts
SetShortcutLaunchOptions: any
```

Defined in:  [src/deck-components/SteamClient.ts:80](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L80)

##### SetShortcutName

```ts
SetShortcutName: any
```

Defined in:  [src/deck-components/SteamClient.ts:77](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L77)

##### SetShortcutStartDir

```ts
SetShortcutStartDir: any
```

Defined in:  [src/deck-components/SteamClient.ts:79](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L79)

##### SetStreamingClientForApp

```ts
SetStreamingClientForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:69](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L69)

##### SetThirdPartyControllerConfiguration

```ts
SetThirdPartyControllerConfiguration: any
```

Defined in:  [src/deck-components/SteamClient.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L62)

##### ShowControllerConfigurator

```ts
ShowControllerConfigurator: any
```

Defined in:  [src/deck-components/SteamClient.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L61)

##### ShowStore

```ts
ShowStore: any
```

Defined in:  [src/deck-components/SteamClient.ts:91](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L91)

##### SkipShaderProcessing

```ts
SkipShaderProcessing: any
```

Defined in:  [src/deck-components/SteamClient.ts:98](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L98)

##### SpecifyCompatTool

```ts
SpecifyCompatTool: any
```

Defined in:  [src/deck-components/SteamClient.ts:75](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L75)

##### StreamGame

```ts
StreamGame: any
```

Defined in:  [src/deck-components/SteamClient.ts:87](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L87)

##### SubscribeWorkshopItem

```ts
SubscribeWorkshopItem: any
```

Defined in:  [src/deck-components/SteamClient.ts:38](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L38)

##### TerminateApp

```ts
TerminateApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:89](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L89)

##### ToggleAllowDesktopConfiguration

```ts
ToggleAllowDesktopConfiguration: any
```

Defined in:  [src/deck-components/SteamClient.ts:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L63)

##### ToggleAppFamilyBlockedState

```ts
ToggleAppFamilyBlockedState: any
```

Defined in:  [src/deck-components/SteamClient.ts:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L22)

##### ToggleAppSteamCloudEnabled

```ts
ToggleAppSteamCloudEnabled: any
```

Defined in:  [src/deck-components/SteamClient.ts:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L23)

##### ToggleAppSteamCloudSyncOnSuspendEnabled

```ts
ToggleAppSteamCloudSyncOnSuspendEnabled: any
```

Defined in:  [src/deck-components/SteamClient.ts:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L24)

##### ToggleEnableDesktopTheatreForApp

```ts
ToggleEnableDesktopTheatreForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:27](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L27)

##### ToggleEnableSteamOverlayForApp

```ts
ToggleEnableSteamOverlayForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:26](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L26)

##### ToggleOverrideResolutionForInternalDisplay

```ts
ToggleOverrideResolutionForInternalDisplay: any
```

Defined in:  [src/deck-components/SteamClient.ts:25](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L25)

##### UninstallApps

```ts
UninstallApps: any
```

Defined in:  [src/deck-components/SteamClient.ts:90](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L90)

##### UninstallFlatpakApp

```ts
UninstallFlatpakApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L60)

##### UploadLocalScreenshot

```ts
UploadLocalScreenshot: any
```

Defined in:  [src/deck-components/SteamClient.ts:44](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L44)

##### VerifyApp

```ts
VerifyApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:86](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L86)

##### VerifyFilesForApp

```ts
VerifyFilesForApp: any
```

Defined in:  [src/deck-components/SteamClient.ts:32](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L32)

---

### LifetimeNotification

#### Prop

is not properly set by Steam for non-steam game shortcuts, so it defaults to 0 for them

#### Index

##### Properties

- bRunning
- nInstanceID
- unAppID

#### Properties

##### bRunning

```ts
bRunning: boolean
```

Defined in:  [src/deck-components/SteamClient.ts:204](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L204)

##### nInstanceID

```ts
nInstanceID: number
```

Defined in:  [src/deck-components/SteamClient.ts:203](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L203)

##### unAppID

```ts
unAppID: number
```

Defined in:  [src/deck-components/SteamClient.ts:202](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L202)

---

### SteamAppOverview

#### Index

##### Properties

- display_name
- gameid

#### Properties

##### display\_name

```ts
display_name: string
```

Defined in:  [src/deck-components/SteamClient.ts:298](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L298)

##### gameid

```ts
gameid: string
```

Defined in:  [src/deck-components/SteamClient.ts:299](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L299)

---

### SteamClient

#### Index

##### Properties

- Apps
- Browser
- BrowserView
- ClientNotifications
- Cloud
- Console
- Downloads
- FamilySharing
- FriendSettings
- Friends
- GameSessions
- Input
- InstallFolder
- Installs
- MachineStorage
- Messaging
- Notifications
- OpenVR
- Overlay
- Parental
- RegisterIFrameNavigatedCallback
- RemotePlay
- RoamingStorage
- Screenshots
- Settings
- SharedConnection
- Stats
- Storage
- Streaming
- System
- UI
- URL
- Updates
- User
- WebChat
- Window

#### Properties

##### Apps

```ts
Apps: Apps
```

Defined in:  [src/deck-components/SteamClient.ts:148](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L148)

##### Browser

```ts
Browser: any
```

Defined in:  [src/deck-components/SteamClient.ts:149](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L149)

##### BrowserView

```ts
BrowserView: any
```

Defined in:  [src/deck-components/SteamClient.ts:150](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L150)

##### ClientNotifications

```ts
ClientNotifications: any
```

Defined in:  [src/deck-components/SteamClient.ts:151](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L151)

##### Cloud

```ts
Cloud: any
```

Defined in:  [src/deck-components/SteamClient.ts:152](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L152)

##### Console

```ts
Console: any
```

Defined in:  [src/deck-components/SteamClient.ts:153](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L153)

##### Downloads

```ts
Downloads: any
```

Defined in:  [src/deck-components/SteamClient.ts:154](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L154)

##### FamilySharing

```ts
FamilySharing: any
```

Defined in:  [src/deck-components/SteamClient.ts:155](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L155)

##### FriendSettings

```ts
FriendSettings: any
```

Defined in:  [src/deck-components/SteamClient.ts:156](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L156)

##### Friends

```ts
Friends: any
```

Defined in:  [src/deck-components/SteamClient.ts:157](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L157)

##### GameSessions

```ts
GameSessions: any
```

Defined in:  [src/deck-components/SteamClient.ts:158](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L158)

##### Input

```ts
Input: any
```

Defined in:  [src/deck-components/SteamClient.ts:159](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L159)

##### InstallFolder

```ts
InstallFolder: any
```

Defined in:  [src/deck-components/SteamClient.ts:160](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L160)

##### Installs

```ts
Installs: any
```

Defined in:  [src/deck-components/SteamClient.ts:161](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L161)

##### MachineStorage

```ts
MachineStorage: any
```

Defined in:  [src/deck-components/SteamClient.ts:162](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L162)

##### Messaging

```ts
Messaging: any
```

Defined in:  [src/deck-components/SteamClient.ts:163](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L163)

##### Notifications

```ts
Notifications: any
```

Defined in:  [src/deck-components/SteamClient.ts:164](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L164)

##### OpenVR

```ts
OpenVR: any
```

Defined in:  [src/deck-components/SteamClient.ts:165](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L165)

##### Overlay

```ts
Overlay: any
```

Defined in:  [src/deck-components/SteamClient.ts:166](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L166)

##### Parental

```ts
Parental: any
```

Defined in:  [src/deck-components/SteamClient.ts:167](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L167)

##### RegisterIFrameNavigatedCallback

```ts
RegisterIFrameNavigatedCallback: any
```

Defined in:  [src/deck-components/SteamClient.ts:168](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L168)

##### RemotePlay

```ts
RemotePlay: any
```

Defined in:  [src/deck-components/SteamClient.ts:169](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L169)

##### RoamingStorage

```ts
RoamingStorage: any
```

Defined in:  [src/deck-components/SteamClient.ts:170](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L170)

##### Screenshots

```ts
Screenshots: any
```

Defined in:  [src/deck-components/SteamClient.ts:171](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L171)

##### Settings

```ts
Settings: any
```

Defined in:  [src/deck-components/SteamClient.ts:172](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L172)

##### SharedConnection

```ts
SharedConnection: any
```

Defined in:  [src/deck-components/SteamClient.ts:173](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L173)

##### Stats

```ts
Stats: any
```

Defined in:  [src/deck-components/SteamClient.ts:174](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L174)

##### Storage

```ts
Storage: any
```

Defined in:  [src/deck-components/SteamClient.ts:175](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L175)

##### Streaming

```ts
Streaming: any
```

Defined in:  [src/deck-components/SteamClient.ts:176](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L176)

##### System

```ts
System: any
```

Defined in:  [src/deck-components/SteamClient.ts:177](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L177)

##### UI

```ts
UI: any
```

Defined in:  [src/deck-components/SteamClient.ts:178](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L178)

##### URL

```ts
URL: any
```

Defined in:  [src/deck-components/SteamClient.ts:179](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L179)

##### Updates

```ts
Updates: any
```

Defined in:  [src/deck-components/SteamClient.ts:180](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L180)

##### User

```ts
User: any
```

Defined in:  [src/deck-components/SteamClient.ts:181](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L181)

##### WebChat

```ts
WebChat: any
```

Defined in:  [src/deck-components/SteamClient.ts:182](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L182)

##### Window

```ts
Window: Window
```

Defined in:  [src/deck-components/SteamClient.ts:183](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L183)

---

### SteamShortcut

#### Index

##### Properties

- appid
- data

#### Properties

##### appid

```ts
appid: number
```

Defined in:  [src/deck-components/SteamClient.ts:187](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L187)

##### data

```ts
data: Object
```

###### Type declaration

- `bIsApplication`: `boolean`

- `strAppName`: `string`

- `strArguments`: `string`

- `strExePath`: `string`

- `strShortcutPath`: `string`

- `strSortAs`: `string`

Defined in:  [src/deck-components/SteamClient.ts:188](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L188)

---

### Window

#### Index

##### Properties

- BringToFront
- FlashWindow
- GamescopeBlur
- GetBrowserID
- GetMousePositionDetails
- GetWindowDimensions
- GetWindowRestoreDetails
- HideWindow
- IsWindowMinimized
- Minimize
- MoveTo
- PositionWindowRelative
- ProcessShuttingDown
- RegisterForExternalDisplayChanged
- ResizeTo
- SetAutoDisplayScale
- SetComposition
- SetForegroundWindow
- SetKeyFocus
- SetManualDisplayScaleFactor
- SetMinSize
- SetResizeGrip
- SetWindowIcon
- ShowWindow
- StopFlashWindow
- ToggleMaximize

#### Properties

##### BringToFront

```ts
BringToFront: any
```

Defined in:  [src/deck-components/SteamClient.ts:131](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L131)

##### FlashWindow

```ts
FlashWindow: any
```

Defined in:  [src/deck-components/SteamClient.ts:134](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L134)

##### GamescopeBlur

```ts
GamescopeBlur: any
```

Defined in:  [src/deck-components/SteamClient.ts:130](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L130)

##### GetBrowserID

```ts
GetBrowserID: any
```

Defined in:  [src/deck-components/SteamClient.ts:144](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L144)

##### GetMousePositionDetails

```ts
GetMousePositionDetails: any
```

Defined in:  [src/deck-components/SteamClient.ts:142](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L142)

##### GetWindowDimensions

```ts
GetWindowDimensions: any
```

Defined in:  [src/deck-components/SteamClient.ts:139](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L139)

##### GetWindowRestoreDetails

```ts
GetWindowRestoreDetails: any
```

Defined in:  [src/deck-components/SteamClient.ts:140](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L140)

##### HideWindow

```ts
HideWindow: any
```

Defined in:  [src/deck-components/SteamClient.ts:137](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L137)

##### IsWindowMinimized

```ts
IsWindowMinimized: any
```

Defined in:  [src/deck-components/SteamClient.ts:143](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L143)

##### Minimize

```ts
Minimize: any
```

Defined in:  [src/deck-components/SteamClient.ts:122](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L122)

##### MoveTo

```ts
MoveTo: any
```

Defined in:  [src/deck-components/SteamClient.ts:125](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L125)

##### PositionWindowRelative

```ts
PositionWindowRelative: any
```

Defined in:  [src/deck-components/SteamClient.ts:141](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L141)

##### ProcessShuttingDown

```ts
ProcessShuttingDown: any
```

Defined in:  [src/deck-components/SteamClient.ts:123](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L123)

##### RegisterForExternalDisplayChanged

```ts
RegisterForExternalDisplayChanged: any
```

Defined in:  [src/deck-components/SteamClient.ts:119](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L119)

##### ResizeTo

```ts
ResizeTo: any
```

Defined in:  [src/deck-components/SteamClient.ts:126](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L126)

##### SetAutoDisplayScale

```ts
SetAutoDisplayScale: any
```

Defined in:  [src/deck-components/SteamClient.ts:121](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L121)

##### SetComposition

```ts
SetComposition: any
```

Defined in:  [src/deck-components/SteamClient.ts:129](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L129)

##### SetForegroundWindow

```ts
SetForegroundWindow: any
```

Defined in:  [src/deck-components/SteamClient.ts:132](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L132)

##### SetKeyFocus

```ts
SetKeyFocus: any
```

Defined in:  [src/deck-components/SteamClient.ts:133](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L133)

##### SetManualDisplayScaleFactor

```ts
SetManualDisplayScaleFactor: any
```

Defined in:  [src/deck-components/SteamClient.ts:120](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L120)

##### SetMinSize

```ts
SetMinSize: any
```

Defined in:  [src/deck-components/SteamClient.ts:127](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L127)

##### SetResizeGrip

```ts
SetResizeGrip: any
```

Defined in:  [src/deck-components/SteamClient.ts:128](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L128)

##### SetWindowIcon

```ts
SetWindowIcon: any
```

Defined in:  [src/deck-components/SteamClient.ts:138](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L138)

##### ShowWindow

```ts
ShowWindow: any
```

Defined in:  [src/deck-components/SteamClient.ts:136](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L136)

##### StopFlashWindow

```ts
StopFlashWindow: any
```

Defined in:  [src/deck-components/SteamClient.ts:135](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L135)

##### ToggleMaximize

```ts
ToggleMaximize: any
```

Defined in:  [src/deck-components/SteamClient.ts:124](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L124)

## Type Aliases

### AppAchievements

```ts
AppAchievements: Object
```

#### Type declaration

- `nAchieved`: `number`

- `nTotal`: `number`

- `vecAchievedHidden`: `any`[]

- `vecHighlight`: `any`[]

- `vecUnachieved`: `any`[]

Defined in:  [src/deck-components/SteamClient.ts:207](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L207)

---

### AppLanguages

```ts
AppLanguages: Object
```

#### Type declaration

- `strDisplayName`: `string`

- `strShortName`: `string`

Defined in:  [src/deck-components/SteamClient.ts:215](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L215)
