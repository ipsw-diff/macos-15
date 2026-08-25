## security

> `/usr/bin/security`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__dof_security_`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-61439.140.10.0.0
+61439.140.10.0.1
   __TEXT.__text: 0x236a4
   __TEXT.__auth_stubs: 0x1f30
   __TEXT.__objc_stubs: 0x9e0
   __TEXT.__objc_methlist: 0x128
-  __TEXT.__const: 0x828
+  __TEXT.__const: 0x830
   __TEXT.__dlopen_cstrs: 0x10b
   __TEXT.__gcc_except_tab: 0xe00
   __TEXT.__cstring: 0xc24d
```
