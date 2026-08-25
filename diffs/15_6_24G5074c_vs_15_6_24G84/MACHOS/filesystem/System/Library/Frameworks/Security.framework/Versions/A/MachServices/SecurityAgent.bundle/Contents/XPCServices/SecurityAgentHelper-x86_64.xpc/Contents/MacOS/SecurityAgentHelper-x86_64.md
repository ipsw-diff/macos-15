## SecurityAgentHelper-x86_64

> `/System/Library/Frameworks/Security.framework/Versions/A/MachServices/SecurityAgent.bundle/Contents/XPCServices/SecurityAgentHelper-x86_64.xpc/Contents/MacOS/SecurityAgentHelper-x86_64`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-55579.140.3.0.0
-  __TEXT.__text: 0x21827
-  __TEXT.__stubs: 0x5a0
+55579.140.3.0.1
+  __TEXT.__text: 0x21b97
+  __TEXT.__stubs: 0x5ac
   __TEXT.__const: 0xe0
-  __TEXT.__objc_methname: 0x4aca
-  __TEXT.__oslogstring: 0x2667
+  __TEXT.__objc_methname: 0x4ad9
+  __TEXT.__oslogstring: 0x26f7
   __TEXT.__objc_classname: 0x34c
   __TEXT.__objc_methtype: 0x15aa
   __TEXT.__cstring: 0x1d31
-  __TEXT.__gcc_except_tab: 0x404
+  __TEXT.__gcc_except_tab: 0x3c8
   __TEXT.__ustring: 0x776
   __TEXT.__dlopen_cstrs: 0x11d
-  __TEXT.__unwind_info: 0x700
-  __DATA_CONST.__got: 0xba8
+  __TEXT.__unwind_info: 0x710
+  __TEXT.__eh_frame: 0x58
+  __DATA_CONST.__got: 0xbc0
   __DATA_CONST.__const: 0x790
   __DATA_CONST.__cfstring: 0x1840
   __DATA_CONST.__objc_classlist: 0xd8

   __DATA_CONST.__objc_arrayobj: 0x60
   __DATA_CONST.__objc_intobj: 0xa8
   __DATA_CONST.__objc_doubleobj: 0x10
-  __DATA.__objc_const: 0x66c8
-  __DATA.__objc_selrefs: 0x1238
+  __DATA.__objc_const: 0x66e0
+  __DATA.__objc_selrefs: 0x1240
   __DATA.__objc_ivar: 0x518
   __DATA.__objc_data: 0xbf8
   __DATA.__data: 0x490

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 743
-  Symbols:   516
-  CStrings:  1718
+  Functions: 749
+  Symbols:   519
+  CStrings:  1723
 
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
+ "isPeerTrusted:"
- "Request: caller is trusted: %d"
- "Unapproved caller %{public}s, SecurityAgent and authorizationhost may only be invoked by Apple software."
```
