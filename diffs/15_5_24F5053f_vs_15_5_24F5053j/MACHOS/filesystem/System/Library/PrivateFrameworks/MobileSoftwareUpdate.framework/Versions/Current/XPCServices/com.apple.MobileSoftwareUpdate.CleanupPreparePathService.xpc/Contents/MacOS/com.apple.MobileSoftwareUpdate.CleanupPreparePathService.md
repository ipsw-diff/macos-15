## com.apple.MobileSoftwareUpdate.CleanupPreparePathService

> `/System/Library/PrivateFrameworks/MobileSoftwareUpdate.framework/Versions/Current/XPCServices/com.apple.MobileSoftwareUpdate.CleanupPreparePathService.xpc/Contents/MacOS/com.apple.MobileSoftwareUpdate.CleanupPreparePathService`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2171.120.30.0.4
-  __TEXT.__text: 0xa283c
-  __TEXT.__auth_stubs: 0x1b00
+2171.120.44.0.1
+  __TEXT.__text: 0xa2980
+  __TEXT.__auth_stubs: 0x1b10
   __TEXT.__objc_stubs: 0x4b60
   __TEXT.__objc_methlist: 0x1dac
-  __TEXT.__cstring: 0x18d6b
-  __TEXT.__const: 0x77b40
+  __TEXT.__cstring: 0x18f20
+  __TEXT.__const: 0x77b20
   __TEXT.__oslogstring: 0x19fe
   __TEXT.__objc_classname: 0x273
   __TEXT.__gcc_except_tab: 0x4c0

   __TEXT.__ustring: 0x4
   __TEXT.__unwind_info: 0x12c0
   __TEXT.__eh_frame: 0x318
-  __DATA_CONST.__auth_got: 0xd90
+  __DATA_CONST.__auth_got: 0xd98
   __DATA_CONST.__got: 0x388
   __DATA_CONST.__auth_ptr: 0x70
-  __DATA_CONST.__const: 0x2ac8
-  __DATA_CONST.__cfstring: 0xc580
+  __DATA_CONST.__const: 0x2ab8
+  __DATA_CONST.__cfstring: 0xc680
   __DATA_CONST.__objc_classlist: 0xe0
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x18

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpartition2_dynamic.dylib
   Functions: 1851
-  Symbols:   3508
-  CStrings:  4246
+  Symbols:   3509
+  CStrings:  4254
 
Symbols:
+ _CFPreferencesGetAppBooleanValue
+ __BIDeviceInfoGetMacPlatformFromIODT
- __BIDeviceInfoGetMacPlatformType
Functions:
~ _main : 3272 -> 3532
~ _Shift : 324 -> 320
~ __BIDeviceInfoGetMacPlatform : 632 -> 596
~ _BIDeviceInfoGetMacPlatformString : 36 -> 140
CStrings:
+ "FakeOSVersionChangedOnReboot"
+ "FakeUpdateAttemptedOnReboot"
+ "First boot after update: Attempting to clear out MobileAsset preferences\n"
+ "First boot after update: Deleting V1 asset path\n"
+ "First boot after update: Done deleting V1 asset path\n"
+ "First boot after update: Not clearing MobileAsset preference overrides due to default\n"
+ "First boot after update: Not clearing out MobileAsset preferences\n"
+ "Forcing OSVersion changed to true due to override\n"
+ "Forcing update attempted to true due to override\n"
+ "PreserveDefaultsOnUpdate"
+ "virtual_machine"
- "First boot after update: Done purging brains\n"
- "First boot after update: Purging brains\n"
- "other"
```
