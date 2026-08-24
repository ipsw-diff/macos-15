## libmobileassetd.dylib

> `/usr/lib/libmobileassetd.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_protorefs`
- `__DATA.__objc_superrefs`
- `__DATA.__data`
- `__DATA.__s_async_hook`

```diff

-1487.120.62.0.0
-  __TEXT.__text: 0x2b835c
-  __TEXT.__auth_stubs: 0x2380
-  __TEXT.__objc_stubs: 0x22780
-  __TEXT.__objc_methlist: 0x10664
-  __TEXT.__const: 0x484e
-  __TEXT.__cstring: 0x37df6
-  __TEXT.__objc_methname: 0x3df0e
-  __TEXT.__objc_classname: 0xe88
-  __TEXT.__objc_methtype: 0x3ba1
-  __TEXT.__oslogstring: 0x4c6cd
-  __TEXT.__gcc_except_tab: 0x30d0
+1487.140.25.0.0
+  __TEXT.__text: 0x2b8b1c
+  __TEXT.__auth_stubs: 0x2390
+  __TEXT.__objc_stubs: 0x228e0
+  __TEXT.__objc_methlist: 0x1069c
+  __TEXT.__const: 0x476e
+  __TEXT.__cstring: 0x38126
+  __TEXT.__objc_methname: 0x3e0f0
+  __TEXT.__objc_classname: 0xea8
+  __TEXT.__objc_methtype: 0x3ba4
+  __TEXT.__oslogstring: 0x4ca1d
+  __TEXT.__gcc_except_tab: 0x30b0
   __TEXT.__swift5_typeref: 0x1093
   __TEXT.__constg_swiftt: 0x14fc
   __TEXT.__swift5_fieldmd: 0xfec

   __TEXT.__swift5_protos: 0x60
   __TEXT.__swift5_capture: 0x30
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x4838
+  __TEXT.__unwind_info: 0x4840
   __TEXT.__eh_frame: 0x332c
-  __DATA_CONST.__auth_got: 0x11d0
+  __DATA_CONST.__auth_got: 0x11d8
   __DATA_CONST.__got: 0x680
   __DATA_CONST.__auth_ptr: 0x968
-  __DATA_CONST.__const: 0x6930
-  __DATA_CONST.__cfstring: 0x2bac0
-  __DATA_CONST.__objc_classlist: 0x3f8
+  __DATA_CONST.__const: 0x6980
+  __DATA_CONST.__cfstring: 0x2bd20
+  __DATA_CONST.__objc_classlist: 0x400
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9930
+  __DATA_CONST.__objc_selrefs: 0x9960
   __DATA_CONST.__objc_intobj: 0x558
-  __DATA_CONST.__objc_arraydata: 0xb70
+  __DATA_CONST.__objc_arraydata: 0xbb8
   __DATA_CONST.__objc_arrayobj: 0x270
   __DATA_CONST.__objc_dictobj: 0xf0
-  __DATA.__objc_const: 0x15290
+  __DATA.__objc_const: 0x153b0
   __DATA.__objc_protorefs: 0x18
-  __DATA.__objc_classrefs: 0x7d8
+  __DATA.__objc_classrefs: 0x7e8
   __DATA.__objc_superrefs: 0x2f8
-  __DATA.__objc_ivar: 0x1400
-  __DATA.__objc_data: 0x2778
+  __DATA.__objc_ivar: 0x140c
+  __DATA.__objc_data: 0x27c8
   __DATA.__data: 0x26ca
   __DATA.__s_async_hook: 0x190
   __DATA.__swift56_hooks: 0xb0

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 8475
-  Symbols:   15223
-  CStrings:  16264
+  Functions: 8482
+  Symbols:   15254
+  CStrings:  16305
 
Symbols:
+ +[DownloadManager addNWActivityToDownloadInfo:andTask:andLabel:withOptions:]
+ +[MADAutoAssetControlManager preferenceForceStartupHealthReport]
+ +[MADAutoAssetControlManager preferenceHealthReportAdditionalSetNames]
+ +[MADAutoAssetPersisted isConsideredMatchWithoutVersion:ofEntryFullEntryIDName:toSelectorPersistedEntryID:]
+ +[MAThirdPartyCompatibilityDaemon _sanitizedURLPathComponentFor:]
+ +[MAThirdPartyCompatibilityDaemon isThirdPartyAssetType:]
+ +[MAThirdPartyCompatibilityDaemon thirdPartyServerURLForAssetType:]
+ -[MADAutoAssetControlManager locatePersistedKnownDescriptorEntryIDs:forAssetType:]
+ -[MADAutoAssetControlManager preferenceForceStartupHealthReport]
+ -[MADAutoAssetControlManager preferenceHealthReportAdditionalSetNames]
+ -[MADAutoAssetControlManager setPreferenceForceStartupHealthReport:]
+ -[MADAutoAssetSetHealthReport latestInstanceFromPreSUStaging]
+ -[MADAutoAssetSetHealthReport setLatestInstanceFromPreSUStaging:]
+ GCC_except_table32
+ GCC_except_table635
+ GCC_except_table639
+ GCC_except_table645
+ GCC_except_table661
+ GCC_except_table800
+ GCC_except_table99
+ OBJC_IVAR_$_MADAutoAssetControlManager._preferenceForceStartupHealthReport
+ OBJC_IVAR_$_MADAutoAssetControlManager._preferenceHealthReportAdditionalSetNames
+ OBJC_IVAR_$_MADAutoAssetSetHealthReport._latestInstanceFromPreSUStaging
+ _Constants
+ _InvShiftRows_RotWord
+ _OBJC_CLASS_$_MAThirdPartyCompatibilityDaemon
+ _OBJC_CLASS_$_NSRegularExpression
+ _OBJC_METACLASS_$_MAThirdPartyCompatibilityDaemon
+ _S_Box_Inverse_Zero
+ __MAPreferencesCopyArrayOfStrings
+ __MAPreferencesCopyNSArrayOfStringsValue
+ __OBJC_$_CLASS_METHODS_MAThirdPartyCompatibilityDaemon
+ __OBJC_CLASS_RO_$_MAThirdPartyCompatibilityDaemon
+ __OBJC_METACLASS_RO_$_MAThirdPartyCompatibilityDaemon
+ ___block_descriptor_97_e8_32s40s48s56s64s72s80r88r_e5_v8?0l
+ ___copy_helper_block_e8_32s40s48s56s64s72s80r88r
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80r88r
+ _downloadTypeForTaskDescriptor
+ _isDisallowedFromContentCaching
+ _kMobileAssetPreferencesAutoHealthReportSetNames
+ _kMobileAssetPreferencesAutoStartupHealthReport
+ _kMobileAssetPreferencesThirdPartyStagingBucketPathComponent
+ _kMobileAssetPreferencesThirdPartyStagingPathComponent
+ _kSecAttrAccessibleAlwaysThisDeviceOnlyPrivate
+ _nw_activity_submit_metrics
+ _objc_msgSend$_sanitizedURLPathComponentFor:
+ _objc_msgSend$addCharactersInString:
+ _objc_msgSend$addNWActivityToDownloadInfo:andTask:andLabel:withOptions:
+ _objc_msgSend$alphanumericCharacterSet
+ _objc_msgSend$compatibilityVersionStringForAssetType:
+ _objc_msgSend$isBootedOSSecureInternal
+ _objc_msgSend$isConsideredMatchWithoutVersion:ofEntryFullEntryIDName:toSelectorPersistedEntryID:
+ _objc_msgSend$latestInstanceFromPreSUStaging
+ _objc_msgSend$locatePersistedKnownDescriptorEntryIDs:forAssetType:
+ _objc_msgSend$precomposedStringWithCanonicalMapping
+ _objc_msgSend$preferenceForceStartupHealthReport
+ _objc_msgSend$preferenceHealthReportAdditionalSetNames
+ _objc_msgSend$regularExpressionWithPattern:options:error:
+ _objc_msgSend$setLatestInstanceFromPreSUStaging:
+ _objc_msgSend$stringByReplacingMatchesInString:options:range:withTemplate:
+ _objc_msgSend$thirdPartyServerURLForAssetType:
+ _simplifySetIdentifier
+ ccaes_arm_encrypt_key128
+ ccaes_arm_encrypt_key192
+ ccaes_arm_encrypt_key256
- +[DownloadManager addNWActivityToDownloadInfo:andTask:andLabel:]
- +[MADAutoAssetStager controlForcePurge:]
- +[MADAutoAssetStager persistedStagedCount]
- -[MADAutoAssetControlManager newSetDescriptorLimitedToLockInformation:forSetConfiguration:]
- -[MADAutoAssetControlManager verifySetLookupResultPreferringDownloaded:]
- -[MADAutoAssetStager _setConfigurationHasEntriesWhenTargeting:]
- -[MADAutoAssetStager _targetNameLookupResults:]
- -[MADAutoAssetStager action_EliminateDoneDecideMoreCandidates:error:]
- -[MADAutoAssetStager action_ResumingNextAvailableBeginDownload:error:]
- -[MADAutoAssetStager newTargetLookupResultsForTargetTrainName:forTargetRestoreVersion:]
- GCC_except_table27
- GCC_except_table637
- GCC_except_table641
- GCC_except_table649
- GCC_except_table663
- GCC_except_table67
- GCC_except_table799
- GCC_except_table97
- _AESSubBytesWordTable
- ___42+[MADAutoAssetStager persistedStagedCount]_block_invoke
- _ccaes_arm_decrypt_key128
- _ccaes_arm_decrypt_key192
- _ccaes_arm_decrypt_key256
- _ccaes_arm_encrypt_key128
- _ccaes_arm_encrypt_key192
- _ccaes_arm_encrypt_key256
- _kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly
- _objc_msgSend$action_EliminateDoneDecideMoreCandidates:error:
- _objc_msgSend$action_ResumingNextAvailableBeginDownload:error:
- _objc_msgSend$addNWActivityToDownloadInfo:andTask:andLabel:
- _objc_msgSend$defaultThirdPartyServerURLForAssetType:
- _objc_msgSend$initWithAssetType:
- aes_dkey_expansion
- aes_key_expansion
CStrings:
+ "%@:locatePersistedKnownDescriptorEntryIDs"
+ "%@:newAtomicInstanceAndSetDescriptorFromStaged"
+ "%{public}@\n[AUTO-STAGER] {AddToStagedDecideMoreAvailable} asset-descriptor ALREADY-DOWNLOADED | self.activeJobDescriptor:%{public}@"
+ "%{public}@\n[AUTO-STAGER] {AddToStaged} [BY-GROUP-MODE] asset-descriptor ALREADY-DOWNLOADED | self.activeJobDescriptor:%{public}@"
+ "%{public}@ | MISSING asset-version | entryName:%{public}@"
+ "%{public}@ | MISSING param | entryName:%{public}@ | selectorPersistedEntryID:%{public}@"
+ "%{public}@ | corrupted current-entry-IDs | %{public}@"
+ "%{public}@ | invalid asset-selector (no asset-specifier) | assetSelector:%{public}@"
+ "%{public}@ | invalid asset-selector (no asset-type) | assetSelector:%{public}@"
+ "%{public}@ | invalid regex | regexError:%{public}@"
+ "%{public}@ | nil regex (no regexError)"
+ "%{public}@ | unable to form persisted-entry-ID | assetSelector:%{public}@"
+ "-_"
+ "2.5.1"
+ "2.6.2"
+ "AutoHealthReportSets"
+ "AutoStartupHealthReport"
+ "GlowGSeed"
+ "MAThirdPartyCompatibility: %@ override (%@) provided, with illegal characters."
+ "MAThirdPartyCompatibilityDaemon"
+ "Metrics"
+ "PSUS"
+ "Replacing"
+ "Setting"
+ "Starting built-in MobileAsset brain built Jun  3 2025 08:37:41"
+ "Starting downloaded MobileAsset brain (version: %@) built Jun  3 2025 08:37:41"
+ "T@\"NSArray\",R,&,N,V_preferenceHealthReportAdditionalSetNames"
+ "TB,N,V_preferenceForceStartupHealthReport"
+ "TB,V_latestInstanceFromPreSUStaging"
+ "ThirdPartyStagingBucketPathComponent"
+ "ThirdPartyStagingPathComponent"
+ "[%{public}@] {%{public}@} responding to client with error | responseMessage:%{public}@, responseError:%{public}@"
+ "[AUTO-SHORT-TERM][LATEST]{trackShortTermLockedSetDescriptor} %{public}@ latest supporting SHORT-TERM locking | atomicInstance:%{public}@ | setDescriptor:%{public}@"
+ "[MA_PREFS] {_MAPreferencesCopyArrayOfStrings} invalid entry for key:%{public}@ | value:%{public}@ | index:%d | not a string"
+ "[MA_PREFS] {_MAPreferencesCopyNSArrayOfStringsValue} invalid type for key:%{public}@ | expecting array of strings"
+ "_[0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+\\.[0-9]+_[0-9]+$"
+ "_latestInstanceFromPreSUStaging"
+ "_preferenceForceStartupHealthReport"
+ "_preferenceHealthReportAdditionalSetNames"
+ "_sanitizedURLPathComponentFor:"
+ "addCharactersInString:"
+ "addNWActivityToDownloadInfo:andTask:andLabel:withOptions:"
+ "alphanumericCharacterSet"
+ "com.apple.MobileAsset.UAF.FM.CodeLM"
+ "com.apple.MobileAsset.UAF.FM.GenerativeModels"
+ "com.apple.MobileAsset.UAF.Handwriting.Synthesis"
+ "com.apple.MobileAsset.UAF.IF.Planner"
+ "com.apple.MobileAsset.UAF.Search.ODLA"
+ "com.apple.MobileAsset.UAF.Speech.AutomaticSpeechRecognition"
+ "com.apple.MobileAsset.UAF.VoiceAssistant"
+ "compatibilityVersionStringForAssetType:"
+ "https://mesu.apple.com/3p/%@/%@/assets/%@/%@/"
+ "https://mesu.apple.com/3p/%@/assets/%@/%@/"
+ "https://mesu.apple.com/3p/assets/%@/%@/"
+ "https://mesu.apple.com/3p/staging/assets/%@/%@/"
+ "isBootedOSSecureInternal"
+ "isConsideredMatchWithoutVersion:ofEntryFullEntryIDName:toSelectorPersistedEntryID:"
+ "latestInstanceFromPreSUStaging"
+ "locatePersistedKnownDescriptorEntryIDs:forAssetType:"
+ "macos"
+ "precomposedStringWithCanonicalMapping"
+ "preferenceForceStartupHealthReport"
+ "preferenceHealthReportAdditionalSetNames"
+ "rampForeground:%@, discretionary:%@, timeout:%@, allowSame:%@, allowContentCaching:%@ | [installed] build:%@, version:%@ | analyticsData:%@"
+ "regularExpressionWithPattern:options:error:"
+ "set-identifier (for given client-domain-name) is not currently defined | clientDomainName:%@ | assetSetIdentifier:%@"
+ "setLatestInstanceFromPreSUStaging:"
+ "setPreferenceForceStartupHealthReport:"
+ "stringByReplacingMatchesInString:options:range:withTemplate:"
+ "thirdPartyServerURLForAssetType:"
+ "v44@0:8@16@24I32@36"
+ "{%@:newAtomicInstanceAndSetDescriptorFromStaged} unable to allocate already-downloaded-atomic-entry | alreadyDownloadedDescriptor:%@"
+ "{%@} unable to determine localContentURL of already-downloaded-descriptor | alreadyDownloadedDescriptor:%@"
+ "{%{public}@} [%{public}@] | fromLookupResultSetDescriptor:%{public}@ | reportedDiscoveredEntries:\n%{public}@"
+ "{%{public}@} [DROP-SET-DESCRIPTOR] set-descriptor with downloaded entry missing from filesystem | entry:%ld-of-%ld | nextDownloadedEntry:%{public}@ | localContentURL:%{public}@ | setDescriptor:%{public}@"
+ "{%{public}@} [DROP-SET-DESCRIPTOR] set-descriptor with downloaded entry missing localContentURL | entry:%ld-of-%ld | nextDownloadedEntry:%{public}@ | setDescriptor:%{public}@"
+ "{%{public}@} [DROP-SET-DESCRIPTOR] set-descriptor with downloaded entry that is not a directory | entry:%ld-of-%ld | nextDownloadedEntry:%{public}@ | localContentURL:%{public}@ | setDescriptor:%{public}@"
+ "{%{public}@} [KEEP-SET-DESCRIPTOR] set-descriptor with downloaded entry on filesystem | entry:%ld-of-%ld | nextDownloadedEntry:%{public}@ | localContentURL:%{public}@ | setDescriptor:%{public}@"
+ "{%{public}@} no auto-asset-descriptor entry found | entry:%{public}@"
+ "{%{public}@} no persisted-entry found | assetSelector:%{public}@"
+ "{%{public}@} no persisted-entry found | entry:%{public}@"
+ "{%{public}@} unable to load known descriptor | entry:%{public}@"
+ "{%{public}@} unable to load persisted-state entry | entry:%{public}@"
+ "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | by-set-configuration lookup-cache disabled | set-configuration:%{public}@ | assetAudience:%{public}@ | setAssetType:%{public}@"
+ "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | cached entry config mismatch | removed entry | set-configuration:%{public}@ | assetAudience:%{public}@ | setAssetType:%{public}@"
+ "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | cached secs(%ld) <= max-valid secs(%ld) | using entry | set-configuration:%{public}@ | assetAudience:%{public}@ | setAssetType:%{public}@"
+ "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | cached secs(%ld) > max-valid secs(%ld) | removed entry | set-configuration:%{public}@ | assetAudience:%{public}@ | setAssetType:%{public}@"
+ "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | current time before cached entry time - removed future entry | set-configuration:%{public}@ | assetAudience:%{public}@ | setAssetType:%{public}@"
+ "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | no cached entry | set-configuration:%{public}@ | assetAudience:%{public}@ | setAssetType:%{public}@"
+ "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | unable to determine by-set-configuration lookup-cache key (no asset-type from set-configuration) | setConfiguration:%{public}@ | setAssetType:%{public}@"
+ "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | unable to determine by-set-configuration lookup-cache key | setConfiguration:%{public}@ | setAssetType:%{public}@ | assetAudience:%{public}@ | setAssetType:%{public}@"
+ "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | unable to determine timestamp(s) | removed entry | set-configuration:%{public}@ | assetAudience:%{public}@ | setAssetType:%{public}@"
+ "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | unable to locate auto-asset-lookup-cache | set-configuration:%{public}@ | setAssetType:%{public}@"
- "%{public}@\n[AUTO-STAGER] {newTargetLookupResultsForTargetTrainName} unable to retrieve target-lookup-results | entryID:%{public}@"
- "2.5.0"
- "2.6.1"
- "EliminateDoneDecideMoreCandidates"
- "GlowF"
- "LOOKUP_RESULTS"
- "ResumingNextAvailableBeginDownload"
- "Starting built-in MobileAsset brain built Apr 19 2025 01:26:20"
- "Starting downloaded MobileAsset brain (version: %@) built Apr 19 2025 01:26:20"
- "[%{public}@]\n{verifySetLookupResultPreferringDownloaded} replaced stager set-lookup-result | staged-assetID:%{public}@ | downloaded-assetID:%{public}@"
- "[%{public}@]\n{verifySetLookupResultPreferringDownloaded} stager set-lookup-result with no downloaded descriptor (dropped) | nextDiscoveredEntry:%{public}@"
- "[%{public}@]\n{verifySetLookupResultPreferringDownloaded} unable to allocate replacement entry | staged-assetID:%{public}@ | downloaded-assetID:%{public}@"
- "[%{public}@] {newTargetLookupResultsForTargetTrainName} unable to load target-lookup-results | entryID:%{public}@"
- "[AUTO-ASSET] [LOCAL-CONTENT-URL] {verifySetLookupResultPreferringDownloaded} not adopting set-lookup-result - %{public}@"
- "[AUTO-SHORT-TERM][LATEST]{trackShortTermLockedSetDescriptor} latest supporting SHORT-TERM locking | atomicInstance:%{public}@ | setDescriptor:%{public}@"
- "_setConfigurationHasEntriesWhenTargeting:"
- "_targetNameLookupResults:"
- "action_EliminateDoneDecideMoreCandidates:error:"
- "action_ResumingNextAvailableBeginDownload:error:"
- "addNWActivityToDownloadInfo:andTask:andLabel:"
- "controlForcePurge:"
- "defaultThirdPartyServerURLForAssetType:"
- "newSetDescriptorLimitedToLockInformation:forSetConfiguration:"
- "newTargetLookupResultsForTargetTrainName"
- "newTargetLookupResultsForTargetTrainName:forTargetRestoreVersion:"
- "persistedStagedCount"
- "rampForeground:%@, discretionary:%@, timeout:%@, allowSame:%@ | [installed] build:%@, version:%@ | analyticsData:%@"
- "set-identifier (for given client-domain-name) is not currently defined"
- "unable to get local content URL | downloadedDescriptor:%@"
- "v36@0:8@16@24I32"
- "verifySetLookupResultPreferringDownloaded"
- "verifySetLookupResultPreferringDownloaded:"
- "{%@} no auto-asset-descriptor entry found | entry:%{public}@"
- "{%@} no persisted-entry found | assetSelector:%{public}@"
- "{%@} no persisted-entry found | entry:%{public}@"
- "{%{public}@} [DROP-SET-DESCRIPTOR] set-descriptor with downloaded entry missing from filesystem | entry:%ld-of-%ld | nextDownloadedEntry:%{public}@ | localContentURL:%{public}@"
- "{%{public}@} [DROP-SET-DESCRIPTOR] set-descriptor with downloaded entry missing localContentURL | entry:%ld-of-%ld | nextDownloadedEntry:%{public}@"
- "{%{public}@} [DROP-SET-DESCRIPTOR] set-descriptor with downloaded entry that is not a directory | entry:%ld-of-%ld | nextDownloadedEntry:%{public}@ | localContentURL:%{public}@"
- "{%{public}@} [KEEP-SET-DESCRIPTOR] set-descriptor with downloaded entry on filesystem | entry:%ld-of-%ld | nextDownloadedEntry:%{public}@ | localContentURL:%{public}@"
- "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | by-set-configuration lookup-cache disabled | set-configuration:%{public}@ | assetAudience:%{public}@"
- "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | cached entry config mismatch | removed entry | set-configuration:%{public}@ | assetAudience:%{public}@"
- "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | cached secs(%ld) <= max-valid secs(%ld) | using entry | set-configuration:%{public}@ | assetAudience:%{public}@"
- "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | cached secs(%ld) > max-valid secs(%ld) | removed entry | set-configuration:%{public}@ | assetAudience:%{public}@"
- "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | current time before cached entry time - removed future entry | set-configuration:%{public}@ | assetAudience:%{public}@"
- "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | no cached entry | set-configuration:%{public}@ | assetAudience:%{public}@"
- "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | unable to determine by-set-configuration lookup-cache key (no asset-type from set-configuration) | setConfiguration:%{public}@"
- "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | unable to determine by-set-configuration lookup-cache key | setConfiguration:%{public}@ | setAssetType:%{public}@ | assetAudience:%{public}@"
- "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | unable to determine timestamp(s) | removed entry | set-configuration:%{public}@ | assetAudience:%{public}@"
- "{AUTO-LOOKUP-CACHE[%{public}@]:cachedLookupResultForSetConfiguration} | unable to locate auto-asset-lookup-cache | set-configuration:%{public}@"
- "{AUTO-STAGER:persistedStagedCount} | unable to determine previous staging information from persisted-state (no auto-asset-stager)"
- "{_setConfigurationHasEntriesWhenTargeting} no auto-asset-entries for set-configuration:%@"
- "{controlForcePurge} failed to locate shared AutoAssetStager"
```
