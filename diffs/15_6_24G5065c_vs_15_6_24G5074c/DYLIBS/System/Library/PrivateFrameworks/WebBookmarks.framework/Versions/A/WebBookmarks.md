## WebBookmarks

> `/System/Library/PrivateFrameworks/WebBookmarks.framework/Versions/A/WebBookmarks`

```diff

-621.3.7.0.0
-  __TEXT.__text: 0xa79f4
+621.3.8.0.0
+  __TEXT.__text: 0xa852c
   __TEXT.__auth_stubs: 0xb30
-  __TEXT.__objc_methlist: 0x810c
+  __TEXT.__objc_methlist: 0x814c
   __TEXT.__const: 0x306
-  __TEXT.__gcc_except_tab: 0xa978
-  __TEXT.__cstring: 0xd93c
-  __TEXT.__oslogstring: 0x791c
+  __TEXT.__gcc_except_tab: 0xaa94
+  __TEXT.__cstring: 0xd98c
+  __TEXT.__oslogstring: 0x7b6f
   __TEXT.__dlopen_cstrs: 0x50
   __TEXT.__constg_swiftt: 0x60
   __TEXT.__swift5_typeref: 0x9
   __TEXT.__swift5_reflstr: 0x1c
   __TEXT.__swift5_fieldmd: 0x1c
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x3f20
+  __TEXT.__unwind_info: 0x3f60
   __TEXT.__objc_classname: 0xa21
-  __TEXT.__objc_methname: 0x151b9
+  __TEXT.__objc_methname: 0x15204
   __TEXT.__objc_methtype: 0x272b
-  __TEXT.__objc_stubs: 0xe200
+  __TEXT.__objc_stubs: 0xe260
   __DATA_CONST.__got: 0x748
   __DATA_CONST.__const: 0xc38
   __DATA_CONST.__objc_classlist: 0x220
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x100
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4a30
+  __DATA_CONST.__objc_selrefs: 0x4a48
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x1c0
   __DATA_CONST.__objc_arraydata: 0x358

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 3494
-  Symbols:   7559
-  CStrings:  5332
+  Functions: 3508
+  Symbols:   7573
+  CStrings:  5343
 
Symbols:
+ -[WBTabCollection deleteWindowsNotInLastSession]
+ -[WBTabCollection tabCountForTabGroupWithUUID:]
+ -[WBTabGroupManager deleteWindowsNotInLastSession]
+ -[WBTabGroupManager tabCountForTabGroupWithUUID:]
+ -[WBWindowState copyForRecovery]
+ -[WebBookmarkTabCollection tabCountForTabGroupWithUUID:]
+ GCC_except_table106
+ GCC_except_table154
+ GCC_except_table190
+ GCC_except_table199
+ GCC_except_table204
+ GCC_except_table211
+ GCC_except_table223
+ GCC_except_table233
+ GCC_except_table237
+ GCC_except_table241
+ GCC_except_table242
+ GCC_except_table259
+ GCC_except_table260
+ GCC_except_table269
+ GCC_except_table273
+ GCC_except_table274
+ GCC_except_table294
+ GCC_except_table295
+ GCC_except_table304
+ _OUTLINED_FUNCTION_12
+ ___47-[WBTabCollection tabCountForTabGroupWithUUID:]_block_invoke
+ ___48-[WBTabCollection deleteWindowsNotInLastSession]_block_invoke
+ _objc_msgSend$deleteWindowsNotInLastSession
+ _objc_msgSend$initWithUUID:
+ _objc_msgSend$tabCountForTabGroupWithUUID:
- GCC_except_table143
- GCC_except_table155
- GCC_except_table193
- GCC_except_table194
- GCC_except_table201
- GCC_except_table213
- GCC_except_table227
- GCC_except_table239
- GCC_except_table240
- GCC_except_table243
- GCC_except_table257
- GCC_except_table258
- GCC_except_table271
- GCC_except_table285
- GCC_except_table308
- GCC_except_table314
- GCC_except_table315
CStrings:
+ "<%@: %p; activeTabGroupUUID = %@; identifier = %d; sceneID = %@; uuid = %@; restoration_archive = %lu; localTabGroup = %@<%d> with %ld tab(s), selectedTabGroup = %@, isPrivate = %d>"
+ "Cannot save bookmark: failed to get hidden ancestor count (%i) with error: %{public}@"
+ "Cannot save bookmark: failed to update order index of bookmarks during insertion (%i) with error: %{public}@"
+ "Could not reorder bookmarks in parent: %d, error: %{public}@"
+ "Deleting windowState with UUID: %{public}@"
+ "Failed to clear title words for bookmark with ID: %d"
+ "Failed to index bookmark with ID: %d"
+ "Failed to index for bookmark with ID: (%d), word_index: (%d) and error: %{public}@"
+ "Failed to save bookmark %{public}@ isFolder: %d Invalid parentID %d"
+ "Failed to update bookmark, could not add extraAttributes %{public}@"
+ "Failed to update bookmark, could not finalize sqlite statement %{public}@ with error %{public}@"
+ "Failed to update bookmark, could not prepare sqlite statement %{public}@ with error: %{public}@"
+ "copyForRecovery"
+ "deleteWindowsNotInLastSession"
+ "tabCountForTabGroupWithUUID:"
- "<%@: %p; activeTabGroupUUID = %@; identifier = %d; sceneID = %@; uuid = %@; restoration_archive = %lu>"
- "Cannot save bookmark: failed to get hidden ancestor count (%i)"
- "Cannot save bookmark: failed to update order index of bookmarks during insertion (%i)"
- "Failed to save bookmark %{public}@: Invalid parentID %d"
```
