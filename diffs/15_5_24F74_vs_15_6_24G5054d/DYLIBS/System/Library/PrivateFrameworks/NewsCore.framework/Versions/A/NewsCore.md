## NewsCore

> `/System/Library/PrivateFrameworks/NewsCore.framework/Versions/A/NewsCore`

```diff

-5681.0.0.0.0
-  __TEXT.__text: 0x3f8430
+5691.0.0.0.0
+  __TEXT.__text: 0x3f9bdc
   __TEXT.__auth_stubs: 0x32e0
-  __TEXT.__objc_methlist: 0x33044
-  __TEXT.__const: 0x7108
+  __TEXT.__objc_methlist: 0x330f4
+  __TEXT.__const: 0x7708
   __TEXT.__swift5_typeref: 0x2b1a
   __TEXT.__constg_swiftt: 0x1f1c
   __TEXT.__swift5_reflstr: 0x1450
   __TEXT.__swift5_fieldmd: 0x1a2c
   __TEXT.__swift5_proto: 0x554
   __TEXT.__swift5_types: 0x268
-  __TEXT.__cstring: 0x561c1
+  __TEXT.__cstring: 0x56888
   __TEXT.__swift5_capture: 0x8ac
   __TEXT.__swift5_builtin: 0x118
   __TEXT.__swift5_protos: 0x4c
   __TEXT.__swift5_assocty: 0x310
   __TEXT.__swift_as_entry: 0x22c
   __TEXT.__swift_as_ret: 0x2ac
-  __TEXT.__oslogstring: 0x1573e
+  __TEXT.__oslogstring: 0x15923
   __TEXT.__swift5_mpenum: 0x4c
-  __TEXT.__gcc_except_tab: 0x5484
+  __TEXT.__gcc_except_tab: 0x54c4
   __TEXT.__dlopen_cstrs: 0x11c
   __TEXT.__ustring: 0x27a
-  __TEXT.__unwind_info: 0xd3d8
+  __TEXT.__unwind_info: 0xd3f0
   __TEXT.__eh_frame: 0x74f8
-  __TEXT.__objc_classname: 0x74d9
-  __TEXT.__objc_methname: 0x83ce8
-  __TEXT.__objc_methtype: 0xc786
-  __TEXT.__objc_stubs: 0x347c0
+  __TEXT.__objc_classname: 0x74db
+  __TEXT.__objc_methname: 0x83e98
+  __TEXT.__objc_methtype: 0xc74e
+  __TEXT.__objc_stubs: 0x34840
   __DATA_CONST.__got: 0x29b8
-  __DATA_CONST.__const: 0x6bb8
+  __DATA_CONST.__const: 0x6bc0
   __DATA_CONST.__objc_classlist: 0x1bd8
   __DATA_CONST.__objc_catlist: 0x2a8
   __DATA_CONST.__objc_protolist: 0x880
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x141a0
+  __DATA_CONST.__objc_selrefs: 0x141e0
   __DATA_CONST.__objc_protorefs: 0x1e0
   __DATA_CONST.__objc_superrefs: 0x1558
   __DATA_CONST.__objc_arraydata: 0x1d38
   __AUTH_CONST.__auth_got: 0x1988
-  __AUTH_CONST.__const: 0x153c8
-  __AUTH_CONST.__cfstring: 0x30420
-  __AUTH_CONST.__objc_const: 0x745d8
+  __AUTH_CONST.__const: 0x15398
+  __AUTH_CONST.__cfstring: 0x30480
+  __AUTH_CONST.__objc_const: 0x74708
   __AUTH_CONST.__objc_arrayobj: 0x540
   __AUTH_CONST.__objc_intobj: 0x13c8
   __AUTH_CONST.__objc_dictobj: 0xbe0
   __AUTH_CONST.__objc_doubleobj: 0x120
   __AUTH.__objc_data: 0xa648
-  __AUTH.__data: 0x13f0
-  __DATA.__objc_ivar: 0x52b4
-  __DATA.__data: 0x7098
+  __AUTH.__data: 0x13e0
+  __DATA.__objc_ivar: 0x52c8
+  __DATA.__data: 0x6af8
   __DATA.__bss: 0xbf68
   __DATA.__common: 0x288
   __DATA_DIRTY.__objc_data: 0x70d0

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 22702
-  Symbols:   43148
-  CStrings:  28273
+  Functions: 22716
+  Symbols:   43167
+  CStrings:  28292
 
Symbols:
+ +[FCCKRecordFieldSchema fieldWithName:type:isEncrypted:]
+ +[FCEdgeCacheHint(NewsSpecific) edgeCacheHintForWidgetArticles]
+ +[FCEdgeCacheHint(NewsSpecific) edgeCacheHintForWidgetConfig]
+ -[FCCKDatabaseEncryptionMiddleware _removeField:fromRecord:]
+ -[FCCKRecordFieldSchema sanitizeValue:]
+ -[FCCKRecordSchema schemaForField:]
+ -[FCFileCoordinatedTodayPersonalizationUpdate submitUpdate:]
+ -[FCFileCoordinatedTodayPrivateDataTransactionQueue enqueueTransaction:withMaxTransactionCount:]
+ -[FCMultiSourceHeadlinesOperation cachePolicyForArticles]
+ -[FCMultiSourceHeadlinesOperation edgeCacheHint]
+ -[FCMultiSourceHeadlinesOperation heldRecordsCompletionHandler]
+ -[FCMultiSourceHeadlinesOperation resultHeldRecordsByType]
+ -[FCMultiSourceHeadlinesOperation setCachePolicyForArticles:]
+ -[FCMultiSourceHeadlinesOperation setEdgeCacheHint:]
+ -[FCMultiSourceHeadlinesOperation setHeldRecordsCompletionHandler:]
+ -[FCMultiSourceHeadlinesOperation setResultHeldRecordsByType:]
+ -[FCNewsAppConfig adSponsorshipsEnabled]
+ -[FCNewsAppConfig isTodaySponsorshipEligible]
+ -[FCWritablePrivateDataStorage writeReadHistoryItem:]
+ -[FCWritablePrivateDataStorage writeSeenHistoryItems:]
+ -[NSFileManager(FCAdditions) fc_removeContentsOfDirectoryAtURL:removedItemCount:error:]
+ OBJC_IVAR_$_FCCKRecordFieldSchema._type
+ _FCWidgetShouldIgnoreJSONRecordsSharedPreferenceKey
+ _NSURLFileResourceIdentifierKey
+ ___47-[NTPBAVAsset(Bookmark) resolvedFileResourceID]_block_invoke_2
+ ___51-[FCMultiSourceHeadlinesOperation performOperation]_block_invoke_2
+ ___60-[FCFileCoordinatedTodayPersonalizationUpdate submitUpdate:]_block_invoke
+ ___96-[FCFileCoordinatedTodayPrivateDataTransactionQueue enqueueTransaction:withMaxTransactionCount:]_block_invoke
+ _fsctl
+ _objc_msgSend$cachePolicyForArticles
+ _objc_msgSend$depositSyncWithAccessor:
+ _objc_msgSend$enqueueTransaction:withMaxTransactionCount:
+ _objc_msgSend$fc_removeContentsOfDirectoryAtURL:removedItemCount:error:
+ _objc_msgSend$heldRecordsCompletionHandler
+ _objc_msgSend$resultHeldRecordsByType
+ _objc_msgSend$setResultHeldRecordsByType:
- +[FCCKRecordFieldSchema fieldWithName:isEncrypted:]
- +[FCEdgeCacheHint(NewsSpecific) edgeCacheHintForToday]
- -[FCFileCoordinatedTodayPersonalizationUpdate submitUpdate:withCompletion:]
- -[FCFileCoordinatedTodayPrivateDataTransactionQueue enqueueTransaction:withMaxTransactionCount:completion:]
- -[FCWritablePrivateDataStorage writeReadHistoryItem:withCompletion:]
- -[FCWritablePrivateDataStorage writeSeenHistoryItems:withCompletion:]
- _CacheManagementEnumerateAssets
- _OBJC_CLASS_$_CacheManagementAsset
- ___107-[FCFileCoordinatedTodayPrivateDataTransactionQueue enqueueTransaction:withMaxTransactionCount:completion:]_block_invoke
- ___68-[FCWritablePrivateDataStorage writeReadHistoryItem:withCompletion:]_block_invoke
- ___69-[FCWritablePrivateDataStorage writeSeenHistoryItems:withCompletion:]_block_invoke
- ___75-[FCFileCoordinatedTodayPersonalizationUpdate submitUpdate:withCompletion:]_block_invoke
- ___76-[FCAVAssetDownloadManager initWithAssetCache:keyCache:networkReachability:]_block_invoke_2
- ___block_descriptor_40_e8_32s_e30_B16?0"CacheManagementAsset"8l
- _objc_msgSend$assetFromPath:withIdentifier:
- _objc_msgSend$commit
- _objc_msgSend$enqueueTransaction:withMaxTransactionCount:completion:
CStrings:
+ "-[FCCKRecordFieldSchema sanitizeValue:]"
+ "-[FCFileCoordinatedTodayPersonalizationUpdate submitUpdate:]"
+ "-[FCFileCoordinatedTodayPrivateDataTransactionQueue enqueueTransaction:withMaxTransactionCount:]"
+ "-[FCWritablePrivateDataStorage writeReadHistoryItem:]"
+ "-[FCWritablePrivateDataStorage writeSeenHistoryItems:]"
+ "AV asset cache failed to look up resource ID, assetID=%{public}@, url=%{public}@, error=%{public}@"
+ "AV asset cache failed to look up resource ID, url=%{public}@, error=%{public}@"
+ "AV asset download manager failed to mark asset as purgeable, URL=%{public}@, errno=%{public}@"
+ "Client record field is missing from the schema: %{public}@.%{public}@"
+ "Server record field is missing from the schema: %{public}@.%{public}@"
+ "T@\"FCCachePolicy\",&,N,V_cachePolicyForArticles"
+ "T@\"NSArray\",C,N,V_articleIDs"
+ "T@\"NSDictionary\",&,N,V_resultHeldRecordsByType"
+ "T@?,C,N,V_heldRecordsCompletionHandler"
+ "_cachePolicyForArticles"
+ "_heldRecordsCompletionHandler"
+ "adSponsorshipsEnabled"
+ "adSponsorshipsEnabledLevel"
+ "cachePolicyForArticles"
+ "edgeCacheHintForWidgetArticles"
+ "edgeCacheHintForWidgetConfig"
+ "enqueueTransaction:withMaxTransactionCount:"
+ "failed to create directory for AV asset downloads with error: %{public}@"
+ "failed to create directory for AV asset downloads with exception: %{public}@"
+ "fc_removeContentsOfDirectoryAtURL:removedItemCount:error:"
+ "heldRecordsCompletionHandler"
+ "isTodaySponsorshipEligible"
+ "privateDataCleanupToV4Level3"
+ "privateDataMigrateToV4Level3"
+ "resultHeldRecordsByType"
+ "setCachePolicyForArticles:"
+ "setHeldRecordsCompletionHandler:"
+ "setResultHeldRecordsByType:"
+ "submitUpdate:"
+ "unexpected type %@ for field %@"
+ "unexpected type within array %@ for field %@"
+ "v24@0:8@\"<FCReadingHistoryItem>\"16"
+ "widget_ignore_json_records"
+ "widgetarticles"
+ "writeReadHistoryItem:"
+ "writeSeenHistoryItems:"
- "*** Assertion failure (Identifier: UnknownRecordField) : %s %s:%d %{public}@"
- "-[FCCKDatabaseEncryptionMiddleware _decryptRecord:withEncryptionKey:mapping:error:]"
- "-[FCFileCoordinatedTodayPersonalizationUpdate submitUpdate:withCompletion:]"
- "-[FCFileCoordinatedTodayPrivateDataTransactionQueue enqueueTransaction:withMaxTransactionCount:completion:]"
- "-[FCWritablePrivateDataStorage writeReadHistoryItem:withCompletion:]"
- "-[FCWritablePrivateDataStorage writeSeenHistoryItems:withCompletion:]"
- "B16@?0@\"CacheManagementAsset\"8"
- "Client record field is missing from the schema: %@.%@"
- "Server record field is missing from the schema: %@.%@"
- "assetFromPath:withIdentifier:"
- "commit"
- "edgeCacheHintForToday"
- "enqueueTransaction:withMaxTransactionCount:completion:"
- "multi-source headlines operation requires a cached records lookup block whenever record source persistence is bypassed"
- "privateDataCleanupToV4Level2"
- "privateDataMigrateToV4Level2"
- "submitUpdate:withCompletion:"
- "v32@0:8@\"<FCReadingHistoryItem>\"16@?<v@?>24"
- "v32@0:8@\"NSArray\"16@?<v@?>24"
- "v40@0:8@16Q24@?32"
- "writeReadHistoryItem:withCompletion:"
- "writeSeenHistoryItems:withCompletion:"
```
