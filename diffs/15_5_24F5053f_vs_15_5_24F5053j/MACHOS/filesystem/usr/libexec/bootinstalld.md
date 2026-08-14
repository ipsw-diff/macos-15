## bootinstalld

> `/usr/libexec/bootinstalld`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-658.0.0.0.0
-  __TEXT.__text: 0x4f2c
+659.0.0.0.0
+  __TEXT.__text: 0x4f48
   __TEXT.__auth_stubs: 0x2e0
-  __TEXT.__objc_stubs: 0xfa0
+  __TEXT.__objc_stubs: 0xf60
   __TEXT.__objc_methlist: 0x33c
   __TEXT.__cstring: 0x9fa
-  __TEXT.__objc_methname: 0xeea
+  __TEXT.__objc_methname: 0xecb
   __TEXT.__objc_classname: 0xad
   __TEXT.__objc_methtype: 0x310
   __TEXT.__const: 0x18
-  __TEXT.__gcc_except_tab: 0x260
+  __TEXT.__gcc_except_tab: 0x268
   __TEXT.__unwind_info: 0x180
   __DATA_CONST.__auth_got: 0x180
   __DATA_CONST.__got: 0x138

   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x10
   __DATA.__objc_const: 0x538
-  __DATA.__objc_selrefs: 0x500
+  __DATA.__objc_selrefs: 0x4f0
   __DATA.__objc_ivar: 0x10
   __DATA.__objc_data: 0xf0
   __DATA.__data: 0x180

   - /usr/lib/libobjc.A.dylib
   Functions: 67
   Symbols:   94
-  CStrings:  288
+  CStrings:  286
 
Functions:
~ sub_100003380 : 448 -> 496
~ sub_100003c50 -> sub_100003c80 : 1736 -> 1716
CStrings:
- "keyEnumerator"
- "objectEnumerator"
```
