## smd

> `/usr/libexec/smd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA.__data`

```diff

-2894.121.3.0.0
+2894.140.10.0.0
   __TEXT.__text: 0x11dfc
   __TEXT.__auth_stubs: 0xc40
   __TEXT.__objc_stubs: 0x13c0

   __TEXT.__objc_classname: 0x193
   __TEXT.__objc_methtype: 0x9f0
   __TEXT.__objc_methname: 0x13d7
-  __TEXT.__cstring: 0x11b3
+  __TEXT.__cstring: 0x11bc
   __TEXT.__gcc_except_tab: 0x308
   __TEXT.__unwind_info: 0x440
   __DATA_CONST.__auth_got: 0x630
CStrings:
+ "@(#)VERSION:Darwin Privileged Tool Bootstrapper Version 2.0.0: Tue Jun  3 03:44:22 PDT 2025; root:libxpc_executables-2894.140.10~69/smd/RELEASE_ARM64E"
+ "Darwin Privileged Tool Bootstrapper Version 2.0.0: Tue Jun  3 03:44:22 PDT 2025; root:libxpc_executables-2894.140.10~69/smd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Privileged Tool Bootstrapper Version 2.0.0: Tue Apr 22 20:06:54 PDT 2025; root:libxpc_executables-2894.121.3~2/smd/RELEASE_ARM64E"
- "Darwin Privileged Tool Bootstrapper Version 2.0.0: Tue Apr 22 20:06:54 PDT 2025; root:libxpc_executables-2894.121.3~2/smd/RELEASE_ARM64E"
```
