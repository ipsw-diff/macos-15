## FSKit

> `/System/Library/Frameworks/FSKit.framework/Versions/A/FSKit`

```diff

-531.140.7.0.0
-  __TEXT.__text: 0x42594
+531.140.7.0.2
+  __TEXT.__text: 0x42cbc
   __TEXT.__auth_stubs: 0xaa0
-  __TEXT.__objc_methlist: 0x4334
+  __TEXT.__objc_methlist: 0x439c
   __TEXT.__const: 0x390
   __TEXT.__gcc_except_tab: 0xf14
-  __TEXT.__cstring: 0x3e5f
-  __TEXT.__oslogstring: 0x2c46
+  __TEXT.__cstring: 0x3e6f
+  __TEXT.__oslogstring: 0x2c91
   __TEXT.__swift5_typeref: 0x1d1
   __TEXT.__swift5_capture: 0x58
   __TEXT.__swift5_reflstr: 0x16

   __TEXT.__swift5_types: 0x8
   __TEXT.__swift_as_entry: 0x8
   __TEXT.__swift_as_ret: 0x8
-  __TEXT.__unwind_info: 0x1238
+  __TEXT.__unwind_info: 0x1268
   __TEXT.__eh_frame: 0x138
   __TEXT.__objc_classname: 0x825
-  __TEXT.__objc_methname: 0x9396
+  __TEXT.__objc_methname: 0x9471
   __TEXT.__objc_methtype: 0x325e
-  __TEXT.__objc_stubs: 0x5460
+  __TEXT.__objc_stubs: 0x54c0
   __DATA_CONST.__got: 0x3e8
   __DATA_CONST.__const: 0x2c8
   __DATA_CONST.__objc_classlist: 0x208
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x140
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x22b0
+  __DATA_CONST.__objc_selrefs: 0x22d0
   __DATA_CONST.__objc_protorefs: 0xe8
   __DATA_CONST.__objc_superrefs: 0x190
   __DATA_CONST.__objc_arraydata: 0x30
   __AUTH_CONST.__auth_got: 0x560
   __AUTH_CONST.__const: 0x15c8
   __AUTH_CONST.__cfstring: 0x1e40
-  __AUTH_CONST.__objc_const: 0x7018
+  __AUTH_CONST.__objc_const: 0x7038
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH.__objc_data: 0x1590
   __AUTH.__data: 0x80

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1887
-  Symbols:   3701
-  CStrings:  2807
+  Functions: 1898
+  Symbols:   3713
+  CStrings:  2812
 
Symbols:
+ +[FSKitDiskArbHelper DAMountFSKitVolume:deviceName:mountPoint:volumeName:auditToken:mountOptions:]
+ -[FSClient(Private) activateVolume:shortName:options:auditToken:replyHandler:]
+ -[FSClient(Private) deactivateVolume:shortName:numericOptions:auditToken:replyHandler:]
+ -[FSClient(Private) loadResource:shortName:options:auditToken:replyHandler:]
+ -[FSClient(Private) unloadResource:shortName:options:auditToken:replyHandler:]
+ -[FSClient(Project) deactivateVolume:shortName:numericOptions:auditToken:replyHandler:]
+ -[FSModuleExtension(Project) sendConfigureUserClientWithReplyHandler:]
+ __98+[FSKitDiskArbHelper DAMountFSKitVolume:deviceName:mountPoint:volumeName:auditToken:mountOptions:]_block_invoke
+ ___70-[FSModuleExtension(Project) sendConfigureUserClientWithReplyHandler:]_block_invoke
+ ___76-[FSClient(Private) loadResource:shortName:options:auditToken:replyHandler:]_block_invoke
+ ___78-[FSClient(Private) activateVolume:shortName:options:auditToken:replyHandler:]_block_invoke
+ ___78-[FSClient(Private) unloadResource:shortName:options:auditToken:replyHandler:]_block_invoke
+ ___87-[FSClient(Private) deactivateVolume:shortName:numericOptions:auditToken:replyHandler:]_block_invoke
+ ___87-[FSClient(Project) deactivateVolume:shortName:numericOptions:auditToken:replyHandler:]_block_invoke
+ ___98+[FSKitDiskArbHelper DAMountFSKitVolume:deviceName:mountPoint:volumeName:auditToken:mountOptions:]_block_invoke
+ ___block_descriptor_148_e8_32s40s48s56s64s72s80s88s96r104r_e36_v32?0"FSVolumeDescription"8Q16^B24l
+ _objc_msgSend$DAMountFSKitVolume:deviceName:mountPoint:volumeName:auditToken:mountOptions:
+ _objc_msgSend$activateVolume:shortName:options:auditToken:replyHandler:
+ _objc_msgSend$deactivateVolume:shortName:numericOptions:auditToken:replyHandler:
+ _objc_msgSend$loadResource:shortName:options:auditToken:replyHandler:
+ _objc_msgSend$sendConfigureUserClientWithReplyHandler:
+ _objc_msgSend$unloadResource:shortName:options:auditToken:replyHandler:
- +[FSKitDiskArbHelper DAMountFSKitVolume:deviceName:mountPoint:volumeName:mountOptions:]
- -[FSModuleExtension(Project) sendConfigureUserClient:replyHandler:]
- GCC_except_table107
- __87+[FSKitDiskArbHelper DAMountFSKitVolume:deviceName:mountPoint:volumeName:mountOptions:]_block_invoke
- ___67-[FSModuleExtension(Project) sendConfigureUserClient:replyHandler:]_block_invoke
- ___87+[FSKitDiskArbHelper DAMountFSKitVolume:deviceName:mountPoint:volumeName:mountOptions:]_block_invoke
- ___block_descriptor_116_e8_32s40s48s56s64s72s80s88s96r104r_e36_v32?0"FSVolumeDescription"8Q16^B24l
- _objc_msgSend$DAMountFSKitVolume:deviceName:mountPoint:volumeName:mountOptions:
- _objc_msgSend$fsMachPort
- _objc_msgSend$mountVolume:fileSystem:displayName:provider:domainError:on:how:options:
CStrings:
+ "%s: Created FSMachPort = %d"
+ "%s: Extension (%{public}@) doesn't have a mach port to configure user client"
+ "%s: Failed to create FSMachPort"
+ "+[FSKitDiskArbHelper DAMountFSKitVolume:deviceName:mountPoint:volumeName:auditToken:mountOptions:]"
+ "+[FSKitDiskArbHelper DAMountFSKitVolume:deviceName:mountPoint:volumeName:auditToken:mountOptions:]_block_invoke"
+ "-[FSModuleExtension(Project) sendConfigureUserClientWithReplyHandler:]"
+ "DAMountFSKitVolume:deviceName:mountPoint:volumeName:auditToken:mountOptions:"
+ "activateVolume:shortName:options:auditToken:replyHandler:"
+ "deactivateVolume:shortName:numericOptions:auditToken:replyHandler:"
+ "loadResource:shortName:options:auditToken:replyHandler:"
+ "sendConfigureUserClientWithReplyHandler:"
+ "unloadResource:shortName:options:auditToken:replyHandler:"
- "%s: Failed to create LiveFSMachPort"
- "+[FSKitDiskArbHelper DAMountFSKitVolume:deviceName:mountPoint:volumeName:mountOptions:]"
- "+[FSKitDiskArbHelper DAMountFSKitVolume:deviceName:mountPoint:volumeName:mountOptions:]_block_invoke"
- "-[FSModuleExtension(Project) sendConfigureUserClient:replyHandler:]"
- "DAMountFSKitVolume:deviceName:mountPoint:volumeName:mountOptions:"
- "created fsFSMachPort = %d"
- "mountVolume:fileSystem:displayName:provider:domainError:on:how:options:"
```
