## smd

> `/usr/libexec/smd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2894.140.10.0.0
-  __TEXT.__text: 0x11dfc
+2894.140.11.0.0
+  __TEXT.__text: 0x11e1c
   __TEXT.__auth_stubs: 0xc40
-  __TEXT.__objc_stubs: 0x13c0
-  __TEXT.__objc_methlist: 0x9a0
+  __TEXT.__objc_stubs: 0x1440
+  __TEXT.__objc_methlist: 0x990
   __TEXT.__const: 0x118
-  __TEXT.__oslogstring: 0x18df
+  __TEXT.__oslogstring: 0x18c7
   __TEXT.__objc_classname: 0x193
-  __TEXT.__objc_methtype: 0x9f0
-  __TEXT.__objc_methname: 0x13d7
-  __TEXT.__cstring: 0x11bc
-  __TEXT.__gcc_except_tab: 0x308
+  __TEXT.__objc_methtype: 0x9cc
+  __TEXT.__objc_methname: 0x13d9
+  __TEXT.__cstring: 0x11f6
+  __TEXT.__gcc_except_tab: 0x31c
   __TEXT.__unwind_info: 0x440
   __DATA_CONST.__auth_got: 0x630
   __DATA_CONST.__got: 0x110

   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x38
-  __DATA.__objc_const: 0xe48
-  __DATA.__objc_selrefs: 0x5b8
+  __DATA.__objc_const: 0xe40
+  __DATA.__objc_selrefs: 0x5d8
   __DATA.__objc_ivar: 0x28
   __DATA.__objc_data: 0x410
   __DATA.__data: 0x260

   - /usr/lib/libobjc.A.dylib
   Functions: 396
   Symbols:   240
-  CStrings:  663
+  CStrings:  667
 
CStrings:
+ "/Library/LaunchDaemons/"
+ "@(#)VERSION:Darwin Privileged Tool Bootstrapper Version 2.0.0: Sun Jun 22 22:07:13 PDT 2025; root:libxpc_executables-2894.140.11~35/smd/RELEASE_ARM64E"
+ "Caller not xpcproxy"
+ "Darwin Privileged Tool Bootstrapper Version 2.0.0: Sun Jun 22 22:07:13 PDT 2025; root:libxpc_executables-2894.140.11~35/smd/RELEASE_ARM64E"
+ "absoluteURL"
+ "com.apple.private.xpc.is.xpcproxy"
+ "count"
+ "hasPrefix:"
+ "pathComponents"
- "@(#)VERSION:Darwin Privileged Tool Bootstrapper Version 2.0.0: Tue Jun  3 03:44:22 PDT 2025; root:libxpc_executables-2894.140.10~69/smd/RELEASE_ARM64E"
- "B48@0:8^q16@\"NSURL\"24@\"NSURL\"32^@40"
- "Darwin Privileged Tool Bootstrapper Version 2.0.0: Tue Jun  3 03:44:22 PDT 2025; root:libxpc_executables-2894.140.10~69/smd/RELEASE_ARM64E"
- "failed to determine path of legacy item: %@"
- "initFileURLWithPath:isDirectory:relativeToURL:"
```
