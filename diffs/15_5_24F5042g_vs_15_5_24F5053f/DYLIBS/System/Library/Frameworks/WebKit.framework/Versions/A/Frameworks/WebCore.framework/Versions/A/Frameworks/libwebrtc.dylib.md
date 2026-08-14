## libwebrtc.dylib

> `/System/Library/Frameworks/WebKit.framework/Versions/A/Frameworks/WebCore.framework/Versions/A/Frameworks/libwebrtc.dylib`

```diff

-621.2.1.11.5
-  __TEXT.__text: 0xa86474
-  __TEXT.__auth_stubs: 0x1310
+621.2.3.11.1
+  __TEXT.__text: 0xa87960
+  __TEXT.__auth_stubs: 0x13e0
   __TEXT.__objc_methlist: 0x14e4
   __TEXT.__const: 0xb3468
-  __TEXT.__cstring: 0x540e0
-  __TEXT.__gcc_except_tab: 0x17d8
-  __TEXT.__unwind_info: 0x3620
+  __TEXT.__cstring: 0x544bb
+  __TEXT.__gcc_except_tab: 0x1820
+  __TEXT.__unwind_info: 0x3660
   __TEXT.__eh_frame: 0x1178
   __TEXT.__objc_classname: 0x45a
   __TEXT.__objc_methname: 0x27ee
   __TEXT.__objc_methtype: 0x41fe
   __TEXT.__objc_stubs: 0x19e0
-  __DATA_CONST.__got: 0x290
+  __DATA_CONST.__got: 0x2b8
   __DATA_CONST.__const: 0x15e80
   __DATA_CONST.__objc_classlist: 0x108
   __DATA_CONST.__objc_catlist: 0x8

   __DATA_CONST.__objc_selrefs: 0x890
   __DATA_CONST.__objc_superrefs: 0xa8
   __DATA_CONST.__objc_arraydata: 0x40
-  __AUTH_CONST.__auth_got: 0x998
-  __AUTH_CONST.__const: 0x1faa0
-  __AUTH_CONST.__cfstring: 0x360
+  __AUTH_CONST.__auth_got: 0xa00
+  __AUTH_CONST.__const: 0x1fc40
+  __AUTH_CONST.__cfstring: 0x380
   __AUTH_CONST.__objc_const: 0x35d8
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_dictobj: 0xa0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 18168
-  Symbols:   23134
-  CStrings:  9487
+  Functions: 18196
+  Symbols:   23186
+  CStrings:  9501
 
Symbols:
+ _CFArrayAppendValue
+ _CFArrayCreateMutable
+ _CFDataGetTypeID
+ _CFDictionaryGetTypeID
+ _CFGetTypeID
+ _CMBaseObjectGetDerivedStorage
+ _CMDerivedObjectCreate
+ _CMFormatDescriptionGetExtensions
+ _VTDecoderSessionEmitDecodedFrame
+ _VTDecoderSessionGetPixelBufferPool
+ _VTDecoderSessionSetPixelBufferAttributes
+ _VTRegisterVideoDecoder
+ _VTVideoDecoderGetClassID
+ __ZN6webrtc16RefCountedObjectINS_31WebKitEncodedImageBufferWrapperEED0Ev
+ __ZN6webrtc16RefCountedObjectINS_31WebKitEncodedImageBufferWrapperEED1Ev
+ __ZN6webrtc21WebKitDecoderReceiver31initializeFromFormatDescriptionEPK25opaqueCMFormatDescription
+ __ZN6webrtc21WebKitDecoderReceiver7DecodedERNS_10VideoFrameE
+ __ZN6webrtc21WebKitDecoderReceiver7DecodedERNS_10VideoFrameENSt3__18optionalIiEENS4_IhEE
+ __ZN6webrtc21WebKitDecoderReceiver7DecodedERNS_10VideoFrameEx
+ __ZN6webrtc21WebKitDecoderReceiverD0Ev
+ __ZN6webrtc21WebKitDecoderReceiverD1Ev
+ __ZN6webrtc24registerWebKitVP9DecoderEv
+ __ZN6webrtc31WebKitEncodedImageBufferWrapper4dataEv
+ __ZN6webrtcL18finalizeVP9DecoderEP18OpaqueCMBaseObject
+ __ZN6webrtcL20invalidateVP9DecoderEP18OpaqueCMBaseObject
+ __ZN6webrtcL21decodeVP9DecoderFrameEP20OpaqueVTVideoDecoderP25OpaqueVTVideoDecoderFrameP20opaqueCMSampleBufferjPj
+ __ZN6webrtcL22WebKitVP9DecoderVTableE
+ __ZN6webrtcL22createWebKitVP9DecoderEjPK13__CFAllocatorPP20OpaqueVTVideoDecoder
+ __ZN6webrtcL22startVP9DecoderSessionEP20OpaqueVTVideoDecoderP27OpaqueVTVideoDecoderSessionPK25opaqueCMFormatDescription
+ __ZN6webrtcL26WebKitVP9Decoder_BaseClassE
+ __ZN6webrtcL30copyVP9DecoderDebugDescriptionEP18OpaqueCMBaseObject
+ __ZN6webrtcL34WebKitVP9Decoder_VideoDecoderClassE
+ __ZNK6webrtc16RefCountedObjectINS_31WebKitEncodedImageBufferWrapperEE6AddRefEv
+ __ZNK6webrtc16RefCountedObjectINS_31WebKitEncodedImageBufferWrapperEE7ReleaseEv
+ __ZNK6webrtc16RefCountedObjectINS_31WebKitEncodedImageBufferWrapperEE9HasOneRefEv
+ __ZNK6webrtc31WebKitEncodedImageBufferWrapper4dataEv
+ __ZNK6webrtc31WebKitEncodedImageBufferWrapper4sizeEv
+ __ZNKSt3__110__function6__funcIZN6webrtc21WebKitDecoderReceiver7DecodedERNS2_10VideoFrameEE3$_0NS_9allocatorIS6_EEFP10__CVBuffermmNS2_10BufferTypeEEE7__cloneEPNS0_6__baseISC_EE
+ __ZNKSt3__110__function6__funcIZN6webrtc21WebKitDecoderReceiver7DecodedERNS2_10VideoFrameEE3$_0NS_9allocatorIS6_EEFP10__CVBuffermmNS2_10BufferTypeEEE7__cloneEv
+ __ZNSt3__110__function6__funcIZN6webrtc21WebKitDecoderReceiver7DecodedERNS2_10VideoFrameEE3$_0NS_9allocatorIS6_EEFP10__CVBuffermmNS2_10BufferTypeEEE18destroy_deallocateEv
+ __ZNSt3__110__function6__funcIZN6webrtc21WebKitDecoderReceiver7DecodedERNS2_10VideoFrameEE3$_0NS_9allocatorIS6_EEFP10__CVBuffermmNS2_10BufferTypeEEE7destroyEv
+ __ZNSt3__110__function6__funcIZN6webrtc21WebKitDecoderReceiver7DecodedERNS2_10VideoFrameEE3$_0NS_9allocatorIS6_EEFP10__CVBuffermmNS2_10BufferTypeEEED0Ev
+ __ZNSt3__110__function6__funcIZN6webrtc21WebKitDecoderReceiver7DecodedERNS2_10VideoFrameEE3$_0NS_9allocatorIS6_EEFP10__CVBuffermmNS2_10BufferTypeEEED1Ev
+ __ZNSt3__110__function6__funcIZN6webrtc21WebKitDecoderReceiver7DecodedERNS2_10VideoFrameEE3$_0NS_9allocatorIS6_EEFP10__CVBuffermmNS2_10BufferTypeEEEclEOmSE_OSB_
+ __ZTVN6webrtc16RefCountedObjectINS_31WebKitEncodedImageBufferWrapperEEE
+ __ZTVN6webrtc21WebKitDecoderReceiverE
+ __ZTVNSt3__110__function6__funcIZN6webrtc21WebKitDecoderReceiver7DecodedERNS2_10VideoFrameEE3$_0NS_9allocatorIS6_EEFP10__CVBuffermmNS2_10BufferTypeEEEE
+ _kCFTypeArrayCallBacks
+ _kCVPixelBufferExtendedPixelsBottomKey
+ _kCVPixelBufferExtendedPixelsLeftKey
+ _kCVPixelBufferExtendedPixelsRightKey
+ _kCVPixelBufferExtendedPixelsTopKey
CStrings:
+ ", vtError "
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/libwebrtc/Source/ThirdParty/libwebrtc/Source/webrtc/webkit_sdk/WebKit/WebKitDecoderReceiver.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/libwebrtc/Source/ThirdParty/libwebrtc/Source/webrtc/webkit_sdk/WebKit/WebKitVP9Decoder.cpp"
+ "Failed to allocate cpi->cyclic_refresh->map"
+ "VP9 decoder creation failed, CMDerivedObjectCreate failed with error "
+ "VP9 decoder creation failed, no decoder output"
+ "VP9 decoder: CMBlockBufferGetDataPointer failed with error "
+ "VP9 decoder: decoder failed with error "
+ "VP9 decoder: failed to create contiguous block buffer with error "
+ "VP9 decoder: failed to get data buffer"
+ "VP9 decoder: failed to get decoder from instance while decoding"
+ "VP9 decoder: failed to get decoder from instance while starting"
+ "VP9 decoder: invalidation failed as instance has no decoder"
+ "WebKit VP9 decoder"
```
