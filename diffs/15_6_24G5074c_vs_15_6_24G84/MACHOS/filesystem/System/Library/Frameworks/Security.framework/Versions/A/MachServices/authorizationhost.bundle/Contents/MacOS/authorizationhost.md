## authorizationhost

> `/System/Library/Frameworks/Security.framework/Versions/A/MachServices/authorizationhost.bundle/Contents/MacOS/authorizationhost`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-55579.140.3.0.0
-  __TEXT.__text: 0x22044
-  __TEXT.__auth_stubs: 0x1320
-  __TEXT.__objc_stubs: 0x18e0
-  __TEXT.__objc_methlist: 0x8dc
+55579.140.3.0.1
+  __TEXT.__text: 0x22384
+  __TEXT.__auth_stubs: 0x1340
+  __TEXT.__objc_stubs: 0x1900
+  __TEXT.__objc_methlist: 0x8e4
   __TEXT.__const: 0x260
-  __TEXT.__cstring: 0x279c
-  __TEXT.__objc_methname: 0x141a
+  __TEXT.__cstring: 0x27ae
+  __TEXT.__objc_methname: 0x1429
   __TEXT.__objc_classname: 0x1dc
   __TEXT.__objc_methtype: 0x75c
-  __TEXT.__oslogstring: 0x2d6e
-  __TEXT.__gcc_except_tab: 0x274
+  __TEXT.__oslogstring: 0x2dec
+  __TEXT.__gcc_except_tab: 0x258
   __TEXT.__dlopen_cstrs: 0x39b
-  __TEXT.__unwind_info: 0x648
-  __DATA_CONST.__auth_got: 0x9a0
+  __TEXT.__unwind_info: 0x650
+  __TEXT.__eh_frame: 0x48
+  __DATA_CONST.__auth_got: 0x9b0
   __DATA_CONST.__got: 0x260
-  __DATA_CONST.__auth_ptr: 0x20
+  __DATA_CONST.__auth_ptr: 0x28
   __DATA_CONST.__const: 0x820
   __DATA_CONST.__cfstring: 0xd80
   __DATA_CONST.__objc_classlist: 0xb0

   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA.__objc_const: 0x10c8
-  __DATA.__objc_selrefs: 0x708
+  __DATA.__objc_selrefs: 0x710
   __DATA.__objc_ivar: 0x7c
   __DATA.__objc_data: 0x6e0
   __DATA.__data: 0x138

   - /usr/lib/libcsfde.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpam.2.dylib
-  Functions: 795
-  Symbols:   524
-  CStrings:  1075
+  Functions: 799
+  Symbols:   526
+  CStrings:  1081
 
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
+ "authorizationhost"
+ "isPeerTrusted:"
- "Request: caller is trusted: %d"
- "Unapproved caller %{public}s, SecurityAgent and authorizationhost may only be invoked by Apple software."
```
