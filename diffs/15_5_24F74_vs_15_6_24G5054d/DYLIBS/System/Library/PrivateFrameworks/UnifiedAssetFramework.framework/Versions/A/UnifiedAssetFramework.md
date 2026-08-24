## UnifiedAssetFramework

> `/System/Library/PrivateFrameworks/UnifiedAssetFramework.framework/Versions/A/UnifiedAssetFramework`

```diff

-3405.8.1.0.0
-  __TEXT.__text: 0x73f2c
-  __TEXT.__auth_stubs: 0x980
-  __TEXT.__objc_methlist: 0x3518
+3406.5.1.0.0
+  __TEXT.__text: 0x746a8
+  __TEXT.__auth_stubs: 0x990
+  __TEXT.__objc_methlist: 0x3538
   __TEXT.__const: 0x100
   __TEXT.__dlopen_cstrs: 0x296
   __TEXT.__gcc_except_tab: 0x13a4
-  __TEXT.__cstring: 0x9f34
-  __TEXT.__oslogstring: 0xbfc3
-  __TEXT.__unwind_info: 0x1140
-  __TEXT.__objc_classname: 0x424
-  __TEXT.__objc_methname: 0xa0d5
+  __TEXT.__cstring: 0x9fd7
+  __TEXT.__oslogstring: 0xc09a
+  __TEXT.__unwind_info: 0x1150
+  __TEXT.__objc_classname: 0x441
+  __TEXT.__objc_methname: 0xa12e
   __TEXT.__objc_methtype: 0xfe4
-  __TEXT.__objc_stubs: 0x8240
-  __DATA_CONST.__got: 0x4e0
+  __TEXT.__objc_stubs: 0x8280
+  __DATA_CONST.__got: 0x4e8
   __DATA_CONST.__const: 0x858
-  __DATA_CONST.__objc_classlist: 0x160
+  __DATA_CONST.__objc_classlist: 0x168
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2740
+  __DATA_CONST.__objc_selrefs: 0x2750
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0xe8
   __DATA_CONST.__objc_arraydata: 0x108
-  __AUTH_CONST.__auth_got: 0x4d0
-  __AUTH_CONST.__const: 0x1b30
-  __AUTH_CONST.__cfstring: 0x4100
-  __AUTH_CONST.__objc_const: 0x4300
+  __AUTH_CONST.__auth_got: 0x4d8
+  __AUTH_CONST.__const: 0x1b60
+  __AUTH_CONST.__cfstring: 0x4140
+  __AUTH_CONST.__objc_const: 0x4390
   __AUTH_CONST.__objc_intobj: 0x240
   __AUTH_CONST.__objc_arrayobj: 0xd8
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH.__objc_data: 0xdc0
+  __AUTH.__objc_data: 0xe10
   __DATA.__objc_ivar: 0x350
   __DATA.__data: 0x230
   __DATA.__bss: 0x318

   - /System/Library/Frameworks/Network.framework/Versions/A/Network
   - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/Frameworks/SystemConfiguration.framework/Versions/A/SystemConfiguration
+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/Versions/A/CoreAnalytics
   - /System/Library/PrivateFrameworks/FeedbackLogger.framework/Versions/A/FeedbackLogger
   - /System/Library/PrivateFrameworks/MobileAsset.framework/Versions/A/MobileAsset
   - /System/Library/PrivateFrameworks/ProactiveSupport.framework/Versions/A/ProactiveSupport

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 1471
-  Symbols:   3698
-  CStrings:  3597
+  Functions: 1474
+  Symbols:   3710
+  CStrings:  3607
 
Symbols:
+ +[UAFCoreAnalyticsInstrumenter logUAFAssetSetState:assetSpecifiersAndVersions:]
+ +[UAFCoreAnalyticsInstrumenter sendCAEvent:assetSpecifier:assetVersion:]
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_UAFCoreAnalyticsInstrumenter
+ _OBJC_METACLASS_$_UAFCoreAnalyticsInstrumenter
+ __OBJC_$_CLASS_METHODS_UAFCoreAnalyticsInstrumenter
+ __OBJC_CLASS_RO_$_UAFCoreAnalyticsInstrumenter
+ __OBJC_METACLASS_RO_$_UAFCoreAnalyticsInstrumenter
+ ___72+[UAFCoreAnalyticsInstrumenter sendCAEvent:assetSpecifier:assetVersion:]_block_invoke
+ ___block_descriptor_56_e8_32s40s48s_e19_"NSDictionary"8?0l
+ _objc_msgSend$logUAFAssetSetState:assetSpecifiersAndVersions:
+ _objc_msgSend$sendCAEvent:assetSpecifier:assetVersion:
CStrings:
+ "%s Emitting asset set state CA event for %{public}@"
+ "%s Emitting asset set state CA event for specifier: %{public}@ with version: %{public}@ from asset set: %{public}@"
+ "%s Sent asset set state CA event for %{public}@"
+ "+[UAFCoreAnalyticsInstrumenter logUAFAssetSetState:assetSpecifiersAndVersions:]"
+ "@\"NSDictionary\"8@?0"
+ "UAFCoreAnalyticsInstrumenter"
+ "com.apple.MobileAsset.CN.Guardrail"
+ "com.apple.uaf.AssetSetState"
+ "logUAFAssetSetState:assetSpecifiersAndVersions:"
+ "sendCAEvent:assetSpecifier:assetVersion:"
```
