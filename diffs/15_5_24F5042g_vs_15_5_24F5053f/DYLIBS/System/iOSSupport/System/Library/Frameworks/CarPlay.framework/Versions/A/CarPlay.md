## CarPlay

> `/System/iOSSupport/System/Library/Frameworks/CarPlay.framework/Versions/A/CarPlay`

```diff

-340.2.0.0.0
-  __TEXT.__text: 0x38d3c
-  __TEXT.__auth_stubs: 0x5f0
-  __TEXT.__objc_methlist: 0x5e80
-  __TEXT.__const: 0x1b8
-  __TEXT.__cstring: 0x32bb
-  __TEXT.__oslogstring: 0x1351
-  __TEXT.__gcc_except_tab: 0x5b0
-  __TEXT.__unwind_info: 0x12c8
-  __TEXT.__objc_classname: 0xd08
-  __TEXT.__objc_methname: 0xc1e4
-  __TEXT.__objc_methtype: 0x1ed3
-  __TEXT.__objc_stubs: 0x72e0
-  __DATA_CONST.__got: 0x4c0
-  __DATA_CONST.__const: 0x17a0
-  __DATA_CONST.__objc_classlist: 0x2b0
+347.24.1.0.0
+  __TEXT.__text: 0x3bc9c
+  __TEXT.__auth_stubs: 0x600
+  __TEXT.__objc_methlist: 0x63a0
+  __TEXT.__const: 0x1d0
+  __TEXT.__cstring: 0x35e6
+  __TEXT.__oslogstring: 0x1420
+  __TEXT.__gcc_except_tab: 0x5bc
+  __TEXT.__unwind_info: 0x13b0
+  __TEXT.__objc_classname: 0xdd8
+  __TEXT.__objc_methname: 0xca10
+  __TEXT.__objc_methtype: 0x1fc5
+  __TEXT.__objc_stubs: 0x76c0
+  __DATA_CONST.__got: 0x4f8
+  __DATA_CONST.__const: 0x17c8
+  __DATA_CONST.__objc_classlist: 0x2e8
   __DATA_CONST.__objc_catlist: 0x18
-  __DATA_CONST.__objc_protolist: 0x1c0
+  __DATA_CONST.__objc_protolist: 0x1c8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x28f8
-  __DATA_CONST.__objc_protorefs: 0xe0
-  __DATA_CONST.__objc_superrefs: 0x210
-  __AUTH_CONST.__auth_got: 0x308
-  __AUTH_CONST.__const: 0x6c0
-  __AUTH_CONST.__cfstring: 0x3700
-  __AUTH_CONST.__objc_const: 0x16e20
+  __DATA_CONST.__objc_selrefs: 0x2a68
+  __DATA_CONST.__objc_protorefs: 0xe8
+  __DATA_CONST.__objc_superrefs: 0x248
+  __AUTH_CONST.__auth_got: 0x310
+  __AUTH_CONST.__const: 0x6e0
+  __AUTH_CONST.__cfstring: 0x39e0
+  __AUTH_CONST.__objc_const: 0x180f8
   __AUTH_CONST.__objc_intobj: 0xd8
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH.__objc_data: 0x1ae0
-  __DATA.__objc_ivar: 0x670
-  __DATA.__data: 0x1500
-  __DATA.__bss: 0x208
+  __AUTH.__objc_data: 0x1d10
+  __DATA.__objc_ivar: 0x6dc
+  __DATA.__data: 0x1560
+  __DATA.__bss: 0x268
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/Versions/A/CoreGraphics
   - /System/Library/Frameworks/CoreLocation.framework/Versions/A/CoreLocation

   - /System/iOSSupport/System/Library/Frameworks/UIKit.framework/Versions/A/UIKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1995
-  Symbols:   4721
-  CStrings:  3009
+  Functions: 2096
+  Symbols:   4956
+  CStrings:  3149
 
Symbols:
+ +[CPChargingStationConnector(CPAccNavUpdate) accNavParameterKeysIndexed]
+ +[CPChargingStationConnector(CPAccNavUpdate) accNavParametersIndexed]
+ +[CPChargingStationConnector(CPAccNavUpdate) accNavParameters]
+ +[CPListImageRowItem _setMaximumImageSize:]
+ +[CPListItem _setMaximumImageSize:]
+ +[CPNowPlayingMode defaultNowPlayingMode]
+ +[CPNowPlayingMode supportsSecureCoding]
+ +[CPNowPlayingModeSports supportsSecureCoding]
+ +[CPNowPlayingSportsClock supportsSecureCoding]
+ +[CPNowPlayingSportsEventStatus supportsSecureCoding]
+ +[CPNowPlayingSportsTeam supportsSecureCoding]
+ +[CPNowPlayingSportsTeamLogo supportsSecureCoding]
+ -[CPChargingStationConnector(CPAccNavUpdate) clearValueForKey:]
+ -[CPInterfaceController _completeSetupWithCompletion:]
+ -[CPListTemplate setShowsSpinnerWhileEmpty:]
+ -[CPListTemplate showsSpinnerWhileEmpty]
+ -[CPNavigationManager _updateRouteGuidance:]
+ -[CPNavigationManager controlsAccNav]
+ -[CPNavigationManager mutateRouteGuidance:]
+ -[CPNavigationManager setControlsAccNav:]
+ -[CPNowPlayingMode .cxx_destruct]
+ -[CPNowPlayingMode encodeWithCoder:]
+ -[CPNowPlayingMode hash]
+ -[CPNowPlayingMode identifier]
+ -[CPNowPlayingMode initWithCoder:]
+ -[CPNowPlayingMode init]
+ -[CPNowPlayingMode isEqual:]
+ -[CPNowPlayingMode isEqualToNowPlayingMode:]
+ -[CPNowPlayingModeSports .cxx_destruct]
+ -[CPNowPlayingModeSports backgroundArtwork]
+ -[CPNowPlayingModeSports encodeWithCoder:]
+ -[CPNowPlayingModeSports eventStatus]
+ -[CPNowPlayingModeSports hash]
+ -[CPNowPlayingModeSports initWithCoder:]
+ -[CPNowPlayingModeSports initWithLeftTeam:rightTeam:eventStatus:backgroundArtwork:]
+ -[CPNowPlayingModeSports isEqual:]
+ -[CPNowPlayingModeSports isEqualToNowPlayingModeSports:]
+ -[CPNowPlayingModeSports leftTeam]
+ -[CPNowPlayingModeSports rightTeam]
+ -[CPNowPlayingSportsClock countsUp]
+ -[CPNowPlayingSportsClock encodeWithCoder:]
+ -[CPNowPlayingSportsClock hash]
+ -[CPNowPlayingSportsClock initWithCoder:]
+ -[CPNowPlayingSportsClock initWithElapsedTime:paused:]
+ -[CPNowPlayingSportsClock initWithTimeRemaining:paused:]
+ -[CPNowPlayingSportsClock isEqual:]
+ -[CPNowPlayingSportsClock isEqualToSportsClock:]
+ -[CPNowPlayingSportsClock isPaused]
+ -[CPNowPlayingSportsClock timeValue]
+ -[CPNowPlayingSportsEventStatus .cxx_destruct]
+ -[CPNowPlayingSportsEventStatus encodeWithCoder:]
+ -[CPNowPlayingSportsEventStatus eventClock]
+ -[CPNowPlayingSportsEventStatus eventStatusImage]
+ -[CPNowPlayingSportsEventStatus eventStatusText]
+ -[CPNowPlayingSportsEventStatus hash]
+ -[CPNowPlayingSportsEventStatus initWithCoder:]
+ -[CPNowPlayingSportsEventStatus initWithEventStatusText:eventStatusImage:eventClock:]
+ -[CPNowPlayingSportsEventStatus isEqual:]
+ -[CPNowPlayingSportsEventStatus isEqualToGameStatus:]
+ -[CPNowPlayingSportsTeam .cxx_destruct]
+ -[CPNowPlayingSportsTeam encodeWithCoder:]
+ -[CPNowPlayingSportsTeam eventScore]
+ -[CPNowPlayingSportsTeam hash]
+ -[CPNowPlayingSportsTeam identifier]
+ -[CPNowPlayingSportsTeam initWithCoder:]
+ -[CPNowPlayingSportsTeam initWithName:logo:teamStandings:eventScore:possessionIndicator:favorite:]
+ -[CPNowPlayingSportsTeam isEqual:]
+ -[CPNowPlayingSportsTeam isEqualToSportsTeam:]
+ -[CPNowPlayingSportsTeam isFavorite]
+ -[CPNowPlayingSportsTeam logo]
+ -[CPNowPlayingSportsTeam name]
+ -[CPNowPlayingSportsTeam possessionIndicator]
+ -[CPNowPlayingSportsTeam teamStandings]
+ -[CPNowPlayingSportsTeamLogo .cxx_destruct]
+ -[CPNowPlayingSportsTeamLogo encodeWithCoder:]
+ -[CPNowPlayingSportsTeamLogo hashValue]
+ -[CPNowPlayingSportsTeamLogo initWithCoder:]
+ -[CPNowPlayingSportsTeamLogo initWithTeamInitials:]
+ -[CPNowPlayingSportsTeamLogo initWithTeamLogo:]
+ -[CPNowPlayingSportsTeamLogo initials]
+ -[CPNowPlayingSportsTeamLogo isEqual:]
+ -[CPNowPlayingSportsTeamLogo isEqualToTeamLogo:]
+ -[CPNowPlayingSportsTeamLogo logo]
+ -[CPNowPlayingTemplate nowPlayingMode]
+ -[CPNowPlayingTemplate setNowPlayingMode:]
+ -[CPTemplateApplicationDashboardScene sceneSettingsDiffAction]
+ -[CPTemplateApplicationDashboardScene setSceneSettingsDiffAction:]
+ -[CPTemplateApplicationInstrumentClusterScene sceneSettingsDiffAction]
+ -[CPTemplateApplicationInstrumentClusterScene setSceneSettingsDiffAction:]
+ -[CPTemplateApplicationScene sceneSettingsDiffAction]
+ -[CPTemplateApplicationScene setSceneSettingsDiffAction:]
+ -[CPTemplateUISceneSettingsDiffAction .cxx_destruct]
+ -[CPTemplateUISceneSettingsDiffAction _performActionsForUIScene:withUpdatedFBSScene:settingsDiff:fromSettings:transitionContext:lifecycleActionType:]
+ -[CPTemplateUISceneSettingsDiffAction initWithInspectors:]
+ -[CPTemplateUISceneSettingsDiffAction inspectors]
+ -[CPTemplateUISceneSettingsDiffAction setInspectors:]
+ GCC_except_table109
+ GCC_except_table31
+ OBJC_IVAR_$_CPListTemplate._showsSpinnerWhileEmpty
+ OBJC_IVAR_$_CPNavigationManager._controlsAccNav
+ OBJC_IVAR_$_CPNowPlayingMode._identifier
+ OBJC_IVAR_$_CPNowPlayingModeSports._backgroundArtwork
+ OBJC_IVAR_$_CPNowPlayingModeSports._eventStatus
+ OBJC_IVAR_$_CPNowPlayingModeSports._leftTeam
+ OBJC_IVAR_$_CPNowPlayingModeSports._rightTeam
+ OBJC_IVAR_$_CPNowPlayingSportsClock._countsUp
+ OBJC_IVAR_$_CPNowPlayingSportsClock._paused
+ OBJC_IVAR_$_CPNowPlayingSportsClock._timeValue
+ OBJC_IVAR_$_CPNowPlayingSportsEventStatus._eventClock
+ OBJC_IVAR_$_CPNowPlayingSportsEventStatus._eventStatusImage
+ OBJC_IVAR_$_CPNowPlayingSportsEventStatus._eventStatusText
+ OBJC_IVAR_$_CPNowPlayingSportsTeam._eventScore
+ OBJC_IVAR_$_CPNowPlayingSportsTeam._favorite
+ OBJC_IVAR_$_CPNowPlayingSportsTeam._identifier
+ OBJC_IVAR_$_CPNowPlayingSportsTeam._logo
+ OBJC_IVAR_$_CPNowPlayingSportsTeam._name
+ OBJC_IVAR_$_CPNowPlayingSportsTeam._possessionIndicator
+ OBJC_IVAR_$_CPNowPlayingSportsTeam._teamStandings
+ OBJC_IVAR_$_CPNowPlayingSportsTeamLogo._initials
+ OBJC_IVAR_$_CPNowPlayingSportsTeamLogo._logo
+ OBJC_IVAR_$_CPNowPlayingTemplate._nowPlayingMode
+ OBJC_IVAR_$_CPTemplateApplicationDashboardScene._sceneSettingsDiffAction
+ OBJC_IVAR_$_CPTemplateApplicationInstrumentClusterScene._sceneSettingsDiffAction
+ OBJC_IVAR_$_CPTemplateApplicationScene._sceneSettingsDiffAction
+ OBJC_IVAR_$_CPTemplateUISceneSettingsDiffAction._inspectors
+ _CGSizeZero
+ _OBJC_CLASS_$_CPNowPlayingMode
+ _OBJC_CLASS_$_CPNowPlayingModeSports
+ _OBJC_CLASS_$_CPNowPlayingSportsClock
+ _OBJC_CLASS_$_CPNowPlayingSportsEventStatus
+ _OBJC_CLASS_$_CPNowPlayingSportsTeam
+ _OBJC_CLASS_$_CPNowPlayingSportsTeamLogo
+ _OBJC_CLASS_$_CPTemplateUISceneSettingsDiffAction
+ _OBJC_METACLASS_$_CPNowPlayingMode
+ _OBJC_METACLASS_$_CPNowPlayingModeSports
+ _OBJC_METACLASS_$_CPNowPlayingSportsClock
+ _OBJC_METACLASS_$_CPNowPlayingSportsEventStatus
+ _OBJC_METACLASS_$_CPNowPlayingSportsTeam
+ _OBJC_METACLASS_$_CPNowPlayingSportsTeamLogo
+ _OBJC_METACLASS_$_CPTemplateUISceneSettingsDiffAction
+ __96-[CPListTemplate listTemplateWithIdentifier:didSelectImageAtIndex:inImageRowItemWithIdentifier:]_block_invoke
+ __OBJC_$_CLASS_METHODS_CPChargingStationConnector(CPAccNavUpdate)
+ __OBJC_$_CLASS_METHODS_CPNowPlayingMode
+ __OBJC_$_CLASS_METHODS_CPNowPlayingModeSports
+ __OBJC_$_CLASS_METHODS_CPNowPlayingSportsClock
+ __OBJC_$_CLASS_METHODS_CPNowPlayingSportsEventStatus
+ __OBJC_$_CLASS_METHODS_CPNowPlayingSportsTeam
+ __OBJC_$_CLASS_METHODS_CPNowPlayingSportsTeamLogo
+ __OBJC_$_CLASS_PROP_LIST_CPNowPlayingMode
+ __OBJC_$_CLASS_PROP_LIST_CPNowPlayingModeSports
+ __OBJC_$_CLASS_PROP_LIST_CPNowPlayingSportsClock
+ __OBJC_$_CLASS_PROP_LIST_CPNowPlayingSportsEventStatus
+ __OBJC_$_CLASS_PROP_LIST_CPNowPlayingSportsTeam
+ __OBJC_$_CLASS_PROP_LIST_CPNowPlayingSportsTeamLogo
+ __OBJC_$_INSTANCE_METHODS_CPChargingStationConnector(CPAccNavUpdate)
+ __OBJC_$_INSTANCE_METHODS_CPNowPlayingMode
+ __OBJC_$_INSTANCE_METHODS_CPNowPlayingModeSports
+ __OBJC_$_INSTANCE_METHODS_CPNowPlayingSportsClock
+ __OBJC_$_INSTANCE_METHODS_CPNowPlayingSportsEventStatus
+ __OBJC_$_INSTANCE_METHODS_CPNowPlayingSportsTeam
+ __OBJC_$_INSTANCE_METHODS_CPNowPlayingSportsTeamLogo
+ __OBJC_$_INSTANCE_METHODS_CPTemplateUISceneSettingsDiffAction
+ __OBJC_$_INSTANCE_VARIABLES_CPNowPlayingMode
+ __OBJC_$_INSTANCE_VARIABLES_CPNowPlayingModeSports
+ __OBJC_$_INSTANCE_VARIABLES_CPNowPlayingSportsClock
+ __OBJC_$_INSTANCE_VARIABLES_CPNowPlayingSportsEventStatus
+ __OBJC_$_INSTANCE_VARIABLES_CPNowPlayingSportsTeam
+ __OBJC_$_INSTANCE_VARIABLES_CPNowPlayingSportsTeamLogo
+ __OBJC_$_INSTANCE_VARIABLES_CPTemplateUISceneSettingsDiffAction
+ __OBJC_$_PROP_LIST_CPNowPlayingMode
+ __OBJC_$_PROP_LIST_CPNowPlayingModeSports
+ __OBJC_$_PROP_LIST_CPNowPlayingSportsClock
+ __OBJC_$_PROP_LIST_CPNowPlayingSportsEventStatus
+ __OBJC_$_PROP_LIST_CPNowPlayingSportsTeam
+ __OBJC_$_PROP_LIST_CPNowPlayingSportsTeamLogo
+ __OBJC_$_PROP_LIST_CPTemplateUISceneSettingsDiffAction
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CPTabBarTemplateProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CPTabBarTemplateProviding
+ __OBJC_$_PROTOCOL_REFS_CPTabBarTemplateProviding
+ __OBJC_CLASS_PROTOCOLS_$_CPChargingStationConnector(CPAccNavUpdate)
+ __OBJC_CLASS_PROTOCOLS_$_CPNowPlayingMode
+ __OBJC_CLASS_PROTOCOLS_$_CPNowPlayingModeSports
+ __OBJC_CLASS_PROTOCOLS_$_CPNowPlayingSportsClock
+ __OBJC_CLASS_PROTOCOLS_$_CPNowPlayingSportsEventStatus
+ __OBJC_CLASS_PROTOCOLS_$_CPNowPlayingSportsTeam
+ __OBJC_CLASS_PROTOCOLS_$_CPNowPlayingSportsTeamLogo
+ __OBJC_CLASS_PROTOCOLS_$_CPTemplateUISceneSettingsDiffAction
+ __OBJC_CLASS_RO_$_CPNowPlayingMode
+ __OBJC_CLASS_RO_$_CPNowPlayingModeSports
+ __OBJC_CLASS_RO_$_CPNowPlayingSportsClock
+ __OBJC_CLASS_RO_$_CPNowPlayingSportsEventStatus
+ __OBJC_CLASS_RO_$_CPNowPlayingSportsTeam
+ __OBJC_CLASS_RO_$_CPNowPlayingSportsTeamLogo
+ __OBJC_CLASS_RO_$_CPTemplateUISceneSettingsDiffAction
+ __OBJC_LABEL_PROTOCOL_$_CPTabBarTemplateProviding
+ __OBJC_METACLASS_RO_$_CPNowPlayingMode
+ __OBJC_METACLASS_RO_$_CPNowPlayingModeSports
+ __OBJC_METACLASS_RO_$_CPNowPlayingSportsClock
+ __OBJC_METACLASS_RO_$_CPNowPlayingSportsEventStatus
+ __OBJC_METACLASS_RO_$_CPNowPlayingSportsTeam
+ __OBJC_METACLASS_RO_$_CPNowPlayingSportsTeamLogo
+ __OBJC_METACLASS_RO_$_CPTemplateUISceneSettingsDiffAction
+ __OBJC_PROTOCOL_$_CPTabBarTemplateProviding
+ __OBJC_PROTOCOL_REFERENCE_$_CPTabBarTemplateProviding
+ ___41+[CPNowPlayingMode defaultNowPlayingMode]_block_invoke
+ ___54-[CPInterfaceController _completeSetupWithCompletion:]_block_invoke
+ ___54-[CPInterfaceController _completeSetupWithCompletion:]_block_invoke_2
+ ___62+[CPChargingStationConnector(CPAccNavUpdate) accNavParameters]_block_invoke
+ ___64-[CPTemplateApplicationScene initWithSession:connectionOptions:]_block_invoke_2
+ ___64-[CPTemplateApplicationScene initWithSession:connectionOptions:]_block_invoke_3
+ ___69+[CPChargingStationConnector(CPAccNavUpdate) accNavParametersIndexed]_block_invoke
+ ___72+[CPChargingStationConnector(CPAccNavUpdate) accNavParameterKeysIndexed]_block_invoke
+ ___block_descriptor_40_e8_32bs_e17_v16?0"NSValue"8ls32l8
+ ___block_descriptor_48_e8_32s40bs_e17_v16?0"NSValue"8ls32l8s40l8
+ __os_feature_enabled_impl
+ _maximumImageSize
+ _objc_msgSend$CGSizeValue
+ _objc_msgSend$_completeSetupWithCompletion:
+ _objc_msgSend$_setMaximumImageSize:
+ _objc_msgSend$_updateRouteGuidance:
+ _objc_msgSend$backgroundArtwork
+ _objc_msgSend$countsUp
+ _objc_msgSend$eventClock
+ _objc_msgSend$eventScore
+ _objc_msgSend$eventStatus
+ _objc_msgSend$eventStatusImage
+ _objc_msgSend$eventStatusText
+ _objc_msgSend$initWithInspectors:
+ _objc_msgSend$initials
+ _objc_msgSend$inspectors
+ _objc_msgSend$isEqualToGameStatus:
+ _objc_msgSend$isEqualToNowPlayingMode:
+ _objc_msgSend$isEqualToNowPlayingModeSports:
+ _objc_msgSend$isEqualToSportsClock:
+ _objc_msgSend$isEqualToSportsTeam:
+ _objc_msgSend$isEqualToTeamLogo:
+ _objc_msgSend$isFavorite
+ _objc_msgSend$isPaused
+ _objc_msgSend$leftTeam
+ _objc_msgSend$logo
+ _objc_msgSend$nowPlayingMode
+ _objc_msgSend$possessionIndicator
+ _objc_msgSend$preferredImageRowMaximumImageSizeWithReply:
+ _objc_msgSend$preferredListMaximumImageSizeWithReply:
+ _objc_msgSend$rightTeam
+ _objc_msgSend$sceneSettingsDiffAction
+ _objc_msgSend$setSceneSettingsDiffAction:
+ _objc_msgSend$showsSpinnerWhileEmpty
+ _objc_msgSend$substringToIndex:
+ _objc_msgSend$teamStandings
+ _objc_msgSend$timeValue
+ defaultNowPlayingMode.__defaultMode
+ defaultNowPlayingMode.onceToken
- +[CPAccNavUpdate _valueFromDictionary:forParamKey:]
- -[CPTemplateApplicationDashboardScene _performActionsForUIScene:withUpdatedFBSScene:settingsDiff:fromSettings:transitionContext:lifecycleActionType:]
- -[CPTemplateApplicationScene _performActionsForUIScene:withUpdatedFBSScene:settingsDiff:fromSettings:transitionContext:lifecycleActionType:]
- GCC_except_table106
- GCC_except_table30
- _OBJC_CLASS_$_UIImageSymbolConfiguration
- __OBJC_$_CLASS_METHODS_CPChargingStationConnector
- __OBJC_$_CLASS_PROP_LIST_CPChargingStationConnector
- __OBJC_$_INSTANCE_METHODS_CPChargingStationConnector
- __OBJC_$_PROP_LIST_CPChargingStationConnector
- __OBJC_CLASS_PROTOCOLS_$_CPChargingStationConnector
- ___51+[CPAccNavUpdate _valueFromDictionary:forParamKey:]_block_invoke
- ___96-[CPListTemplate listTemplateWithIdentifier:didSelectImageAtIndex:inImageRowItemWithIdentifier:]_block_invoke_2
- ___block_descriptor_56_e8_32s40s_e15_v32?0816^B24ls32l8s40l8
- _objc_msgSend$_valueFromDictionary:forParamKey:
- _objc_msgSend$configurationWithPointSize:
- _objc_msgSend$enumerateKeysAndObjectsUsingBlock:
- _objc_msgSend$imageWithSymbolConfiguration:
CStrings:
+ "%@ selected image row item %{public}@ image index %{public}@"
+ "%@ selected list item %{public}@"
+ "%@: Update now playing mode %@"
+ "&"
+ "0"
+ "@\"CPNowPlayingMode\""
+ "@\"CPNowPlayingSportsClock\""
+ "@\"CPNowPlayingSportsEventStatus\""
+ "@\"CPNowPlayingSportsTeam\""
+ "@\"CPNowPlayingSportsTeamLogo\""
+ "@\"CPTemplateUISceneSettingsDiffAction\""
+ "@28@0:8d16B24"
+ "@60@0:8@16@24@32@40@48B56"
+ "CGSizeValue"
+ "CPListImageRowItem setting maxImageSize (%{public}f,%{public}f)"
+ "CPListItem setting maxImageSize (%{public}f,%{public}f)"
+ "CPNowPlayingMode"
+ "CPNowPlayingModeSports"
+ "CPNowPlayingSportsClock"
+ "CPNowPlayingSportsEventStatus"
+ "CPNowPlayingSportsTeam"
+ "CPNowPlayingSportsTeamLogo"
+ "CPTabBarTemplateProviding"
+ "CPTemplateUISceneSettingsDiffAction"
+ "CarPlay"
+ "ChargingStationInfoList"
+ "ConnectorType"
+ "Sports"
+ "T@\"CPNowPlayingMode\",&,N,V_nowPlayingMode"
+ "T@\"CPNowPlayingMode\",R,N"
+ "T@\"CPNowPlayingSportsClock\",R,C,N,V_eventClock"
+ "T@\"CPNowPlayingSportsEventStatus\",R,N,V_eventStatus"
+ "T@\"CPNowPlayingSportsTeam\",R,N,V_leftTeam"
+ "T@\"CPNowPlayingSportsTeam\",R,N,V_rightTeam"
+ "T@\"CPNowPlayingSportsTeamLogo\",R,C,N,V_logo"
+ "T@\"CPTemplateUISceneSettingsDiffAction\",&,N,V_sceneSettingsDiffAction"
+ "T@\"NSArray\",&,N,V_inspectors"
+ "T@\"NSArray\",R,C,N,V_eventStatusText"
+ "T@\"NSString\",R,C,N,V_eventScore"
+ "T@\"NSString\",R,C,N,V_initials"
+ "T@\"NSString\",R,C,N,V_name"
+ "T@\"NSString\",R,C,N,V_teamStandings"
+ "T@\"UIImage\",R,C,N,V_backgroundArtwork"
+ "T@\"UIImage\",R,C,N,V_eventStatusImage"
+ "T@\"UIImage\",R,C,N,V_logo"
+ "T@\"UIImage\",R,C,N,V_possessionIndicator"
+ "TB,N,V_controlsAccNav"
+ "TB,N,V_showsSpinnerWhileEmpty"
+ "TB,R,N,GisFavorite,V_favorite"
+ "TB,R,N,GisPaused,V_paused"
+ "TB,R,N,V_countsUp"
+ "Td,R,N,V_timeValue"
+ "_backgroundArtwork"
+ "_completeSetupWithCompletion:"
+ "_controlsAccNav"
+ "_countsUp"
+ "_eventClock"
+ "_eventScore"
+ "_eventStatus"
+ "_eventStatusImage"
+ "_eventStatusText"
+ "_favorite"
+ "_initials"
+ "_inspectors"
+ "_leftTeam"
+ "_logo"
+ "_nowPlayingMode"
+ "_paused"
+ "_possessionIndicator"
+ "_rightTeam"
+ "_sceneSettingsDiffAction"
+ "_setMaximumImageSize:"
+ "_showsSpinnerWhileEmpty"
+ "_teamStandings"
+ "_timeValue"
+ "_updateRouteGuidance:"
+ "backgroundArtwork"
+ "controlsAccNav"
+ "countsUp"
+ "defaultNowPlayingMode"
+ "eventClock"
+ "eventScore"
+ "eventStatus"
+ "eventStatusImage"
+ "eventStatusText"
+ "favorite"
+ "hashValue"
+ "initWithElapsedTime:paused:"
+ "initWithEventStatusText:eventStatusImage:eventClock:"
+ "initWithInspectors:"
+ "initWithLeftTeam:rightTeam:eventStatus:backgroundArtwork:"
+ "initWithName:logo:teamStandings:eventScore:possessionIndicator:favorite:"
+ "initWithTeamInitials:"
+ "initWithTeamLogo:"
+ "initWithTimeRemaining:paused:"
+ "initials"
+ "inspectors"
+ "isEqualToGameStatus:"
+ "isEqualToNowPlayingMode:"
+ "isEqualToNowPlayingModeSports:"
+ "isEqualToSportsClock:"
+ "isEqualToSportsTeam:"
+ "isEqualToTeamLogo:"
+ "isFavorite"
+ "isPaused"
+ "kCPListTemplateShowsEmptySpinnerKey"
+ "kCPNowPlayingModeIdentifier"
+ "kCPNowPlayingModeSportsBackgroundArtworkKey"
+ "kCPNowPlayingModeSportsEventStatusClockKey"
+ "kCPNowPlayingModeSportsEventStatusKey"
+ "kCPNowPlayingModeSportsEventStatusTextKey"
+ "kCPNowPlayingModeSportsEventtatusImageKey"
+ "kCPNowPlayingModeSportsLeftTeamKey"
+ "kCPNowPlayingModeSportsRightTeamKey"
+ "kCPNowPlayingSportsTeamFavoriteKey"
+ "kCPNowPlayingSportsTeamIdentifierKey"
+ "kCPNowPlayingSportsTeamInitialsKey"
+ "kCPNowPlayingSportsTeamLogoImageKey"
+ "kCPNowPlayingSportsTeamLogoKey"
+ "kCPNowPlayingSportsTeamNameKey"
+ "kCPNowPlayingSportsTeamPossessionIndicatorKey"
+ "kCPNowPlayingSportsTeamScoreKey"
+ "kCPNowPlayingSportsTeamStandingKey"
+ "kCPNowPlayingSportsTimerCountsUpKey"
+ "kCPNowPlayingSportsTimerPausedKey"
+ "kCPNowPlayingSportsTimerTimeValueKey"
+ "kCPTemplateNowPlayingModeKey"
+ "leftTeam"
+ "logo"
+ "mutateRouteGuidance:"
+ "nowPlayingMode"
+ "paused"
+ "possessionIndicator"
+ "preferredImageRowMaximumImageSizeWithReply:"
+ "preferredListMaximumImageSizeWithReply:"
+ "rightTeam"
+ "sceneSettingsDiffAction"
+ "setControlsAccNav:"
+ "setInspectors:"
+ "setNowPlayingMode:"
+ "setSceneSettingsDiffAction:"
+ "setShowsSpinnerWhileEmpty:"
+ "showsSpinnerWhileEmpty"
+ "substringToIndex:"
+ "teamStandings"
+ "timeValue"
+ "v16@?0@\"NSValue\"8"
+ "v24@0:8@?<v@?@\"NSValue\">16"
- "%@ didSelectListItemWithIdentifier %@"
- "ChargingStationPower"
- "ChargingStationVoltage"
- "_valueFromDictionary:forParamKey:"
- "configurationWithPointSize:"
- "enumerateKeysAndObjectsUsingBlock:"
- "imageWithSymbolConfiguration:"
- "v32@?0@8@16^B24"
```
