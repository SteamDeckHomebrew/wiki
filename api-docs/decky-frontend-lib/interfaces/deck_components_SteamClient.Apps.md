[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [deck-components/SteamClient](../modules/deck_components_SteamClient.md) / Apps

# Interface: Apps

[deck-components/SteamClient](../modules/deck_components_SteamClient.md).Apps

## Table of contents

### Properties

- [AddShortcut](deck_components_SteamClient.Apps.md#addshortcut)
- [AddUserTagToApps](deck_components_SteamClient.Apps.md#addusertagtoapps)
- [BackupFilesForApp](deck_components_SteamClient.Apps.md#backupfilesforapp)
- [BrowseLocalFilesForApp](deck_components_SteamClient.Apps.md#browselocalfilesforapp)
- [BrowseScreenshotForApp](deck_components_SteamClient.Apps.md#browsescreenshotforapp)
- [BrowseScreenshotsForApp](deck_components_SteamClient.Apps.md#browsescreenshotsforapp)
- [CancelGameAction](deck_components_SteamClient.Apps.md#cancelgameaction)
- [CancelLaunch](deck_components_SteamClient.Apps.md#cancellaunch)
- [ClearAndSetUserTagsOnApp](deck_components_SteamClient.Apps.md#clearandsetusertagsonapp)
- [ClearCustomArtworkForApp](deck_components_SteamClient.Apps.md#clearcustomartworkforapp)
- [ClearCustomLogoPositionForApp](deck_components_SteamClient.Apps.md#clearcustomlogopositionforapp)
- [ClearProton](deck_components_SteamClient.Apps.md#clearproton)
- [ClearUserTagsOnApps](deck_components_SteamClient.Apps.md#clearusertagsonapps)
- [ContinueGameAction](deck_components_SteamClient.Apps.md#continuegameaction)
- [CreateDesktopShortcutForApp](deck_components_SteamClient.Apps.md#createdesktopshortcutforapp)
- [DeleteLocalScreenshot](deck_components_SteamClient.Apps.md#deletelocalscreenshot)
- [DownloadWorkshopItem](deck_components_SteamClient.Apps.md#downloadworkshopitem)
- [FetchMarketingMessages](deck_components_SteamClient.Apps.md#fetchmarketingmessages)
- [GetAchievementsInTimeRange](deck_components_SteamClient.Apps.md#getachievementsintimerange)
- [GetActiveGameActions](deck_components_SteamClient.Apps.md#getactivegameactions)
- [GetAllShortcuts](deck_components_SteamClient.Apps.md#getallshortcuts)
- [GetAvailableCompatTools](deck_components_SteamClient.Apps.md#getavailablecompattools)
- [GetCachedAppDetails](deck_components_SteamClient.Apps.md#getcachedappdetails)
- [GetCloudPendingRemoteOperations](deck_components_SteamClient.Apps.md#getcloudpendingremoteoperations)
- [GetConflictingFileTimestamps](deck_components_SteamClient.Apps.md#getconflictingfiletimestamps)
- [GetDetailsForScreenshotUpload](deck_components_SteamClient.Apps.md#getdetailsforscreenshotupload)
- [GetDownloadedWorkshopItems](deck_components_SteamClient.Apps.md#getdownloadedworkshopitems)
- [GetFriendAchievementsForApp](deck_components_SteamClient.Apps.md#getfriendachievementsforapp)
- [GetFriendsWhoPlay](deck_components_SteamClient.Apps.md#getfriendswhoplay)
- [GetGameActionDetails](deck_components_SteamClient.Apps.md#getgameactiondetails)
- [GetGameActionForApp](deck_components_SteamClient.Apps.md#getgameactionforapp)
- [GetLaunchOptionsForApp](deck_components_SteamClient.Apps.md#getlaunchoptionsforapp)
- [GetLibraryBootstrapData](deck_components_SteamClient.Apps.md#getlibrarybootstrapdata)
- [GetMyAchievementsForApp](deck_components_SteamClient.Apps.md#getmyachievementsforapp)
- [GetResolutionOverrideForApp](deck_components_SteamClient.Apps.md#getresolutionoverrideforapp)
- [GetScreenshotsInTimeRange](deck_components_SteamClient.Apps.md#getscreenshotsintimerange)
- [GetShortcutData](deck_components_SteamClient.Apps.md#getshortcutdata)
- [GetSoundtrackDetails](deck_components_SteamClient.Apps.md#getsoundtrackdetails)
- [GetStoreTagLocalization](deck_components_SteamClient.Apps.md#getstoretaglocalization)
- [GetSubscribedWorkshopItems](deck_components_SteamClient.Apps.md#getsubscribedworkshopitems)
- [InstallApp](deck_components_SteamClient.Apps.md#installapp)
- [InstallFlatpakAppAndCreateShortcut](deck_components_SteamClient.Apps.md#installflatpakappandcreateshortcut)
- [JoinAppContentBeta](deck_components_SteamClient.Apps.md#joinappcontentbeta)
- [JoinAppContentBetaByPassword](deck_components_SteamClient.Apps.md#joinappcontentbetabypassword)
- [ListFlatpakApps](deck_components_SteamClient.Apps.md#listflatpakapps)
- [LoadEula](deck_components_SteamClient.Apps.md#loadeula)
- [MarkEulaAccepted](deck_components_SteamClient.Apps.md#markeulaaccepted)
- [MarkEulaRejected](deck_components_SteamClient.Apps.md#markeularejected)
- [MarkMarketingMessageSeen](deck_components_SteamClient.Apps.md#markmarketingmessageseen)
- [OpenAppSettingsDialog](deck_components_SteamClient.Apps.md#openappsettingsdialog)
- [PromptToChangeShortcut](deck_components_SteamClient.Apps.md#prompttochangeshortcut)
- [PromptToSelectShortcutIcon](deck_components_SteamClient.Apps.md#prompttoselectshortcuticon)
- [RegisterForAchievementChanges](deck_components_SteamClient.Apps.md#registerforachievementchanges)
- [RegisterForAppDetails](deck_components_SteamClient.Apps.md#registerforappdetails)
- [RegisterForAppOverviewChanges](deck_components_SteamClient.Apps.md#registerforappoverviewchanges)
- [RegisterForGameActionEnd](deck_components_SteamClient.Apps.md#registerforgameactionend)
- [RegisterForGameActionShowError](deck_components_SteamClient.Apps.md#registerforgameactionshowerror)
- [RegisterForGameActionShowUI](deck_components_SteamClient.Apps.md#registerforgameactionshowui)
- [RegisterForGameActionStart](deck_components_SteamClient.Apps.md#registerforgameactionstart)
- [RegisterForGameActionTaskChange](deck_components_SteamClient.Apps.md#registerforgameactiontaskchange)
- [RegisterForGameActionUserRequest](deck_components_SteamClient.Apps.md#registerforgameactionuserrequest)
- [RegisterForLocalizationChanges](deck_components_SteamClient.Apps.md#registerforlocalizationchanges)
- [RegisterForMarketingMessages](deck_components_SteamClient.Apps.md#registerformarketingmessages)
- [RegisterForWorkshopChanges](deck_components_SteamClient.Apps.md#registerforworkshopchanges)
- [RegisterForWorkshopItemDownloads](deck_components_SteamClient.Apps.md#registerforworkshopitemdownloads)
- [RemoveShortcut](deck_components_SteamClient.Apps.md#removeshortcut)
- [RemoveUserTagFromApps](deck_components_SteamClient.Apps.md#removeusertagfromapps)
- [ReportLibraryAssetCacheMiss](deck_components_SteamClient.Apps.md#reportlibraryassetcachemiss)
- [ReportMarketingMessageSeen](deck_components_SteamClient.Apps.md#reportmarketingmessageseen)
- [RequestIconDataForApp](deck_components_SteamClient.Apps.md#requesticondataforapp)
- [RequestLegacyCDKeysForApp](deck_components_SteamClient.Apps.md#requestlegacycdkeysforapp)
- [ResetHiddenState](deck_components_SteamClient.Apps.md#resethiddenstate)
- [RunGame](deck_components_SteamClient.Apps.md#rungame)
- [SaveAchievementProgressCache](deck_components_SteamClient.Apps.md#saveachievementprogresscache)
- [ScanForShortcuts](deck_components_SteamClient.Apps.md#scanforshortcuts)
- [SetAppAutoUpdateBehavior](deck_components_SteamClient.Apps.md#setappautoupdatebehavior)
- [SetAppBackgroundDownloadsBehavior](deck_components_SteamClient.Apps.md#setappbackgrounddownloadsbehavior)
- [SetAppCurrentLanguage](deck_components_SteamClient.Apps.md#setappcurrentlanguage)
- [SetAppHidden](deck_components_SteamClient.Apps.md#setapphidden)
- [SetAppLaunchOptions](deck_components_SteamClient.Apps.md#setapplaunchoptions)
- [SetAppResolutionOverride](deck_components_SteamClient.Apps.md#setappresolutionoverride)
- [SetCachedAppDetails](deck_components_SteamClient.Apps.md#setcachedappdetails)
- [SetControllerRumblePreference](deck_components_SteamClient.Apps.md#setcontrollerrumblepreference)
- [SetCustomArtworkForApp](deck_components_SteamClient.Apps.md#setcustomartworkforapp)
- [SetCustomLogoPositionForApp](deck_components_SteamClient.Apps.md#setcustomlogopositionforapp)
- [SetDLCEnabled](deck_components_SteamClient.Apps.md#setdlcenabled)
- [SetLocalScreenshotCaption](deck_components_SteamClient.Apps.md#setlocalscreenshotcaption)
- [SetLocalScreenshotSpoiler](deck_components_SteamClient.Apps.md#setlocalscreenshotspoiler)
- [SetShortcutExe](deck_components_SteamClient.Apps.md#setshortcutexe)
- [SetShortcutIsVR](deck_components_SteamClient.Apps.md#setshortcutisvr)
- [SetShortcutLaunchOptions](deck_components_SteamClient.Apps.md#setshortcutlaunchoptions)
- [SetShortcutName](deck_components_SteamClient.Apps.md#setshortcutname)
- [SetShortcutStartDir](deck_components_SteamClient.Apps.md#setshortcutstartdir)
- [SetStreamingClientForApp](deck_components_SteamClient.Apps.md#setstreamingclientforapp)
- [SetThirdPartyControllerConfiguration](deck_components_SteamClient.Apps.md#setthirdpartycontrollerconfiguration)
- [ShowControllerConfigurator](deck_components_SteamClient.Apps.md#showcontrollerconfigurator)
- [ShowStore](deck_components_SteamClient.Apps.md#showstore)
- [SkipShaderProcessing](deck_components_SteamClient.Apps.md#skipshaderprocessing)
- [SpecifyCompatTool](deck_components_SteamClient.Apps.md#specifycompattool)
- [StreamGame](deck_components_SteamClient.Apps.md#streamgame)
- [SubscribeWorkshopItem](deck_components_SteamClient.Apps.md#subscribeworkshopitem)
- [TerminateApp](deck_components_SteamClient.Apps.md#terminateapp)
- [ToggleAllowDesktopConfiguration](deck_components_SteamClient.Apps.md#toggleallowdesktopconfiguration)
- [ToggleAppFamilyBlockedState](deck_components_SteamClient.Apps.md#toggleappfamilyblockedstate)
- [ToggleAppSteamCloudEnabled](deck_components_SteamClient.Apps.md#toggleappsteamcloudenabled)
- [ToggleAppSteamCloudSyncOnSuspendEnabled](deck_components_SteamClient.Apps.md#toggleappsteamcloudsynconsuspendenabled)
- [ToggleEnableDesktopTheatreForApp](deck_components_SteamClient.Apps.md#toggleenabledesktoptheatreforapp)
- [ToggleEnableSteamOverlayForApp](deck_components_SteamClient.Apps.md#toggleenablesteamoverlayforapp)
- [ToggleOverrideResolutionForInternalDisplay](deck_components_SteamClient.Apps.md#toggleoverrideresolutionforinternaldisplay)
- [UninstallApps](deck_components_SteamClient.Apps.md#uninstallapps)
- [UninstallFlatpakApp](deck_components_SteamClient.Apps.md#uninstallflatpakapp)
- [UploadLocalScreenshot](deck_components_SteamClient.Apps.md#uploadlocalscreenshot)
- [VerifyApp](deck_components_SteamClient.Apps.md#verifyapp)
- [VerifyFilesForApp](deck_components_SteamClient.Apps.md#verifyfilesforapp)

## Properties

### AddShortcut

• **AddShortcut**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:56](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L56)

___

### AddUserTagToApps

• **AddUserTagToApps**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:11](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L11)

___

### BackupFilesForApp

• **BackupFilesForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:31](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L31)

___

### BrowseLocalFilesForApp

• **BrowseLocalFilesForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:28](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L28)

___

### BrowseScreenshotForApp

• **BrowseScreenshotForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:30](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L30)

___

### BrowseScreenshotsForApp

• **BrowseScreenshotsForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:29](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L29)

___

### CancelGameAction

• **CancelGameAction**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:94](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L94)

___

### CancelLaunch

• **CancelLaunch**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:88](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L88)

___

### ClearAndSetUserTagsOnApp

• **ClearAndSetUserTagsOnApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:14](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L14)

___

### ClearCustomArtworkForApp

• **ClearCustomArtworkForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:71](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L71)

___

### ClearCustomLogoPositionForApp

• **ClearCustomLogoPositionForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:73](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L73)

___

### ClearProton

• **ClearProton**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:104](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L104)

___

### ClearUserTagsOnApps

• **ClearUserTagsOnApps**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:13](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L13)

___

### ContinueGameAction

• **ContinueGameAction**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:93](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L93)

___

### CreateDesktopShortcutForApp

• **CreateDesktopShortcutForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:33](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L33)

___

### DeleteLocalScreenshot

• **DeleteLocalScreenshot**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:45](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L45)

___

### DownloadWorkshopItem

• **DownloadWorkshopItem**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:40](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L40)

___

### FetchMarketingMessages

• **FetchMarketingMessages**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:106](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L106)

___

### GetAchievementsInTimeRange

• **GetAchievementsInTimeRange**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:36](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L36)

___

### GetActiveGameActions

• **GetActiveGameActions**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:95](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L95)

___

### GetAllShortcuts

• **GetAllShortcuts**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:54](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L54)

___

### GetAvailableCompatTools

• **GetAvailableCompatTools**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:76](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L76)

___

### GetCachedAppDetails

• **GetCachedAppDetails**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:65](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L65)

___

### GetCloudPendingRemoteOperations

• **GetCloudPendingRemoteOperations**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:103](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L103)

___

### GetConflictingFileTimestamps

• **GetConflictingFileTimestamps**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:102](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L102)

___

### GetDetailsForScreenshotUpload

• **GetDetailsForScreenshotUpload**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:43](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L43)

___

### GetDownloadedWorkshopItems

• **GetDownloadedWorkshopItems**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:39](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L39)

___

### GetFriendAchievementsForApp

• **GetFriendAchievementsForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:9](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L9)

___

### GetFriendsWhoPlay

• **GetFriendsWhoPlay**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:47](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L47)

___

### GetGameActionDetails

• **GetGameActionDetails**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:96](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L96)

___

### GetGameActionForApp

• **GetGameActionForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:97](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L97)

___

### GetLaunchOptionsForApp

• **GetLaunchOptionsForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:51](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L51)

___

### GetLibraryBootstrapData

• **GetLibraryBootstrapData**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:7](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L7)

___

### GetMyAchievementsForApp

• **GetMyAchievementsForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:10](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L10)

___

### GetResolutionOverrideForApp

• **GetResolutionOverrideForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:52](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L52)

___

### GetScreenshotsInTimeRange

• **GetScreenshotsInTimeRange**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:46](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L46)

___

### GetShortcutData

• **GetShortcutData**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:55](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L55)

___

### GetSoundtrackDetails

• **GetSoundtrackDetails**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:49](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L49)

___

### GetStoreTagLocalization

• **GetStoreTagLocalization**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:50](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L50)

___

### GetSubscribedWorkshopItems

• **GetSubscribedWorkshopItems**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:37](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L37)

___

### InstallApp

• **InstallApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:84](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L84)

___

### InstallFlatpakAppAndCreateShortcut

• **InstallFlatpakAppAndCreateShortcut**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:58](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L58)

___

### JoinAppContentBeta

• **JoinAppContentBeta**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:34](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L34)

___

### JoinAppContentBetaByPassword

• **JoinAppContentBetaByPassword**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:35](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L35)

___

### ListFlatpakApps

• **ListFlatpakApps**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:59](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L59)

___

### LoadEula

• **LoadEula**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:101](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L101)

___

### MarkEulaAccepted

• **MarkEulaAccepted**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:99](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L99)

___

### MarkEulaRejected

• **MarkEulaRejected**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:100](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L100)

___

### MarkMarketingMessageSeen

• **MarkMarketingMessageSeen**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:107](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L107)

___

### OpenAppSettingsDialog

• **OpenAppSettingsDialog**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:115](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L115)

___

### PromptToChangeShortcut

• **PromptToChangeShortcut**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:82](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L82)

___

### PromptToSelectShortcutIcon

• **PromptToSelectShortcutIcon**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:83](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L83)

___

### RegisterForAchievementChanges

• **RegisterForAchievementChanges**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:8](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L8)

___

### RegisterForAppDetails

• **RegisterForAppDetails**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:3](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L3)

___

### RegisterForAppOverviewChanges

• **RegisterForAppOverviewChanges**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:2](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L2)

___

### RegisterForGameActionEnd

• **RegisterForGameActionEnd**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:110](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L110)

___

### RegisterForGameActionShowError

• **RegisterForGameActionShowError**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:113](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L113)

___

### RegisterForGameActionShowUI

• **RegisterForGameActionShowUI**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:114](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L114)

___

### RegisterForGameActionStart

• **RegisterForGameActionStart**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:109](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L109)

___

### RegisterForGameActionTaskChange

• **RegisterForGameActionTaskChange**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:111](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L111)

___

### RegisterForGameActionUserRequest

• **RegisterForGameActionUserRequest**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:112](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L112)

___

### RegisterForLocalizationChanges

• **RegisterForLocalizationChanges**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:4](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L4)

___

### RegisterForMarketingMessages

• **RegisterForMarketingMessages**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:105](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L105)

___

### RegisterForWorkshopChanges

• **RegisterForWorkshopChanges**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:5](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L5)

___

### RegisterForWorkshopItemDownloads

• **RegisterForWorkshopItemDownloads**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:6](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L6)

___

### RemoveShortcut

• **RemoveShortcut**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:57](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L57)

___

### RemoveUserTagFromApps

• **RemoveUserTagFromApps**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:12](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L12)

___

### ReportLibraryAssetCacheMiss

• **ReportLibraryAssetCacheMiss**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:67](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L67)

___

### ReportMarketingMessageSeen

• **ReportMarketingMessageSeen**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:108](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L108)

___

### RequestIconDataForApp

• **RequestIconDataForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:74](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L74)

___

### RequestLegacyCDKeysForApp

• **RequestLegacyCDKeysForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:48](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L48)

___

### ResetHiddenState

• **ResetHiddenState**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:16](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L16)

___

### RunGame

• **RunGame**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:85](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L85)

___

### SaveAchievementProgressCache

• **SaveAchievementProgressCache**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:68](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L68)

___

### ScanForShortcuts

• **ScanForShortcuts**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:53](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L53)

___

### SetAppAutoUpdateBehavior

• **SetAppAutoUpdateBehavior**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:20](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L20)

___

### SetAppBackgroundDownloadsBehavior

• **SetAppBackgroundDownloadsBehavior**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:21](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L21)

___

### SetAppCurrentLanguage

• **SetAppCurrentLanguage**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:19](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L19)

___

### SetAppHidden

• **SetAppHidden**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:15](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L15)

___

### SetAppLaunchOptions

• **SetAppLaunchOptions**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:17](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L17)

___

### SetAppResolutionOverride

• **SetAppResolutionOverride**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:18](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L18)

___

### SetCachedAppDetails

• **SetCachedAppDetails**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:66](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L66)

___

### SetControllerRumblePreference

• **SetControllerRumblePreference**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:64](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L64)

___

### SetCustomArtworkForApp

• **SetCustomArtworkForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:70](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L70)

___

### SetCustomLogoPositionForApp

• **SetCustomLogoPositionForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:72](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L72)

___

### SetDLCEnabled

• **SetDLCEnabled**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:92](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L92)

___

### SetLocalScreenshotCaption

• **SetLocalScreenshotCaption**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:41](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L41)

___

### SetLocalScreenshotSpoiler

• **SetLocalScreenshotSpoiler**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:42](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L42)

___

### SetShortcutExe

• **SetShortcutExe**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:78](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L78)

___

### SetShortcutIsVR

• **SetShortcutIsVR**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:81](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L81)

___

### SetShortcutLaunchOptions

• **SetShortcutLaunchOptions**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:80](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L80)

___

### SetShortcutName

• **SetShortcutName**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:77](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L77)

___

### SetShortcutStartDir

• **SetShortcutStartDir**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:79](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L79)

___

### SetStreamingClientForApp

• **SetStreamingClientForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:69](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L69)

___

### SetThirdPartyControllerConfiguration

• **SetThirdPartyControllerConfiguration**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:62](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L62)

___

### ShowControllerConfigurator

• **ShowControllerConfigurator**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:61](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L61)

___

### ShowStore

• **ShowStore**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:91](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L91)

___

### SkipShaderProcessing

• **SkipShaderProcessing**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:98](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L98)

___

### SpecifyCompatTool

• **SpecifyCompatTool**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:75](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L75)

___

### StreamGame

• **StreamGame**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:87](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L87)

___

### SubscribeWorkshopItem

• **SubscribeWorkshopItem**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:38](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L38)

___

### TerminateApp

• **TerminateApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:89](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L89)

___

### ToggleAllowDesktopConfiguration

• **ToggleAllowDesktopConfiguration**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:63](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L63)

___

### ToggleAppFamilyBlockedState

• **ToggleAppFamilyBlockedState**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:22](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L22)

___

### ToggleAppSteamCloudEnabled

• **ToggleAppSteamCloudEnabled**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:23](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L23)

___

### ToggleAppSteamCloudSyncOnSuspendEnabled

• **ToggleAppSteamCloudSyncOnSuspendEnabled**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:24](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L24)

___

### ToggleEnableDesktopTheatreForApp

• **ToggleEnableDesktopTheatreForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:27](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L27)

___

### ToggleEnableSteamOverlayForApp

• **ToggleEnableSteamOverlayForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:26](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L26)

___

### ToggleOverrideResolutionForInternalDisplay

• **ToggleOverrideResolutionForInternalDisplay**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:25](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L25)

___

### UninstallApps

• **UninstallApps**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:90](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L90)

___

### UninstallFlatpakApp

• **UninstallFlatpakApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:60](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L60)

___

### UploadLocalScreenshot

• **UploadLocalScreenshot**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:44](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L44)

___

### VerifyApp

• **VerifyApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:86](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L86)

___

### VerifyFilesForApp

• **VerifyFilesForApp**: `any`

#### Defined in

[src/deck-components/SteamClient.ts:32](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/925ea8c/src/deck-components/SteamClient.ts#L32)
