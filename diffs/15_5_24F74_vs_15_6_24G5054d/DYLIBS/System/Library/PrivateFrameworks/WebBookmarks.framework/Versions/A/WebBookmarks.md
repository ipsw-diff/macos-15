## WebBookmarks

> `/System/Library/PrivateFrameworks/WebBookmarks.framework/Versions/A/WebBookmarks`

```diff

-621.2.5.11.8
-  __TEXT.__text: 0xa7188
+621.3.6.1.0
+  __TEXT.__text: 0xa79f4
   __TEXT.__auth_stubs: 0xb30
   __TEXT.__objc_methlist: 0x810c
   __TEXT.__const: 0x306
-  __TEXT.__gcc_except_tab: 0xa860
-  __TEXT.__cstring: 0xd95c
-  __TEXT.__oslogstring: 0x7812
+  __TEXT.__gcc_except_tab: 0xa978
+  __TEXT.__cstring: 0xd93c
+  __TEXT.__oslogstring: 0x791c
   __TEXT.__dlopen_cstrs: 0x50
   __TEXT.__constg_swiftt: 0x60
   __TEXT.__swift5_typeref: 0x9
   __TEXT.__swift5_reflstr: 0x1c
   __TEXT.__swift5_fieldmd: 0x1c
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x3f08
+  __TEXT.__unwind_info: 0x3f20
   __TEXT.__objc_classname: 0xa21
   __TEXT.__objc_methname: 0x151b9
   __TEXT.__objc_methtype: 0x272b
   __TEXT.__objc_stubs: 0xe200
   __DATA_CONST.__got: 0x748
-  __DATA_CONST.__const: 0xc40
+  __DATA_CONST.__const: 0xc38
   __DATA_CONST.__objc_classlist: 0x220
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x100

   __DATA_CONST.__objc_arraydata: 0x358
   __AUTH_CONST.__auth_got: 0x5b0
   __AUTH_CONST.__const: 0x36a0
-  __AUTH_CONST.__cfstring: 0x5d40
+  __AUTH_CONST.__cfstring: 0x5d20
   __AUTH_CONST.__objc_const: 0x9730
   __AUTH_CONST.__objc_arrayobj: 0xf0
   __AUTH_CONST.__objc_intobj: 0x360

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 3492
-  Symbols:   7560
-  CStrings:  5327
+  Functions: 3494
+  Symbols:   7559
+  CStrings:  5332
 
Symbols:
- _backgroundTaskExpirationContext
Functions:
~ -[WebBookmarkTabCollection _reEncodeSessionStateDataIfNeeded] : 488 -> 496
~ -[WBTab initWithBookmarkStorage:] : 272 -> 516
+ _OUTLINED_FUNCTION_0
~ -[WBTabCollection saveBrowserState:completionHandler:] : 364 -> 448
~ -[WBTabCollection insertItems:inParentWithID:afterItem:completionHandler:] : 436 -> 516
~ -[WBTabCollection insertItems:inParent:afterItem:completionHandler:] : 480 -> 560
~ -[WBTabCollection insertItemsIntoPlace:inParentWithID:completionHandler:] : 372 -> 456
~ -[WBTabCollection insertItemsIntoPlace:inParent:completionHandler:] : 420 -> 500
~ -[WBTabCollection saveItem:completionHandler:] : 364 -> 448
~ -[WBTabCollection saveItems:completionHandler:] : 364 -> 448
~ -[WBTabCollection reorderItem:afterItem:completionHandler:] : 420 -> 500
~ -[WBTabCollection reorderItemIntoPlace:completionHandler:] : 364 -> 448
~ -[WBTabCollection deleteItems:leaveTombstones:completionHandler:] : 372 -> 456
~ -[WBTabCollection updateItems:inParentWithID:completionHandler:] : 372 -> 456
~ -[WBTabCollection setFrequentlyVisitedSites:forProfileWithIdentifier:completionHandler:] : 452 -> 532
~ -[WBTabCollection topScopedBookmarkListForTabGroup:] : 280 -> 548
~ -[WBTabCollection shareRecordForTabGroup:completionHandler:] : 364 -> 448
~ -[WBTabCollection setHasSharedTabGroupsWithCompletionHandler:] : 304 -> 388
~ -[WBTabCollection getActiveParticipantsInTab:completionHandler:] : 364 -> 448
~ -[WBTabCollection deleteWindowStates:completionHandler:] : 364 -> 448
~ -[WBTabCollection saveWindowState:completionHandler:] : 364 -> 448
~ -[WBTabCollection saveWindowRestorationArchiveData:forWindowUUIDString:completionHandler:] : 568 -> 648
~ -[WBReusableTabManager cache:willEvictObject:] : 424 -> 420
~ -[WBTabGroupManager initWithCollection:] : 1428 -> 1396
~ -[WBTabGroupManager dealloc] : 124 -> 96
+ -[WBTabGroupManager setShouldPrepareBackgroundTaskExpiration:]
~ -[WBTabGroupManager observeValueForKeyPath:ofObject:change:context:] : 336 -> 200
- -[WBTabGroupManager isBroadcastingPresenceUpdates]
- _OUTLINED_FUNCTION_1
~ -[WBTab initWithBookmarkStorage:].cold.1 : 180 -> 164
+ -[WBTab initWithBookmarkStorage:].cold.2
+ -[WBTabGroup initWithBookmarkStorage:lastSelectedTabUUID:kind:].cold.1
CStrings:
+ "Background task will expire soon. Block performing database task"
+ "Background task will expire soon. Block reading bookmarks. %{public}@"
+ "WBTab initialized with a malformed UUID %{public}@"
+ "WBTab must be backed by a bookmark %{public}@"
+ "WBTab must have a UUID %{public}@"
```
