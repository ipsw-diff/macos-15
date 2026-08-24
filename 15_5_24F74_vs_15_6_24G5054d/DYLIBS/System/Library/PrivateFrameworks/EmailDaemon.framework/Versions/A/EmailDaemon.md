## EmailDaemon

> `/System/Library/PrivateFrameworks/EmailDaemon.framework/Versions/A/EmailDaemon`

```diff

-3826.600.51.1.1
-  __TEXT.__text: 0x29c6d0
-  __TEXT.__auth_stubs: 0x2570
-  __TEXT.__objc_methlist: 0x15ebc
-  __TEXT.__const: 0x1e08
-  __TEXT.__gcc_except_tab: 0x4cc90
-  __TEXT.__cstring: 0x21457
-  __TEXT.__oslogstring: 0x190e6
+3826.700.51.0.0
+  __TEXT.__text: 0x29bf70
+  __TEXT.__auth_stubs: 0x2560
+  __TEXT.__objc_methlist: 0x15ecc
+  __TEXT.__const: 0x1e38
+  __TEXT.__gcc_except_tab: 0x4cba0
+  __TEXT.__cstring: 0x213e7
+  __TEXT.__oslogstring: 0x19056
   __TEXT.__ustring: 0x2c
   __TEXT.__dlopen_cstrs: 0x57
   __TEXT.__swift5_typeref: 0x935

   __TEXT.__swift_as_entry: 0x14
   __TEXT.__swift_as_ret: 0x14
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x10a48
+  __TEXT.__unwind_info: 0x10a18
   __TEXT.__eh_frame: 0xc40
-  __TEXT.__objc_classname: 0x2f42
-  __TEXT.__objc_methname: 0x3a05b
-  __TEXT.__objc_methtype: 0x8721
-  __TEXT.__objc_stubs: 0x253c0
+  __TEXT.__objc_classname: 0x2f55
+  __TEXT.__objc_methname: 0x39fe3
+  __TEXT.__objc_methtype: 0x870d
+  __TEXT.__objc_stubs: 0x25360
   __DATA_CONST.__got: 0x1b28
   __DATA_CONST.__const: 0x1f78
   __DATA_CONST.__objc_classlist: 0x9c0
   __DATA_CONST.__objc_catlist: 0x48
-  __DATA_CONST.__objc_protolist: 0x408
+  __DATA_CONST.__objc_protolist: 0x410
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xbae8
-  __DATA_CONST.__objc_protorefs: 0xd0
+  __DATA_CONST.__objc_selrefs: 0xbae0
+  __DATA_CONST.__objc_protorefs: 0xd8
   __DATA_CONST.__objc_superrefs: 0x6b8
   __DATA_CONST.__objc_arraydata: 0x5b8
-  __AUTH_CONST.__auth_got: 0x12c8
+  __AUTH_CONST.__auth_got: 0x12c0
   __AUTH_CONST.__const: 0xc018
-  __AUTH_CONST.__cfstring: 0x10fe0
-  __AUTH_CONST.__objc_const: 0x253a0
+  __AUTH_CONST.__cfstring: 0x10f40
+  __AUTH_CONST.__objc_const: 0x253d0
   __AUTH_CONST.__objc_intobj: 0x8e8
   __AUTH_CONST.__objc_arrayobj: 0x270
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_doubleobj: 0x60
   __AUTH.__objc_data: 0x3538
-  __AUTH.__data: 0xc50
+  __AUTH.__data: 0xc40
   __DATA.__objc_ivar: 0x1718
-  __DATA.__data: 0x3690
+  __DATA.__data: 0x36c0
   __DATA.__crash_info: 0x40
   __DATA.__bss: 0x30e0
   __DATA.__common: 0x40

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 10926
-  Symbols:   20938
-  CStrings:  14360
+  Functions: 10921
+  Symbols:   20936
+  CStrings:  14351
 
Symbols:
+ -[EDBatchingMessageQueryIterator _callHandlerWithError:]
+ -[EDBatchingMessageQueryIterator _callHandlerWithMessages:]
+ -[EDCategoryCoreAnalyticsLogger _isMailAccountBucketBarHidden:]
+ OBJC_IVAR_$_EDBatchingMessageQueryIterator._handlerLock
+ _OBJC_CLASS_$_EMSmartMailbox
+ __106-[EDBatchingMessageQueryIterator initWithMessagePersistence:query:batchSize:firstBatchSize:limit:handler:]_block_invoke
+ __70-[EDCategoryPersistence persistCategorizationResultMap:userInitiated:]_block_invoke
+ __OBJC_$_PROP_LIST_MSBucketBarMailbox
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MSBucketBarMailbox
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MSBucketBarMailbox
+ __OBJC_$_PROTOCOL_REFS_MSBucketBarMailbox
+ __OBJC_LABEL_PROTOCOL_$_MSBucketBarMailbox
+ __OBJC_PROTOCOL_$_MSBucketBarMailbox
+ __OBJC_PROTOCOL_REFERENCE_$_MSBucketBarMailbox
+ ___block_descriptor_56_ea8_32s40s_e21_B16?0"<EDAccount>"8l
+ ___block_descriptor_94_ea8_32s40s48s56s64s72r_e25_v32?0"EFSQLRow"8Q16^B24l
+ _objc_msgSend$_callHandlerWithError:
+ _objc_msgSend$_callHandlerWithMessages:
+ _objc_msgSend$_isMailAccountBucketBarHidden:
+ _objc_msgSend$isBucketBarHiddenForMailboxes:
+ _objc_msgSend$unifiedMailboxOfType:name:
- -[EDCategoryCoreAnalyticsLogger _extractAccountIdentifier:]
- -[EDCategoryCoreAnalyticsLogger _retrieveBlackPearlConfig]
- -[EDCategoryCoreAnalyticsLogger isMailAccountBlackPearlEnabled:accountIdentifier:bbConfig:accountIdentifierTobbConfig:]
- -[EDMarkCertificateVerifier _certificateFromPEMData:]
- -[EDMarkCertificateVerifier _certificateFromPEMFile:]
- -[EDMarkCertificateVerifier _loadVMCRootCertificates]
- -[EDMarkCertificateVerifier vmcRootCertificates]
- OBJC_IVAR_$_EDMarkCertificateVerifier._vmcRootCertificates
- _OBJC_CLASS_$_NSRegularExpression
- _SecTrustSetAnchorCertificates
- __OBJC_$_INSTANCE_VARIABLES_EDMarkCertificateVerifier
- __OBJC_$_PROP_LIST_EDMarkCertificateVerifier
- ___58-[EDCategoryCoreAnalyticsLogger _retrieveBlackPearlConfig]_block_invoke
- ___block_descriptor_64_ea8_32s40s48s_e21_B16?0"<EDAccount>"8l
- ___block_descriptor_93_ea8_32s40s48s56s64s72r_e25_v32?0"EFSQLRow"8Q16^B24l
- _objc_msgSend$_extractAccountIdentifier:
- _objc_msgSend$_retrieveBlackPearlConfig
- _objc_msgSend$initWithContentsOfFile:
- _objc_msgSend$isMailAccountBlackPearlEnabled:accountIdentifier:bbConfig:accountIdentifierTobbConfig:
- _objc_msgSend$rangeOfFirstMatchInString:options:range:
- _objc_msgSend$regularExpressionWithPattern:options:error:
- _objc_msgSend$removeThreadProxies:forMove:
- _objc_msgSend$vmcRootCertificates
CStrings:
+ "MSBucketBarMailbox"
+ "_callHandlerWithError:"
+ "_callHandlerWithMessages:"
+ "_handlerLock"
+ "_isMailAccountBucketBarHidden:"
+ "bucketBarConfigurationIdentifier"
+ "isBucketBarHiddenForMailboxes:"
+ "isInboxMailbox"
+ "unifiedMailboxOfType:name:"
- "%@%@"
- "/[0-9A-F]{8}-[0-9A-F]{4}-[0-9A-F]{4}-[0-9A-F]{4}-[0-9A-F]{12}/"
- "B48@0:8@16@24@32@40"
- "Unable to set anchor certificates"
- "[BlackPearl] [ETL-To-CA] Account Extraction for path %@ error %@"
- "_extractAccountIdentifier:"
- "_retrieveBlackPearlConfig"
- "_vmcRootCertificates"
- "accountKey: %@, mailAccountInboxesEnabled: %ui"
- "digicert vmc root"
- "entrust vmc root"
- "initWithContentsOfFile:"
- "isMailAccountBlackPearlEnabled:accountIdentifier:bbConfig:accountIdentifierTobbConfig:"
- "pem"
- "rangeOfFirstMatchInString:options:range:"
- "regularExpressionWithPattern:options:error:"
- "removeThreadProxies:forMove:"
- "vmcRootCertificates"
```
