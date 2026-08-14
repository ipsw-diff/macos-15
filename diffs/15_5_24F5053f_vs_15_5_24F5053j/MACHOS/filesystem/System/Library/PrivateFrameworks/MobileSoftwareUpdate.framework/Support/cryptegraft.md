## cryptegraft

> `/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/Support/cryptegraft`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_classrefs`

```diff

-2171.120.30.0.4
-  __TEXT.__text: 0x318
-  __TEXT.__auth_stubs: 0xe0
+2171.120.44.0.1
+  __TEXT.__text: 0x360
+  __TEXT.__auth_stubs: 0x120
   __TEXT.__objc_stubs: 0x60
-  __TEXT.__cstring: 0x1cc
+  __TEXT.__cstring: 0x1f9
   __TEXT.__objc_methname: 0x44
   __TEXT.__unwind_info: 0x60
-  __DATA_CONST.__auth_got: 0x78
+  __DATA_CONST.__auth_got: 0x98
   __DATA_CONST.__got: 0x18
   __DATA_CONST.__cfstring: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8

   - /System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/Versions/A/MobileSoftwareUpdate
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2
-  Symbols:   31
-  CStrings:  16
+  Functions: 3
+  Symbols:   36
+  CStrings:  18
 
Symbols:
+ _csr_check
+ _errx
+ _os_variant_allows_internal_security_policies
+ _rootless_restricted_environment
+ main
Functions:
~ _main : 720 -> 764
CStrings:
+ "cryptegraft"
+ "not allowed while SIP is enabled"
```
