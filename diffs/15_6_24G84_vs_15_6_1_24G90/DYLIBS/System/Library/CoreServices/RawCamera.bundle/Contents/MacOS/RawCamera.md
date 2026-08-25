## RawCamera

> `/System/Library/CoreServices/RawCamera.bundle/Contents/MacOS/RawCamera`

```diff

-1738.140.3.0.0
-  __TEXT.__text: 0x1f3364
-  __TEXT.__auth_stubs: 0x1680
+1738.140.3.0.11
+  __TEXT.__text: 0x1f3a80
+  __TEXT.__auth_stubs: 0x16a0
   __TEXT.__objc_methlist: 0x16e4
   __TEXT.__const: 0x152d6
-  __TEXT.__gcc_except_tab: 0x2d64c
+  __TEXT.__gcc_except_tab: 0x2d794
   __TEXT.__oslogstring: 0xec0
   __TEXT.__cstring: 0xee08
   __TEXT.__dof_RawCamera: 0x8f7
-  __TEXT.__unwind_info: 0xb1f8
+  __TEXT.__unwind_info: 0xb210
   __TEXT.__eh_frame: 0x278
   __TEXT.__objc_classname: 0x4b9
   __TEXT.__objc_methname: 0x3914
   __TEXT.__objc_methtype: 0xdd3
   __TEXT.__objc_stubs: 0x2da0
-  __DATA_CONST.__got: 0x9b0
+  __DATA_CONST.__got: 0x9c8
   __DATA_CONST.__const: 0x2388
   __DATA_CONST.__objc_classlist: 0x1e0
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0xcf8
   __DATA_CONST.__objc_superrefs: 0xf0
-  __DATA_CONST.__objc_arraydata: 0x3948
-  __AUTH_CONST.__auth_got: 0xb58
+  __DATA_CONST.__objc_arraydata: 0x3950
+  __AUTH_CONST.__auth_got: 0xb68
   __AUTH_CONST.__const: 0x36150
   __AUTH_CONST.__cfstring: 0x18060
   __AUTH_CONST.__objc_const: 0x48b0
-  __AUTH_CONST.__objc_arrayobj: 0x570
-  __AUTH_CONST.__objc_intobj: 0x39f0
+  __AUTH_CONST.__objc_arrayobj: 0x588
+  __AUTH_CONST.__objc_intobj: 0x3a20
   __AUTH_CONST.__objc_doubleobj: 0x480
   __AUTH_CONST.__objc_dictobj: 0x4d58
   __AUTH_CONST.__objc_floatobj: 0xc0

   - /System/Library/Frameworks/UniformTypeIdentifiers.framework/Versions/A/UniformTypeIdentifiers
   - /System/Library/PrivateFrameworks/AppleJPEG.framework/Versions/A/AppleJPEG
   - /System/Library/PrivateFrameworks/AppleJPEGXL.framework/Versions/A/AppleJPEGXL
+  - /System/Library/PrivateFrameworks/CMPhoto.framework/Versions/A/CMPhoto
   - /System/Library/PrivateFrameworks/CoreAnalytics.framework/Versions/A/CoreAnalytics
   - /System/Library/PrivateFrameworks/MobileAsset.framework/Versions/A/MobileAsset
   - /usr/lib/libSystem.B.dylib

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 6459
-  Symbols:   752
+  Functions: 6461
+  Symbols:   757
   CStrings:  4243
 
Symbols:
+ _CMPhotoDecompressionContainerCreateImageForIndex
+ _CMPhotoDecompressionContainerGetImageCount
+ _CMPhotoDecompressionSessionCreate
+ _CMPhotoDecompressionSessionCreateContainer
+ _CVPixelBufferGetDataSize
+ _kCMPhotoContainerFormatString_JFIF
+ _kCMPhotoDecompressionContainerOption_AllowedFormatsAndCodecs
+ _kCMPhotoDecompressionOption_OutputPixelFormat
- _CGImageGetBytesPerRow
- _CGImageGetHeight
- _CGImageGetWidth
```
