## nfcd

> `/usr/libexec/nfcd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-355.2.1.0.0
-  __TEXT.__text: 0x1e8bb0
+355.3.0.0.0
+  __TEXT.__text: 0x1e8bbc
   __TEXT.__auth_stubs: 0x1350
   __TEXT.__objc_stubs: 0xa300
   __TEXT.__objc_methlist: 0x7300
   __TEXT.__const: 0x1090
   __TEXT.__dlopen_cstrs: 0x70
   __TEXT.__oslogstring: 0x1cc7b
-  __TEXT.__cstring: 0x257ac
+  __TEXT.__cstring: 0x257aa
   __TEXT.__objc_classname: 0x1461
   __TEXT.__objc_methname: 0x13093
   __TEXT.__objc_methtype: 0x3c7e
Functions:
~ sub_10016ae94 : 3656 -> 3668
CStrings:
+ "NFCD built from (B&I) Stockholm_Base-355.3"
- "NFCD built from (B&I) Stockholm_Base-355.2.1"
```
