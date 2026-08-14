## launchd

> `/sbin/launchd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__dof_launchd`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2894.120.16.0.1
+2894.120.17.0.0
   __TEXT.__text: 0x51c2c
   __TEXT.__auth_stubs: 0x1ed0
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x1f4
   __TEXT.__const: 0x2e0
-  __TEXT.__cstring: 0x156c0
+  __TEXT.__cstring: 0x156b8
   __TEXT.__launchd: 0x1
   __TEXT.__objc_methname: 0x8
   __TEXT.__objc_classname: 0x1ba
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Thu Apr  3 23:55:40 PDT 2025; root:libxpc_executables-2894.120.17~72/launchd/RELEASE_ARM64E"
+ "Darwin Bootstrapper Version 7.0.0: Thu Apr  3 23:55:40 PDT 2025; root:libxpc_executables-2894.120.17~72/launchd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Fri Mar 21 19:16:02 PDT 2025; root:libxpc_executables-2894.120.16.0.1~22/launchd/RELEASE_ARM64E"
- "Darwin Bootstrapper Version 7.0.0: Fri Mar 21 19:16:02 PDT 2025; root:libxpc_executables-2894.120.16.0.1~22/launchd/RELEASE_ARM64E"
```
