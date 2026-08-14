## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/Versions/A/ImageIO`

```diff

-2661.4.9.0.0
-  __TEXT.__text: 0x2eddac
-  __TEXT.__auth_stubs: 0x47e0
+2661.5.1.0.0
+  __TEXT.__text: 0x2edc50
+  __TEXT.__auth_stubs: 0x47f0
   __TEXT.__objc_methlist: 0xb58
   __TEXT.__const: 0x14328
-  __TEXT.__gcc_except_tab: 0x19ac4
-  __TEXT.__cstring: 0x4aa6c
+  __TEXT.__gcc_except_tab: 0x19adc
+  __TEXT.__cstring: 0x4ac39
   __TEXT.__oslogstring: 0x17
   __TEXT.__ustring: 0x20
   __TEXT.__unwind_info: 0xa9b8

   __TEXT.__objc_methtype: 0x1efc
   __TEXT.__objc_stubs: 0x21c0
   __DATA_CONST.__got: 0x5b8
-  __DATA_CONST.__const: 0xb430
+  __DATA_CONST.__const: 0xb450
   __DATA_CONST.__objc_classlist: 0x48
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0xa08
   __DATA_CONST.__objc_superrefs: 0x30
   __DATA_CONST.__objc_arraydata: 0x20
-  __AUTH_CONST.__auth_got: 0x2408
-  __AUTH_CONST.__const: 0x3c3e0
+  __AUTH_CONST.__auth_got: 0x2410
+  __AUTH_CONST.__const: 0x3c400
   __AUTH_CONST.__cfstring: 0xd9e0
   __AUTH_CONST.__objc_const: 0xe50
   __AUTH_CONST.__objc_doubleobj: 0x20

   __DATA.__objc_ivar: 0x84
   __DATA.__data: 0x24a8
   __DATA.__crash_info: 0x40
-  __DATA.__bss: 0x5818
+  __DATA.__bss: 0x5828
   __DATA.__common: 0x144c
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/ColorSync.framework/Versions/A/ColorSync

   - /usr/lib/libexpat.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 9875
-  Symbols:   15260
-  CStrings:  9332
+  Functions: 9879
+  Symbols:   15268
+  CStrings:  9339
 
Symbols:
+ IIO_CreateIdentityToken
+ _IIO_CreateIdentityToken
+ _IIO_GetIdentityToken
+ _Z38IIO_CreateIOSurfaceWithFormatAndBuffermmmjPhmb
+ __Z28IIO_CreateIOSurfaceFromImageP7CGImage
+ __Z29IIO_CreateIOSurfaceWithFormatmmmjb
+ __Z37IIO_CreateBiPlanarIOSurfaceWithFormatj6CGSizeS_jPhjyjyjbPi
+ __Z38IIO_CreateIOSurfaceWithFormatAndBuffermmmjPhmb
+ __ZL14gIdentityToken
+ __ZL34IIO_create_RGhA_IOSurfaceFromImageP7CGImagej
+ __ZN13PNGReadPlugin19DecodeComposedImageEP19IIOImageReadSessionP13GlobalPNGInfoRK14ReadPluginDataRK13PNGPluginDataRK6CGRectPhm
+ __ZN13PNGReadPlugin28EnsureFrameBufferQueueExistsEP19IIOImageReadSessionP13GlobalPNGInfoRK14ReadPluginDataRK13PNGPluginDatal
+ __ZZ23IIO_CreateIdentityTokenE13clientTokenID
+ __ZZ23IIO_CreateIdentityTokenE9onceToken
+ ___IIO_CreateIdentityToken_block_invoke
+ ____ZN13PNGReadPlugin28EnsureFrameBufferQueueExistsEP19IIOImageReadSessionP13GlobalPNGInfoRK14ReadPluginDataRK13PNGPluginDatal_block_invoke
+ _mach_port_mod_refs
- _Z38IIO_CreateIOSurfaceWithFormatAndBuffermmmjPhmbj
- __Z28IIO_CreateIOSurfaceFromImageP7CGImagej
- __Z29IIO_CreateIOSurfaceWithFormatmmmjbj
- __Z37IIO_CreateBiPlanarIOSurfaceWithFormatj6CGSizeS_jPhjyjyjbjPi
- __Z38IIO_CreateIOSurfaceWithFormatAndBuffermmmjPhmbj
- __ZL34IIO_create_RGhA_IOSurfaceFromImageP7CGImagejj
- __ZN13PNGReadPlugin19DecodeComposedImageEP19IIOImageReadSessionP13GlobalPNGInfoRK14ReadPluginDataRK13PNGPluginDataRK6CGRectPhmj
- __ZN13PNGReadPlugin28EnsureFrameBufferQueueExistsEP19IIOImageReadSessionP13GlobalPNGInfoRK14ReadPluginDataRK13PNGPluginDatalj
- ____ZN13PNGReadPlugin28EnsureFrameBufferQueueExistsEP19IIOImageReadSessionP13GlobalPNGInfoRK14ReadPluginDataRK13PNGPluginDatalj_block_invoke
CStrings:
+ "    AppleJPEGReadPlugin - offset: %ld   size: %d\n"
+ "    HEIFReadPlugin(JPEG) - offset: %ld   size: %d\n"
+ "*** ERROR: CGImageCreateFlexRangeMetadata failed to create gainmapdata (err=%d)\n"
+ "*** ERROR: CGImagePluginInitThumbJPEGAtOffsetWithOptions is called with offset: %ld   size: %ld\n"
+ "offset:%ld  size:%ld"
+ "❌ ERROR: IIO_CreateIdentityToken should not be called from the ImageIOXPCService\n"
+ "❌ ERROR: failed to create token. 'task_create_identity_token' returned %ld"
```
