## SPOwner

> `/System/Library/PrivateFrameworks/SPOwner.framework/Versions/A/SPOwner`

```diff

-396.25.2.11.11
-  __TEXT.__text: 0x7cb28
+396.25.2.11.14
+  __TEXT.__text: 0x7c164
   __TEXT.__auth_stubs: 0xb20
-  __TEXT.__objc_methlist: 0xb33c
-  __TEXT.__cstring: 0x6637
+  __TEXT.__objc_methlist: 0xaf1c
+  __TEXT.__cstring: 0x6517
   __TEXT.__const: 0x440
-  __TEXT.__gcc_except_tab: 0x1b3c
-  __TEXT.__oslogstring: 0x75c8
+  __TEXT.__gcc_except_tab: 0x1b24
+  __TEXT.__oslogstring: 0x7688
   __TEXT.__swift5_typeref: 0x124
   __TEXT.__swift5_fieldmd: 0xfc
   __TEXT.__constg_swiftt: 0xfc

   __TEXT.__swift_as_entry: 0x1c
   __TEXT.__swift5_capture: 0x50
   __TEXT.__swift_as_ret: 0x18
-  __TEXT.__unwind_info: 0x2380
+  __TEXT.__unwind_info: 0x2320
   __TEXT.__eh_frame: 0x278
-  __TEXT.__objc_classname: 0x1350
-  __TEXT.__objc_methname: 0x12737
-  __TEXT.__objc_methtype: 0x3938
-  __TEXT.__objc_stubs: 0xa8c0
-  __DATA_CONST.__got: 0x5b8
-  __DATA_CONST.__const: 0x870
-  __DATA_CONST.__objc_classlist: 0x430
-  __DATA_CONST.__objc_protolist: 0x1d8
+  __TEXT.__objc_classname: 0x12ab
+  __TEXT.__objc_methname: 0x12788
+  __TEXT.__objc_methtype: 0x38ba
+  __TEXT.__objc_stubs: 0xa920
+  __DATA_CONST.__got: 0x5a8
+  __DATA_CONST.__const: 0x860
+  __DATA_CONST.__objc_classlist: 0x410
+  __DATA_CONST.__objc_protolist: 0x1c0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x39d8
-  __DATA_CONST.__objc_protorefs: 0xd8
-  __DATA_CONST.__objc_superrefs: 0x360
+  __DATA_CONST.__objc_protorefs: 0xd0
+  __DATA_CONST.__objc_superrefs: 0x340
   __DATA_CONST.__objc_arraydata: 0x28
   __AUTH_CONST.__auth_got: 0x5a0
-  __AUTH_CONST.__const: 0x2120
+  __AUTH_CONST.__const: 0x20f0
   __AUTH_CONST.__cfstring: 0x5b00
-  __AUTH_CONST.__objc_const: 0x135c8
+  __AUTH_CONST.__objc_const: 0x12ce8
   __AUTH_CONST.__objc_intobj: 0xd8
   __AUTH_CONST.__objc_arrayobj: 0x30
-  __AUTH.__objc_data: 0x1af0
+  __AUTH.__objc_data: 0x19b0
   __AUTH.__data: 0x180
-  __DATA.__objc_ivar: 0xe38
-  __DATA.__data: 0x16e8
-  __DATA.__bss: 0x910
+  __DATA.__objc_ivar: 0xdd0
+  __DATA.__data: 0x15c8
+  __DATA.__bss: 0x900
   __DATA.__common: 0x20
   __DATA_DIRTY.__objc_data: 0xf00
   __DATA_DIRTY.__bss: 0x40

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 4150
-  Symbols:   8515
-  CStrings:  4713
+  Functions: 4067
+  Symbols:   8357
+  CStrings:  4701
 
Symbols:
+ +[SPHandle handleWithString:formattedName:]
+ -[SPHandle formattedName]
+ -[SPHandle initWithType:destination:formattedName:]
+ -[SPHandle setFormattedName:]
+ -[SPInternalSimpleBeacon lockedTimestamp]
+ -[SPInternalSimpleBeacon rawDeviceModel]
+ -[SPInternalSimpleBeacon setLockedTimestamp:]
+ -[SPInternalSimpleBeacon setRawDeviceModel:]
+ -[SPInternalSimpleBeacon setWipedTimestamp:]
+ -[SPInternalSimpleBeacon wipedTimestamp]
+ GCC_except_table125
+ GCC_except_table140
+ GCC_except_table142
+ GCC_except_table144
+ OBJC_IVAR_$_SPHandle._formattedName
+ OBJC_IVAR_$_SPInternalSimpleBeacon._lockedTimestamp
+ OBJC_IVAR_$_SPInternalSimpleBeacon._rawDeviceModel
+ OBJC_IVAR_$_SPInternalSimpleBeacon._wipedTimestamp
+ ___block_descriptor_40_e8_32s_e35_B16?0"NSOrderedCollectionChange"8l
+ ___block_descriptor_48_e8_32s40s_e30_v24?0"SPBeacon"8"NSError"16l
+ ___block_descriptor_80_e8_32s40s48s56s64s72s_e51_v24?0"NSOrderedCollectionDifference"8"NSError"16l
+ ___block_descriptor_80_e8_32s40s48s56s64s72s_e5_v8?0l
+ ___copy_helper_block_e8_32s40s48s56s64s72s
+ ___destroy_helper_block_e8_32s40s48s56s64s72s
+ _objc_msgSend$fm_filter:
+ _objc_msgSend$formattedName
+ _objc_msgSend$initWithType:destination:formattedName:
+ _objc_msgSend$lockedTimestamp
+ _objc_msgSend$rawDeviceModel
+ _objc_msgSend$setFormattedName:
+ _objc_msgSend$setLockedTimestamp:
+ _objc_msgSend$setRawDeviceModel:
+ _objc_msgSend$setWipedTimestamp:
+ _objc_msgSend$wipedTimestamp
- +[SPIntentSessionContext deviceListUseCase]
- +[SPIntentSessionContext itemListUseCase]
- +[SPIntentSessionContext supportsSecureCoding]
- +[SPSimpleBeaconContext unifiedBeaconContext]
- +[SPUnifiedSupportSession beaconsChanges:]
- +[SPUnifiedSupportSession unifiedBeacons:]
- -[SPIntentSession .cxx_destruct]
- -[SPIntentSession context]
- -[SPIntentSession init]
- -[SPIntentSession proxy]
- -[SPIntentSession remoteInterface]
- -[SPIntentSession serviceDescription]
- -[SPIntentSession session]
- -[SPIntentSession setContext:]
- -[SPIntentSession setProxy:]
- -[SPIntentSession setServiceDescription:]
- -[SPIntentSession setSession:]
- -[SPIntentSession startSessionWithContext:completion:]
- -[SPIntentSession stopSessionWithCompletion:]
- -[SPIntentSessionContext .cxx_destruct]
- -[SPIntentSessionContext copyWithZone:]
- -[SPIntentSessionContext encodeWithCoder:]
- -[SPIntentSessionContext identifier]
- -[SPIntentSessionContext initWithCoder:]
- -[SPIntentSessionContext initWithUseCase:]
- -[SPIntentSessionContext setIdentifier:]
- -[SPIntentSessionContext setUseCase:]
- -[SPIntentSessionContext useCase]
- -[SPOwnerInterface unifiedSupportSession]
- -[SPUnifiedBeacon .cxx_destruct]
- -[SPUnifiedBeacon accessoryProductInfo]
- -[SPUnifiedBeacon batteryLevel]
- -[SPUnifiedBeacon batteryPercentage]
- -[SPUnifiedBeacon connected]
- -[SPUnifiedBeacon deviceClass]
- -[SPUnifiedBeacon deviceColor]
- -[SPUnifiedBeacon deviceDisplayName]
- -[SPUnifiedBeacon deviceModel]
- -[SPUnifiedBeacon groupIdentifier]
- -[SPUnifiedBeacon identifier]
- -[SPUnifiedBeacon initWithInternalSimpleBeacon:]
- -[SPUnifiedBeacon isMine]
- -[SPUnifiedBeacon lostModeInfo]
- -[SPUnifiedBeacon lowPowerMode]
- -[SPUnifiedBeacon multipartStatus]
- -[SPUnifiedBeacon name]
- -[SPUnifiedBeacon online]
- -[SPUnifiedBeacon owner]
- -[SPUnifiedBeacon partIdentifier]
- -[SPUnifiedBeacon role]
- -[SPUnifiedBeacon setAccessoryProductInfo:]
- -[SPUnifiedBeacon setBatteryLevel:]
- -[SPUnifiedBeacon setBatteryPercentage:]
- -[SPUnifiedBeacon setConnected:]
- -[SPUnifiedBeacon setDeviceClass:]
- -[SPUnifiedBeacon setDeviceColor:]
- -[SPUnifiedBeacon setDeviceDisplayName:]
- -[SPUnifiedBeacon setDeviceModel:]
- -[SPUnifiedBeacon setGroupIdentifier:]
- -[SPUnifiedBeacon setIdentifier:]
- -[SPUnifiedBeacon setIsMine:]
- -[SPUnifiedBeacon setLostModeInfo:]
- -[SPUnifiedBeacon setLowPowerMode:]
- -[SPUnifiedBeacon setMultipartStatus:]
- -[SPUnifiedBeacon setName:]
- -[SPUnifiedBeacon setOnline:]
- -[SPUnifiedBeacon setOwner:]
- -[SPUnifiedBeacon setPartIdentifier:]
- -[SPUnifiedBeacon setRole:]
- -[SPUnifiedBeacon setTaskInformation:]
- -[SPUnifiedBeacon setThisDevice:]
- -[SPUnifiedBeacon setType:]
- -[SPUnifiedBeacon taskInformation]
- -[SPUnifiedBeacon thisDevice]
- -[SPUnifiedBeacon type]
- -[SPUnifiedSupportSession .cxx_destruct]
- -[SPUnifiedSupportSession init]
- -[SPUnifiedSupportSession queue]
- -[SPUnifiedSupportSession registerSimpleBeaconInterfaceWithContext:collectionDifference:completion:]
- -[SPUnifiedSupportSession setQueue:]
- -[SPUnifiedSupportSession setSimpleBeaconUpdateInterface:]
- -[SPUnifiedSupportSession simpleBeaconUpdateInterface]
- -[SPUnifiedSupportSession startUpdatingBeaconsWithContext:collectionDifference:completion:]
- -[SPUnifiedSupportSession stopUpdatingBeaconsWithCompletion:]
- -[SPUnifiedSupportSession unifiedBeacons]
- GCC_except_table104
- GCC_except_table145
- GCC_except_table146
- GCC_except_table147
- LogCategory_UnifiedSupport
- LogCategory_UnifiedSupport.log
- LogCategory_UnifiedSupport.onceToken
- OBJC_IVAR_$_SPIntentSession._context
- OBJC_IVAR_$_SPIntentSession._proxy
- OBJC_IVAR_$_SPIntentSession._serviceDescription
- OBJC_IVAR_$_SPIntentSession._session
- OBJC_IVAR_$_SPIntentSessionContext._identifier
- OBJC_IVAR_$_SPIntentSessionContext._useCase
- OBJC_IVAR_$_SPUnifiedBeacon._accessoryProductInfo
- OBJC_IVAR_$_SPUnifiedBeacon._batteryLevel
- OBJC_IVAR_$_SPUnifiedBeacon._batteryPercentage
- OBJC_IVAR_$_SPUnifiedBeacon._connected
- OBJC_IVAR_$_SPUnifiedBeacon._deviceClass
- OBJC_IVAR_$_SPUnifiedBeacon._deviceColor
- OBJC_IVAR_$_SPUnifiedBeacon._deviceDisplayName
- OBJC_IVAR_$_SPUnifiedBeacon._deviceModel
- OBJC_IVAR_$_SPUnifiedBeacon._groupIdentifier
- OBJC_IVAR_$_SPUnifiedBeacon._identifier
- OBJC_IVAR_$_SPUnifiedBeacon._isMine
- OBJC_IVAR_$_SPUnifiedBeacon._lostModeInfo
- OBJC_IVAR_$_SPUnifiedBeacon._lowPowerMode
- OBJC_IVAR_$_SPUnifiedBeacon._multipartStatus
- OBJC_IVAR_$_SPUnifiedBeacon._name
- OBJC_IVAR_$_SPUnifiedBeacon._online
- OBJC_IVAR_$_SPUnifiedBeacon._owner
- OBJC_IVAR_$_SPUnifiedBeacon._partIdentifier
- OBJC_IVAR_$_SPUnifiedBeacon._role
- OBJC_IVAR_$_SPUnifiedBeacon._taskInformation
- OBJC_IVAR_$_SPUnifiedBeacon._thisDevice
- OBJC_IVAR_$_SPUnifiedBeacon._type
- OBJC_IVAR_$_SPUnifiedSupportSession._queue
- OBJC_IVAR_$_SPUnifiedSupportSession._simpleBeaconUpdateInterface
- _LogCategory_UnifiedSupport
- _OBJC_CLASS_$_SPIntentSession
- _OBJC_CLASS_$_SPIntentSessionContext
- _OBJC_CLASS_$_SPUnifiedBeacon
- _OBJC_CLASS_$_SPUnifiedSupportSession
- _OBJC_METACLASS_$_SPIntentSession
- _OBJC_METACLASS_$_SPIntentSessionContext
- _OBJC_METACLASS_$_SPUnifiedBeacon
- _OBJC_METACLASS_$_SPUnifiedSupportSession
- _SPIntentSessionErrorDomain
- _SPUnifiedSupportErrorDomain
- __OBJC_$_CLASS_METHODS_SPIntentSessionContext
- __OBJC_$_CLASS_METHODS_SPUnifiedSupportSession
- __OBJC_$_CLASS_PROP_LIST_SPIntentSessionContext
- __OBJC_$_INSTANCE_METHODS_SPIntentSession
- __OBJC_$_INSTANCE_METHODS_SPIntentSessionContext
- __OBJC_$_INSTANCE_METHODS_SPUnifiedBeacon
- __OBJC_$_INSTANCE_METHODS_SPUnifiedSupportSession
- __OBJC_$_INSTANCE_VARIABLES_SPIntentSession
- __OBJC_$_INSTANCE_VARIABLES_SPIntentSessionContext
- __OBJC_$_INSTANCE_VARIABLES_SPUnifiedBeacon
- __OBJC_$_INSTANCE_VARIABLES_SPUnifiedSupportSession
- __OBJC_$_PROP_LIST_SPIntentSession
- __OBJC_$_PROP_LIST_SPIntentSessionContext
- __OBJC_$_PROP_LIST_SPUnifiedBeacon
- __OBJC_$_PROP_LIST_SPUnifiedSupportProtocol
- __OBJC_$_PROP_LIST_SPUnifiedSupportSession
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_SPIntentSessionProtocol
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_SPUnifiedSupportProtocol
- __OBJC_$_PROTOCOL_METHOD_TYPES_SPIntentSessionProtocol
- __OBJC_$_PROTOCOL_METHOD_TYPES_SPUnifiedSupportProtocol
- __OBJC_$_PROTOCOL_REFS_SPIntentSessionClientXPCProtocol
- __OBJC_$_PROTOCOL_REFS_SPIntentSessionProtocol
- __OBJC_$_PROTOCOL_REFS_SPUnifiedSupportProtocol
- __OBJC_CLASS_PROTOCOLS_$_SPIntentSession
- __OBJC_CLASS_PROTOCOLS_$_SPIntentSessionContext
- __OBJC_CLASS_PROTOCOLS_$_SPUnifiedSupportSession
- __OBJC_CLASS_RO_$_SPIntentSession
- __OBJC_CLASS_RO_$_SPIntentSessionContext
- __OBJC_CLASS_RO_$_SPUnifiedBeacon
- __OBJC_CLASS_RO_$_SPUnifiedSupportSession
- __OBJC_LABEL_PROTOCOL_$_SPIntentSessionClientXPCProtocol
- __OBJC_LABEL_PROTOCOL_$_SPIntentSessionProtocol
- __OBJC_LABEL_PROTOCOL_$_SPUnifiedSupportProtocol
- __OBJC_METACLASS_RO_$_SPIntentSession
- __OBJC_METACLASS_RO_$_SPIntentSessionContext
- __OBJC_METACLASS_RO_$_SPUnifiedBeacon
- __OBJC_METACLASS_RO_$_SPUnifiedSupportSession
- __OBJC_PROTOCOL_$_SPIntentSessionClientXPCProtocol
- __OBJC_PROTOCOL_$_SPIntentSessionProtocol
- __OBJC_PROTOCOL_$_SPUnifiedSupportProtocol
- __OBJC_PROTOCOL_REFERENCE_$_SPIntentSessionProtocol
- ___100-[SPUnifiedSupportSession registerSimpleBeaconInterfaceWithContext:collectionDifference:completion:]_block_invoke
- ___42+[SPUnifiedSupportSession beaconsChanges:]_block_invoke
- ___42+[SPUnifiedSupportSession unifiedBeacons:]_block_invoke
- ___61-[SPUnifiedSupportSession stopUpdatingBeaconsWithCompletion:]_block_invoke
- ___91-[SPUnifiedSupportSession startUpdatingBeaconsWithContext:collectionDifference:completion:]_block_invoke
- ___LogCategory_UnifiedSupport_block_invoke
- ___block_descriptor_48_e8_32s40bs_e18_v16?0"FMFuture"8l
- ___block_descriptor_48_e8_32s40w_e30_v24?0"SPBeacon"8"NSError"16l
- ___block_descriptor_88_e8_32s40s48s56s64s72s80s_e5_v8?0l
- ___copy_helper_block_e8_32s40s48s56s64s72s80s
- ___destroy_helper_block_e8_32s40s48s56s64s72s80s
- _objc_msgSend$initWithUseCase:
- _objc_msgSend$setUseCase:
- _objc_msgSend$simpleBeacons
- _objc_msgSend$startSessionWithContext:completion:
- _objc_msgSend$stopSessionWithContext:completion:
- _objc_msgSend$unifiedBeacons:
- _objc_msgSend$useCase
CStrings:
+ "<%@: %p %ld:%@ %@>"
+ "B16@?0@\"NSOrderedCollectionChange\"8"
+ "SPOwnerSession: registered for task info updates on this beacon: %@, subscribed: %i, error %@"
+ "SPOwnerSession: stopped all task info updates on this beacon: %@, stopped: %i, error %@"
+ "SPOwnerSession: task info updated beacon: %@, changes: %lu, error %@"
+ "T@\"NSDate\",C,N,V_lockedTimestamp"
+ "T@\"NSDate\",C,N,V_wipedTimestamp"
+ "T@\"NSString\",C,N,V_formattedName"
+ "T@\"NSString\",C,N,V_rawDeviceModel"
+ "_formattedName"
+ "_lockedTimestamp"
+ "_rawDeviceModel"
+ "_wipedTimestamp"
+ "fm_filter:"
+ "formattedName"
+ "handleWithString:formattedName:"
+ "initWithType:destination:formattedName:"
+ "lockedTimestamp"
+ "rawDeviceModel"
+ "setFormattedName:"
+ "setLockedTimestamp:"
+ "setRawDeviceModel:"
+ "setWipedTimestamp:"
+ "wipedTimestamp"
- "-[SPUnifiedSupportSession startUpdatingBeaconsWithContext:collectionDifference:completion:]"
- "-[SPUnifiedSupportSession stopUpdatingBeaconsWithCompletion:]"
- "<%@: %p %ld:%@>"
- "@\"<SPIntentSessionProtocol>\""
- "@\"NSArray\"16@0:8"
- "@\"SPIntentSessionContext\""
- "SPIntentSession"
- "SPIntentSessionClientXPCProtocol"
- "SPIntentSessionContext"
- "SPIntentSessionProtocol"
- "SPOwnerSession: notifiedBeaconsChangedBlock: %@"
- "SPUnifiedBeacon"
- "SPUnifiedSupportProtocol"
- "SPUnifiedSupportSession"
- "T@\"<SPIntentSessionProtocol>\",&,N,V_proxy"
- "T@\"SPIntentSessionContext\",&,N,V_context"
- "TQ,N,V_useCase"
- "_useCase"
- "com.apple.SPOwner.SPUnifiedSupport.ErrorDomain"
- "com.apple.SPOwner.SPUnifiedSupportSession"
- "com.apple.icloud.searchpartyd.SPIntentSession.ErrorDomain"
- "com.apple.icloud.searchpartyd.intentsession"
- "deviceListUseCase"
- "initWithUseCase:"
- "itemListUseCase"
- "setUseCase:"
- "startSessionWithContext:completion:"
- "stopSessionWithCompletion:"
- "stopSessionWithContext:completion:"
- "unifiedBeaconContext"
- "unifiedBeacons"
- "unifiedSupport"
- "unifiedSupportSession"
- "useCase"
- "v16@?0@\"FMFuture\"8"
- "v32@0:8@\"SPIntentSessionContext\"16@?<v@?@\"NSError\">24"
```
