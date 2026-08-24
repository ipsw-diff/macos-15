## nfcd

> `/usr/libexec/nfcd`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-355.4.0.0.0
-  __TEXT.__text: 0x1e7af0
+356.2.0.0.0
+  __TEXT.__text: 0x1e7c2c
   __TEXT.__auth_stubs: 0x1350
-  __TEXT.__objc_stubs: 0xa340
-  __TEXT.__objc_methlist: 0x7300
-  __TEXT.__const: 0x1090
+  __TEXT.__objc_stubs: 0xa360
+  __TEXT.__objc_methlist: 0x7310
+  __TEXT.__const: 0x1130
   __TEXT.__dlopen_cstrs: 0x70
   __TEXT.__oslogstring: 0x1cc7b
-  __TEXT.__cstring: 0x25799
+  __TEXT.__cstring: 0x257ad
   __TEXT.__objc_classname: 0x1461
-  __TEXT.__objc_methname: 0x130c6
+  __TEXT.__objc_methname: 0x130ee
   __TEXT.__objc_methtype: 0x3c7e
   __TEXT.__gcc_except_tab: 0x56a4
   __TEXT.__unwind_info: 0x2670

   __DATA_CONST.__objc_arrayobj: 0x120
   __DATA_CONST.__objc_dictobj: 0xbe0
   __DATA.__objc_const: 0xefa8
-  __DATA.__objc_selrefs: 0x4568
+  __DATA.__objc_selrefs: 0x4570
   __DATA.__objc_ivar: 0xc28
   __DATA.__objc_data: 0x2c10
   __DATA.__data: 0x1df0

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libnfshared.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3272
+  Functions: 3273
   Symbols:   431
-  CStrings:  8040
+  CStrings:  8041
 
CStrings:
+ "NFCD built from (B&I) Stockholm_Base-356.2"
+ "_wildcardPollSystemCodeForTag:outError:"
- "NFCD built from (B&I) Stockholm_Base-355.4"
```
