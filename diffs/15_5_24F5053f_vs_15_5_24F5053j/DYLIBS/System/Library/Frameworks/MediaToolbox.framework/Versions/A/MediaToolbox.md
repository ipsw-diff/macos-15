## MediaToolbox

> `/System/Library/Frameworks/MediaToolbox.framework/Versions/A/MediaToolbox`

```diff

-3225.5.2.0.0
-  __TEXT.__text: 0x85e554
-  __TEXT.__auth_stubs: 0xa8f0
+3225.7.1.0.0
+  __TEXT.__text: 0x85f90c
+  __TEXT.__auth_stubs: 0xa930
   __TEXT.__objc_methlist: 0x1c84
-  __TEXT.__const: 0x1c600
-  __TEXT.__gcc_except_tab: 0xe2c
-  __TEXT.__oslogstring: 0x3f70f
-  __TEXT.__cstring: 0x5472f
+  __TEXT.__const: 0x1c610
+  __TEXT.__gcc_except_tab: 0xe84
+  __TEXT.__oslogstring: 0x3f85f
+  __TEXT.__cstring: 0x5488f
   __TEXT.__ustring: 0x1f8
   __TEXT.__dlopen_cstrs: 0xaa
-  __TEXT.__unwind_info: 0x10920
+  __TEXT.__unwind_info: 0x10940
   __TEXT.__eh_frame: 0x1a04
   __TEXT.__objc_classname: 0x763
-  __TEXT.__objc_methname: 0x486b
+  __TEXT.__objc_methname: 0x48cf
   __TEXT.__objc_methtype: 0x1b8e
-  __TEXT.__objc_stubs: 0x4560
+  __TEXT.__objc_stubs: 0x45e0
   __DATA_CONST.__got: 0x2f88
-  __DATA_CONST.__const: 0x1d068
+  __DATA_CONST.__const: 0x1d128
   __DATA_CONST.__objc_classlist: 0x1d8
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x16b0
+  __DATA_CONST.__objc_selrefs: 0x16d0
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x198
   __DATA_CONST.__objc_arraydata: 0x30
-  __AUTH_CONST.__auth_got: 0x5490
+  __AUTH_CONST.__auth_got: 0x54b0
   __AUTH_CONST.__const: 0x361e0
-  __AUTH_CONST.__cfstring: 0x4c160
+  __AUTH_CONST.__cfstring: 0x4c320
   __AUTH_CONST.__objc_const: 0x3ea8
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__objc_doubleobj: 0x10

   __DATA.__objc_ivar: 0x218
   __DATA.__data: 0x2590
   __DATA.__common: 0x17d8
-  __DATA.__bss: 0x32e0
+  __DATA.__bss: 0x3300
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libnetwork.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 27906
-  Symbols:   12912
-  CStrings:  17412
+  Functions: 27914
+  Symbols:   12921
+  CStrings:  17438
 
Symbols:
+ _CFSetGetTypeID
+ _FigCFSetAddSet
+ _FigCopySetOfSystemSupportedMediaFileExtensions
+ _FigStreamingCacheGetMediaStreamDurationAndBytesInCacheAtTime
+ _kFigAlternateNSPredicateVariableKey_AudioMediaSelection
+ _kFigItemIntegratedTimelineSetTimeOption_UpdateCurrentTimeImmediately
+ _kFigPlaybackItemProperty_AutomaticallyHandlesInterstitialEvents
+ _objc_exception_rethrow
+ _objc_terminate
CStrings:
+ "<<<< FigItemIntegratedTimeline >>>> %s: %p: %s, can proceed to post SnapshotOutOfSync notifications"
+ "<<<< FigPlayerInterstitial >>>> %s: %p: dequeuing %@ from interstitialPlayer %p"
+ "<<<< FigPlayerInterstitial >>>> %s: %p: enqueued %@ for event %@"
+ "<<<< FigStreamPlayer >>>> %s: [%p|%{public}s] <%p|%{public}s>: Setting automaticallyHandlesInterstitialEvents to %d"
+ "<<<< FigStreamPlayer >>>> %s: [%p|%{public}s] <%p|%{public}s>: track: %ld, first needFrame: %f, gopQueue: %f (len: %ld)"
+ "AutomaticallyHandlesInterstitialEvents"
+ "UpdateCurrentTimeImmediately"
+ "audioMediaSelection"
+ "compoundPredicateType"
+ "coordinator was not able to vend its tracked events"
+ "doc"
+ "docx"
+ "fpfsi_EnqueueVideoSamplesWithClamping"
+ "fpic_DequeueItemsFromInterstitialPlayer"
+ "fpic_EnsureNextEventWillBuffer_block_invoke"
+ "initWithType:subpredicates:"
+ "jpg"
+ "observed first set of server side interstitials"
+ "pdf"
+ "png"
+ "predicateWithSubstitutionVariables:"
+ "rtf"
+ "subpredicates"
+ "tar"
+ "tif"
+ "tiff"
+ "zip"
- "<<<< FigItemIntegratedTimeline >>>> %s: %p: observed first set of server side interstitials, can proceed to post SnapshotOutOfSync notifications"
```
