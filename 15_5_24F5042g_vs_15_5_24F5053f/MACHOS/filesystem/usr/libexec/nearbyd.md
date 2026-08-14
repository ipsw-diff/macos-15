## nearbyd

> `/usr/libexec/nearbyd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-466.0.1.0.0
-  __TEXT.__text: 0x41c024
-  __TEXT.__auth_stubs: 0x2300
-  __TEXT.__objc_stubs: 0x10120
+466.0.3.0.0
+  __TEXT.__text: 0x41b580
+  __TEXT.__auth_stubs: 0x2310
+  __TEXT.__objc_stubs: 0x10140
   __TEXT.__init_offsets: 0x288
-  __TEXT.__objc_methlist: 0xb394
-  __TEXT.__gcc_except_tab: 0x43d80
+  __TEXT.__objc_methlist: 0xb39c
+  __TEXT.__gcc_except_tab: 0x43d90
   __TEXT.__const: 0x2d5618
-  __TEXT.__cstring: 0x301f4
-  __TEXT.__objc_methname: 0x1870c
-  __TEXT.__oslogstring: 0x47f99
+  __TEXT.__cstring: 0x30260
+  __TEXT.__objc_methname: 0x18765
+  __TEXT.__oslogstring: 0x47fc2
   __TEXT.__objc_classname: 0x177e
   __TEXT.__objc_methtype: 0x1abac
   __TEXT.__constg_swiftt: 0x80

   __TEXT.__swift5_reflstr: 0x13
   __TEXT.__swift5_fieldmd: 0x28
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x15fb0
+  __TEXT.__unwind_info: 0x16100
   __TEXT.__eh_frame: 0x38
-  __DATA_CONST.__auth_got: 0x1198
+  __DATA_CONST.__auth_got: 0x11a0
   __DATA_CONST.__got: 0x7d0
-  __DATA_CONST.__auth_ptr: 0x50
-  __DATA_CONST.__const: 0x1fbb0
-  __DATA_CONST.__cfstring: 0x11ba0
+  __DATA_CONST.__auth_ptr: 0x58
+  __DATA_CONST.__const: 0x1fba0
+  __DATA_CONST.__cfstring: 0x11c00
   __DATA_CONST.__objc_classlist: 0x4a0
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x220

   __DATA_CONST.__objc_superrefs: 0x440
   __DATA_CONST.__objc_arraydata: 0x3b0
   __DATA_CONST.__objc_arrayobj: 0x198
-  __DATA_CONST.__objc_intobj: 0x5b8
+  __DATA_CONST.__objc_intobj: 0x5d0
   __DATA_CONST.__objc_dictobj: 0xa0
-  __DATA.__objc_const: 0x13a88
-  __DATA.__objc_selrefs: 0x4dd0
-  __DATA.__objc_ivar: 0x12fc
+  __DATA.__objc_const: 0x13ac8
+  __DATA.__objc_selrefs: 0x4dd8
+  __DATA.__objc_ivar: 0x1304
   __DATA.__objc_data: 0x2ef0
   __DATA.__data: 0x2d24
   __DATA.__bss: 0xbc40

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 18082
-  Symbols:   841
-  CStrings:  15464
+  Functions: 18053
+  Symbols:   842
+  CStrings:  15471
 
Symbols:
+ _MGGetBoolAnswer
CStrings:
+ "#ni-ca,[%@] appPresentedLiveActivity [s]"
+ "DeviceProximityCapability"
+ "UWB not supported"
+ "_isExtendedDistanceMeasurementEnabled"
+ "_isLiveActivityEverActive"
+ "appPresentedLiveActivity"
+ "didReceiveAlishaUpdate_block_invoke"
+ "isLiveActivityActive"
- "didReceiveAlishaUpdate"
```
