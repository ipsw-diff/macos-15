## DeviceCheck

> `/System/Library/Frameworks/DeviceCheck.framework/Versions/A/DeviceCheck`

```diff

-109.6.0.0.0
-  __TEXT.__text: 0xa8f0
-  __TEXT.__auth_stubs: 0x350
+109.7.0.0.0
+  __TEXT.__text: 0xaaa4
+  __TEXT.__auth_stubs: 0x370
   __TEXT.__objc_methlist: 0x66c
   __TEXT.__const: 0xb0
-  __TEXT.__cstring: 0xa0e
-  __TEXT.__gcc_except_tab: 0x480
+  __TEXT.__cstring: 0xa2c
+  __TEXT.__gcc_except_tab: 0x58c
   __TEXT.__oslogstring: 0x9bc
-  __TEXT.__unwind_info: 0x2c8
+  __TEXT.__unwind_info: 0x2d8
   __TEXT.__objc_classname: 0xf8
   __TEXT.__objc_methname: 0x1004
   __TEXT.__objc_methtype: 0x53b

   __DATA_CONST.__objc_selrefs: 0x470
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x18
-  __AUTH_CONST.__auth_got: 0x1b8
+  __AUTH_CONST.__auth_got: 0x1c8
   __AUTH_CONST.__const: 0x5a0
   __AUTH_CONST.__cfstring: 0x6a0
   __AUTH_CONST.__objc_const: 0xa58

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 192
-  Symbols:   510
+  Symbols:   512
   CStrings:  356
 
Symbols:
+ _objc_sync_enter
+ _objc_sync_exit
Functions:
~ -[DCAnalytics sendPerformanceForCategory:eventType:] : 2788 -> 3224
```
