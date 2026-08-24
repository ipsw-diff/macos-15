## seserviced

> `/usr/libexec/seserviced`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_data`

```diff

-55.4.0.0.0
-  __TEXT.__text: 0x107a30
-  __TEXT.__auth_stubs: 0x2510
-  __TEXT.__objc_stubs: 0x47a0
-  __TEXT.__objc_methlist: 0x2720
-  __TEXT.__const: 0x4068
+56.2.0.0.0
+  __TEXT.__text: 0x10baf8
+  __TEXT.__auth_stubs: 0x2530
+  __TEXT.__objc_stubs: 0x47c0
+  __TEXT.__objc_methlist: 0x2728
+  __TEXT.__const: 0x47d8
   __TEXT.__gcc_except_tab: 0x1890
-  __TEXT.__objc_methname: 0x6e97
-  __TEXT.__oslogstring: 0x50e2
-  __TEXT.__cstring: 0xc39e
+  __TEXT.__objc_methname: 0x6fd3
+  __TEXT.__oslogstring: 0x52b2
+  __TEXT.__cstring: 0xc6ad
   __TEXT.__objc_classname: 0x6b0
   __TEXT.__objc_methtype: 0x2c84
-  __TEXT.__constg_swiftt: 0x1114
-  __TEXT.__swift5_typeref: 0x128b
+  __TEXT.__constg_swiftt: 0x12ec
+  __TEXT.__swift5_typeref: 0x135a
   __TEXT.__swift5_builtin: 0x154
-  __TEXT.__swift5_reflstr: 0xee0
-  __TEXT.__swift5_fieldmd: 0x13dc
-  __TEXT.__swift5_assocty: 0x198
-  __TEXT.__swift5_proto: 0x2a8
-  __TEXT.__swift5_types: 0x170
-  __TEXT.__swift5_capture: 0x5c4
+  __TEXT.__swift5_reflstr: 0x1210
+  __TEXT.__swift5_fieldmd: 0x161c
+  __TEXT.__swift5_assocty: 0x1e0
+  __TEXT.__swift5_proto: 0x2e8
+  __TEXT.__swift5_types: 0x194
+  __TEXT.__swift5_capture: 0x604
   __TEXT.__swift5_mpenum: 0x5c
   __TEXT.__swift5_protos: 0x14
   __TEXT.__swift_as_entry: 0xf8
   __TEXT.__swift_as_ret: 0x144
-  __TEXT.__unwind_info: 0x2b80
-  __TEXT.__eh_frame: 0x4e70
-  __DATA_CONST.__auth_got: 0x1298
-  __DATA_CONST.__got: 0x7b8
-  __DATA_CONST.__auth_ptr: 0x588
-  __DATA_CONST.__const: 0x6188
-  __DATA_CONST.__cfstring: 0x4d40
-  __DATA_CONST.__objc_classlist: 0x268
+  __TEXT.__unwind_info: 0x2c78
+  __TEXT.__eh_frame: 0x4ec0
+  __DATA_CONST.__auth_got: 0x12a8
+  __DATA_CONST.__got: 0x7d8
+  __DATA_CONST.__auth_ptr: 0x5b8
+  __DATA_CONST.__const: 0x6640
+  __DATA_CONST.__cfstring: 0x4dc0
+  __DATA_CONST.__objc_classlist: 0x278
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x128
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arrayobj: 0x78
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA_CONST.__objc_intobj: 0x198
-  __DATA.__objc_const: 0x5cf8
-  __DATA.__objc_selrefs: 0x1a78
+  __DATA.__objc_const: 0x5ec8
+  __DATA.__objc_selrefs: 0x1ae0
   __DATA.__objc_ivar: 0x2c0
   __DATA.__objc_data: 0x1d80
-  __DATA.__data: 0x2ac8
-  __DATA.__bss: 0x4cd0
+  __DATA.__data: 0x2b80
+  __DATA.__bss: 0x54d0
   __DATA.__common: 0x152
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth

   - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/PrivateFrameworks/AtomicsInternal.framework/Versions/A/AtomicsInternal
   - /System/Library/PrivateFrameworks/AuthKit.framework/Versions/A/AuthKit
+  - /System/Library/PrivateFrameworks/BackgroundSystemTasks.framework/Versions/A/BackgroundSystemTasks
   - /System/Library/PrivateFrameworks/CBORLibrary.framework/Versions/A/CBORLibrary
   - /System/Library/PrivateFrameworks/CoreAnalytics.framework/Versions/A/CoreAnalytics
   - /System/Library/PrivateFrameworks/CryptoKitPrivate.framework/Versions/A/CryptoKitPrivate

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 3418
-  Symbols:   991
-  CStrings:  3134
+  Functions: 3517
+  Symbols:   998
+  CStrings:  3179
 
Symbols:
+ _$s8Dispatch0A4TimeVMa
+ _$s8Dispatch0A4TimeVMn
+ _$sSo17OS_dispatch_queueC8DispatchE20AutoreleaseFrequencyO7inherityA2EmFWC
+ _$sSuN
+ _OBJC_CLASS_$_BGRepeatingSystemTaskRequest
+ _OBJC_CLASS_$_BGSystemTaskScheduler
+ _swift_initStaticObject
CStrings:
+ "%s task %s expired"
+ "%s task %s is already scheduled"
+ "%s task %s launched"
+ "Error %@ while scheduling general analytics task for"
+ "Failed to register task with identifier %s"
+ "Failed to submit task requrest with identifier %s"
+ "Scheduled task %s has expired"
+ "Scheduled task %s is being launched"
+ "Unable to deregister previously registered task"
+ "Will overwrite previously scheduled task with identifier %s"
+ "_TtC10seserviced18SESAnalyticsLogger"
+ "_TtCC10seserviced18SESAnalyticsLogger19SECSessionAnalytics"
+ "asset.compatibility.version"
+ "asset.content.version"
+ "assetCompatibilityVersion"
+ "assetContentVersion"
+ "com.apple.sesd.generalStatistics"
+ "com.apple.seserviced.scheduledActivities"
+ "com.apple.seserviced.viennaHeartbeatReporting"
+ "com.apple.seserviced.viennaPresentmentReporting"
+ "countsKeyedByCountEvents"
+ "currentTask"
+ "deregisterTaskWithIdentifier:"
+ "elapsedTimesKeyedByEvents"
+ "handleAnalyticsTaskExpiration(task:)"
+ "handleAnalyticsTaskLaunch(task:)"
+ "invalidationReason"
+ "macOS (15.6) - SecureElementService-56.2"
+ "registerForTaskWithIdentifier:usingQueue:launchHandler:"
+ "scheduleAnalyticsTask()"
+ "scheduledActivities"
+ "setExpirationHandler:"
+ "setInterval:"
+ "setMinDurationBetweenInstances:"
+ "setPriority:"
+ "setRequiresExternalPower:"
+ "setRequiresNetworkConnectivity:"
+ "setTaskCompleted"
+ "sharedScheduler"
+ "startup"
+ "submitTaskRequest:error:"
+ "taskInterval"
+ "taskRequestForIdentifier:"
+ "totalSecureElementCredentialSession"
+ "v16@?0@\"BGSystemTask\"8"
+ "vienna.session.count"
- "macOS (15.5) - SecureElementService-55.4"
```
