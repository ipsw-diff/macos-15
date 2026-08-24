## csfdiagnose

> `/usr/bin/csfdiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA.__objc_selrefs`

```diff

 301.22.5.5.0
   __TEXT.__text: 0x19958
   __TEXT.__auth_stubs: 0xae0
-  __TEXT.__const: 0x132e
+  __TEXT.__const: 0x135e
   __TEXT.__swift5_entry: 0x8
   __TEXT.__swift5_typeref: 0x4af
   __TEXT.__swift5_fieldmd: 0x5e0

   __DATA_CONST.__const: 0xcc0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA.__objc_selrefs: 0x60
-  __DATA.__data: 0x810
+  __DATA.__data: 0x7e0
   __DATA.__common: 0x1b0
   __DATA.__bss: 0x2b00
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
```
