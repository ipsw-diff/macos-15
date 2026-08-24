## FSKit

> `/System/Library/Frameworks/FSKit.framework/Versions/A/FSKit`

```diff

-531.120.18.0.2
-  __TEXT.__text: 0x42514
+531.140.6.0.0
+  __TEXT.__text: 0x42594
   __TEXT.__auth_stubs: 0xaa0
-  __TEXT.__objc_methlist: 0x4324
-  __TEXT.__const: 0x380
-  __TEXT.__gcc_except_tab: 0xf1c
+  __TEXT.__objc_methlist: 0x4334
+  __TEXT.__const: 0x390
+  __TEXT.__gcc_except_tab: 0xf14
   __TEXT.__cstring: 0x3e5f
   __TEXT.__oslogstring: 0x2c46
   __TEXT.__swift5_typeref: 0x1d1

   __TEXT.__unwind_info: 0x1238
   __TEXT.__eh_frame: 0x138
   __TEXT.__objc_classname: 0x825
-  __TEXT.__objc_methname: 0x9386
+  __TEXT.__objc_methname: 0x9396
   __TEXT.__objc_methtype: 0x325e
-  __TEXT.__objc_stubs: 0x5440
+  __TEXT.__objc_stubs: 0x5460
   __DATA_CONST.__got: 0x3e8
   __DATA_CONST.__const: 0x2c8
   __DATA_CONST.__objc_classlist: 0x208
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x140
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x22a8
+  __DATA_CONST.__objc_selrefs: 0x22b0
   __DATA_CONST.__objc_protorefs: 0xe8
   __DATA_CONST.__objc_superrefs: 0x190
   __DATA_CONST.__objc_arraydata: 0x30

   __AUTH.__objc_data: 0x1590
   __AUTH.__data: 0x80
   __DATA.__objc_ivar: 0x3f4
-  __DATA.__data: 0xf88
+  __DATA.__data: 0xf78
   __DATA.__bss: 0x360
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1885
-  Symbols:   3697
-  CStrings:  2806
+  Functions: 1887
+  Symbols:   3701
+  CStrings:  2807
 
Symbols:
+ -[FSBlockDeviceResource(Project) terminateLocked]
+ GCC_except_table115
+ GCC_except_table78
+ GCC_except_table92
+ ___43-[FSBlockDeviceResource(Private) terminate]_block_invoke
+ _objc_msgSend$terminateLocked
- GCC_except_table68
- GCC_except_table88
Functions:
~ _deviceNotificationCallback : 1068 -> 1116
+ -[FSBlockDeviceResource(Project) terminateLocked]
~ -[FSBlockDeviceResource(Private) terminate] : 180 -> 192
+ +[FSBlockDeviceBufferResource supportsSecureCoding]
~ -[FSItem init] : 184 -> 124
CStrings:
+ "terminateLocked"
```
