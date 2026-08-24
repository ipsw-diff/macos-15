## gamed

> `/usr/libexec/gamed`

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
- `__DATA_CONST.__cfstring`
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

-819.4.46.0.0
-  __TEXT.__text: 0x3073bc
+819.4.47.0.0
+  __TEXT.__text: 0x307494
   __TEXT.__auth_stubs: 0x34e0
   __TEXT.__objc_stubs: 0x19300
   __TEXT.__objc_methlist: 0xd6b4
-  __TEXT.__const: 0x69b58
+  __TEXT.__const: 0x6a3f8
   __TEXT.__objc_classname: 0x1d64
-  __TEXT.__oslogstring: 0x159de
-  __TEXT.__cstring: 0x1b12f
+  __TEXT.__oslogstring: 0x15a2e
+  __TEXT.__cstring: 0x1b1af
   __TEXT.__objc_methname: 0x20d97
   __TEXT.__objc_methtype: 0x5b15
   __TEXT.__gcc_except_tab: 0x30c0

   __TEXT.__swift_as_entry: 0x31c
   __TEXT.__swift_as_ret: 0x340
   __TEXT.__swift5_mpenum: 0x1c
-  __TEXT.__unwind_info: 0x7ed0
+  __TEXT.__unwind_info: 0x7ec8
   __TEXT.__eh_frame: 0x7ea8
   __DATA_CONST.__auth_got: 0x1a88
   __DATA_CONST.__got: 0x1b48
-  __DATA_CONST.__auth_ptr: 0x8a8
+  __DATA_CONST.__auth_ptr: 0x8a0
   __DATA_CONST.__const: 0x18ec8
   __DATA_CONST.__cfstring: 0xbe40
   __DATA_CONST.__objc_classlist: 0x918

   __DATA.__objc_selrefs: 0x7c50
   __DATA.__objc_ivar: 0x714
   __DATA.__objc_data: 0x6ab8
-  __DATA.__data: 0x47a0
+  __DATA.__data: 0x3f10
   __DATA.__bss: 0x4e00
   __DATA.__common: 0xa84
   - /AppleInternal/Library/Frameworks/TapToRadarKit.framework/Versions/A/TapToRadarKit

   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 10462
   Symbols:   1951
-  CStrings:  9972
+  CStrings:  9973
 
Functions:
~ sub_10011d6bc : 240 -> 456
CStrings:
+ "For bundleID: %@ we are returning playerInternal with ID: %@ in auth reponse"
```
