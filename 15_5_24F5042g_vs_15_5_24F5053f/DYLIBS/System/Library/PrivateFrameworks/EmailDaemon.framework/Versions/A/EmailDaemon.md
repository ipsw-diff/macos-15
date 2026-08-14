## EmailDaemon

> `/System/Library/PrivateFrameworks/EmailDaemon.framework/Versions/A/EmailDaemon`

```diff

-3826.600.15.1.1
-  __TEXT.__text: 0x29a64c
+3826.600.32.0.0
+  __TEXT.__text: 0x29c058
   __TEXT.__auth_stubs: 0x2500
-  __TEXT.__objc_methlist: 0x15c6c
+  __TEXT.__objc_methlist: 0x15ebc
   __TEXT.__const: 0x1e08
-  __TEXT.__gcc_except_tab: 0x4c9cc
-  __TEXT.__cstring: 0x213e7
-  __TEXT.__oslogstring: 0x18eb6
+  __TEXT.__gcc_except_tab: 0x4cc90
+  __TEXT.__cstring: 0x21457
+  __TEXT.__oslogstring: 0x190e6
   __TEXT.__ustring: 0x2c
   __TEXT.__dlopen_cstrs: 0x57
   __TEXT.__swift5_typeref: 0x92b

   __TEXT.__swift_as_entry: 0x14
   __TEXT.__swift_as_ret: 0x14
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x10940
+  __TEXT.__unwind_info: 0x10a40
   __TEXT.__eh_frame: 0xc40
-  __TEXT.__objc_classname: 0x2ed9
-  __TEXT.__objc_methname: 0x39d06
-  __TEXT.__objc_methtype: 0x869d
-  __TEXT.__objc_stubs: 0x25120
-  __DATA_CONST.__got: 0x1b00
-  __DATA_CONST.__const: 0x1f50
-  __DATA_CONST.__objc_classlist: 0x9a8
+  __TEXT.__objc_classname: 0x2f42
+  __TEXT.__objc_methname: 0x3a05f
+  __TEXT.__objc_methtype: 0x8721
+  __TEXT.__objc_stubs: 0x253c0
+  __DATA_CONST.__got: 0x1b20
+  __DATA_CONST.__const: 0x1f78
+  __DATA_CONST.__objc_classlist: 0x9c0
   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x408
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xba30
+  __DATA_CONST.__objc_selrefs: 0xbae8
   __DATA_CONST.__objc_protorefs: 0xd0
-  __DATA_CONST.__objc_superrefs: 0x6a0
+  __DATA_CONST.__objc_superrefs: 0x6b8
   __DATA_CONST.__objc_arraydata: 0x5b8
   __AUTH_CONST.__auth_got: 0x1290
-  __AUTH_CONST.__const: 0xbfc8
-  __AUTH_CONST.__cfstring: 0x10f80
-  __AUTH_CONST.__objc_const: 0x24ef8
+  __AUTH_CONST.__const: 0xc018
+  __AUTH_CONST.__cfstring: 0x10fe0
+  __AUTH_CONST.__objc_const: 0x253a0
   __AUTH_CONST.__objc_intobj: 0x8e8
   __AUTH_CONST.__objc_arrayobj: 0x270
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_doubleobj: 0x60
-  __AUTH.__objc_data: 0x3448
+  __AUTH.__objc_data: 0x3538
   __AUTH.__data: 0xc50
-  __DATA.__objc_ivar: 0x16f4
+  __DATA.__objc_ivar: 0x1718
   __DATA.__data: 0x3680
   __DATA.__crash_info: 0x40
   __DATA.__bss: 0x30e0
   __DATA.__common: 0x40
   __DATA_DIRTY.__objc_data: 0x2ee0
   __DATA_DIRTY.__data: 0x10
-  __DATA_DIRTY.__bss: 0x808
+  __DATA_DIRTY.__bss: 0x828
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AppIntents.framework/Versions/A/AppIntents
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 10870
-  Symbols:   20826
-  CStrings:  14312
+  Functions: 10923
+  Symbols:   20938
+  CStrings:  14360
 
Symbols:
+ +[EDCoreAnalyticAccountMapper supportsSecureCoding]
+ +[EDCoreAnalyticAccountMapperService log]
+ +[EDCoreAnalyticsBiomeInteractionEventLog log]
+ -[EDBiomeBlackPearlLogger logReadEventForMessageID:accountId:readTimestamp:categorizationEnabled:]
+ -[EDCategoryCoreAnalyticsLogger _extractAccountIdentifier:]
+ -[EDCategoryCoreAnalyticsLogger _findAccountMapping:]
+ -[EDCategoryCoreAnalyticsLogger _retrieveBlackPearlConfig]
+ -[EDCategoryCoreAnalyticsLogger accountMapperService]
+ -[EDCategoryCoreAnalyticsLogger isMailAccountBlackPearlEnabled:accountIdentifier:bbConfig:accountIdentifierTobbConfig:]
+ -[EDCategoryCoreAnalyticsLogger setAccountMapperService:]
+ -[EDCategorySubsystem coreAnalyticsBiomeEventLog]
+ -[EDCoreAnalyticAccountMapper .cxx_destruct]
+ -[EDCoreAnalyticAccountMapper accounts]
+ -[EDCoreAnalyticAccountMapper date]
+ -[EDCoreAnalyticAccountMapper encodeWithCoder:]
+ -[EDCoreAnalyticAccountMapper indexOfAccountId:]
+ -[EDCoreAnalyticAccountMapper initWithCoder:]
+ -[EDCoreAnalyticAccountMapper setAccounts:]
+ -[EDCoreAnalyticAccountMapper setDate:]
+ -[EDCoreAnalyticAccountMapperService .cxx_destruct]
+ -[EDCoreAnalyticAccountMapperService _allActiveMailAccounts]
+ -[EDCoreAnalyticAccountMapperService _convertMailAccountToAccountMapper]
+ -[EDCoreAnalyticAccountMapperService _retrieveFromDisk]
+ -[EDCoreAnalyticAccountMapperService accountMapper]
+ -[EDCoreAnalyticAccountMapperService accountsProvider]
+ -[EDCoreAnalyticAccountMapperService findAccountId:]
+ -[EDCoreAnalyticAccountMapperService getFileNameURL]
+ -[EDCoreAnalyticAccountMapperService initWithAccountProvider:]
+ -[EDCoreAnalyticAccountMapperService lock]
+ -[EDCoreAnalyticAccountMapperService numberOfActiveAccounts]
+ -[EDCoreAnalyticAccountMapperService saveToDisk]
+ -[EDCoreAnalyticAccountMapperService serialQueue]
+ -[EDCoreAnalyticAccountMapperService setAccountMapper:]
+ -[EDCoreAnalyticAccountMapperService setAccountsProvider:]
+ -[EDCoreAnalyticAccountMapperService setLock:]
+ -[EDCoreAnalyticAccountMapperService setSerialQueue:]
+ -[EDCoreAnalyticAccountMapperService validate]
+ -[EDCoreAnalyticsBiomeInteractionEventLog .cxx_destruct]
+ -[EDCoreAnalyticsBiomeInteractionEventLog initWithReadBiomeCollector:]
+ -[EDCoreAnalyticsBiomeInteractionEventLog persistEvent:dataFromMessage:]
+ -[EDCoreAnalyticsBiomeInteractionEventLog persistEvent:dataFromMessage:account:]
+ -[EDCoreAnalyticsBiomeInteractionEventLog persistEvent:date:conversationID:data:]
+ -[EDCoreAnalyticsBiomeInteractionEventLog persistEvent:date:message:data:]
+ -[EDCoreAnalyticsBiomeInteractionEventLog persistEvent:date:message:mailbox:]
+ -[EDCoreAnalyticsBiomeInteractionEventLog persistEvent:date:message:mailboxType:]
+ -[EDCoreAnalyticsBiomeInteractionEventLog readBiomeCollector]
+ -[EDCoreAnalyticsBiomeInteractionEventLog setReadBiomeCollector:]
+ -[EDPersistenceDatabaseConnection _fetchTransactionWriteGenerationWithSQLConnection:newGeneration:error:]
+ -[EDPersistenceDatabaseConnection _storeTransactionWriteGenerationWithSQLConnection:newGeneration:error:]
+ OBJC_IVAR_$_EDCategoryCoreAnalyticsLogger._accountMapperService
+ OBJC_IVAR_$_EDCategorySubsystem._coreAnalyticsBiomeEventLog
+ OBJC_IVAR_$_EDCoreAnalyticAccountMapper._accounts
+ OBJC_IVAR_$_EDCoreAnalyticAccountMapper._date
+ OBJC_IVAR_$_EDCoreAnalyticAccountMapperService._accountMapper
+ OBJC_IVAR_$_EDCoreAnalyticAccountMapperService._accountsProvider
+ OBJC_IVAR_$_EDCoreAnalyticAccountMapperService._lock
+ OBJC_IVAR_$_EDCoreAnalyticAccountMapperService._serialQueue
+ OBJC_IVAR_$_EDCoreAnalyticsBiomeInteractionEventLog._readBiomeCollector
+ _EDCoreAnalyticAccountMapperFile
+ _OBJC_CLASS_$_EDCoreAnalyticAccountMapper
+ _OBJC_CLASS_$_EDCoreAnalyticAccountMapperService
+ _OBJC_CLASS_$_EDCoreAnalyticsBiomeInteractionEventLog
+ _OBJC_CLASS_$_NSRegularExpression
+ _OBJC_METACLASS_$_EDCoreAnalyticAccountMapper
+ _OBJC_METACLASS_$_EDCoreAnalyticAccountMapperService
+ _OBJC_METACLASS_$_EDCoreAnalyticsBiomeInteractionEventLog
+ __60-[EDCoreAnalyticAccountMapperService _allActiveMailAccounts]_block_invoke
+ __OBJC_$_CLASS_METHODS_EDCoreAnalyticAccountMapper
+ __OBJC_$_CLASS_METHODS_EDCoreAnalyticAccountMapperService
+ __OBJC_$_CLASS_METHODS_EDCoreAnalyticsBiomeInteractionEventLog
+ __OBJC_$_CLASS_PROP_LIST_EDCoreAnalyticAccountMapper
+ __OBJC_$_CLASS_PROP_LIST_EDCoreAnalyticAccountMapperService
+ __OBJC_$_CLASS_PROP_LIST_EDCoreAnalyticsBiomeInteractionEventLog
+ __OBJC_$_INSTANCE_METHODS_EDCoreAnalyticAccountMapper
+ __OBJC_$_INSTANCE_METHODS_EDCoreAnalyticAccountMapperService
+ __OBJC_$_INSTANCE_METHODS_EDCoreAnalyticsBiomeInteractionEventLog
+ __OBJC_$_INSTANCE_VARIABLES_EDCoreAnalyticAccountMapper
+ __OBJC_$_INSTANCE_VARIABLES_EDCoreAnalyticAccountMapperService
+ __OBJC_$_INSTANCE_VARIABLES_EDCoreAnalyticsBiomeInteractionEventLog
+ __OBJC_$_PROP_LIST_EDCoreAnalyticAccountMapper
+ __OBJC_$_PROP_LIST_EDCoreAnalyticAccountMapperService
+ __OBJC_$_PROP_LIST_EDCoreAnalyticsBiomeInteractionEventLog
+ __OBJC_CLASS_PROTOCOLS_$_EDCoreAnalyticAccountMapper
+ __OBJC_CLASS_PROTOCOLS_$_EDCoreAnalyticAccountMapperService
+ __OBJC_CLASS_PROTOCOLS_$_EDCoreAnalyticsBiomeInteractionEventLog
+ __OBJC_CLASS_RO_$_EDCoreAnalyticAccountMapper
+ __OBJC_CLASS_RO_$_EDCoreAnalyticAccountMapperService
+ __OBJC_CLASS_RO_$_EDCoreAnalyticsBiomeInteractionEventLog
+ __OBJC_METACLASS_RO_$_EDCoreAnalyticAccountMapper
+ __OBJC_METACLASS_RO_$_EDCoreAnalyticAccountMapperService
+ __OBJC_METACLASS_RO_$_EDCoreAnalyticsBiomeInteractionEventLog
+ ___105-[EDPersistenceDatabaseConnection _fetchTransactionWriteGenerationWithSQLConnection:newGeneration:error:]_block_invoke
+ ___41+[EDCoreAnalyticAccountMapperService log]_block_invoke
+ ___46+[EDCoreAnalyticsBiomeInteractionEventLog log]_block_invoke
+ ___58-[EDCategoryCoreAnalyticsLogger _retrieveBlackPearlConfig]_block_invoke
+ ___60-[EDCoreAnalyticAccountMapperService _allActiveMailAccounts]_block_invoke
+ ___block_descriptor_32_e31_q24?0"NSString"8"NSString"16l
+ ___block_descriptor_40_ea8_32s_e28_v32?0"<EDAccount>"8Q16^B24l
+ ___block_descriptor_56_ea8_32s40s48r_e25_v32?0"NSString"816^B24l
+ ___block_descriptor_64_ea8_32s40s48s_e21_B16?0"<EDAccount>"8l
+ _objc_msgSend$_allActiveMailAccounts
+ _objc_msgSend$_convertMailAccountToAccountMapper
+ _objc_msgSend$_extractAccountIdentifier:
+ _objc_msgSend$_findAccountMapping:
+ _objc_msgSend$_retrieveBlackPearlConfig
+ _objc_msgSend$_retrieveFromDisk
+ _objc_msgSend$accountMapper
+ _objc_msgSend$accountMapperService
+ _objc_msgSend$accounts
+ _objc_msgSend$findAccountId:
+ _objc_msgSend$getFileNameURL
+ _objc_msgSend$indexOfAccountId:
+ _objc_msgSend$initWithAccountProvider:
+ _objc_msgSend$initWithReadBiomeCollector:
+ _objc_msgSend$isAvailable
+ _objc_msgSend$isDate:inSameDayAsDate:
+ _objc_msgSend$isMailAccountBlackPearlEnabled:accountIdentifier:bbConfig:accountIdentifierTobbConfig:
+ _objc_msgSend$rangeOfFirstMatchInString:options:range:
+ _objc_msgSend$regularExpressionWithPattern:options:error:
+ _objc_msgSend$saveToDisk
+ _objc_msgSend$setAccountMapper:
+ _objc_msgSend$setAccounts:
+ _objc_msgSend$validate
- -[EDBiomeBlackPearlLogger logReadEventForMessageID:messageDictionary:]
- -[EDCategoryCoreAnalyticsLogger logReadEventForMessages:categoryPersistence:]
- -[EDPersistenceDatabaseConnection _fetchTransactionWriteGenerationWithSQLConnection:newGeneration:]
- -[EDPersistenceDatabaseConnection _storeTransactionWriteGenerationWithSQLConnection:newGeneration:]
- ___77-[EDCategoryCoreAnalyticsLogger logReadEventForMessages:categoryPersistence:]_block_invoke
- ___77-[EDCategoryCoreAnalyticsLogger logReadEventForMessages:categoryPersistence:]_block_invoke_2
- ___99-[EDPersistenceDatabaseConnection _fetchTransactionWriteGenerationWithSQLConnection:newGeneration:]_block_invoke
- ___block_descriptor_40_ea8_32s_e21_B16?0"<EDAccount>"8l
- ___block_descriptor_64_ea8_32s40s48s56s_e37_v32?0"<EDPersistedMessage>"8Q16^B24l
- _objc_msgSend$logReadEventForMessageID:messageDictionary:
- _objc_msgSend$logReadEventForMessages:categoryPersistence:
CStrings:
+ "\f"
+ "-[EDPersistenceDatabaseConnection _fetchTransactionWriteGenerationWithSQLConnection:newGeneration:error:]"
+ "-[EDPersistenceDatabaseConnection _storeTransactionWriteGenerationWithSQLConnection:newGeneration:error:]"
+ "/[0-9A-F]{8}-[0-9A-F]{4}-[0-9A-F]{4}-[0-9A-F]{4}-[0-9A-F]{12}/"
+ "@\"EDCoreAnalyticAccountMapper\""
+ "@\"EDCoreAnalyticAccountMapperService\""
+ "@\"EDCoreAnalyticsBiomeInteractionEventLog\""
+ "Address string for address %{mask:mailaddr}@ is invalid. Treating as commerce"
+ "B48@0:8@16@24@32@40"
+ "CAAccountMapper.plist"
+ "Cannot verify business display name for address with addressID %lld, due to empty address display name"
+ "Cannot verify business for address with addressID %lld, due to nil address"
+ "EDCoreAnalyticAccountMapper"
+ "EDCoreAnalyticAccountMapperService"
+ "EDCoreAnalyticsBiomeInteractionEventLog"
+ "Failed to categorize message with error %{public}@ sender %{mask:mailaddr}@ isVIP: %{BOOL}d isContact: %{BOOL}d unsubPresent: %{BOOL}d isPrimarySender: %{BOOL}d"
+ "Failed to get redacted address for addressID %lld"
+ "Found addressID %lld is mapped to businessID %lld but display names do not match: businessName: %{public}@, messageName: %{public}@ (%{public}@)"
+ "Network not available, stopping download and verification."
+ "Recipient %{mask:mailaddr}@ isNotPersonal: %s"
+ "Sender %{mask:mailaddr}@ isVIP: %s isContact: %s unsubPresent: %s isPrimarySender: %s"
+ "T@\"EDCoreAnalyticAccountMapper\",&,V_accountMapper"
+ "T@\"EDCoreAnalyticAccountMapperService\",&,N,V_accountMapperService"
+ "T@\"EDCoreAnalyticsBiomeInteractionEventLog\",R,N,V_coreAnalyticsBiomeEventLog"
+ "T@\"NSDate\",N,V_date"
+ "T@\"NSLock\",&,N,V_lock"
+ "WITH receive_row_num AS (    SELECT accountId,           messageId,           senderId,           receivingAccountDomain,           metadataPrimaryKey,           predictedCategory,           currCategoryView,           reasonCodes,           isAllInboxesCategoriesEnabled AS isAllInboxesBlackPearlEnabled,           isMailAccountPersonalAccount,           isMailAccountCategoriesEnabled AS isMailAccountBlackPearlEnabled,           CASE WHEN receiveTimestamp >= %llu                     THEN TRUE                ELSE FALSE                END AS isL1,           ROW_NUMBER() OVER (PARTITION BY accountId, messageId ORDER BY eventTimestamp DESC) AS rn    FROM \"Mail.CategorizationAnalytics.Receive\"    WHERE receiveTimestamp >= %llu          AND receiveTimestamp < %llu          AND accountId IN (%@) ),receive AS (    SELECT accountId,           messageId,           senderId,           receivingAccountDomain,           metadataPrimaryKey,           predictedCategory,           currCategoryView,           reasonCodes,           isAllInboxesBlackPearlEnabled,           isMailAccountPersonalAccount,           isMailAccountBlackPearlEnabled,           isL1    FROM receive_row_num    WHERE rn = 1),read_row_num AS (    SELECT accountId,           messageId,           readTimestamp,           readWithCategoriesEnabled,           ROW_NUMBER() OVER (PARTITION BY accountId, messageId ORDER BY readTimestamp ASC) AS rn    FROM \"Mail.CategorizationAnalytics.Read\"),read AS (    SELECT accountId,           messageId,           readTimestamp AS firstReadTimestamp,           readWithCategoriesEnabled AS hadFirstReadWithBlackPearlEnabled    FROM read_row_num    WHERE rn = 1),recategorize_row_num AS (    SELECT accountId,           messageId,           currCategoryView,           recategorizationBy,           recategorizeTimestamp,           ROW_NUMBER() OVER (PARTITION BY accountId, messageId ORDER BY recategorizeTimestamp DESC) AS rn    FROM \"Mail.CategorizationAnalytics.Recategorize\"),recategorize AS (    SELECT accountId,           messageId,           currCategoryView,           recategorizationBy,           recategorizeTimestamp AS lastRecategorizeTimestamp    FROM recategorize_row_num    WHERE rn = 1),flattened AS (    SELECT receive.accountId,           receive.messageId,           receive.senderId,           receive.receivingAccountDomain,           receive.metadataPrimaryKey,           receive.isAllInboxesBlackPearlEnabled,           receive.isMailAccountPersonalAccount,           receive.isMailAccountBlackPearlEnabled,           receive.predictedCategory,           COALESCE(recategorize.currCategoryView, receive.currCategoryView) AS currCategoryView,           read.hadFirstReadWithBlackPearlEnabled,           CASE                 WHEN read.firstReadTimestamp IS NOT NULL                         AND recategorize.lastRecategorizeTimestamp IS NULL                     THEN TRUE                WHEN read.firstReadTimestamp IS NULL                         AND recategorize.lastRecategorizeTimestamp IS NOT NULL                     THEN FALSE                WHEN read.firstReadTimestamp IS NOT NULL                         AND recategorize.lastRecategorizeTimestamp IS NOT NULL                         AND read.firstReadTimestamp < recategorize.lastRecategorizeTimestamp                     THEN TRUE                WHEN read.firstReadTimestamp IS NOT NULL                         AND recategorize.lastRecategorizeTimestamp IS NOT NULL                         AND read.firstReadTimestamp >= recategorize.lastRecategorizeTimestamp                     THEN FALSE                WHEN read.firstReadTimestamp IS NULL                         AND recategorize.lastRecategorizeTimestamp IS NULL                     THEN False                ELSE NULL                END AS hadReadBeforeRecat,           receive.reasonCodes,           recategorize.recategorizationBy,           receive.isL1,           ROW_NUMBER() OVER (ORDER BY RANDOM()) AS rn    FROM receive         LEFT JOIN read                 ON receive.accountId = read.accountId                    AND receive.messageId = read.messageId         LEFT JOIN recategorize                 ON receive.accountId = recategorize.accountId                    AND receive.messageId = recategorize.messageId), sampled_msg_cnt AS (    SELECT MIN(500, (ABS(RANDOM()) %% (COUNT(*) - FLOOR(0.9 * COUNT(*)) + 1)) + FLOOR(0.9 * COUNT(*))) AS max_rn    FROM flattened) SELECT accountId,       messageId,       senderId,       receivingAccountDomain,       metadataPrimaryKey,       isAllInboxesBlackPearlEnabled,       isMailAccountPersonalAccount,       isMailAccountBlackPearlEnabled,       predictedCategory,       currCategoryView,       hadFirstReadWithBlackPearlEnabled,       hadReadBeforeRecat,       reasonCodes,       recategorizationBy,       isL1 FROM flattened      JOIN sampled_msg_cnt           ON 1=1 WHERE rn <= max_rn;"
+ "[BlackPearl] [ETL-To-CA] Account Extraction for path %@ error %@"
+ "[BlackPearl][AccountMapper] Failed to remove temporary read URL [%@] error [%@]"
+ "[BlackPearl][AccountMapper] list of Active accounts in order : %@ mailAccounts total count %lu"
+ "_accountMapper"
+ "_accountMapperService"
+ "_allActiveMailAccounts"
+ "_convertMailAccountToAccountMapper"
+ "_coreAnalyticsBiomeEventLog"
+ "_extractAccountIdentifier:"
+ "_findAccountMapping:"
+ "_retrieveBlackPearlConfig"
+ "_retrieveFromDisk"
+ "accountKey: %@, mailAccountInboxesEnabled: %ui"
+ "accountMapper"
+ "accountMapperService"
+ "coreAnalyticsBiomeEventLog"
+ "findAccountId:"
+ "getFileNameURL"
+ "indexOfAccountId:"
+ "initWithAccountProvider:"
+ "initWithReadBiomeCollector:"
+ "isAvailable"
+ "isDate:inSameDayAsDate:"
+ "isMailAccountBlackPearlEnabled:accountIdentifier:bbConfig:accountIdentifierTobbConfig:"
+ "logReadEventForMessageID:accountId:readTimestamp:categorizationEnabled:"
+ "q24@?0@\"NSString\"8@\"NSString\"16"
+ "rangeOfFirstMatchInString:options:range:"
+ "regularExpressionWithPattern:options:error:"
+ "saveToDisk"
+ "setAccountMapper:"
+ "setAccountMapperService:"
+ "setLock:"
+ "validate"
- "-[EDPersistenceDatabaseConnection _fetchTransactionWriteGenerationWithSQLConnection:newGeneration:]"
- "-[EDPersistenceDatabaseConnection _storeTransactionWriteGenerationWithSQLConnection:newGeneration:]"
- "Address string for address %{public}@ is invalid. Treating as commerce"
- "Failed to categorize message with error %{public}@ sender %{public}@ isVIP: %{BOOL}d isContact: %{BOOL}d unsubPresent: %{BOOL}d isPrimarySender: %{BOOL}d"
- "Found addressID %@ is mapped to businessID %lld but display names do not match: businessName: %{public}@, messageName: %{public}@ (%{public}@)"
- "Recipient %{public}@ isNotPersonal: %s"
- "Sender %{public}@ isVIP: %s isContact: %s unsubPresent: %s isPrimarySender: %s"
- "T@\"EMCategory\",R,N"
- "WITH receive_row_num AS (    SELECT accountId,           messageId,           senderId,           receivingAccountDomain,           metadataPrimaryKey,           predictedCategory,           currCategoryView,           reasonCodes,           isAllInboxesCategoriesEnabled AS isAllInboxesBlackPearlEnabled,           isMailAccountPersonalAccount,           isMailAccountCategoriesEnabled AS isMailAccountBlackPearlEnabled,           CASE WHEN receiveTimestamp >= %llu                     THEN TRUE                ELSE FALSE                END AS isL1,           ROW_NUMBER() OVER (PARTITION BY accountId, messageId ORDER BY eventTimestamp DESC) AS rn    FROM \"Mail.CategorizationAnalytics.Receive\"    WHERE receiveTimestamp >= %llu          AND receiveTimestamp < %llu          AND accountId IN (%@) ),receive AS (    SELECT accountId,           messageId,           senderId,           receivingAccountDomain,           metadataPrimaryKey,           predictedCategory,           currCategoryView,           reasonCodes,           isAllInboxesBlackPearlEnabled,           isMailAccountPersonalAccount,           isMailAccountBlackPearlEnabled,           isL1    FROM receive_row_num    WHERE rn = 1),read_row_num AS (    SELECT accountId,           messageId,           readTimestamp,           readWithCategoriesEnabled,           ROW_NUMBER() OVER (PARTITION BY accountId, messageId ORDER BY readTimestamp ASC) AS rn    FROM \"Mail.CategorizationAnalytics.Read\"),read AS (    SELECT accountId,           messageId,           readTimestamp AS firstReadTimestamp,           readWithCategoriesEnabled AS hadFirstReadWithBlackPearlEnabled    FROM read_row_num    WHERE rn = 1),recategorize_row_num AS (    SELECT accountId,           messageId,           currCategoryView,           recategorizationBy,           recategorizeTimestamp,           ROW_NUMBER() OVER (PARTITION BY accountId, messageId ORDER BY recategorizeTimestamp DESC) AS rn    FROM \"Mail.CategorizationAnalytics.Recategorize\"),recategorize AS (    SELECT accountId,           messageId,           currCategoryView,           recategorizationBy,           recategorizeTimestamp AS lastRecategorizeTimestamp    FROM recategorize_row_num    WHERE rn = 1),flattened AS (    SELECT receive.accountId,           receive.messageId,           receive.senderId,           receive.receivingAccountDomain,           receive.metadataPrimaryKey,           receive.isAllInboxesBlackPearlEnabled,           receive.isMailAccountPersonalAccount,           receive.isMailAccountBlackPearlEnabled,           receive.predictedCategory,           COALESCE(recategorize.currCategoryView, receive.currCategoryView) AS currCategoryView,           read.hadFirstReadWithBlackPearlEnabled,           CASE                 WHEN read.firstReadTimestamp IS NOT NULL                         AND recategorize.lastRecategorizeTimestamp IS NULL                     THEN TRUE                WHEN read.firstReadTimestamp IS NULL                         AND recategorize.lastRecategorizeTimestamp IS NOT NULL                     THEN FALSE                WHEN read.firstReadTimestamp IS NOT NULL                         AND recategorize.lastRecategorizeTimestamp IS NOT NULL                         AND read.firstReadTimestamp < recategorize.lastRecategorizeTimestamp                     THEN TRUE                WHEN read.firstReadTimestamp IS NOT NULL                         AND recategorize.lastRecategorizeTimestamp IS NOT NULL                         AND read.firstReadTimestamp >= recategorize.lastRecategorizeTimestamp                     THEN FALSE                WHEN read.firstReadTimestamp IS NULL                         AND recategorize.lastRecategorizeTimestamp IS NULL                     THEN False                ELSE NULL                END AS hadReadBeforeRecat,           receive.reasonCodes,           recategorize.recategorizationBy,           receive.isL1,           ROW_NUMBER() OVER (ORDER BY RANDOM()) AS rn    FROM receive         LEFT JOIN read                 ON receive.accountId = read.accountId                    AND receive.messageId = read.messageId         LEFT JOIN recategorize                 ON receive.accountId = recategorize.accountId                    AND receive.messageId = recategorize.messageId), sampled_msg_cnt AS (    SELECT MIN(500, (ABS(RANDOM()) %% (COUNT(*) - FLOOR(0.9 * COUNT(*)) + 1)) + FLOOR(0.9 * COUNT(*))) AS max_rn    FROM flattened) SELECT NULL AS accountId,       messageId,       senderId,       receivingAccountDomain,       metadataPrimaryKey,       isAllInboxesBlackPearlEnabled,       isMailAccountPersonalAccount,       isMailAccountBlackPearlEnabled,       predictedCategory,       currCategoryView,       NULL AS hadFirstReadWithBlackPearlEnabled,       NULL AS hadReadBeforeRecat,       reasonCodes,       recategorizationBy,       isL1 FROM flattened      JOIN sampled_msg_cnt           ON 1=1 WHERE rn <= max_rn;"
- "accountKey: %@, mailAccountInboxesEnabled: %@"
- "logReadEventForMessageID:messageDictionary:"
- "logReadEventForMessages:categoryPersistence:"
```
