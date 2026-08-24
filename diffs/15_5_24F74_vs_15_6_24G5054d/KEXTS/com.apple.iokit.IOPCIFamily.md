## com.apple.iokit.IOPCIFamily

> `com.apple.iokit.IOPCIFamily`

```diff

-681.120.3.0.0
+681.140.3.0.0
   __TEXT.__const: 0x710
-  __TEXT.__cstring: 0x54d8
-  __TEXT_EXEC.__text: 0x31124
+  __TEXT.__cstring: 0x554b
+  __TEXT_EXEC.__text: 0x31738
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xcc
   __DATA.__common: 0x218
   __DATA_CONST.__auth_got: 0x458
-  __DATA_CONST.__got: 0xf8
+  __DATA_CONST.__got: 0x100
   __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__mod_init_func: 0x20
   __DATA_CONST.__mod_term_func: 0x20

   __DATA_CONST.__kalloc_type: 0x600
   __DATA_CONST.__kalloc_var: 0x190
   __LINKINFO.__symbolsets: 0x639f
-  Functions: 739
-  Symbols:   1319
-  CStrings:  672
+  Functions: 743
+  Symbols:   1324
+  CStrings:  675
 
Symbols:
+ __ZN11IOPCIDevice13initiatePauseEv
+ __ZN11IOPCIDevice14isInitializingEv
+ __ZN11IOPCIDevice15busyStateChangeEPvS0_jP9IOServiceS0_m
+ __ZN11IOPCIDevice17pauseTimerHandlerEP18IOTimerEventSource
+ __ZZN11IOPCIBridge10publishNubEP11IOPCIDevicejE21kalloc_type_view_2971
+ __ZZN11IOPCIBridge17createEventSourceEP8OSObjectPFvS1_P16IOPCIEventSourcePK10IOPCIEventEjE21kalloc_type_view_5821
+ __ZZN11IOPCIDevice12initReservedEvE20kalloc_type_view_405
+ __ZZN11IOPCIDevice4freeEvE20kalloc_type_view_434
+ __ZZN11IOPCIDevice4freeEvE20kalloc_type_view_450
+ __ZZN15IOPCI2PCIBridge21startBridgeInterruptsEP9IOServiceE21kalloc_type_view_5208
+ __ZZN15IOPCI2PCIBridge4stopEP9IOServiceE21kalloc_type_view_5616
+ __ZZN16IOPCIEventSource4freeEvE21kalloc_type_view_5946
+ _gIOBusyInterest
- __ZZN11IOPCIBridge10publishNubEP11IOPCIDevicejE21kalloc_type_view_2962
- __ZZN11IOPCIBridge17createEventSourceEP8OSObjectPFvS1_P16IOPCIEventSourcePK10IOPCIEventEjE21kalloc_type_view_5812
- __ZZN11IOPCIDevice12initReservedEvE20kalloc_type_view_394
- __ZZN11IOPCIDevice4freeEvE20kalloc_type_view_423
- __ZZN11IOPCIDevice4freeEvE20kalloc_type_view_433
- __ZZN15IOPCI2PCIBridge21startBridgeInterruptsEP9IOServiceE21kalloc_type_view_5199
- __ZZN15IOPCI2PCIBridge4stopEP9IOServiceE21kalloc_type_view_5607
- __ZZN16IOPCIEventSource4freeEvE21kalloc_type_view_5937
CStrings:
+ "%s(0x%qx) still initializing, deferring pause\n"
+ "21:12:22"
+ "22222222221222111212211111111111111211222112"
+ "Jun 11 2025"
+ "[%s()] nub %s(0x%qx) has busy state %u\n"
+ "busyStateChange"
+ "configOp:->deferredRequestPause: %s(0x%qx)\n"
- "19:43:11"
- "22222222221222111212211111111111111211222"
- "Apr 22 2025"
- "configOp:->pause: %s(0x%qx), 0x%x\n"
```
