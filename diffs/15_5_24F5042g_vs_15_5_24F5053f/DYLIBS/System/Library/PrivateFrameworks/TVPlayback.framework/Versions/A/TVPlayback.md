## TVPlayback

> `/System/Library/PrivateFrameworks/TVPlayback.framework/Versions/A/TVPlayback`

```diff

-563.50.1.0.0
-  __TEXT.__text: 0x61c4c
-  __TEXT.__auth_stubs: 0x620
-  __TEXT.__objc_methlist: 0x5540
+563.50.4.0.0
+  __TEXT.__text: 0x61fe8
+  __TEXT.__auth_stubs: 0x630
+  __TEXT.__objc_methlist: 0x5550
   __TEXT.__const: 0x238
-  __TEXT.__cstring: 0x62dc
-  __TEXT.__oslogstring: 0x41ad
-  __TEXT.__gcc_except_tab: 0x2210
-  __TEXT.__unwind_info: 0x1488
+  __TEXT.__cstring: 0x6313
+  __TEXT.__oslogstring: 0x439c
+  __TEXT.__gcc_except_tab: 0x2200
+  __TEXT.__unwind_info: 0x1478
   __TEXT.__objc_classname: 0x6ff
-  __TEXT.__objc_methname: 0x109b4
+  __TEXT.__objc_methname: 0x109cd
   __TEXT.__objc_methtype: 0x1fa9
-  __TEXT.__objc_stubs: 0xa2e0
-  __DATA_CONST.__got: 0x688
-  __DATA_CONST.__const: 0xc70
+  __TEXT.__objc_stubs: 0xa300
+  __DATA_CONST.__got: 0x690
+  __DATA_CONST.__const: 0xc78
   __DATA_CONST.__objc_classlist: 0x1c0
   __DATA_CONST.__objc_catlist: 0x80
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3898
+  __DATA_CONST.__objc_selrefs: 0x38a0
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x150
   __DATA_CONST.__objc_arraydata: 0x10
-  __AUTH_CONST.__auth_got: 0x320
+  __AUTH_CONST.__auth_got: 0x328
   __AUTH_CONST.__const: 0x1c70
-  __AUTH_CONST.__cfstring: 0x6200
+  __AUTH_CONST.__cfstring: 0x6220
   __AUTH_CONST.__objc_const: 0x8360
   __AUTH_CONST.__objc_intobj: 0x4e0
   __AUTH_CONST.__objc_arrayobj: 0x30

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2025
-  Symbols:   5055
-  CStrings:  4048
+  Functions: 2026
+  Symbols:   5059
+  CStrings:  4055
 
Symbols:
+ -[TVPPlayer _integratedTimelineEnabled]
+ -[TVPPlayer _isNetworkAvailable]
+ GCC_except_table382
+ GCC_except_table406
+ GCC_except_table414
+ GCC_except_table419
+ GCC_except_table424
+ GCC_except_table427
+ GCC_except_table430
+ GCC_except_table436
+ GCC_except_table440
+ GCC_except_table445
+ GCC_except_table449
+ GCC_except_table454
+ GCC_except_table462
+ GCC_except_table464
+ GCC_except_table466
+ GCC_except_table493
+ GCC_except_table495
+ GCC_except_table498
+ GCC_except_table504
+ GCC_except_table511
+ GCC_except_table514
+ GCC_except_table519
+ GCC_except_table523
+ GCC_except_table529
+ GCC_except_table537
+ GCC_except_table540
+ GCC_except_table552
+ GCC_except_table554
+ GCC_except_table557
+ GCC_except_table561
+ GCC_except_table723
+ _CFRelease
+ _TVPMediaItemMetadataRestrictToOfflineAudioOptions
+ _kCFAllocatorDefault
+ _objc_msgSend$_integratedTimelineEnabled
+ _objc_msgSend$_isNetworkAvailable
- -[TVPPlayer _interstitialsEnabled]
- GCC_except_table245
- GCC_except_table381
- GCC_except_table405
- GCC_except_table412
- GCC_except_table417
- GCC_except_table422
- GCC_except_table425
- GCC_except_table428
- GCC_except_table435
- GCC_except_table439
- GCC_except_table444
- GCC_except_table448
- GCC_except_table453
- GCC_except_table461
- GCC_except_table463
- GCC_except_table465
- GCC_except_table492
- GCC_except_table494
- GCC_except_table497
- GCC_except_table503
- GCC_except_table510
- GCC_except_table513
- GCC_except_table518
- GCC_except_table522
- GCC_except_table528
- GCC_except_table536
- GCC_except_table539
- GCC_except_table551
- GCC_except_table553
- GCC_except_table556
- GCC_except_table560
- GCC_except_table722
- _objc_msgSend$_interstitialsEnabled
Functions:
~ -[TVPPlayer setCurrentPlayerItem:] : 608 -> 612
~ -[TVPPlayer _addBoundaryTimeObserversToIntegratedTimeline:] : 1456 -> 1592
~ ___59-[TVPPlayer _addBoundaryTimeObserversToIntegratedTimeline:]_block_invoke : 160 -> 144
+ -[TVPPlayer _isNetworkAvailable]
~ __42-[TVPPlayer _registerStateMachineHandlers]_block_invoke_3.777 : 3808 -> 4044
~ __42-[TVPPlayer _registerStateMachineHandlers]_block_invoke_4.1041 : 2644 -> 2860
~ -[TVPReachabilityMonitor dealloc] : 152 -> 164
~ ___58-[TVPMediaItemLoader _loadMediaItemMetadataAsynchronously]_block_invoke_3 : 2244 -> 2392
CStrings:
+ "Adding boundary observer to segment %@ for time %@"
+ "DisableIntegratedTimeline"
+ "Media item is downloaded and wants to restrict automatic media selection to offline options"
+ "Media item is downloaded but network is not available.  Restricting automatic media selection to offline options"
+ "Media item metadata already contains a haptics URL string, not overriding"
+ "Playback of downloaded content failed with not connected error.  Will retry playback of downloaded content and restrict automatic media selection to offline options"
+ "TVPMediaItemMetadataRestrictToOfflineAudioOptions"
+ "_integratedTimelineEnabled"
+ "_isNetworkAvailable"
- "DisableInterstitials"
- "_interstitialsEnabled"
```
