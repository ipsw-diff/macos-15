## InputAnalyticsServer

> `/System/Library/PrivateFrameworks/InputAnalyticsServer.framework/Versions/A/InputAnalyticsServer`

```diff

-64.503.0.0.0
-  __TEXT.__text: 0x39f54
+64.504.0.0.0
+  __TEXT.__text: 0x3ae8c
   __TEXT.__auth_stubs: 0xad0
-  __TEXT.__objc_methlist: 0x2864
+  __TEXT.__objc_methlist: 0x2964
   __TEXT.__const: 0x1e0
-  __TEXT.__cstring: 0x2819
-  __TEXT.__oslogstring: 0x3c26
+  __TEXT.__cstring: 0x28d9
+  __TEXT.__oslogstring: 0x3c56
   __TEXT.__gcc_except_tab: 0x318
   __TEXT.__swift5_typeref: 0x115
   __TEXT.__swift5_capture: 0x88

   __TEXT.__swift5_types: 0x8
   __TEXT.__swift_as_entry: 0x1c
   __TEXT.__swift_as_ret: 0x1c
-  __TEXT.__unwind_info: 0x9d8
+  __TEXT.__unwind_info: 0xa00
   __TEXT.__eh_frame: 0x310
-  __TEXT.__objc_classname: 0x545
-  __TEXT.__objc_methname: 0x6334
-  __TEXT.__objc_methtype: 0x852
-  __TEXT.__objc_stubs: 0x4ba0
-  __DATA_CONST.__got: 0xb78
-  __DATA_CONST.__const: 0x7c0
-  __DATA_CONST.__objc_classlist: 0x178
+  __TEXT.__objc_classname: 0x586
+  __TEXT.__objc_methname: 0x64d2
+  __TEXT.__objc_methtype: 0x885
+  __TEXT.__objc_stubs: 0x4c60
+  __DATA_CONST.__got: 0xc30
+  __DATA_CONST.__const: 0x7f8
+  __DATA_CONST.__objc_classlist: 0x188
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1568
+  __DATA_CONST.__objc_selrefs: 0x15a8
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0xf8
+  __DATA_CONST.__objc_superrefs: 0x100
   __DATA_CONST.__objc_arraydata: 0x90
   __AUTH_CONST.__auth_got: 0x578
-  __AUTH_CONST.__const: 0xcf8
-  __AUTH_CONST.__cfstring: 0x2a60
-  __AUTH_CONST.__objc_const: 0x47c0
+  __AUTH_CONST.__const: 0xd38
+  __AUTH_CONST.__cfstring: 0x2ac0
+  __AUTH_CONST.__objc_const: 0x4970
   __AUTH_CONST.__objc_arrayobj: 0xa8
-  __AUTH_CONST.__objc_intobj: 0x720
-  __AUTH.__objc_data: 0xef0
+  __AUTH_CONST.__objc_intobj: 0x7e0
+  __AUTH.__objc_data: 0xf90
   __AUTH.__data: 0x50
-  __DATA.__objc_ivar: 0x354
+  __DATA.__objc_ivar: 0x360
   __DATA.__data: 0x3d8
-  __DATA.__bss: 0x2d0
+  __DATA.__bss: 0x2e0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/PrivateFrameworks/Anvil.framework/Versions/A/Anvil

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1209
-  Symbols:   467
-  CStrings:  1802
+  Functions: 1232
+  Symbols:   490
+  CStrings:  1825
 
Symbols:
+ _IAPayloadKeyImageGenerationBlockingCategory
+ _IAPayloadKeyImageGenerationBlockingInputOutputCategory
+ _IAPayloadKeyImageGenerationBlockingSubCategory
+ _IAPayloadValueGenmojiCreationFailReasonCancel
+ _IAPayloadValueGenmojiCreationFailReasonInputLanguage
+ _IAPayloadValueGenmojiCreationFailReasonInputLexicon
+ _IAPayloadValueGenmojiCreationFailReasonPolicyViolationDetectedFacesPolicy
+ _IAPayloadValueGenmojiCreationFailReasonPolicyViolationNonPersonalizedGeneratedImageCaptionPolicy
+ _IAPayloadValueGenmojiUnspecified
+ _IAPayloadValueImageGenerationBlockingCategoryImageRejection
+ _IAPayloadValueImageGenerationBlockingCategoryPeoplePolicyViolation
+ _IAPayloadValueImageGenerationBlockingCategorySoftwareError
+ _IAPayloadValueImageGenerationBlockingCategoryTextPromptRejection
+ _IAPayloadValueImageGenerationBlockingInputOutputCategoryInput
+ _IAPayloadValueImageGenerationBlockingInputOutputCategoryOutput
+ _IAPayloadValueImageGenerationBlockingSubCategoryLexiconOrLanguage
+ _IAPayloadValueImageGenerationBlockingSubCategoryMultiplePeople
+ _IAPayloadValueImageGenerationBlockingSubCategoryUnexpectedPeopleInOutput
+ _IAPayloadValueImageGenerationBlockingSubCategoryUnspecified
+ _IAPayloadValueImageGenerationFeatureGenmoji
+ _IAPayloadValueImageGenerationFeatureImagePlayground
+ _IAPayloadValueImageGenerationFeatureImageWand
+ _IASignalImageGenerationPreviewGenerated
+ _IASignalImageGenerationPreviewNotGenerated
- _IAPayloadKeyGenmojiCreationErrorDescription
CStrings:
+ "%@"
+ "@\"BMWritingToolsComposeAndAdjust\""
+ "IAImageGeneration"
+ "IASImageGenerationResultAnalyzer"
+ "IASImageGenerationResultAnalyzer.m"
+ "IASImageGenerationResultEvent"
+ "Obfuscating subcategory %{sensitive}@"
+ "Publishing"
+ "Q40@0:8@16@24Q32"
+ "T@\"BMWritingToolsComposeAndAdjust\",&,N,V_biomeWritingToolsComposeAndAdjust"
+ "_biomeWritingToolsComposeAndAdjust"
+ "biomeWritingToolsComposeAndAdjust"
+ "com.apple.inputAnalytics.imageGenerationResult"
+ "com.apple.inputAnalytics.server.IASImageGenerationResultAnalyzer"
+ "featureForFeature:"
+ "generationResult"
+ "getObfuscatedFailureReasonString"
+ "rejectionCategory"
+ "rejectionCategoryDetails"
+ "rejectionCategoryDetailsForBlockingSubCategory:"
+ "rejectionCategoryForBlockingCategory:"
+ "rejectionInputOutput"
+ "rejectionInputOutputForBlockingInputOutputCategory:"
+ "setBiomeWritingToolsComposeAndAdjust:"
+ "setValuesForKeysWithDictionary:"
+ "translateValue:withMapping:withDefaultValue:"
- "errorDescription"
- "genmojiCreationFailReasonToEnumMap"
- "shownFailReasonEnum"
```
