## AppKit

> `/System/Library/Frameworks/AppKit.framework/Versions/C/AppKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-2575.70.4.0.0
-  __TEXT.__text: 0xef02a4
+2575.70.50.0.0
+  __TEXT.__text: 0xeef3bc
   __TEXT.__auth_stubs: 0xfd80
-  __TEXT.__objc_methlist: 0xcab60
+  __TEXT.__objc_methlist: 0xcab08
   __TEXT.__const: 0x1d5b8
   __TEXT.__dlopen_cstrs: 0xe9d
-  __TEXT.__cstring: 0xc39dc
+  __TEXT.__cstring: 0xc3882
   __TEXT.__swift5_typeref: 0x75ce
   __TEXT.__swift5_reflstr: 0x4edf
   __TEXT.__swift5_assocty: 0x1958

   __TEXT.__swift5_builtin: 0x5c8
   __TEXT.__swift5_capture: 0x1f10
   __TEXT.__swift5_mpenum: 0x38
-  __TEXT.__oslogstring: 0x1a614
+  __TEXT.__oslogstring: 0x1a607
   __TEXT.__swift5_protos: 0xd8
   __TEXT.__swift_as_entry: 0xd4
   __TEXT.__swift_as_ret: 0xa4
-  __TEXT.__gcc_except_tab: 0xa5698
+  __TEXT.__gcc_except_tab: 0xa54c4
   __TEXT.__ustring: 0x15ea
   __TEXT.__dof_NSTrackin: 0x7e7
   __TEXT.__dof_NSApplica: 0x809
   __TEXT.__dof_NSAccessi: 0x1eb
-  __TEXT.__unwind_info: 0x536e8
+  __TEXT.__unwind_info: 0x53670
   __TEXT.__eh_frame: 0x5b18
   __TEXT.__objc_classname: 0x15673
-  __TEXT.__objc_methname: 0x153db1
+  __TEXT.__objc_methname: 0x153bf7
   __TEXT.__objc_methtype: 0x3f096
-  __TEXT.__objc_stubs: 0xfbc00
+  __TEXT.__objc_stubs: 0xfbae0
   __DATA_CONST.__got: 0x4f10
-  __DATA_CONST.__const: 0xa1a0
+  __DATA_CONST.__const: 0xa188
   __DATA_CONST.__objc_classlist: 0x4798
   __DATA_CONST.__objc_nlclslist: 0x20
   __DATA_CONST.__objc_catlist: 0x1e0
   __DATA_CONST.__objc_protolist: 0xf90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4cb08
+  __DATA_CONST.__objc_selrefs: 0x4cac8
   __DATA_CONST.__objc_protorefs: 0x558
   __DATA_CONST.__objc_superrefs: 0x3cd0
   __DATA_CONST.__objc_arraydata: 0x4050
   __AUTH_CONST.__auth_got: 0x7ed8
-  __AUTH_CONST.__const: 0x360c0
-  __AUTH_CONST.__cfstring: 0x976e0
-  __AUTH_CONST.__objc_const: 0xf2f80
+  __AUTH_CONST.__const: 0x36070
+  __AUTH_CONST.__cfstring: 0x975e0
+  __AUTH_CONST.__objc_const: 0xf2f00
   __AUTH_CONST.__objc_intobj: 0x2d00
   __AUTH_CONST.__objc_dictobj: 0x7a8
   __AUTH_CONST.__objc_doubleobj: 0x3c0

   __AUTH_CONST.__objc_floatobj: 0x20
   __AUTH.__objc_data: 0xf420
   __AUTH.__data: 0x4238
-  __DATA.__objc_ivar: 0x72c4
+  __DATA.__objc_ivar: 0x72b4
   __DATA.__data: 0x10468
   __DATA.__crash_info: 0x40
-  __DATA.__bss: 0x2b328
+  __DATA.__bss: 0x2b318
   __DATA.__common: 0xee4
   __DATA_DIRTY.__objc_ivar: 0x44c0
   __DATA_DIRTY.__objc_data: 0x22970

   - /System/Library/PrivateFrameworks/MobileKeyBag.framework/Versions/A/MobileKeyBag
   - /System/Library/PrivateFrameworks/MultitouchSupport.framework/Versions/A/MultitouchSupport
   - /System/Library/PrivateFrameworks/PerformanceAnalysis.framework/Versions/A/PerformanceAnalysis
-  - /System/Library/PrivateFrameworks/RemoteViewServices.framework/Versions/A/RemoteViewServices
   - /System/Library/PrivateFrameworks/RenderBox.framework/Versions/A/RenderBox
   - /System/Library/PrivateFrameworks/SkyLight.framework/Versions/A/SkyLight
   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 87307
-  Symbols:   147620
-  CStrings:  83063
+  Functions: 87295
+  Symbols:   147591
+  CStrings:  83041
 
Symbols:
+ __NSFileSandboxingRequestRelatedItemExtension
+ __OBJC_$_INSTANCE_METHODS_NSFileVersion(NSDocumentInternal|BUStarfieldTimelineSupport)
+ __OBJC_CLASS_PROTOCOLS_$_NSFileVersion(NSDocumentInternal|BUStarfieldTimelineSupport)
+ ____softLinkTSMMenuKeyTrans_block_invoke
+ ___block_descriptor_48_ea8_32s40r_e29_v24?0"NSArray"8"NSError"16l
- +[NSFileVersion(NSExtensions) _finishedWithBackupCollection:]
- +[NSFileVersion(NSExtensions) _getBackupVersionsForURL:queue:completionHandler:]
- -[NSDocumentRevisionsController _asyncVersionLookupErrorCode]
- -[NSDocumentRevisionsController _asyncVersionLookupInProgress]
- -[NSDocumentRevisionsController _setAsyncVersionLookupError:forDocument:]
- -[NSDocumentRevisionsController _setAsyncVersionLookupInProgress:forDocument:]
- -[NSDocumentRevisionsController _updateAsyncVersionLookupStatus]
- GCC_except_table422
- OBJC_IVAR_$_NSDocumentRevisionsController._timeMachineStatusPlaceholderView
- OBJC_IVAR_$_NSDocumentRevisionsController.asyncVersionLookupErrorCode
- OBJC_IVAR_$_NSDocumentRevisionsController.asyncVersionLookupInProgress
- OBJC_IVAR_$_NSDocumentRevisionsController.backupCollectionToken
- _PBOXRelatedItemRequest
- __OBJC_$_CLASS_METHODS_NSFileVersion(NSDocumentInternal|BUStarfieldTimelineSupport|NSExtensions)
- __OBJC_$_INSTANCE_METHODS_NSFileVersion(NSDocumentInternal|BUStarfieldTimelineSupport|NSExtensions)
- __OBJC_CLASS_PROTOCOLS_$_NSFileVersion(NSDocumentInternal|BUStarfieldTimelineSupport|NSExtensions)
- ___61+[NSFileVersion(NSExtensions) _finishedWithBackupCollection:]_block_invoke
- ___80+[NSFileVersion(NSExtensions) _getBackupVersionsForURL:queue:completionHandler:]_block_invoke
- ___80+[NSFileVersion(NSExtensions) _getBackupVersionsForURL:queue:completionHandler:]_block_invoke_2
- ___80+[NSFileVersion(NSExtensions) _getBackupVersionsForURL:queue:completionHandler:]_block_invoke_3
- ___block_descriptor_56_ea8_32s40r48r_e29_v24?0"NSArray"8"NSError"16l
- ___block_descriptor_56_ea8_32s40r48r_e33_v32?0^v8"NSArray"16"NSError"24l
- _getBackupVersionsForURL:queue:completionHandler:.predicate
- _objc_msgSend$_asyncVersionLookupErrorCode
- _objc_msgSend$_asyncVersionLookupInProgress
- _objc_msgSend$_finishedWithBackupCollection:
- _objc_msgSend$_getBackupVersionsForURL:queue:completionHandler:
- _objc_msgSend$_initWithFileURL:library:clientID:name:contentsURL:isBackup:revision:
- _objc_msgSend$_setAsyncVersionLookupError:forDocument:
- _objc_msgSend$_setAsyncVersionLookupInProgress:forDocument:
- _objc_msgSend$_updateAsyncVersionLookupStatus
- _objc_msgSend$setMessage2:
- _pathToSystemFramework
- _sIncompleteMenus
CStrings:
+ "NSPersistentDocument: Request for item %{sensitive}@ related to document %{sensitive}@ failed"
+ "_TSMMenuKeyTransWithModifiersBegin"
+ "_TSMMenuKeyTransWithModifiersEnd"
+ "com.apple.Keynote"
- "%@: URL parameter may not be nil"
- "%@: queue parameter may not be nil"
- "/Versions/A/RemoteViewServices"
- "Error retrieving versions from Time Machine"
- "NSPersistentDocument: Request for item %{sensitive}@ related to document %{sensitive}@ failed: %{private}@"
- "No previous versions available"
- "PBOXBackupItemCollectionCopyItems"
- "PBOXBackupItemCollectionCreateWithURL"
- "PBOXBackupItemCollectionRelease"
- "RemoteViewServices.framework"
- "Retrieving versions"
- "Time Machine can\\U2019t find your backup disk"
- "_NSPBOXStatusErrorDomain"
- "_asyncVersionLookupErrorCode"
- "_asyncVersionLookupInProgress"
- "_finishedWithBackupCollection:"
- "_getBackupVersionsForURL:queue:completionHandler:"
- "_initWithFileURL:library:clientID:name:contentsURL:isBackup:revision:"
- "_setAsyncVersionLookupError:forDocument:"
- "_setAsyncVersionLookupInProgress:forDocument:"
- "_timeMachineStatusPlaceholderView"
- "_updateAsyncVersionLookupStatus"
- "asyncVersionLookupErrorCode"
- "asyncVersionLookupInProgress"
- "backupCollectionToken"
- "v32@?0^v8@\"NSArray\"16@\"NSError\"24"
```
