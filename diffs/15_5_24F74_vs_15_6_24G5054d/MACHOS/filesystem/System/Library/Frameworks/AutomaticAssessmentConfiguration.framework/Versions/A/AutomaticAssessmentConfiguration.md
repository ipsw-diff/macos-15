## AutomaticAssessmentConfiguration

> `/System/Library/Frameworks/AutomaticAssessmentConfiguration.framework/Versions/A/AutomaticAssessmentConfiguration`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_protolist`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH.__objc_data`
- `__DATA.__data`

```diff

-14.2.9.0.0
-  __TEXT.__text: 0x244c
+14.6.1.0.0
+  __TEXT.__text: 0x24ac
   __TEXT.__auth_stubs: 0x140
   __TEXT.__objc_methlist: 0x414
   __TEXT.__const: 0x70
   __TEXT.__cstring: 0x27f
   __TEXT.__unwind_info: 0x138
   __TEXT.__objc_classname: 0xb0
-  __TEXT.__objc_methname: 0xe47
+  __TEXT.__objc_methname: 0xeb2
   __TEXT.__objc_methtype: 0x1ee
-  __TEXT.__objc_stubs: 0xa20
+  __TEXT.__objc_stubs: 0xa60
   __DATA_CONST.__got: 0xb8
   __DATA_CONST.__const: 0x28
   __DATA_CONST.__objc_classlist: 0x28
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x338
+  __DATA_CONST.__objc_selrefs: 0x348
   __DATA_CONST.__objc_superrefs: 0x20
   __AUTH_CONST.__auth_got: 0xa8
   __AUTH_CONST.__const: 0x80
   __AUTH_CONST.__cfstring: 0x160
-  __AUTH_CONST.__objc_const: 0x780
+  __AUTH_CONST.__objc_const: 0x7a0
   __AUTH.__objc_data: 0x190
-  __DATA.__objc_ivar: 0x50
+  __DATA.__objc_ivar: 0x54
   __DATA.__data: 0xc0
   __DATA.__bss: 0x10
   - /System/Library/Frameworks/AutomaticAssessmentConfiguration.framework/Versions/A/Frameworks/AACClient.framework/Versions/A/AACClient

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 93
-  Symbols:   295
-  CStrings:  190
+  Symbols:   298
+  CStrings:  193
 
Symbols:
+ OBJC_IVAR_$_AEAssessmentConfiguration._allowsAccessibilityTypingFeedback
+ _objc_msgSend$allowsAccessibilityTypingFeedback
+ _objc_msgSend$setAllowsAccessibilityTypingFeedback:
Functions:
~ +[AEAssessmentConfiguration configurationFromWrapper:] : 536 -> 548
~ -[AEAssessmentConfiguration hash] : 580 -> 628
~ -[AEAssessmentConfiguration configurationWrapper] : 440 -> 452
~ -[AEAssessmentConfiguration copyWithZone:] : 236 -> 244
~ -[AEAssessmentConfiguration isEqualToConfiguration:] : 556 -> 572
CStrings:
+ "_allowsAccessibilityTypingFeedback"
+ "allowsAccessibilityTypingFeedback"
+ "setAllowsAccessibilityTypingFeedback:"
```
