## findmydevice-user-agent

> `/usr/libexec/findmydevice-user-agent`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__data`

```diff

 438.25.2.11.18
-  __TEXT.__text: 0x7bf0
-  __TEXT.__auth_stubs: 0x2e0
-  __TEXT.__objc_stubs: 0xba0
-  __TEXT.__objc_methlist: 0x3e4
-  __TEXT.__const: 0xd0
-  __TEXT.__objc_methname: 0xc1e
-  __TEXT.__cstring: 0x20cf
-  __TEXT.__oslogstring: 0xd98
-  __TEXT.__objc_classname: 0x10a
-  __TEXT.__objc_methtype: 0x1fe
-  __TEXT.__gcc_except_tab: 0xa4
-  __TEXT.__unwind_info: 0x208
-  __DATA_CONST.__auth_got: 0x180
-  __DATA_CONST.__got: 0x108
-  __DATA_CONST.__const: 0x12b0
-  __DATA_CONST.__cfstring: 0x2bc0
-  __DATA_CONST.__objc_classlist: 0x50
+  __TEXT.__text: 0x92c0
+  __TEXT.__auth_stubs: 0x330
+  __TEXT.__objc_stubs: 0xce0
+  __TEXT.__objc_methlist: 0x484
+  __TEXT.__const: 0xf0
+  __TEXT.__objc_methname: 0xdb5
+  __TEXT.__cstring: 0x21b1
+  __TEXT.__oslogstring: 0xe99
+  __TEXT.__objc_classname: 0x128
+  __TEXT.__objc_methtype: 0x277
+  __TEXT.__gcc_except_tab: 0x1b4
+  __TEXT.__unwind_info: 0x248
+  __DATA_CONST.__auth_got: 0x1a8
+  __DATA_CONST.__got: 0x110
+  __DATA_CONST.__const: 0x1370
+  __DATA_CONST.__cfstring: 0x2c40
+  __DATA_CONST.__objc_classlist: 0x58
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x10
-  __DATA.__objc_const: 0xc20
-  __DATA.__objc_selrefs: 0x3f8
+  __DATA.__objc_const: 0xd18
+  __DATA.__objc_selrefs: 0x450
   __DATA.__objc_ivar: 0xc
-  __DATA.__objc_data: 0x320
+  __DATA.__objc_data: 0x370
   __DATA.__data: 0x1f0
-  __DATA.__bss: 0x140
+  __DATA.__bss: 0x150
   __DATA.__common: 0x8
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /System/Library/PrivateFrameworks/IDS.framework/Versions/A/IDS
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 211
-  Symbols:   90
-  CStrings:  659
+  Functions: 240
+  Symbols:   96
+  CStrings:  688
 
Symbols:
+ _OBJC_CLASS_$_NSLock
+ _dispatch_group_create
+ _dispatch_group_enter
+ _dispatch_group_leave
+ _dispatch_group_wait
+ _dispatch_time
CStrings:
+ "-[FMDFMMUAXPCServer downloadSharedConfigurationWithLocale:reply:]"
+ "-[FMDFMMUAXPCServer getTheftAndLossCoverageWithSerialNumber:reply:]"
+ "DAEMON API: %s"
+ "FMDSharedConfigurationManager"
+ "Q24@0:8@16"
+ "Q32@0:8@16d24"
+ "T&L device coverage %@ for UDID: %@, error: %@"
+ "T&L device coverage %{public}@ for serialNumber: %@, error: %@"
+ "T@\"FMDSharedConfigurationManager\",R,N"
+ "XPC error for deviceCoverageWithSerialNumber: %li"
+ "_hasSharedConfigurationAccessEntitlement"
+ "brassStatus"
+ "com.apple.icloud.FindMyDevice.FindMyDeviceSharedConfiguration.access"
+ "deviceCoverageWithSerialNumber: %@ timed out"
+ "deviceCoverageWithUDID: %@ timed out"
+ "downloadSharedConfigurationWithLocale:reply:"
+ "false"
+ "getTheftAndLossCoverageWithSerialNumber:reply:"
+ "getTheftAndLossCoverageWithUDID:reply:"
+ "sharedConfigurationConfiguration"
+ "theftAndLossCoverageWithSerialNumber:"
+ "theftAndLossCoverageWithSerialNumber:timeout:"
+ "theftAndLossCoverageWithUDID:"
+ "theftAndLossCoverageWithUDID:timeout:"
+ "true"
+ "unlock"
+ "v32@0:8@\"NSString\"16@?<v@?@\"NSError\">24"
+ "v32@0:8@\"NSString\"16@?<v@?Q@\"NSError\">24"
+ "v32@0:8@16@?24"
```
