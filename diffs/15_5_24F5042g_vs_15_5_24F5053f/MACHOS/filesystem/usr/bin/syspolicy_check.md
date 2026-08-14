## syspolicy_check

> `/usr/bin/syspolicy_check`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__data`

```diff

-620.120.1.0.0
+620.120.4.0.0
   __TEXT.__text: 0x15d1c
   __TEXT.__auth_stubs: 0xc80
   __TEXT.__objc_stubs: 0xfe0

   __DATA_CONST.__objc_classlist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x30
+  __DATA_CONST.__objc_intobj: 0x48
   __DATA_CONST.__objc_arraydata: 0x3c8
   __DATA_CONST.__objc_arrayobj: 0x138
   __DATA_CONST.__objc_dupclass: 0x40
   __DATA_CONST.__objc_dictobj: 0xc8
-  __DATA_CONST.__objc_intobj: 0x18
   __DATA.__objc_const: 0x1260
   __DATA.__objc_selrefs: 0x630
   __DATA.__objc_ivar: 0x114
```
