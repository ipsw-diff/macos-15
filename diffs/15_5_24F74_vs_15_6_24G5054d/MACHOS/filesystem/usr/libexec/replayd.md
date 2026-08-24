## replayd

> `/usr/libexec/replayd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-620.2.1.0.0
-  __TEXT.__text: 0xb2270
+630.4.2.0.0
+  __TEXT.__text: 0xb236c
   __TEXT.__auth_stubs: 0x1980
   __TEXT.__objc_stubs: 0xc720
   __TEXT.__objc_methlist: 0x5f0c
   __TEXT.__const: 0x460
   __TEXT.__oslogstring: 0xfc13
-  __TEXT.__cstring: 0x12d22
+  __TEXT.__cstring: 0x12d4f
   __TEXT.__objc_classname: 0x9e7
   __TEXT.__objc_methname: 0x123ab
   __TEXT.__objc_methtype: 0x3651

   __DATA_CONST.__got: 0xa58
   __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__const: 0x2180
-  __DATA_CONST.__cfstring: 0x5340
+  __DATA_CONST.__cfstring: 0x5360
   __DATA_CONST.__objc_classlist: 0x280
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0xd8

   - /usr/lib/libobjc.A.dylib
   Functions: 2991
   Symbols:   753
-  CStrings:  6075
+  CStrings:  6076
 
Functions:
~ sub_100083764 : 1048 -> 1140
~ sub_100083cd4 -> sub_100083d30 : 396 -> 488
~ sub_100084084 -> sub_10008413c : 208 -> 260
~ sub_100091594 -> sub_100091680 : 344 -> 352
~ sub_1000b12c8 -> sub_1000b13bc : 184 -> 192
CStrings:
+ "SCContentSharingPickerInfoPresentingBundleID"
```
