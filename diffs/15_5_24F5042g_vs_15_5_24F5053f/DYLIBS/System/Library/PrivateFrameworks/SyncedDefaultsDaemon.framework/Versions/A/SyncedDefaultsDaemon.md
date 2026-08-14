## SyncedDefaultsDaemon

> `/System/Library/PrivateFrameworks/SyncedDefaultsDaemon.framework/Versions/A/SyncedDefaultsDaemon`

```diff

-2260.0.0.0.0
-  __TEXT.__text: 0x3c9b8
+2260.11.0.0.0
+  __TEXT.__text: 0x3cc7c
   __TEXT.__auth_stubs: 0x970
-  __TEXT.__objc_methlist: 0x1698
+  __TEXT.__objc_methlist: 0x16b0
   __TEXT.__const: 0x136
-  __TEXT.__gcc_except_tab: 0x10f4
+  __TEXT.__gcc_except_tab: 0x1104
   __TEXT.__cstring: 0x2169
-  __TEXT.__oslogstring: 0x6c56
+  __TEXT.__oslogstring: 0x6ce1
   __TEXT.__dlopen_cstrs: 0xb5
   __TEXT.__swift5_typeref: 0x5
-  __TEXT.__unwind_info: 0xbf0
+  __TEXT.__unwind_info: 0xbf8
   __TEXT.__objc_classname: 0x1c8
-  __TEXT.__objc_methname: 0x5cc1
+  __TEXT.__objc_methname: 0x5d03
   __TEXT.__objc_methtype: 0xd3b
-  __TEXT.__objc_stubs: 0x4ee0
+  __TEXT.__objc_stubs: 0x4f20
   __DATA_CONST.__got: 0x430
   __DATA_CONST.__const: 0x1c0
   __DATA_CONST.__objc_classlist: 0x68
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x16f0
+  __DATA_CONST.__objc_selrefs: 0x1700
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x38
   __DATA_CONST.__objc_arraydata: 0x1f8

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1167
-  Symbols:   2012
-  CStrings:  1885
+  Functions: 1171
+  Symbols:   2019
+  CStrings:  1889
 
Symbols:
+ -[SYDCoreDataStore _loadPersistentContainerWithError:]
+ -[SYDCoreDataStore _persistentContainerWithError:]
+ GCC_except_table104
+ __42-[SYDCoreDataStore destroyPersistentStore]_block_invoke
+ __54-[SYDCoreDataStore _loadPersistentContainerWithError:]_block_invoke
+ __70-[SYDSyncManager performOneTimeDataSeparatedLocalDataResetIfNecessary]_block_invoke
+ ___54-[SYDCoreDataStore _loadPersistentContainerWithError:]_block_invoke
+ _objc_msgSend$_loadPersistentContainerWithError:
+ _objc_msgSend$_persistentContainerWithError:
- GCC_except_table102
- __49-[SYDCoreDataStore persistentContainerWithError:]_block_invoke
CStrings:
+ "Error calling setHasPerformedOneTimeDataSeparatedLocalDataReset: %@"
+ "Failed to access persistent store immediately after reset"
+ "Finished resetting persistent store"
+ "_loadPersistentContainerWithError:"
+ "_persistentContainerWithError:"
- "Reset persistent store"
```
