## WiFiPolicy

> `/System/Library/PrivateFrameworks/WiFiPolicy.framework/Versions/A/WiFiPolicy`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-925.33.0.0.0
-  __TEXT.__text: 0xc3c90
+935.1.0.0.0
+  __TEXT.__text: 0xc401c
   __TEXT.__auth_stubs: 0x12d0
-  __TEXT.__objc_methlist: 0x110d0
+  __TEXT.__objc_methlist: 0x110f0
   __TEXT.__const: 0x628
-  __TEXT.__cstring: 0x1b536
-  __TEXT.__oslogstring: 0x355d
+  __TEXT.__cstring: 0x1b547
+  __TEXT.__oslogstring: 0x35b0
   __TEXT.__gcc_except_tab: 0x17a0
-  __TEXT.__unwind_info: 0x20d8
+  __TEXT.__unwind_info: 0x20e0
   __TEXT.__objc_classname: 0x1379
-  __TEXT.__objc_methname: 0x315e5
+  __TEXT.__objc_methname: 0x31649
   __TEXT.__objc_methtype: 0x39f7
-  __TEXT.__objc_stubs: 0x17a20
+  __TEXT.__objc_stubs: 0x17a60
   __DATA_CONST.__got: 0x9e0
   __DATA_CONST.__const: 0xb98
   __DATA_CONST.__objc_classlist: 0x510
   __DATA_CONST.__objc_catlist: 0x58
   __DATA_CONST.__objc_protolist: 0x100
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x95f0
+  __DATA_CONST.__objc_selrefs: 0x9608
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x430
   __DATA_CONST.__objc_arraydata: 0xa58
   __AUTH_CONST.__auth_got: 0x980
   __AUTH_CONST.__const: 0x1ba0
-  __AUTH_CONST.__cfstring: 0x18480
-  __AUTH_CONST.__objc_const: 0x20ac0
+  __AUTH_CONST.__cfstring: 0x18460
+  __AUTH_CONST.__objc_const: 0x20af0
   __AUTH_CONST.__objc_intobj: 0x1740
   __AUTH_CONST.__objc_arrayobj: 0x390
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH.__objc_data: 0x3200
-  __DATA.__objc_ivar: 0x2090
+  __DATA.__objc_ivar: 0x2094
   __DATA.__data: 0x1bc0
   __DATA.__bss: 0x263
   __DATA.__common: 0x20

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 6020
-  Symbols:   13264
-  CStrings:  12730
+  Functions: 6023
+  Symbols:   13270
+  CStrings:  12738
 
Symbols:
+ -[WiFiUsageMonitor cachedFaults]
+ -[WiFiUsageMonitor processCachedFaults]
+ -[WiFiUsageMonitor setCachedFaults:]
+ GCC_except_table242
+ OBJC_IVAR_$_WiFiUsageMonitor._cachedFaults
+ _objc_msgSend$cachedFaults
+ _objc_msgSend$processCachedFaults
- GCC_except_table241
Functions:
~ -[WiFiUsageLinkSession performLinkTestFor:isTriggeredByFault:] : 964 -> 932
~ -[WiFiUsageMonitor init] : 732 -> 756
~ ___116-[WiFiUsageMonitor setLinkEvent:isInvoluntary:linkChangeReason:linkChangeSubreason:withNetworkDetails:forInterface:]_block_invoke : 1736 -> 1744
~ -[WiFiUsageMonitor sendFaultToDB:] : 176 -> 488
- -[WiFiUsageMonitor .cxx_destruct]
- -[WiFiUsageMonitor_UsbDevice initWithName:vid:isApple:locationID:]
+ -[WiFiUsageMonitor .cxx_destruct]
+ -[WiFiUsageMonitor_UsbDevice initWithName:vid:isApple:locationID:]
+ -[WiFiUsageMonitor_UsbDevice setName:]
+ -[WiFiUsageMonitor_UsbDevice setLocationID:]
~ -[WFMeasure initWithType:andReason:prevTestedOptions:andInterfaceName:] : 1752 -> 1764
+ -[WiFiUsageMonitor processCachedFaults]
CStrings:
+ "%s: Appended to in-memory cache (%lu %f.0sec)"
+ "%s: Processing in-memory cache (%lu)"
+ "-[WiFiUsageMonitor processCachedFaults]"
+ "-[WiFiUsageMonitor sendFaultToDB:]"
+ "T@\"NSMutableArray\",&,V_cachedFaults"
+ "_cachedFaults"
+ "cachedFaults"
+ "processCachedFaults"
+ "setCachedFaults:"
- "%s Rejected due to [WiFiUsagePrivacyFilter isInternalInstall]\n"
```
