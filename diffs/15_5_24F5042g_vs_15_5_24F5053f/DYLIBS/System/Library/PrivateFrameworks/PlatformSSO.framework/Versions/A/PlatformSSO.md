## PlatformSSO

> `/System/Library/PrivateFrameworks/PlatformSSO.framework/Versions/A/PlatformSSO`

```diff

-417.120.1.0.0
-  __TEXT.__text: 0x98c1c
-  __TEXT.__auth_stubs: 0xec0
-  __TEXT.__objc_methlist: 0x3b34
+417.120.3.0.0
+  __TEXT.__text: 0x98ff4
+  __TEXT.__auth_stubs: 0xed0
+  __TEXT.__objc_methlist: 0x3b7c
   __TEXT.__const: 0x180
-  __TEXT.__gcc_except_tab: 0x2070
-  __TEXT.__cstring: 0xc739
+  __TEXT.__gcc_except_tab: 0x205c
+  __TEXT.__cstring: 0xc7a3
   __TEXT.__oslogstring: 0x3ff2
   __TEXT.__dlopen_cstrs: 0x41a
-  __TEXT.__unwind_info: 0x1b48
-  __TEXT.__objc_classname: 0x415
-  __TEXT.__objc_methname: 0xbe12
-  __TEXT.__objc_methtype: 0x1cd6
-  __TEXT.__objc_stubs: 0x9720
+  __TEXT.__unwind_info: 0x1b50
+  __TEXT.__objc_classname: 0x413
+  __TEXT.__objc_methname: 0xbec4
+  __TEXT.__objc_methtype: 0x1cfc
+  __TEXT.__objc_stubs: 0x9760
   __DATA_CONST.__got: 0x5c8
   __DATA_CONST.__const: 0x5c0
   __DATA_CONST.__objc_classlist: 0x110
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2ae0
+  __DATA_CONST.__objc_selrefs: 0x2af8
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0xd8
   __DATA_CONST.__objc_arraydata: 0xa0
-  __AUTH_CONST.__auth_got: 0x770
-  __AUTH_CONST.__const: 0x1b10
+  __AUTH_CONST.__auth_got: 0x778
+  __AUTH_CONST.__const: 0x1b40
   __AUTH_CONST.__cfstring: 0x5c60
-  __AUTH_CONST.__objc_const: 0x8138
+  __AUTH_CONST.__objc_const: 0x81a0
   __AUTH_CONST.__objc_intobj: 0x180
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0xd8
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH.__objc_data: 0xaa0
-  __DATA.__objc_ivar: 0x344
+  __DATA.__objc_ivar: 0x34c
   __DATA.__data: 0x600
   __DATA.__bss: 0x400
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /System/Library/PrivateFrameworks/login.framework/Versions/A/login
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2770
-  Symbols:   4683
-  CStrings:  3628
+  Functions: 2779
+  Symbols:   4697
+  CStrings:  3636
 
Symbols:
+ -[POAgentAuthenticationProcess configurationQueue]
+ -[POAgentAuthenticationProcess setConfigurationQueue:]
+ -[PODaemonProcess configurationQueue]
+ -[PODaemonProcess setConfigurationQueue:]
+ -[POExtension authorizationDidFailWithOtherVersionError:]
+ -[POExtension initWithExtensionBundleIdentifier:delegate:]
+ -[POExtension initWithExtensionBundleIdentifier:extensionManager:delegate:]
+ GCC_except_table120
+ GCC_except_table124
+ GCC_except_table131
+ GCC_except_table153
+ GCC_except_table162
+ GCC_except_table181
+ GCC_except_table241
+ GCC_except_table250
+ GCC_except_table271
+ GCC_except_table277
+ GCC_except_table336
+ GCC_except_table347
+ GCC_except_table54
+ GCC_except_table563
+ GCC_except_table566
+ GCC_except_table72
+ GCC_except_table91
+ OBJC_IVAR_$_POAgentAuthenticationProcess._configurationQueue
+ OBJC_IVAR_$_PODaemonProcess._configurationQueue
+ ___59-[POAgentAuthenticationProcess handleConfigurationChanged:]_block_invoke
+ ___block_descriptor_42_e8_32s_e5_v8?0l
+ _dispatch_async_and_wait
+ _objc_msgSend$authorization:didCompleteWithCredential:error:
+ _objc_msgSend$configurationQueue
+ _objc_msgSend$initWithExtensionBundleIdentifier:extensionManager:delegate:
- -[POExtension initWithExtensionBundleIdentifier:]
- -[POExtension initWithExtensionBundleIdentifier:extensionManager:]
- GCC_except_table122
- GCC_except_table129
- GCC_except_table133
- GCC_except_table152
- GCC_except_table161
- GCC_except_table180
- GCC_except_table240
- GCC_except_table249
- GCC_except_table260
- GCC_except_table268
- GCC_except_table273
- GCC_except_table332
- GCC_except_table343
- GCC_except_table557
- GCC_except_table560
- _objc_msgSend$initWithExtensionBundleIdentifier:extensionManager:
CStrings:
+ "-[POExtension authorizationDidFailWithOtherVersionError:]"
+ "@40@0:8@16@24@32"
+ "T@\"NSObject<OS_dispatch_queue>\",&,V_configurationQueue"
+ "_configurationQueue"
+ "authorizationDidFailWithOtherVersionError:"
+ "com.apple.AppSSOAgent.PlatformSSO.configuration"
+ "configurationQueue"
+ "initWithExtensionBundleIdentifier:delegate:"
+ "initWithExtensionBundleIdentifier:extensionManager:delegate:"
+ "setConfigurationQueue:"
+ "v24@0:8@\"NSString\"16"
+ "\xf0\xf01"
- "$"
- "initWithExtensionBundleIdentifier:"
- "initWithExtensionBundleIdentifier:extensionManager:"
- "\xf0\xf0!"
```
