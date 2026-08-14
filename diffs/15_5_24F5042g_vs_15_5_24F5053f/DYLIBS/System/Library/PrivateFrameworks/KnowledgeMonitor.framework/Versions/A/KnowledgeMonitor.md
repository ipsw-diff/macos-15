## KnowledgeMonitor

> `/System/Library/PrivateFrameworks/KnowledgeMonitor.framework/Versions/A/KnowledgeMonitor`

```diff

-458.5.0.1.0
-  __TEXT.__text: 0x1c7c4
-  __TEXT.__auth_stubs: 0x890
-  __TEXT.__objc_methlist: 0x1e94
-  __TEXT.__const: 0x100
+458.7.0.0.0
+  __TEXT.__text: 0x1cf14
+  __TEXT.__auth_stubs: 0x8b0
+  __TEXT.__objc_methlist: 0x1ed4
+  __TEXT.__const: 0x108
   __TEXT.__gcc_except_tab: 0x49c
-  __TEXT.__cstring: 0x14b9
-  __TEXT.__oslogstring: 0x186f
-  __TEXT.__unwind_info: 0x720
+  __TEXT.__cstring: 0x14e5
+  __TEXT.__oslogstring: 0x19cd
+  __TEXT.__unwind_info: 0x748
   __TEXT.__objc_classname: 0x39a
-  __TEXT.__objc_methname: 0x5672
+  __TEXT.__objc_methname: 0x572d
   __TEXT.__objc_methtype: 0xa63
-  __TEXT.__objc_stubs: 0x3f80
-  __DATA_CONST.__got: 0x3c0
+  __TEXT.__objc_stubs: 0x4060
+  __DATA_CONST.__got: 0x3c8
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__objc_classlist: 0xe0
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1630
+  __DATA_CONST.__objc_selrefs: 0x1668
   __DATA_CONST.__objc_superrefs: 0xb8
-  __DATA_CONST.__objc_arraydata: 0x48
-  __AUTH_CONST.__auth_got: 0x458
+  __DATA_CONST.__objc_arraydata: 0x40
+  __AUTH_CONST.__auth_got: 0x468
   __AUTH_CONST.__const: 0x710
   __AUTH_CONST.__cfstring: 0xd20
   __AUTH_CONST.__objc_const: 0x2fd8
-  __AUTH_CONST.__objc_arrayobj: 0xa8
+  __AUTH_CONST.__objc_intobj: 0x108
+  __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__objc_intobj: 0xf0
   __AUTH.__objc_data: 0x3c0
   __DATA.__objc_ivar: 0x230
   __DATA.__data: 0x3c8
-  __DATA.__bss: 0x58
+  __DATA.__bss: 0x60
   __DATA_DIRTY.__objc_data: 0x500
   __DATA_DIRTY.__bss: 0x8
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 735
-  Symbols:   1902
-  CStrings:  1370
+  Functions: 746
+  Symbols:   1919
+  CStrings:  1387
 
Symbols:
+ -[_DKBacklightMonitor _shutdownDateFromSpringBoard]
+ -[_DKBacklightMonitor _shutdownDateFromSysctl]
+ -[_DKBacklightMonitor donateRetroactiveShutdownBacklightOffEvent]
+ -[_DKBacklightMonitor handleShutdownNotification]
+ -[_DKBacklightMonitor shutdownDate]
+ ___65-[_DKBacklightMonitor donateRetroactiveShutdownBacklightOffEvent]_block_invoke
+ ___NSArray0__struct
+ ___error
+ _objc_msgSend$_shutdownDateFromSysctl
+ _objc_msgSend$checkShutdownConditionOfBacklightStream
+ _objc_msgSend$dateWithTimeIntervalSinceNow:
+ _objc_msgSend$donateRetroactiveShutdownBacklightOffEvent
+ _objc_msgSend$handleShutdownNotification
+ _objc_msgSend$shutdownDate
+ _objc_msgSend$timeIntervalSinceNow
+ _sysctlbyname
+ donateRetroactiveShutdownBacklightOffEvent.onceToken
CStrings:
+ "%@: Shutdown date is in the future"
+ "%@: bootDate: %@"
+ "%@: shutdownDate is: %@"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBacklightMonitor.m:175"
+ "Elapsed PMU RTC ticks in USecs since shutdown: %{public}@"
+ "SpringBoard shutdown date: %{public}@"
+ "Unable to get kern.monotonicclock_usecs: %{errno}d"
+ "Unable to get kern.shutdowntime: %{errno}d"
+ "Using shutdown date from kern.shutdowntime: %{public}@"
+ "_shutdownDateFromSpringBoard"
+ "_shutdownDateFromSysctl"
+ "dateWithTimeIntervalSinceNow:"
+ "donateRetroactiveShutdownBacklightOffEvent"
+ "handleShutdownNotification"
+ "kern.monotonicclock_usecs"
+ "kern.monotonicclock_usecs[0] must be non-zero"
+ "kern.shutdowntime"
+ "kern.shutdowntime must be non-zero"
+ "shutdownDate"
+ "timeIntervalSinceNow"
- "%@: SBLastKnownShutdownDate is: %@"
- "%@: bootTime: %@"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBacklightMonitor.m:262"
```
