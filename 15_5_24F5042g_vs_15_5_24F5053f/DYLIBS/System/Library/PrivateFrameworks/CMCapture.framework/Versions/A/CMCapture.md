## CMCapture

> `/System/Library/PrivateFrameworks/CMCapture.framework/Versions/A/CMCapture`

```diff

-587.120.2.0.1
-  __TEXT.__text: 0x4c41d0
+587.122.2.0.0
+  __TEXT.__text: 0x4c548c
   __TEXT.__auth_stubs: 0x3d80
-  __TEXT.__objc_methlist: 0x211fc
+  __TEXT.__objc_methlist: 0x21214
   __TEXT.__const: 0x142160
-  __TEXT.__cstring: 0x7a211
-  __TEXT.__oslogstring: 0x9f6c7
-  __TEXT.__gcc_except_tab: 0x1bc4
+  __TEXT.__cstring: 0x7a27f
+  __TEXT.__oslogstring: 0x9fa99
+  __TEXT.__gcc_except_tab: 0x1bd8
   __TEXT.__dlopen_cstrs: 0xfa
   __TEXT.__ustring: 0x10
   __TEXT.__unwind_info: 0x8860
   __TEXT.__objc_classname: 0x46e6
-  __TEXT.__objc_methname: 0x7440a
+  __TEXT.__objc_methname: 0x744b2
   __TEXT.__objc_methtype: 0xd34d
-  __TEXT.__objc_stubs: 0x2e7a0
+  __TEXT.__objc_stubs: 0x2e820
   __DATA_CONST.__got: 0x55f0
   __DATA_CONST.__const: 0x50d8
   __DATA_CONST.__objc_classlist: 0x1038
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x258
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xe5b8
+  __DATA_CONST.__objc_selrefs: 0xe5c8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0xf58
   __DATA_CONST.__objc_arraydata: 0x1338
   __AUTH_CONST.__auth_got: 0x1ed0
   __AUTH_CONST.__const: 0x4d30
-  __AUTH_CONST.__cfstring: 0x34d40
-  __AUTH_CONST.__objc_const: 0x5dd58
+  __AUTH_CONST.__cfstring: 0x34d60
+  __AUTH_CONST.__objc_const: 0x5de08
   __AUTH_CONST.__objc_intobj: 0x3060
   __AUTH_CONST.__objc_arrayobj: 0xf90
   __AUTH_CONST.__objc_doubleobj: 0x1c0

   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH.__objc_data: 0x3ca0
   __AUTH.__data: 0xe0
-  __DATA.__objc_ivar: 0x6ff4
+  __DATA.__objc_ivar: 0x7008
   __DATA.__data: 0x2c04
   __DATA.__common: 0x1510
   __DATA.__bss: 0x1943

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 20323
-  Symbols:   39451
-  CStrings:  35665
+  Functions: 20342
+  Symbols:   39475
+  CStrings:  35687
 
Symbols:
+ -[BWFigVideoCaptureDevice _updateMLVNRActiveTime:]
+ -[BWStreamingSessionAnalyticsPayload mlvnrActiveTime]
+ -[BWStreamingSessionAnalyticsPayload setMlvnrActiveTime:]
+ GCC_except_table130
+ GCC_except_table165
+ GCC_except_table215
+ GCC_except_table262
+ GCC_except_table300
+ GCC_except_table350
+ GCC_except_table374
+ GCC_except_table376
+ GCC_except_table390
+ GCC_except_table882
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._deskCamMLVNRStartTime
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._deskCamMLVNRTotalTime
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._mainCamMLVNRStartTime
+ OBJC_IVAR_$_BWFigVideoCaptureDevice._mainCamMLVNRTotalTime
+ OBJC_IVAR_$_BWStreamingSessionAnalyticsPayload._mlvnrActiveTime
+ _OUTLINED_FUNCTION_482
+ _OUTLINED_FUNCTION_483
+ _OUTLINED_FUNCTION_484
+ _OUTLINED_FUNCTION_485
+ _OUTLINED_FUNCTION_486
+ _OUTLINED_FUNCTION_487
+ _OUTLINED_FUNCTION_488
+ _OUTLINED_FUNCTION_489
+ _OUTLINED_FUNCTION_490
+ _OUTLINED_FUNCTION_491
+ _OUTLINED_FUNCTION_492
+ _OUTLINED_FUNCTION_493
+ _objc_msgSend$isManualCinematicFramingActive
+ _objc_msgSend$mlvnrActiveTime
+ _objc_msgSend$setMlvnrActiveTime:
+ _objc_msgSend$setUltraWideActive:
- GCC_except_table129
- GCC_except_table164
- GCC_except_table214
- GCC_except_table261
- GCC_except_table299
- GCC_except_table349
- GCC_except_table373
- GCC_except_table375
- GCC_except_table389
- GCC_except_table881
CStrings:
+ "-[BWFigVideoCaptureDevice _resetAnalyticsData]"
+ "-[BWFigVideoCaptureDevice _updateMLVNRActiveTime:]"
+ "<<<< BWFigCaptureDevice >>>> %s: %{public}@: not setting %{public}@ to %{public}i"
+ "<<<< BWFigCaptureDevice >>>> %s: %{public}@: set %{public}@ to %{public}i"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: Adding DeskCam MLVNR last duration of %f secs, total time: %f"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: Adding MLVNR last duration of %f secs, total time: %f"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: DeskCam MLVNR turned off at %lld / %d after %f secs. Total time: %f secs"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: DeskCam MLVNR turned on at %lld / %d"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: MLVNR total time set to zero"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: MLVNR turned off at %lld / %d after %f secs. Total time: %f secs"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: MLVNR turned on at %lld / %d"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: Reporting MLVNR Active Time set to %u"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: Reporting MLVNR Active Time set to %u (for DeskCam)"
+ "<<<< BWFigVideoCaptureDevice >>>> %s: deskCamActive=%d, ultraWideActive=%d"
+ "<<<< FigCaptureSession >>>> %s: %{public}@ Stop monitoring for %@"
+ "TI,N,V_mlvnrActiveTime"
+ "_deskCamMLVNRStartTime"
+ "_deskCamMLVNRTotalTime"
+ "_mainCamMLVNRStartTime"
+ "_mainCamMLVNRTotalTime"
+ "_mlvnrActiveTime"
+ "description=CameraCapture-587.122.2"
+ "mlvnrActiveTime"
+ "setMlvnrActiveTime:"
- "<<<< FigCaptureSession >>>> %s: The \"Recording video while multitasking\" dialog only applies to iOS"
- "description=CameraCapture-587.120.2.0.1"
```
