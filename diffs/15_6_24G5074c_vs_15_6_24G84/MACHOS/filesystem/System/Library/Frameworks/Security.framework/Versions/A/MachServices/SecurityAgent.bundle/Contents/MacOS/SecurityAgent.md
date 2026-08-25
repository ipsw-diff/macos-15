## SecurityAgent

> `/System/Library/Frameworks/Security.framework/Versions/A/MachServices/SecurityAgent.bundle/Contents/MacOS/SecurityAgent`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__objc_methtype`
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
-  __TEXT.__text: 0x2d2f0
-  __TEXT.__auth_stubs: 0x1270
-  __TEXT.__objc_stubs: 0x5100
-  __TEXT.__objc_methlist: 0x280c
-  __TEXT.__const: 0x169
+55579.140.3.0.1
+  __TEXT.__text: 0x2d65c
+  __TEXT.__auth_stubs: 0x1290
+  __TEXT.__objc_stubs: 0x5120
+  __TEXT.__objc_methlist: 0x281c
+  __TEXT.__const: 0x171
   __TEXT.__cstring: 0x2e96
-  __TEXT.__gcc_except_tab: 0x438
-  __TEXT.__oslogstring: 0x29d6
-  __TEXT.__objc_methname: 0x556a
+  __TEXT.__gcc_except_tab: 0x3fc
+  __TEXT.__oslogstring: 0x2a54
+  __TEXT.__objc_methname: 0x5579
   __TEXT.__objc_classname: 0x643
   __TEXT.__objc_methtype: 0x16f1
   __TEXT.__ustring: 0x156e
   __TEXT.__dlopen_cstrs: 0x10d
-  __TEXT.__unwind_info: 0x9c0
-  __DATA_CONST.__auth_got: 0x948
+  __TEXT.__unwind_info: 0x9c8
+  __TEXT.__eh_frame: 0x48
+  __DATA_CONST.__auth_got: 0x958
   __DATA_CONST.__got: 0x528
-  __DATA_CONST.__auth_ptr: 0x18
+  __DATA_CONST.__auth_ptr: 0x20
   __DATA_CONST.__const: 0x970
   __DATA_CONST.__cfstring: 0x2880
   __DATA_CONST.__objc_classlist: 0x1c8

   __DATA_CONST.__objc_intobj: 0xc0
   __DATA_CONST.__objc_doubleobj: 0x10
   __DATA.__objc_const: 0x4870
-  __DATA.__objc_selrefs: 0x1a68
+  __DATA.__objc_selrefs: 0x1a70
   __DATA.__objc_ivar: 0x38c
   __DATA.__objc_data: 0x11d0
   __DATA.__data: 0x492

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1062
-  Symbols:   728
-  CStrings:  2175
+  Functions: 1067
+  Symbols:   730
+  CStrings:  2180
 
Symbols:
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
