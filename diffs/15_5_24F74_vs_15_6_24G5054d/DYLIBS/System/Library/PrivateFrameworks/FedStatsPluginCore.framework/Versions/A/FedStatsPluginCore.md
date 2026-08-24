## FedStatsPluginCore

> `/System/Library/PrivateFrameworks/FedStatsPluginCore.framework/Versions/A/FedStatsPluginCore`

```diff

-40.0.0.0.0
-  __TEXT.__text: 0x113c0
+46.0.0.0.0
+  __TEXT.__text: 0x114bc
   __TEXT.__auth_stubs: 0x260
-  __TEXT.__objc_methlist: 0xc54
+  __TEXT.__objc_methlist: 0xc3c
   __TEXT.__const: 0xa8
-  __TEXT.__cstring: 0x1fa0
+  __TEXT.__cstring: 0x1fac
   __TEXT.__gcc_except_tab: 0x2c
-  __TEXT.__oslogstring: 0x1189
+  __TEXT.__oslogstring: 0x1136
   __TEXT.__unwind_info: 0x2f0
   __TEXT.__objc_classname: 0x3ef
-  __TEXT.__objc_methname: 0x25b2
-  __TEXT.__objc_methtype: 0x385
-  __TEXT.__objc_stubs: 0x20c0
+  __TEXT.__objc_methname: 0x2594
+  __TEXT.__objc_methtype: 0x37a
+  __TEXT.__objc_stubs: 0x2080
   __DATA_CONST.__got: 0x288
   __DATA_CONST.__const: 0xf0
   __DATA_CONST.__objc_classlist: 0xf8
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x990
+  __DATA_CONST.__objc_selrefs: 0x980
   __DATA_CONST.__objc_superrefs: 0xa0
   __DATA_CONST.__objc_arraydata: 0x118
   __AUTH_CONST.__auth_got: 0x140
   __AUTH_CONST.__const: 0x260
-  __AUTH_CONST.__cfstring: 0x2640
+  __AUTH_CONST.__cfstring: 0x2620
   __AUTH_CONST.__objc_const: 0x1f68
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__objc_dictobj: 0x28

   - /System/Library/PrivateFrameworks/Trial.framework/Versions/A/Trial
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 306
-  Symbols:   936
-  CStrings:  889
+  Functions: 304
+  Symbols:   931
+  CStrings:  885
 
Symbols:
+ +[FedStatsPluginCoreConsentCheckHelper checkChinaAIEligibility]
+ -[FedStatsPluginRecipe checkDeviceOSVersionFilterWithError:]
+ _objc_msgSend$checkChinaAIEligibility
+ _objc_msgSend$checkDeviceOSVersionFilter:
+ _objc_msgSend$checkDeviceOSVersionFilterWithError:
- +[FedStatsPluginCoreConsentCheckHelper checkMCN]
- +[FedStatsPluginCoreConsentCheckHelper checkRSAEligibilityForApple]
- +[FedStatsPluginCoreConsentCheckHelper checkRSAEligibilityForCondition:]
- +[FedStatsPluginCoreConsentCheckHelper checkRSAEligibilityForThirdParty]
- _OUTLINED_FUNCTION_7
- _objc_msgSend$checkMCN
- _objc_msgSend$checkRSAEligibilityForApple
- _objc_msgSend$checkRSAEligibilityForCondition:
- _objc_msgSend$checkRSAEligibilityForThirdParty
- _objc_msgSend$uppercaseString
CStrings:
+ "Cannot load recipe."
+ "Checking device filter %@."
+ "Device is not China AI eligible."
+ "Regional safety consent for China AI is required for this use-case but not given"
+ "The plugin should not run for %@ as device filter: %@."
+ "checkChinaAIEligibility"
+ "checkDeviceOSVersionFilter:"
+ "checkDeviceOSVersionFilterWithError:"
+ "deviceOSVersionFilter"
+ "needsCNAI"
- "B20@0:8B16"
- "CN"
- "Mainland CN consent is required for this use-case but not given"
- "Regional safety consent for 3rd party is required for this use-case but not given"
- "Regional safety consent for Apple is required for this use-case but not given"
- "This feature is turned off. No consent could be given."
- "checkMCN"
- "checkRSAEligibilityForApple"
- "checkRSAEligibilityForCondition:"
- "checkRSAEligibilityForThirdParty"
- "needsMCN"
- "needsRSAFirst"
- "needsRSAThird"
- "uppercaseString"
```
