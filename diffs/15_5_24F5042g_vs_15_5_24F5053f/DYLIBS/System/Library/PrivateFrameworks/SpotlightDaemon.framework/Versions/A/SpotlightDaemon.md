## SpotlightDaemon

> `/System/Library/PrivateFrameworks/SpotlightDaemon.framework/Versions/A/SpotlightDaemon`

```diff

-2333.41.1.3.0
-  __TEXT.__text: 0xa5260
-  __TEXT.__auth_stubs: 0x1ba0
-  __TEXT.__objc_methlist: 0x3e1c
+2333.47.1.0.0
+  __TEXT.__text: 0xa6bdc
+  __TEXT.__auth_stubs: 0x1bc0
+  __TEXT.__objc_methlist: 0x3e7c
   __TEXT.__const: 0x350
-  __TEXT.__cstring: 0x7acd
-  __TEXT.__oslogstring: 0x8ad0
-  __TEXT.__gcc_except_tab: 0x3cd0
-  __TEXT.__unwind_info: 0x2018
+  __TEXT.__cstring: 0x798f
+  __TEXT.__oslogstring: 0x8cd6
+  __TEXT.__gcc_except_tab: 0x3d54
+  __TEXT.__unwind_info: 0x2040
   __TEXT.__objc_classname: 0x469
-  __TEXT.__objc_methname: 0xcd48
-  __TEXT.__objc_methtype: 0x21f3
-  __TEXT.__objc_stubs: 0xa6e0
-  __DATA_CONST.__got: 0x920
+  __TEXT.__objc_methname: 0xcfc2
+  __TEXT.__objc_methtype: 0x2269
+  __TEXT.__objc_stubs: 0xa7a0
+  __DATA_CONST.__got: 0x938
   __DATA_CONST.__const: 0x4a8
   __DATA_CONST.__objc_classlist: 0x150
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x30f0
+  __DATA_CONST.__objc_selrefs: 0x3138
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0xf8
   __DATA_CONST.__objc_arraydata: 0x390
-  __AUTH_CONST.__auth_got: 0xde8
-  __AUTH_CONST.__const: 0x4668
-  __AUTH_CONST.__cfstring: 0x6820
+  __AUTH_CONST.__auth_got: 0xdf8
+  __AUTH_CONST.__const: 0x4728
+  __AUTH_CONST.__cfstring: 0x6940
   __AUTH_CONST.__objc_const: 0x5320
   __AUTH_CONST.__objc_arrayobj: 0x2a0
   __AUTH_CONST.__objc_intobj: 0x120

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
-  Functions: 2646
-  Symbols:   5486
-  CStrings:  4349
+  Functions: 2667
+  Symbols:   5510
+  CStrings:  4382
 
Symbols:
+ -[SPConcreteCoreSpotlightIndexer _startInternalQueryWithIndex:query:fetchAttributes:forBundleIds:maxCount:resultsHandler:resultQueue:postFilter:clientBundleID:]
+ -[SPConcreteCoreSpotlightIndexer fetchMeCard:isNotCreateNewIndex:]
+ -[SPConcreteCoreSpotlightIndexer reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:completionValue:alwaysReindexWithCompletionAttribute:force:postFilter:]
+ -[SPConcreteCoreSpotlightIndexer revokeExpiredItems:activity:]
+ -[SPConcreteCoreSpotlightIndexer updateDerivedIsMe:]
+ -[SPConcreteCoreSpotlightIndexer updateDerivedIsMe:nameTokens:alias:onlyIfNotAlready:]
+ -[SPConcreteCoreSpotlightIndexer updateDerivedIsMeIfNotAlready:]
+ -[SPConcreteCoreSpotlightIndexer updateDerivedIsMeNot:nameTokens:alias:]
+ -[SPConcreteCoreSpotlightIndexer updateDerivedIsMeTextContentMatch:nameTokens:alias:onlyIfNotAlready:]
+ -[SPConcreteCoreSpotlightIndexer updateDerivedIsMeTextContentMatchNot:nameTokens:alias:]
+ -[SPConcreteCoreSpotlightIndexer updateMeCardInfo:middleName:familyName:emailAddresses:isFirstTimeCheck:isNotCreateNewIndex:]
+ -[SPCoreSpotlightIndexer revokeExpiredItems:activity:protected:]
+ GCC_except_table1008
+ GCC_except_table1013
+ GCC_except_table1018
+ GCC_except_table1023
+ GCC_except_table1029
+ GCC_except_table1046
+ GCC_except_table1094
+ GCC_except_table1096
+ GCC_except_table1101
+ GCC_except_table1142
+ GCC_except_table1148
+ GCC_except_table1314
+ GCC_except_table1317
+ GCC_except_table1318
+ GCC_except_table1319
+ GCC_except_table1451
+ GCC_except_table1480
+ GCC_except_table181
+ GCC_except_table185
+ GCC_except_table188
+ GCC_except_table192
+ GCC_except_table204
+ GCC_except_table206
+ GCC_except_table207
+ GCC_except_table219
+ GCC_except_table238
+ GCC_except_table251
+ GCC_except_table259
+ GCC_except_table293
+ GCC_except_table300
+ GCC_except_table312
+ GCC_except_table340
+ GCC_except_table363
+ GCC_except_table402
+ GCC_except_table403
+ GCC_except_table428
+ GCC_except_table444
+ GCC_except_table456
+ GCC_except_table459
+ GCC_except_table502
+ GCC_except_table511
+ GCC_except_table531
+ GCC_except_table546
+ GCC_except_table547
+ GCC_except_table600
+ GCC_except_table601
+ GCC_except_table602
+ GCC_except_table684
+ GCC_except_table705
+ GCC_except_table731
+ GCC_except_table735
+ GCC_except_table739
+ GCC_except_table770
+ GCC_except_table782
+ GCC_except_table793
+ GCC_except_table817
+ GCC_except_table818
+ GCC_except_table826
+ GCC_except_table867
+ GCC_except_table918
+ GCC_except_table954
+ GCC_except_table958
+ GCC_except_table959
+ GCC_except_table965
+ GCC_except_table967
+ GCC_except_table973
+ GCC_except_table986
+ GCC_except_table989
+ GCC_except_table999
+ _MDItemCardUnderName
+ _MDItemDerivedIsMe
+ _MDItemDerivedIsMeTextContentMatch
+ __196-[SPConcreteCoreSpotlightIndexer reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:completionValue:alwaysReindexWithCompletionAttribute:force:postFilter:]_block_invoke
+ __196-[SPConcreteCoreSpotlightIndexer reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:completionValue:alwaysReindexWithCompletionAttribute:force:postFilter:]_block_invoke_2
+ __196-[SPConcreteCoreSpotlightIndexer reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:completionValue:alwaysReindexWithCompletionAttribute:force:postFilter:]_block_invoke_4
+ __62-[SPConcreteCoreSpotlightIndexer revokeExpiredItems:activity:]_block_invoke
+ __SIGetMeNameTokens
+ __SISetDuplicateOidsCheckSuspendState
+ ___160-[SPConcreteCoreSpotlightIndexer _startInternalQueryWithIndex:query:fetchAttributes:forBundleIds:maxCount:resultsHandler:resultQueue:postFilter:clientBundleID:]_block_invoke
+ ___196-[SPConcreteCoreSpotlightIndexer reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:completionValue:alwaysReindexWithCompletionAttribute:force:postFilter:]_block_invoke
+ ___196-[SPConcreteCoreSpotlightIndexer reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:completionValue:alwaysReindexWithCompletionAttribute:force:postFilter:]_block_invoke_2
+ ___196-[SPConcreteCoreSpotlightIndexer reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:completionValue:alwaysReindexWithCompletionAttribute:force:postFilter:]_block_invoke_3
+ ___196-[SPConcreteCoreSpotlightIndexer reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:completionValue:alwaysReindexWithCompletionAttribute:force:postFilter:]_block_invoke_4
+ ___62-[SPConcreteCoreSpotlightIndexer revokeExpiredItems:activity:]_block_invoke
+ ___62-[SPConcreteCoreSpotlightIndexer revokeExpiredItems:activity:]_block_invoke_2
+ ___64-[SPCoreSpotlightIndexer revokeExpiredItems:activity:protected:]_block_invoke
+ ___64-[SPCoreSpotlightIndexer revokeExpiredItems:activity:protected:]_block_invoke_2
+ ___66-[SPConcreteCoreSpotlightIndexer fetchMeCard:isNotCreateNewIndex:]_block_invoke
+ ___90-[SPCoreSpotlightIndexer _issueCommand:outFileDescriptor:searchContext:completionHandler:]_block_invoke_19
+ ___block_descriptor_104_e8_32s40s48s56s64s72r80w_e69_v48?0"SPQueryJob"8q16Q24^{__MDStoreOIDArray=}32^{__MDPlistBytes=}40l
+ ___block_descriptor_40_e8_32w_e31_v16?0"BGRepeatingSystemTask"8l
+ ___block_descriptor_49_e8_32s40w_e18_v20?0^{__SI=}8C16l
+ ___block_descriptor_64_e8_32s40s48r56w_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48r56w_e69_v48?0"SPQueryJob"8q16Q24^{__MDStoreOIDArray=}32^{__MDPlistBytes=}40l
+ ___block_descriptor_90_e8_32s40s48r56r64r_e13_v24?0^8^B16l
+ ___block_descriptor_98_e8_32s40s48s56s64r_e69_v48?0"SPQueryJob"8q16Q24^{__MDStoreOIDArray=}32^{__MDPlistBytes=}40l
+ ___copy_helper_block_e8_32s40s48s56s64s72r80w
+ ___destroy_helper_block_e8_32s40s48s56s64s72r80w
+ _createEqualORQuery
+ _createNotEqualANDQuery
+ _objc_msgSend$_startInternalQueryWithIndex:query:fetchAttributes:forBundleIds:maxCount:resultsHandler:resultQueue:postFilter:clientBundleID:
+ _objc_msgSend$fetchMeCard:isNotCreateNewIndex:
+ _objc_msgSend$reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:completionValue:alwaysReindexWithCompletionAttribute:force:postFilter:
+ _objc_msgSend$revokeExpiredItems:activity:
+ _objc_msgSend$revokeExpiredItems:activity:protected:
+ _objc_msgSend$stringWithCapacity:
+ _objc_msgSend$updateDerivedIsMe:
+ _objc_msgSend$updateDerivedIsMe:nameTokens:alias:onlyIfNotAlready:
+ _objc_msgSend$updateDerivedIsMeIfNotAlready:
+ _objc_msgSend$updateDerivedIsMeNot:nameTokens:alias:
+ _objc_msgSend$updateDerivedIsMeTextContentMatch:nameTokens:alias:onlyIfNotAlready:
+ _objc_msgSend$updateDerivedIsMeTextContentMatchNot:nameTokens:alias:
+ _objc_msgSend$updateMeCardInfo:middleName:familyName:emailAddresses:isFirstTimeCheck:isNotCreateNewIndex:
- -[SPConcreteCoreSpotlightIndexer fetchMeCard:]
- -[SPConcreteCoreSpotlightIndexer revokeExpiredItems:]
- -[SPConcreteCoreSpotlightIndexer updateMeCardInfo:middleName:familyName:emailAddresses:isFirstTimeCheck:]
- -[SPCoreSpotlightIndexer revokeExpiredItems:protected:]
- GCC_except_table1003
- GCC_except_table1009
- GCC_except_table1026
- GCC_except_table1073
- GCC_except_table1075
- GCC_except_table1080
- GCC_except_table112
- GCC_except_table1121
- GCC_except_table1127
- GCC_except_table116
- GCC_except_table1293
- GCC_except_table1296
- GCC_except_table1297
- GCC_except_table1298
- GCC_except_table1428
- GCC_except_table1457
- GCC_except_table179
- GCC_except_table183
- GCC_except_table195
- GCC_except_table196
- GCC_except_table208
- GCC_except_table225
- GCC_except_table227
- GCC_except_table229
- GCC_except_table248
- GCC_except_table282
- GCC_except_table289
- GCC_except_table301
- GCC_except_table329
- GCC_except_table352
- GCC_except_table381
- GCC_except_table391
- GCC_except_table417
- GCC_except_table433
- GCC_except_table445
- GCC_except_table448
- GCC_except_table491
- GCC_except_table500
- GCC_except_table520
- GCC_except_table525
- GCC_except_table535
- GCC_except_table588
- GCC_except_table589
- GCC_except_table590
- GCC_except_table672
- GCC_except_table693
- GCC_except_table711
- GCC_except_table715
- GCC_except_table719
- GCC_except_table750
- GCC_except_table762
- GCC_except_table773
- GCC_except_table797
- GCC_except_table798
- GCC_except_table806
- GCC_except_table82
- GCC_except_table847
- GCC_except_table898
- GCC_except_table934
- GCC_except_table938
- GCC_except_table939
- GCC_except_table945
- GCC_except_table946
- GCC_except_table947
- GCC_except_table953
- GCC_except_table969
- GCC_except_table979
- GCC_except_table988
- GCC_except_table993
- GCC_except_table998
- __143-[SPConcreteCoreSpotlightIndexer reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:force:postFilter:]_block_invoke
- __143-[SPConcreteCoreSpotlightIndexer reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:force:postFilter:]_block_invoke_2
- __143-[SPConcreteCoreSpotlightIndexer reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:force:postFilter:]_block_invoke_4
- __53-[SPConcreteCoreSpotlightIndexer revokeExpiredItems:]_block_invoke
- __53-[SPConcreteCoreSpotlightIndexer revokeExpiredItems:]_block_invoke_2
- ___143-[SPConcreteCoreSpotlightIndexer reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:force:postFilter:]_block_invoke
- ___143-[SPConcreteCoreSpotlightIndexer reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:force:postFilter:]_block_invoke_2
- ___143-[SPConcreteCoreSpotlightIndexer reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:force:postFilter:]_block_invoke_3
- ___143-[SPConcreteCoreSpotlightIndexer reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:force:postFilter:]_block_invoke_4
- ___145-[SPConcreteCoreSpotlightIndexer _startInternalQueryWithIndex:query:fetchAttributes:forBundleIds:maxCount:resultsHandler:resultQueue:postFilter:]_block_invoke
- ___46-[SPConcreteCoreSpotlightIndexer fetchMeCard:]_block_invoke
- ___53-[SPConcreteCoreSpotlightIndexer revokeExpiredItems:]_block_invoke
- ___53-[SPConcreteCoreSpotlightIndexer revokeExpiredItems:]_block_invoke_2
- ___55-[SPCoreSpotlightIndexer revokeExpiredItems:protected:]_block_invoke
- ___55-[SPCoreSpotlightIndexer revokeExpiredItems:protected:]_block_invoke_2
- ___block_descriptor_48_e8_32s40w_e18_v20?0^{__SI=}8C16l
- ___block_descriptor_56_e8_32s40s48w_e5_v8?0l
- ___block_descriptor_80_e8_32s40s48s56w_e69_v48?0"SPQueryJob"8q16Q24^{__MDStoreOIDArray=}32^{__MDPlistBytes=}40l
- ___block_descriptor_88_e8_32s40s48r56r64r_e13_v24?0^8^B16l
- ___block_descriptor_96_e8_32s40s48s56s64r_e69_v48?0"SPQueryJob"8q16Q24^{__MDStoreOIDArray=}32^{__MDPlistBytes=}40l
- _objc_msgSend$fetchMeCard:
- _objc_msgSend$revokeExpiredItems:
- _objc_msgSend$revokeExpiredItems:protected:
- _objc_msgSend$updateDerivedFromToIsMeNameAdded:
- _objc_msgSend$updateDerivedFromToIsMeNameUpdated:
- _objc_msgSend$updateDerivedIsFromToMe:
- _objc_msgSend$updateMeCardInfo:middleName:familyName:emailAddresses:isFirstTimeCheck:
CStrings:
+ "%@ || %@"
+ "%@.%@"
+ "(%@ && (%@))"
+ "(%@ || %@)"
+ "(%@!=\"%@\"%@)"
+ "(%@=\"%@\"%@)"
+ "(%@=\"%@\")"
+ "((%@!=1) && (%@=\"%@\"))"
+ "((%@=1) && (%@!=\"%@\"))"
+ "((%@=1) && (%@=\"%@\"))"
+ "*warn* Name Tokens Array is nil"
+ "/Library/Metadata/CoreSpotlight/HistoricalReports"
+ "2333.47.1"
+ "B88@0:8^{__SI=}16@24@32@40Q48@?56@64@72@80"
+ "Marked BGST activity:%@ as defferred"
+ "Marked BGST activity:%@ as done"
+ "Marked XPC activity:%s as deferred"
+ "Performing BGST activity:%@"
+ "Registering BGST activity:%@"
+ "SPQueryFinished for activity:com.apple.searchd.expirations pc=%@"
+ "SPQueryResults deferred for activity:com.apple.searchd.expirations pc=%@"
+ "SPQueryResults for activity:com.apple.searchd.expirations pc=%@"
+ "XPC activity:com.apple.searchd.expirations not started pc=%@"
+ "XPC activity:com.apple.searchd.expirations starting ... pc=%@"
+ "_startInternalQueryWithIndex:query:fetchAttributes:forBundleIds:maxCount:resultsHandler:resultQueue:postFilter:clientBundleID:"
+ "cdw"
+ "com.apple.corespotlight.fixup"
+ "com.apple.searchd.duplicateOidCheck"
+ "com.apple.searchd.duplicateOidCheck.AB"
+ "fetchMeCard:isNotCreateNewIndex:"
+ "kSPDerivedIsMe"
+ "kSPDerivedIsMeNot"
+ "kSPDerivedIsMeTextContentMatch"
+ "kSPDerivedIsMeTextContentMatchNot"
+ "reindexAttributes:ofItemsMatchingQuery:indexAttrName:withVersion:perItemCompletionAttribute:completionValue:alwaysReindexWithCompletionAttribute:force:postFilter:"
+ "revokeExpiredItems:activity:"
+ "revokeExpiredItems:activity:protected:"
+ "stringWithCapacity:"
+ "updateDerivedIsMe"
+ "updateDerivedIsMe:"
+ "updateDerivedIsMe:nameTokens:alias:onlyIfNotAlready:"
+ "updateDerivedIsMeIfNotAlready"
+ "updateDerivedIsMeIfNotAlready:"
+ "updateDerivedIsMeNot:nameTokens:alias:"
+ "updateDerivedIsMeTextContentMatch:nameTokens:alias:onlyIfNotAlready:"
+ "updateDerivedIsMeTextContentMatchNot:nameTokens:alias:"
+ "updateMeCardInfo:middleName:familyName:emailAddresses:isFirstTimeCheck:isNotCreateNewIndex:"
+ "v36@0:8B16@20@28"
+ "v40@0:8B16@20@28B36"
+ "v56@0:8@16@24@32@40B48B52"
+ "v76@0:8@16@24@32Q40@48B56B60B64@68"
- "((%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\") || (%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\"))"
- "(((%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\") && %@ != \"*\") || ((%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\") && %@ != \"*\") || ((%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\") && %@ != \"*\"))"
- "(((%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\") && %@ != \"*\") || ((%@ = \"*\" ||%@ = \"*\" ||%@ = \"*\") && %@ != \"*\"))"
- "/Library/Spotlight/CoreSpotlight/HistoricalReports"
- "2333.41.1.3"
- "_kMDItemDerivedIsFromMe"
- "_kMDItemDerivedIsMe"
- "_kMDItemDerivedIsToMe"
- "fetchMeCard:"
- "kSPDerivedFromToIsMeNameAdded"
- "kSPDerivedFromToIsMeNameUpdated"
- "kSPDerivedFromToMeEmailAdded"
- "kSPDerivedFromToMeEmailUpdated"
- "revokeExpiredItems:"
- "revokeExpiredItems:protected:"
- "updateDerivedIsFromToMe"
- "updateMeCardInfo:middleName:familyName:emailAddresses:isFirstTimeCheck:"
- "v52@0:8@16@24@32@40B48"
```
