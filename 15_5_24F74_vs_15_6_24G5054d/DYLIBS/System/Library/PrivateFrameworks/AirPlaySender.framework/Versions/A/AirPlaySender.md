## AirPlaySender

> `/System/Library/PrivateFrameworks/AirPlaySender.framework/Versions/A/AirPlaySender`

```diff

-860.7.1.0.0
-  __TEXT.__text: 0x178650
+870.8.1.0.0
+  __TEXT.__text: 0x178830
   __TEXT.__auth_stubs: 0x4690
   __TEXT.__objc_methlist: 0x52c
   __TEXT.__const: 0xcf30
   __TEXT.__gcc_except_tab: 0x560
-  __TEXT.__cstring: 0x59241
+  __TEXT.__cstring: 0x593c6
   __TEXT.__dlopen_cstrs: 0x164
   __TEXT.__oslogstring: 0x33e
-  __TEXT.__unwind_info: 0x3580
+  __TEXT.__unwind_info: 0x3578
   __TEXT.__objc_classname: 0xb4
   __TEXT.__objc_methname: 0x14a4
   __TEXT.__objc_methtype: 0x8f1
   __TEXT.__objc_stubs: 0x1280
-  __DATA_CONST.__got: 0x1858
+  __DATA_CONST.__got: 0x1860
   __DATA_CONST.__const: 0x3470
   __DATA_CONST.__objc_classlist: 0x10
   __DATA_CONST.__objc_catlist: 0x10

   - /System/Library/PrivateFrameworks/WiFiPeerToPeer.framework/Versions/A/WiFiPeerToPeer
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 6512
-  Symbols:   6920
-  CStrings:  7556
+  Functions: 6504
+  Symbols:   6918
+  CStrings:  7559
 
Symbols:
+ _kFigEndpointStreamAudioEngineSampleBufferAttachmentKey_FlushRangeEnd
- _OUTLINED_FUNCTION_178
- _OUTLINED_FUNCTION_179
- _OUTLINED_FUNCTION_180
CStrings:
+ "870.8.1"
+ "BAE [%{ptr}] %s[0x%04X] ### FlushWithinSampleRange: Could not process all invalid samples at this time. Discard Count: %u lastRemoteMediaTimeDiscarded %1.3f (sample time %1.3f), flushSampleRangeStart %1.3f\n"
+ "BAE [%{ptr}] %s[0x%04X] ### FlushWithinSampleRange: Could not process all valid samples at this time. Prepared: %u nextRemoteMediaTimestamp %1.3f (sample time %1.3f), flushSampleRangeStart %1.3f\n"
+ "BAE [%{ptr}] %s[0x%04X] Discarded invalid sample buffer [%p] OPTS: %1.3f (media time: %1.3f), flush sample range start: %1.3f\n"
+ "BAE [%{ptr}] %s[0x%04X] End of flush range processing, nextRemoteMediaTimestamp: %1.6f (%lld/%d)\n"
+ "BAE [%{ptr}] %s[0x%04X] FlushWithinSampleRange: Discarding all invalid samples: nextRemoteMediaTimestamp %1.3f end %1.3f\n"
+ "BAE [%{ptr}] %s[0x%04X] FlushWithinSampleRange: Process valid samples complete: Prepared: %u nextRemoteMediaTimestamp %1.3f (sample time %1.3f)\n"
+ "BAE [%{ptr}] %s[0x%04X] FlushWithinSampleRange: Processed invalid samples complete: Discard Count: %u lastRemoteMediaTimeDiscarded %1.3f (sample time %1.3f)\n"
+ "BAE [%{ptr}] %s[0x%04X] FlushWithinSampleRange: Processing all valid samples: nextRemoteMediaTimestamp %1.3f\n"
+ "BAE [%{ptr}] %s[0x%04X] FlushWithinSampleRange: Trimm of unwanted samples from message ring complete: next valid message media time %1.3f (sample time %1.3f)\n"
+ "BAE [%{ptr}] %s[0x%04X] FlushWithinSampleRange: currentMediaTime = %1.3f nextRemoteMediaTimestamp = %1.3f\n"
+ "BAE [%{ptr}] %s[0x%04X] FlushWithinSampleRange: flushRangeRemoteMediaTime %1.3f:%1.3f\n"
+ "BAE [%{ptr}] %s[0x%04X] FlushWithinSampleRange: sampleRange %1.3f:%1.3f (sbufEndOutputPTS %1.3f)\n"
+ "BAE [%{ptr}] %s[0x%04X] Process valid sample buffer [%p] OPTS: %1.3f (media time: %1.3f), flush sample range start: %1.3f\n"
+ "BAE [%{ptr}] %s[0x%04X] SetRateAndAnchorTime - set firstSampleTimeAfterReset to %1.3f\n"
+ "Boolean bufferedAudioEngine_shouldDiscardSampleBuffer(FigEndpointStreamAudioEngineRef, CMSampleBufferRef)"
+ "OSStatus bufferedAudioEngine_flushWithinSampleRangeInternal(void *)"
- "860.7.1"
- "BAE [%{ptr}] %s[0x%04X] ### FlushWithinSampleRange: Could not process all invalid samples of the next song. Discard Count: %u lastRemoteMediaTimeDiscarded (%ld/%d)\n"
- "BAE [%{ptr}] %s[0x%04X] ### FlushWithinSampleRange: Could not process all valid samples of the current song. Prepared: %u NextRTP (%ld/%d)\n"
- "BAE [%{ptr}] %s[0x%04X] ### FlushWithinSampleRange: Failed with err = %d\n"
- "BAE [%{ptr}] %s[0x%04X] Discarding sbuf with opts %1.3f for current flush time range: start = %1.3f, end = %1.3f \n"
- "BAE [%{ptr}] %s[0x%04X] FlushWithinSampleRange: Discarding all invalid samples: Next (%ld/%d) Start (%ld/%d)\n"
- "BAE [%{ptr}] %s[0x%04X] FlushWithinSampleRange: Process valid samples complete: Prepared: %u NextRemoteMediaTimestamp (%ld/%d)\n"
- "BAE [%{ptr}] %s[0x%04X] FlushWithinSampleRange: Processed invalid samples complete: Discard Count: %u lastRemoteMediaTimeDiscarded (%ld/%d)\n"
- "BAE [%{ptr}] %s[0x%04X] FlushWithinSampleRange: Processing all valid samples: Next (%ld/%d) Start (%ld/%d)\n"
- "BAE [%{ptr}] %s[0x%04X] FlushWithinSampleRange: currentRTP = (%u / %f) CURR nextRTP_TS = (%u / %f) NEW nextRTP_TS = (%u / %f)\n"
- "BAE [%{ptr}] %s[0x%04X] FlushWithinSampleRange: flushRangeRemoteMediaTime.start.value = %ld flushRangeRemoteMediaTime.start.ts = %d flushRangeRemoteMediaTime.duration.value = %ld flushRangeRemoteMediaTime.duration.ts = %d\n"
- "BAE [%{ptr}] %s[0x%04X] FlushWithinSampleRange: sampleRange.start.value = %ld sampleRange.start.ts = %d duration.value = %ld duration.ts = %d first.value = %lu first.ts = %d\n"
- "bufferedAudioEngine_isTimeWithinBounds"
- "void bufferedAudioEngine_flushWithinSampleRangeInternal(void *)"
```
