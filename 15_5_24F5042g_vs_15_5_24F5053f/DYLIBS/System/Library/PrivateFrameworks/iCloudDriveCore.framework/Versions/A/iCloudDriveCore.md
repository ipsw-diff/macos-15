## iCloudDriveCore

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/Versions/A/iCloudDriveCore`

```diff

-3437.120.2.0.0
-  __TEXT.__text: 0x345b6c
+3437.120.13.0.1
+  __TEXT.__text: 0x345d84
   __TEXT.__auth_stubs: 0x1a20
-  __TEXT.__objc_methlist: 0x190fc
+  __TEXT.__objc_methlist: 0x1912c
   __TEXT.__const: 0x4d0
-  __TEXT.__cstring: 0x7a964
-  __TEXT.__oslogstring: 0x3bf41
-  __TEXT.__gcc_except_tab: 0x1a0f4
+  __TEXT.__cstring: 0x7aa36
+  __TEXT.__oslogstring: 0x3be9a
+  __TEXT.__gcc_except_tab: 0x1a0e4
   __TEXT.__ustring: 0x88
-  __TEXT.__unwind_info: 0x9b70
+  __TEXT.__unwind_info: 0x9b88
   __TEXT.__objc_classname: 0x2679
-  __TEXT.__objc_methname: 0x41523
+  __TEXT.__objc_methname: 0x4155a
   __TEXT.__objc_methtype: 0x893d
-  __TEXT.__objc_stubs: 0x2cdc0
+  __TEXT.__objc_stubs: 0x2ce00
   __DATA_CONST.__got: 0x1758
   __DATA_CONST.__const: 0x1ca0
   __DATA_CONST.__objc_classlist: 0x998
   __DATA_CONST.__objc_catlist: 0xe0
   __DATA_CONST.__objc_protolist: 0x258
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xdd60
+  __DATA_CONST.__objc_selrefs: 0xdd78
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x870
   __DATA_CONST.__objc_arraydata: 0xf60
   __AUTH_CONST.__auth_got: 0xd20
   __AUTH_CONST.__const: 0xaa18
-  __AUTH_CONST.__cfstring: 0x22440
+  __AUTH_CONST.__cfstring: 0x22460
   __AUTH_CONST.__objc_const: 0x3b050
   __AUTH_CONST.__objc_intobj: 0xb40
   __AUTH_CONST.__objc_arrayobj: 0x288
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_doubleobj: 0x50
   __AUTH.__objc_data: 0x5ff0
-  __AUTH.__data: 0x20
+  __AUTH.__data: 0x28
   __DATA.__objc_ivar: 0x1ed4
   __DATA.__data: 0x25f0
-  __DATA.__bss: 0x610
+  __DATA.__bss: 0x620
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit

   - /usr/lib/libprequelite.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 13363
-  Symbols:   23308
-  CStrings:  22275
+  Functions: 13367
+  Symbols:   23309
+  CStrings:  22277
 
Symbols:
+ -[BRCFSDownloader _buildDownloadActiveJobsResultSetForThrottleID:etag:kind:]
+ -[BRCFSDownloader _cancelJobs:state:cancelError:]
+ -[NSFileProviderItemVersion(BRItemAdditions) br_isValidContentVersion]
+ -[NSFileProviderItemVersion(BRItemAdditions) br_isValidStructureVersion]
+ GCC_except_table162
+ GCC_except_table171
+ _objc_msgSend$_buildDownloadActiveJobsResultSetForThrottleID:etag:kind:
+ _objc_msgSend$_cancelJobs:state:cancelError:
+ _objc_msgSend$beforeFirstSyncComponent
+ _objc_msgSend$br_isValidContentVersion
+ _objc_msgSend$br_isValidStructureVersion
+ _objc_msgSend$brc_genericDownloadErrorWithUnderlyingError:
+ _objc_msgSend$isFilePackageAtPath:
- GCC_except_table150
- GCC_except_table158
- GCC_except_table164
- GCC_except_table169
- GCC_except_table212
- GCC_except_table216
- ___52-[BRCSharingAcceptFlowOperation _completeWithError:]_block_invoke_3
- _objc_msgSend$closeWithError:
- _objc_msgSend$initWithEnvironmentName:namedDelegatePort:enablePushDuringSleep:queue:
- _objc_msgSend$setDarkWakeTopics:
- _objc_msgSend$setEnabledTopics:ignoredTopics:opportunisticTopics:nonWakingTopics:
- _objc_msgSend$setPushWakeTopics:
CStrings:
+ "-[BRCFSDownloader _cancelJobs:state:cancelError:]"
+ "BRCWorkspace.m"
+ "SELECT throttle_id, download_kind, download_etag, transfer_operation, transfer_stage, app_library_rowid, zone_rowid, throttle_state, transfer_size FROM client_downloads WHERE throttle_id = %lld    AND throttle_state != 0"
+ "SELECT throttle_id, download_kind, download_etag, transfer_operation, transfer_stage, app_library_rowid, zone_rowid, throttle_state, transfer_size FROM client_downloads WHERE throttle_id = %lld AND download_etag = %@   AND throttle_state != 0"
+ "[DEBUG] Opening directory at %@%@"
+ "_buildDownloadActiveJobsResultSetForThrottleID:etag:kind:"
+ "_cancelJobs:state:cancelError:"
+ "beforeFirstSyncComponent"
+ "br_isValidContentVersion"
+ "br_isValidStructureVersion"
+ "brc_genericDownloadErrorWithUnderlyingError:"
+ "isFilePackageAtPath:"
- "-[BRCFSDownloader _cancelJobs:state:]"
- "-[BRCPendingChangesStream _dbBecameCorrupted:withDescription:]"
- "SELECT throttle_id, download_kind, download_etag, transfer_operation, transfer_stage, app_library_rowid, zone_rowid, throttle_state, transfer_size FROM client_downloads WHERE throttle_id = %lld AND throttle_state != 0"
- "[CRIT] error closing BRCPendingChangesStream DB connection: %@%@"
- "[DEBUG] opening directory at %@%@"
- "[ERROR] We are in an error scenario, trying to close the DB, but it's busy - let's avoid dealloc it%@"
- "initWithEnvironmentName:namedDelegatePort:enablePushDuringSleep:queue:"
- "setDarkWakeTopics:"
- "setEnabledTopics:ignoredTopics:opportunisticTopics:nonWakingTopics:"
- "setPushWakeTopics:"
```
