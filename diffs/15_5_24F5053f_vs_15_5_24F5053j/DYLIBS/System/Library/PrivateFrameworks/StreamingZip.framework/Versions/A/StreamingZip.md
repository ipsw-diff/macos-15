## StreamingZip

> `/System/Library/PrivateFrameworks/StreamingZip.framework/Versions/A/StreamingZip`

```diff

-226.0.0.0.0
-  __TEXT.__text: 0x27348
+226.120.1.0.0
+  __TEXT.__text: 0x27784
   __TEXT.__auth_stubs: 0xcd0
-  __TEXT.__objc_methlist: 0xe6c
+  __TEXT.__objc_methlist: 0xe84
   __TEXT.__const: 0x150
-  __TEXT.__cstring: 0x8701
+  __TEXT.__cstring: 0x8761
   __TEXT.__gcc_except_tab: 0x2b8
   __TEXT.__oslogstring: 0x544
-  __TEXT.__unwind_info: 0x450
+  __TEXT.__unwind_info: 0x458
   __TEXT.__eh_frame: 0xb4
   __TEXT.__objc_classname: 0x1b3
-  __TEXT.__objc_methname: 0x2f97
-  __TEXT.__objc_methtype: 0xd7e
-  __TEXT.__objc_stubs: 0x23c0
+  __TEXT.__objc_methname: 0x2fed
+  __TEXT.__objc_methtype: 0xd9f
+  __TEXT.__objc_stubs: 0x2420
   __DATA_CONST.__got: 0xb8
-  __DATA_CONST.__const: 0x760
+  __DATA_CONST.__const: 0x768
   __DATA_CONST.__objc_classlist: 0x40
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa80
+  __DATA_CONST.__objc_selrefs: 0xa98
   __AUTH_CONST.__auth_got: 0x678
   __AUTH_CONST.__const: 0x620
-  __AUTH_CONST.__cfstring: 0x4640
-  __AUTH_CONST.__objc_const: 0x1a10
+  __AUTH_CONST.__cfstring: 0x4680
+  __AUTH_CONST.__objc_const: 0x1a30
   __AUTH.__objc_data: 0x280
   __DATA.__objc_protorefs: 0x10
   __DATA.__objc_classrefs: 0xf8
   __DATA.__objc_superrefs: 0x38
-  __DATA.__objc_ivar: 0x168
+  __DATA.__objc_ivar: 0x16c
   __DATA.__data: 0x448
   __DATA.__bss: 0xc1
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 391
-  Symbols:   1288
-  CStrings:  1496
+  Functions: 394
+  Symbols:   1296
+  CStrings:  1504
 
Symbols:
+ -[SZExtractor _setUpWithPath:options:error:]
+ -[SZExtractor initWithOptions:error:]
+ -[SZExtractor initWithPath:options:error:]
+ GCC_except_table383
+ OBJC_IVAR_$_StreamingUnzipper._passthroughEnabled
+ _SZExtractorOptionsNoPassthrough
+ _SZThrowForSetupError
+ _objc_msgSend$_setUpWithPath:options:error:
+ _objc_msgSend$initWithOptions:error:
+ _objc_msgSend$initWithPath:options:error:
+ _objc_msgSend$userInfo
- -[SZExtractor _setUpWithPath:options:]
- GCC_except_table380
- _objc_msgSend$_setUpWithPath:options:
CStrings:
+ "-[SZExtractor _setUpWithPath:options:error:]"
+ "@32@0:8@16^@24"
+ "B40@0:8@16@24^@32"
+ "Byte stream does not represent a valid streamable archive"
+ "SZExtractorOptionsNoPassthrough"
+ "_passthroughEnabled"
+ "_setUpWithPath:options:error:"
+ "initWithOptions:error:"
+ "initWithPath:options:error:"
+ "userInfo"
- "-[SZExtractor _setUpWithPath:options:]"
- "_setUpWithPath:options:"
```
