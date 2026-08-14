## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/Versions/A/AVConference`

```diff

-2115.2.1.0.0
-  __TEXT.__text: 0x6c01c8
+2115.4.1.0.0
+  __TEXT.__text: 0x6c04d8
   __TEXT.__auth_stubs: 0x4f00
-  __TEXT.__objc_methlist: 0x307d0
+  __TEXT.__objc_methlist: 0x307b8
   __TEXT.__const: 0x138e0
-  __TEXT.__cstring: 0x7d688
-  __TEXT.__oslogstring: 0xf35d7
+  __TEXT.__cstring: 0x7d76f
+  __TEXT.__oslogstring: 0xf3644
   __TEXT.__gcc_except_tab: 0x2a90
   __TEXT.__ustring: 0x144
-  __TEXT.__unwind_info: 0xef80
+  __TEXT.__unwind_info: 0xef90
   __TEXT.__objc_classname: 0x47b9
-  __TEXT.__objc_methname: 0x7131f
-  __TEXT.__objc_methtype: 0x244bc
-  __TEXT.__objc_stubs: 0x46b80
+  __TEXT.__objc_methname: 0x713bf
+  __TEXT.__objc_methtype: 0x2449f
+  __TEXT.__objc_stubs: 0x46bc0
   __DATA_CONST.__got: 0x1510
   __DATA_CONST.__const: 0x3198
   __DATA_CONST.__objc_classlist: 0x1170
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x448
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x146a8
+  __DATA_CONST.__objc_selrefs: 0x146b0
   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__objc_superrefs: 0xf88
   __DATA_CONST.__objc_arraydata: 0x2558
   __AUTH_CONST.__auth_got: 0x2798
   __AUTH_CONST.__const: 0x6d80
-  __AUTH_CONST.__cfstring: 0x221c0
-  __AUTH_CONST.__objc_const: 0x5b730
+  __AUTH_CONST.__cfstring: 0x221e0
+  __AUTH_CONST.__objc_const: 0x5b738
   __AUTH_CONST.__objc_intobj: 0x4098
   __AUTH_CONST.__objc_arrayobj: 0x1a28
   __AUTH_CONST.__objc_floatobj: 0x30

   __AUTH_CONST.__objc_dictobj: 0x2f8
   __AUTH.__objc_data: 0x9ab0
   __AUTH.__data: 0xb0
-  __DATA.__objc_ivar: 0x63e8
+  __DATA.__objc_ivar: 0x63f0
   __DATA.__data: 0x75e8
   __DATA.__bss: 0xaf8
   __DATA.__common: 0x9

   - /usr/lib/libtailspin.dylib
   - /usr/lib/libz.1.dylib
   Functions: 28436
-  Symbols:   45745
-  CStrings:  46290
+  Symbols:   45748
+  CStrings:  46298
 
Symbols:
+ +[VCCallSession isRelayDeviceRole:]
+ -[VCAVFoundationCapture isVideoCaptureOutputAspectRatioOverrideOptimizedSupported]
+ -[VCAudioStream shouldSetUpMediaRecorderWithParticipantInfoDictionary:]
+ -[VCCellularAudioTap stateQueue]
+ GCC_except_table320
+ GCC_except_table376
+ GCC_except_table42
+ GCC_except_table46
+ GCC_except_table466
+ OBJC_IVAR_$_VCAudioCaptions._isAudioConverterActive
+ OBJC_IVAR_$_VCCellularAudioTap._callbackCounter
+ _objc_msgSend$isRelayDeviceRole:
+ _objc_msgSend$isVideoCaptureOutputAspectRatioOverrideOptimizedSupported
+ _objc_msgSend$isVideoSettingsAspectRatioOverrideOptimized
+ _objc_msgSend$shouldSetUpMediaRecorderWithParticipantInfoDictionary:
- +[VCHardwareSettings captureFormatPrefer16by9ForSquare]
- -[VCAudioCaptionsCoordinator setStateLock:]
- -[VCAudioManager applyVoiceMixingMedia]
- -[VCHardwareSettingsEmbedded captureFormatPrefer16by9ForSquare]
- -[VCHardwareSettingsMac captureFormatPrefer16by9ForSquare]
- GCC_except_table24
- GCC_except_table319
- GCC_except_table375
- GCC_except_table43
- GCC_except_table465
- _objc_msgSend$applyVoiceMixingMedia
- _objc_msgSend$captureFormatPrefer16by9ForSquare
CStrings:
+ " [%s] %s:%d %@(%p) Reset audio converter for ASR version=%s"
+ " [%s] %s:%d AspectRatioOverrideEnabled, update output override to 1088x1088 on cameraFormat=%@"
+ " [%s] %s:%d Reset audio converter for ASR version=%s"
+ " [%s] %s:%d Setting Voice Mixing Enabled=%d"
+ " [%s] %s:%d isVideoSettingsAspectRatioOverrideSupported=%d, isVideoSettingsAspectRatioOverrideOptimized=%d"
+ " [%s] %s:%d output is NULL"
+ "-[VCAVFoundationCapture isVideoCaptureOutputAspectRatioOverrideOptimizedSupported]"
+ "-[VCAudioCaptions pushAudioSamples:]_block_invoke"
+ "-[VCAudioManager stateSessionStartedWithAudioUnitProperties:sessionProperties:client:newState:]"
+ "2115.4.1"
+ "ForceAVCapturePrefer16By9ForSquare"
+ "IsRelayDeviceRole"
+ "IsWalkieTalkieMode"
+ "Q24@0:8I16C20"
+ "T@\"NSObject<OS_dispatch_queue>\",R,N,V_stateQueue"
+ "V1"
+ "V2"
+ "^{os_unfair_lock_s=I}16@0:8"
+ "_callbackCounter"
+ "_isAudioConverterActive"
+ "isRelayDeviceRole:"
+ "isVideoCaptureOutputAspectRatioOverrideOptimizedSupported"
+ "isVideoSettingsAspectRatioOverrideOptimized"
+ "shouldSetUpMediaRecorderWithParticipantInfoDictionary:"
- " [%s] %s:%d %@(%p) isMixingVoiceWithMediaEnabled=%d"
- " [%s] %s:%d %@(%p) isMixingVoiceWithMediaEnabled=%d failed. result=%08X"
- " [%s] %s:%d isMixingVoiceWithMediaEnabled=%d"
- " [%s] %s:%d isMixingVoiceWithMediaEnabled=%d failed. result=%08X"
- " [%s] %s:%d pick 1088x1088 cameraFormat=%@"
- "-[VCAudioManager applyVoiceMixingMedia]"
- "2115.2.1"
- "AFECL"
- "AVCapturePrefer16By9ForSquare"
- "Q24@0:8i16C20"
- "T{os_unfair_lock_s=I},N,V_stateLock"
- "applyVoiceMixingMedia"
- "captureFormatPrefer16by9ForSquare"
- "setStateLock:"
- "v20@0:8{os_unfair_lock_s=I}16"
- "{os_unfair_lock_s=I}16@0:8"
```
