## smd

> `/usr/libexec/smd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2894.120.17.0.0
-  __TEXT.__text: 0x11dbc
+2894.121.3.0.0
+  __TEXT.__text: 0x11dfc
   __TEXT.__auth_stubs: 0xc40
   __TEXT.__objc_stubs: 0x13c0
   __TEXT.__objc_methlist: 0x9a0

   __TEXT.__oslogstring: 0x18df
   __TEXT.__objc_classname: 0x193
   __TEXT.__objc_methtype: 0x9f0
-  __TEXT.__objc_methname: 0x13ba
-  __TEXT.__cstring: 0x11bd
+  __TEXT.__objc_methname: 0x13d7
+  __TEXT.__cstring: 0x11b3
   __TEXT.__gcc_except_tab: 0x308
   __TEXT.__unwind_info: 0x440
   __DATA_CONST.__auth_got: 0x630
Functions:
~ sub_10000a424 : 428 -> 492
CStrings:
+ "@(#)VERSION:Darwin Privileged Tool Bootstrapper Version 2.0.0: Tue Apr 22 20:50:41 PDT 2025; root:libxpc_executables-2894.121.3~4/smd/RELEASE_ARM64E"
+ "Contents"
+ "Darwin Privileged Tool Bootstrapper Version 2.0.0: Tue Apr 22 20:50:41 PDT 2025; root:libxpc_executables-2894.121.3~4/smd/RELEASE_ARM64E"
+ "URLByAppendingPathComponent:isDirectory:"
+ "dataWithContentsOfURL:"
- "%s/Contents/%s"
- "@(#)VERSION:Darwin Privileged Tool Bootstrapper Version 2.0.0: Thu Apr  3 23:58:13 PDT 2025; root:libxpc_executables-2894.120.17~72/smd/RELEASE_ARM64E"
- "Darwin Privileged Tool Bootstrapper Version 2.0.0: Thu Apr  3 23:58:13 PDT 2025; root:libxpc_executables-2894.120.17~72/smd/RELEASE_ARM64E"
- "UTF8String"
- "dataWithContentsOfFile:"
```
