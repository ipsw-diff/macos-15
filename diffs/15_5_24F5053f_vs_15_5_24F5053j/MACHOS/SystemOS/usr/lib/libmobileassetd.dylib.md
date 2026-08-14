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
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_protorefs`
- `__DATA.__objc_classrefs`
- `__DATA.__objc_superrefs`
- `__DATA.__objc_data`
- `__DATA.__data`
- `__DATA.__s_async_hook`

```diff

-1487.120.52.0.0
-  __TEXT.__text: 0x2b6840
-  __TEXT.__auth_stubs: 0x2330
-  __TEXT.__objc_stubs: 0x22720
-  __TEXT.__objc_methlist: 0x105e4
-  __TEXT.__const: 0x485e
-  __TEXT.__cstring: 0x37c36
-  __TEXT.__objc_methname: 0x3dc77
-  __TEXT.__objc_classname: 0xe8a
-  __TEXT.__objc_methtype: 0x3bf5
-  __TEXT.__oslogstring: 0x4b7c0
-  __TEXT.__gcc_except_tab: 0x2fe4
+1487.120.62.0.0
+  __TEXT.__text: 0x2b835c
+  __TEXT.__auth_stubs: 0x2380
+  __TEXT.__objc_stubs: 0x22780
+  __TEXT.__objc_methlist: 0x10664
+  __TEXT.__const: 0x484e
+  __TEXT.__cstring: 0x37f26
+  __TEXT.__objc_methname: 0x3df0e
+  __TEXT.__objc_classname: 0xe88
+  __TEXT.__objc_methtype: 0x3ba1
+  __TEXT.__oslogstring: 0x4c6cd
+  __TEXT.__gcc_except_tab: 0x30d0
   __TEXT.__swift5_typeref: 0x1093
   __TEXT.__constg_swiftt: 0x14fc
   __TEXT.__swift5_fieldmd: 0xfec

   __TEXT.__swift5_protos: 0x60
   __TEXT.__swift5_capture: 0x30
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x4820
+  __TEXT.__unwind_info: 0x4838
   __TEXT.__eh_frame: 0x332c
-  __DATA_CONST.__auth_got: 0x11a8
-  __DATA_CONST.__got: 0x670
+  __DATA_CONST.__auth_got: 0x11d0
+  __DATA_CONST.__got: 0x680
   __DATA_CONST.__auth_ptr: 0x968
-  __DATA_CONST.__const: 0x6948
-  __DATA_CONST.__cfstring: 0x2ba00
+  __DATA_CONST.__const: 0x6930
+  __DATA_CONST.__cfstring: 0x2bba0
   __DATA_CONST.__objc_classlist: 0x3f8
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x98f8
+  __DATA_CONST.__objc_selrefs: 0x9930
   __DATA_CONST.__objc_intobj: 0x558
-  __DATA_CONST.__objc_arraydata: 0xb98
+  __DATA_CONST.__objc_arraydata: 0xbb8
   __DATA_CONST.__objc_arrayobj: 0x270
   __DATA_CONST.__objc_dictobj: 0xf0
-  __DATA.__objc_const: 0x15250
+  __DATA.__objc_const: 0x15290
   __DATA.__objc_protorefs: 0x18
   __DATA.__objc_classrefs: 0x7d8
   __DATA.__objc_superrefs: 0x2f8
-  __DATA.__objc_ivar: 0x13fc
+  __DATA.__objc_ivar: 0x1400
   __DATA.__objc_data: 0x2778
   __DATA.__data: 0x26ca
   __DATA.__s_async_hook: 0x190
   __DATA.__swift56_hooks: 0xb0
-  __DATA.__bss: 0x5518
+  __DATA.__bss: 0x54e8
   __DATA.__common: 0x90
   - /System/Library/Frameworks/AuthenticationServices.framework/Versions/A/AuthenticationServices
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 8468
-  Symbols:   15208
-  CStrings:  16224
+  Functions: 8475
+  Symbols:   15223
+  CStrings:  16271
 
Symbols:
+ +[MADAutoAssetControlManager preferenceMaxStagerFilesystemMegabytes]
+ +[MADAutoAssetControlManager preferenceStagerInjectAvailableDups]
+ +[MADAutoAssetControlManager preferenceStagerInjectAvailableOlderVersions]
+ +[MADAutoAssetHistory recordOperation:toHistoryType:fromLayer:forTargetOSVersion:forTargetBuildVersion:withAddendumMessage:]
+ -[DownloadManager keyManager]
+ -[DownloadManager pallasDelegate]
+ -[DownloadManager setKeyManager:]
+ -[DownloadManager setPallasDelegate:]
+ -[DownloaderSessionDelegate .cxx_destruct]
+ -[DownloaderSessionDelegate keyManagerDelegate]
+ -[DownloaderSessionDelegate queue]
+ -[MADAutoAssetControlManager preferenceMaxStagerFilesystemMegabytes]
+ -[MADAutoAssetControlManager preferenceStagerInjectAvailableDups]
+ -[MADAutoAssetControlManager preferenceStagerInjectAvailableOlderVersions]
+ -[MADAutoAssetControlManager setPreferenceMaxStagerFilesystemMegabytes:]
+ -[MADAutoAssetControlManager setPreferenceStagerInjectAvailableDups:]
+ -[MADAutoAssetControlManager setPreferenceStagerInjectAvailableOlderVersions:]
+ -[MADAutoAssetDescriptor initForAssetType:fromMetadata:fromBaseDescriptor:substitutingAssetVersion:invalidReasons:]
+ -[MADAutoAssetStager considerInjectionIntoAvailableForStaging]
+ -[MADAutoAssetStager dedupAvailableForStaging:dedupingAssetDescriptors:ofContainerName:]
+ -[MAKeyManagerDownloadSessionDelegate baaCertManager]
+ -[MAKeyManagerDownloadSessionDelegate copyKeyAndBAACerificateChain:]
+ -[MAKeyManagerDownloadSessionDelegate copyKeyAndSelfSignedCertificateChain:]
+ -[MAKeyManagerDownloadSessionDelegate initWithName:certType:]
+ -[MAKeyManagerDownloadSessionDelegate refreshBAACertificate]
+ -[MAKeyManagerDownloadSessionDelegate underlyingQueue]
+ -[MobileAssetHealthReport init]
+ -[MobileAssetHealthReport scheduleReport]
+ -[MobileAssetHealthReport setLastReportDate:]
+ -[MobileAssetKeyManager initWithDelegate:]
+ GCC_except_table147
+ GCC_except_table160
+ GCC_except_table171
+ GCC_except_table210
+ GCC_except_table37
+ GCC_except_table446
+ GCC_except_table45
+ GCC_except_table637
+ GCC_except_table641
+ GCC_except_table647
+ GCC_except_table649
+ GCC_except_table663
+ GCC_except_table799
+ OBJC_IVAR_$_DownloadManager._keyManager
+ OBJC_IVAR_$_DownloadManager._pallasDelegate
+ OBJC_IVAR_$_DownloaderSessionDelegate._keyManagerDelegate
+ OBJC_IVAR_$_MADAutoAssetControlManager._preferenceMaxStagerFilesystemMegabytes
+ OBJC_IVAR_$_MADAutoAssetControlManager._preferenceStagerInjectAvailableDups
+ OBJC_IVAR_$_MADAutoAssetControlManager._preferenceStagerInjectAvailableOlderVersions
+ OBJC_IVAR_$_MAKeyManagerDownloadSessionDelegate._baaCertManager
+ OBJC_IVAR_$_MAKeyManagerDownloadSessionDelegate._underlyingQueue
+ _OBJC_EHTYPE_$_NSException
+ _XPC_ACTIVITY_REQUIRE_NETWORK_CONNECTIVITY
+ __41-[MobileAssetHealthReport scheduleReport]_block_invoke
+ ___31-[MobileAssetHealthReport init]_block_invoke
+ ___41-[MobileAssetHealthReport scheduleReport]_block_invoke
+ ___45-[MobileAssetHealthReport setLastReportDate:]_block_invoke
+ ___68-[MAKeyManagerDownloadSessionDelegate copyKeyAndBAACerificateChain:]_block_invoke
+ ___block_descriptor_40_e8_32s_e33_v16?0"NSObject<OS_xpc_object>"8l
+ _dispatch_async_and_wait
+ _kMobileAssetPreferencesAutoAssetStagerFilesystemMaxMegabytes
+ _kMobileAssetPreferencesAutoAssetStagerInjectAvailableDups
+ _kMobileAssetPreferencesAutoAssetStagerInjectAvailableOlderVersions
+ _objc_begin_catch
+ _objc_end_catch
+ _objc_msgSend$URLSession:didReceiveChallenge:completionHandler:
+ _objc_msgSend$baaCertManager
+ _objc_msgSend$considerInjectionIntoAvailableForStaging
+ _objc_msgSend$copyKeyAndBAACerificateChain:
+ _objc_msgSend$copyKeyAndSelfSignedCertificateChain:
+ _objc_msgSend$dedupAvailableForStaging:dedupingAssetDescriptors:ofContainerName:
+ _objc_msgSend$downloadSessionDelegate
+ _objc_msgSend$initForAssetType:fromMetadata:fromBaseDescriptor:substitutingAssetVersion:invalidReasons:
+ _objc_msgSend$initWithName:certType:
+ _objc_msgSend$keyManager
+ _objc_msgSend$keyManagerDelegate
+ _objc_msgSend$lowercaseString
+ _objc_msgSend$pallasDelegate
+ _objc_msgSend$preferenceMaxStagerFilesystemMegabytes
+ _objc_msgSend$preferenceStagerInjectAvailableDups
+ _objc_msgSend$preferenceStagerInjectAvailableOlderVersions
+ _objc_msgSend$reason
+ _objc_msgSend$recordOperation:toHistoryType:fromLayer:forTargetOSVersion:forTargetBuildVersion:withAddendumMessage:
+ _objc_msgSend$refreshBAACertificate
+ _objc_msgSend$scheduleReport
+ _objc_msgSend$setKeyManager:
+ _objc_msgSend$setPallasDelegate:
+ _objc_msgSend$setUnderlyingQueue:
+ _objc_setProperty_atomic_copy
+ _xpc_dictionary_create_empty
- -[ControlManager downloadManager]
- -[DownloadManager authPallasBAACertManager]
- -[DownloadManager authPallasSessionDelegate]
- -[DownloadManager authPallasSession]
- -[DownloadManager setAuthPallasBAACertManager:]
- -[DownloadManager setAuthPallasSession:]
- -[DownloadManager setAuthPallasSessionDelegate:]
- -[DownloadManager setOperationQueue:]
- -[DownloadManager setSplunkOperationQueue:]
- -[MADAutoAssetControlManager _initializePeriodicHealthReport]
- -[MobileAssetHealthReport initWithInterval:leeway:]
- -[MobileAssetHealthReport reportCadance]
- -[MobileAssetHealthReport reportLeeway]
- -[MobileAssetHealthReport reportTimer]
- -[MobileAssetHealthReport scheduleReport:]
- -[MobileAssetHealthReport setLastRerpotDate:]
- -[MobileAssetHealthReport setReportCadance:]
- -[MobileAssetHealthReport setReportLeeway:]
- -[MobileAssetHealthReport setReportTimer:]
- GCC_except_table162
- GCC_except_table173
- GCC_except_table18
- GCC_except_table213
- GCC_except_table32
- GCC_except_table36
- GCC_except_table42
- GCC_except_table447
- GCC_except_table46
- GCC_except_table638
- GCC_except_table642
- GCC_except_table648
- GCC_except_table650
- GCC_except_table664
- GCC_except_table797
- GCC_except_table83
- MACopyDawToken:.manager
- MACopyDawToken:.mobileAssetKeyManagerAllocDispatchOnce
- OBJC_IVAR_$_ControlManager._downloadManager
- OBJC_IVAR_$_DownloadManager._authPallasBAACertManager
- OBJC_IVAR_$_DownloadManager._authPallasSession
- OBJC_IVAR_$_DownloadManager._authPallasSessionDelegate
- OBJC_IVAR_$_MobileAssetHealthReport._reportCadance
- OBJC_IVAR_$_MobileAssetHealthReport._reportLeeway
- OBJC_IVAR_$_MobileAssetHealthReport._reportTimer
- __42-[MobileAssetHealthReport scheduleReport:]_block_invoke
- ___34-[DownloadManager MACopyDawToken:]_block_invoke
- ___42-[MobileAssetHealthReport scheduleReport:]_block_invoke
- ___45-[MobileAssetHealthReport setLastRerpotDate:]_block_invoke
- ___51-[MobileAssetHealthReport initWithInterval:leeway:]_block_invoke
- ___55-[DownloadManager downloadNeedsSSO:taskDescriptor:url:]_block_invoke
- ___64-[DownloadManager decryptContentEncryptedAssetAtPathIfRequired:]_block_invoke
- _objc_msgSend$_initializePeriodicHealthReport
- _objc_msgSend$authPallasBAACertManager
- _objc_msgSend$authPallasSessionDelegate
- _objc_msgSend$getLastReportDate
- _objc_msgSend$initWithInterval:leeway:
- _objc_msgSend$operationQueue
- _objc_msgSend$recordOperation:toHistoryType:fromLayer:fromClient:
- _objc_msgSend$reportCadance
- _objc_msgSend$reportLeeway
- _objc_msgSend$reportTimer
- _objc_msgSend$scheduleReport:
- _objc_msgSend$setAuthPallasBAACertManager:
- _objc_msgSend$setAuthPallasSession:
- _objc_msgSend$setAuthPallasSessionDelegate:
- _objc_msgSend$setCertArray:
- _objc_msgSend$setLastRerpotDate:
- _objc_msgSend$setMaxConcurrentOperationCount:
- _objc_msgSend$setRefKey:
- _objc_msgSend$setReportTimer:
- _objc_msgSend$splunkOperationQueue
- decryptContentEncryptedAssetAtPathIfRequired:.keyManager
- decryptContentEncryptedAssetAtPathIfRequired:.keyManagerDispatchOnce
- downloadNeedsSSO:taskDescriptor:url:.keyManager
- downloadNeedsSSO:taskDescriptor:url:.keyManagerDispatchOnce
CStrings:
+ "%@:isAnyAvailableForStagingByGroup"
+ "0.0.0.0.0,0"
+ "2.5.0"
+ "@\"MobileAssetKeyManager\""
+ "@56@0:8@16@24@32@40^@48"
+ "AutoAssetStagerFilesystemMaxMegabytes"
+ "AutoAssetStagerInjectAvailableDups"
+ "AutoAssetStagerInjectAvailableOlderVersions"
+ "DETERMINED"
+ "DETERMINE_DONE             "
+ "DETERMINE_DROPPED          "
+ "DownloadSession"
+ "PallasSession"
+ "Starting built-in MobileAsset brain built Apr 13 2025 23:44:29"
+ "Starting downloaded MobileAsset brain (version: %@) built Apr 13 2025 23:44:29"
+ "T@\"MABAACertManager\",R,&,N,V_baaCertManager"
+ "T@\"MAKeyManagerDownloadSessionDelegate\",&,N,V_pallasDelegate"
+ "T@\"MAKeyManagerDownloadSessionDelegate\",R,&,N,V_keyManagerDelegate"
+ "T@\"MobileAssetKeyManager\",&,N,V_keyManager"
+ "T@\"NSArray\",C,V_certArray"
+ "T@\"NSObject<OS_dispatch_queue>\",R,&,N,V_underlyingQueue"
+ "T@\"NSOperationQueue\",R,&,N"
+ "T@\"NSOperationQueue\",R,N,V_operationQueue"
+ "T@\"NSOperationQueue\",R,N,V_splunkOperationQueue"
+ "T@,&,V_refKey"
+ "TB,N,V_preferenceStagerInjectAvailableDups"
+ "TB,N,V_preferenceStagerInjectAvailableOlderVersions"
+ "Tq,N,V_preferenceMaxStagerFilesystemMegabytes"
+ "Will not prompt user for AppleConnect token for key retrieval due to override on downloadOptions"
+ "[%@](%@) {%@} %@"
+ "[%@](%@) {%@} total size on-disk after extraction too large | availableForStaging:%ld | totalFilesystemBytes:%llu | maxFilesystemBytes:%llu"
+ "[AuthenticatedPallas]: Pallas server(%{public}@) %{public}s authentication"
+ "[BackgroundTaskOverride]: Configuring download for task:%{public}@ overriding Cellular"
+ "[BackgroundTaskOverride]: Configuring download for task:%{public}@ overriding Constrained"
+ "[BackgroundTaskOverride]: Configuring download for task:%{public}@ overriding Expensive"
+ "[BackgroundTaskOverride]: Configuring download for task:%{public}@ overriding:%{public}@"
+ "[BackgroundTaskOverride]: Download already started for task:%{public}@ overriding Cellular:%{public}@ Expensive:%{public}@ Constrained:%{public}@"
+ "[BackgroundTaskOverride]: Download already started for task:%{public}@. Overriding of download properties not supported for in process downloads"
+ "[BackgroundTaskOverride]: Failed to set backgroundTaskOverride for task:%{public}@ ExceptionName:%{public}@ ExceptionReason:%{public}@"
+ "[BackgroundTaskOverride]: Failed to set backgroundTaskOverrides for task:%{public}@ ExceptionName:%{public}@ ExceptionReason:%{public}@"
+ "[BackgroundTaskOverride]: Overriding of parameters not supported for in process downloads. Skipping"
+ "[MAKeyManagerDownloadSessionDelegate]: Disabling mTLS - no certificates available"
+ "[MobileAssetHealthReport] Report %@ submitted to CoreAnalytics"
+ "[MobileAssetHealthReport] Report %@ submitted to Splunk"
+ "[MobileAssetHealthReport]: Unknown XPC activity state (%ld) for activity %s"
+ "[MobileAssetHealthReport]: Use existing criteria: %@"
+ "[MobileAssetHealthReport]: Use new criteria: %@"
+ "[MobileAssetHealthReport]: XPC activity %s is checking in"
+ "[MobileAssetHealthReport]: XPC activity %s is running"
+ "^{__SecKey={__CFRuntimeBase=QAQ}^{__SecKeyDescriptor}^v}24@0:8^@16"
+ "__KnoxMTLS"
+ "_baaCertManager"
+ "_keyManager"
+ "_keyManagerDelegate"
+ "_pallasDelegate"
+ "_preferenceMaxStagerFilesystemMegabytes"
+ "_preferenceStagerInjectAvailableDups"
+ "_preferenceStagerInjectAvailableOlderVersions"
+ "_underlyingQueue"
+ "baaCertManager"
+ "com.apple.mobileassetd.health-report"
+ "considerInjectionIntoAvailableForStaging"
+ "copyKeyAndBAACerificateChain:"
+ "copyKeyAndSelfSignedCertificateChain:"
+ "corrupted descriptor (key:%@)"
+ "dedupAvailableForStaging:dedupingAssetDescriptors:ofContainerName:"
+ "device out-of-memory"
+ "does *NOT* require"
+ "dropped all available-for-staging | %@"
+ "finalized available-for-staging | beganFromCount:%ld | duplicateCount:%ld | multipleCount:%ld | notComparableCount:%ld | availableForStaging:%ld | totalFilesystemBytes:%llu"
+ "gdmf.apple.com"
+ "initForAssetType:fromMetadata:fromBaseDescriptor:substitutingAssetVersion:invalidReasons:"
+ "initWithName:certType:"
+ "keyManager"
+ "keyManagerDelegate"
+ "lowercaseString"
+ "nothing in trimmed-available-for-staging"
+ "pallasDelegate"
+ "preferenceMaxStagerFilesystemMegabytes"
+ "preferenceStagerInjectAvailableDups"
+ "preferenceStagerInjectAvailableOlderVersions"
+ "reason"
+ "recordOperation:toHistoryType:fromLayer:forTargetOSVersion:forTargetBuildVersion:withAddendumMessage:"
+ "refreshBAACertificate"
+ "requires"
+ "scheduleReport"
+ "setKeyManager:"
+ "setLastReportDate:"
+ "setPallasDelegate:"
+ "setPreferenceMaxStagerFilesystemMegabytes:"
+ "setPreferenceStagerInjectAvailableDups:"
+ "setPreferenceStagerInjectAvailableOlderVersions:"
+ "setUnderlyingQueue:"
+ "underlyingQueue"
+ "{%{public}@}\n[%{public}@](%{public}@) [DEDUP-AVAILABLE-FOR-STAGING] asset-descriptor array validated | availableSummary:%{public}@"
+ "{%{public}@}\n[%{public}@](%{public}@) [DEDUP-AVAILABLE-FOR-STAGING] asset-versions not comparable (filtered latest encountered) | droppedDescriptor:%{public}@ | keptDescriptor:%{public}@"
+ "{%{public}@}\n[%{public}@](%{public}@) [DEDUP-AVAILABLE-FOR-STAGING] dropped all assets that had been considered as available-for-staging | droppedAllReason:%{public}@"
+ "{%{public}@}\n[%{public}@](%{public}@) [DEDUP-AVAILABLE-FOR-STAGING] duplicate descriptor (filtered) | nextAvailableDescriptor:%{public}@"
+ "{%{public}@}\n[%{public}@](%{public}@) [DEDUP-AVAILABLE-FOR-STAGING] multiple asset-versions (filtered older) | olderDescriptor:%{public}@ | newerDescriptor:%{public}@"
+ "{%{public}@}\n[%{public}@](%{public}@) [DEDUP-AVAILABLE-FOR-STAGING] potential total byte count issue | totalFilesystemBytes:%llu | miscountedFilesystemBytes:%llu"
+ "{%{public}@}\n[SET-STATUS-ERROR-CHANGE] failed set-job that was converted to success (already latest-to-vend) | setConfiguration:%{public}@"
+ "{%{public}@}\n[SET-STATUS-ERROR-CHANGE] failed set-job that was converted to success (have latest-to-vend) | setConfiguration:%{public}@"
+ "{%{public}@}\n[SET-STATUS-ERROR-CHANGE] failed set-job that was converted to success (matches latest-to-vend) | setConfiguration:%{public}@"
+ "{considerInjectionIntoAvailableForStaging} [DEDUP-AVAILABLE-FOR-STAGING] discrepancy detected while building test available-for-staging array-with-duplicates | nextFromOriginal:%{public}@ | originalAvailableForStaging:%ld | againAvailableForStaging:%ld"
+ "{considerInjectionIntoAvailableForStaging} [DEDUP-AVAILABLE-FOR-STAGING] discrepancy detected while building test available-for-staging array-with-older | nextFromOriginal:%{public}@ | originalAvailableForStaging:%ld | olderAvailableForStaging:%ld"
+ "{considerInjectionIntoAvailableForStaging} [DEDUP-AVAILABLE-FOR-STAGING] empty again-available-for-staging while building test available-for-staging array-with-duplicates | nextFromOriginal:%{public}@ | originalAvailableForStaging:%ld | againAvailableForStaging:%ld"
+ "{considerInjectionIntoAvailableForStaging} [DEDUP-AVAILABLE-FOR-STAGING] empty again-available-for-staging while building test available-for-staging array-with-older | nextFromOriginal:%{public}@ | originalAvailableForStaging:%ld | olderAvailableForStaging:%ld"
+ "{considerInjectionIntoAvailableForStaging} [DEDUP-AVAILABLE-FOR-STAGING] injected available-for-staging array-with-duplicates | availableForStaging:%ld"
+ "{considerInjectionIntoAvailableForStaging} [DEDUP-AVAILABLE-FOR-STAGING] injected available-for-staging array-with-older | availableForStaging:%ld"
+ "{considerInjectionIntoAvailableForStaging} [DEDUP-AVAILABLE-FOR-STAGING] nil nextDescriptor while building test available-for-staging array-with-duplicates | nextFromOriginal:%{public}@ | originalAvailableForStaging:%ld | againAvailableForStaging:%ld"
+ "{considerInjectionIntoAvailableForStaging} [DEDUP-AVAILABLE-FOR-STAGING] nil nextDescriptor while building test available-for-staging array-with-older | nextFromOriginal:%{public}@ | originalAvailableForStaging:%ld | olderAvailableForStaging:%ld"
- "%"
- "%@%@Queue"
- "%{public}@ user for AppleConnect token for key retrieval due to override on downloadOptions"
- "2.4.3"
- "@32@0:8d16d24"
- "AuthPallasSession"
- "Configuring download for task:%{public}@ overriding Cellular"
- "Configuring download for task:%{public}@ overriding Constrained"
- "Configuring download for task:%{public}@ overriding Expensive"
- "Configuring download for task:%{public}@ overriding:%{public}@"
- "Download already started for task:%{public}@ overriding Cellular:%{public}@ Expensive:%{public}@ Constrained:%{public}@"
- "HealthReportIntervalSec"
- "HealthReportLeewaySec"
- "Knox lookup for decryption key %{public}@"
- "Starting built-in MobileAsset brain built Apr  6 2025 19:19:18"
- "Starting downloaded MobileAsset brain (version: %@) built Apr  6 2025 19:19:18"
- "T@\"MABAACertManager\",&,N,V_authPallasBAACertManager"
- "T@\"MAKeyManagerDownloadSessionDelegate\",&,N,V_authPallasSessionDelegate"
- "T@\"NSArray\",&,N,V_certArray"
- "T@\"NSObject<OS_dispatch_source>\",&,N,V_reportTimer"
- "T@\"NSOperationQueue\",&,N,V_operationQueue"
- "T@\"NSOperationQueue\",&,N,V_splunkOperationQueue"
- "T@\"NSURLSession\",&,N,V_authPallasSession"
- "T^{__SecKey={__CFRuntimeBase=QAQ}^{__SecKeyDescriptor}^v},N,V_refKey"
- "Td,V_reportCadance"
- "Td,V_reportLeeway"
- "Using internal server trust for %{public}@"
- "Will not prompt"
- "Will prompt(if required)"
- "[AuthenticatedPallas]: Pallas server(%{public}@) does *NOT* require authentication"
- "[AuthenticatedPallas]: Pallas server(%{public}@) requires authentication"
- "[MobileAssetHealthReport]: Reporting interval is %lf seconds (leeway = %lf seconds)"
- "[MobileAssetHealthReport]: scheduleReport: Canceling previously scheduled report"
- "[MobileAssetHealthReport]: scheduleReport: LastReportDate: [%{public}@]"
- "[MobileAssetHealthReport]: scheduleReport: Next report delay: %lf seconds"
- "^{__SecKey={__CFRuntimeBase=QAQ}^{__SecKeyDescriptor}^v}"
- "^{__SecKey={__CFRuntimeBase=QAQ}^{__SecKeyDescriptor}^v}16@0:8"
- "_authPallasBAACertManager"
- "_authPallasSession"
- "_authPallasSessionDelegate"
- "_initializePeriodicHealthReport"
- "_reportCadance"
- "_reportLeeway"
- "_reportTimer"
- "authPallasBAACertManager"
- "authPallasSession"
- "authPallasSessionDelegate"
- "https://gdmf.apple.com/assets"
- "initWithInterval:leeway:"
- "reportCadance"
- "reportLeeway"
- "reportTimer"
- "scheduleReport:"
- "setAuthPallasBAACertManager:"
- "setAuthPallasSession:"
- "setAuthPallasSessionDelegate:"
- "setLastRerpotDate:"
- "setMaxConcurrentOperationCount:"
- "setOperationQueue:"
- "setReportCadance:"
- "setReportLeeway:"
- "setReportTimer:"
- "setSplunkOperationQueue:"
- "v24@0:8^{__SecKey={__CFRuntimeBase=QAQ}^{__SecKeyDescriptor}^v}16"
```
