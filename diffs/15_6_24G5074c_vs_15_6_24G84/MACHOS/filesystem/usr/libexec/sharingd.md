## sharingd

> `/usr/libexec/sharingd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2060.80.21.0.0
-  __TEXT.__text: 0x63d9c0
+2060.80.31.0.0
+  __TEXT.__text: 0x63d900
   __TEXT.__auth_stubs: 0x89d0
   __TEXT.__objc_stubs: 0x271e0
   __TEXT.__objc_methlist: 0x1a394
   __TEXT.__cstring: 0x35ca4
-  __TEXT.__objc_methname: 0x38bc3
+  __TEXT.__objc_methname: 0x38b7b
   __TEXT.__objc_classname: 0x25f7
   __TEXT.__objc_methtype: 0x83e1
   __TEXT.__const: 0x14eb1
-  __TEXT.__oslogstring: 0x2dcb9
+  __TEXT.__oslogstring: 0x2dc99
   __TEXT.__gcc_except_tab: 0x2cec
   __TEXT.__ustring: 0x50
   __TEXT.__dlopen_cstrs: 0xb0

   __TEXT.__eh_frame: 0x207f8
   __DATA_CONST.__auth_got: 0x44f8
   __DATA_CONST.__got: 0x2a78
-  __DATA_CONST.__auth_ptr: 0x1a10
+  __DATA_CONST.__auth_ptr: 0x1bb8
   __DATA_CONST.__const: 0x17708
   __DATA_CONST.__cfstring: 0x14220
   __DATA_CONST.__objc_classlist: 0xd18

   __DATA_CONST.__objc_dictobj: 0x15b8
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA.__objc_const: 0x32c28
-  __DATA.__objc_selrefs: 0xd708
+  __DATA.__objc_selrefs: 0xd6f0
   __DATA.__objc_ivar: 0x2488
   __DATA.__objc_data: 0x9590
   __DATA.__data: 0x15702

   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 23117
   Symbols:   3830
-  CStrings:  21679
+  CStrings:  21676
 
Functions:
~ sub_1004d5584 : 1504 -> 1312
CStrings:
+ "Failed to create auth tag: %s"
+ "Setting auth tag on %s to %s"
- "Failed to create temp auth tag: %s"
- "Setting temp auth tag on %s to %s"
- "nearbyInfoV2Flags"
- "setNearbyInfoV2Flags:"
- "setNearbyInfoV2TempAuthTagData:"
```
