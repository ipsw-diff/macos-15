## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/Versions/A/ImageIO`

```diff

-2661.5.2.0.0
-  __TEXT.__text: 0x2edcd4
+2661.6.2.0.0
+  __TEXT.__text: 0x2ee078
   __TEXT.__auth_stubs: 0x47f0
   __TEXT.__objc_methlist: 0xb58
   __TEXT.__const: 0x14328
-  __TEXT.__gcc_except_tab: 0x19adc
-  __TEXT.__cstring: 0x4acbb
+  __TEXT.__gcc_except_tab: 0x19ae4
+  __TEXT.__cstring: 0x4af9c
   __TEXT.__oslogstring: 0x17
   __TEXT.__ustring: 0x20
   __TEXT.__unwind_info: 0xa9b8

   - /usr/lib/libexpat.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 9880
+  Functions: 9881
   Symbols:   15268
-  CStrings:  9341
+  CStrings:  9350
 
Functions:
~ __ZN14TIFFReadPlugin10initializeEP13IIODictionary : 2836 -> 2904
~ __ZN12IIOImageRead16getBytesAtOffsetEPvmm : 472 -> 464
~ __ZN19AppleJPEGReadPlugin10initializeEP13IIODictionary : 5880 -> 6220
~ __ZN13IIOReadPlugin19imageBlockSetCreateEP15CGImageProvider6CGSize6CGRectmPKP12CGImageBlockPv : 484 -> 572
~ __ZN19IIOImageReadSession8getBytesEPvm : 96 -> 172
~ __ZN14IIO_Reader_PVR13getImageCountEP19IIOImageReadSessionP13IIODictionaryP19CGImageSourceStatusPj : 676 -> 728
~ __Z10AlphaBlendItElPK13vImage_BufferS2_S2_j : 176 -> 252
~ __Z10AlphaBlendIjElPK13vImage_BufferS2_S2_j : 152 -> 228
~ __ZN13PSDReadPlugin21decodeBlockSubsampledER20IIODecodeFrameParamsjj : 2352 -> 2388
~ _IIOCreateMemoryString : 1108 -> 1112
~ __ZN13JP2ReadPlugin27checkContinousCodestreamBoxEP10IIOScannery : 224 -> 216
~ __ZN19AppleJPEGReadPlugin20copyImageBlockSetImpEP7InfoRecP15CGImageProvider6CGRect6CGSizePK14__CFDictionary : 3908 -> 3976
~ _ZN19AppleJPEGReadPlugin10initializeEP13IIODictionary.cold.2 : 44 -> 64
~ _ZN19AppleJPEGReadPlugin10initializeEP13IIODictionary.cold.3 : 24 -> 44
~ _ZN19AppleJPEGReadPlugin10initializeEP13IIODictionary.cold.4 : 144 -> 24
~ _ZN19AppleJPEGReadPlugin10initializeEP13IIODictionary.cold.5 : 32 -> 144
+ _ZN19AppleJPEGReadPlugin10initializeEP13IIODictionary.cold.6
CStrings:
+ "*** ERROR: IIOImageReadSession::getBytes: count:%ld   offset:%ld   imgSize:%ld\n"
+ "*** ERROR: combination of samplesPerPixel(%d) and extraSamples(%d) is not supported\n"
+ "*** ERROR: failed to read %d bytes at offset %ld\n"
+ "*** ERROR: invalid rowBytes[%d] < width[%d]*bpc[%d]*4\n"
+ "*** ERROR: rect:{%g,%g,%g,%g} - invalid height\n"
+ "*** ERROR: rect:{%g,%g,%g,%g} - invalid width\n"
+ "*** ERROR: unexpected data '%02X%02X %02X%02X' at offset %ld\n"
+ "*** ERROR: unsupported bitsPerComponent[%d] for PHOTOMETRIC_YCBCR\n"
+ "*** invalid PVR file: Bits Per Pixel: %d\n"
+ "AlphaBlend"
- "*** ERROR: samplesPerPixel(%d) and extraSamples(%d) don't match\n"
```
