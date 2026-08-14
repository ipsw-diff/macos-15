## UnifiedAssetFramework

> `/System/Library/PrivateFrameworks/UnifiedAssetFramework.framework/Versions/A/UnifiedAssetFramework`

```diff

-3405.5.1.0.0
-  __TEXT.__text: 0x73c30
+3405.8.1.0.0
+  __TEXT.__text: 0x73f2c
   __TEXT.__auth_stubs: 0x980
-  __TEXT.__objc_methlist: 0x34f8
+  __TEXT.__objc_methlist: 0x3518
   __TEXT.__const: 0x100
   __TEXT.__dlopen_cstrs: 0x296
   __TEXT.__gcc_except_tab: 0x13a4
-  __TEXT.__cstring: 0x9f14
-  __TEXT.__oslogstring: 0xbf32
-  __TEXT.__unwind_info: 0x1138
+  __TEXT.__cstring: 0x9f34
+  __TEXT.__oslogstring: 0xbfc3
+  __TEXT.__unwind_info: 0x1140
   __TEXT.__objc_classname: 0x424
-  __TEXT.__objc_methname: 0x9ff6
+  __TEXT.__objc_methname: 0xa0d5
   __TEXT.__objc_methtype: 0xfe4
-  __TEXT.__objc_stubs: 0x81e0
-  __DATA_CONST.__got: 0x4d8
-  __DATA_CONST.__const: 0x850
+  __TEXT.__objc_stubs: 0x8240
+  __DATA_CONST.__got: 0x4e0
+  __DATA_CONST.__const: 0x858
   __DATA_CONST.__objc_classlist: 0x160
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2720
+  __DATA_CONST.__objc_selrefs: 0x2740
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0xe8
   __DATA_CONST.__objc_arraydata: 0x108
   __AUTH_CONST.__auth_got: 0x4d0
   __AUTH_CONST.__const: 0x1b30
-  __AUTH_CONST.__cfstring: 0x40e0
-  __AUTH_CONST.__objc_const: 0x42d0
+  __AUTH_CONST.__cfstring: 0x4100
+  __AUTH_CONST.__objc_const: 0x4300
   __AUTH_CONST.__objc_intobj: 0x240
   __AUTH_CONST.__objc_arrayobj: 0xd8
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH.__objc_data: 0xdc0
-  __DATA.__objc_ivar: 0x34c
+  __DATA.__objc_ivar: 0x350
   __DATA.__data: 0x230
   __DATA.__bss: 0x318
   __DATA.__common: 0x60

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 1468
-  Symbols:   3689
-  CStrings:  3589
+  Functions: 1471
+  Symbols:   3698
+  CStrings:  3597
 
Symbols:
+ +[UAFAssetSetMetadata OSThirdPartyCompatibilityVersion:]
+ -[UAFAssetSetMetadata OSSupported:]
+ -[UAFAssetSetMetadata setThirdPartyCompatibilityVersion:]
+ -[UAFAssetSetMetadata thirdPartyCompatibilityVersion]
+ OBJC_IVAR_$_UAFAssetSetMetadata._thirdPartyCompatibilityVersion
+ _OBJC_CLASS_$_MAThirdPartyCompatibility
+ _kUAFThirdPartyCompatibilityVersion
+ _objc_msgSend$OSSupported:
+ _objc_msgSend$OSThirdPartyCompatibilityVersion:
+ _objc_msgSend$compatibilityVersionStringForAssetType:
+ _objc_msgSend$thirdPartyCompatibilityVersion
- -[UAFAssetSetMetadata OSSupported]
- _objc_msgSend$OSSupported
CStrings:
+ "%s %{public}@: Asset set %{public}@ with third party compatibility version %{public}@ incompatible with current compatibility version %{public}@"
+ "-[UAFAssetSetMetadata OSSupported:]"
+ "OSSupported:"
+ "OSThirdPartyCompatibilityVersion:"
+ "T@\"NSString\",&,N,V_thirdPartyCompatibilityVersion"
+ "ThirdPartyCompatibilityVersion"
+ "_thirdPartyCompatibilityVersion"
+ "compatibilityVersionStringForAssetType:"
+ "setThirdPartyCompatibilityVersion:"
+ "thirdPartyCompatibilityVersion"
- "-[UAFAssetSetMetadata OSSupported]"
- "OSSupported"
```
