## iCloudDriveCore

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/Versions/A/iCloudDriveCore`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-3437.120.13.0.1
-  __TEXT.__text: 0x345d84
+3437.120.20.0.0
+  __TEXT.__text: 0x346ccc
   __TEXT.__auth_stubs: 0x1a20
-  __TEXT.__objc_methlist: 0x1912c
+  __TEXT.__objc_methlist: 0x191dc
   __TEXT.__const: 0x4d0
-  __TEXT.__cstring: 0x7aa36
-  __TEXT.__oslogstring: 0x3be9a
-  __TEXT.__gcc_except_tab: 0x1a0e4
+  __TEXT.__cstring: 0x7ab3f
+  __TEXT.__oslogstring: 0x3bf49
+  __TEXT.__gcc_except_tab: 0x1a0fc
   __TEXT.__ustring: 0x88
-  __TEXT.__unwind_info: 0x9b88
+  __TEXT.__unwind_info: 0x9b98
   __TEXT.__objc_classname: 0x2679
-  __TEXT.__objc_methname: 0x4155a
-  __TEXT.__objc_methtype: 0x893d
-  __TEXT.__objc_stubs: 0x2ce00
+  __TEXT.__objc_methname: 0x4171e
+  __TEXT.__objc_methtype: 0x8964
+  __TEXT.__objc_stubs: 0x2cfa0
   __DATA_CONST.__got: 0x1758
-  __DATA_CONST.__const: 0x1ca0
+  __DATA_CONST.__const: 0x1ca8
   __DATA_CONST.__objc_classlist: 0x998
   __DATA_CONST.__objc_catlist: 0xe0
   __DATA_CONST.__objc_protolist: 0x258
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xdd78
+  __DATA_CONST.__objc_selrefs: 0xddf0
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x870
+  __DATA_CONST.__objc_superrefs: 0x878
   __DATA_CONST.__objc_arraydata: 0xf60
   __AUTH_CONST.__auth_got: 0xd20
   __AUTH_CONST.__const: 0xaa18
-  __AUTH_CONST.__cfstring: 0x22460
-  __AUTH_CONST.__objc_const: 0x3b050
+  __AUTH_CONST.__cfstring: 0x22560
+  __AUTH_CONST.__objc_const: 0x3b120
   __AUTH_CONST.__objc_intobj: 0xb40
   __AUTH_CONST.__objc_arrayobj: 0x288
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_doubleobj: 0x50
   __AUTH.__objc_data: 0x5ff0
   __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0x1ed4
+  __DATA.__objc_ivar: 0x1ee0
   __DATA.__data: 0x25f0
   __DATA.__bss: 0x620
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/libprequelite.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 13367
-  Symbols:   23309
-  CStrings:  22277
+  Functions: 13384
+  Symbols:   23342
+  CStrings:  22304
 
Symbols:
+ +[BRCAccountSession(BRCDatabaseManager) _checkIntegrity:serverTruth:session:skipControlFiles:dbCreationDate:deviceIDChanged:error:]
+ +[BRCAccountSession(BRCDatabaseManager) _registerLastBootIfNeeded:table:skipControlFiles:dbCreationDate:deviceIDChanged:]
+ +[BRCAccountSession(BRCDatabaseManager) openAndValidateDatabase:serverTruth:session:baseURL:skipControlFiles:initialVersion:lastCurrentVersion:dbCreationDate:deviceIDChanged:error:]
+ +[CKRecord(BRCItemAdditions) _validateCKObject:isRereference:enhancedDrivePrivacyEnabled:]
+ -[AppTelemetryInvestigation(AppTelemetryDriveTelemetryExtension) dbAge]
+ -[AppTelemetryInvestigation(AppTelemetryDriveTelemetryExtension) hasDbAge]
+ -[AppTelemetryInvestigation(AppTelemetryDriveTelemetryExtension) hasIsConsolidated]
+ -[AppTelemetryInvestigation(AppTelemetryDriveTelemetryExtension) isConsolidated]
+ -[AppTelemetryInvestigation(AppTelemetryDriveTelemetryExtension) setDbAge:]
+ -[AppTelemetryInvestigation(AppTelemetryDriveTelemetryExtension) setHasDbAge:]
+ -[AppTelemetryInvestigation(AppTelemetryDriveTelemetryExtension) setHasIsConsolidated:]
+ -[AppTelemetryInvestigation(AppTelemetryDriveTelemetryExtension) setIsConsolidated:]
+ -[AppTelemetryInvestigation(BRCAdditions) _daysSinceLastOSUpdate]
+ -[AppTelemetryInvestigation(BRCAdditions) _dbAgeFromDbCreationDate:]
+ -[AppTelemetryInvestigation(BRCAdditions) init]
+ -[BRCAccountSession dbCreationDate]
+ -[BRCAccountSession isConsolidatedAccount]
+ -[BRCFSUploader _serializeServerSideAssetCopyPluginFieldsForRecord:newZone:origZone:]
+ -[BRCUserDefaults allowAssetReferencesOfMMCSV1Assets]
+ -[BRCUserDefaults enhancedDrivePrivacyRolledBack]
+ GCC_except_table139
+ GCC_except_table188
+ GCC_except_table245
+ GCC_except_table254
+ GCC_except_table260
+ GCC_except_table269
+ GCC_except_table288
+ GCC_except_table363
+ GCC_except_table495
+ GCC_except_table575
+ OBJC_IVAR_$_AppTelemetryInvestigation._dbAge
+ OBJC_IVAR_$_AppTelemetryInvestigation._isConsolidated
+ OBJC_IVAR_$_BRCAccountSession._dbCreationDate
+ __181+[BRCAccountSession(BRCDatabaseManager) openAndValidateDatabase:serverTruth:session:baseURL:skipControlFiles:initialVersion:lastCurrentVersion:dbCreationDate:deviceIDChanged:error:]_block_invoke
+ __OBJC_$_INSTANCE_METHODS_AppTelemetryInvestigation(AppTelemetryDriveTelemetryExtension|BRCAdditions)
+ ___181+[BRCAccountSession(BRCDatabaseManager) openAndValidateDatabase:serverTruth:session:baseURL:skipControlFiles:initialVersion:lastCurrentVersion:dbCreationDate:deviceIDChanged:error:]_block_invoke
+ ___65-[AppTelemetryInvestigation(BRCAdditions) _daysSinceLastOSUpdate]_block_invoke
+ ___block_descriptor_98_e8_32s40s48s56r_e23_B16?0"PQLConnection"8l
+ _kBRRecordAssetReReference
+ _objc_msgSend$_checkIntegrity:serverTruth:session:skipControlFiles:dbCreationDate:deviceIDChanged:error:
+ _objc_msgSend$_dbAgeFromDbCreationDate:
+ _objc_msgSend$_registerLastBootIfNeeded:table:skipControlFiles:dbCreationDate:deviceIDChanged:
+ _objc_msgSend$_serializeServerSideAssetCopyPluginFieldsForRecord:newZone:origZone:
+ _objc_msgSend$_validateCKObject:isRereference:enhancedDrivePrivacyEnabled:
+ _objc_msgSend$allowAssetReferencesOfMMCSV1Assets
+ _objc_msgSend$dbAge
+ _objc_msgSend$dbCreationDate
+ _objc_msgSend$enhancedDrivePrivacyRolledBack
+ _objc_msgSend$hasDbAge
+ _objc_msgSend$hasIsConsolidated
+ _objc_msgSend$isConsolidated
+ _objc_msgSend$isConsolidatedAccount
+ _objc_msgSend$isReference
+ _objc_msgSend$openAndValidateDatabase:serverTruth:session:baseURL:skipControlFiles:initialVersion:lastCurrentVersion:dbCreationDate:deviceIDChanged:error:
+ _objc_msgSend$setDbAge:
+ _objc_msgSend$setIsConsolidated:
- +[AppTelemetryTimeSeriesEvent(BRCAdditions) _daysSinceLastOSUpdate]
- +[BRCAccountSession(BRCDatabaseManager) _checkIntegrity:serverTruth:session:skipControlFiles:deviceIDChanged:error:]
- +[BRCAccountSession(BRCDatabaseManager) _registerLastBootIfNeeded:table:skipControlFiles:deviceIDChanged:]
- +[BRCAccountSession(BRCDatabaseManager) openAndValidateDatabase:serverTruth:session:baseURL:skipControlFiles:initialVersion:lastCurrentVersion:deviceIDChanged:error:]
- +[CKRecord(BRCItemAdditions) _validateCKObject:enhancedDrivePrivacyEnabled:]
- GCC_except_table175
- GCC_except_table205
- GCC_except_table244
- GCC_except_table253
- GCC_except_table255
- GCC_except_table257
- GCC_except_table361
- GCC_except_table493
- GCC_except_table573
- __166+[BRCAccountSession(BRCDatabaseManager) openAndValidateDatabase:serverTruth:session:baseURL:skipControlFiles:initialVersion:lastCurrentVersion:deviceIDChanged:error:]_block_invoke
- __OBJC_$_INSTANCE_METHODS_AppTelemetryInvestigation(AppTelemetryDriveTelemetryExtension)
- ___166+[BRCAccountSession(BRCDatabaseManager) openAndValidateDatabase:serverTruth:session:baseURL:skipControlFiles:initialVersion:lastCurrentVersion:deviceIDChanged:error:]_block_invoke
- ___67+[AppTelemetryTimeSeriesEvent(BRCAdditions) _daysSinceLastOSUpdate]_block_invoke
- ___block_descriptor_90_e8_32s40s48s56r_e23_B16?0"PQLConnection"8l
- _objc_msgSend$_checkIntegrity:serverTruth:session:skipControlFiles:deviceIDChanged:error:
- _objc_msgSend$_registerLastBootIfNeeded:table:skipControlFiles:deviceIDChanged:
- _objc_msgSend$_validateCKObject:enhancedDrivePrivacyEnabled:
- _objc_msgSend$openAndValidateDatabase:serverTruth:session:baseURL:skipControlFiles:initialVersion:lastCurrentVersion:deviceIDChanged:error:
CStrings:
+ "+[BRCAccountSession(BRCDatabaseManager) _checkIntegrity:serverTruth:session:skipControlFiles:dbCreationDate:deviceIDChanged:error:]"
+ "+[BRCAccountSession(BRCDatabaseManager) _registerLastBootIfNeeded:table:skipControlFiles:dbCreationDate:deviceIDChanged:]"
+ "+[BRCAccountSession(BRCDatabaseManager) openAndValidateDatabase:serverTruth:session:baseURL:skipControlFiles:initialVersion:lastCurrentVersion:dbCreationDate:deviceIDChanged:error:]"
+ "+[BRCAccountSession(BRCDatabaseManager) openAndValidateDatabase:serverTruth:session:baseURL:skipControlFiles:initialVersion:lastCurrentVersion:dbCreationDate:deviceIDChanged:error:]_block_invoke"
+ "+[CKRecord(BRCItemAdditions) _validateCKObject:isRereference:enhancedDrivePrivacyEnabled:]"
+ "B64@0:8@16B24@28B36^@40^B48^@56"
+ "B88@0:8@16B24@28@36B44^I48^I56^@64^B72^@80"
+ "SELECT date FROM %@ ORDER BY rowid ASC LIMIT 1"
+ "T@\"NSDate\",R,N,V_dbCreationDate"
+ "[DEBUG] Allowing rereference of mmcsv1 asset%@"
+ "[DEBUG] Allowing rereference of mmcsv1 package%@"
+ "[WARNING] Stripping enhanced drive privacy bit because it was rolled back %@%@"
+ "_checkIntegrity:serverTruth:session:skipControlFiles:dbCreationDate:deviceIDChanged:error:"
+ "_dbAge"
+ "_dbAgeFromDbCreationDate:"
+ "_dbCreationDate"
+ "_isConsolidated"
+ "_registerLastBootIfNeeded:table:skipControlFiles:dbCreationDate:deviceIDChanged:"
+ "_serializeServerSideAssetCopyPluginFieldsForRecord:newZone:origZone:"
+ "_validateCKObject:isRereference:enhancedDrivePrivacyEnabled:"
+ "allowAssetReferencesOfMMCSV1Assets"
+ "br_assetRereference"
+ "consolidate = %s|"
+ "dbAge"
+ "dbAge = %lld|"
+ "dbCreationDate"
+ "enhancedDrivePrivacyRolledBack"
+ "errorDomain = %@|errorCode = %lld|errorDescription = %@|underlyingErrorDomain = %@|underlyingErrorCode = %lld|"
+ "hasDbAge"
+ "hasIsConsolidated"
+ "isConsolidated"
+ "isConsolidatedAccount"
+ "isReference"
+ "lastOSUpdate = %lld|"
+ "openAndValidateDatabase:serverTruth:session:baseURL:skipControlFiles:initialVersion:lastCurrentVersion:dbCreationDate:deviceIDChanged:error:"
+ "setDbAge:"
+ "setHasDbAge:"
+ "setHasIsConsolidated:"
+ "setIsConsolidated:"
+ "sync.allow-mmcsv1-asset-references"
+ "sync.enhanced-drive-privacy.rollback"
+ "v52@0:8@16@24B32^@36^B44"
+ "{?=\"dbAge\"b1\"errorCode\"b1\"eventTimestamp\"b1\"lastOSUpdate\"b1\"underlyingErrorCode\"b1\"hasForegroundClients\"b1\"isConsolidated\"b1\"isEnhancedDrivePrivacyEnabled\"b1\"isPCSChained\"b1\"nonDiscretionary\"b1\"sharedZone\"b1}"
- "+[BRCAccountSession(BRCDatabaseManager) _checkIntegrity:serverTruth:session:skipControlFiles:deviceIDChanged:error:]"
- "+[BRCAccountSession(BRCDatabaseManager) _registerLastBootIfNeeded:table:skipControlFiles:deviceIDChanged:]"
- "+[BRCAccountSession(BRCDatabaseManager) openAndValidateDatabase:serverTruth:session:baseURL:skipControlFiles:initialVersion:lastCurrentVersion:deviceIDChanged:error:]"
- "+[BRCAccountSession(BRCDatabaseManager) openAndValidateDatabase:serverTruth:session:baseURL:skipControlFiles:initialVersion:lastCurrentVersion:deviceIDChanged:error:]_block_invoke"
- "+[CKRecord(BRCItemAdditions) _validateCKObject:enhancedDrivePrivacyEnabled:]"
- "B56@0:8@16B24@28B36^B40^@48"
- "B80@0:8@16B24@28@36B44^I48^I56^B64^@72"
- "O"
- "_checkIntegrity:serverTruth:session:skipControlFiles:deviceIDChanged:error:"
- "_registerLastBootIfNeeded:table:skipControlFiles:deviceIDChanged:"
- "_validateCKObject:enhancedDrivePrivacyEnabled:"
- "errorDomain = %@|errorCode = %lld| errorDescription = %@| underlyingErrorDomain = %@| underlyingErrorCode = %lld"
- "lastOSUpdate = %lld"
- "openAndValidateDatabase:serverTruth:session:baseURL:skipControlFiles:initialVersion:lastCurrentVersion:deviceIDChanged:error:"
- "v44@0:8@16@24B32^B36"
- "{?=\"errorCode\"b1\"eventTimestamp\"b1\"lastOSUpdate\"b1\"underlyingErrorCode\"b1\"hasForegroundClients\"b1\"isEnhancedDrivePrivacyEnabled\"b1\"isPCSChained\"b1\"nonDiscretionary\"b1\"sharedZone\"b1}"
```
