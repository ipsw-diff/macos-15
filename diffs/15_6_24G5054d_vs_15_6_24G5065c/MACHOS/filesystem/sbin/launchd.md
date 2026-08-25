## launchd

> `/sbin/launchd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__dof_launchd`

```diff

-2894.140.10.0.0
+2894.140.11.0.0
   __TEXT.__text: 0x51b74
   __TEXT.__auth_stubs: 0x1ed0
   __TEXT.__init_offsets: 0x4
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Sun Jun 22 22:05:17 PDT 2025; root:libxpc_executables-2894.140.11~35/launchd/RELEASE_ARM64E"
+ "Darwin Bootstrapper Version 7.0.0: Sun Jun 22 22:05:17 PDT 2025; root:libxpc_executables-2894.140.11~35/launchd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Tue Jun  3 03:42:14 PDT 2025; root:libxpc_executables-2894.140.10~69/launchd/RELEASE_ARM64E"
- "Darwin Bootstrapper Version 7.0.0: Tue Jun  3 03:42:14 PDT 2025; root:libxpc_executables-2894.140.10~69/launchd/RELEASE_ARM64E"
```
