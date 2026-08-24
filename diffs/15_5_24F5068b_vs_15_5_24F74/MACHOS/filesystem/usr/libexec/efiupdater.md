## efiupdater

> `/usr/libexec/efiupdater`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

   __TEXT.__text: 0x2c54
   __TEXT.__auth_stubs: 0x480
   __TEXT.__objc_stubs: 0x420
-  __TEXT.__const: 0x27a
+  __TEXT.__const: 0x272
   __TEXT.__gcc_except_tab: 0x28
   __TEXT.__cstring: 0x9d9
   __TEXT.__objc_methname: 0x2ba
CStrings:
+ "efiupdater 32~9419 (Official), built 2025-04-18T21:42:24-0700"
- "efiupdater 32~9436 (Official), built 2025-04-20T03:01:30-0700"
```
