## HealthDaemon

> `/System/Library/PrivateFrameworks/HealthDaemon.framework/Versions/A/HealthDaemon`

```diff

-5200.5.1.0.0
-  __TEXT.__text: 0x7b0a5c
+5200.6.2.0.0
+  __TEXT.__text: 0x7b0dc0
   __TEXT.__auth_stubs: 0x39e0
-  __TEXT.__objc_methlist: 0x41c64
+  __TEXT.__objc_methlist: 0x41c74
   __TEXT.__const: 0x1c5b4
-  __TEXT.__cstring: 0x76458
+  __TEXT.__cstring: 0x764bb
   __TEXT.__swift5_typeref: 0x370
   __TEXT.__swift5_capture: 0x128
   __TEXT.__constg_swiftt: 0x530

   __TEXT.__swift5_reflstr: 0x232
   __TEXT.__swift5_fieldmd: 0x274
   __TEXT.__swift5_types: 0x30
-  __TEXT.__oslogstring: 0x3d8b9
+  __TEXT.__oslogstring: 0x3d947
   __TEXT.__swift5_protos: 0x8
   __TEXT.__swift5_proto: 0x14
-  __TEXT.__gcc_except_tab: 0x37e64
+  __TEXT.__gcc_except_tab: 0x37ea0
   __TEXT.__ustring: 0x70
-  __TEXT.__unwind_info: 0x1bac8
+  __TEXT.__unwind_info: 0x1bae8
   __TEXT.__eh_frame: 0x918
   __TEXT.__objc_classname: 0xc660
-  __TEXT.__objc_methname: 0x8b753
+  __TEXT.__objc_methname: 0x8b7a1
   __TEXT.__objc_methtype: 0x174e8
   __TEXT.__objc_stubs: 0x4e180
   __DATA_CONST.__got: 0x5048

   __DATA_CONST.__objc_catlist: 0x470
   __DATA_CONST.__objc_protolist: 0x998
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x193e0
+  __DATA_CONST.__objc_selrefs: 0x193e8
   __DATA_CONST.__objc_protorefs: 0x1b0
   __DATA_CONST.__objc_superrefs: 0x1da8
   __DATA_CONST.__objc_arraydata: 0x8720
   __AUTH_CONST.__auth_got: 0x1d08
-  __AUTH_CONST.__const: 0x210d8
+  __AUTH_CONST.__const: 0x21108
   __AUTH_CONST.__cfstring: 0x3c260
-  __AUTH_CONST.__objc_const: 0x7af60
+  __AUTH_CONST.__objc_const: 0x7af80
   __AUTH_CONST.__objc_arrayobj: 0x1f08
   __AUTH_CONST.__objc_intobj: 0x43c8
   __AUTH_CONST.__objc_doubleobj: 0x3c0
   __AUTH_CONST.__objc_dictobj: 0x118
   __AUTH.__objc_data: 0x19b20
   __AUTH.__data: 0x1c0
-  __DATA.__objc_ivar: 0x50bc
+  __DATA.__objc_ivar: 0x50c0
   __DATA.__data: 0x77b8
   __DATA.__common: 0x24
   __DATA.__bss: 0x800

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 33138
-  Symbols:   66355
-  CStrings:  34377
+  Functions: 33142
+  Symbols:   66360
+  CStrings:  34382
 
Symbols:
+ -[HDDatabase _protectedDataQueue_handleSpringboardLockoutNotification]
+ -[HDDatabase unitTest_triggerSpringboardLockout]
+ OBJC_IVAR_$_HDDatabase._protectedDataLock_protectedDataState
+ OBJC_IVAR_$_HDDatabase._springboardLockoutToken
+ ___48-[HDDatabase unitTest_triggerSpringboardLockout]_block_invoke
+ ___65-[HDDatabase _protectedDataQueue_beginObservingContentProtection]_block_invoke
+ ___block_descriptor_40_ea8_32w_e8_v12?0i8l
- GCC_except_table122
- OBJC_IVAR_$_HDDatabase._protectedDataState
CStrings:
+ "%{public}@: Received biolockout notification; flushing protected data"
+ "Ignoring invalid protection state transition (%{public}@ -> %{public}@)"
+ "_protectedDataLock_protectedDataState"
+ "_springboardLockoutToken"
+ "com.apple.springboard.lock-with-force-biolockout"
+ "unitTest_triggerSpringboardLockout"
- "_protectedDataState"
```
