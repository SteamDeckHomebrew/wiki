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

> [`AppAchievements`](SteamClient#appachievements)

Defined in:  [src/deck-components/SteamClient.ts:221](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L221)

##### bCanMoveInstallFolder

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:222](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L222)

##### bCloudAvailable

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:223](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L223)

##### bCloudEnabledForAccount

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:224](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L224)

##### bCloudEnabledForApp

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:225](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L225)

##### bCloudSyncOnSuspendAvailable

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:226](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L226)

##### bCloudSyncOnSuspendEnabled

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:227](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L227)

##### bCommunityMarketPresence

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:228](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L228)

##### bEnableAllowDesktopConfiguration

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:229](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L229)

##### bFreeRemovableLicense

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:230](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L230)

##### bHasAllLegacyCDKeys

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:231](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L231)

##### bHasAnyLocalContent

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:232](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L232)

##### bHasLockedPrivateBetas

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:233](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L233)

##### bIsExcludedFromSharing

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:234](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L234)

##### bIsSubscribedTo

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:235](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L235)

##### bOverlayEnabled

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:236](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L236)

##### bOverrideInternalResolution

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:237](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L237)

##### bRequiresLegacyCDKey

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:238](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L238)

##### bShortcutIsVR

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:239](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L239)

##### bShowCDKeyInMenus

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:240](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L240)

##### bShowControllerConfig

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:241](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L241)

##### bSupportsCDKeyCopyToClipboard

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:242](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L242)

##### bVRGameTheatreEnabled

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:243](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L243)

##### bWorkshopVisible

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:244](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L244)

##### eAppOwnershipFlags

> `number`

Defined in:  [src/deck-components/SteamClient.ts:245](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L245)

##### eAutoUpdateValue

> `number`

Defined in:  [src/deck-components/SteamClient.ts:246](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L246)

##### eBackgroundDownloads

> `number`

Defined in:  [src/deck-components/SteamClient.ts:247](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L247)

##### eCloudSync

> `number`

Defined in:  [src/deck-components/SteamClient.ts:248](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L248)

##### eControllerRumblePreference

> `number`

Defined in:  [src/deck-components/SteamClient.ts:249](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L249)

##### eDisplayStatus

> `number`

Defined in:  [src/deck-components/SteamClient.ts:250](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L250)

##### eEnableThirdPartyControllerConfiguration

> `number`

Defined in:  [src/deck-components/SteamClient.ts:251](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L251)

##### eSteamInputControllerMask

> `number`

Defined in:  [src/deck-components/SteamClient.ts:252](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L252)

##### iInstallFolder

> `number`

Defined in:  [src/deck-components/SteamClient.ts:253](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L253)

##### lDiskUsageBytes

> `number`

Defined in:  [src/deck-components/SteamClient.ts:254](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L254)

##### lDlcUsageBytes

> `number`

Defined in:  [src/deck-components/SteamClient.ts:255](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L255)

##### nBuildID

> `number`

Defined in:  [src/deck-components/SteamClient.ts:256](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L256)

##### nCompatToolPriority

> `number`

Defined in:  [src/deck-components/SteamClient.ts:257](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L257)

##### nPlaytimeForever

> `number`

Defined in:  [src/deck-components/SteamClient.ts:258](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L258)

##### nScreenshots

> `number`

Defined in:  [src/deck-components/SteamClient.ts:259](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L259)

##### rtLastTimePlayed

> `number`

Defined in:  [src/deck-components/SteamClient.ts:260](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L260)

##### rtLastUpdated

> `number`

Defined in:  [src/deck-components/SteamClient.ts:261](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L261)

##### rtPurchased

> `number`

Defined in:  [src/deck-components/SteamClient.ts:262](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L262)

##### selectedLanguage

> `object`

```ts
{
    strDisplayName: string;
    strShortName: string;
}
```

###### Type declaration

| Member | Type |
| :------ | :------ |
| `strDisplayName` | `string` |
| `strShortName` | `string` |

Defined in:  [src/deck-components/SteamClient.ts:263](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L263)

##### strCloudBytesAvailable

> `string`

Defined in:  [src/deck-components/SteamClient.ts:267](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L267)

##### strCloudBytesUsed

> `string`

Defined in:  [src/deck-components/SteamClient.ts:268](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L268)

##### strCompatToolDisplayName

> `string`

Defined in:  [src/deck-components/SteamClient.ts:269](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L269)

##### strCompatToolName

> `string`

Defined in:  [src/deck-components/SteamClient.ts:270](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L270)

##### strDeveloperName

> `string`

Defined in:  [src/deck-components/SteamClient.ts:271](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L271)

##### strDeveloperURL

> `string`

Defined in:  [src/deck-components/SteamClient.ts:272](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L272)

##### strDisplayName

> `string`

Defined in:  [src/deck-components/SteamClient.ts:273](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L273)

##### strExternalSubscriptionURL

> `string`

Defined in:  [src/deck-components/SteamClient.ts:274](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L274)

##### strFlatpakAppID

> `string`

Defined in:  [src/deck-components/SteamClient.ts:275](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L275)

##### strHomepageURL

> `string`

Defined in:  [src/deck-components/SteamClient.ts:276](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L276)

##### strLaunchOptions

> `string`

Defined in:  [src/deck-components/SteamClient.ts:277](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L277)

##### strManualURL

> `string`

Defined in:  [src/deck-components/SteamClient.ts:278](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L278)

##### strOwnerSteamID

> `string`

Defined in:  [src/deck-components/SteamClient.ts:279](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L279)

##### strResolutionOverride

> `string`

Defined in:  [src/deck-components/SteamClient.ts:280](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L280)

##### strSelectedBeta

> `string`

Defined in:  [src/deck-components/SteamClient.ts:281](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L281)

##### strShortcutExe

> `string`

Defined in:  [src/deck-components/SteamClient.ts:282](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L282)

##### strShortcutLaunchOptions

> `string`

Defined in:  [src/deck-components/SteamClient.ts:283](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L283)

##### strShortcutStartDir

> `string`

Defined in:  [src/deck-components/SteamClient.ts:284](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L284)

##### strSteamDeckBlogURL

> `string`

Defined in:  [src/deck-components/SteamClient.ts:285](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L285)

##### unAppID

> `number`

Defined in:  [src/deck-components/SteamClient.ts:286](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L286)

##### vecBetas

> `any`[]

Defined in:  [src/deck-components/SteamClient.ts:287](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L287)

##### vecDLC

> `any`[]

Defined in:  [src/deck-components/SteamClient.ts:288](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L288)

##### vecDeckCompatTestResults

> `any`[]

Defined in:  [src/deck-components/SteamClient.ts:289](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L289)

##### vecLanguages

> [`AppLanguages`](SteamClient#applanguages)[]

Defined in:  [src/deck-components/SteamClient.ts:290](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L290)

##### vecLegacyCDKeys

> `any`[]

Defined in:  [src/deck-components/SteamClient.ts:291](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L291)

##### vecMusicAlbums

> `any`[]

Defined in:  [src/deck-components/SteamClient.ts:292](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L292)

##### vecPlatforms

> `string`[]

Defined in:  [src/deck-components/SteamClient.ts:293](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L293)

##### vecScreenShots

> `any`[]

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

> `any`

Defined in:  [src/deck-components/SteamClient.ts:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L56)

##### AddUserTagToApps

> `any`

Defined in:  [src/deck-components/SteamClient.ts:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L11)

##### BackupFilesForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:31](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L31)

##### BrowseLocalFilesForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:28](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L28)

##### BrowseScreenshotForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:30](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L30)

##### BrowseScreenshotsForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L29)

##### CancelGameAction

> `any`

Defined in:  [src/deck-components/SteamClient.ts:94](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L94)

##### CancelLaunch

> `any`

Defined in:  [src/deck-components/SteamClient.ts:88](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L88)

##### ClearAndSetUserTagsOnApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L14)

##### ClearCustomArtworkForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:71](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L71)

##### ClearCustomLogoPositionForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:73](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L73)

##### ClearProton

> `any`

Defined in:  [src/deck-components/SteamClient.ts:104](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L104)

##### ClearUserTagsOnApps

> `any`

Defined in:  [src/deck-components/SteamClient.ts:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L13)

##### ContinueGameAction

> `any`

Defined in:  [src/deck-components/SteamClient.ts:93](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L93)

##### CreateDesktopShortcutForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:33](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L33)

##### DeleteLocalScreenshot

> `any`

Defined in:  [src/deck-components/SteamClient.ts:45](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L45)

##### DownloadWorkshopItem

> `any`

Defined in:  [src/deck-components/SteamClient.ts:40](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L40)

##### FetchMarketingMessages

> `any`

Defined in:  [src/deck-components/SteamClient.ts:106](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L106)

##### GetAchievementsInTimeRange

> `any`

Defined in:  [src/deck-components/SteamClient.ts:36](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L36)

##### GetActiveGameActions

> `any`

Defined in:  [src/deck-components/SteamClient.ts:95](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L95)

##### GetAllShortcuts

> `any`

Defined in:  [src/deck-components/SteamClient.ts:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L54)

##### GetAvailableCompatTools

> `any`

Defined in:  [src/deck-components/SteamClient.ts:76](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L76)

##### GetCachedAppDetails

> `any`

Defined in:  [src/deck-components/SteamClient.ts:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L65)

##### GetCloudPendingRemoteOperations

> `any`

Defined in:  [src/deck-components/SteamClient.ts:103](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L103)

##### GetConflictingFileTimestamps

> `any`

Defined in:  [src/deck-components/SteamClient.ts:102](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L102)

##### GetDetailsForScreenshotUpload

> `any`

Defined in:  [src/deck-components/SteamClient.ts:43](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L43)

##### GetDownloadedWorkshopItems

> `any`

Defined in:  [src/deck-components/SteamClient.ts:39](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L39)

##### GetFriendAchievementsForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L9)

##### GetFriendsWhoPlay

> `any`

Defined in:  [src/deck-components/SteamClient.ts:47](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L47)

##### GetGameActionDetails

> `any`

Defined in:  [src/deck-components/SteamClient.ts:96](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L96)

##### GetGameActionForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:97](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L97)

##### GetLaunchOptionsForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L51)

##### GetLibraryBootstrapData

> `any`

Defined in:  [src/deck-components/SteamClient.ts:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L7)

##### GetMyAchievementsForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L10)

##### GetResolutionOverrideForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L52)

##### GetScreenshotsInTimeRange

> `any`

Defined in:  [src/deck-components/SteamClient.ts:46](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L46)

##### GetShortcutData

> `any`

Defined in:  [src/deck-components/SteamClient.ts:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L55)

##### GetSoundtrackDetails

> `any`

Defined in:  [src/deck-components/SteamClient.ts:49](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L49)

##### GetStoreTagLocalization

> `any`

Defined in:  [src/deck-components/SteamClient.ts:50](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L50)

##### GetSubscribedWorkshopItems

> `any`

Defined in:  [src/deck-components/SteamClient.ts:37](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L37)

##### InstallApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:84](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L84)

##### InstallFlatpakAppAndCreateShortcut

> `any`

Defined in:  [src/deck-components/SteamClient.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L58)

##### JoinAppContentBeta

> `any`

Defined in:  [src/deck-components/SteamClient.ts:34](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L34)

##### JoinAppContentBetaByPassword

> `any`

Defined in:  [src/deck-components/SteamClient.ts:35](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L35)

##### ListFlatpakApps

> `any`

Defined in:  [src/deck-components/SteamClient.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L59)

##### LoadEula

> `any`

Defined in:  [src/deck-components/SteamClient.ts:101](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L101)

##### MarkEulaAccepted

> `any`

Defined in:  [src/deck-components/SteamClient.ts:99](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L99)

##### MarkEulaRejected

> `any`

Defined in:  [src/deck-components/SteamClient.ts:100](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L100)

##### MarkMarketingMessageSeen

> `any`

Defined in:  [src/deck-components/SteamClient.ts:107](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L107)

##### OpenAppSettingsDialog

> `any`

Defined in:  [src/deck-components/SteamClient.ts:115](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L115)

##### PromptToChangeShortcut

> `any`

Defined in:  [src/deck-components/SteamClient.ts:82](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L82)

##### PromptToSelectShortcutIcon

> `any`

Defined in:  [src/deck-components/SteamClient.ts:83](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L83)

##### RegisterForAchievementChanges

> `any`

Defined in:  [src/deck-components/SteamClient.ts:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L8)

##### RegisterForAppDetails

> `any`

Defined in:  [src/deck-components/SteamClient.ts:3](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L3)

##### RegisterForAppOverviewChanges

> `any`

Defined in:  [src/deck-components/SteamClient.ts:2](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L2)

##### RegisterForGameActionEnd

> `any`

Defined in:  [src/deck-components/SteamClient.ts:110](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L110)

##### RegisterForGameActionShowError

> `any`

Defined in:  [src/deck-components/SteamClient.ts:113](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L113)

##### RegisterForGameActionShowUI

> `any`

Defined in:  [src/deck-components/SteamClient.ts:114](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L114)

##### RegisterForGameActionStart

> `any`

Defined in:  [src/deck-components/SteamClient.ts:109](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L109)

##### RegisterForGameActionTaskChange

> `any`

Defined in:  [src/deck-components/SteamClient.ts:111](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L111)

##### RegisterForGameActionUserRequest

> `any`

Defined in:  [src/deck-components/SteamClient.ts:112](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L112)

##### RegisterForLocalizationChanges

> `any`

Defined in:  [src/deck-components/SteamClient.ts:4](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L4)

##### RegisterForMarketingMessages

> `any`

Defined in:  [src/deck-components/SteamClient.ts:105](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L105)

##### RegisterForWorkshopChanges

> `any`

Defined in:  [src/deck-components/SteamClient.ts:5](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L5)

##### RegisterForWorkshopItemDownloads

> `any`

Defined in:  [src/deck-components/SteamClient.ts:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L6)

##### RemoveShortcut

> `any`

Defined in:  [src/deck-components/SteamClient.ts:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L57)

##### RemoveUserTagFromApps

> `any`

Defined in:  [src/deck-components/SteamClient.ts:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L12)

##### ReportLibraryAssetCacheMiss

> `any`

Defined in:  [src/deck-components/SteamClient.ts:67](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L67)

##### ReportMarketingMessageSeen

> `any`

Defined in:  [src/deck-components/SteamClient.ts:108](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L108)

##### RequestIconDataForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:74](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L74)

##### RequestLegacyCDKeysForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:48](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L48)

##### ResetHiddenState

> `any`

Defined in:  [src/deck-components/SteamClient.ts:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L16)

##### RunGame

> `any`

Defined in:  [src/deck-components/SteamClient.ts:85](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L85)

##### SaveAchievementProgressCache

> `any`

Defined in:  [src/deck-components/SteamClient.ts:68](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L68)

##### ScanForShortcuts

> `any`

Defined in:  [src/deck-components/SteamClient.ts:53](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L53)

##### SetAppAutoUpdateBehavior

> `any`

Defined in:  [src/deck-components/SteamClient.ts:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L20)

##### SetAppBackgroundDownloadsBehavior

> `any`

Defined in:  [src/deck-components/SteamClient.ts:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L21)

##### SetAppCurrentLanguage

> `any`

Defined in:  [src/deck-components/SteamClient.ts:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L19)

##### SetAppHidden

> `any`

Defined in:  [src/deck-components/SteamClient.ts:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L15)

##### SetAppLaunchOptions

> `any`

Defined in:  [src/deck-components/SteamClient.ts:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L17)

##### SetAppResolutionOverride

> `any`

Defined in:  [src/deck-components/SteamClient.ts:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L18)

##### SetCachedAppDetails

> `any`

Defined in:  [src/deck-components/SteamClient.ts:66](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L66)

##### SetControllerRumblePreference

> `any`

Defined in:  [src/deck-components/SteamClient.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L64)

##### SetCustomArtworkForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:70](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L70)

##### SetCustomLogoPositionForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:72](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L72)

##### SetDLCEnabled

> `any`

Defined in:  [src/deck-components/SteamClient.ts:92](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L92)

##### SetLocalScreenshotCaption

> `any`

Defined in:  [src/deck-components/SteamClient.ts:41](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L41)

##### SetLocalScreenshotSpoiler

> `any`

Defined in:  [src/deck-components/SteamClient.ts:42](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L42)

##### SetShortcutExe

> `any`

Defined in:  [src/deck-components/SteamClient.ts:78](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L78)

##### SetShortcutIsVR

> `any`

Defined in:  [src/deck-components/SteamClient.ts:81](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L81)

##### SetShortcutLaunchOptions

> `any`

Defined in:  [src/deck-components/SteamClient.ts:80](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L80)

##### SetShortcutName

> `any`

Defined in:  [src/deck-components/SteamClient.ts:77](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L77)

##### SetShortcutStartDir

> `any`

Defined in:  [src/deck-components/SteamClient.ts:79](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L79)

##### SetStreamingClientForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:69](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L69)

##### SetThirdPartyControllerConfiguration

> `any`

Defined in:  [src/deck-components/SteamClient.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L62)

##### ShowControllerConfigurator

> `any`

Defined in:  [src/deck-components/SteamClient.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L61)

##### ShowStore

> `any`

Defined in:  [src/deck-components/SteamClient.ts:91](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L91)

##### SkipShaderProcessing

> `any`

Defined in:  [src/deck-components/SteamClient.ts:98](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L98)

##### SpecifyCompatTool

> `any`

Defined in:  [src/deck-components/SteamClient.ts:75](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L75)

##### StreamGame

> `any`

Defined in:  [src/deck-components/SteamClient.ts:87](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L87)

##### SubscribeWorkshopItem

> `any`

Defined in:  [src/deck-components/SteamClient.ts:38](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L38)

##### TerminateApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:89](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L89)

##### ToggleAllowDesktopConfiguration

> `any`

Defined in:  [src/deck-components/SteamClient.ts:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L63)

##### ToggleAppFamilyBlockedState

> `any`

Defined in:  [src/deck-components/SteamClient.ts:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L22)

##### ToggleAppSteamCloudEnabled

> `any`

Defined in:  [src/deck-components/SteamClient.ts:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L23)

##### ToggleAppSteamCloudSyncOnSuspendEnabled

> `any`

Defined in:  [src/deck-components/SteamClient.ts:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L24)

##### ToggleEnableDesktopTheatreForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:27](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L27)

##### ToggleEnableSteamOverlayForApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:26](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L26)

##### ToggleOverrideResolutionForInternalDisplay

> `any`

Defined in:  [src/deck-components/SteamClient.ts:25](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L25)

##### UninstallApps

> `any`

Defined in:  [src/deck-components/SteamClient.ts:90](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L90)

##### UninstallFlatpakApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L60)

##### UploadLocalScreenshot

> `any`

Defined in:  [src/deck-components/SteamClient.ts:44](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L44)

##### VerifyApp

> `any`

Defined in:  [src/deck-components/SteamClient.ts:86](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L86)

##### VerifyFilesForApp

> `any`

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

> `boolean`

Defined in:  [src/deck-components/SteamClient.ts:204](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L204)

##### nInstanceID

> `number`

Defined in:  [src/deck-components/SteamClient.ts:203](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L203)

##### unAppID

> `number`

Defined in:  [src/deck-components/SteamClient.ts:202](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L202)

---

### SteamAppOverview

#### Index

##### Properties

- display_name
- gameid

#### Properties

##### display\_name

> `string`

Defined in:  [src/deck-components/SteamClient.ts:298](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L298)

##### gameid

> `string`

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

> [`Apps`](SteamClient#apps)

Defined in:  [src/deck-components/SteamClient.ts:148](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L148)

##### Browser

> `any`

Defined in:  [src/deck-components/SteamClient.ts:149](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L149)

##### BrowserView

> `any`

Defined in:  [src/deck-components/SteamClient.ts:150](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L150)

##### ClientNotifications

> `any`

Defined in:  [src/deck-components/SteamClient.ts:151](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L151)

##### Cloud

> `any`

Defined in:  [src/deck-components/SteamClient.ts:152](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L152)

##### Console

> `any`

Defined in:  [src/deck-components/SteamClient.ts:153](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L153)

##### Downloads

> `any`

Defined in:  [src/deck-components/SteamClient.ts:154](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L154)

##### FamilySharing

> `any`

Defined in:  [src/deck-components/SteamClient.ts:155](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L155)

##### FriendSettings

> `any`

Defined in:  [src/deck-components/SteamClient.ts:156](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L156)

##### Friends

> `any`

Defined in:  [src/deck-components/SteamClient.ts:157](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L157)

##### GameSessions

> `any`

Defined in:  [src/deck-components/SteamClient.ts:158](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L158)

##### Input

> `any`

Defined in:  [src/deck-components/SteamClient.ts:159](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L159)

##### InstallFolder

> `any`

Defined in:  [src/deck-components/SteamClient.ts:160](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L160)

##### Installs

> `any`

Defined in:  [src/deck-components/SteamClient.ts:161](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L161)

##### MachineStorage

> `any`

Defined in:  [src/deck-components/SteamClient.ts:162](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L162)

##### Messaging

> `any`

Defined in:  [src/deck-components/SteamClient.ts:163](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L163)

##### Notifications

> `any`

Defined in:  [src/deck-components/SteamClient.ts:164](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L164)

##### OpenVR

> `any`

Defined in:  [src/deck-components/SteamClient.ts:165](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L165)

##### Overlay

> `any`

Defined in:  [src/deck-components/SteamClient.ts:166](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L166)

##### Parental

> `any`

Defined in:  [src/deck-components/SteamClient.ts:167](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L167)

##### RegisterIFrameNavigatedCallback

> `any`

Defined in:  [src/deck-components/SteamClient.ts:168](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L168)

##### RemotePlay

> `any`

Defined in:  [src/deck-components/SteamClient.ts:169](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L169)

##### RoamingStorage

> `any`

Defined in:  [src/deck-components/SteamClient.ts:170](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L170)

##### Screenshots

> `any`

Defined in:  [src/deck-components/SteamClient.ts:171](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L171)

##### Settings

> `any`

Defined in:  [src/deck-components/SteamClient.ts:172](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L172)

##### SharedConnection

> `any`

Defined in:  [src/deck-components/SteamClient.ts:173](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L173)

##### Stats

> `any`

Defined in:  [src/deck-components/SteamClient.ts:174](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L174)

##### Storage

> `any`

Defined in:  [src/deck-components/SteamClient.ts:175](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L175)

##### Streaming

> `any`

Defined in:  [src/deck-components/SteamClient.ts:176](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L176)

##### System

> `any`

Defined in:  [src/deck-components/SteamClient.ts:177](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L177)

##### UI

> `any`

Defined in:  [src/deck-components/SteamClient.ts:178](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L178)

##### URL

> `any`

Defined in:  [src/deck-components/SteamClient.ts:179](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L179)

##### Updates

> `any`

Defined in:  [src/deck-components/SteamClient.ts:180](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L180)

##### User

> `any`

Defined in:  [src/deck-components/SteamClient.ts:181](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L181)

##### WebChat

> `any`

Defined in:  [src/deck-components/SteamClient.ts:182](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L182)

##### Window

> [`Window`](SteamClient#window)

Defined in:  [src/deck-components/SteamClient.ts:183](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L183)

---

### SteamShortcut

#### Index

##### Properties

- appid
- data

#### Properties

##### appid

> `number`

Defined in:  [src/deck-components/SteamClient.ts:187](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L187)

##### data

> `object`

```ts
{
    bIsApplication: boolean;
    strAppName: string;
    strArguments: string;
    strExePath: string;
    strShortcutPath: string;
    strSortAs: string;
}
```

###### Type declaration

| Member | Type |
| :------ | :------ |
| `bIsApplication` | `boolean` |
| `strAppName` | `string` |
| `strArguments` | `string` |
| `strExePath` | `string` |
| `strShortcutPath` | `string` |
| `strSortAs` | `string` |

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

> `any`

Defined in:  [src/deck-components/SteamClient.ts:131](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L131)

##### FlashWindow

> `any`

Defined in:  [src/deck-components/SteamClient.ts:134](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L134)

##### GamescopeBlur

> `any`

Defined in:  [src/deck-components/SteamClient.ts:130](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L130)

##### GetBrowserID

> `any`

Defined in:  [src/deck-components/SteamClient.ts:144](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L144)

##### GetMousePositionDetails

> `any`

Defined in:  [src/deck-components/SteamClient.ts:142](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L142)

##### GetWindowDimensions

> `any`

Defined in:  [src/deck-components/SteamClient.ts:139](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L139)

##### GetWindowRestoreDetails

> `any`

Defined in:  [src/deck-components/SteamClient.ts:140](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L140)

##### HideWindow

> `any`

Defined in:  [src/deck-components/SteamClient.ts:137](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L137)

##### IsWindowMinimized

> `any`

Defined in:  [src/deck-components/SteamClient.ts:143](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L143)

##### Minimize

> `any`

Defined in:  [src/deck-components/SteamClient.ts:122](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L122)

##### MoveTo

> `any`

Defined in:  [src/deck-components/SteamClient.ts:125](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L125)

##### PositionWindowRelative

> `any`

Defined in:  [src/deck-components/SteamClient.ts:141](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L141)

##### ProcessShuttingDown

> `any`

Defined in:  [src/deck-components/SteamClient.ts:123](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L123)

##### RegisterForExternalDisplayChanged

> `any`

Defined in:  [src/deck-components/SteamClient.ts:119](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L119)

##### ResizeTo

> `any`

Defined in:  [src/deck-components/SteamClient.ts:126](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L126)

##### SetAutoDisplayScale

> `any`

Defined in:  [src/deck-components/SteamClient.ts:121](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L121)

##### SetComposition

> `any`

Defined in:  [src/deck-components/SteamClient.ts:129](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L129)

##### SetForegroundWindow

> `any`

Defined in:  [src/deck-components/SteamClient.ts:132](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L132)

##### SetKeyFocus

> `any`

Defined in:  [src/deck-components/SteamClient.ts:133](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L133)

##### SetManualDisplayScaleFactor

> `any`

Defined in:  [src/deck-components/SteamClient.ts:120](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L120)

##### SetMinSize

> `any`

Defined in:  [src/deck-components/SteamClient.ts:127](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L127)

##### SetResizeGrip

> `any`

Defined in:  [src/deck-components/SteamClient.ts:128](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L128)

##### SetWindowIcon

> `any`

Defined in:  [src/deck-components/SteamClient.ts:138](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L138)

##### ShowWindow

> `any`

Defined in:  [src/deck-components/SteamClient.ts:136](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L136)

##### StopFlashWindow

> `any`

Defined in:  [src/deck-components/SteamClient.ts:135](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L135)

##### ToggleMaximize

> `any`

Defined in:  [src/deck-components/SteamClient.ts:124](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L124)

## Type Aliases

### AppAchievements

> `object`

```ts
{
    nAchieved: number;
    nTotal: number;
    vecAchievedHidden: any[];
    vecHighlight: any[];
    vecUnachieved: any[];
}
```

#### Type declaration

| Member | Type |
| :------ | :------ |
| `nAchieved` | `number` |
| `nTotal` | `number` |
| `vecAchievedHidden` | `any`[] |
| `vecHighlight` | `any`[] |
| `vecUnachieved` | `any`[] |

Defined in:  [src/deck-components/SteamClient.ts:207](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L207)

---

### AppLanguages

> `object`

```ts
{
    strDisplayName: string;
    strShortName: string;
}
```

#### Type declaration

| Member | Type |
| :------ | :------ |
| `strDisplayName` | `string` |
| `strShortName` | `string` |

Defined in:  [src/deck-components/SteamClient.ts:215](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/-/src/deck-components/SteamClient.ts#L215)
