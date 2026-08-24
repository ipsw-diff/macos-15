## KnowledgeMonitor

> `/System/Library/PrivateFrameworks/KnowledgeMonitor.framework/Versions/A/KnowledgeMonitor`

```diff

-458.7.0.0.0
-  __TEXT.__text: 0x1cf14
+458.8.0.0.0
+  __TEXT.__text: 0x1d2fc
   __TEXT.__auth_stubs: 0x8b0
-  __TEXT.__objc_methlist: 0x1ed4
-  __TEXT.__const: 0x108
-  __TEXT.__gcc_except_tab: 0x49c
-  __TEXT.__cstring: 0x14e5
-  __TEXT.__oslogstring: 0x19cd
-  __TEXT.__unwind_info: 0x748
+  __TEXT.__objc_methlist: 0x1eec
+  __TEXT.__const: 0x110
+  __TEXT.__gcc_except_tab: 0x4b0
+  __TEXT.__cstring: 0x1505
+  __TEXT.__oslogstring: 0x1a0d
+  __TEXT.__unwind_info: 0x750
   __TEXT.__objc_classname: 0x39a
-  __TEXT.__objc_methname: 0x572d
-  __TEXT.__objc_methtype: 0xa63
-  __TEXT.__objc_stubs: 0x4060
-  __DATA_CONST.__got: 0x3c8
+  __TEXT.__objc_methname: 0x57ac
+  __TEXT.__objc_methtype: 0xa6e
+  __TEXT.__objc_stubs: 0x4100
+  __DATA_CONST.__got: 0x3d0
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__objc_classlist: 0xe0
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1668
+  __DATA_CONST.__objc_selrefs: 0x1690
   __DATA_CONST.__objc_superrefs: 0xb8
   __DATA_CONST.__objc_arraydata: 0x40
   __AUTH_CONST.__auth_got: 0x468
   __AUTH_CONST.__const: 0x710
-  __AUTH_CONST.__cfstring: 0xd20
-  __AUTH_CONST.__objc_const: 0x2fd8
+  __AUTH_CONST.__cfstring: 0xd40
+  __AUTH_CONST.__objc_const: 0x2ff8
   __AUTH_CONST.__objc_intobj: 0x108
   __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH.__objc_data: 0x3c0
-  __DATA.__objc_ivar: 0x230
+  __DATA.__objc_ivar: 0x234
   __DATA.__data: 0x3c8
   __DATA.__bss: 0x60
   __DATA_DIRTY.__objc_data: 0x500

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 746
-  Symbols:   1919
-  CStrings:  1387
+  Functions: 749
+  Symbols:   1930
+  CStrings:  1398
 
Symbols:
+ -[_DKBacklightMonitor _lastAliveDate]
+ -[_DKBacklightMonitor _setLastAliveDate:]
+ GCC_except_table29
+ OBJC_IVAR_$__DKBacklightMonitor._lastAliveDateTimer
+ _OBJC_CLASS_$_NSTimer
+ __65-[_DKBacklightMonitor donateRetroactiveShutdownBacklightOffEvent]_block_invoke
+ ___block_descriptor_40_e8_32w_e17_v16?0"NSTimer"8l
+ _objc_msgSend$_lastAliveDate
+ _objc_msgSend$_setLastAliveDate:
+ _objc_msgSend$laterDate:
+ _objc_msgSend$scheduledTimerWithTimeInterval:repeats:block:
+ _objc_msgSend$sendEvent:date:
- ___block_descriptor_48_e8_32s40w_e8_v12?0i8l
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBacklightMonitor.m:191"
+ "@\"NSTimer\""
+ "Last alive date is: %{public}@"
+ "LastAliveDate"
+ "Setting last alive date: %{public}@"
+ "Shutdown date from kern.shutdowntime is: %{public}@"
+ "_lastAliveDate"
+ "_lastAliveDateTimer"
+ "_setLastAliveDate:"
+ "laterDate:"
+ "scheduledTimerWithTimeInterval:repeats:block:"
+ "sendEvent:date:"
+ "v16@?0@\"NSTimer\"8"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBacklightMonitor.m:175"
- "Using shutdown date from kern.shutdowntime: %{public}@"
```
