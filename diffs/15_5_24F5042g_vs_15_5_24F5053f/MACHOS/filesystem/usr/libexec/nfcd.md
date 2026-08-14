## nfcd

> `/usr/libexec/nfcd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-355.1.0.0.0
-  __TEXT.__text: 0x1e8b28
+355.2.1.0.0
+  __TEXT.__text: 0x1e8bb0
   __TEXT.__auth_stubs: 0x1350
   __TEXT.__objc_stubs: 0xa300
   __TEXT.__objc_methlist: 0x7300
   __TEXT.__const: 0x1090
   __TEXT.__dlopen_cstrs: 0x70
   __TEXT.__oslogstring: 0x1cc7b
-  __TEXT.__cstring: 0x257aa
+  __TEXT.__cstring: 0x257ac
   __TEXT.__objc_classname: 0x1461
   __TEXT.__objc_methname: 0x13093
   __TEXT.__objc_methtype: 0x3c7e

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x140
   __DATA_CONST.__objc_superrefs: 0x2f8
-  __DATA_CONST.__objc_intobj: 0x5610
+  __DATA_CONST.__objc_intobj: 0x55f8
   __DATA_CONST.__objc_arraydata: 0x1a10
   __DATA_CONST.__objc_arrayobj: 0x120
   __DATA_CONST.__objc_dictobj: 0xbe0

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libnfshared.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3271
+  Functions: 3272
   Symbols:   430
   CStrings:  8039
 
CStrings:
+ "NFCD built from (B&I) Stockholm_Base-355.2.1"
- "NFCD built from (B&I) Stockholm_Base-355.1"
```
