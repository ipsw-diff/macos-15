## CalendarDaemon

> `/System/Library/PrivateFrameworks/CalendarDaemon.framework/Versions/A/CalendarDaemon`

```diff

-1194.6.2.0.0
-  __TEXT.__text: 0x70fac
+1194.7.1.0.0
+  __TEXT.__text: 0x7102c
   __TEXT.__auth_stubs: 0x3410
-  __TEXT.__objc_methlist: 0x5b7c
+  __TEXT.__objc_methlist: 0x5b8c
   __TEXT.__cstring: 0x6ce9
   __TEXT.__const: 0x150
-  __TEXT.__oslogstring: 0x7daa
+  __TEXT.__oslogstring: 0x7df9
   __TEXT.__gcc_except_tab: 0x1a74
   __TEXT.__dlopen_cstrs: 0xc0
   __TEXT.__ustring: 0x4
   __TEXT.__unwind_info: 0x1960
   __TEXT.__objc_classname: 0x13cf
-  __TEXT.__objc_methname: 0xd9cd
+  __TEXT.__objc_methname: 0xd9ee
   __TEXT.__objc_methtype: 0x6367
   __TEXT.__objc_stubs: 0x8c60
   __DATA_CONST.__got: 0x908

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x1b8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2db0
+  __DATA_CONST.__objc_selrefs: 0x2db8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x270
   __DATA_CONST.__objc_arraydata: 0x350
   __AUTH_CONST.__auth_got: 0x1a18
   __AUTH_CONST.__const: 0x22c0
   __AUTH_CONST.__cfstring: 0x7540
-  __AUTH_CONST.__objc_const: 0xb588
+  __AUTH_CONST.__objc_const: 0xb5a0
   __AUTH_CONST.__objc_intobj: 0x420
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x18

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 2068
-  Symbols:   6144
-  CStrings:  4177
+  Functions: 2069
+  Symbols:   6145
+  CStrings:  4180
 
Symbols:
+ +[CADSpotlightIndexer calDBChangeFetchBatchSize]
+ __OBJC_$_CLASS_PROP_LIST_CADSpotlightIndexer
- _OUTLINED_FUNCTION_8
Functions:
~ ___41-[CADSpotlightIndexer _incrementalUpdate]_block_invoke : 1252 -> 1304
+ +[CADSpotlightIndexer calDBChangeFetchBatchSize]
~ _OUTLINED_FUNCTION_4 : 32 -> 12
~ _OUTLINED_FUNCTION_6 : 12 -> 16
~ _OUTLINED_FUNCTION_7 : 16 -> 32
- _OUTLINED_FUNCTION_8
~ __41-[CADSpotlightIndexer _incrementalUpdate]_block_invoke.cold.5 : 124 -> 52
+ __41-[CADSpotlightIndexer _incrementalUpdate]_block_invoke.cold.6
~ __40-[CADSpotlightIndexer _deleteFromIndex:]_block_invoke.cold.1 : 116 -> 128
~ __61-[CADSpotlightIndexer _sendSpotlightUpdates:deletes:toIndex:]_block_invoke.161.cold.1 : 116 -> 128
~ -[CADSpotlightIndexer reindexAllItemsForBundleID:protectionClass:acknowledgementHandler:].cold.1 : 108 -> 120
~ -[CADSpotlightIndexer provideDataForBundleID:protectionClass:itemIdentifier:typeIdentifier:options:completionHandler:].cold.1 : 108 -> 120
CStrings:
+ "Failed to get personaID for aux database, not advancing change sequence number"
+ "Ti,R,N"
+ "calDBChangeFetchBatchSize"
```
