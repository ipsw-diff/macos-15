## smd

> `/usr/libexec/smd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2894.140.11.0.1
+2894.140.12.0.0
   __TEXT.__text: 0x11e1c
   __TEXT.__auth_stubs: 0xc40
   __TEXT.__objc_stubs: 0x1440
   __TEXT.__objc_methlist: 0x990
-  __TEXT.__const: 0x120
+  __TEXT.__const: 0x118
   __TEXT.__oslogstring: 0x18c7
   __TEXT.__objc_classname: 0x193
   __TEXT.__objc_methtype: 0x9cc
   __TEXT.__objc_methname: 0x13d9
-  __TEXT.__cstring: 0x11fe
+  __TEXT.__cstring: 0x11f6
   __TEXT.__gcc_except_tab: 0x31c
   __TEXT.__unwind_info: 0x440
   __DATA_CONST.__auth_got: 0x630
CStrings:
+ "@(#)VERSION:Darwin Privileged Tool Bootstrapper Version 2.0.0: Fri Jul 11 20:01:39 PDT 2025; root:libxpc_executables-2894.140.12~26/smd/RELEASE_ARM64E"
+ "Darwin Privileged Tool Bootstrapper Version 2.0.0: Fri Jul 11 20:01:39 PDT 2025; root:libxpc_executables-2894.140.12~26/smd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Privileged Tool Bootstrapper Version 2.0.0: Sun Jul  6 18:49:54 PDT 2025; root:libxpc_executables-2894.140.11.0.1~19/smd/RELEASE_ARM64E"
- "Darwin Privileged Tool Bootstrapper Version 2.0.0: Sun Jul  6 18:49:54 PDT 2025; root:libxpc_executables-2894.140.11.0.1~19/smd/RELEASE_ARM64E"
```
