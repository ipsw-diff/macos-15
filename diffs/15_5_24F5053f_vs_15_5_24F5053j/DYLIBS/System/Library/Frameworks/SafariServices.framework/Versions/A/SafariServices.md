## SafariServices

> `/System/Library/Frameworks/SafariServices.framework/Versions/A/SafariServices`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-621.2.3.11.1
-  __TEXT.__text: 0x18f80
-  __TEXT.__auth_stubs: 0x570
+621.2.4.11.2
+  __TEXT.__text: 0x190ac
+  __TEXT.__auth_stubs: 0x5b0
   __TEXT.__objc_methlist: 0x1574
-  __TEXT.__gcc_except_tab: 0x206c
-  __TEXT.__cstring: 0x194a
+  __TEXT.__gcc_except_tab: 0x2080
+  __TEXT.__cstring: 0x1990
   __TEXT.__const: 0xa0
   __TEXT.__oslogstring: 0xc60
   __TEXT.__unwind_info: 0xc38
   __TEXT.__objc_classname: 0x40e
-  __TEXT.__objc_methname: 0x3f84
-  __TEXT.__objc_methtype: 0xbdd
+  __TEXT.__objc_methname: 0x3fa0
+  __TEXT.__objc_methtype: 0xbfc
   __TEXT.__objc_stubs: 0x2b80
   __DATA_CONST.__got: 0x208
   __DATA_CONST.__const: 0x138

   __DATA_CONST.__objc_selrefs: 0xeb8
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x78
-  __AUTH_CONST.__auth_got: 0x2d0
+  __AUTH_CONST.__auth_got: 0x2f0
   __AUTH_CONST.__const: 0xd20
-  __AUTH_CONST.__cfstring: 0x8e0
-  __AUTH_CONST.__objc_const: 0x2308
+  __AUTH_CONST.__cfstring: 0x900
+  __AUTH_CONST.__objc_const: 0x2328
   __AUTH.__objc_data: 0xa0
-  __DATA.__objc_ivar: 0xa0
+  __DATA.__objc_ivar: 0xa4
   __DATA.__data: 0x5b0
   __DATA.__bss: 0xe0
   __DATA.__common: 0x8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 650
-  Symbols:   1585
-  CStrings:  907
+  Functions: 651
+  Symbols:   1591
+  CStrings:  910
 
Symbols:
+ GCC_except_table105
+ GCC_except_table91
+ GCC_except_table93
+ OBJC_IVAR_$_SFContentBlockerManager._discoveryNotificationQueue
+ ___69-[SFContentBlockerManager queryControllerDidUpdate:resultDifference:]_block_invoke_4
+ _dispatch_queue_attr_make_with_autorelease_frequency
+ _dispatch_queue_create
+ _dispatch_resume
+ _dispatch_suspend
- GCC_except_table104
- GCC_except_table90
- GCC_except_table92
Functions:
~ -[SFContentBlockerManager _findContentBlockerAppExtensions] : 372 -> 520
~ ___59-[SFContentBlockerManager _findContentBlockerAppExtensions]_block_invoke : 92 -> 100
~ -[SFContentBlockerManager queryControllerDidUpdate:resultDifference:] : 308 -> 160
~ ___69-[SFContentBlockerManager queryControllerDidUpdate:resultDifference:]_block_invoke : 64 -> 280
~ ___69-[SFContentBlockerManager queryControllerDidUpdate:resultDifference:]_block_invoke_2 : 156 -> 64
~ ___69-[SFContentBlockerManager queryControllerDidUpdate:resultDifference:]_block_invoke_3 : 12 -> 156
+ ___69-[SFContentBlockerManager queryControllerDidUpdate:resultDifference:]_block_invoke_4
~ -[SFContentBlockerManager .cxx_destruct] : 168 -> 180
CStrings:
+ "@\"NSObject<OS_dispatch_queue>\""
+ "_discoveryNotificationQueue"
+ "com.apple.SafariServices.SFContentBlockerManager.%@.%p.discoveryQueue"
+ "\x92"
- "\x82"
```
