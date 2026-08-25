## com.apple.MobileSoftwareUpdate.CleanupPreparePathService

> `/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/Versions/A/XPCServices/com.apple.MobileSoftwareUpdate.CleanupPreparePathService.xpc/Contents/MacOS/com.apple.MobileSoftwareUpdate.CleanupPreparePathService`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_classrefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2171.140.7.0.0
-  __TEXT.__text: 0xa2980
+2171.140.14.501.1
+  __TEXT.__text: 0xa2b44
   __TEXT.__auth_stubs: 0x1b10
-  __TEXT.__objc_stubs: 0x4b60
-  __TEXT.__objc_methlist: 0x1dac
-  __TEXT.__cstring: 0x18fa2
+  __TEXT.__objc_stubs: 0x4ba0
+  __TEXT.__objc_methlist: 0x1dd4
+  __TEXT.__cstring: 0x18feb
   __TEXT.__const: 0x77b20
   __TEXT.__oslogstring: 0x19fe
   __TEXT.__objc_classname: 0x273
   __TEXT.__gcc_except_tab: 0x4c0
-  __TEXT.__objc_methname: 0x51fa
+  __TEXT.__objc_methname: 0x5256
   __TEXT.__objc_methtype: 0xfdb
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x12c0
+  __TEXT.__unwind_info: 0x12d0
   __TEXT.__eh_frame: 0x318
   __DATA_CONST.__auth_got: 0xd98
   __DATA_CONST.__got: 0x388

   __DATA_CONST.__objc_dictobj: 0x208
   __DATA_CONST.__objc_arrayobj: 0xf0
   __DATA.__objc_const: 0x26e8
-  __DATA.__objc_selrefs: 0x1720
+  __DATA.__objc_selrefs: 0x1740
   __DATA.__objc_ivar: 0x1b4
   __DATA.__objc_data: 0x8c0
   __DATA.__data: 0x560

   - /usr/lib/liblzma.5.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpartition2_dynamic.dylib
-  Functions: 1851
-  Symbols:   3509
-  CStrings:  4254
+  Functions: 1857
+  Symbols:   3518
+  CStrings:  4259
 
Symbols:
+ -[MSUSFRTargetController _NSIHDataForTicketPath:error:]
+ -[MSUSFRTargetController _NSIHStringForTicketPath:error:]
+ -[MSUSFRTargetController bootedSFRManifestHash]
+ -[MSUSFRTargetController currentSFRManifestHash]
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/MobileSoftwareUpdate/install/TempContent/Objects/MobileSoftwareUpdate.build/CleanupPreparePathService.build/Objects-normal/arm64e/gestalt_interface.o
+ __copy_sfr_manifest_hash
+ __copy_value_from_IONode
+ __hexStringForBytes
+ _objc_msgSend$_NSIHDataForTicketPath:error:
+ _objc_msgSend$_NSIHStringForTicketPath:error:
+ _objc_msgSend$initWithUTF8String:
+ _objc_msgSend$mutableBytes
+ gestalt_interface.m
- -[MSUSFRTargetController _NSIHForTicketPath:error:]
- _objc_msgSend$_NSIHForTicketPath:error:
- _objc_msgSend$cStringUsingEncoding:
- sprint_hex.kAsciiHexChars
CStrings:
+ "%s: Got a non-CFData return value from IORegistryEntryCreateCFProperty for property %@\n"
+ "%s: failed to decode migratorMetrics, reporting encoded metrics instead"
+ "_NSIHDataForTicketPath:error:"
+ "_NSIHStringForTicketPath:error:"
+ "_copy_value_from_IONode"
+ "bootedSFRManifestHash"
+ "currentSFRManifestHash"
+ "initWithUTF8String:"
+ "mutableBytes"
- "%s: bad decoded metrics"
- "%s: failed to find APFSDecodeMetricsString, reporting encoded metrics"
- "_NSIHForTicketPath:error:"
- "cStringUsingEncoding:"
```
