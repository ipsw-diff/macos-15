## MobileDevice

> `/System/Library/Templates/Data/Library/Apple/System/Library/PrivateFrameworks/MobileDevice.framework/Versions/A/MobileDevice`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__dof_MobileDev`
- `__TEXT.__dof_afc`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__objc_const`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__objc_classrefs`
- `__DATA.__data`

```diff

 1784.140.4.0.0
-  __TEXT.__text: 0x2850dc
-  __TEXT.__auth_stubs: 0x4030
+  __TEXT.__text: 0x2853c4
+  __TEXT.__auth_stubs: 0x4040
   __TEXT.__objc_methlist: 0x3df4
   __TEXT.__const: 0x1018ec
-  __TEXT.__cstring: 0x749d6
+  __TEXT.__cstring: 0x74a30
   __TEXT.__gcc_except_tab: 0x3cdc
   __TEXT.__oslogstring: 0x96a
   __TEXT.__ustring: 0x15a
   __TEXT.__dof_MobileDev: 0x1ac1
   __TEXT.__dof_afc: 0x6d7
-  __TEXT.__unwind_info: 0x6888
-  __TEXT.__eh_frame: 0x6a4
+  __TEXT.__unwind_info: 0x6898
+  __TEXT.__eh_frame: 0x6f4
   __TEXT.__objc_classname: 0xe13
   __TEXT.__objc_methname: 0x7174
   __TEXT.__objc_methtype: 0x2453
   __TEXT.__objc_stubs: 0x58c0
   __DATA_CONST.__got: 0x380
-  __DATA_CONST.__const: 0x7448
+  __DATA_CONST.__const: 0x7428
   __DATA_CONST.__objc_classlist: 0x298
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x1b88
-  __AUTH_CONST.__auth_got: 0x2030
-  __AUTH_CONST.__const: 0x8688
-  __AUTH_CONST.__cfstring: 0x3b4c0
+  __AUTH_CONST.__auth_got: 0x2038
+  __AUTH_CONST.__const: 0x8668
+  __AUTH_CONST.__cfstring: 0x3b480
   __AUTH_CONST.__objc_const: 0x71c0
   __AUTH.__objc_data: 0x19f0
   __AUTH.__data: 0x338

   __DATA.__objc_superrefs: 0x290
   __DATA.__objc_ivar: 0x4b4
   __DATA.__data: 0x1af8
-  __DATA.__bss: 0x41b8
+  __DATA.__bss: 0x41a8
   __DATA.__common: 0x10c0
   - /Library/Apple/System/Library/PrivateFrameworks/DeviceInterface.framework/Versions/A/DeviceInterface
   - /Library/Apple/usr/appleinternal/lib/libMobileRestoreInternalExtensions.dylib

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libssl.35.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 9496
+  Functions: 9497
   Symbols:   13828
-  CStrings:  15987
+  CStrings:  15989
 
Symbols:
+ ___isPlatformOrVariantPlatformVersionAtLeast
+ __isPlatformOrVariantPlatformVersionAtLeast
+ _taDFU_AppleKIS_enabled
+ _taDFU_deviceinterfaced_enabled
+ _tadfu_transport_client_usable
- ___taDFU_use_deviceinterfaced_block_invoke
- _taDFU_useKISKext
- taDFU_startDeviceDiscoveryForVIDPID
- taDFU_use_deviceinterfaced.onceToken
- taDFU_use_deviceinterfaced.result
CStrings:
+ "%s Overriding behavior with boot-arg, KIS kext is forced: %s"
+ "%s deviceinterfaced enabled: %s."
+ "KIS kext is %s"
+ "Platform2 == PLATFORM_MACOS && \"unexpected platform\""
+ "__isPlatformOrVariantPlatformVersionAtLeast"
+ "applekis.enabled"
+ "os_version_check.c"
+ "restore library built Jul  1 2025 at 12:11:39"
+ "taDFU_AppleKIS_enabled"
- "%s Overriding behavior with boot-arg, using kext: %d"
- "EnableDeviceInterfaceDaemon"
- "com.apple.libDFU"
- "deviceinterfaced enabled: %d."
- "deviceinterfaced is forced %s"
- "restore library built Jun 17 2025 at 22:02:37"
- "taDFU_useKISKext"
```
