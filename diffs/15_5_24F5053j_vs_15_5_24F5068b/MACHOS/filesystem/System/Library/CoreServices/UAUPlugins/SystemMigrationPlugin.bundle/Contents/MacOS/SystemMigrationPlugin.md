## SystemMigrationPlugin

> `/System/Library/CoreServices/UAUPlugins/SystemMigrationPlugin.bundle/Contents/MacOS/SystemMigrationPlugin`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_classlist`
- `__DATA.__objc_data`

```diff

-533.0.0.0.0
-  __TEXT.__text: 0xa8
-  __TEXT.__auth_stubs: 0x50
-  __TEXT.__objc_stubs: 0x60
-  __TEXT.__objc_methlist: 0x1c4
-  __TEXT.__cstring: 0x86
-  __TEXT.__objc_classname: 0x3c
-  __TEXT.__objc_methname: 0x262
-  __TEXT.__objc_methtype: 0x112
-  __TEXT.__unwind_info: 0x68
-  __DATA_CONST.__auth_got: 0x30
-  __DATA_CONST.__got: 0x10
-  __DATA_CONST.__cfstring: 0x60
+533.1.0.0.0
+  __TEXT.__text: 0x214
+  __TEXT.__auth_stubs: 0x80
+  __TEXT.__objc_stubs: 0x120
+  __TEXT.__objc_methlist: 0x20c
+  __TEXT.__const: 0x8
+  __TEXT.__cstring: 0xc0
+  __TEXT.__objc_classname: 0x54
+  __TEXT.__objc_methname: 0x399
+  __TEXT.__objc_methtype: 0x21f
+  __TEXT.__unwind_info: 0x70
+  __DATA_CONST.__auth_got: 0x48
+  __DATA_CONST.__got: 0x18
+  __DATA_CONST.__const: 0x70
+  __DATA_CONST.__cfstring: 0x80
   __DATA_CONST.__objc_classlist: 0x8
-  __DATA_CONST.__objc_protolist: 0x10
+  __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_arraydata: 0x8
-  __DATA_CONST.__objc_arrayobj: 0x18
-  __DATA.__objc_const: 0x258
-  __DATA.__objc_selrefs: 0xf8
+  __DATA_CONST.__objc_protorefs: 0x8
+  __DATA.__objc_const: 0x280
+  __DATA.__objc_selrefs: 0x148
   __DATA.__objc_ivar: 0x4
   __DATA.__objc_data: 0x50
-  __DATA.__data: 0xc0
+  __DATA.__data: 0x120
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/PreferencePanes.framework/Versions/A/PreferencePanes

   - /System/Library/PrivateFrameworks/UAUPlugin.framework/Versions/A/UAUPlugin
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 7
-  Symbols:   16
-  CStrings:  62
+  Functions: 11
+  Symbols:   20
+  CStrings:  84
 
Symbols:
+ _NSLog
+ _OBJC_CLASS_$_NSXPCConnection
+ _OBJC_CLASS_$_NSXPCInterface
+ __NSConcreteGlobalBlock
+ __NSConcreteStackBlock
+ _objc_alloc
+ _objc_release
+ _objc_retain
+ _objc_retainAutoreleasedReturnValue
- _OBJC_CLASS_$_NSConstantArray
- _OBJC_CLASS_$_NSTask
- _OBJC_CLASS_$_SUOSUFollowUpHelper
- _objc_unsafeClaimAutoreleasedReturnValue
- _setAttentionCountForPreferencePane
CStrings:
+ "Failed to connect to migrationhelper: %@"
+ "Failed to perform UAU actions: %@"
+ "MigrationHelperProtocol"
+ "UAU actions completed successfully."
+ "com.apple.installandsetup.migrationhelper"
+ "doImportWithParameters:desktopPictureURL:reply:"
+ "encryptDiskWithiCloudUser:iCloudPassword:localUser:localPassword:andBag:reply:"
+ "initWithMachServiceName:options:"
+ "interfaceWithProtocol:"
+ "invalidate"
+ "localizedDescription"
+ "remoteObjectProxyWithErrorHandler:"
+ "resume"
+ "setMigrationRequestUUID:"
+ "setOriginatingApplication:"
+ "setRemoteObjectInterface:"
+ "updateUserAccountWithReply:"
+ "v16@?0@\"NSError\"8"
+ "v20@?0B8@\"NSError\"12"
+ "v24@0:8@\"NSString\"16"
+ "v24@0:8@?16"
+ "v24@0:8@?<v@?B@\"NSError\">16"
+ "v24@0:8Q16"
+ "v40@0:8@\"NSDictionary\"16@\"NSURL\"24@?<v@?B@\"NSArray\">32"
+ "v40@0:8@16@24@?32"
+ "v64@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32@\"NSString\"40@\"NSDictionary\"48@?<v@?B@\"NSError\">56"
+ "v64@0:8@16@24@32@40@48@?56"
- "/System/Library/PrivateFrameworks/SystemMigrationNetwork.framework/Resources/migrationhelper"
- "clearFollowUp"
- "com.apple.preferences.softwareupdate"
- "launchedTaskWithLaunchPath:arguments:"
- "uau"
```
