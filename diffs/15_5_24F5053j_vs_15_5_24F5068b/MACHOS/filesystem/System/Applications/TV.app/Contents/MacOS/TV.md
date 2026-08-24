## TV

> `/System/Applications/TV.app/Contents/MacOS/TV`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_capture`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_nlclslist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__thread_vars`

```diff

-1.5.5.30.0
-  __TEXT.__text: 0xe5f488
-  __TEXT.__auth_stubs: 0x6e70
+1.5.5.33.0
+  __TEXT.__text: 0xe5bd7c
+  __TEXT.__auth_stubs: 0x6d90
   __TEXT.__objc_stubs: 0x21ae0
   __TEXT.__init_offsets: 0x254
   __TEXT.__objc_methlist: 0x16b50
-  __TEXT.__const: 0xb7a29
-  __TEXT.__cstring: 0x77e29
+  __TEXT.__const: 0xb76c9
+  __TEXT.__cstring: 0x77c07
   __TEXT.__objc_methname: 0x3140c
   __TEXT.__constg_swiftt: 0x1194
   __TEXT.__swift5_typeref: 0x87e

   __TEXT.__objc_classname: 0x2de6
   __TEXT.__objc_methtype: 0x1040e
   __TEXT.__swift5_capture: 0x398
-  __TEXT.__gcc_except_tab: 0xbf218
-  __TEXT.__oslogstring: 0x1fdc2
+  __TEXT.__gcc_except_tab: 0xbef18
+  __TEXT.__oslogstring: 0x1f964
   __TEXT.__ustring: 0x80
-  __TEXT.__unwind_info: 0x484f8
+  __TEXT.__unwind_info: 0x483d0
   __TEXT.__eh_frame: 0x26c
-  __DATA_CONST.__auth_got: 0x3750
-  __DATA_CONST.__got: 0x1f68
+  __DATA_CONST.__auth_got: 0x36e0
+  __DATA_CONST.__got: 0x1f28
   __DATA_CONST.__auth_ptr: 0x3d8
-  __DATA_CONST.__const: 0x142d38
-  __DATA_CONST.__cfstring: 0x263a0
+  __DATA_CONST.__const: 0x142b60
+  __DATA_CONST.__cfstring: 0x26300
   __DATA_CONST.__objc_classlist: 0xc60
   __DATA_CONST.__objc_nlclslist: 0x8
   __DATA_CONST.__objc_catlist: 0x98

   __DATA.__objc_selrefs: 0xcbc0
   __DATA.__objc_ivar: 0x1118
   __DATA.__objc_data: 0x9188
-  __DATA.__data: 0x4be4
+  __DATA.__data: 0x4bdc
   __DATA.__thread_vars: 0x18
   __DATA.__thread_data: 0x10
   __DATA.__common: 0xee30

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 61317
-  Symbols:   2817
-  CStrings:  30337
+  Functions: 61273
+  Symbols:   2795
+  CStrings:  30305
 
Symbols:
+ _AVCFPlayerItemSeekToTimeWithCompletionCallback
- _AVCFAssetDownloadSessionDownloadInterstitials
- _AVCFMediaSelectionOptionCopyPropertyList
- _AVCFPlayerIntegratedTimelineSnapshotsOutOfSyncNotification
- _AVCFPlayerIntegratedTimelineSnapshotsOutOfSyncReasonCurrentSegmentChanged
- _AVCFPlayerIntegratedTimelineSnapshotsOutOfSyncReasonKey
- _AVCFPlayerIntegratedTimelineSnapshotsOutOfSyncReasonLoadedTimeRangesChanged
- _AVCFPlayerIntegratedTimelineSnapshotsOutOfSyncReasonSegmentsChanged
- _AVCFPlayerInterstitialEventMonitorCurrentEventDidChangeNotification
- _AVCFPlayerInterstitialEventMonitorEventsDidChangeNotification
- _AVCFPlayerInterstitialEventMonitor_Copy_InterstitialPlayer
- _AVCFPlayerInterstitialEventMonitor_Create
- _AVCFPlayerItemIntegratedTimelineInspection_Copy_CurrentDate
- _AVCFPlayerItemIntegratedTimelineInspection_Get_CurrentTime
- _AVCFPlayerItemIntegratedTimelineSnapshot_Copy_CurrentSegment
- _AVCFPlayerItemIntegratedTimelineSnapshot_Copy_Segments
- _AVCFPlayerItemIntegratedTimelineSnapshot_Get_Duration
- _AVCFPlayerItemIntegratedTimeline_Copy_CurrentSnapshot
- _AVCFPlayerItemIntegratedTimeline_SeekToTime
- _AVCFPlayerItemIntegratedTimeline_TypeCast
- _AVCFPlayerItemSegment_Copy_LoadedTimeRanges
- _AVCFPlayerItemSegment_Get_Type
- _AVCFPlayerItem_Copy_IntegratedTimeline
- _AVCFPlayerSetExternalPlaybackInterstitialSchedulingStrategy
CStrings:
+ "%s/AMPLibraryAgent-1.5.5.33"
+ "1.5.5.33"
+ "13.5.5.33"
+ "Apple TV 1.5.5.33"
+ "inSampleAccurate"
+ "play> avcff> AVCFPlayerItemSeekToTime 0x%llx t=%lld"
+ "play> avcff> AVCFPlayerItemSeekToTimeWithCompletionCallback 0x%llx t=%lld"
- "%s/AMPLibraryAgent-1.5.5.30"
- "1.5.5.30"
- "13.5.5.30"
- "<---"
- "AVCFAssetDownloadSessionInterstitialMediaSelectionCriteria"
- "AVCFMediaCharacteristicAudible"
- "AVCFMediaCharacteristicIsOriginalContent"
- "AVCFPlayerMediaSelectionCriteriaPremiumCharacteristicsKey"
- "Apple TV 1.5.5.30"
- "HandleTracksChanged"
- "InterstitialSegmentChanged"
- "MediaSelectionOptionsTaggedMediaCharacteristics"
- "integratedTimeline != nullptr"
- "interstitialPlayer != nullptr"
- "interstitials"
- "itavcfPlayerItem.interstitialSegmentChanged"
- "mAVCFInterstitialEventMonitor != nullptr"
- "mCachedSnapshot != nullptr"
- "mIntegratedTimeline != nullptr"
- "mPlatPlayerPriv != nullptr"
- "play> avcff> %s interstitial ppi=%p %s"
- "play> avcff> %s primary ppi=%p %s"
- "play> avcff> alt> '%{public}s' not found for playerItem %p"
- "play> avcff> alt> SetAlternateTrackHandlerPlayerItem %p (%@) ppi=%p --> %p"
- "play> avcff> alt> setting '%{public}s' on playerItem %p"
- "play> avcff> noti> timeline> '%{public}@'"
- "play> avcff> noti> timeline> reason '%{public}s'"
- "play> avcff> timeline> AVCFPlayerItemIntegratedTimelineSnapshot_Copy_CurrentSegment returned nil"
- "play> avcff> timeline> AVCFPlayerItemIntegratedTimelineSnapshot_Copy_CurrentSegment type=%d"
- "play> avcff> timeline> AVCFPlayerItemIntegratedTimelineSnapshot_Copy_Segments %d"
- "play> avcff> timeline> AVCFPlayerItemIntegratedTimelineSnapshot_Get_Duration (%0.2f NotLive)"
- "play> avcff> timeline> AVCFPlayerItemIntegratedTimelineSnapshot_Get_Duration (indefinite)"
- "play> avcff> timeline> AVCFPlayerItemIntegratedTimelineSnapshot_Get_Duration (invalid)"
- "play> avcff> timeline> AVCFPlayerItemIntegratedTimeline_Copy_CurrentSnapshot"
- "play> avcff> timeline> AVCFPlayerItemIntegratedTimeline_SeekToTime %02.f"
- "play> avcff> timeline> AVCFPlayerItemSegment_Copy_LoadedTimeRanges (%0.2f - %0.2f)"
- "play> cm> force recheck initial audio locale ppi=%p"
- "play> cm> timeline> ***ERROR*** CopyCurrentSnapshot returned nil"
- "timelineInspection != nullptr"
```
