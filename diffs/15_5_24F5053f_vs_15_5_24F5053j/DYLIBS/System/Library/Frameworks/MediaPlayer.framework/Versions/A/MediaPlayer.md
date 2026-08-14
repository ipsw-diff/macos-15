## MediaPlayer

> `/System/Library/Frameworks/MediaPlayer.framework/Versions/A/MediaPlayer`

```diff

-4024.600.2.0.0
-  __TEXT.__text: 0x1ded38
+4024.600.8.0.0
+  __TEXT.__text: 0x1dedbc
   __TEXT.__auth_stubs: 0x27d0
   __TEXT.__objc_methlist: 0x1bcc4
   __TEXT.__const: 0x38bb
   __TEXT.__dlopen_cstrs: 0x1da
-  __TEXT.__cstring: 0x24a77
+  __TEXT.__cstring: 0x249f8
   __TEXT.__constg_swiftt: 0x80
   __TEXT.__swift5_typeref: 0x42
   __TEXT.__swift5_reflstr: 0xc
   __TEXT.__swift5_fieldmd: 0x2c
   __TEXT.__swift5_proto: 0x14
   __TEXT.__swift5_types: 0x8
-  __TEXT.__gcc_except_tab: 0x7f1c
-  __TEXT.__oslogstring: 0xb670
+  __TEXT.__gcc_except_tab: 0x7f18
+  __TEXT.__oslogstring: 0xb734
   __TEXT.__ustring: 0x1ca
   __TEXT.__unwind_info: 0x8028
   __TEXT.__eh_frame: 0x110

   __DATA_CONST.__objc_arraydata: 0x768
   __AUTH_CONST.__auth_got: 0x1400
   __AUTH_CONST.__const: 0xa3e0
-  __AUTH_CONST.__cfstring: 0x1d2e0
+  __AUTH_CONST.__cfstring: 0x1d2c0
   __AUTH_CONST.__objc_const: 0x2f520
   __AUTH_CONST.__objc_arrayobj: 0xd98
   __AUTH_CONST.__objc_intobj: 0x3d8
Symbols:
+ __77-[MPNowPlayingInfoCenter _contentItemForIdentifier:alreadyOnDataSourceQueue:]_block_invoke
- ___77-[MPNowPlayingInfoCenter _contentItemForIdentifier:alreadyOnDataSourceQueue:]_block_invoke_4
Functions:
~ -[MPNowPlayingInfoCenter _contentItemForIdentifier:alreadyOnDataSourceQueue:] : 616 -> 592
~ ___77-[MPNowPlayingInfoCenter _contentItemForIdentifier:alreadyOnDataSourceQueue:]_block_invoke_2 : 412 -> 568
CStrings:
+ "[InfoCenter] <%@: %p (%@)> _contentItemForIdentifier | contentItemID mismatch [MPNowPlayingPlaybackQueueDataSource produced incorrect content item] requestedID=%{public}@ contentItemID=%{public}@"
- "MPNowPlayingPlaybackQueueDataSource produced content item does not match requested identifier: requestedID=%@ contentItemID=%@"
```
