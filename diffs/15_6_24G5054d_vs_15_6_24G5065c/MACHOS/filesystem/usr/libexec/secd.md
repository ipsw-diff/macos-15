## secd

> `/usr/libexec/secd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-61439.140.8.0.0
+61439.140.10.0.0
   __TEXT.__text: 0x2622b8
   __TEXT.__auth_stubs: 0x3790
   __TEXT.__objc_stubs: 0x1ad00
   __TEXT.__objc_methlist: 0x146c4
-  __TEXT.__const: 0x3e4
+  __TEXT.__const: 0x3ec
   __TEXT.__cstring: 0x1f0e7
   __TEXT.__oslogstring: 0x29163
   __TEXT.__dlopen_cstrs: 0x172
```
