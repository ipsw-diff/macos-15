## DeviceInterface

> `/System/Library/Templates/Data/Library/Apple/System/Library/PrivateFrameworks/DeviceInterface.framework/Versions/A/DeviceInterface`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__data`

```diff

-208.121.1.0.0
-  __TEXT.__text: 0x86f9c
+208.140.7.0.0
+  __TEXT.__text: 0x89140
   __TEXT.__auth_stubs: 0x640
-  __TEXT.__objc_methlist: 0x5c3c
+  __TEXT.__objc_methlist: 0x5d1c
   __TEXT.__const: 0x64
-  __TEXT.__oslogstring: 0x4003
-  __TEXT.__cstring: 0x4821
+  __TEXT.__oslogstring: 0x4356
+  __TEXT.__cstring: 0x48c5
   __TEXT.__gcc_except_tab: 0x8a4
-  __TEXT.__unwind_info: 0x1388
+  __TEXT.__unwind_info: 0x13c0
   __TEXT.__objc_classname: 0xd4a
-  __TEXT.__objc_methname: 0xd55f
+  __TEXT.__objc_methname: 0xd819
   __TEXT.__objc_methtype: 0x696b
-  __TEXT.__objc_stubs: 0x62e0
+  __TEXT.__objc_stubs: 0x63e0
   __DATA_CONST.__got: 0x240
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__objc_classlist: 0x2e0
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2270
+  __DATA_CONST.__objc_selrefs: 0x22f8
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x2d0
   __AUTH_CONST.__auth_got: 0x330
   __AUTH_CONST.__const: 0x7c0
   __AUTH_CONST.__cfstring: 0x620
-  __AUTH_CONST.__objc_const: 0xc4b0
+  __AUTH_CONST.__objc_const: 0xc5a0
   __AUTH_CONST.__objc_intobj: 0x120
   __AUTH.__objc_data: 0x1cc0
   __AUTH.__data: 0x4f0
-  __DATA.__objc_ivar: 0xa78
+  __DATA.__objc_ivar: 0xa8c
   __DATA.__data: 0x4b0
   __DATA.__bss: 0xa0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpcap.A.dylib
-  Functions: 2518
-  Symbols:   4954
-  CStrings:  3232
+  Functions: 2539
+  Symbols:   4988
+  CStrings:  3283
 
Symbols:
+ -[KISInterfaceDebugUSB dcmWatchdogTimerRegisterValue]
+ -[KISInterfaceDebugUSB isWatchdogAvailable]
+ -[KISInterfaceDebugUSB processWatchdogChange:data:length:]
+ -[KISInterfaceDebugUSB processWatchdogChangePart1:data:length:]
+ -[KISInterfaceDebugUSB processWatchdogChangePart2:data:length:]
+ -[KISInterfaceDebugUSB processWatchdogChangePart3:data:length:]
+ -[KISInterfaceDebugUSB setDcmWatchdogTimerRegisterValue:]
+ -[KISInterfaceDebugUSB setWatchdogChangeCompleted:]
+ -[KISInterfaceDebugUSB setWatchdogChangeStarted:]
+ -[KISInterfaceDebugUSB setWatchdogInitStep:]
+ -[KISInterfaceDebugUSB setupWatchdogPart1]
+ -[KISInterfaceDebugUSB setupWatchdogPart2]
+ -[KISInterfaceDebugUSB setupWatchdogPart3]
+ -[KISInterfaceDebugUSB startWatchdogChange]
+ -[KISInterfaceDebugUSB watchdogChangeCompleted]
+ -[KISInterfaceDebugUSB watchdogChangeStarted]
+ -[KISInterfaceDebugUSB watchdogInitStep]
+ -[RSMInterfaceKIS dcmEndpoint]
+ -[RSMInterfaceKIS isWatchdogAvailable]
+ OBJC_IVAR_$_KISInterfaceDebugUSB._dcmWatchdogTimerRegisterValue
+ OBJC_IVAR_$_KISInterfaceDebugUSB._watchdogChangeCompleted
+ OBJC_IVAR_$_KISInterfaceDebugUSB._watchdogChangeStarted
+ OBJC_IVAR_$_KISInterfaceDebugUSB._watchdogInitStep
+ OBJC_IVAR_$_RSMInterfaceKIS._dcmEndpoint
+ ___os_log_helper_16_2_4_8_32_8_0_4_0_4_0
+ ___os_log_helper_16_2_5_8_32_8_0_4_0_4_0_8_64
+ _objc_msgSend$processWatchdogChange:data:length:
+ _objc_msgSend$processWatchdogChangePart1:data:length:
+ _objc_msgSend$processWatchdogChangePart2:data:length:
+ _objc_msgSend$processWatchdogChangePart3:data:length:
+ _objc_msgSend$setupWatchdogPart1
+ _objc_msgSend$setupWatchdogPart2
+ _objc_msgSend$setupWatchdogPart3
+ _objc_msgSend$startWatchdogChange
CStrings:
+ "%s (DCM) clearWatchdogStatus failed"
+ "%s (DCM) clearWatchdogStatus for bitmask: %x"
+ "%s (DCM) interfaceID 0x%llx portalID %d response received length %d"
+ "%s (DCM) interfaceID 0x%llx portalID %d response received length %d, payload: %@"
+ "%s DCM portal endpoint lookup failed"
+ "%s DCM register for callbacks for endpoint %d failed"
+ "%s read WDOG_DRAIN_STATUS"
+ "%s read watchdog status failed"
+ "%s: KIS[0x%llx] Processing Watchdog change."
+ "%s: KIS[0x%llx] Starting Watchdog change."
+ "-[KISInterfaceDebugUSB processWatchdogChange:data:length:]"
+ "-[KISInterfaceDebugUSB startWatchdogChange]"
+ "-[RSMInterfaceKIS isWatchdogAvailable]"
+ "TB,N,V_watchdogChangeCompleted"
+ "TB,N,V_watchdogChangeStarted"
+ "TC,R,N,V_dcmEndpoint"
+ "TI,N,V_dcmWatchdogTimerRegisterValue"
+ "Ti,N,V_watchdogInitStep"
+ "_dcmEndpoint"
+ "_dcmWatchdogTimerRegisterValue"
+ "_watchdogChangeCompleted"
+ "_watchdogChangeStarted"
+ "_watchdogInitStep"
+ "dcmEndpoint"
+ "dcmWatchdogTimerRegisterValue"
+ "portal %d is clogged"
+ "processWatchdogChange:data:length:"
+ "processWatchdogChangePart1"
+ "processWatchdogChangePart1: WatchdogTimer value: %x, will set new value: %x"
+ "processWatchdogChangePart1: completed"
+ "processWatchdogChangePart1:data:length:"
+ "processWatchdogChangePart2"
+ "processWatchdogChangePart2: completed"
+ "processWatchdogChangePart2:data:length:"
+ "processWatchdogChangePart3"
+ "processWatchdogChangePart3: completed"
+ "processWatchdogChangePart3:data:length:"
+ "rsm_response_callback"
+ "setDcmWatchdogTimerRegisterValue:"
+ "setWatchdogChangeCompleted:"
+ "setWatchdogChangeStarted:"
+ "setWatchdogInitStep:"
+ "setupWatchdogPart1"
+ "setupWatchdogPart1: %d"
+ "setupWatchdogPart2"
+ "setupWatchdogPart2: %d"
+ "setupWatchdogPart3"
+ "setupWatchdogPart3: %d"
+ "startWatchdogChange"
+ "watchdogChangeCompleted"
+ "watchdogChangeStarted"
+ "watchdogInitStep"
+ "\xf8\""
- "%s clearWatchdogStatus failed"
- "\xe8\""
```
