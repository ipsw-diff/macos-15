## dasd

> `/usr/libexec/dasd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-1856.120.11.0.0
-  __TEXT.__text: 0xe1eb4
+1856.120.11.0.1
+  __TEXT.__text: 0xe1f90
   __TEXT.__auth_stubs: 0xf50
   __TEXT.__objc_stubs: 0x11de0
   __TEXT.__objc_methlist: 0xd5a8

   __TEXT.__oslogstring: 0xbf8e
   __TEXT.__objc_classname: 0x13bf
   __TEXT.__objc_methtype: 0x2536
-  __TEXT.__gcc_except_tab: 0x36fc
+  __TEXT.__gcc_except_tab: 0x37a4
   __TEXT.__dlopen_cstrs: 0x1f8
-  __TEXT.__unwind_info: 0x3040
+  __TEXT.__unwind_info: 0x3048
   __DATA_CONST.__auth_got: 0x7b8
   __DATA_CONST.__got: 0x7a8
   __DATA_CONST.__auth_ptr: 0x8
Functions:
~ sub_100035e34 : 2216 -> 2436
```
