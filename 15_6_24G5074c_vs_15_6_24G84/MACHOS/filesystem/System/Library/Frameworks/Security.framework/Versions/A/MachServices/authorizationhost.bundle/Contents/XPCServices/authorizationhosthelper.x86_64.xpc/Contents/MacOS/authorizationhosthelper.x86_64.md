## authorizationhosthelper.x86_64

> `/System/Library/Frameworks/Security.framework/Versions/A/MachServices/authorizationhost.bundle/Contents/XPCServices/authorizationhosthelper.x86_64.xpc/Contents/MacOS/authorizationhosthelper.x86_64`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-55579.140.3.0.0
-  __TEXT.__text: 0x83f7
-  __TEXT.__stubs: 0x2c4
+55579.140.3.0.1
+  __TEXT.__text: 0x8777
+  __TEXT.__stubs: 0x2d0
   __TEXT.__const: 0x70
-  __TEXT.__objc_methname: 0xd5a
-  __TEXT.__cstring: 0x627
+  __TEXT.__objc_methname: 0xd69
+  __TEXT.__cstring: 0x639
   __TEXT.__objc_classname: 0x121
   __TEXT.__objc_methtype: 0x6a6
-  __TEXT.__oslogstring: 0xc67
-  __TEXT.__gcc_except_tab: 0xac
+  __TEXT.__oslogstring: 0xcf7
+  __TEXT.__gcc_except_tab: 0xa4
   __TEXT.__dlopen_cstrs: 0x5d
-  __TEXT.__unwind_info: 0x2a8
-  __DATA_CONST.__got: 0x4f0
+  __TEXT.__unwind_info: 0x2c8
+  __TEXT.__eh_frame: 0x58
+  __DATA_CONST.__got: 0x508
   __DATA_CONST.__const: 0x370
   __DATA_CONST.__cfstring: 0x2c0
   __DATA_CONST.__objc_classlist: 0x68
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x40
-  __DATA.__objc_const: 0x1548
-  __DATA.__objc_selrefs: 0x3d0
+  __DATA.__objc_const: 0x1568
+  __DATA.__objc_selrefs: 0x3d8
   __DATA.__objc_ivar: 0xe0
   __DATA.__objc_data: 0x778
   __DATA.__data: 0xb1

   - /System/Library/Frameworks/SecurityInterface.framework/Versions/A/SecurityInterface
   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
+  - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 262
-  Symbols:   228
-  CStrings:  411
+  Functions: 268
+  Symbols:   231
+  CStrings:  417
 
Symbols:
+ ____chkstk_darwin
+ _audit_token_to_pid
+ _rootless_check_trusted
CStrings:
+ "Detected untrusted caller %s"
+ "Invalid connection parameter"
+ "Request: caller is trusted: %d (signature %d)"
+ "System Integrity Protection is not enabled"
+ "Unable to get the path from PID %d"
+ "Unapproved caller %{public}s, %{public}s may only be invoked by Apple software."
+ "authorizationhost"
+ "isPeerTrusted:"
- "Request: caller is trusted: %d"
- "Unapproved caller %{public}s, SecurityAgent and authorizationhost may only be invoked by Apple software."
```
