## SecurityAgentHelper-arm64

> `/System/Library/Frameworks/Security.framework/Versions/A/MachServices/SecurityAgent.bundle/Contents/XPCServices/SecurityAgentHelper-arm64.xpc/Contents/MacOS/SecurityAgentHelper-arm64`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_classrefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-55579.140.3.0.0
-  __TEXT.__text: 0x1f608
-  __TEXT.__auth_stubs: 0xf10
-  __TEXT.__objc_stubs: 0x44c0
-  __TEXT.__objc_methlist: 0x1eac
+55579.140.3.0.1
+  __TEXT.__text: 0x1f94c
+  __TEXT.__auth_stubs: 0xf30
+  __TEXT.__objc_stubs: 0x44e0
+  __TEXT.__objc_methlist: 0x1eb4
   __TEXT.__const: 0x130
-  __TEXT.__objc_methname: 0x4973
-  __TEXT.__oslogstring: 0x205b
+  __TEXT.__objc_methname: 0x4982
+  __TEXT.__oslogstring: 0x20d9
   __TEXT.__objc_classname: 0x34c
   __TEXT.__objc_methtype: 0x159f
   __TEXT.__cstring: 0x1d31
-  __TEXT.__gcc_except_tab: 0x404
+  __TEXT.__gcc_except_tab: 0x3c8
   __TEXT.__ustring: 0x776
   __TEXT.__dlopen_cstrs: 0x10d
-  __TEXT.__unwind_info: 0x768
-  __DATA_CONST.__auth_got: 0x798
+  __TEXT.__unwind_info: 0x770
+  __TEXT.__eh_frame: 0x48
+  __DATA_CONST.__auth_got: 0x7a8
   __DATA_CONST.__got: 0x408
-  __DATA_CONST.__auth_ptr: 0x10
+  __DATA_CONST.__auth_ptr: 0x18
   __DATA_CONST.__const: 0x7b0
   __DATA_CONST.__cfstring: 0x1840
   __DATA_CONST.__objc_classlist: 0xd8

   __DATA_CONST.__objc_intobj: 0xa8
   __DATA_CONST.__objc_doubleobj: 0x10
   __DATA.__objc_const: 0x2f50
-  __DATA.__objc_selrefs: 0x1708
+  __DATA.__objc_selrefs: 0x1710
   __DATA.__objc_ivar: 0x28c
   __DATA.__objc_data: 0x870
   __DATA.__data: 0x490

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 766
-  Symbols:   516
-  CStrings:  1700
+  Functions: 771
+  Symbols:   519
+  CStrings:  1705
 
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
+ "isPeerTrusted:"
- "Request: caller is trusted: %d"
- "Unapproved caller %{public}s, SecurityAgent and authorizationhost may only be invoked by Apple software."
```
