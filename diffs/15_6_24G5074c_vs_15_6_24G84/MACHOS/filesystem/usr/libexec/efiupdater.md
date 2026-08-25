## efiupdater

> `/usr/libexec/efiupdater`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

   __TEXT.__objc_stubs: 0x420
   __TEXT.__const: 0x27a
   __TEXT.__gcc_except_tab: 0x28
-  __TEXT.__cstring: 0x9d9
+  __TEXT.__cstring: 0x9da
   __TEXT.__objc_methname: 0x2ba
   __TEXT.__unwind_info: 0xe0
   __DATA_CONST.__auth_got: 0x250
CStrings:
+ "efiupdater 32~10218 (Official), built 2025-07-11T19:13:28-0700"
- "efiupdater 32~9863 (Official), built 2025-06-03T02:42:05-0700"
```
