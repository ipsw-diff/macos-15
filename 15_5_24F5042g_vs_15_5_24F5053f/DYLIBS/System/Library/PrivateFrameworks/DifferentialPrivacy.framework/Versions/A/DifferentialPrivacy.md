## DifferentialPrivacy

> `/System/Library/PrivateFrameworks/DifferentialPrivacy.framework/Versions/A/DifferentialPrivacy`

```diff

-659.120.3.0.0
-  __TEXT.__text: 0x66174
-  __TEXT.__auth_stubs: 0xd80
-  __TEXT.__objc_methlist: 0x5700
-  __TEXT.__const: 0x810
-  __TEXT.__cstring: 0x473d
-  __TEXT.__oslogstring: 0x4112
+659.120.7.0.3
+  __TEXT.__text: 0x67a98
+  __TEXT.__auth_stubs: 0xd90
+  __TEXT.__objc_methlist: 0x58d4
+  __TEXT.__const: 0x840
+  __TEXT.__cstring: 0x48cd
+  __TEXT.__oslogstring: 0x41ee
   __TEXT.__gcc_except_tab: 0xbc4
   __TEXT.__ustring: 0x4
   __TEXT.__dlopen_cstrs: 0x74
-  __TEXT.__constg_swiftt: 0x218
-  __TEXT.__swift5_typeref: 0x141
+  __TEXT.__constg_swiftt: 0x244
+  __TEXT.__swift5_typeref: 0x147
   __TEXT.__swift5_reflstr: 0x1ed
-  __TEXT.__swift5_fieldmd: 0x1dc
-  __TEXT.__swift5_types: 0x28
+  __TEXT.__swift5_fieldmd: 0x1ec
+  __TEXT.__swift5_types: 0x2c
   __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_proto: 0x30
-  __TEXT.__unwind_info: 0x1888
+  __TEXT.__unwind_info: 0x18e8
   __TEXT.__eh_frame: 0x548
-  __TEXT.__objc_classname: 0xd30
-  __TEXT.__objc_methname: 0x99e7
+  __TEXT.__objc_classname: 0xdbb
+  __TEXT.__objc_methname: 0x9d6e
   __TEXT.__objc_methtype: 0x12fe
-  __TEXT.__objc_stubs: 0x7c60
-  __DATA_CONST.__got: 0x7a8
-  __DATA_CONST.__const: 0x7d8
-  __DATA_CONST.__objc_classlist: 0x480
+  __TEXT.__objc_stubs: 0x7e40
+  __DATA_CONST.__got: 0x7c8
+  __DATA_CONST.__const: 0x7f8
+  __DATA_CONST.__objc_classlist: 0x4a0
   __DATA_CONST.__objc_catlist: 0x10
-  __DATA_CONST.__objc_protolist: 0x90
+  __DATA_CONST.__objc_protolist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2480
+  __DATA_CONST.__objc_selrefs: 0x2520
   __DATA_CONST.__objc_protorefs: 0x20
-  __DATA_CONST.__objc_superrefs: 0x2e0
+  __DATA_CONST.__objc_superrefs: 0x2f0
   __DATA_CONST.__objc_arraydata: 0x728
-  __AUTH_CONST.__auth_got: 0x6d8
-  __AUTH_CONST.__const: 0xf90
-  __AUTH_CONST.__cfstring: 0x4b00
-  __AUTH_CONST.__objc_const: 0xaad0
+  __AUTH_CONST.__auth_got: 0x6e0
+  __AUTH_CONST.__const: 0xfb0
+  __AUTH_CONST.__cfstring: 0x4c00
+  __AUTH_CONST.__objc_const: 0xafc8
   __AUTH_CONST.__objc_intobj: 0xd38
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH.__objc_data: 0x1498
-  __AUTH.__data: 0x1a0
-  __DATA.__objc_ivar: 0x530
-  __DATA.__data: 0x908
-  __DATA.__bss: 0x8b0
+  __AUTH.__objc_data: 0x1638
+  __AUTH.__data: 0x1c8
+  __DATA.__objc_ivar: 0x55c
+  __DATA.__data: 0x968
+  __DATA.__bss: 0x8c0
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0x1c20
   __DATA_DIRTY.__bss: 0x28

   - /usr/lib/swift/libswiftDarwin.dylib
   - /usr/lib/swift/libswiftDispatch.dylib
   - /usr/lib/swift/libswiftIOKit.dylib
+  - /usr/lib/swift/libswiftMetal.dylib
   - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftQuartzCore.dylib
+  - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_errno.dylib

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 2395
-  Symbols:   5036
-  CStrings:  3003
+  Functions: 2435
+  Symbols:   5139
+  CStrings:  3060
 
Symbols:
+ +[_DPAppleIntelligenceReportParameters isValidDonation:]
+ +[_DPDediscoDonation(TaskConfig) defaultValueForKey:]
+ +[_DPDiagnosticsAndUsageTransparencyLog convertToHexString:]
+ +[_DPDiagnosticsAndUsageTransparencyLog formatNoisedData:dimension:]
+ +[_DPDiagnosticsAndUsageTransparencyLog formatSerializedData:]
+ +[_DPDiagnosticsAndUsageTransparencyLog inPlaceReplaceOccurrencesOf:with:inBytes:bytesLength:caseSensitiveSearch:repeat:]
+ +[_DPDiagnosticsAndUsageTransparencyLog insertIfPossibleObj:intoJSONDictionary:withKey:]
+ +[_DPStrings tokensFilePrefix]
+ +[_DPTransparencyLogError errorWithCode:description:]
+ -[_DPAppleIntelligenceReportParameters .cxx_destruct]
+ -[_DPAppleIntelligenceReportParameters dimension]
+ -[_DPAppleIntelligenceReportParameters initWithDonation:]
+ -[_DPAppleIntelligenceReportParameters key]
+ -[_DPAppleIntelligenceReportParameters localEpsilon]
+ -[_DPAppleIntelligenceReportParameters minBatchSize]
+ -[_DPAppleIntelligenceReportParameters ohttp]
+ -[_DPAppleIntelligenceReportParameters privateAccessToken]
+ -[_DPAppleIntelligenceReportParameters targetCentralDelta]
+ -[_DPAppleIntelligenceReportParameters targetCentralEpsilon]
+ -[_DPAppleIntelligenceReportParameters taskExpiration]
+ -[_DPAppleIntelligenceTransparencyLog .cxx_destruct]
+ -[_DPAppleIntelligenceTransparencyLog donations]
+ -[_DPAppleIntelligenceTransparencyLog initWithDonations:error:]
+ -[_DPAppleIntelligenceTransparencyLog writeToDiskWithError:]
+ -[_DPDediscoDonation(TaskConfig) getHelperServerName]
+ -[_DPDediscoDonation(TaskConfig) getLeaderServerName]
+ -[_DPDediscoDonation(TaskConfig) isFeatureEnabled:withError:]
+ -[_DPDediscoDonation(TaskConfig) isOHTTPEnabledWithError:]
+ -[_DPDediscoDonation(TaskConfig) isPrivateAccessTokenEnabledWithError:]
+ -[_DPDediscoDonation(TaskConfig) isTelemetryAllowed]
+ -[_DPDiagnosticsAndUsageTransparencyLog .cxx_destruct]
+ -[_DPDiagnosticsAndUsageTransparencyLog contentsForDonations:withReportName:]
+ -[_DPDiagnosticsAndUsageTransparencyLog dataSource]
+ -[_DPDiagnosticsAndUsageTransparencyLog filterMetadataFieldsInSimplifiedLog:]
+ -[_DPDiagnosticsAndUsageTransparencyLog initWithDonations:error:]
+ -[_DPDiagnosticsAndUsageTransparencyLog jsonRepresentationForMetadataInDonation:]
+ -[_DPDiagnosticsAndUsageTransparencyLog jsonRepresentationFromParameters:]
+ -[_DPDiagnosticsAndUsageTransparencyLog key]
+ -[_DPDiagnosticsAndUsageTransparencyLog numDonations]
+ -[_DPDiagnosticsAndUsageTransparencyLog rawSerializedData]
+ -[_DPDiagnosticsAndUsageTransparencyLog reportName]
+ -[_DPDiagnosticsAndUsageTransparencyLog serializedData]
+ -[_DPDiagnosticsAndUsageTransparencyLog writeToDiskWithError:]
+ -[_DPKeyProperties transparencyLogReportName]
+ -[_DPTransparencyLogError initWithCode:description:]
+ OBJC_IVAR_$__DPAppleIntelligenceReportParameters._dimension
+ OBJC_IVAR_$__DPAppleIntelligenceReportParameters._key
+ OBJC_IVAR_$__DPAppleIntelligenceReportParameters._localEpsilon
+ OBJC_IVAR_$__DPAppleIntelligenceReportParameters._minBatchSize
+ OBJC_IVAR_$__DPAppleIntelligenceReportParameters._ohttp
+ OBJC_IVAR_$__DPAppleIntelligenceReportParameters._privateAccessToken
+ OBJC_IVAR_$__DPAppleIntelligenceReportParameters._targetCentralDelta
+ OBJC_IVAR_$__DPAppleIntelligenceReportParameters._targetCentralEpsilon
+ OBJC_IVAR_$__DPAppleIntelligenceReportParameters._taskExpiration
+ OBJC_IVAR_$__DPAppleIntelligenceTransparencyLog._donations
+ OBJC_IVAR_$__DPDiagnosticsAndUsageTransparencyLog._dataSource
+ OBJC_IVAR_$__DPDiagnosticsAndUsageTransparencyLog._key
+ OBJC_IVAR_$__DPDiagnosticsAndUsageTransparencyLog._numDonations
+ OBJC_IVAR_$__DPDiagnosticsAndUsageTransparencyLog._rawSerializedData
+ OBJC_IVAR_$__DPDiagnosticsAndUsageTransparencyLog._reportName
+ OBJC_IVAR_$__DPDiagnosticsAndUsageTransparencyLog._serializedData
+ OBJC_IVAR_$__DPKeyProperties._transparencyLogReportName
+ _DPNewTransparencyLog
+ _NSInvalidArgumentException
+ _OBJC_CLASS_$__DPAppleIntelligenceReportParameters
+ _OBJC_CLASS_$__DPAppleIntelligenceReportShim
+ _OBJC_CLASS_$__DPAppleIntelligenceTransparencyLog
+ _OBJC_CLASS_$__DPDiagnosticsAndUsageTransparencyLog
+ _OBJC_CLASS_$__DPTransparencyLogError
+ _OBJC_METACLASS_$__DPAppleIntelligenceReportParameters
+ _OBJC_METACLASS_$__DPAppleIntelligenceReportShim
+ _OBJC_METACLASS_$__DPAppleIntelligenceTransparencyLog
+ _OBJC_METACLASS_$__DPDiagnosticsAndUsageTransparencyLog
+ _OBJC_METACLASS_$__DPTransparencyLogError
+ __CLASS_METHODS__DPAppleIntelligenceReportShim
+ __DATA__DPAppleIntelligenceReportShim
+ __DPNewTransparencyLog
+ __DPTransparencyLogErrorDomain
+ __INSTANCE_METHODS__DPAppleIntelligenceReportShim
+ __METACLASS_DATA__DPAppleIntelligenceReportShim
+ __OBJC_$_CLASS_METHODS__DPAppleIntelligenceReportParameters
+ __OBJC_$_CLASS_METHODS__DPDediscoDonation(TaskConfig)
+ __OBJC_$_CLASS_METHODS__DPDiagnosticsAndUsageTransparencyLog
+ __OBJC_$_CLASS_METHODS__DPTransparencyLogError
+ __OBJC_$_INSTANCE_METHODS__DPAppleIntelligenceReportParameters
+ __OBJC_$_INSTANCE_METHODS__DPAppleIntelligenceTransparencyLog
+ __OBJC_$_INSTANCE_METHODS__DPDediscoDonation(TaskConfig)
+ __OBJC_$_INSTANCE_METHODS__DPDiagnosticsAndUsageTransparencyLog
+ __OBJC_$_INSTANCE_METHODS__DPTransparencyLogError
+ __OBJC_$_INSTANCE_VARIABLES__DPAppleIntelligenceReportParameters
+ __OBJC_$_INSTANCE_VARIABLES__DPAppleIntelligenceTransparencyLog
+ __OBJC_$_INSTANCE_VARIABLES__DPDiagnosticsAndUsageTransparencyLog
+ __OBJC_$_PROP_LIST__DPAppleIntelligenceReportParameters
+ __OBJC_$_PROP_LIST__DPAppleIntelligenceTransparencyLog
+ __OBJC_$_PROP_LIST__DPDiagnosticsAndUsageTransparencyLog
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS__DPTransparencyLog
+ __OBJC_$_PROTOCOL_METHOD_TYPES__DPTransparencyLog
+ __OBJC_$_PROTOCOL_REFS__DPTransparencyLog
+ __OBJC_CLASS_PROTOCOLS_$__DPAppleIntelligenceTransparencyLog
+ __OBJC_CLASS_PROTOCOLS_$__DPDiagnosticsAndUsageTransparencyLog
+ __OBJC_CLASS_RO_$__DPAppleIntelligenceReportParameters
+ __OBJC_CLASS_RO_$__DPAppleIntelligenceTransparencyLog
+ __OBJC_CLASS_RO_$__DPDiagnosticsAndUsageTransparencyLog
+ __OBJC_CLASS_RO_$__DPTransparencyLogError
+ __OBJC_LABEL_PROTOCOL_$__DPTransparencyLog
+ __OBJC_METACLASS_RO_$__DPAppleIntelligenceReportParameters
+ __OBJC_METACLASS_RO_$__DPAppleIntelligenceTransparencyLog
+ __OBJC_METACLASS_RO_$__DPDiagnosticsAndUsageTransparencyLog
+ __OBJC_METACLASS_RO_$__DPTransparencyLogError
+ __OBJC_PROTOCOL_$__DPTransparencyLog
+ ___53+[_DPDediscoDonation(TaskConfig) defaultValueForKey:]_block_invoke
+ __swift_FORCE_LOAD_$_swiftMetal
+ __swift_FORCE_LOAD_$_swiftMetal_$_DifferentialPrivacy
+ __swift_FORCE_LOAD_$_swiftQuartzCore
+ __swift_FORCE_LOAD_$_swiftQuartzCore_$_DifferentialPrivacy
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers_$_DifferentialPrivacy
+ _kDPKPTransparencyLogReportName
+ _kDPTransparencyLogAppleIntelligenceReport
+ _objc_exception_throw
+ _objc_msgSend$defaultValueForKey:
+ _objc_msgSend$donations
+ _objc_msgSend$errorWithCode:underlyingError:description:
+ _objc_msgSend$exceptionWithName:reason:userInfo:
+ _objc_msgSend$filterMetadataFieldsInSimplifiedLog:
+ _objc_msgSend$formatNoisedData:dimension:
+ _objc_msgSend$initWithDonation:
+ _objc_msgSend$isFeatureEnabled:withError:
+ _objc_msgSend$isValidDonation:
+ _objc_msgSend$ohttp
+ _objc_msgSend$privateAccessToken
+ _objc_msgSend$sendLogWithKey:dimension:taskExpiration:minBatchSize:targetCentralEpsilon:targetCentralDelta:localEpsilon:privateAccessToken:ohttp:
+ _objc_msgSend$targetCentralDelta
+ _objc_msgSend$targetCentralEpsilon
+ _objc_msgSend$taskExpiration
+ _objc_msgSend$transparencyLogReportName
+ _symbolic _____ 19DifferentialPrivacy27AppleIntelligenceReportShimC
+ defaultValueForKey:.defaultValues
+ defaultValueForKey:.onceToken
- +[_DPTransparencyLogCreator convertToHexString:]
- +[_DPTransparencyLogCreator formatSerializedData:]
- +[_DPTransparencyLogCreator inPlaceReplaceOccurrencesOf:with:inBytes:bytesLength:caseSensitiveSearch:repeat:]
- +[_DPTransparencyLogCreator insertIfPossibleObj:intoJSONDictionary:withKey:]
- -[_DPTransparencyLogCreator .cxx_destruct]
- -[_DPTransparencyLogCreator contentsForDonations:withReportName:]
- -[_DPTransparencyLogCreator dataSource]
- -[_DPTransparencyLogCreator filterMetadataFieldsInPrivateEvolutionLog:]
- -[_DPTransparencyLogCreator initWithDonations:error:]
- -[_DPTransparencyLogCreator jsonRepresentationForMetadataInDonation:]
- -[_DPTransparencyLogCreator jsonRepresentationFromParameters:]
- -[_DPTransparencyLogCreator key]
- -[_DPTransparencyLogCreator numDonations]
- -[_DPTransparencyLogCreator rawSerializedData]
- -[_DPTransparencyLogCreator reportName]
- -[_DPTransparencyLogCreator serializedData]
- -[_DPTransparencyLogCreator writeToDiskWithError:]
- OBJC_IVAR_$__DPTransparencyLogCreator._dataSource
- OBJC_IVAR_$__DPTransparencyLogCreator._key
- OBJC_IVAR_$__DPTransparencyLogCreator._numDonations
- OBJC_IVAR_$__DPTransparencyLogCreator._rawSerializedData
- OBJC_IVAR_$__DPTransparencyLogCreator._reportName
- OBJC_IVAR_$__DPTransparencyLogCreator._serializedData
- _OBJC_CLASS_$__DPTransparencyLogCreator
- _OBJC_METACLASS_$__DPTransparencyLogCreator
- __DPTransparencyLogCreatorErrorDomain
- __OBJC_$_CLASS_METHODS__DPDediscoDonation
- __OBJC_$_CLASS_METHODS__DPTransparencyLogCreator
- __OBJC_$_INSTANCE_METHODS__DPDediscoDonation
- __OBJC_$_INSTANCE_METHODS__DPTransparencyLogCreator
- __OBJC_$_INSTANCE_VARIABLES__DPTransparencyLogCreator
- __OBJC_$_PROP_LIST__DPTransparencyLogCreator
- __OBJC_CLASS_RO_$__DPTransparencyLogCreator
- __OBJC_METACLASS_RO_$__DPTransparencyLogCreator
- _kPrivateEvolutionReportName
- _objc_msgSend$filterMetadataFieldsInPrivateEvolutionLog:
CStrings:
+ "AppleIntelligenceTransparencyReport"
+ "Expect '%@' property to have string type, instead got type: '%@'."
+ "Incorrect data type for %@.%@ - expect dictionary"
+ "Incorrect data type for %@.%@.%@ - expect boolean"
+ "Invalid collection ID=%@"
+ "Malformed kDPMetadataDediscoTaskConfig in metadata, expected a dictionary."
+ "Not supported for this build"
+ "Skip transparency log for %{privacy}@"
+ "T@\"NSArray\",R,N,V_donations"
+ "T@\"NSString\",R,N,V_transparencyLogReportName"
+ "TB,R,N,V_ohttp"
+ "TB,R,N,V_privateAccessToken"
+ "TI,R,N,V_dimension"
+ "TI,R,N,V_minBatchSize"
+ "TQ,R,N,V_taskExpiration"
+ "TaskConfig"
+ "Td,R,N,V_targetCentralDelta"
+ "Td,R,N,V_targetCentralEpsilon"
+ "Tokens"
+ "TransparencyLogReportName"
+ "Unsupported version for collectionID=%@"
+ "_DPAppleIntelligenceReportParameters"
+ "_DPAppleIntelligenceReportShim"
+ "_DPAppleIntelligenceTransparencyLog"
+ "_DPDiagnosticsAndUsageTransparencyLog"
+ "_DPTransparencyLog"
+ "_DPTransparencyLogError"
+ "_donations"
+ "_minBatchSize"
+ "_ohttp"
+ "_privateAccessToken"
+ "_targetCentralDelta"
+ "_targetCentralEpsilon"
+ "_taskExpiration"
+ "_transparencyLogReportName"
+ "defaultValueForKey:"
+ "donations"
+ "empty donations"
+ "exceptionWithName:reason:userInfo:"
+ "fedstats:com.apple.insights.other-analysis.analysisB"
+ "filterMetadataFieldsInSimplifiedLog:"
+ "formatNoisedData:dimension:"
+ "getHelperServerName"
+ "getLeaderServerName"
+ "initWithDonation:"
+ "isFeatureEnabled:withError:"
+ "isOHTTPEnabledWithError:"
+ "isPrivateAccessTokenEnabledWithError:"
+ "isTelemetryAllowed"
+ "isValidDonation:"
+ "ohttp"
+ "privateAccessToken"
+ "sendLogWithKey:dimension:taskExpiration:minBatchSize:targetCentralEpsilon:targetCentralDelta:localEpsilon:privateAccessToken:ohttp:"
+ "skip log for collectionID=%@: invalid metadata"
+ "targetCentralDelta"
+ "targetCentralEpsilon"
+ "taskExpiration"
+ "tokensFilePrefix"
+ "transparencyLogReportName"
+ "v72@0:8@16I24Q28I36d40d48d56B64B68"
- "PrivateEvolution"
- "_DPTransparencyLogCreator"
- "filterMetadataFieldsInPrivateEvolutionLog:"
```
