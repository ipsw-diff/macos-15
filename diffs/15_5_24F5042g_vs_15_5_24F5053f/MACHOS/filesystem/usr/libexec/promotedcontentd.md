## promotedcontentd

> `/usr/libexec/promotedcontentd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-555.48.0.0.0
-  __TEXT.__text: 0x2b04cc
+555.48.1.2.0
+  __TEXT.__text: 0x2b038c
   __TEXT.__auth_stubs: 0x33a0
   __TEXT.__objc_stubs: 0x17740
   __TEXT.__objc_methlist: 0x1487c
   __TEXT.__const: 0x6dbe8
   __TEXT.__objc_methname: 0x2416f
   __TEXT.__oslogstring: 0xd1a9
-  __TEXT.__cstring: 0x1222f
+  __TEXT.__cstring: 0x121ef
   __TEXT.__objc_classname: 0x25c0
   __TEXT.__objc_methtype: 0x4a1a
   __TEXT.__gcc_except_tab: 0x16bc

   __TEXT.__eh_frame: 0x2e18
   __DATA_CONST.__auth_got: 0x19e0
   __DATA_CONST.__got: 0xf68
-  __DATA_CONST.__auth_ptr: 0xbe8
+  __DATA_CONST.__auth_ptr: 0xbb8
   __DATA_CONST.__const: 0x14ad8
   __DATA_CONST.__cfstring: 0xe640
   __DATA_CONST.__objc_classlist: 0xd30

   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 9958
   Symbols:   2070
-  CStrings:  10517
+  CStrings:  10516
 
Functions:
~ sub_100163aa8 : 2608 -> 2288
CStrings:
- "Response Handler Error: Error received from server. Error: "
```
