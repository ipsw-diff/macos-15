## MobileAsset

> `/System/Library/PrivateFrameworks/MobileAsset.framework/Versions/A/MobileAsset`

```diff

-1487.120.62.0.0
-  __TEXT.__text: 0x90160
-  __TEXT.__auth_stubs: 0x790
-  __TEXT.__objc_methlist: 0x63e4
+1487.140.25.0.0
+  __TEXT.__text: 0x8faec
+  __TEXT.__auth_stubs: 0x780
+  __TEXT.__objc_methlist: 0x63dc
   __TEXT.__const: 0x288
   __TEXT.__gcc_except_tab: 0xbe4
-  __TEXT.__cstring: 0x105e7
-  __TEXT.__oslogstring: 0xa0c8
-  __TEXT.__unwind_info: 0x1b88
+  __TEXT.__cstring: 0x104c1
+  __TEXT.__oslogstring: 0xa062
+  __TEXT.__unwind_info: 0x1b78
   __TEXT.__objc_classname: 0x889
-  __TEXT.__objc_methname: 0x15004
+  __TEXT.__objc_methname: 0x14f5d
   __TEXT.__objc_methtype: 0x1768
-  __TEXT.__objc_stubs: 0x81e0
-  __DATA_CONST.__got: 0x410
-  __DATA_CONST.__const: 0xc48
+  __TEXT.__objc_stubs: 0x8120
+  __DATA_CONST.__got: 0x400
+  __DATA_CONST.__const: 0xc38
   __DATA_CONST.__objc_classlist: 0x250
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x30c8
+  __DATA_CONST.__objc_selrefs: 0x3090
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x220
   __DATA_CONST.__objc_arraydata: 0x2f0
-  __AUTH_CONST.__auth_got: 0x3d8
-  __AUTH_CONST.__const: 0x1cd0
-  __AUTH_CONST.__cfstring: 0xd9a0
+  __AUTH_CONST.__auth_got: 0x3d0
+  __AUTH_CONST.__const: 0x1cb0
+  __AUTH_CONST.__cfstring: 0xd8a0
   __AUTH_CONST.__objc_const: 0x98f0
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__objc_dictobj: 0x28

   __AUTH.__objc_data: 0x1720
   __DATA.__objc_ivar: 0x7fc
   __DATA.__data: 0x368
-  __DATA.__bss: 0x320
+  __DATA.__bss: 0x310
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2842
-  Symbols:   5560
-  CStrings:  4784
+  Functions: 2833
+  Symbols:   5541
+  CStrings:  4767
 
Symbols:
+ _objc_msgSend$isThirdPartyAssetType:
- +[MAThirdPartyCompatibility _sanitizedURLPathComponentFor:]
- _CFPreferencesCopyAppValue
- _OBJC_CLASS_$_SUCoreDevice
- __MAPreferencesCopyNSStringValue
- __MAPreferencesCopyValue
- ____MAPreferencesCopyValue_block_invoke
- ____preferencesDomainProtectionDispatchQueue_block_invoke
- __preferencesDomainProtectionDispatchQueue
- _kMobileAssetPreferencesThirdPartyStagingBucketPathComponent
- _kMobileAssetPreferencesThirdPartyStagingPathComponent
- _objc_msgSend$_sanitizedURLPathComponentFor:
- _objc_msgSend$addCharactersInString:
- _objc_msgSend$alphanumericCharacterSet
- _objc_msgSend$isBootedOSSecureInternal
- _objc_msgSend$precomposedStringWithCanonicalMapping
- _objc_msgSend$sharedDevice
- _objc_msgSend$stringValue
- _preferencesDomainProtectionDispatchQueue
- _preferencesDomainProtectionDispatchQueue.preferencesDomainQueue
- _preferencesDomainProtectionDispatchQueue.preferencesDomainQueueOnce
CStrings:
+ "Failed to retrieve server url for:(%@) from daemon. %ld"
+ "Using caching server for %{public}@ %{public}@ is enabled: %d"
- "-_"
- "MAThirdPartyCompatibility: %@ override (%@) provided, with illegal characters."
- "The cache server is: %d"
- "ThirdPartyStagingBucketPathComponent"
- "ThirdPartyStagingPathComponent"
- "[MA_PREFS] {_MAPreferencesCopyNSStringValue} invalid type for key:%{public}@ | expecting string or number or boolean"
- "_sanitizedURLPathComponentFor:"
- "addCharactersInString:"
- "alphanumericCharacterSet"
- "com.apple.MobileAsset.preferencesDomain"
- "https://mesu.apple.com/3p/%@/%@/assets/%@/%@/"
- "https://mesu.apple.com/3p/%@/assets/%@/%@/"
- "https://mesu.apple.com/3p/assets/%@/%@/"
- "https://mesu.apple.com/3p/staging/assets/%@/%@/"
- "isBootedOSSecureInternal"
- "macos"
- "precomposedStringWithCanonicalMapping"
- "sharedDevice"
- "stringValue"
```
