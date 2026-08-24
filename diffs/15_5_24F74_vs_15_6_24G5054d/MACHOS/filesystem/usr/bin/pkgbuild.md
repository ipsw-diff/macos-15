## pkgbuild

> `/usr/bin/pkgbuild`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-860.0.0.0.0
+860.140.3.0.0
   __TEXT.__text: 0x5cb4
   __TEXT.__auth_stubs: 0x200
   __TEXT.__objc_stubs: 0x1ec0
   __TEXT.__objc_methlist: 0x62c
-  __TEXT.__const: 0x48
+  __TEXT.__const: 0x50
   __TEXT.__cstring: 0x14ca
   __TEXT.__objc_methname: 0x20c5
   __TEXT.__objc_classname: 0x5c
```
