[decky-frontend-lib](../README.md) / [Modules](../modules.md) / [deck-components/SteamClient](../modules/deck_components_SteamClient.md) / AppDetails

# Interface: AppDetails

[deck-components/SteamClient](../modules/deck_components_SteamClient.md).AppDetails

## Table of contents

### Properties

- [achievements](deck_components_SteamClient.AppDetails.md#achievements)
- [bCanMoveInstallFolder](deck_components_SteamClient.AppDetails.md#bcanmoveinstallfolder)
- [bCloudAvailable](deck_components_SteamClient.AppDetails.md#bcloudavailable)
- [bCloudEnabledForAccount](deck_components_SteamClient.AppDetails.md#bcloudenabledforaccount)
- [bCloudEnabledForApp](deck_components_SteamClient.AppDetails.md#bcloudenabledforapp)
- [bCloudSyncOnSuspendAvailable](deck_components_SteamClient.AppDetails.md#bcloudsynconsuspendavailable)
- [bCloudSyncOnSuspendEnabled](deck_components_SteamClient.AppDetails.md#bcloudsynconsuspendenabled)
- [bCommunityMarketPresence](deck_components_SteamClient.AppDetails.md#bcommunitymarketpresence)
- [bEnableAllowDesktopConfiguration](deck_components_SteamClient.AppDetails.md#benableallowdesktopconfiguration)
- [bFreeRemovableLicense](deck_components_SteamClient.AppDetails.md#bfreeremovablelicense)
- [bHasAllLegacyCDKeys](deck_components_SteamClient.AppDetails.md#bhasalllegacycdkeys)
- [bHasAnyLocalContent](deck_components_SteamClient.AppDetails.md#bhasanylocalcontent)
- [bHasLockedPrivateBetas](deck_components_SteamClient.AppDetails.md#bhaslockedprivatebetas)
- [bIsExcludedFromSharing](deck_components_SteamClient.AppDetails.md#bisexcludedfromsharing)
- [bIsSubscribedTo](deck_components_SteamClient.AppDetails.md#bissubscribedto)
- [bOverlayEnabled](deck_components_SteamClient.AppDetails.md#boverlayenabled)
- [bOverrideInternalResolution](deck_components_SteamClient.AppDetails.md#boverrideinternalresolution)
- [bRequiresLegacyCDKey](deck_components_SteamClient.AppDetails.md#brequireslegacycdkey)
- [bShortcutIsVR](deck_components_SteamClient.AppDetails.md#bshortcutisvr)
- [bShowCDKeyInMenus](deck_components_SteamClient.AppDetails.md#bshowcdkeyinmenus)
- [bShowControllerConfig](deck_components_SteamClient.AppDetails.md#bshowcontrollerconfig)
- [bSupportsCDKeyCopyToClipboard](deck_components_SteamClient.AppDetails.md#bsupportscdkeycopytoclipboard)
- [bVRGameTheatreEnabled](deck_components_SteamClient.AppDetails.md#bvrgametheatreenabled)
- [bWorkshopVisible](deck_components_SteamClient.AppDetails.md#bworkshopvisible)
- [eAppOwnershipFlags](deck_components_SteamClient.AppDetails.md#eappownershipflags)
- [eAutoUpdateValue](deck_components_SteamClient.AppDetails.md#eautoupdatevalue)
- [eBackgroundDownloads](deck_components_SteamClient.AppDetails.md#ebackgrounddownloads)
- [eCloudSync](deck_components_SteamClient.AppDetails.md#ecloudsync)
- [eControllerRumblePreference](deck_components_SteamClient.AppDetails.md#econtrollerrumblepreference)
- [eDisplayStatus](deck_components_SteamClient.AppDetails.md#edisplaystatus)
- [eEnableThirdPartyControllerConfiguration](deck_components_SteamClient.AppDetails.md#eenablethirdpartycontrollerconfiguration)
- [eSteamInputControllerMask](deck_components_SteamClient.AppDetails.md#esteaminputcontrollermask)
- [iInstallFolder](deck_components_SteamClient.AppDetails.md#iinstallfolder)
- [lDiskUsageBytes](deck_components_SteamClient.AppDetails.md#ldiskusagebytes)
- [lDlcUsageBytes](deck_components_SteamClient.AppDetails.md#ldlcusagebytes)
- [nBuildID](deck_components_SteamClient.AppDetails.md#nbuildid)
- [nCompatToolPriority](deck_components_SteamClient.AppDetails.md#ncompattoolpriority)
- [nPlaytimeForever](deck_components_SteamClient.AppDetails.md#nplaytimeforever)
- [nScreenshots](deck_components_SteamClient.AppDetails.md#nscreenshots)
- [rtLastTimePlayed](deck_components_SteamClient.AppDetails.md#rtlasttimeplayed)
- [rtLastUpdated](deck_components_SteamClient.AppDetails.md#rtlastupdated)
- [rtPurchased](deck_components_SteamClient.AppDetails.md#rtpurchased)
- [selectedLanguage](deck_components_SteamClient.AppDetails.md#selectedlanguage)
- [strCloudBytesAvailable](deck_components_SteamClient.AppDetails.md#strcloudbytesavailable)
- [strCloudBytesUsed](deck_components_SteamClient.AppDetails.md#strcloudbytesused)
- [strCompatToolDisplayName](deck_components_SteamClient.AppDetails.md#strcompattooldisplayname)
- [strCompatToolName](deck_components_SteamClient.AppDetails.md#strcompattoolname)
- [strDeveloperName](deck_components_SteamClient.AppDetails.md#strdevelopername)
- [strDeveloperURL](deck_components_SteamClient.AppDetails.md#strdeveloperurl)
- [strDisplayName](deck_components_SteamClient.AppDetails.md#strdisplayname)
- [strExternalSubscriptionURL](deck_components_SteamClient.AppDetails.md#strexternalsubscriptionurl)
- [strFlatpakAppID](deck_components_SteamClient.AppDetails.md#strflatpakappid)
- [strHomepageURL](deck_components_SteamClient.AppDetails.md#strhomepageurl)
- [strLaunchOptions](deck_components_SteamClient.AppDetails.md#strlaunchoptions)
- [strManualURL](deck_components_SteamClient.AppDetails.md#strmanualurl)
- [strOwnerSteamID](deck_components_SteamClient.AppDetails.md#strownersteamid)
- [strResolutionOverride](deck_components_SteamClient.AppDetails.md#strresolutionoverride)
- [strSelectedBeta](deck_components_SteamClient.AppDetails.md#strselectedbeta)
- [strShortcutExe](deck_components_SteamClient.AppDetails.md#strshortcutexe)
- [strShortcutLaunchOptions](deck_components_SteamClient.AppDetails.md#strshortcutlaunchoptions)
- [strShortcutStartDir](deck_components_SteamClient.AppDetails.md#strshortcutstartdir)
- [strSteamDeckBlogURL](deck_components_SteamClient.AppDetails.md#strsteamdeckblogurl)
- [unAppID](deck_components_SteamClient.AppDetails.md#unappid)
- [vecBetas](deck_components_SteamClient.AppDetails.md#vecbetas)
- [vecDLC](deck_components_SteamClient.AppDetails.md#vecdlc)
- [vecDeckCompatTestResults](deck_components_SteamClient.AppDetails.md#vecdeckcompattestresults)
- [vecLanguages](deck_components_SteamClient.AppDetails.md#veclanguages)
- [vecLegacyCDKeys](deck_components_SteamClient.AppDetails.md#veclegacycdkeys)
- [vecMusicAlbums](deck_components_SteamClient.AppDetails.md#vecmusicalbums)
- [vecPlatforms](deck_components_SteamClient.AppDetails.md#vecplatforms)
- [vecScreenShots](deck_components_SteamClient.AppDetails.md#vecscreenshots)

## Properties

### achievements

• **achievements**: [`AppAchievements`](../modules/deck_components_SteamClient.md#appachievements)

#### Defined in

[src/deck-components/SteamClient.ts:221](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L221)

___

### bCanMoveInstallFolder

• **bCanMoveInstallFolder**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:222](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L222)

___

### bCloudAvailable

• **bCloudAvailable**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:223](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L223)

___

### bCloudEnabledForAccount

• **bCloudEnabledForAccount**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:224](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L224)

___

### bCloudEnabledForApp

• **bCloudEnabledForApp**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:225](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L225)

___

### bCloudSyncOnSuspendAvailable

• **bCloudSyncOnSuspendAvailable**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:226](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L226)

___

### bCloudSyncOnSuspendEnabled

• **bCloudSyncOnSuspendEnabled**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:227](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L227)

___

### bCommunityMarketPresence

• **bCommunityMarketPresence**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:228](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L228)

___

### bEnableAllowDesktopConfiguration

• **bEnableAllowDesktopConfiguration**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:229](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L229)

___

### bFreeRemovableLicense

• **bFreeRemovableLicense**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:230](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L230)

___

### bHasAllLegacyCDKeys

• **bHasAllLegacyCDKeys**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:231](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L231)

___

### bHasAnyLocalContent

• **bHasAnyLocalContent**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:232](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L232)

___

### bHasLockedPrivateBetas

• **bHasLockedPrivateBetas**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:233](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L233)

___

### bIsExcludedFromSharing

• **bIsExcludedFromSharing**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:234](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L234)

___

### bIsSubscribedTo

• **bIsSubscribedTo**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:235](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L235)

___

### bOverlayEnabled

• **bOverlayEnabled**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:236](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L236)

___

### bOverrideInternalResolution

• **bOverrideInternalResolution**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:237](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L237)

___

### bRequiresLegacyCDKey

• **bRequiresLegacyCDKey**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:238](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L238)

___

### bShortcutIsVR

• **bShortcutIsVR**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:239](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L239)

___

### bShowCDKeyInMenus

• **bShowCDKeyInMenus**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:240](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L240)

___

### bShowControllerConfig

• **bShowControllerConfig**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:241](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L241)

___

### bSupportsCDKeyCopyToClipboard

• **bSupportsCDKeyCopyToClipboard**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:242](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L242)

___

### bVRGameTheatreEnabled

• **bVRGameTheatreEnabled**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:243](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L243)

___

### bWorkshopVisible

• **bWorkshopVisible**: `boolean`

#### Defined in

[src/deck-components/SteamClient.ts:244](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L244)

___

### eAppOwnershipFlags

• **eAppOwnershipFlags**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:245](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L245)

___

### eAutoUpdateValue

• **eAutoUpdateValue**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:246](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L246)

___

### eBackgroundDownloads

• **eBackgroundDownloads**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:247](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L247)

___

### eCloudSync

• **eCloudSync**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:248](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L248)

___

### eControllerRumblePreference

• **eControllerRumblePreference**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:249](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L249)

___

### eDisplayStatus

• **eDisplayStatus**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:250](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L250)

___

### eEnableThirdPartyControllerConfiguration

• **eEnableThirdPartyControllerConfiguration**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:251](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L251)

___

### eSteamInputControllerMask

• **eSteamInputControllerMask**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:252](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L252)

___

### iInstallFolder

• **iInstallFolder**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:253](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L253)

___

### lDiskUsageBytes

• **lDiskUsageBytes**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:254](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L254)

___

### lDlcUsageBytes

• **lDlcUsageBytes**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:255](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L255)

___

### nBuildID

• **nBuildID**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:256](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L256)

___

### nCompatToolPriority

• **nCompatToolPriority**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:257](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L257)

___

### nPlaytimeForever

• **nPlaytimeForever**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:258](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L258)

___

### nScreenshots

• **nScreenshots**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:259](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L259)

___

### rtLastTimePlayed

• **rtLastTimePlayed**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:260](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L260)

___

### rtLastUpdated

• **rtLastUpdated**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:261](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L261)

___

### rtPurchased

• **rtPurchased**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:262](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L262)

___

### selectedLanguage

• **selectedLanguage**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `strDisplayName` | `string` |
| `strShortName` | `string` |

#### Defined in

[src/deck-components/SteamClient.ts:263](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L263)

___

### strCloudBytesAvailable

• **strCloudBytesAvailable**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:267](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L267)

___

### strCloudBytesUsed

• **strCloudBytesUsed**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:268](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L268)

___

### strCompatToolDisplayName

• **strCompatToolDisplayName**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:269](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L269)

___

### strCompatToolName

• **strCompatToolName**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:270](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L270)

___

### strDeveloperName

• **strDeveloperName**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:271](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L271)

___

### strDeveloperURL

• **strDeveloperURL**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:272](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L272)

___

### strDisplayName

• **strDisplayName**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:273](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L273)

___

### strExternalSubscriptionURL

• **strExternalSubscriptionURL**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:274](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L274)

___

### strFlatpakAppID

• **strFlatpakAppID**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:275](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L275)

___

### strHomepageURL

• **strHomepageURL**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:276](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L276)

___

### strLaunchOptions

• **strLaunchOptions**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:277](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L277)

___

### strManualURL

• **strManualURL**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:278](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L278)

___

### strOwnerSteamID

• **strOwnerSteamID**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:279](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L279)

___

### strResolutionOverride

• **strResolutionOverride**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:280](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L280)

___

### strSelectedBeta

• **strSelectedBeta**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:281](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L281)

___

### strShortcutExe

• **strShortcutExe**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:282](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L282)

___

### strShortcutLaunchOptions

• **strShortcutLaunchOptions**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:283](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L283)

___

### strShortcutStartDir

• **strShortcutStartDir**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:284](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L284)

___

### strSteamDeckBlogURL

• **strSteamDeckBlogURL**: `string`

#### Defined in

[src/deck-components/SteamClient.ts:285](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L285)

___

### unAppID

• **unAppID**: `number`

#### Defined in

[src/deck-components/SteamClient.ts:286](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L286)

___

### vecBetas

• **vecBetas**: `any`[]

#### Defined in

[src/deck-components/SteamClient.ts:287](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L287)

___

### vecDLC

• **vecDLC**: `any`[]

#### Defined in

[src/deck-components/SteamClient.ts:288](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L288)

___

### vecDeckCompatTestResults

• **vecDeckCompatTestResults**: `any`[]

#### Defined in

[src/deck-components/SteamClient.ts:289](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L289)

___

### vecLanguages

• **vecLanguages**: [`AppLanguages`](../modules/deck_components_SteamClient.md#applanguages)[]

#### Defined in

[src/deck-components/SteamClient.ts:290](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L290)

___

### vecLegacyCDKeys

• **vecLegacyCDKeys**: `any`[]

#### Defined in

[src/deck-components/SteamClient.ts:291](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L291)

___

### vecMusicAlbums

• **vecMusicAlbums**: `any`[]

#### Defined in

[src/deck-components/SteamClient.ts:292](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L292)

___

### vecPlatforms

• **vecPlatforms**: `string`[]

#### Defined in

[src/deck-components/SteamClient.ts:293](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L293)

___

### vecScreenShots

• **vecScreenShots**: `any`[]

#### Defined in

[src/deck-components/SteamClient.ts:294](https://github.com/SteamDeckHomebrew/decky-frontend-lib/blob/82ed487/src/deck-components/SteamClient.ts#L294)
