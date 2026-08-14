## diskimagesiod

> `/usr/libexec/diskimagesiod`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-385.120.3.0.0
-  __TEXT.__text: 0x16d2d4
+385.120.4.0.0
+  __TEXT.__text: 0x16e5f0
   __TEXT.__auth_stubs: 0x2070
   __TEXT.__objc_stubs: 0x5940
   __TEXT.__objc_methlist: 0x31b4
-  __TEXT.__gcc_except_tab: 0x13af8
-  __TEXT.__const: 0xcd8c
-  __TEXT.__cstring: 0xeffb
+  __TEXT.__gcc_except_tab: 0x13ba0
+  __TEXT.__const: 0xce4c
+  __TEXT.__cstring: 0xf00d
   __TEXT.__oslogstring: 0x2693
   __TEXT.__objc_methname: 0x6706
   __TEXT.__objc_classname: 0x5c0

   __TEXT.__swift5_fieldmd: 0x10
   __TEXT.__swift5_types: 0x4
   __TEXT.__ustring: 0x13c
-  __TEXT.__unwind_info: 0xa0b8
+  __TEXT.__unwind_info: 0xa150
   __TEXT.__eh_frame: 0x158
   __DATA_CONST.__auth_got: 0x1050
   __DATA_CONST.__got: 0x5b8
   __DATA_CONST.__auth_ptr: 0x30
-  __DATA_CONST.__const: 0x2a4e8
+  __DATA_CONST.__const: 0x2a928
   __DATA_CONST.__cfstring: 0x3f00
   __DATA_CONST.__objc_classlist: 0x218
   __DATA_CONST.__objc_catlist: 0x8

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 8298
+  Functions: 8330
   Symbols:   743
-  CStrings:  3447
+  CStrings:  3449
 
CStrings:
+ " (errno "
+ " updated from "
+ "), reading from backup"
+ "Failed opening "
- " and update original, "
- ", reading from backup"
```
