## textcontextd

> `/usr/libexec/textcontextd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

   __TEXT.__text: 0x4778
   __TEXT.__auth_stubs: 0x560
   __TEXT.__objc_methlist: 0x23c
-  __TEXT.__const: 0xfa
+  __TEXT.__const: 0x18a
   __TEXT.__objc_methname: 0x32c
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constg_swiftt: 0x13c

   __DATA.__objc_const: 0x708
   __DATA.__objc_selrefs: 0x148
   __DATA.__objc_data: 0x290
-  __DATA.__data: 0x270
+  __DATA.__data: 0x1e0
   __DATA.__common: 0x20
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
```
