## NewsCore

> `/System/Library/PrivateFrameworks/NewsCore.framework/Versions/A/NewsCore`

```diff

-5680.0.0.0.0
-  __TEXT.__text: 0x3f3e30
-  __TEXT.__auth_stubs: 0x3280
-  __TEXT.__objc_methlist: 0x32f94
-  __TEXT.__const: 0x7088
-  __TEXT.__swift5_typeref: 0x2a60
-  __TEXT.__constg_swiftt: 0x1eb4
-  __TEXT.__swift5_reflstr: 0x13e0
-  __TEXT.__swift5_fieldmd: 0x19ac
+5681.0.0.0.0
+  __TEXT.__text: 0x3f8430
+  __TEXT.__auth_stubs: 0x32e0
+  __TEXT.__objc_methlist: 0x33044
+  __TEXT.__const: 0x7108
+  __TEXT.__swift5_typeref: 0x2b1a
+  __TEXT.__constg_swiftt: 0x1f1c
+  __TEXT.__swift5_reflstr: 0x1450
+  __TEXT.__swift5_fieldmd: 0x1a2c
   __TEXT.__swift5_proto: 0x554
-  __TEXT.__swift5_types: 0x25c
-  __TEXT.__cstring: 0x55f82
+  __TEXT.__swift5_types: 0x268
+  __TEXT.__cstring: 0x561c1
   __TEXT.__swift5_capture: 0x8ac
   __TEXT.__swift5_builtin: 0x118
   __TEXT.__swift5_protos: 0x4c
   __TEXT.__swift5_assocty: 0x310
-  __TEXT.__swift_as_entry: 0x228
-  __TEXT.__swift_as_ret: 0x2a4
-  __TEXT.__oslogstring: 0x155ce
+  __TEXT.__swift_as_entry: 0x22c
+  __TEXT.__swift_as_ret: 0x2ac
+  __TEXT.__oslogstring: 0x1573e
   __TEXT.__swift5_mpenum: 0x4c
-  __TEXT.__gcc_except_tab: 0x5464
+  __TEXT.__gcc_except_tab: 0x5484
   __TEXT.__dlopen_cstrs: 0x11c
   __TEXT.__ustring: 0x27a
-  __TEXT.__unwind_info: 0xd300
-  __TEXT.__eh_frame: 0x72f0
-  __TEXT.__objc_classname: 0x74f3
-  __TEXT.__objc_methname: 0x83c01
-  __TEXT.__objc_methtype: 0xc7c4
-  __TEXT.__objc_stubs: 0x34700
-  __DATA_CONST.__got: 0x29b0
-  __DATA_CONST.__const: 0x6b80
-  __DATA_CONST.__objc_classlist: 0x1bd0
+  __TEXT.__unwind_info: 0xd3d8
+  __TEXT.__eh_frame: 0x74f8
+  __TEXT.__objc_classname: 0x74d9
+  __TEXT.__objc_methname: 0x83ce8
+  __TEXT.__objc_methtype: 0xc786
+  __TEXT.__objc_stubs: 0x347c0
+  __DATA_CONST.__got: 0x29b8
+  __DATA_CONST.__const: 0x6bb8
+  __DATA_CONST.__objc_classlist: 0x1bd8
   __DATA_CONST.__objc_catlist: 0x2a8
   __DATA_CONST.__objc_protolist: 0x880
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x14150
+  __DATA_CONST.__objc_selrefs: 0x141a0
   __DATA_CONST.__objc_protorefs: 0x1e0
   __DATA_CONST.__objc_superrefs: 0x1558
   __DATA_CONST.__objc_arraydata: 0x1d38
-  __AUTH_CONST.__auth_got: 0x1958
-  __AUTH_CONST.__const: 0x153c0
-  __AUTH_CONST.__cfstring: 0x30340
-  __AUTH_CONST.__objc_const: 0x744f0
+  __AUTH_CONST.__auth_got: 0x1988
+  __AUTH_CONST.__const: 0x153c8
+  __AUTH_CONST.__cfstring: 0x30420
+  __AUTH_CONST.__objc_const: 0x745d8
   __AUTH_CONST.__objc_arrayobj: 0x540
   __AUTH_CONST.__objc_intobj: 0x13c8
   __AUTH_CONST.__objc_dictobj: 0xbe0
   __AUTH_CONST.__objc_doubleobj: 0x120
-  __AUTH.__objc_data: 0xa4c8
-  __AUTH.__data: 0x1378
-  __DATA.__objc_ivar: 0x52b8
-  __DATA.__data: 0x7078
-  __DATA.__bss: 0xbf58
-  __DATA.__common: 0x280
-  __DATA_DIRTY.__objc_data: 0x7120
+  __AUTH.__objc_data: 0xa648
+  __AUTH.__data: 0x13f0
+  __DATA.__objc_ivar: 0x52b4
+  __DATA.__data: 0x7098
+  __DATA.__bss: 0xbf68
+  __DATA.__common: 0x288
+  __DATA_DIRTY.__objc_data: 0x70d0
   __DATA_DIRTY.__common: 0x100
   __DATA_DIRTY.__bss: 0x38
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 22643
-  Symbols:   43119
-  CStrings:  28252
+  Functions: 22702
+  Symbols:   43148
+  CStrings:  28273
 
Symbols:
+ +[FCFeedContext feedContextForSmarterFetch]
+ -[FCFeedDatabase lookupFeedItemsForFeedID:feedRange:completion:]
+ -[FCFeedDatabase saveFeedItems:feedID:feedRange:]
+ -[FCFeedRange clampOrder:]
+ -[FCNewsAppConfig isSmarterFetchEnabledForESL]
+ -[FCNewsAppConfig isSmarterFetchEnabledForLatest]
+ -[FCNewsAppConfig smarterFetchStrategy]
+ -[NTPBSmarterFetchRequest(FCAdditions) initWithUserInfo:personalizationParams:tagsFollowed:mutedTagIDs:fetchRecordSpecs:fetchSource:fetchStrategy:fromDate:toDate:]
+ GCC_except_table37
+ _FCCKFeedItemSurfacedByArticleListIDsKey
+ _FCCKFeedItemSurfacedByChannelIDKey
+ _FCCKFeedItemSurfacedBySectionIDKey
+ _FCCKFeedItemSurfacedByTopicIDKey
+ _FCTodayFeedSmarterFetchForESLSharedPreferenceKey
+ _FCTodayFeedSmarterFetchForLatestSharedPreferenceKey
+ _OBJC_CLASS_$_FCSmarterFetchConstants
+ _OBJC_CLASS_$_FCThrottleRegistry
+ _OBJC_METACLASS_$_FCSmarterFetchConstants
+ _OBJC_METACLASS_$_FCThrottleRegistry
+ __CLASS_METHODS_FCSmarterFetchConstants
+ __CLASS_METHODS_FCThrottleRegistry
+ __CLASS_PROPERTIES_FCSmarterFetchConstants
+ __CLASS_PROPERTIES_FCThrottleRegistry
+ __DATA_FCSmarterFetchConstants
+ __DATA_FCThrottleRegistry
+ __INSTANCE_METHODS_FCSmarterFetchConstants
+ __INSTANCE_METHODS_FCThrottleRegistry
+ __IVARS_FCThrottleRegistry
+ __METACLASS_DATA_FCSmarterFetchConstants
+ __METACLASS_DATA_FCThrottleRegistry
+ ___49-[FCFeedDatabase saveFeedItems:feedID:feedRange:]_block_invoke
+ ___64-[FCFeedDatabase lookupFeedItemsForFeedID:feedRange:completion:]_block_invoke
+ ___64-[FCFeedDatabase lookupFeedItemsForFeedID:feedRange:completion:]_block_invoke_2
+ _objc_msgSend$maxOrder
+ _objc_msgSend$minOrder
+ _objc_msgSend$setMutedTagIds:
+ _objc_msgSend$shared
+ _objc_msgSend$shouldThrottleGroup:outRetryAfter:
+ _objc_msgSend$throttleGroup:retryAfter:
+ _swift_continuation_resume
+ _symbolic SccySaySo12NTPBFeedItemCG_SaySo11FCFeedRangeCGt_____G s5NeverO
+ _symbolic So14FCFeedDatabaseC
+ _symbolic So14NSUserDefaultsC
+ _symbolic _____ 8NewsCore16ThrottleRegistryC
+ _symbolic _____ 8NewsCore21SmarterFetchConstantsC
+ _symbolic _____ySS_So13FCFeedContextCtG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s11_SetStorageC s6UInt64V
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s6UInt64V
+ _symbolic _____yytG 2os21OSAllocatedUnfairLockV
+ _symbolic _____yyt_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic ypSg
- +[FCFeedTransformationClamp transformationWithDateRange:]
- +[FCFeedTransformationClamp transformationWithFeedRange:]
- -[FCFeedTransformationClamp .cxx_destruct]
- -[FCFeedTransformationClamp feedRange]
- -[FCFeedTransformationClamp setFeedRange:]
- -[FCFeedTransformationClamp transformFeedItems:]
- -[FCOperation _userDefaultsKeyForThrottleEndDate]
- -[NTPBSmarterFetchRequest(FCAdditions) initWithUserInfo:personalizationParams:tagsFollowed:fetchRecordSpecs:fetchSource:fetchStrategy:fromDate:toDate:]
- OBJC_IVAR_$_FCFeedTransformationClamp._feedRange
- _FCTodayFeedSmarterFetchSharedPreferenceKey
- _OBJC_CLASS_$_FCFeedTransformationClamp
- _OBJC_METACLASS_$_FCFeedTransformationClamp
- __48-[FCOperation _handleThrottlingFromError:delay:]_block_invoke
- __OBJC_$_CLASS_METHODS_FCFeedTransformationClamp
- __OBJC_$_INSTANCE_METHODS_FCFeedTransformationClamp
- __OBJC_$_INSTANCE_VARIABLES_FCFeedTransformationClamp
- __OBJC_$_PROP_LIST_FCFeedTransformationClamp
- __OBJC_CLASS_PROTOCOLS_$_FCFeedTransformationClamp
- __OBJC_CLASS_RO_$_FCFeedTransformationClamp
- __OBJC_METACLASS_RO_$_FCFeedTransformationClamp
- ___48-[FCFeedTransformationClamp transformFeedItems:]_block_invoke
- ___48-[FCOperation _handleThrottlingFromError:delay:]_block_invoke
CStrings:
+ "-[FCOperation _handleThrottlingFromError:delay:]_block_invoke"
+ "FCOperationThrottling:"
+ "FCSmarterFetchConstants"
+ "FCThrottleRegistry"
+ "NewsCore/ThrottleRegistry.swift"
+ "T@\"FCFeedContext\",R,N"
+ "T@\"FCFeedDatabase\",R,N"
+ "T@\"FCFeedDatabase\",R,N,V_feedDatabase"
+ "T@\"FCThrottleRegistry\",N,R"
+ "appConfigManager"
+ "clampOrder:"
+ "feedContextForSmarterFetch"
+ "feedIDForLatest"
+ "finished with just the contents of the cache, id=%{public}s"
+ "initWithDomain:code:userInfo:"
+ "initWithUserInfo:personalizationParams:tagsFollowed:mutedTagIDs:fetchRecordSpecs:fetchSource:fetchStrategy:fromDate:toDate:"
+ "isSmarterFetchEnabledForESL"
+ "isSmarterFetchEnabledForLatest"
+ "lookupFeedItemsForFeedID:feedRange:completion:"
+ "maxRetryAfter"
+ "news.today_feed_pool.smarter_fetch_for_esl"
+ "news.today_feed_pool.smarter_fetch_for_latest"
+ "received Smarter Fetch response, time=%{public}lldms, id=%{public}s, headers=%{public}s"
+ "retrieved %{public}ld feed items from the cache, missingRanges=%{public}ld, id=%{public}s"
+ "saveFeedItems:feedID:feedRange:"
+ "saved %{public}ld feed items to the cache, id=%{public}s"
+ "setMutedTagIds:"
+ "shared"
+ "shouldThrottleGroup:outRetryAfter:"
+ "smarter_fetch:latest"
+ "throttleGroup:retryAfter:"
+ "userDefaults"
+ "will fetch My Articles from Smarter Fetch, range=%{public}@, id=%{public}s"
+ "will fetch from range=%{public}@, id=%{public}s"
- "-[FCOperation _handleThrottlingFromError:delay:]"
- "@\"<FCFeedDatabaseProtocol>\""
- "@\"<FCFeedDatabaseProtocol>\"16@0:8"
- "FCFeedTransformationClamp"
- "FCOperationThrottling:%@"
- "T@\"<FCFeedDatabaseProtocol>\",R,N"
- "T@\"<FCFeedDatabaseProtocol>\",R,N,V_feedDatabase"
- "T@\"FCFeedRange\",&,N,V_feedRange"
- "initWithUserInfo:personalizationParams:tagsFollowed:fetchRecordSpecs:fetchSource:fetchStrategy:fromDate:toDate:"
- "news.today_feed_pool.smarter_fetch"
- "received Smarter Fetch response, time=%{public}lldms, id=%{public}s"
- "transformationWithDateRange:"
- "transformationWithFeedRange:"
```
