## libnetquality.dylib

> `/usr/lib/libnetquality.dylib`

```diff

-147.120.6.0.0
-  __TEXT.__text: 0x1a7d8
-  __TEXT.__auth_stubs: 0x9b0
-  __TEXT.__objc_methlist: 0x169c
+147.140.5.0.0
+  __TEXT.__text: 0x1a8d0
+  __TEXT.__auth_stubs: 0x9c0
+  __TEXT.__objc_methlist: 0x16a4
   __TEXT.__const: 0x190
-  __TEXT.__gcc_except_tab: 0x514
-  __TEXT.__cstring: 0x235a
-  __TEXT.__oslogstring: 0x162a
+  __TEXT.__gcc_except_tab: 0x520
+  __TEXT.__cstring: 0x2377
+  __TEXT.__oslogstring: 0x1656
   __TEXT.__unwind_info: 0x518
   __TEXT.__objc_classname: 0x315
-  __TEXT.__objc_methname: 0x3e3a
+  __TEXT.__objc_methname: 0x3e54
   __TEXT.__objc_methtype: 0xc57
-  __TEXT.__objc_stubs: 0x3260
+  __TEXT.__objc_stubs: 0x3280
   __DATA_CONST.__got: 0x178
   __DATA_CONST.__const: 0x178
   __DATA_CONST.__objc_classlist: 0xc0
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xef8
+  __DATA_CONST.__objc_selrefs: 0xf00
   __DATA_CONST.__objc_superrefs: 0xa0
   __DATA_CONST.__objc_arraydata: 0x58
-  __AUTH_CONST.__auth_got: 0x4e8
+  __AUTH_CONST.__auth_got: 0x4f0
   __AUTH_CONST.__const: 0x580
   __AUTH_CONST.__cfstring: 0x1900
   __AUTH_CONST.__objc_const: 0x36b0

   - /System/Library/PrivateFrameworks/Rapport.framework/Versions/A/Rapport
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 577
-  Symbols:   1616
-  CStrings:  1305
+  Functions: 578
+  Symbols:   1619
+  CStrings:  1308
 
Symbols:
+ -[NetworkQualityConfiguration hasCustomConfigurationSet]
+ _network_config_get_l4s_enabled
+ _objc_msgSend$hasCustomConfigurationSet
Functions:
~ ___53-[NetworkQualityExecutions runWithCompletionHandler:]_block_invoke : 2672 -> 2888
+ -[NetworkQualityConfiguration hasCustomConfigurationSet]
CStrings:
+ "%s:%u - Using L4S Server pool for test run."
+ "hasCustomConfigurationSet"
+ "mensura-l4s.networking.apple"
```
