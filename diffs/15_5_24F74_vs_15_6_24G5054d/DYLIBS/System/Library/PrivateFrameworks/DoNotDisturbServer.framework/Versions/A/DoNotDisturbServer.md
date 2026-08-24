## DoNotDisturbServer

> `/System/Library/PrivateFrameworks/DoNotDisturbServer.framework/Versions/A/DoNotDisturbServer`

```diff

-433.6.1.0.0
-  __TEXT.__text: 0xcc9c8
+433.7.1.0.0
+  __TEXT.__text: 0xccc14
   __TEXT.__auth_stubs: 0x1100
-  __TEXT.__objc_methlist: 0xa550
-  __TEXT.__const: 0x418
-  __TEXT.__cstring: 0x8374
-  __TEXT.__oslogstring: 0xfaa0
+  __TEXT.__objc_methlist: 0xa568
+  __TEXT.__const: 0x4e0
+  __TEXT.__cstring: 0x83e4
+  __TEXT.__oslogstring: 0xfb40
   __TEXT.__gcc_except_tab: 0xdc8
   __TEXT.__constg_swiftt: 0x14c
   __TEXT.__swift5_typeref: 0x150

   __TEXT.__swift5_proto: 0xc
   __TEXT.__swift_as_entry: 0x2c
   __TEXT.__swift_as_ret: 0x2c
-  __TEXT.__unwind_info: 0x26a8
+  __TEXT.__unwind_info: 0x26b8
   __TEXT.__eh_frame: 0x540
   __TEXT.__objc_classname: 0x2866
-  __TEXT.__objc_methname: 0x18db9
+  __TEXT.__objc_methname: 0x18dd8
   __TEXT.__objc_methtype: 0x73b9
-  __TEXT.__objc_stubs: 0xfbe0
+  __TEXT.__objc_stubs: 0xfc20
   __DATA_CONST.__got: 0xda0
   __DATA_CONST.__const: 0xa08
   __DATA_CONST.__objc_classlist: 0x5e8
   __DATA_CONST.__objc_catlist: 0x138
   __DATA_CONST.__objc_protolist: 0x3c8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4978
+  __DATA_CONST.__objc_selrefs: 0x4988
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x3d0
   __DATA_CONST.__objc_arraydata: 0x330
   __AUTH_CONST.__auth_got: 0x890
   __AUTH_CONST.__const: 0x2d50
-  __AUTH_CONST.__cfstring: 0x6fe0
+  __AUTH_CONST.__cfstring: 0x7020
   __AUTH_CONST.__objc_const: 0x24e28
   __AUTH_CONST.__objc_intobj: 0x2d0
   __AUTH_CONST.__objc_dictobj: 0x488

   __AUTH.__objc_data: 0x3cd0
   __AUTH.__data: 0x78
   __DATA.__objc_ivar: 0x9dc
-  __DATA.__data: 0x3300
+  __DATA.__data: 0x3230
   __DATA.__bss: 0x3b0
   __DATA.__common: 0x1b0
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 3712
-  Symbols:   8971
-  CStrings:  6149
+  Functions: 3718
+  Symbols:   8978
+  CStrings:  6155
 
Symbols:
+ -[DNDSMeDeviceService devicesChanged]
+ -[DNDSMeDeviceService meDeviceChanged]
+ ___37-[DNDSMeDeviceService devicesChanged]_block_invoke
+ ___38-[DNDSMeDeviceService meDeviceChanged]_block_invoke
+ _fmlDevicesChangedNotificationCallback
+ _fmlMeDeviceChangedNotificationCallback
+ _objc_msgSend$devicesChanged
+ _objc_msgSend$meDeviceChanged
- GCC_except_table19
CStrings:
+ "FMLDevicesChangedNotification"
+ "FMLMeDeviceChangedNotification"
+ "devicesChanged"
+ "meDeviceChanged"
+ "received notification that 'Me Device' devices changed fetching Me Device"
+ "received notification that 'Me Device' status changed fetching Me Device"
```
