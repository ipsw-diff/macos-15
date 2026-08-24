## transparencyd

> `/usr/libexec/transparencyd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-1218.120.15.0.0
-  __TEXT.__text: 0x2925a4
+1218.140.4.0.0
+  __TEXT.__text: 0x2925e8
   __TEXT.__auth_stubs: 0x2ce0
-  __TEXT.__objc_stubs: 0x1b820
+  __TEXT.__objc_stubs: 0x1b7e0
   __TEXT.__objc_methlist: 0x149e0
-  __TEXT.__cstring: 0x11fa2
+  __TEXT.__cstring: 0x11fbb
   __TEXT.__objc_classname: 0x2c24
   __TEXT.__objc_methname: 0x21aab
   __TEXT.__objc_methtype: 0x714b
-  __TEXT.__const: 0xa1f8
+  __TEXT.__const: 0xa678
   __TEXT.__gcc_except_tab: 0x4d78
   __TEXT.__oslogstring: 0x10bda
   __TEXT.__swift5_typeref: 0x2378

   __TEXT.__swift_as_entry: 0x110
   __TEXT.__swift_as_ret: 0xb8
   __TEXT.__swift5_protos: 0x14
-  __TEXT.__unwind_info: 0xa140
+  __TEXT.__unwind_info: 0xa148
   __TEXT.__eh_frame: 0x4d88
   __DATA_CONST.__auth_got: 0x1680
   __DATA_CONST.__got: 0xe80
-  __DATA_CONST.__auth_ptr: 0x610
+  __DATA_CONST.__auth_ptr: 0x5e8
   __DATA_CONST.__const: 0x159a0
-  __DATA_CONST.__cfstring: 0xdc00
+  __DATA_CONST.__cfstring: 0xdc20
   __DATA_CONST.__objc_classlist: 0xc90
   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x3b0

   __DATA.__objc_selrefs: 0x81e8
   __DATA.__objc_ivar: 0x1078
   __DATA.__objc_data: 0x9000
-  __DATA.__data: 0xa530
+  __DATA.__data: 0xa0d0
   __DATA.__thread_vars: 0x48
   __DATA.__thread_bss: 0xc
   __DATA.__bss: 0x114a8

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 15955
+  Functions: 15956
   Symbols:   1349
-  CStrings:  10806
+  CStrings:  10807
 
CStrings:
+ "idms-fetch"
```
