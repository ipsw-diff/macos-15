## BiomeStorage

> `/System/Library/PrivateFrameworks/BiomeStorage.framework/Versions/A/BiomeStorage`

```diff

-166.22.1.0.0
-  __TEXT.__text: 0x2d148
+166.23.0.1.0
+  __TEXT.__text: 0x2d34c
   __TEXT.__auth_stubs: 0x570
-  __TEXT.__objc_methlist: 0x1f9c
+  __TEXT.__objc_methlist: 0x1fc4
   __TEXT.__const: 0x1f8
   __TEXT.__cstring: 0x16bd
-  __TEXT.__oslogstring: 0x42fa
+  __TEXT.__oslogstring: 0x4338
   __TEXT.__gcc_except_tab: 0x9a8
   __TEXT.__dlopen_cstrs: 0xac
-  __TEXT.__unwind_info: 0xad8
-  __TEXT.__objc_classname: 0x31a
-  __TEXT.__objc_methname: 0x50a9
+  __TEXT.__unwind_info: 0xae8
+  __TEXT.__objc_classname: 0x31b
+  __TEXT.__objc_methname: 0x5146
   __TEXT.__objc_methtype: 0x1228
-  __TEXT.__objc_stubs: 0x3c40
+  __TEXT.__objc_stubs: 0x3ca0
   __DATA_CONST.__got: 0x240
   __DATA_CONST.__const: 0x1e8
   __DATA_CONST.__objc_classlist: 0xc8
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1298
+  __DATA_CONST.__objc_selrefs: 0x12c0
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0xc0
   __AUTH_CONST.__auth_got: 0x2c8
   __AUTH_CONST.__const: 0x600
   __AUTH_CONST.__cfstring: 0x14c0
-  __AUTH_CONST.__objc_const: 0x4b50
+  __AUTH_CONST.__objc_const: 0x4b80
   __AUTH.__objc_data: 0x7d0
-  __DATA.__objc_ivar: 0x290
+  __DATA.__objc_ivar: 0x294
   __DATA.__data: 0x4e0
   __DATA.__bss: 0x240
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 999
-  Symbols:   2008
-  CStrings:  1491
+  Functions: 1004
+  Symbols:   2017
+  CStrings:  1499
 
Symbols:
+ -[BMSegmentManager handleDeviceLockedCX]
+ -[BMSegmentManager lockingCXReceived]
+ -[BMSegmentManager setLockingCXReceived:]
+ GCC_except_table119
+ OBJC_IVAR_$_BMSegmentManager._lockingCXReceived
+ __40-[BMSegmentManager handleDeviceLockedCX]_block_invoke
+ ___40-[BMSegmentManager handleDeviceLockedCX]_block_invoke
+ _objc_msgSend$handleDeviceLockedCX
+ _objc_msgSend$isClassCXUnlocked
+ _objc_msgSend$stringByDeletingLastPathComponent
- GCC_except_table115
CStrings:
+ "Cx Locked received without a prior Cx expiring for stream: %@"
+ "TB,N,V_lockingCXReceived"
+ "_lockingCXReceived"
+ "handleDeviceLockedCX"
+ "isClassCXUnlocked"
+ "lockingCXReceived"
+ "setLockingCXReceived:"
+ "stringByDeletingLastPathComponent"
+ "\xa1"
- "\x91"
```
