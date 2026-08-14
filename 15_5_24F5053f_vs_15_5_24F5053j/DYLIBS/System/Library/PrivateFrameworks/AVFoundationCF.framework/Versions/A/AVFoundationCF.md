## AVFoundationCF

> `/System/Library/PrivateFrameworks/AVFoundationCF.framework/Versions/A/AVFoundationCF`

```diff

-710.5.2.0.0
-  __TEXT.__text: 0xc1f84
+710.7.1.0.0
+  __TEXT.__text: 0xc203c
   __TEXT.__auth_stubs: 0x2460
   __TEXT.__objc_methlist: 0xa4
   __TEXT.__const: 0x368
-  __TEXT.__oslogstring: 0x10379
-  __TEXT.__cstring: 0x15947
-  __TEXT.__unwind_info: 0x1c68
+  __TEXT.__oslogstring: 0x10421
+  __TEXT.__cstring: 0x15937
+  __TEXT.__unwind_info: 0x1c60
   __TEXT.__objc_classname: 0x47
   __TEXT.__objc_methname: 0x3d9
   __TEXT.__objc_methtype: 0x11c

   - /System/Library/PrivateFrameworks/InternationalSupport.framework/Versions/A/InternationalSupport
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3509
-  Symbols:   5480
-  CStrings:  3319
+  Functions: 3510
+  Symbols:   5481
+  CStrings:  3320
 
Symbols:
+ AVCFPlayerLayer_Set_ShowInterstitialInsteadWithDelay
+ _AVCFPlayerLayer_CopyInterstitialLayerIfCreated
+ _timeline_AttachToCoordinator
+ timeline_AttachToCoordinator
- AVCFPlaybackCoordinator_ApplyIntegratedTimelineSeek
- _timeline_AttachToInterstitialCoordinator
- timeline_AttachToInterstitialCoordinator
CStrings:
+ "<<<< AVCFPlayerItem >>>> %s: no interstitialCoordinator, err = %d [%{public}s]"
+ "<<<< AVCFPlayerItem >>>> %s: no player attached, yet [%{public}s]"
+ "<<<< AVCFPlayerLayer >>>> %s: no interstitialLayer from (%p) layer"
+ "<<<< Interstitial >>>> %s: no figPlaybackItem [%{public}s]"
+ "<<<< PlaybackCoordinator >>>> %s: (%p) %s coordinator called (%p) FigPlaybackCoordinatorHandleUpdatedTimelineStateFromMedium with currentTransportControlState (%p) : %@"
+ "<<<< PlaybackCoordinator >>>> %s: integratedTimeline %p seek at %.2f current time at %.2f applied : %d"
+ "interstitial"
+ "no integratedTimeline from interstitial item"
+ "primary"
+ "timeline_AttachToCoordinator"
- "<<<< AVCFPlayerItem >>>> %s: no coordinator, err = %d [%{public}s]"
- "<<<< AVCFPlayerItem >>>> %s: no integratedTimeline for interstitialPlayer [%{public}s]"
- "<<<< AVCFPlayerItem >>>> %s: no player [%{public}s]"
- "<<<< AVCFPlayerItem >>>> %s: timeline_AttachToItem err = %d [%{public}s]"
- "<<<< PlaybackCoordinator >>>> %s: integrated timeline seek at %.2f current time at %.2f applied"
- "AVCFPlayerLayerCreateWithAVCFPlayer"
- "figPlaybackItem"
- "interstitialLayer"
- "timeline_AttachToInterstitialCoordinator"
```
