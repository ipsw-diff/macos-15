## AppleVideoDecoder

> `/System/Library/Video/Plug-Ins/AppleVideoDecoder.bundle/Contents/MacOS/AppleVideoDecoder`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`

```diff

-863.1.0.0.0
-  __TEXT.__text: 0x153904
+865.0.0.0.0
+  __TEXT.__text: 0x141184
   __TEXT.__auth_stubs: 0xea0
-  __TEXT.__const: 0xc1df
-  __TEXT.__oslogstring: 0xfc82
-  __TEXT.__cstring: 0x5d34
-  __TEXT.__gcc_except_tab: 0x8dc
-  __TEXT.__unwind_info: 0x1968
+  __TEXT.__const: 0xc062
+  __TEXT.__oslogstring: 0xfcc8
+  __TEXT.__cstring: 0x5c9d
+  __TEXT.__gcc_except_tab: 0x850
+  __TEXT.__unwind_info: 0x1828
   __DATA_CONST.__auth_got: 0x758
-  __DATA_CONST.__got: 0x330
+  __DATA_CONST.__got: 0x338
   __DATA_CONST.__auth_ptr: 0x10
-  __DATA_CONST.__const: 0x4818
+  __DATA_CONST.__const: 0x42b8
   __DATA_CONST.__cfstring: 0x720
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA.__data: 0x88

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2253
-  Symbols:   347
-  CStrings:  1904
+  Functions: 2127
+  Symbols:   348
+  CStrings:  1905
 
Symbols:
+ _kIOSurfaceAcceleratorDefaultChromaDownsample
CStrings:
+ "21:23:55"
+ "21:23:56"
+ "21:23:57"
+ "AppleAVD: %s(): Thyme AVD is not supported in this AppleAVD driver!!!"
+ "Jun 11 2025"
+ "createThymeAvcDecoder"
+ "createThymeAvxDecoder"
+ "createThymeHevcDecoder"
+ "createThymeLghDecoder"
- "20:06:18"
- "20:06:19"
- "20:06:20"
- "Apr 22 2025"
- "int CAHDecThymeAvc::populateSliceRegisters(AvcSliceRegisters *, int)"
- "int32_t CAHDecThymeAvx::getUpscaleConvolveStep(int, int)"
- "int32_t CAHDecThymeAvx::getUpscaleConvolveX0(int, int, int32_t)"
- "virtual int CAHDecThymeAvx::populatePictureRegisters()"
```
