## launchctl

> `/bin/launchctl`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-2894.140.11.0.0
-  __TEXT.__text: 0xdec0
+2894.140.11.0.1
+  __TEXT.__text: 0xde98
   __TEXT.__auth_stubs: 0xc70
   __TEXT.__const: 0x1a0
-  __TEXT.__cstring: 0x5e89
+  __TEXT.__cstring: 0x5e79
   __TEXT.__objc_classname: 0x1
   __TEXT.__launchctl: 0x1
   __TEXT.__oslogstring: 0x19

   - /usr/lib/libobjc.A.dylib
   Functions: 150
   Symbols:   227
-  CStrings:  752
+  CStrings:  751
 
Functions:
~ sub_100004e28 : 8316 -> 8276
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Control Interface Version 7.0.0: Sun Jul  6 18:50:10 PDT 2025; root:libxpc_executables-2894.140.11.0.1~19/launchctl/RELEASE_ARM64E"
+ "Darwin Bootstrapper Control Interface Version 7.0.0: Sun Jul  6 18:50:10 PDT 2025; root:libxpc_executables-2894.140.11.0.1~19/launchctl/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Control Interface Version 7.0.0: Sun Jun 22 22:07:29 PDT 2025; root:libxpc_executables-2894.140.11~35/launchctl/RELEASE_ARM64E"
- "Darwin Bootstrapper Control Interface Version 7.0.0: Sun Jun 22 22:07:29 PDT 2025; root:libxpc_executables-2894.140.11~35/launchctl/RELEASE_ARM64E"
- "shutdown-on-clean = %d\n"
```
