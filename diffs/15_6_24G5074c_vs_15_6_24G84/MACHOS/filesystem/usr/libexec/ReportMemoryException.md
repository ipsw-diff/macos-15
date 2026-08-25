## ReportMemoryException

> `/usr/libexec/ReportMemoryException`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

-281.100.5.0.0
-  __TEXT.__text: 0x8bdc
+281.140.2.0.0
+  __TEXT.__text: 0x8c34
   __TEXT.__auth_stubs: 0x5d0
   __TEXT.__objc_stubs: 0xda0
   __TEXT.__objc_methlist: 0x14
Functions:
~ sub_1000074b0 : 2072 -> 2156
~ sub_100008638 -> sub_10000868c : 56 -> 60
```
