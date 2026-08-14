## ScreenReader

> `/System/Library/PrivateFrameworks/ScreenReader.framework/Versions/A/ScreenReader`

```diff

-964.12.10.0.0
-  __TEXT.__text: 0x296e2c
+964.12.12.0.0
+  __TEXT.__text: 0x296fdc
   __TEXT.__auth_stubs: 0x2b60
-  __TEXT.__objc_methlist: 0x23bdc
+  __TEXT.__objc_methlist: 0x23bec
   __TEXT.__const: 0xdaa
   __TEXT.__gcc_except_tab: 0x320c
-  __TEXT.__cstring: 0x1f98e
+  __TEXT.__cstring: 0x1f99e
   __TEXT.__dlopen_cstrs: 0x66b
   __TEXT.__oslogstring: 0x339
   __TEXT.__ustring: 0x48

   __TEXT.__swift5_types: 0x4
   __TEXT.__dof_SCRMapEle: 0x47e
   __TEXT.__dof_SCRSpeech: 0x21a
-  __TEXT.__unwind_info: 0x7f40
+  __TEXT.__unwind_info: 0x7f48
   __TEXT.__objc_classname: 0x324c
-  __TEXT.__objc_methname: 0x52444
+  __TEXT.__objc_methname: 0x524a3
   __TEXT.__objc_methtype: 0x7e17
-  __TEXT.__objc_stubs: 0x3ebe0
+  __TEXT.__objc_stubs: 0x3ec40
   __DATA_CONST.__got: 0x1a98
   __DATA_CONST.__const: 0x2110
   __DATA_CONST.__objc_classlist: 0xcf0
   __DATA_CONST.__objc_catlist: 0x78
   __DATA_CONST.__objc_protolist: 0x218
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x129f0
+  __DATA_CONST.__objc_selrefs: 0x12a08
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x9a0
   __DATA_CONST.__objc_arraydata: 0x7d8
   __AUTH_CONST.__auth_got: 0x15c0
-  __AUTH_CONST.__const: 0x3a00
-  __AUTH_CONST.__cfstring: 0x24160
+  __AUTH_CONST.__const: 0x3a20
+  __AUTH_CONST.__cfstring: 0x241c0
   __AUTH_CONST.__objc_const: 0x2efd8
   __AUTH_CONST.__objc_arrayobj: 0x1b0
   __AUTH_CONST.__objc_intobj: 0x1428

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 12629
-  Symbols:   27856
-  CStrings:  18372
+  Functions: 12631
+  Symbols:   27861
+  CStrings:  18378
 
Symbols:
+ -[SCRSpeechSettings setDefaultVoiceSelection:rate:pitch:volume:]
+ -[SCRSpeechSettings systemLanguageIDInVoiceSettings]
+ ___45-[SCRApplication menuWasDestroyedWithUIMenu:]_block_invoke
+ _objc_msgSend$languageIdentifier
+ _objc_msgSend$setDefaultVoiceSelection:rate:pitch:volume:
+ _objc_msgSend$systemLanguageIDInVoiceSettings
- -[SCRSpeechSettings setDefaultVoiceSelection:languageID:rate:pitch:volume:]
CStrings:
+ "en-HK"
+ "languageIdentifier"
+ "setDefaultVoiceSelection:rate:pitch:volume:"
+ "systemLanguageIDInVoiceSettings"
+ "yue"
+ "zh-HK"
```
