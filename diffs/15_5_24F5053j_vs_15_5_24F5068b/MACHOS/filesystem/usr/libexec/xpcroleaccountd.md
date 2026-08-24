## xpcroleaccountd

> `/usr/libexec/xpcroleaccountd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2894.120.17.0.0
-  __TEXT.__text: 0x3204
-  __TEXT.__auth_stubs: 0x5e0
+2894.121.3.0.0
+  __TEXT.__text: 0x3418
+  __TEXT.__auth_stubs: 0x600
   __TEXT.__objc_stubs: 0x60
-  __TEXT.__const: 0xa8
-  __TEXT.__cstring: 0x501
-  __TEXT.__oslogstring: 0x90c
+  __TEXT.__const: 0xa0
+  __TEXT.__cstring: 0x4fd
+  __TEXT.__gcc_except_tab: 0x21c
+  __TEXT.__oslogstring: 0x93e
   __TEXT.__objc_methname: 0x30
-  __TEXT.__unwind_info: 0x118
-  __DATA_CONST.__auth_got: 0x2f8
+  __TEXT.__unwind_info: 0x180
+  __DATA_CONST.__auth_got: 0x310
   __DATA_CONST.__got: 0x58
   __DATA_CONST.__const: 0xf0
   __DATA_CONST.__cfstring: 0xe0

   - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 76
-  Symbols:   110
-  CStrings:  83
+  Functions: 79
+  Symbols:   113
+  CStrings:  84
 
Symbols:
+ __Unwind_Resume
+ ___objc_personality_v0
+ _objc_terminate
CStrings:
+ "%s failed final check for RoleAccount entitlement"
+ "@(#)VERSION:Darwin Role Account Bootstrapper Version 1.0.0: Tue Apr 22 20:51:10 PDT 2025; root:libxpc_executables-2894.121.3~4/xpcroleaccountd/RELEASE_ARM64E"
+ "Darwin Role Account Bootstrapper Version 1.0.0: Tue Apr 22 20:51:10 PDT 2025; root:libxpc_executables-2894.121.3~4/xpcroleaccountd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Role Account Bootstrapper Version 1.0.0: Thu Apr  3 23:58:51 PDT 2025; root:libxpc_executables-2894.120.17~72/xpcroleaccountd/RELEASE_ARM64E"
- "Darwin Role Account Bootstrapper Version 1.0.0: Thu Apr  3 23:58:51 PDT 2025; root:libxpc_executables-2894.120.17~72/xpcroleaccountd/RELEASE_ARM64E"
```
