## authorizationhosthelper.arm64

> `/System/Library/Frameworks/Security.framework/Versions/A/MachServices/authorizationhost.bundle/Contents/XPCServices/authorizationhosthelper.arm64.xpc/Contents/MacOS/authorizationhosthelper.arm64`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-55579.140.3.0.0
-  __TEXT.__text: 0x8654
-  __TEXT.__auth_stubs: 0x780
-  __TEXT.__objc_stubs: 0xec0
-  __TEXT.__objc_methlist: 0x71c
-  __TEXT.__const: 0xd0
-  __TEXT.__cstring: 0x626
+55579.140.3.0.1
+  __TEXT.__text: 0x898c
+  __TEXT.__auth_stubs: 0x7a0
+  __TEXT.__objc_stubs: 0xee0
+  __TEXT.__objc_methlist: 0x734
+  __TEXT.__const: 0xe0
+  __TEXT.__cstring: 0x638
   __TEXT.__objc_classname: 0x121
-  __TEXT.__objc_methname: 0xd34
+  __TEXT.__objc_methname: 0xd43
   __TEXT.__objc_methtype: 0x6a6
-  __TEXT.__oslogstring: 0xa86
-  __TEXT.__gcc_except_tab: 0xb8
+  __TEXT.__oslogstring: 0xb04
+  __TEXT.__gcc_except_tab: 0xac
   __TEXT.__dlopen_cstrs: 0x5d
-  __TEXT.__unwind_info: 0x2c0
-  __DATA_CONST.__auth_got: 0x3d0
+  __TEXT.__unwind_info: 0x2d0
+  __TEXT.__eh_frame: 0x48
+  __DATA_CONST.__auth_got: 0x3e0
   __DATA_CONST.__got: 0x120
+  __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__const: 0x388
   __DATA_CONST.__cfstring: 0x2c0
   __DATA_CONST.__objc_classlist: 0x68

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x40
   __DATA.__objc_const: 0xb58
-  __DATA.__objc_selrefs: 0x4c8
+  __DATA.__objc_selrefs: 0x4d0
   __DATA.__objc_ivar: 0x70
   __DATA.__objc_data: 0x410
   __DATA.__data: 0xb1

   - /System/Library/Frameworks/SecurityInterface.framework/Versions/A/SecurityInterface
   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
+  - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 272
-  Symbols:   228
-  CStrings:  409
+  Functions: 277
+  Symbols:   231
+  CStrings:  415
 
Symbols:
+ ___chkstk_darwin
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
