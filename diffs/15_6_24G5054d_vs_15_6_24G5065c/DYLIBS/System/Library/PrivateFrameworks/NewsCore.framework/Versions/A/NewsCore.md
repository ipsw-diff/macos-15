## NewsCore

> `/System/Library/PrivateFrameworks/NewsCore.framework/Versions/A/NewsCore`

```diff

-5691.0.0.0.0
-  __TEXT.__text: 0x3f9bdc
+5696.0.0.0.0
+  __TEXT.__text: 0x3fa2ac
   __TEXT.__auth_stubs: 0x32e0
-  __TEXT.__objc_methlist: 0x330f4
+  __TEXT.__objc_methlist: 0x33114
   __TEXT.__const: 0x7708
   __TEXT.__swift5_typeref: 0x2b1a
   __TEXT.__constg_swiftt: 0x1f1c

   __TEXT.__swift5_fieldmd: 0x1a2c
   __TEXT.__swift5_proto: 0x554
   __TEXT.__swift5_types: 0x268
-  __TEXT.__cstring: 0x56888
+  __TEXT.__cstring: 0x569b1
   __TEXT.__swift5_capture: 0x8ac
   __TEXT.__swift5_builtin: 0x118
   __TEXT.__swift5_protos: 0x4c
   __TEXT.__swift5_assocty: 0x310
   __TEXT.__swift_as_entry: 0x22c
   __TEXT.__swift_as_ret: 0x2ac
-  __TEXT.__oslogstring: 0x15923
+  __TEXT.__oslogstring: 0x159e7
   __TEXT.__swift5_mpenum: 0x4c
   __TEXT.__gcc_except_tab: 0x54c4
   __TEXT.__dlopen_cstrs: 0x11c
   __TEXT.__ustring: 0x27a
-  __TEXT.__unwind_info: 0xd3f0
+  __TEXT.__unwind_info: 0xd400
   __TEXT.__eh_frame: 0x74f8
-  __TEXT.__objc_classname: 0x74db
-  __TEXT.__objc_methname: 0x83e98
+  __TEXT.__objc_classname: 0x74de
+  __TEXT.__objc_methname: 0x83f18
   __TEXT.__objc_methtype: 0xc74e
-  __TEXT.__objc_stubs: 0x34840
+  __TEXT.__objc_stubs: 0x348a0
   __DATA_CONST.__got: 0x29b8
   __DATA_CONST.__const: 0x6bc0
   __DATA_CONST.__objc_classlist: 0x1bd8
   __DATA_CONST.__objc_catlist: 0x2a8
   __DATA_CONST.__objc_protolist: 0x880
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x141e0
+  __DATA_CONST.__objc_selrefs: 0x141f8
   __DATA_CONST.__objc_protorefs: 0x1e0
   __DATA_CONST.__objc_superrefs: 0x1558
   __DATA_CONST.__objc_arraydata: 0x1d38
   __AUTH_CONST.__auth_got: 0x1988
-  __AUTH_CONST.__const: 0x15398
-  __AUTH_CONST.__cfstring: 0x30480
+  __AUTH_CONST.__const: 0x153c8
+  __AUTH_CONST.__cfstring: 0x30440
   __AUTH_CONST.__objc_const: 0x74708
   __AUTH_CONST.__objc_arrayobj: 0x540
   __AUTH_CONST.__objc_intobj: 0x13c8

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 22716
-  Symbols:   43167
-  CStrings:  28292
+  Functions: 22720
+  Symbols:   43175
+  CStrings:  28300
 
Symbols:
+ -[FCCKPrivateBatchedSaveRecordsOperation identityLossResponse]
+ -[FCCKPrivateBatchedSaveRecordsOperation setIdentityLossResponse:]
+ -[FCCKPrivateDatabaseOperation identityLossResponse]
+ -[FCCKPrivateDatabaseOperation setIdentityLossResponse:]
+ -[NSError(FCCKAdditions) fc_zoneIDsWithIdentityLossError]
+ __61-[FCCKPrivateDatabaseOperation canRetryWithError:retryAfter:]_block_invoke
+ ___57-[NSError(FCCKAdditions) fc_zoneIDsWithIdentityLossError]_block_invoke_4
+ ___block_descriptor_40_e8_32s_e24_v32?08"NSError"16^B24l
+ _objc_msgSend$fc_zoneIDsWithIdentityLossError
+ _objc_msgSend$identityLossResponse
+ _objc_msgSend$setIdentityLossResponse:
- -[FCCKPrivateBatchedSaveRecordsOperation handleIdentityLoss]
- -[FCCKPrivateBatchedSaveRecordsOperation setHandleIdentityLoss:]
- -[FCCKPrivateDatabaseOperation handleIdentityLoss]
CStrings:
+ "%{public}@ encountered identity loss error, will delete zones: %{public}@"
+ "%{public}@ encountered identity loss error, will ignore"
+ "%{public}@ encountered identity loss error, will rebuild database"
+ "-[FCFeedTransformationFilter transformFeedItemsWithResults:]_block_invoke"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/FeldsparServices/feldsparcore/Classes/FCFeedTransformationFilter.m"
+ "CREATE UNIQUE INDEX IF NOT EXISTS index_feed_item_lookup ON feed_item_lookup (feed_lookup_id, feed_item_order, feature);"
+ "Tq,N,V_identityLossResponse"
+ "_identityLossResponse"
+ "can't apply zero-tabi-score filter without a score profile"
+ "fc_zoneIDsWithIdentityLossError"
+ "identityLossResponse"
+ "setIdentityLossResponse:"
+ "v32@?0@8@\"NSError\"16^B24"
- "CREATE INDEX IF NOT EXISTS index_feed_item_lookup ON feed_item_lookup (feed_lookup_id, feed_item_order, feature);"
- "FCFeedBinA"
- "FCFeedBinB"
- "FCFeedBinC"
- "FCFeedBinUnknown"
```
