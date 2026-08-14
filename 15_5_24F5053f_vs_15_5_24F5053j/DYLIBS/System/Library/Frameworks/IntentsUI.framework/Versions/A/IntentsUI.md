## IntentsUI

> `/System/Library/Frameworks/IntentsUI.framework/Versions/A/IntentsUI`

```diff

-3602.0.0.0.0
-  __TEXT.__text: 0xc768
+3603.0.0.0.0
+  __TEXT.__text: 0xca58
   __TEXT.__auth_stubs: 0x370
   __TEXT.__objc_methlist: 0x1120
-  __TEXT.__const: 0xc0
+  __TEXT.__const: 0xc8
   __TEXT.__gcc_except_tab: 0x11c
   __TEXT.__cstring: 0xde1
-  __TEXT.__oslogstring: 0x580
+  __TEXT.__oslogstring: 0x6b8
   __TEXT.__ustring: 0xa
   __TEXT.__unwind_info: 0x418
   __TEXT.__objc_classname: 0x3b5
-  __TEXT.__objc_methname: 0x31d4
+  __TEXT.__objc_methname: 0x322a
   __TEXT.__objc_methtype: 0x847
-  __TEXT.__objc_stubs: 0x2aa0
-  __DATA_CONST.__got: 0x298
+  __TEXT.__objc_stubs: 0x2b20
+  __DATA_CONST.__got: 0x2a8
   __DATA_CONST.__const: 0x78
   __DATA_CONST.__objc_classlist: 0x88
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xd78
+  __DATA_CONST.__objc_selrefs: 0xd98
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x58
   __DATA_CONST.__objc_arraydata: 0x8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 354
-  Symbols:   1168
-  CStrings:  748
+  Symbols:   1174
+  CStrings:  756
 
Symbols:
+ _OBJC_CLASS_$_NSByteCountFormatter
+ _OBJC_CLASS_$_NSFileManager
+ _objc_msgSend$attributesOfItemAtPath:error:
+ _objc_msgSend$defaultManager
+ _objc_msgSend$fileSize
+ _objc_msgSend$stringFromByteCount:countStyle:
Functions:
~ +[INUIImageSizeProvider downscaledPNGImageForImage:size:error:] : 1920 -> 2672
CStrings:
+ "%s About to scale %@ image %@ from size {%f, %f} to size {%f, %f}"
+ "%s Creating image source from Data, size: %@, target image size: {%f, %f}"
+ "%s Creating image source from URL, size: %@, target image size: {%f, %f}"
+ "%s Will NOT scale %@ image %@ from size {%f, %f} to size {%f, %f} because imageSize > oldImageSize"
+ "attributesOfItemAtPath:error:"
+ "defaultManager"
+ "fileSize"
+ "stringFromByteCount:countStyle:"
```
