## csimporter

> `/System/Applications/System Settings.app/Contents/PlugIns/csimporter.appex/Contents/MacOS/csimporter`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

```diff

-644.3.6.0.0
-  __TEXT.__text: 0xe2fe8
-  __TEXT.__auth_stubs: 0x2470
+644.4.1.0.0
+  __TEXT.__text: 0xc34b0
+  __TEXT.__auth_stubs: 0x23b0
   __TEXT.__objc_methlist: 0xab0
-  __TEXT.__const: 0x31b4
-  __TEXT.__cstring: 0x60a3
-  __TEXT.__swift5_typeref: 0x1d98
-  __TEXT.__objc_methname: 0x2319
-  __TEXT.__constg_swiftt: 0x2f64
-  __TEXT.__swift5_reflstr: 0x1813
-  __TEXT.__swift5_fieldmd: 0x1544
-  __TEXT.__oslogstring: 0x2f5
-  __TEXT.__swift5_capture: 0xe7c
+  __TEXT.__const: 0x3344
+  __TEXT.__cstring: 0x5b03
+  __TEXT.__swift5_typeref: 0x1dbc
+  __TEXT.__objc_methname: 0x2283
+  __TEXT.__constg_swiftt: 0x2ef0
+  __TEXT.__swift5_reflstr: 0x1743
+  __TEXT.__swift5_fieldmd: 0x14b0
+  __TEXT.__oslogstring: 0x100
+  __TEXT.__swift5_capture: 0xe10
   __TEXT.__swift5_builtin: 0x14
-  __TEXT.__swift5_proto: 0x168
-  __TEXT.__swift5_types: 0x12c
+  __TEXT.__swift5_proto: 0x164
+  __TEXT.__swift5_types: 0x128
   __TEXT.__objc_classname: 0x91
   __TEXT.__objc_methtype: 0xa25
   __TEXT.__swift5_assocty: 0x2f8
-  __TEXT.__swift_as_entry: 0x100
+  __TEXT.__swift_as_entry: 0xfc
   __TEXT.__swift5_protos: 0x10
-  __TEXT.__swift_as_ret: 0x74
-  __TEXT.__unwind_info: 0x1ff0
-  __TEXT.__eh_frame: 0x40b0
-  __DATA_CONST.__auth_got: 0x1238
-  __DATA_CONST.__got: 0x6b0
-  __DATA_CONST.__auth_ptr: 0x908
-  __DATA_CONST.__const: 0x3630
-  __DATA_CONST.__objc_classlist: 0x168
+  __TEXT.__swift_as_ret: 0x6c
+  __TEXT.__unwind_info: 0x1f98
+  __TEXT.__eh_frame: 0x3fa8
+  __DATA_CONST.__auth_got: 0x11d8
+  __DATA_CONST.__got: 0x688
+  __DATA_CONST.__auth_ptr: 0x898
+  __DATA_CONST.__const: 0x3540
+  __DATA_CONST.__objc_classlist: 0x160
   __DATA_CONST.__objc_protolist: 0xc8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x90
-  __DATA.__objc_const: 0x4db0
-  __DATA.__objc_selrefs: 0xbb8
-  __DATA.__objc_data: 0x2210
-  __DATA.__data: 0x4a48
-  __DATA.__common: 0x278
+  __DATA.__objc_const: 0x4c00
+  __DATA.__objc_selrefs: 0xb88
+  __DATA.__objc_data: 0x2180
+  __DATA.__data: 0x4988
+  __DATA.__common: 0x238
   __DATA.__bss: 0x2c10
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 2386
-  Symbols:   280
-  CStrings:  1168
+  Functions: 2367
+  Symbols:   270
+  CStrings:  1110
 
Symbols:
- _CFPreferencesSetValue
- _CFPreferencesSynchronize
- _CGSSessionCopyCurrentSessionProperties
- _OBJC_CLASS_$_NSDateFormatter
- _getuid
- _kCFPreferencesCurrentHost
- _notify_cancel
- _notify_get_state
- _notify_register_check
- _notify_set_state
CStrings:
+ "%s:%ld %s %{public}s"
+ "_alwaysShowScrollBars"
+ "_filteredSidebarList"
+ "_sidebarList"
+ "_viewMenuItems"
+ "cs-indexing done"
+ "filterSidebarList(scrollToTop:)"
- "%{private}s"
- "-indexing completed time"
- "-indexing start time"
- "-indexing status"
- ". Perform full index."
- "Added new index items"
- "Added new index items for "
- "Another process is already indexing. Skipping this one."
- "CGSSessionUniqueSessionUUID"
- "Checking user ID: "
- "Deleted old index items. "
- "Error adding new index items: "
- "Error deleting old index items: "
- "Error occurred while ending batch: "
- "Error while fetching clientState "
- "Failed to delete old index items for "
- "Failed to index new items for "
- "INDEXING"
- "Indexing coordinator cancelled"
- "Indexing coordinator registered"
- "Indexing started"
- "Indexing stopped"
- "Is role account: "
- "NOT_INDEXING"
- "Only indexing legacy panes."
- "Perform full index."
- "Running as role account, so do nothing."
- "Search String has changed while filtering sidebar list, ignoring update."
- "Setting filteredSidebarList to resolved results"
- "Setting filteredSidebarList to sidebarList"
- "_TtC10csimporter19IndexingCoordinator"
- "addToIndex(_:setting:representation:statusDict:)"
- "alwaysShowScrollBars"
- "beginIndexBatch"
- "cancel called but not registered"
- "com.apple.settings.indexingCoordinator."
- "endIndexBatchWithClientState:completionHandler:"
- "fetchLastClientStateWithCompletionHandler:"
- "filterSidebarList(searchString:scrollToTop:)"
- "filteredSidebarList"
- "fullIndexComplete"
- "indexingCompleteTimeKey"
- "indexingInProgress called but not registered"
- "indexingStartTimeKey"
- "indexingStatusKey"
- "logger"
- "notifyName"
- "notify_cancel returned error code %u"
- "notify_get_state returned error code %u"
- "notify_register_check returned error code %u"
- "notify_set_state returned error code %u"
- "processName"
- "register called but already registered"
- "registered"
- "runningAsRoleAccount"
- "searchStringIsEmpty"
- "searchableIndex(_:reindexAllSearchableItemsWithAcknowledgementHandler:)"
- "setDateFormat:"
- "setIndexingState called but not registered"
- "sidebarList"
- "stringFromDate:"
- "uidIsRoleAccount(_:)"
- "v24@?0@\"NSData\"8@\"NSError\"16"
- "viewMenuItems"
- "yyyy-MM-dd HH:mm:ssXXXXX"
```
