## AppKit

> `/System/Library/Frameworks/AppKit.framework/Versions/C/AppKit`

```diff

-2575.50.26.0.0
-  __TEXT.__text: 0xeec8f0
+2575.60.2.0.0
+  __TEXT.__text: 0xeefb84
   __TEXT.__auth_stubs: 0xfd80
-  __TEXT.__objc_methlist: 0xcaae8
-  __TEXT.__const: 0x1d378
+  __TEXT.__objc_methlist: 0xcab38
+  __TEXT.__const: 0x1d388
   __TEXT.__dlopen_cstrs: 0xe9d
-  __TEXT.__cstring: 0xc3368
+  __TEXT.__cstring: 0xc3947
   __TEXT.__swift5_typeref: 0x75ce
   __TEXT.__swift5_reflstr: 0x4edf
   __TEXT.__swift5_assocty: 0x1958

   __TEXT.__swift5_builtin: 0x5c8
   __TEXT.__swift5_capture: 0x1f10
   __TEXT.__swift5_mpenum: 0x38
-  __TEXT.__oslogstring: 0x1a3a5
+  __TEXT.__oslogstring: 0x1a5f3
   __TEXT.__swift5_protos: 0xd8
   __TEXT.__swift_as_entry: 0xd4
   __TEXT.__swift_as_ret: 0xa4
-  __TEXT.__gcc_except_tab: 0xa514c
+  __TEXT.__gcc_except_tab: 0xa565c
   __TEXT.__ustring: 0x15ea
   __TEXT.__dof_NSTrackin: 0x7e7
   __TEXT.__dof_NSApplica: 0x809
   __TEXT.__dof_NSAccessi: 0x1eb
-  __TEXT.__unwind_info: 0x535a0
+  __TEXT.__unwind_info: 0x536b8
   __TEXT.__eh_frame: 0x5b18
-  __TEXT.__objc_classname: 0x15653
-  __TEXT.__objc_methname: 0x153cf6
-  __TEXT.__objc_methtype: 0x3f093
-  __TEXT.__objc_stubs: 0xfbb20
+  __TEXT.__objc_classname: 0x15673
+  __TEXT.__objc_methname: 0x153d31
+  __TEXT.__objc_methtype: 0x3f096
+  __TEXT.__objc_stubs: 0xfbba0
   __DATA_CONST.__got: 0x4f10
-  __DATA_CONST.__const: 0xa160
+  __DATA_CONST.__const: 0xa1a0
   __DATA_CONST.__objc_classlist: 0x4798
   __DATA_CONST.__objc_nlclslist: 0x20
   __DATA_CONST.__objc_catlist: 0x1e0
-  __DATA_CONST.__objc_protolist: 0xf88
+  __DATA_CONST.__objc_protolist: 0xf90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4cad8
-  __DATA_CONST.__objc_protorefs: 0x550
+  __DATA_CONST.__objc_selrefs: 0x4caf0
+  __DATA_CONST.__objc_protorefs: 0x558
   __DATA_CONST.__objc_superrefs: 0x3cd0
   __DATA_CONST.__objc_arraydata: 0x4050
   __AUTH_CONST.__auth_got: 0x7ed8
-  __AUTH_CONST.__const: 0x360b0
+  __AUTH_CONST.__const: 0x360a0
   __AUTH_CONST.__cfstring: 0x976c0
-  __AUTH_CONST.__objc_const: 0xf2f00
+  __AUTH_CONST.__objc_const: 0xf2f60
   __AUTH_CONST.__objc_intobj: 0x2d00
   __AUTH_CONST.__objc_dictobj: 0x7a8
   __AUTH_CONST.__objc_doubleobj: 0x3c0

   __AUTH_CONST.__objc_floatobj: 0x20
   __AUTH.__objc_data: 0xf420
   __AUTH.__data: 0x4248
-  __DATA.__objc_ivar: 0x72bc
-  __DATA.__data: 0x10648
+  __DATA.__objc_ivar: 0x72c0
+  __DATA.__data: 0x106a8
   __DATA.__crash_info: 0x40
   __DATA.__bss: 0x2b328
   __DATA.__common: 0xee4
-  __DATA_DIRTY.__objc_ivar: 0x44bc
+  __DATA_DIRTY.__objc_ivar: 0x44c0
   __DATA_DIRTY.__objc_data: 0x22970
   __DATA_DIRTY.__data: 0xab8
   __DATA_DIRTY.__common: 0x1e0
-  __DATA_DIRTY.__bss: 0x4c28
+  __DATA_DIRTY.__bss: 0x4c30
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate
   - /System/Library/Frameworks/Accessibility.framework/Versions/A/Accessibility
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 87278
-  Symbols:   147577
-  CStrings:  83025
+  Functions: 87301
+  Symbols:   147610
+  CStrings:  83057
 
Symbols:
+ -[NSPersistentUIFileManager _createPersistentStateDirectoryForURL:]
+ -[NSPersistentUIFileManager _createPersistentStateDirectoryIfNeeded]
+ -[NSPersistentUIFileManager discardPersistentStateKeepingCrashData:]
+ -[NSPersistentUIFileManager elideAllWriting]
+ -[NSPersistentUIFileManager writeRecords:withWindowInfos:flushingStaleData:]
+ -[NSPersistentUILocalStorageClient discardPersistentStateKeepingCrashData:]
+ -[NSPersistentUILocalStorageClient writeRecords:withWindowInfos:flushingStaleData:]
+ -[NSPersistentUIRecord approximateWrittenSize]
+ -[NSPersistentUIRemoteStorageClient _shouldElideWrites]
+ -[NSPersistentUIRemoteStorageClient discardPersistentStateKeepingCrashData:]
+ -[NSPersistentUIRemoteStorageClient permanentlyElideAllWriting]
+ -[NSPersistentUIRemoteStorageClient writeRecords:withWindowInfos:flushingStaleData:]
+ -[NSPersistentUIStorageService discardPersistentStateKeepingCrashData:]
+ -[NSPersistentUIStorageService elideAllWriting]
+ -[NSPersistentUIStorageService writeRecords:withWindowInfos:flushingStaleData:]
+ -[NSSavePanel _isAllowedExtension:]
+ -[NSSavePanel _preferredFilenameExtension]
+ -[_NSPersistentUIStorageServiceListener _activeConnectionForURL:]
+ -[_NSPersistentUIStorageServiceListener _activeConnections]
+ -[_NSPersistentUIStorageServiceListener _addActiveConnection:forURL:]
+ -[_NSPersistentUIStorageServiceListener _removeConnectionIfActive:forURL:]
+ GCC_except_table357
+ GCC_except_table487
+ GCC_except_table495
+ GCC_except_table508
+ OBJC_IVAR_$_NSDocument._autosavingTimer
+ OBJC_IVAR_$_NSDocument._differenceDueToRecentChanges
+ OBJC_IVAR_$_NSDocument._differenceSinceSaving
+ OBJC_IVAR_$_NSDocument._disabledSuddenTermination
+ OBJC_IVAR_$_NSDocument._editors
+ OBJC_IVAR_$_NSDocument._eventMonitor
+ OBJC_IVAR_$_NSDocument._fileURLSandboxExtensionToken
+ OBJC_IVAR_$_NSDocument._hasPresentedMostRecentAutosavingError
+ OBJC_IVAR_$_NSDocument._ignoreUndoAndRedoNotifications
+ OBJC_IVAR_$_NSDocument._mostRecentAutosavingError
+ OBJC_IVAR_$_NSDocument._nonModalErrors
+ OBJC_IVAR_$_NSDocument._oldVersion
+ OBJC_IVAR_$_NSDocument._temporaryVersionStorageIdentifier
+ OBJC_IVAR_$_NSPersistentUIFileManager._attemptedPersistentStateDirectoryCreation
+ OBJC_IVAR_$_NSPersistentUIManager._approximateWrittenAmountSinceLastStaleDataFlush
+ OBJC_IVAR_$_NSPersistentUIManager._didInitialEmptying
+ OBJC_IVAR_$_NSPersistentUIManager._publicPlistChecksum
+ OBJC_IVAR_$_NSPersistentUIRemoteStorageClient._elidingWrites
+ OBJC_IVAR_$_NSPersistentUIRemoteStorageClient._queue
+ OBJC_IVAR_$__NSPersistentUIStorageServiceListener._activeConnectionByURL
+ OBJC_IVAR_$__NSPersistentUIStorageServiceListener._lock
+ __50-[NSPersistentUIFileManager writePublicPlistData:]_block_invoke
+ __57-[_NSPersistentUIStorageServiceListener setUpConnection:]_block_invoke
+ __NSApproximateWrittenSizeForEncodedKeyedState
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSPersistentUIStorageXPCClient
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSPersistentUIStorageXPCClient
+ __OBJC_LABEL_PROTOCOL_$_NSPersistentUIStorageXPCClient
+ __OBJC_PROTOCOL_$_NSPersistentUIStorageXPCClient
+ __OBJC_PROTOCOL_REFERENCE_$_NSPersistentUIStorageXPCClient
+ ___170-[NSPersistentUIRemoteStorageClient writeWindowSnapshot:length:width:height:bytesPerRow:encryptingWithKey:uuid:checkChecksum:forWindowID:synchronously:completionHandler:]_block_invoke_2
+ ___46-[NSPersistentUIRecord approximateWrittenSize]_block_invoke
+ ___50-[NSPersistentUIFileManager writePublicPlistData:]_block_invoke
+ ___50-[NSPersistentUIRemoteStorageClient readCrashData]_block_invoke_2
+ ___52-[NSPersistentUIRemoteStorageClient writeCrashData:]_block_invoke_2
+ ___53-[NSPersistentUIRemoteStorageClient discardCrashData]_block_invoke_2
+ ___58-[NSPersistentUIRemoteStorageClient writePublicPlistData:]_block_invoke_2
+ ___63-[NSPersistentUIRemoteStorageClient deleteSnapshotForWindowID:]_block_invoke_2
+ ___67-[NSPersistentUIRemoteStorageClient preserveStateDirectoryAtLaunch]_block_invoke_2
+ ___68-[NSPersistentUIFileManager discardPersistentStateKeepingCrashData:]_block_invoke
+ ___70-[NSPersistentUIRemoteStorageClient finishPendingChangesSynchronously]_block_invoke_2
+ ___75-[NSPersistentUILocalStorageClient discardPersistentStateKeepingCrashData:]_block_invoke
+ ___76-[NSPersistentUIFileManager writeRecords:withWindowInfos:flushingStaleData:]_block_invoke
+ ___76-[NSPersistentUIRemoteStorageClient discardPersistentStateKeepingCrashData:]_block_invoke
+ ___76-[NSPersistentUIRemoteStorageClient discardPersistentStateKeepingCrashData:]_block_invoke_2
+ ___79-[NSPersistentUIRemoteStorageClient finishPendingChangesWithCompletionHandler:]_block_invoke_2
+ ___83-[NSPersistentUILocalStorageClient writeRecords:withWindowInfos:flushingStaleData:]_block_invoke
+ ___84-[NSPersistentUIRemoteStorageClient writeRecords:withWindowInfos:flushingStaleData:]_block_invoke
+ ___84-[NSPersistentUIRemoteStorageClient writeRecords:withWindowInfos:flushingStaleData:]_block_invoke_2
+ ____NSApproximateWrittenSizeForEncodedKeyedState_block_invoke
+ ___block_descriptor_110_ea8_32s40s48s56bs_e5_v8?0l
+ ___block_descriptor_33_e18_B16?0"NSString"8l
+ ___block_descriptor_40_ea8_32r_e25_v32?0"NSString"816^B24l
+ ___block_descriptor_44_e5_q8?0l
+ _objc_msgSend$_activeConnectionForURL:
+ _objc_msgSend$_activeConnections
+ _objc_msgSend$_addActiveConnection:forURL:
+ _objc_msgSend$_createPersistentStateDirectoryForURL:
+ _objc_msgSend$_createPersistentStateDirectoryIfNeeded
+ _objc_msgSend$_removeConnectionIfActive:forURL:
+ _objc_msgSend$approximateWrittenSize
+ _objc_msgSend$discardPersistentStateKeepingCrashData:
+ _objc_msgSend$elideAllWriting
+ _objc_msgSend$exportedObject
+ _objc_msgSend$permanentlyElideAllWriting
+ _objc_msgSend$writeRecords:withWindowInfos:flushingStaleData:
- -[NSPersistentUIFileManager _refreshStateDirectoryIfNecessary]
- -[NSPersistentUIFileManager _writePublicPlistData:]
- -[NSPersistentUIFileManager _writeRecords:withWindowInfos:flushingStaleData:]
- -[NSPersistentUIFileManager discardPersistentState]
- -[NSPersistentUIFileManager tryCreatingPersistentStateDirectoryForURL:]
- -[NSPersistentUIFileManager writeRecords:withWindowInfos:]
- -[NSPersistentUILocalStorageClient discardPersistentState]
- -[NSPersistentUILocalStorageClient writeRecords:withWindowInfos:]
- -[NSPersistentUIRemoteStorageClient discardPersistentState]
- -[NSPersistentUIRemoteStorageClient writeRecords:withWindowInfos:]
- -[NSPersistentUIStorageService discardPersistentState]
- -[NSPersistentUIStorageService writeRecords:withWindowInfos:]
- -[NSRemoteSavePanel _restoreDefaultSettings]
- -[_NSPersistentUIStorageServiceListener _addConnectionQueue:]
- -[_NSPersistentUIStorageServiceListener _removeConnectionQueue:]
- GCC_except_table382
- GCC_except_table511
- GCC_except_table515
- GCC_except_table521
- OBJC_IVAR_$_NSDocumentMoreIVars.autosavingTimer
- OBJC_IVAR_$_NSDocumentMoreIVars.differenceDueToRecentChanges
- OBJC_IVAR_$_NSDocumentMoreIVars.differenceSinceSaving
- OBJC_IVAR_$_NSDocumentMoreIVars.disabledSuddenTermination
- OBJC_IVAR_$_NSDocumentMoreIVars.editors
- OBJC_IVAR_$_NSDocumentMoreIVars.eventMonitor
- OBJC_IVAR_$_NSDocumentMoreIVars.fileURLSandboxExtensionToken
- OBJC_IVAR_$_NSDocumentMoreIVars.hasPresentedMostRecentAutosavingError
- OBJC_IVAR_$_NSDocumentMoreIVars.ignoreUndoAndRedoNotifications
- OBJC_IVAR_$_NSDocumentMoreIVars.mostRecentAutosavingError
- OBJC_IVAR_$_NSDocumentMoreIVars.nonModalErrors
- OBJC_IVAR_$_NSDocumentMoreIVars.oldVersion
- OBJC_IVAR_$_NSDocumentMoreIVars.temporaryVersionStorageIdentifier
- OBJC_IVAR_$_NSPersistentUIFileManager._currentFileSize
- OBJC_IVAR_$_NSPersistentUIFileManager._fileSizeAfterLastRewrite
- OBJC_IVAR_$_NSPersistentUIFileManager._publicPlistChecksum
- OBJC_IVAR_$_NSPersistentUIFileManager._stateDirectoryHasBeenRefreshed
- OBJC_IVAR_$_NSPersistentUIFileManager._stateFileHasBeenCreated
- OBJC_IVAR_$__NSPersistentUIStorageServiceListener._connectionQueues
- OBJC_IVAR_$__NSWritingToolsData._forceAcceptSuggestion
- __51-[NSPersistentUIFileManager _writePublicPlistData:]_block_invoke
- __59-[NSPersistentUIRemoteStorageClient stateDirectoryAtLaunch]_block_invoke
- ___51-[NSPersistentUIFileManager _writePublicPlistData:]_block_invoke
- ___58-[NSPersistentUILocalStorageClient discardPersistentState]_block_invoke
- ___59-[NSPersistentUIRemoteStorageClient discardPersistentState]_block_invoke
- ___65-[NSPersistentUILocalStorageClient writeRecords:withWindowInfos:]_block_invoke
- ___66-[NSPersistentUIRemoteStorageClient writeRecords:withWindowInfos:]_block_invoke
- ___71-[NSPersistentUIFileManager tryCreatingPersistentStateDirectoryForURL:]_block_invoke
- ___77-[NSPersistentUIFileManager _writeRecords:withWindowInfos:flushingStaleData:]_block_invoke
- ___block_descriptor_44_ea8_32s_e5_q8?0l
- _objc_msgSend$_addConnectionQueue:
- _objc_msgSend$_refreshStateDirectoryIfNecessary
- _objc_msgSend$_removeConnectionQueue:
- _objc_msgSend$_writePublicPlistData:
- _objc_msgSend$_writeRecords:withWindowInfos:flushingStaleData:
- _objc_msgSend$discardPersistentState
- _objc_msgSend$tryCreatingPersistentStateDirectoryForURL:
- _objc_msgSend$writeRecords:withWindowInfos:
CStrings:
+ "!self->_fetchingStateDirectoryAtLaunch"
+ "%{public}s Emptying for initial flush."
+ "%{public}s Error while eliding writing: %@"
+ "%{public}s Rewrote file (size is now %lu bytes)"
+ "%{public}s Service aleady exists for url %{private}@. Eliding writes from previous service for %{public}@. New connection is %{public}@."
+ "%{public}s Wrote %lu bytes"
+ "%{public}s connection=%{public}@"
+ "%{public}s self=%p connection=%{public}@"
+ "%{public}s self=%p connection=%{public}@ fileManager=nil result=0"
+ "%{public}s self=%p connection=%{public}@ keepCrashData=%d"
+ "%{public}s self=%p connection=%{public}@ result=%d"
+ "%{public}s self=%p connection=%{public}@ stateDirectory=%p"
+ "%{public}s self=%p persistentStateDirectoryURL=%{private}@ fileManager=%p"
+ "%{public}s shouldRestoreState=%d hasPersistentStateToRestore=%d shouldStillRestoreStateAfterPrompting=%d"
+ "%{public}s url=%{private}@ connection=%{public}@"
+ "-[NSApplication _reopenWindowsAsNecessaryIncludingRestorableState:withFullFidelity:completionHandler:]"
+ "-[NSPersistentUIFileManager writePublicPlistData:]"
+ "-[NSPersistentUIFileManager writeRecords:withWindowInfos:flushingStaleData:]"
+ "-[NSPersistentUIRemoteStorageClient deleteSnapshotForWindowID:]_block_invoke_2"
+ "-[NSPersistentUIRemoteStorageClient discardCrashData]_block_invoke_2"
+ "-[NSPersistentUIRemoteStorageClient discardPersistentStateKeepingCrashData:]_block_invoke_2"
+ "-[NSPersistentUIRemoteStorageClient finishPendingChangesSynchronously]_block_invoke_2"
+ "-[NSPersistentUIRemoteStorageClient permanentlyElideAllWriting]"
+ "-[NSPersistentUIRemoteStorageClient readCrashData]_block_invoke_2"
+ "-[NSPersistentUIRemoteStorageClient writeCrashData:]_block_invoke_2"
+ "-[NSPersistentUIRemoteStorageClient writePublicPlistData:]_block_invoke_2"
+ "-[NSPersistentUIRemoteStorageClient writeRecords:withWindowInfos:flushingStaleData:]_block_invoke_2"
+ "-[NSPersistentUIStorageService deleteSnapshotForWindowID:]"
+ "-[NSPersistentUIStorageService discardCrashData]"
+ "-[NSPersistentUIStorageService discardPersistentStateKeepingCrashData:]"
+ "-[NSPersistentUIStorageService elideAllWriting]"
+ "-[NSPersistentUIStorageService finishPendingChangesWithCompletionHandler:]"
+ "-[NSPersistentUIStorageService initWithPersistentStateDirectoryURL:]"
+ "-[NSPersistentUIStorageService invalidate]"
+ "-[NSPersistentUIStorageService preserveStateDirectoryWithCompletionHandler:]"
+ "-[NSPersistentUIStorageService readCrashDataWithCompletionHandler:]"
+ "-[NSPersistentUIStorageService writeCrashData:]"
+ "-[NSPersistentUIStorageService writePublicPlistData:]"
+ "-[NSPersistentUIStorageService writeRecords:withWindowInfos:flushingStaleData:]"
+ "-[NSPersistentUIStorageService writeWindowSnapshotData:width:height:bytesPerRow:encryptingWithKey:uuid:checkChecksum:forWindowID:completionHandler:]"
+ "-[_NSPersistentUIStorageServiceListener _addActiveConnection:forURL:]"
+ "-[_NSPersistentUIStorageServiceListener _removeConnectionIfActive:forURL:]"
+ "-[_NSPersistentUIStorageServiceListener setUpConnection:]"
+ "-[_NSPersistentUIStorageServiceListener setUpConnection:]_block_invoke"
+ "NSPersistentUIApproximateSizeOfWritesUntilStaleDataIsFlushed"
+ "NSPersistentUIRemoteStorageClient.m"
+ "NSPersistentUIStorageXPCClient"
+ "_activeConnectionByURL"
+ "_activeConnectionForURL:"
+ "_activeConnections"
+ "_addActiveConnection:forURL:"
+ "_approximateWrittenAmountSinceLastStaleDataFlush"
+ "_attemptedPersistentStateDirectoryCreation"
+ "_autosavingTimer"
+ "_createPersistentStateDirectoryForURL:"
+ "_createPersistentStateDirectoryIfNeeded"
+ "_didInitialEmptying"
+ "_differenceDueToRecentChanges"
+ "_differenceSinceSaving"
+ "_disabledSuddenTermination"
+ "_elidingWrites"
+ "_fileURLSandboxExtensionToken"
+ "_hasPresentedMostRecentAutosavingError"
+ "_ignoreUndoAndRedoNotifications"
+ "_mostRecentAutosavingError"
+ "_removeConnectionIfActive:forURL:"
+ "approximateWrittenSize"
+ "discardPersistentStateKeepingCrashData:"
+ "elideAllWriting"
+ "permanentlyElideAllWriting"
+ "v36@0:8@\"NSArray\"16@\"NSArray\"24B32"
+ "writeRecords:withWindowInfos:flushingStaleData:"
- "%{public}s Failed to get exclusive access to file at URL '%@'.  Another instance of the app may be running.  This one lost."
- "%{public}s Rewrote file, saving %lu bytes (size is now %lu bytes)"
- "%{public}s Wrote %lu bytes (file size is now %lu)"
- "-[NSPersistentUIFileManager _writePublicPlistData:]"
- "-[NSPersistentUIFileManager _writeRecords:withWindowInfos:flushingStaleData:]"
- "-[NSPersistentUIRemoteStorageClient deleteSnapshotForWindowID:]_block_invoke"
- "-[NSPersistentUIRemoteStorageClient discardCrashData]_block_invoke"
- "-[NSPersistentUIRemoteStorageClient discardPersistentState]_block_invoke"
- "-[NSPersistentUIRemoteStorageClient finishPendingChangesSynchronously]_block_invoke"
- "-[NSPersistentUIRemoteStorageClient readCrashData]_block_invoke"
- "-[NSPersistentUIRemoteStorageClient writeCrashData:]_block_invoke"
- "-[NSPersistentUIRemoteStorageClient writePublicPlistData:]_block_invoke"
- "-[NSPersistentUIRemoteStorageClient writeRecords:withWindowInfos:]_block_invoke"
- "Cancelling outstanding rollover to hide overlay"
- "_addConnectionQueue:"
- "_connectionQueues"
- "_fileSizeAfterLastRewrite"
- "_forceAcceptSuggestion"
- "_refreshStateDirectoryIfNecessary"
- "_removeConnectionQueue:"
- "_stateDirectoryHasBeenRefreshed"
- "_stateFileHasBeenCreated"
- "_writePublicPlistData:"
- "_writeRecords:withWindowInfos:flushingStaleData:"
- "autosavingTimer"
- "differenceDueToRecentChanges"
- "differenceSinceSaving"
- "disabledSuddenTermination"
- "discardPersistentState"
- "editors"
- "fileURLSandboxExtensionToken"
- "hasPresentedMostRecentAutosavingError"
- "ignoreUndoAndRedoNotifications"
- "mostRecentAutosavingError"
- "nonModalErrors"
- "oldVersion"
- "temporaryVersionStorageIdentifier"
- "tryCreatingPersistentStateDirectoryForURL:"
- "v32@0:8@\"NSArray\"16@\"NSArray\"24"
- "writeRecords:withWindowInfos:"
```
