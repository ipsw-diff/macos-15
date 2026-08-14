## MediaPlayer

> `/System/iOSSupport/System/Library/Frameworks/MediaPlayer.framework/Versions/A/MediaPlayer`

```diff

-4024.600.2.0.0
-  __TEXT.__text: 0x1f0f44
+4024.600.8.0.0
+  __TEXT.__text: 0x1f0f58
   __TEXT.__auth_stubs: 0x2fb0
   __TEXT.__objc_methlist: 0x20460
   __TEXT.__const: 0x39d0
-  __TEXT.__cstring: 0x27135
+  __TEXT.__cstring: 0x270b5
   __TEXT.__gcc_except_tab: 0x873c
-  __TEXT.__oslogstring: 0xd707
+  __TEXT.__oslogstring: 0xd7cb
   __TEXT.__dlopen_cstrs: 0x25c
   __TEXT.__ustring: 0x1dc
   __TEXT.__constg_swiftt: 0x80

   __TEXT.__objc_methtype: 0xfa81
   __TEXT.__objc_stubs: 0x26240
   __DATA_CONST.__got: 0x1c50
-  __DATA_CONST.__const: 0xa5b0
+  __DATA_CONST.__const: 0xa590
   __DATA_CONST.__objc_classlist: 0x10c0
   __DATA_CONST.__objc_catlist: 0xa0
   __DATA_CONST.__objc_protolist: 0x340

   __DATA_CONST.__objc_arraydata: 0x780
   __AUTH_CONST.__auth_got: 0x17f0
   __AUTH_CONST.__const: 0x3f00
-  __AUTH_CONST.__cfstring: 0x1ef40
+  __AUTH_CONST.__cfstring: 0x1ef20
   __AUTH_CONST.__objc_const: 0x36b40
   __AUTH_CONST.__objc_intobj: 0x420
   __AUTH_CONST.__objc_arrayobj: 0xdb0

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 12783
-  Symbols:   28101
+  Functions: 12782
+  Symbols:   28099
   CStrings:  18505
 
Symbols:
+ __77-[MPNowPlayingInfoCenter _contentItemForIdentifier:alreadyOnDataSourceQueue:]_block_invoke
- __77-[MPNowPlayingInfoCenter _contentItemForIdentifier:alreadyOnDataSourceQueue:]_block_invoke_2
- ___77-[MPNowPlayingInfoCenter _contentItemForIdentifier:alreadyOnDataSourceQueue:]_block_invoke_4
- ___block_descriptor_64_e8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
Functions:
~ -[MPNowPlayingInfoCenter _contentItemForIdentifier:alreadyOnDataSourceQueue:] : 588 -> 564
~ ___77-[MPNowPlayingInfoCenter _contentItemForIdentifier:alreadyOnDataSourceQueue:]_block_invoke_2 : 376 -> 552
- __77-[MPNowPlayingInfoCenter _contentItemForIdentifier:alreadyOnDataSourceQueue:]_block_invoke_2.cold.1
CStrings:
+ "[InfoCenter] <%@: %p (%@)> _contentItemForIdentifier | contentItemID mismatch [MPNowPlayingPlaybackQueueDataSource produced incorrect content item] requestedID=%{public}@ contentItemID=%{public}@"
- "MPNowPlayingPlaybackQueueDataSource produced content item does not match requested identifier: requestedID=%@ contentItemID=%@"
```
