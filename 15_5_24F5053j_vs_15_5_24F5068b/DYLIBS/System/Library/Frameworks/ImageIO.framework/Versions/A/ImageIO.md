## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/Versions/A/ImageIO`

```diff

-2661.5.1.0.0
-  __TEXT.__text: 0x2edc50
+2661.5.2.0.0
+  __TEXT.__text: 0x2edcd4
   __TEXT.__auth_stubs: 0x47f0
   __TEXT.__objc_methlist: 0xb58
   __TEXT.__const: 0x14328
   __TEXT.__gcc_except_tab: 0x19adc
-  __TEXT.__cstring: 0x4ac39
+  __TEXT.__cstring: 0x4acbb
   __TEXT.__oslogstring: 0x17
   __TEXT.__ustring: 0x20
   __TEXT.__unwind_info: 0xa9b8

   - /usr/lib/libexpat.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 9879
+  Functions: 9880
   Symbols:   15268
-  CStrings:  9339
+  CStrings:  9341
 
Functions:
~ __ZN14TIFFReadPlugin10initializeEP13IIODictionary : 2800 -> 2836
~ __ZN14GIFWritePlugin16writeSingleFrameEv : 2800 -> 2852
~ _ZN14TIFFReadPlugin10initializeEP13IIODictionary.cold.4 : 24 -> 44
+ _ZN14TIFFReadPlugin10initializeEP13IIODictionary.cold.8
CStrings:
+ "*** ERROR: image size %d x %d is too big for a GIF\n"
+ "*** ERROR: unsupported combination PHOTOMETRIC_YCBCR and SAMPLEFORMAT_IEEEFP\n"
```
