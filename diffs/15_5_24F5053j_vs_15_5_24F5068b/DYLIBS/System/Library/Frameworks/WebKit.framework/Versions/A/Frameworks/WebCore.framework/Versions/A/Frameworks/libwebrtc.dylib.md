## libwebrtc.dylib

> `/System/Library/Frameworks/WebKit.framework/Versions/A/Frameworks/WebCore.framework/Versions/A/Frameworks/libwebrtc.dylib`

```diff

-621.2.4.11.2
-  __TEXT.__text: 0xa87960
+621.2.5.11.5
+  __TEXT.__text: 0xa8820c
   __TEXT.__auth_stubs: 0x13e0
   __TEXT.__objc_methlist: 0x14e4
   __TEXT.__const: 0xb3468
-  __TEXT.__cstring: 0x544bb
+  __TEXT.__cstring: 0x544e7
   __TEXT.__gcc_except_tab: 0x1820
   __TEXT.__unwind_info: 0x3660
   __TEXT.__eh_frame: 0x1178

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 18196
-  Symbols:   23186
-  CStrings:  9501
+  Functions: 18198
+  Symbols:   23188
+  CStrings:  9503
 
Symbols:
+ _I210ToP210
+ _I422ToNV21
Functions:
~ __ZN6webrtc21WebKitDecoderReceiver31initializeFromFormatDescriptionEPK25opaqueCMFormatDescription : 204 -> 196
~ __ZNSt3__110__function6__funcIZN6webrtc21WebKitDecoderReceiver7DecodedERNS2_10VideoFrameEE3$_0NS_9allocatorIS6_EEFP10__CVBuffermmNS2_10BufferTypeEEEclEOmSE_OSB_ : 648 -> 696
~ __ZN6webrtc32createPixelBufferFromFrameBufferERNS_16VideoFrameBufferERKNSt3__18functionIFP10__CVBuffermmNS_10BufferTypeEEEE : 2176 -> 3784
+ _I210ToP210
+ _I422ToNV21
CStrings:
+ "type() == Type::kI210"
+ "type() == Type::kI422"
```
