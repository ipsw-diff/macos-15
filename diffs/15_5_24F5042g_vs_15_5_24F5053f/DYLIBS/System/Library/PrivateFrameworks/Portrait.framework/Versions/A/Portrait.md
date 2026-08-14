## Portrait

> `/System/Library/PrivateFrameworks/Portrait.framework/Versions/A/Portrait`

```diff

-436.120.1.0.1
-  __TEXT.__text: 0x9d260
-  __TEXT.__auth_stubs: 0x1080
+436.120.3.0.0
+  __TEXT.__text: 0x9d2f4
+  __TEXT.__auth_stubs: 0x1070
   __TEXT.__delay_stubs: 0x2ec
   __TEXT.__delay_helper: 0x110
   __TEXT.__objc_methlist: 0x8934
   __TEXT.__const: 0x21254
-  __TEXT.__cstring: 0x7756
-  __TEXT.__oslogstring: 0x3bb5
+  __TEXT.__cstring: 0x7780
+  __TEXT.__oslogstring: 0x3bd5
   __TEXT.__gcc_except_tab: 0x780
   __TEXT.__ustring: 0x30
-  __TEXT.__unwind_info: 0x1f78
+  __TEXT.__unwind_info: 0x1f68
   __TEXT.__objc_classname: 0x11d6
-  __TEXT.__objc_methname: 0x18412
+  __TEXT.__objc_methname: 0x1842c
   __TEXT.__objc_methtype: 0x538b
   __TEXT.__objc_stubs: 0xe240
-  __DATA_CONST.__got: 0x910
+  __DATA_CONST.__got: 0x918
   __DATA_CONST.__const: 0x308
   __DATA_CONST.__objc_classlist: 0x508
   __DATA_CONST.__objc_catlist: 0x18

   __DATA_CONST.__objc_classrefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x468
   __DATA_CONST.__objc_arraydata: 0x660
-  __AUTH_CONST.__auth_got: 0x8e0
-  __AUTH_CONST.__const: 0x870
+  __AUTH_CONST.__auth_got: 0x8d8
+  __AUTH_CONST.__const: 0x850
   __AUTH_CONST.__cfstring: 0x4d60
-  __AUTH_CONST.__objc_const: 0x1b5a0
+  __AUTH_CONST.__objc_const: 0x1b5c0
   __AUTH_CONST.__objc_doubleobj: 0x30
   __AUTH_CONST.__objc_intobj: 0x900
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_arrayobj: 0xf0
   __AUTH.__objc_data: 0x3250
   __AUTH.__data: 0xbd0
-  __DATA.__objc_ivar: 0x15d4
+  __DATA.__objc_ivar: 0x15d8
   __DATA.__data: 0x918
-  __DATA.__bss: 0x1d0
+  __DATA.__bss: 0x1c0
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3801
-  Symbols:   8355
-  CStrings:  6124
+  Functions: 3800
+  Symbols:   8353
+  CStrings:  6126
 
Symbols:
+ OBJC_IVAR_$_PTMSRResize._supportsSymmetricScaling
+ _kIOSurfaceAcceleratorSymmetricScaling
- _MGGetSInt64Answer
- ___78-[PTMSRResize _downsample:toDest:useCustomFilter:centerAlignment:synchronous:]_block_invoke
- _downsample:toDest:useCustomFilter:centerAlignment:synchronous:.customFilterSupported
- _downsample:toDest:useCustomFilter:centerAlignment:synchronous:.onceToken
Functions:
~ -[PTMSRResize queryCapabilities] : 308 -> 392
~ -[PTMSRResize setCustomFilter:alignment:sourceWidth:sourceHeight:destinationWidth:destinationHeight:luma_param:chroma_param:] : 572 -> 676
~ _filter_coefficients : 1276 -> 1292
~ -[PTMSRResize _rotate:toDest:synchronous:] : 272 -> 300
~ -[PTMSRResize rotate:crop:rotationDegree:toDest:synchronous:] : 572 -> 600
~ -[PTMSRResize _downsample:toDest:useCustomFilter:centerAlignment:synchronous:] : 408 -> 412
- ___78-[PTMSRResize _downsample:toDest:useCustomFilter:centerAlignment:synchronous:]_block_invoke
+ -[PTMSRResize queryCapabilities].cold.1
- -[PTMSRResize _downsample:toDest:useCustomFilter:centerAlignment:synchronous:].cold.1
CStrings:
+ "IOSurfaceAcceleratorCapabilitiesSymmetricScaling"
+ "MSR supportsSymmetricScaling %i"
+ "_supportsSymmetricScaling"
- "ChipID"
```
