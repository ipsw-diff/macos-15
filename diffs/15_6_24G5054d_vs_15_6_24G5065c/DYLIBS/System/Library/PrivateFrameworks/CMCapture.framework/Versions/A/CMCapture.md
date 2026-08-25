## CMCapture

> `/System/Library/PrivateFrameworks/CMCapture.framework/Versions/A/CMCapture`

```diff

-587.140.7.0.0
-  __TEXT.__text: 0x4c63c0
+587.140.8.0.0
+  __TEXT.__text: 0x4c6410
   __TEXT.__auth_stubs: 0x3d80
   __TEXT.__objc_methlist: 0x212ac
   __TEXT.__const: 0x142160
-  __TEXT.__cstring: 0x7a4c7
-  __TEXT.__oslogstring: 0x9ff89
+  __TEXT.__cstring: 0x7a4f0
+  __TEXT.__oslogstring: 0x9ffb3
   __TEXT.__gcc_except_tab: 0x1bd8
   __TEXT.__dlopen_cstrs: 0xfa
   __TEXT.__ustring: 0x10

   __DATA_CONST.__objc_arraydata: 0x1338
   __AUTH_CONST.__auth_got: 0x1ed0
   __AUTH_CONST.__const: 0x4d30
-  __AUTH_CONST.__cfstring: 0x34da0
+  __AUTH_CONST.__cfstring: 0x34de0
   __AUTH_CONST.__objc_const: 0x5df38
   __AUTH_CONST.__objc_intobj: 0x3060
   __AUTH_CONST.__objc_arrayobj: 0xf90

   - /usr/lib/libobjc.A.dylib
   Functions: 20355
   Symbols:   39500
-  CStrings:  35708
+  CStrings:  35710
 
Functions:
~ +[BWCoreAnalyticsReporter clientApplicationIDType:] : 2264 -> 2304
~ _captureSession_makeCommittedConfigurationLive : 996 -> 1020
~ ___captureSession_updateRunningCondition_block_invoke : 2300 -> 2304
~ _captureSession_commitInflightConfiguration : 3056 -> 3064
~ ___captureSession_SetConfiguration_block_invoke : 1580 -> 1584
CStrings:
+ "<<<< FigCaptureSession >>>> %s: Committed configuration same as live one. Will not update session status to Running"
+ "Cisco-Systems.Spark"
+ "com.microsoft.teams2"
+ "description=CameraCapture-587.140.8"
- "<<<< FigCaptureSession >>>> %s: Committed configuration same as live one."
- "description=CameraCapture-587.140.7"
```
