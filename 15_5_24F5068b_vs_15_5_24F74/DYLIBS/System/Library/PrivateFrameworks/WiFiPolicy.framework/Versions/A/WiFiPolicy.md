## WiFiPolicy

> `/System/Library/PrivateFrameworks/WiFiPolicy.framework/Versions/A/WiFiPolicy`

```diff

 925.33.0.0.0
-  __TEXT.__text: 0xc3c7c
+  __TEXT.__text: 0xc3c90
   __TEXT.__auth_stubs: 0x12d0
   __TEXT.__objc_methlist: 0x110d0
   __TEXT.__const: 0x628
-  __TEXT.__cstring: 0x1b4f7
+  __TEXT.__cstring: 0x1b536
   __TEXT.__oslogstring: 0x355d
   __TEXT.__gcc_except_tab: 0x17a0
   __TEXT.__unwind_info: 0x20d8

   __DATA_CONST.__objc_arraydata: 0xa58
   __AUTH_CONST.__auth_got: 0x980
   __AUTH_CONST.__const: 0x1ba0
-  __AUTH_CONST.__cfstring: 0x18460
+  __AUTH_CONST.__cfstring: 0x18480
   __AUTH_CONST.__objc_const: 0x20ac0
   __AUTH_CONST.__objc_intobj: 0x1740
   __AUTH_CONST.__objc_arrayobj: 0x390

   - /usr/lib/libobjc.A.dylib
   Functions: 6020
   Symbols:   13264
-  CStrings:  12729
+  CStrings:  12730
 
Functions:
~ -[WiFiUsageLinkSession performLinkTestFor:isTriggeredByFault:] : 932 -> 964
~ -[WFMeasure initWithType:andReason:prevTestedOptions:andInterfaceName:] : 1764 -> 1752
CStrings:
+ "%s Rejected due to [WiFiUsagePrivacyFilter isInternalInstall]\n"
```
