## GeoServices

> `/System/Library/PrivateFrameworks/GeoServices.framework/Versions/A/GeoServices`

```diff

-1986.25.3.6.3
-  __TEXT.__text: 0x1706e58
+1986.26.4.18.4
+  __TEXT.__text: 0x170771c
   __TEXT.__auth_stubs: 0x2c80
   __TEXT.__objc_methlist: 0xd10fc
-  __TEXT.__gcc_except_tab: 0x8374c
+  __TEXT.__gcc_except_tab: 0x83794
   __TEXT.__const: 0x7f96e
-  __TEXT.__cstring: 0x930ce
+  __TEXT.__cstring: 0x93408
   __TEXT.__dlopen_cstrs: 0x1f9
-  __TEXT.__oslogstring: 0x1a2a5
+  __TEXT.__oslogstring: 0x1a345
   __TEXT.__ustring: 0x156
   __TEXT.__unwind_info: 0x5aca0
-  __TEXT.__objc_classname: 0x13f85
-  __TEXT.__objc_methname: 0xd399e
+  __TEXT.__objc_classname: 0x13f88
+  __TEXT.__objc_methname: 0xd39aa
   __TEXT.__objc_methtype: 0x686c9
   __TEXT.__objc_stubs: 0x74e80
   __DATA_CONST.__got: 0x3a48
-  __DATA_CONST.__const: 0x157b8
+  __DATA_CONST.__const: 0x157f0
   __DATA_CONST.__objc_classlist: 0x5878
   __DATA_CONST.__objc_catlist: 0xc8
   __DATA_CONST.__objc_protolist: 0x6d8

   __DATA_CONST.__objc_selrefs: 0x33528
   __DATA_CONST.__objc_protorefs: 0x108
   __DATA_CONST.__objc_superrefs: 0x54a8
-  __DATA_CONST.__objc_arraydata: 0x30d8
+  __DATA_CONST.__objc_arraydata: 0x30e0
   __AUTH_CONST.__auth_got: 0x1658
-  __AUTH_CONST.__const: 0x1a738
-  __AUTH_CONST.__cfstring: 0xa4ac0
-  __AUTH_CONST.__objc_const: 0x1613e8
+  __AUTH_CONST.__const: 0x1a758
+  __AUTH_CONST.__cfstring: 0xa4b20
+  __AUTH_CONST.__objc_const: 0x161428
   __AUTH_CONST.__objc_intobj: 0xf90
   __AUTH_CONST.__objc_arrayobj: 0x588
   __AUTH_CONST.__objc_dictobj: 0xc8

   __AUTH.__data: 0x520
   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_data: 0x40
-  __DATA.__objc_ivar: 0x6ec8
-  __DATA.__data: 0x6738
+  __DATA.__objc_ivar: 0x6ed0
+  __DATA.__data: 0x6748
   __DATA.__bss: 0x17a8
   __DATA.__common: 0x790
   __DATA_DIRTY.__objc_ivar: 0xbdec

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 95698
-  Symbols:   154234
-  CStrings:  65955
+  Functions: 95703
+  Symbols:   154244
+  CStrings:  65968
 
Symbols:
+ OBJC_IVAR_$__GEOTileDBWriteQueue._flushTimer
+ OBJC_IVAR_$__GEOTileDBWriteQueue._transaction
+ _GeoServicesConfig_TileDBWriteQueueInterval
+ _GeoServicesConfig_TileDBWriteQueueInterval_Metadata
+ _GeoServicesConfig_TileDBWriteQueueInterval_Metadata_block_invoke_459
+ __20-[GEOTileDB _setup:]_block_invoke_2
+ __76-[GEOTileDB _fetchSubscriptionMetadataWithIdentifierOnQueue:queue:callback:]_block_invoke_2
+ ___74-[_GEOTileDBWriteQueue initWithDB:maxOperations:maxOperationsSizeInBytes:]_block_invoke
+ ___GetDBGeneration_block_invoke
+ ___SetDBGeneration_block_invoke
CStrings:
+ "@category"
+ "@generation"
+ "CREATE TABLE IF NOT EXISTS db_generation (    category INT NOT NULL,    generation INT NOT NULL,    UNIQUE(category)    ON CONFLICT REPLACE    );"
+ "Failed to read file-backed tile data: %{public}@"
+ "GetDBGeneration"
+ "INSERT INTO db_generation    (category, generation)    VALUES (@category, @generation);"
+ "SELECT generation    FROM db_generation    WHERE category = @category;"
+ "Scheduling write queue timer for %.1f seconds"
+ "SetDBGeneration"
+ "Tile DB generation changed (%u => %u). Cleaning up external data"
+ "TileDBWriteQueueInterval"
+ "_flushTimer"
+ "com.apple.geo.com.apple.GeoServices.TileDB.pendingWrites"
```
