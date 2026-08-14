## AirPlaySender

> `/System/Library/PrivateFrameworks/AirPlaySender.framework/Versions/A/AirPlaySender`

```diff

-860.3.1.0.0
-  __TEXT.__text: 0x1791f0
-  __TEXT.__auth_stubs: 0x46a0
+860.5.2.0.0
+  __TEXT.__text: 0x178650
+  __TEXT.__auth_stubs: 0x4690
   __TEXT.__objc_methlist: 0x52c
   __TEXT.__const: 0xcf30
   __TEXT.__gcc_except_tab: 0x560
-  __TEXT.__cstring: 0x5978e
+  __TEXT.__cstring: 0x59241
   __TEXT.__dlopen_cstrs: 0x164
   __TEXT.__oslogstring: 0x33e
-  __TEXT.__unwind_info: 0x35a0
+  __TEXT.__unwind_info: 0x3580
   __TEXT.__objc_classname: 0xb4
   __TEXT.__objc_methname: 0x14a4
   __TEXT.__objc_methtype: 0x8f1

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x660
   __DATA_CONST.__objc_superrefs: 0x10
-  __AUTH_CONST.__auth_got: 0x2360
+  __AUTH_CONST.__auth_got: 0x2358
   __AUTH_CONST.__const: 0x7130
   __AUTH_CONST.__cfstring: 0xcdc0
   __AUTH_CONST.__objc_const: 0x6e0

   - /System/Library/PrivateFrameworks/WiFiPeerToPeer.framework/Versions/A/WiFiPeerToPeer
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 6521
-  Symbols:   6922
-  CStrings:  7609
+  Functions: 6512
+  Symbols:   6920
+  CStrings:  7556
 
Symbols:
+ _FigSignalErrorAt
+ _streamAggregateAudio_subStreamNotificationForwarder
- _FigSignalErrorAt3
- _fig_log_get_emitter
- _streamAggregateAudio_GlitchReportNotificationListener
- _streamAggregateAudio_PerformanceReportNotificationListener
CStrings:
+ "860.5.2"
+ "[%{ptr}] received AudioDataMessage '%C'\n"
- "%s%s%s signalled err=%d (%s) (%s) at %s:%d"
- "(Fig)"
- "-108"
- "-876"
- "-877"
- "-878"
- "-879"
- "-880"
- "860.3.1"
- "APAudioSourceSharedMemory.c"
- "APEndpoint.c"
- "APEndpointPlaybackSessionRemoteControl.m"
- "APEndpointStreamAggregateAudio.c"
- "APSampleBufferConsumerForEndpointStreamAudioEngine.c"
- "APVirtualDisplayTestSink.c"
- "Action not supported"
- "Allocation error"
- "Audio source has been invalidated"
- "Cannot register path"
- "Failed to create bufferMemObject"
- "Failed to create deep copy"
- "Failed to create stateMemObject"
- "Failed to de-serialize"
- "Failed to serialize"
- "Invalid Trigger Token"
- "Item is NULL"
- "NULL audioEngine"
- "NULL bufferMemObject in message"
- "NULL stateMemObject in message"
- "NULL trigger"
- "NULL triggerTokenOut"
- "No data in response"
- "No incoming message"
- "No matched request found"
- "No trigger installed"
- "Object invalidated"
- "Only support one trigger installed at a time"
- "alloc failed"
- "bufferMemory region maps to NULL"
- "bufferMemorySize is zero"
- "can't find valid video track"
- "err"
- "kCMBaseObjectError_Invalidated"
- "kCMBaseObjectError_ParamErr"
- "kFigBaseObjectError_AllocationFailed"
- "kFigBaseObjectError_ValueNotAvailable"
- "kFigEndpointError_AllocationFailed"
- "kFigEndpointPlaybackSessionError_AllocationFailed"
- "kFigEndpointPlaybackSessionError_InvalidParameter"
- "messageID is missing in response event"
- "sbceas_InstallLowWaterTrigger_block_invoke"
- "sbceas_RemoveLowWaterTrigger_block_invoke"
- "stateMemObject maps to NULL"
- "stateMemoryLength < sizeof(RingState)"
- "type is missing in response event"
```
