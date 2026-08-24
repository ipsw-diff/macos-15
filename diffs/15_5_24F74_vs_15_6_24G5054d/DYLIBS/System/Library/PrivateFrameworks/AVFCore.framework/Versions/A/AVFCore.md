## AVFCore

> `/System/Library/PrivateFrameworks/AVFCore.framework/Versions/A/AVFCore`

```diff

-2330.7.1.0.0
-  __TEXT.__text: 0x1b7de4
+2340.8.1.0.0
+  __TEXT.__text: 0x1b7f9c
   __TEXT.__auth_stubs: 0x36b0
-  __TEXT.__objc_methlist: 0x1d714
+  __TEXT.__objc_methlist: 0x1d734
   __TEXT.__const: 0x268
   __TEXT.__gcc_except_tab: 0x45e8
-  __TEXT.__cstring: 0x27785
-  __TEXT.__oslogstring: 0x7846
+  __TEXT.__cstring: 0x2778a
+  __TEXT.__oslogstring: 0x786e
   __TEXT.__ustring: 0x18
   __TEXT.__unwind_info: 0x9008
   __TEXT.__objc_classname: 0x6770
-  __TEXT.__objc_methname: 0x37224
+  __TEXT.__objc_methname: 0x37230
   __TEXT.__objc_methtype: 0xaf9f
-  __TEXT.__objc_stubs: 0x20da0
-  __DATA_CONST.__got: 0x4c60
+  __TEXT.__objc_stubs: 0x20dc0
+  __DATA_CONST.__got: 0x4c70
   __DATA_CONST.__const: 0x3530
   __DATA_CONST.__objc_classlist: 0x1310
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x248
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xae00
+  __DATA_CONST.__objc_selrefs: 0xae08
   __DATA_CONST.__objc_protorefs: 0x40
   __DATA_CONST.__objc_superrefs: 0xdd8
   __DATA_CONST.__objc_arraydata: 0x270
   __AUTH_CONST.__auth_got: 0x1b68
   __AUTH_CONST.__const: 0x3a60
   __AUTH_CONST.__cfstring: 0x19d80
-  __AUTH_CONST.__objc_const: 0x353a0
+  __AUTH_CONST.__objc_const: 0x353c8
   __AUTH_CONST.__objc_intobj: 0x228
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_arrayobj: 0x2d0

   - /System/Library/PrivateFrameworks/MediaExperience.framework/Versions/A/MediaExperience
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 11697
-  Symbols:   28093
+  Functions: 11698
+  Symbols:   28097
   CStrings:  13934
 
Symbols:
+ -[AVPixelBufferAttributesVideoOutputSettings decompressionProperties]
+ OBJC_IVAR_$_AVMetricEventStream._weakSelf
+ _kFigAssetReaderExtractionOption_DecompressionProperties
+ _kVTDecompressionPropertyKey_RequestRAWOutput
+ _objc_msgSend$decompressionProperties
- OBJC_IVAR_$_AVMetricEventStream._publishers
Functions:
~ -[AVPlayerItem(AVMetricEventStreamPublisherInternal) getEventTimelineWithCompletionHandler:] : 696 -> 712
~ -[AVMetricEventStream init] : 196 -> 204
~ -[AVMetricEventStream didReceiveEventForMetricEventTimeline:event:] : 176 -> 180
~ ___50-[AVMetricEventStream addPublisher:eventTimeline:]_block_invoke : 728 -> 692
~ _avmetric_didReceiveEvent : 8 -> 152
~ ___46-[AVMetricEventStream subscribeToMetricEvent:]_block_invoke : 236 -> 240
~ ___49-[AVMetricEventStream subscribeToAllMetricEvents]_block_invoke : 208 -> 212
~ -[AVAssetReaderTrackOutput _figAssetReaderExtractionOptions] : 952 -> 1004
+ -[AVPixelBufferAttributesVideoOutputSettings decompressionProperties]
~ -[AVPlayerItemIntegratedTimelinePeriodicObserver rescheduleObserverWithSnapshot:itemToSchedule:] : 1660 -> 1736
CStrings:
+ "decompressionProperties"
- "_publishers"
```
