## SoftwareUpdateCore

> `/System/Library/PrivateFrameworks/SoftwareUpdateCore.framework/Versions/A/SoftwareUpdateCore`

```diff

-2171.140.7.0.0
-  __TEXT.__text: 0xac7e8
-  __TEXT.__auth_stubs: 0x690
+2171.140.14.501.1
+  __TEXT.__text: 0xac644
+  __TEXT.__auth_stubs: 0x660
   __TEXT.__objc_methlist: 0x730c
-  __TEXT.__const: 0x118
+  __TEXT.__const: 0x138
   __TEXT.__cstring: 0x1438d
-  __TEXT.__oslogstring: 0xb01b
+  __TEXT.__oslogstring: 0xafa9
   __TEXT.__gcc_except_tab: 0x744
-  __TEXT.__unwind_info: 0x1608
+  __TEXT.__unwind_info: 0x1600
   __TEXT.__objc_classname: 0x6d6
   __TEXT.__objc_methname: 0x141a9
   __TEXT.__objc_methtype: 0xeef
   __TEXT.__objc_stubs: 0xd880
-  __DATA_CONST.__got: 0x828
+  __DATA_CONST.__got: 0x820
   __DATA_CONST.__const: 0x13c8
   __DATA_CONST.__objc_classlist: 0x1c8
   __DATA_CONST.__objc_catlist: 0x28

   __DATA_CONST.__objc_selrefs: 0x3f58
   __DATA_CONST.__objc_superrefs: 0x1b0
   __DATA_CONST.__objc_arraydata: 0xe8
-  __AUTH_CONST.__auth_got: 0x358
-  __AUTH_CONST.__const: 0x1280
+  __AUTH_CONST.__auth_got: 0x340
+  __AUTH_CONST.__const: 0x1260
   __AUTH_CONST.__cfstring: 0x12040
   __AUTH_CONST.__objc_const: 0x9d40
   __AUTH_CONST.__objc_dictobj: 0x78

   __AUTH.__objc_data: 0x11d0
   __DATA.__objc_ivar: 0x900
   __DATA.__data: 0x360
-  __DATA.__bss: 0xc0
+  __DATA.__bss: 0xb0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/DiskArbitration.framework/Versions/A/DiskArbitration
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2866
-  Symbols:   6552
-  CStrings:  6100
+  Functions: 2862
+  Symbols:   6544
+  CStrings:  6097
 
Symbols:
+ _uuid_unparse
- _CFUUIDCreateString
- _DADiskCopyDescription
- _DADiskCreateFromVolumePath
- _DASessionCreate
- __52-[SUCoreDevice(SUCoreDeviceExtended) rootVolumeUUID]_block_invoke
- ___52-[SUCoreDevice(SUCoreDeviceExtended) rootVolumeUUID]_block_invoke
- _kDADiskDescriptionVolumeUUIDKey
- rootVolumeUUID.__rootVolumeUUID
- rootVolumeUUID.onceToken
CStrings:
+ "[SUCoreDevice] RootVolumeUUID: getattrlist(\"/\") did not return an ATTR_VOL_UUID attribute."
+ "[SUCoreDevice] RootVolumeUUID: getattrlist(\"/\") failed: %s"
- "[SUCoreDevice] RootVolumeUUID: %@"
- "[SUCoreDevice] RootVolumeUUID: Failed to copy disk description"
- "[SUCoreDevice] RootVolumeUUID: Failed to create disk"
- "[SUCoreDevice] RootVolumeUUID: Failed to create session"
- "[SUCoreDevice] RootVolumeUUID: Failed to find volume UUID"
```
