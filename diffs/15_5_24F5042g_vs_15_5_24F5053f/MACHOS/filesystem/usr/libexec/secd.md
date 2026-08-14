## secd

> `/usr/libexec/secd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-61439.120.15.0.0
+61439.120.22.0.0
   __TEXT.__text: 0x261768
   __TEXT.__auth_stubs: 0x3760
   __TEXT.__objc_stubs: 0x1aca0
   __TEXT.__objc_methlist: 0x1467c
   __TEXT.__const: 0x3ec
   __TEXT.__cstring: 0x1f0ab
-  __TEXT.__oslogstring: 0x28ee9
+  __TEXT.__oslogstring: 0x28ef8
   __TEXT.__dlopen_cstrs: 0x172
   __TEXT.__gcc_except_tab: 0xad38
   __TEXT.__objc_classname: 0x2271
CStrings:
+ "set a new persistentref UUID for item %{private}@, error:%@"
- "set a new persistentref UUID for item %@: %@"
```
