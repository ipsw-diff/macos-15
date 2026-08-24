## SensitiveContentAnalysisML

> `/System/Library/PrivateFrameworks/SensitiveContentAnalysisML.framework/Versions/A/SensitiveContentAnalysisML`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-93.5.5.0.0
-  __TEXT.__text: 0x5ca04
+93.5.7.0.0
+  __TEXT.__text: 0x5cb0c
   __TEXT.__auth_stubs: 0x1ce0
-  __TEXT.__objc_methlist: 0x17d4
-  __TEXT.__const: 0x2f78
-  __TEXT.__gcc_except_tab: 0x4e94
+  __TEXT.__objc_methlist: 0x1804
+  __TEXT.__const: 0x3098
+  __TEXT.__gcc_except_tab: 0x4e9c
   __TEXT.__cstring: 0x2d83
-  __TEXT.__oslogstring: 0xe30
+  __TEXT.__oslogstring: 0xe50
   __TEXT.__dlopen_cstrs: 0x58
   __TEXT.__swift5_typeref: 0x602
   __TEXT.__swift5_fieldmd: 0x3ac

   __TEXT.__swift_as_entry: 0x68
   __TEXT.__swift_as_ret: 0x90
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x2330
+  __TEXT.__unwind_info: 0x2338
   __TEXT.__eh_frame: 0x1590
   __TEXT.__objc_classname: 0x341
-  __TEXT.__objc_methname: 0x349b
-  __TEXT.__objc_methtype: 0x2ea5
-  __TEXT.__objc_stubs: 0x2c60
+  __TEXT.__objc_methname: 0x34e9
+  __TEXT.__objc_methtype: 0x2eaf
+  __TEXT.__objc_stubs: 0x2c80
   __DATA_CONST.__got: 0x510
   __DATA_CONST.__const: 0x300
   __DATA_CONST.__objc_classlist: 0x168
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xd70
+  __DATA_CONST.__objc_selrefs: 0xd80
   __DATA_CONST.__objc_superrefs: 0x100
   __DATA_CONST.__objc_arraydata: 0x1f8
   __AUTH_CONST.__auth_got: 0xe88
   __AUTH_CONST.__const: 0x27f0
   __AUTH_CONST.__cfstring: 0x1500
-  __AUTH_CONST.__objc_const: 0x3a08
+  __AUTH_CONST.__objc_const: 0x3a68
   __AUTH_CONST.__objc_arrayobj: 0xf0
   __AUTH_CONST.__objc_intobj: 0x108
   __AUTH.__objc_data: 0x1388
   __AUTH.__data: 0x2e0
-  __DATA.__objc_ivar: 0x290
-  __DATA.__data: 0x648
+  __DATA.__objc_ivar: 0x298
+  __DATA.__data: 0x530
   __DATA.__bss: 0x20f0
   __DATA.__common: 0x8
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 2123
-  Symbols:   3391
-  CStrings:  1319
+  Functions: 2127
+  Symbols:   3398
+  CStrings:  1323
 
Symbols:
+ -[SCMLImageSanitizerRequest setUserRequestID:]
+ -[SCMLImageSanitizerRequest userRequestID]
+ -[SCMLTextSanitizerRequest setUserRequestID:]
+ -[SCMLTextSanitizerRequest userRequestID]
+ OBJC_IVAR_$_SCMLImageSanitizerRequest._userRequestID
+ OBJC_IVAR_$_SCMLTextSanitizerRequest._userRequestID
+ _objc_msgSend$userRequestID
Functions:
+ -[SCMLTextSanitizerRequest userRequestID]
+ -[SCMLTextSanitizerRequest .cxx_destruct]
~ -[SCMLImageSanitizer sanitizeRequestAsynchronously:completionHandler:] : 1104 -> 1152
+ -[SCMLImageSanitizerRequest userRequestID]
+ -[SCMLImageSanitizerRequest .cxx_destruct]
~ -[SCMLTextSanitizer sanitizeRequestAsynchronously:completionHandler:] : 1448 -> 1512
CStrings:
+ "@\"NSUUID\""
+ "Begin sanitizePixelBuffer inst=%p width=%zu height=%zu attr=%s style=%u userRequestID=%@"
+ "Begin sanitizeText: inst=%p attr=%s %{sensitive}@ userRequestID=%@"
+ "T@\"NSUUID\",&,N,V_userRequestID"
+ "_userRequestID"
+ "setUserRequestID:"
+ "userRequestID"
- "!"
- "Begin sanitizePixelBuffer inst=%p width=%zu height=%zu attr=%s style=%u"
- "Begin sanitizeText: inst=%p attr=%s %{sensitive}@"
```
