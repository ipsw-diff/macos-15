## AVFCapture

> `/System/Library/PrivateFrameworks/AVFCapture.framework/Versions/A/AVFCapture`

```diff

-587.120.2.0.1
-  __TEXT.__text: 0x1df378
+587.122.2.0.0
+  __TEXT.__text: 0x1df3b4
   __TEXT.__auth_stubs: 0x2390
   __TEXT.__objc_methlist: 0x13ef4
-  __TEXT.__cstring: 0x325c1
+  __TEXT.__cstring: 0x325bd
   __TEXT.__const: 0x1100
-  __TEXT.__oslogstring: 0x2898a
+  __TEXT.__oslogstring: 0x289eb
   __TEXT.__gcc_except_tab: 0x37e8
   __TEXT.__dlopen_cstrs: 0x1d1
   __TEXT.__ustring: 0x112
-  __TEXT.__unwind_info: 0x5e60
+  __TEXT.__unwind_info: 0x5e68
   __TEXT.__objc_classname: 0x2649
   __TEXT.__objc_methname: 0x2c42d
   __TEXT.__objc_methtype: 0x4b52

   - /usr/lib/libobjc.A.dylib
   Functions: 8859
   Symbols:   18253
-  CStrings:  12599
+  CStrings:  12600
 
Functions:
~ +[AVCaptureDevice requestGesturesDefaultDisabledNotification] : 416 -> 480
~ -[AVCaptureMetadataOutput _detectedObjectsCollectionForSampleBuffer:input:facesArrayOut:need180DegreeMetadataTransform:] : 3684 -> 3676
~ -[AVCaptureMetadataOutput _legacyFaceCollectionForSampleBuffer:input:] : 624 -> 628
CStrings:
+ "<<<< AVCaptureDevice >>>> %s: gestures-disabled requesting notification (catalyst %d didShow %d)"
+ "description=CameraCapture_AVF-587.122.2"
- "description=CameraCapture_AVF-587.120.2.0.1"
```
