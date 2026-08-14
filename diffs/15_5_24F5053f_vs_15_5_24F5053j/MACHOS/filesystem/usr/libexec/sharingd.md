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
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2060.60.22.0.0
-  __TEXT.__text: 0x63cc0c
+2060.60.31.0.0
+  __TEXT.__text: 0x63cc64
   __TEXT.__auth_stubs: 0x89d0
   __TEXT.__objc_stubs: 0x27180
   __TEXT.__objc_methlist: 0x1a38c
   __TEXT.__cstring: 0x35b0a
-  __TEXT.__objc_methname: 0x38b7f
+  __TEXT.__objc_methname: 0x38b7a
   __TEXT.__objc_classname: 0x25f7
   __TEXT.__objc_methtype: 0x83e1
   __TEXT.__const: 0x12e35
-  __TEXT.__oslogstring: 0x2dc89
+  __TEXT.__oslogstring: 0x2dcb9
   __TEXT.__gcc_except_tab: 0x2cec
   __TEXT.__ustring: 0x50
   __TEXT.__dlopen_cstrs: 0xb0

   __TEXT.__eh_frame: 0x20768
   __DATA_CONST.__auth_got: 0x44f8
   __DATA_CONST.__got: 0x2a78
-  __DATA_CONST.__auth_ptr: 0x1ab8
+  __DATA_CONST.__auth_ptr: 0x1c20
   __DATA_CONST.__const: 0x17548
   __DATA_CONST.__cfstring: 0x14200
   __DATA_CONST.__objc_classlist: 0xd18

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 23079
+  Functions: 23080
   Symbols:   3830
-  CStrings:  21668
+  CStrings:  21669
 
Functions:
~ sub_10012e7c4 : 412 -> 436
+ sub_1006280f0
CStrings:
+ "Data could not be converted to a UTF-8 string."
+ "initWithData:encoding:"
- "stringWithCString:encoding:"
```
