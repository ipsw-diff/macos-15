## AssistantServices

> `/System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/AssistantServices`

```diff

-3405.21.2.0.0
-  __TEXT.__text: 0x1ba330
+3405.27.1.4.1
+  __TEXT.__text: 0x1ba678
   __TEXT.__auth_stubs: 0x1280
   __TEXT.__objc_methlist: 0x1d8dc
   __TEXT.__const: 0x440
   __TEXT.__dlopen_cstrs: 0x324
   __TEXT.__gcc_except_tab: 0x284c
-  __TEXT.__cstring: 0x3a8d8
-  __TEXT.__oslogstring: 0xffb9
+  __TEXT.__cstring: 0x3a8de
+  __TEXT.__oslogstring: 0x1007c
   __TEXT.__ustring: 0x2ac
-  __TEXT.__unwind_info: 0x7790
+  __TEXT.__unwind_info: 0x7798
   __TEXT.__objc_classname: 0x4e8b
   __TEXT.__objc_methname: 0x3a1de
   __TEXT.__objc_methtype: 0xa8df

   __DATA_CONST.__objc_superrefs: 0xde0
   __DATA_CONST.__objc_arraydata: 0x2080
   __AUTH_CONST.__auth_got: 0x950
-  __AUTH_CONST.__const: 0x8140
-  __AUTH_CONST.__cfstring: 0x266a0
+  __AUTH_CONST.__const: 0x8160
+  __AUTH_CONST.__cfstring: 0x266c0
   __AUTH_CONST.__objc_const: 0x332a0
   __AUTH_CONST.__objc_intobj: 0x2328
   __AUTH_CONST.__objc_dictobj: 0xb90

   __AUTH.__data: 0x80
   __DATA.__objc_ivar: 0x2530
   __DATA.__data: 0x40b0
-  __DATA.__bss: 0xf40
+  __DATA.__bss: 0xf50
   __DATA.__common: 0x40
   __DATA_DIRTY.__objc_data: 0x59b0
   __DATA_DIRTY.__data: 0xa0

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 11549
-  Symbols:   25483
-  CStrings:  17753
+  Functions: 11550
+  Symbols:   25486
+  CStrings:  17756
 
Symbols:
+ AFIsLocaleSupportedForSiriClassic.once
+ AFIsLocaleSupportedForSiriClassic.supportedSiriClassicLocales
+ GCC_except_table11296
+ GCC_except_table11447
+ GCC_except_table11466
+ GCC_except_table11469
+ GCC_except_table11471
+ _AFPreferencesReplacementLanguageForLocalRecognizerLanguageCode.onDeviceAlternativeForLanguageCode
+ ___AFIsLocaleSupportedForSiriClassic_block_invoke
- GCC_except_table11295
- GCC_except_table11446
- GCC_except_table11465
- GCC_except_table11468
- GCC_except_table11470
- _AFPreferencesReplacementLanguageForLocalRecognizerLanguageCode.sAlternativeLocalRecognizerLocaleOverrideMap
Functions:
~ _AFDeviceSupportsDisablingServerFallbackWhenMissingAsset : 248 -> 588
+ ___AFIsLocaleSupportedForSiriClassic_block_invoke
CStrings:
+ "%s AFDeviceSupportsDisablingServerFallbackWhenMissingAsset returns true as locale is nil"
+ "%s AFDeviceSupportsDisablingServerFallbackWhenMissingAsset returns true for unsupported server locale: %@"
+ "hi_IN"
```
