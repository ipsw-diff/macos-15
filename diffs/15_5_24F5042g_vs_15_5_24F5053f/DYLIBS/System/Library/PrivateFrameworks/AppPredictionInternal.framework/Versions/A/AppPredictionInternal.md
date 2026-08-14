## AppPredictionInternal

> `/System/Library/PrivateFrameworks/AppPredictionInternal.framework/Versions/A/AppPredictionInternal`

```diff

-588.11.0.0.0
-  __TEXT.__text: 0x472e70
-  __TEXT.__auth_stubs: 0x2c10
-  __TEXT.__objc_methlist: 0x3793c
+588.12.0.0.0
+  __TEXT.__text: 0x476748
+  __TEXT.__auth_stubs: 0x2c70
+  __TEXT.__objc_methlist: 0x379f4
   __TEXT.__const: 0x27c2
-  __TEXT.__cstring: 0x56e92
-  __TEXT.__oslogstring: 0x37896
-  __TEXT.__gcc_except_tab: 0xec8c
+  __TEXT.__cstring: 0x57142
+  __TEXT.__oslogstring: 0x378f6
+  __TEXT.__gcc_except_tab: 0xec50
   __TEXT.__dlopen_cstrs: 0x10a
   __TEXT.__ustring: 0x90
-  __TEXT.__swift5_typeref: 0xd1c
+  __TEXT.__swift5_typeref: 0xe80
   __TEXT.__constg_swiftt: 0x14fc
   __TEXT.__swift5_reflstr: 0x69b
   __TEXT.__swift5_fieldmd: 0x988
   __TEXT.__swift5_proto: 0xc8
   __TEXT.__swift5_types: 0x118
   __TEXT.__swift5_assocty: 0x1c8
-  __TEXT.__swift5_capture: 0x3f8
+  __TEXT.__swift5_capture: 0x4e8
   __TEXT.__swift5_protos: 0x1c
   __TEXT.__swift5_builtin: 0x64
   __TEXT.__swift_as_entry: 0xc0
   __TEXT.__swift_as_ret: 0xac
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0xd708
+  __TEXT.__unwind_info: 0xd7c8
   __TEXT.__eh_frame: 0x1a74
   __TEXT.__objc_classname: 0x89d2
-  __TEXT.__objc_methname: 0xaa5df
-  __TEXT.__objc_methtype: 0x1912a
+  __TEXT.__objc_methname: 0xaa6f8
+  __TEXT.__objc_methtype: 0x19152
   __TEXT.__objc_stubs: 0x4a900
-  __DATA_CONST.__got: 0x3390
-  __DATA_CONST.__const: 0x4258
-  __DATA_CONST.__objc_classlist: 0x1e98
+  __DATA_CONST.__got: 0x33a0
+  __DATA_CONST.__const: 0x4260
+  __DATA_CONST.__objc_classlist: 0x1ea0
   __DATA_CONST.__objc_catlist: 0x120
   __DATA_CONST.__objc_protolist: 0x490
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1b200
+  __DATA_CONST.__objc_selrefs: 0x1b248
   __DATA_CONST.__objc_protorefs: 0xa8
   __DATA_CONST.__objc_superrefs: 0x14b0
   __DATA_CONST.__objc_arraydata: 0x1360
-  __AUTH_CONST.__auth_got: 0x1620
-  __AUTH_CONST.__const: 0xf4b0
-  __AUTH_CONST.__cfstring: 0x395c0
-  __AUTH_CONST.__objc_const: 0x7ffc0
+  __AUTH_CONST.__auth_got: 0x1650
+  __AUTH_CONST.__const: 0xf7f0
+  __AUTH_CONST.__cfstring: 0x395a0
+  __AUTH_CONST.__objc_const: 0x80168
   __AUTH_CONST.__objc_intobj: 0x33c0
   __AUTH_CONST.__objc_arrayobj: 0x1068
   __AUTH_CONST.__objc_dictobj: 0x1b8
   __AUTH_CONST.__objc_floatobj: 0x30
   __AUTH_CONST.__objc_doubleobj: 0x70
-  __AUTH.__objc_data: 0x13560
-  __AUTH.__data: 0x1dd8
+  __AUTH.__objc_data: 0x135d0
+  __AUTH.__data: 0x1df8
   __DATA.__objc_ivar: 0x49b0
-  __DATA.__data: 0x3cf0
-  __DATA.__bss: 0x2478
-  __DATA.__common: 0xa8
+  __DATA.__data: 0x3d40
+  __DATA.__bss: 0x2488
+  __DATA.__common: 0xc0
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 24291
-  Symbols:   45569
-  CStrings:  32343
+  Functions: 24381
+  Symbols:   45588
+  CStrings:  32369
 
Symbols:
+ -[ATXNotificationAndSuggestionDatabase updateNotificationsWithNextAppLaunchDate:receivedDateAfter:forBundleId:]
+ -[ATXNotificationAndSuggestionDatastore updateNotificationsWithNextAppLaunchDate:receivedDateAfter:forBundleId:]
+ OBJC_IVAR_$_ATXNotificationTelemetryLogger._notificationNextAppLaunchRecorder
+ _OBJC_CLASS_$_ATXNotificationNextAppLaunchRecorder
+ _OBJC_METACLASS_$_ATXNotificationNextAppLaunchRecorder
+ __111-[ATXNotificationAndSuggestionDatabase updateNotificationsWithNextAppLaunchDate:receivedDateAfter:forBundleId:]_block_invoke
+ __DATA_ATXNotificationNextAppLaunchRecorder
+ __INSTANCE_METHODS_ATXNotificationNextAppLaunchRecorder
+ __IVARS_ATXNotificationNextAppLaunchRecorder
+ __METACLASS_DATA_ATXNotificationNextAppLaunchRecorder
+ __PROPERTIES_ATXNotificationNextAppLaunchRecorder
+ ___111-[ATXNotificationAndSuggestionDatabase updateNotificationsWithNextAppLaunchDate:receivedDateAfter:forBundleId:]_block_invoke
+ ___111-[ATXNotificationAndSuggestionDatabase updateNotificationsWithNextAppLaunchDate:receivedDateAfter:forBundleId:]_block_invoke_2
+ _keypath_get_selector_appLaunchPublisherProvider
+ _objc_msgSend$initWithDefaults:dataStore:defaultsKeyPrefix:appLaunchPublisherProvider:installedAppsProvider:
+ _objc_msgSend$updateNotificationsWithNextAppLaunch
+ _objc_msgSend$updateNotificationsWithNextAppLaunchDate:receivedDateAfter:forBundleId:
+ _swift_getObjCClassFromMetadata
+ _swift_projectBox
+ _symbolic SDySS_____G 10Foundation4DateV
+ _symbolic SDySS_____Gz_Xx 10Foundation4DateV
+ _symbolic ShySSGIego_
+ _symbolic ShySSGIegr_
+ _symbolic So36ATXNotificationNextAppLaunchRecorderC
+ _symbolic So5NSSetCIeyBa_
+ _symbolic So6NSDateCSo12BPSPublisherCySo12BMStoreEventCySo12BMAppInFocusCGGIeyBya_
+ _symbolic _____So12BPSPublisherCySo12BMStoreEventCySo12BMAppInFocusCGGIegno_ 10Foundation4DateV
+ _symbolic _____So12BPSPublisherCySo12BMStoreEventCySo12BMAppInFocusCGGIegnr_ 10Foundation4DateV
+ _symbolic ______pSg s5ErrorP
+ _symbolic _____ySS_____G s18_DictionaryStorageC 10Foundation4DateV
+ _symbolic _____z_Xx 10Foundation4DateV
- -[ATXNotificationAndSuggestionDatabase updateNotificationWithAppLaunchTimestamp:bundleId:startTimestamp:]
- -[ATXNotificationAndSuggestionDatastore _appLaunchPublisher]
- -[ATXNotificationAndSuggestionDatastore updateNotificationsWithNextAppLaunchTimestamp:bundleId:startTimestamp:]
- OBJC_IVAR_$_ATXNotificationAndSuggestionDatastore._appLaunchPublisher
- __105-[ATXNotificationAndSuggestionDatabase updateNotificationWithAppLaunchTimestamp:bundleId:startTimestamp:]_block_invoke
- ___105-[ATXNotificationAndSuggestionDatabase updateNotificationWithAppLaunchTimestamp:bundleId:startTimestamp:]_block_invoke
- ___105-[ATXNotificationAndSuggestionDatabase updateNotificationWithAppLaunchTimestamp:bundleId:startTimestamp:]_block_invoke_2
- ___block_descriptor_72_e8_32s40s48s56s64r_e22_v16?0"BMStoreEvent"8l
- _kATXNotificationAndSuggestionAppLaunchTimestampDefaultsKey
- _objc_msgSend$_appLaunchPublisher
- _objc_msgSend$updateNotificationWithAppLaunchTimestamp:bundleId:startTimestamp:
- _objc_msgSend$updateNotificationsWithNextAppLaunchTimestamp:bundleId:startTimestamp:
CStrings:
+ "$__lazy_storage_$_appLaunchTimestampKey"
+ "-AppLaunchTimestamp"
+ ":receivedDateAfter"
+ "@\"ATXNotificationNextAppLaunchRecorder\""
+ "@\"NSSet\"8@?0"
+ "@56@0:8@16@24@32@?40@?48"
+ "ATXNotificationNextAppLaunchRecorder"
+ "AppPredictionInternal_Private.NotificationNextAppLaunchRecorder"
+ "NotificationNextAppLaunchRecorder"
+ "NotificationNextAppLaunchRecorder.queue"
+ "NotificationNextAppLaunchRecorder: Could not fetch app launch stream, error: %s"
+ "NotificationNextAppLaunchRecorder: startDate: %s"
+ "T@\"ATXNotificationAndSuggestionDatastore\",N,R,VdataStore"
+ "T@\"NSString\",N,C"
+ "T@\"NSUserDefaults\",N,R,Vdefaults"
+ "T@\"OS_dispatch_queue\",N,&"
+ "T@?,N,C"
+ "T@?,N,R"
+ "UPDATE notifications SET nextAppLaunchTimestamp = :nextAppLaunchTimestamp WHERE bundleId = :bundleId AND receiveTimestamp >= :receivedDateAfter AND receiveTimestamp < :nextAppLaunchTimestamp"
+ "_notificationNextAppLaunchRecorder"
+ "appLaunchPublisherProvider"
+ "appLaunchTimestampKey"
+ "defaultsKeyPrefix"
+ "initWithDefaults:dataStore:defaultsKeyPrefix:appLaunchPublisherProvider:installedAppsProvider:"
+ "installedAppsProvider"
+ "resetDefaults"
+ "setAppLaunchPublisherProvider:"
+ "setAppLaunchTimestampKey:"
+ "setQueue:"
+ "updateNotificationsWithNextAppLaunch"
+ "updateNotificationsWithNextAppLaunchDate:receivedDateAfter:forBundleId:"
- "ATXNotificationAndSuggestionDatastoreAppLaunchTimestamp"
- "UPDATE notifications SET nextAppLaunchTimestamp = :nextAppLaunchTimestamp WHERE bundleId = :bundleId AND receiveTimestamp > :startTimestamp AND receiveTimestamp < :nextAppLaunchTimestamp"
- "[%@] Could not fetch app launch stream with error: %@"
- "updateNotificationWithAppLaunchTimestamp:bundleId:startTimestamp:"
- "updateNotificationsWithNextAppLaunchTimestamp:bundleId:startTimestamp:"
```
