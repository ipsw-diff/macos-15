## com.apple.MobileSoftwareUpdate.CryptegraftService

> `/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/Versions/A/XPCServices/com.apple.MobileSoftwareUpdate.CryptegraftService.xpc/Contents/MacOS/com.apple.MobileSoftwareUpdate.CryptegraftService`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2171.140.7.0.0
-  __TEXT.__text: 0x65294
-  __TEXT.__auth_stubs: 0x1af0
+2171.140.14.501.1
+  __TEXT.__text: 0x65454
+  __TEXT.__auth_stubs: 0x1b30
   __TEXT.__objc_stubs: 0x4ea0
   __TEXT.__objc_methlist: 0x3c64
   __TEXT.__const: 0x4fc0
-  __TEXT.__cstring: 0x144d7
+  __TEXT.__cstring: 0x145fb
   __TEXT.__objc_classname: 0xdb0
   __TEXT.__objc_methtype: 0x130a
   __TEXT.__oslogstring: 0x19f6

   __TEXT.__objc_methname: 0x5bda
   __TEXT.__unwind_info: 0x1580
   __TEXT.__eh_frame: 0xb4
-  __DATA_CONST.__auth_got: 0xd88
+  __DATA_CONST.__auth_got: 0xda8
   __DATA_CONST.__got: 0x410
   __DATA_CONST.__auth_ptr: 0x70
   __DATA_CONST.__const: 0x2098
-  __DATA_CONST.__cfstring: 0xb800
+  __DATA_CONST.__cfstring: 0xb880
   __DATA_CONST.__objc_classlist: 0x308
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x38

   - /usr/lib/libpartition2_dynamic.dylib
   - /usr/lib/libz.1.dylib
   Functions: 2127
-  Symbols:   4441
-  CStrings:  4338
+  Symbols:   4445
+  CStrings:  4349
 
Symbols:
+ _NSHomeDirectory
+ _NSTemporaryDirectory
+ _realpath$DARWIN_EXTSN
+ _sandbox_init_with_parameters
Functions:
~ _main : 52 -> 480
~ _SecCertificateCopyAMSupportCert.cold.4 : 24 -> 28
~ _ccn_sqr_ws : 252 -> 268
CStrings:
+ "%s: realpath() failed for home directory: %{darwin.errno}d\n"
+ "%s: realpath() failed for temporary directory: %{darwin.errno}d\n"
+ "%s: sandbox init failed: %s\n"
+ "20:05:29"
+ "2171.140.14.501.1"
+ "CryptegraftService"
+ "HOME"
+ "Jul  8 2025"
+ "Starting with MobileSoftwareUpdate-%s (built %s %s)\n"
+ "TMPDIR"
+ "_enter_sandbox"
```
