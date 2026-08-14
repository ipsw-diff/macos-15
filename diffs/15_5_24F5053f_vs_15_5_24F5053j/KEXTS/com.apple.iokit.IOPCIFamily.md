## com.apple.iokit.IOPCIFamily

> `com.apple.iokit.IOPCIFamily`

```diff

-681.120.2.0.0
+681.120.2.0.1
   __TEXT.__const: 0x710
-  __TEXT.__cstring: 0x548e
-  __TEXT_EXEC.__text: 0x30f40
+  __TEXT.__cstring: 0x54d8
+  __TEXT_EXEC.__text: 0x31124
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xcc
   __DATA.__common: 0x218

   __DATA_CONST.__kalloc_type: 0x600
   __DATA_CONST.__kalloc_var: 0x190
   __LINKINFO.__symbolsets: 0x639f
-  Functions: 738
-  Symbols:   1318
-  CStrings:  670
+  Functions: 739
+  Symbols:   1319
+  CStrings:  672
 
Symbols:
+ __ZN11IOPCIBridge25findThunderboltPortForNubEP11IOPCIDevice
+ __ZZN11IOPCIBridge10publishNubEP11IOPCIDevicejE21kalloc_type_view_2962
+ __ZZN11IOPCIBridge17createEventSourceEP8OSObjectPFvS1_P16IOPCIEventSourcePK10IOPCIEventEjE21kalloc_type_view_5812
+ __ZZN15IOPCI2PCIBridge21startBridgeInterruptsEP9IOServiceE21kalloc_type_view_5199
+ __ZZN15IOPCI2PCIBridge4stopEP9IOServiceE21kalloc_type_view_5607
+ __ZZN16IOPCIEventSource4freeEvE21kalloc_type_view_5937
- __ZZN11IOPCIBridge10publishNubEP11IOPCIDevicejE21kalloc_type_view_2942
- __ZZN11IOPCIBridge17createEventSourceEP8OSObjectPFvS1_P16IOPCIEventSourcePK10IOPCIEventEjE21kalloc_type_view_5775
- __ZZN15IOPCI2PCIBridge21startBridgeInterruptsEP9IOServiceE21kalloc_type_view_5162
- __ZZN15IOPCI2PCIBridge4stopEP9IOServiceE21kalloc_type_view_5570
- __ZZN16IOPCIEventSource4freeEvE21kalloc_type_view_5900
CStrings:
+ "21:23:39"
+ "Adapter Type"
+ "Apr 15 2025"
+ "nub %s@%u:%u:%u's thunderbolt port wasn't found after %u ms\n"
- "20:11:15"
- "Apr 10 2025"
```
