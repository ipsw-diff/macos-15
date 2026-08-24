## launchd

> `/sbin/launchd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__dof_launchd`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`
- `__DATA.__os_assumes_log`

```diff

-2894.120.17.0.0
-  __TEXT.__text: 0x51c2c
+2894.121.3.0.0
+  __TEXT.__text: 0x51b80
   __TEXT.__auth_stubs: 0x1ed0
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x1f4
   __TEXT.__const: 0x2e0
-  __TEXT.__cstring: 0x156b8
+  __TEXT.__cstring: 0x156b4
   __TEXT.__launchd: 0x1
   __TEXT.__objc_methname: 0x8
   __TEXT.__objc_classname: 0x1ba
   __TEXT.__objc_methtype: 0x8
   __TEXT.__config: 0x3512
   __TEXT.__dof_launchd: 0x81d
-  __TEXT.__unwind_info: 0x1148
+  __TEXT.__unwind_info: 0x1150
   __DATA_CONST.__auth_got: 0xf68
   __DATA_CONST.__got: 0x188
   __DATA_CONST.__auth_ptr: 0x8

   - /usr/lib/libauditd.0.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1616
+  Functions: 1615
   Symbols:   548
   CStrings:  2669
 
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Tue Apr 22 20:48:37 PDT 2025; root:libxpc_executables-2894.121.3~4/launchd/RELEASE_ARM64E"
+ "Darwin Bootstrapper Version 7.0.0: Tue Apr 22 20:48:37 PDT 2025; root:libxpc_executables-2894.121.3~4/launchd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Thu Apr  3 23:55:40 PDT 2025; root:libxpc_executables-2894.120.17~72/launchd/RELEASE_ARM64E"
- "Darwin Bootstrapper Version 7.0.0: Thu Apr  3 23:55:40 PDT 2025; root:libxpc_executables-2894.120.17~72/launchd/RELEASE_ARM64E"
```
