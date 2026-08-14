## com.apple.MobileSoftwareUpdate.CleanupPreparePathService

> `/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/Versions/A/XPCServices/com.apple.MobileSoftwareUpdate.CleanupPreparePathService.xpc/Contents/MacOS/com.apple.MobileSoftwareUpdate.CleanupPreparePathService`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_classrefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2171.120.23.501.1
-  __TEXT.__text: 0xa26fc
-  __TEXT.__auth_stubs: 0x1af0
+2171.120.30.0.4
+  __TEXT.__text: 0xa283c
+  __TEXT.__auth_stubs: 0x1b00
   __TEXT.__objc_stubs: 0x4b60
-  __TEXT.__objc_methlist: 0x1d94
+  __TEXT.__objc_methlist: 0x1dac
   __TEXT.__cstring: 0x18d6b
   __TEXT.__const: 0x77b40
   __TEXT.__oslogstring: 0x19fe
   __TEXT.__objc_classname: 0x273
   __TEXT.__gcc_except_tab: 0x4c0
-  __TEXT.__objc_methname: 0x51bb
+  __TEXT.__objc_methname: 0x51fa
   __TEXT.__objc_methtype: 0xfdb
   __TEXT.__ustring: 0x4
   __TEXT.__unwind_info: 0x12c0
   __TEXT.__eh_frame: 0x318
-  __DATA_CONST.__auth_got: 0xd88
+  __DATA_CONST.__auth_got: 0xd90
   __DATA_CONST.__got: 0x388
   __DATA_CONST.__auth_ptr: 0x70
   __DATA_CONST.__const: 0x2ac8

   __DATA_CONST.__objc_dictobj: 0x208
   __DATA_CONST.__objc_arrayobj: 0xf0
   __DATA.__objc_const: 0x26e8
-  __DATA.__objc_selrefs: 0x1710
+  __DATA.__objc_selrefs: 0x1720
   __DATA.__objc_ivar: 0x1b4
   __DATA.__objc_data: 0x8c0
   __DATA.__data: 0x560

   - /usr/lib/liblzma.5.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpartition2_dynamic.dylib
-  Functions: 1849
-  Symbols:   3505
-  CStrings:  4244
+  Functions: 1851
+  Symbols:   3508
+  CStrings:  4246
 
Symbols:
+ -[MSUSFRTargetController currentSystemRecoveryNSIHData:]
+ -[MSUSFRTargetController proposedSystemRecoveryNSIHData:]
+ _AMSupportCopyDataFromAsciiEncodedHex
CStrings:
+ "currentSystemRecoveryNSIHData:"
+ "proposedSystemRecoveryNSIHData:"
```
