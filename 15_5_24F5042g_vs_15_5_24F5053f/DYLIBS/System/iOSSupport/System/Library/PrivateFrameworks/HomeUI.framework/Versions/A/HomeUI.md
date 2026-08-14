## HomeUI

> `/System/iOSSupport/System/Library/PrivateFrameworks/HomeUI.framework/Versions/A/HomeUI`

```diff

-1026.6.20.0.0
-  __TEXT.__text: 0x5b4628
-  __TEXT.__auth_stubs: 0x6320
-  __TEXT.__objc_methlist: 0x48b34
-  __TEXT.__const: 0x9b30
+1026.6.26.0.0
+  __TEXT.__text: 0x5b4d94
+  __TEXT.__auth_stubs: 0x6330
+  __TEXT.__objc_methlist: 0x48b84
+  __TEXT.__const: 0x9b50
   __TEXT.__dlopen_cstrs: 0xda
-  __TEXT.__cstring: 0x40812
+  __TEXT.__cstring: 0x40953
   __TEXT.__swift5_typeref: 0xa2d0
   __TEXT.__swift5_fieldmd: 0x3754
   __TEXT.__constg_swiftt: 0x7510

   __TEXT.__swift5_proto: 0x4e8
   __TEXT.__swift5_types: 0x440
   __TEXT.__swift5_capture: 0x20a0
-  __TEXT.__oslogstring: 0x1b9f4
+  __TEXT.__oslogstring: 0x1bf4c
   __TEXT.__swift_as_entry: 0x1cc
   __TEXT.__swift_as_ret: 0x1f0
   __TEXT.__swift5_mpenum: 0x3c
-  __TEXT.__gcc_except_tab: 0x8a94
+  __TEXT.__gcc_except_tab: 0x8b00
   __TEXT.__ustring: 0x7e
-  __TEXT.__unwind_info: 0x145a8
+  __TEXT.__unwind_info: 0x145c8
   __TEXT.__eh_frame: 0x7a44
-  __TEXT.__objc_classname: 0xbc26
-  __TEXT.__objc_methname: 0x9f7aa
+  __TEXT.__objc_classname: 0xbc3d
+  __TEXT.__objc_methname: 0x9f889
   __TEXT.__objc_methtype: 0x14433
-  __TEXT.__objc_stubs: 0x63ee0
-  __DATA_CONST.__got: 0x5798
-  __DATA_CONST.__const: 0xdbf8
+  __TEXT.__objc_stubs: 0x64000
+  __DATA_CONST.__got: 0x57a0
+  __DATA_CONST.__const: 0xdc20
   __DATA_CONST.__objc_classlist: 0x2510
-  __DATA_CONST.__objc_catlist: 0x1f0
+  __DATA_CONST.__objc_catlist: 0x1f8
   __DATA_CONST.__objc_protolist: 0x10a8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1eee8
+  __DATA_CONST.__objc_selrefs: 0x1ef28
   __DATA_CONST.__objc_protorefs: 0x628
   __DATA_CONST.__objc_superrefs: 0x1cb0
   __DATA_CONST.__objc_arraydata: 0x840
-  __AUTH_CONST.__auth_got: 0x31a0
-  __AUTH_CONST.__const: 0xed30
-  __AUTH_CONST.__cfstring: 0x1fac0
-  __AUTH_CONST.__objc_const: 0x81618
+  __AUTH_CONST.__auth_got: 0x31a8
+  __AUTH_CONST.__const: 0xed90
+  __AUTH_CONST.__cfstring: 0x1fb80
+  __AUTH_CONST.__objc_const: 0x81690
   __AUTH_CONST.__objc_intobj: 0x1968
   __AUTH_CONST.__objc_arrayobj: 0x3d8
   __AUTH_CONST.__objc_dictobj: 0x578

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 33493
-  Symbols:   54275
-  CStrings:  34586
+  Functions: 33501
+  Symbols:   54299
+  CStrings:  34607
 
Symbols:
+ +[HMHome(HomeHubMigrationBanner) _hh1EOLAccessories:]
+ -[HMHome(HomeHubMigrationBanner) hf_homeHubMigrationBannerDescription]
+ -[HMHome(HomeHubMigrationBanner) hf_homeHubMigrationBannerTitle]
+ -[HMHome(HomeHubMigrationBanner) hf_isHomeHubMigrationBannerVisible]
+ -[HMHome(HomeHubMigrationBanner) hf_shouldDisplayHH2UpdateLearnMore]
+ _HFForceHomeHubMigrationBannerVisible
+ _OBJC_CLASS_$_HFMatterAccessoryLikeItemProvider
+ __OBJC_$_CATEGORY_CLASS_METHODS_HMHome_$_HomeHubMigrationBanner
+ __OBJC_$_CATEGORY_HMHome_$_HomeHubMigrationBanner
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_HMHome_$_HomeHubMigrationBanner
+ __OBJC_$_PROP_LIST_HMHome_$_HomeHubMigrationBanner
+ ___53+[HMHome(HomeHubMigrationBanner) _hh1EOLAccessories:]_block_invoke
+ ___70-[HMHome(HomeHubMigrationBanner) hf_homeHubMigrationBannerDescription]_block_invoke
+ ___70-[HMHome(HomeHubMigrationBanner) hf_homeHubMigrationBannerDescription]_block_invoke_2
+ ___block_descriptor_40_e8_32w_e27_"NAFuture"16?0"NSArray"8lw32l8
+ _objc_msgSend$_hh1EOLAccessories:
+ _objc_msgSend$hf_allResidentAccessories
+ _objc_msgSend$hf_homeHubMigrationBannerDescription
+ _objc_msgSend$hf_homeHubMigrationBannerTitle
+ _objc_msgSend$hf_isHomeHubMigrationBannerVisible
+ _objc_msgSend$hf_shouldDisplayHH2UpdateLearnMore
+ _objc_msgSend$hf_shouldPostHH2UgradeRequired
+ _objc_msgSend$hu_homeUpdateLearnMoreURL
+ _objc_msgSend$itemProviderInHome:inRoom:
+ _objc_msgSend$majorVersion
- _objc_msgSend$hf_shouldPostHomeUgradeRequired
CStrings:
+ "%s: bulletinBoardNotificationByEndpoint: %@ for accessory: %@"
+ "(HMHome:hf_homeHubMigrationBannerDescription:) homeUUID = %{public}@ | Resident contains both ATV and HP | atvs.count = %ld | atvsHH1EOL.count = %ld | hps.count = %ld | hpsHH1EOL.count = %ld | enabledResidents.count = %ld | allResidentsCount = %ld | isOwner = %{BOOL}d"
+ "(HMHome:hf_homeHubMigrationBannerDescription:) homeUUID = %{public}@ | allResidentsAreATVsWithHH1EOL = YES | atvs.count = %ld | atvsHH1EOL.count = %ld | enabledResidents.count = %ld | allResidentsCount = %ld | isOwner = %{BOOL}d"
+ "(HMHome:hf_homeHubMigrationBannerDescription:) homeUUID = %{public}@ | allResidentsAreHPsWithHH1EOL = YES | hps.count = %ld | hpsHH1EOL.count = %ld | enabledResidents.count = %ld | allResidentsCount = %ld | isOwner = %{BOOL}d"
+ "(HMHome:hf_homeHubMigrationBannerDescription:) homeUUID = %{public}@ | allResidentsAreiPads = YES | enabledResidents.count = %ld | enabledIPads.count = %ld | isOwner = %{BOOL}d"
+ "(HUDashboardViewController:didSelectHomeHubMigrationBanner) userTappedLearnMore %{BOOL}d"
+ "(HUHomeHubMigrationBannerItem:shouldHideForHomes:withUserDefaults:softwareUpdateCounter) Forcing home hub migration banner to be visible."
+ "<HMHome+HomeHubMigrationBanner-hf_isHomeHubMigrationBannerVisible:> Showing HH2 migration banner: %{BOOL}d | canUpdateToHH2: %{BOOL}d | isOwner:%{BOOL}d | migrationAvailable:%{BOOL}d | userAlreadyOptedIn:%{BOOL}d | shouldPostHH2UgradeRequired: %{BOOL}d"
+ "<HUSoftwareUpdateStandaloneViewController-bannerView:footerViewTapped:> Completed handling migration banner tapping with result %@"
+ "<HUSoftwareUpdateStandaloneViewController-bannerView:footerViewTapped:> userTappedLearnMore from software update banner %{BOOL}d | hpSWUpdateInProgress = %{BOOL}d"
+ "HULearnMoreTitle"
+ "HUResidentSWUpdateRequired_AllResidentsAreATVsWithHH1EOL_Description"
+ "HUResidentSWUpdateRequired_AllResidentsAreHomePodsWithHH1EOL_Description"
+ "HUResidentSWUpdateRequired_HasHH1EOL_Description"
+ "HUResidentSWUpdateRequired_NonOwner_Description"
+ "HUSoftwareUpdateHomeKitUpdateRequiredDescription_accessoriesOnly"
+ "HomeHubMigrationBanner"
+ "_hh1EOLAccessories:"
+ "hf_allResidentAccessories"
+ "hf_homeHubMigrationBannerDescription"
+ "hf_homeHubMigrationBannerTitle"
+ "hf_isHomeHubMigrationBannerVisible"
+ "hf_shouldDisplayHH2UpdateLearnMore"
+ "hf_shouldPostHH2UgradeRequired"
+ "itemProviderInHome:inRoom:"
+ "majorVersion"
- "%s: bulletinBoardNotificationByEndpoint: %@"
- "Hiding HH2 migration banner. Owner:%@ migrationAvailable:%@ userAlreadyOptedIn:%@"
- "Should show HH2 migration banner?:NO Owner:%{BOOL}d migrationAvailable:%{BOOL}d userAlreadyOptedIn:%{BOOL}d. Skipping user defaults and software update checks."
- "Showing HH2 migration banner. Owner:%@ migrationAvailable:%@ userAlreadyOptedIn:%@"
- "hf_shouldPostHomeUgradeRequired"
```
