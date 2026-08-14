## AppSSO

> `/System/Library/PrivateFrameworks/AppSSO.framework/Versions/A/AppSSO`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-417.120.1.0.0
-  __TEXT.__text: 0x2e064
+417.120.3.0.0
+  __TEXT.__text: 0x2e704
   __TEXT.__auth_stubs: 0x4c0
-  __TEXT.__objc_methlist: 0x19dc
+  __TEXT.__objc_methlist: 0x1a34
   __TEXT.__const: 0x140
-  __TEXT.__gcc_except_tab: 0x1dd0
-  __TEXT.__cstring: 0x2e61
+  __TEXT.__gcc_except_tab: 0x1e4c
+  __TEXT.__cstring: 0x2ed6
   __TEXT.__dlopen_cstrs: 0x6be
-  __TEXT.__oslogstring: 0x4615
-  __TEXT.__unwind_info: 0xdc8
+  __TEXT.__oslogstring: 0x4645
+  __TEXT.__unwind_info: 0xdd8
   __TEXT.__objc_classname: 0x3be
-  __TEXT.__objc_methname: 0x4b35
-  __TEXT.__objc_methtype: 0xa0a
-  __TEXT.__objc_stubs: 0x39e0
-  __DATA_CONST.__got: 0x1e8
-  __DATA_CONST.__const: 0x2e8
+  __TEXT.__objc_methname: 0x4c79
+  __TEXT.__objc_methtype: 0xa2a
+  __TEXT.__objc_stubs: 0x3ae0
+  __DATA_CONST.__got: 0x208
+  __DATA_CONST.__const: 0x2f8
   __DATA_CONST.__objc_classlist: 0xb0
   __DATA_CONST.__objc_protolist: 0x88
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1180
+  __DATA_CONST.__objc_selrefs: 0x11d0
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x80
   __DATA_CONST.__objc_arraydata: 0x28
   __AUTH_CONST.__auth_got: 0x270
-  __AUTH_CONST.__const: 0xe20
-  __AUTH_CONST.__cfstring: 0xfc0
-  __AUTH_CONST.__objc_const: 0x3fa0
+  __AUTH_CONST.__const: 0xe50
+  __AUTH_CONST.__cfstring: 0x1000
+  __AUTH_CONST.__objc_const: 0x4008
   __AUTH_CONST.__objc_intobj: 0x90
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH.__objc_data: 0xa0
-  __DATA.__objc_ivar: 0x164
+  __DATA.__objc_ivar: 0x16c
   __DATA.__data: 0x670
   __DATA.__bss: 0x260
   __DATA_DIRTY.__objc_data: 0x640

   - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/PrivateFrameworks/CoreAnalytics.framework/Versions/A/CoreAnalytics
   - /System/Library/PrivateFrameworks/FrontBoardServices.framework/Versions/A/FrontBoardServices
+  - /System/Library/PrivateFrameworks/PlugInKit.framework/Versions/A/PlugInKit
   - /System/Library/PrivateFrameworks/SharedWebCredentials.framework/Versions/A/SharedWebCredentials
   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /System/Library/PrivateFrameworks/ViewBridge.framework/Versions/A/ViewBridge
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1022
-  Symbols:   1961
-  CStrings:  1507
+  Functions: 1029
+  Symbols:   1986
+  CStrings:  1528
 
Symbols:
+ -[SOConfigurationHost configLoadTimerLock]
+ -[SOConfigurationHost configLoadTimer]
+ -[SOConfigurationHost setConfigLoadTimer:]
+ -[SOConfigurationHost setConfigLoadTimerLock:]
+ -[SOExtension _otherVersionError:]
+ -[SOExtension dealloc]
+ GCC_except_table102
+ GCC_except_table127
+ GCC_except_table128
+ GCC_except_table16
+ GCC_except_table49
+ GCC_except_table51
+ GCC_except_table59
+ GCC_except_table71
+ GCC_except_table86
+ GCC_except_table98
+ OBJC_IVAR_$_SOConfigurationHost._configLoadTimer
+ OBJC_IVAR_$_SOConfigurationHost._configLoadTimerLock
+ _NSDefaultRunLoopMode
+ _OBJC_CLASS_$_NSRunLoop
+ _OBJC_CLASS_$_NSTimer
+ _PKPlugInKitErrorDomain
+ _SONotificationBundleIdentifier
+ _SONotificationOtherVersionError
+ __41-[SOConfigurationHost _extensionsLoaded:]_block_invoke
+ ___block_descriptor_40_e8_32s_e17_v16?0"NSTimer"8l
+ _objc_msgSend$addTimer:forMode:
+ _objc_msgSend$authorizationDidFailWithOtherVersionError:
+ _objc_msgSend$configLoadTimer
+ _objc_msgSend$configLoadTimerLock
+ _objc_msgSend$domain
+ _objc_msgSend$mainRunLoop
+ _objc_msgSend$setConfigLoadTimer:
+ _objc_msgSend$timerWithTimeInterval:repeats:block:
- GCC_except_table100
- GCC_except_table122
- GCC_except_table123
- GCC_except_table48
- GCC_except_table57
- GCC_except_table58
- GCC_except_table69
- GCC_except_table82
- GCC_except_table96
CStrings:
+ "-[SOExtension _otherVersionError:]"
+ "@\"NSTimer\""
+ "Config timer fired"
+ "Handling other version error"
+ "T@\"NSObject\",&,V_configLoadTimerLock"
+ "T@\"NSTimer\",&,V_configLoadTimer"
+ "_configLoadTimer"
+ "_configLoadTimerLock"
+ "_otherVersionError:"
+ "addTimer:forMode:"
+ "authorizationDidFailWithOtherVersionError:"
+ "com.apple.AppSSO.SOExtension.OtherVersionError"
+ "configLoadTimer"
+ "configLoadTimerLock"
+ "domain"
+ "mainRunLoop"
+ "setConfigLoadTimer:"
+ "setConfigLoadTimerLock:"
+ "timerWithTimeInterval:repeats:block:"
+ "v16@?0@\"NSTimer\"8"
+ "v24@0:8@\"NSString\"16"
```
