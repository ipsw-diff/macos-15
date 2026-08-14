## FedStatsPluginCore

> `/System/Library/PrivateFrameworks/FedStatsPluginCore.framework/Versions/A/FedStatsPluginCore`

```diff

-36.0.0.0.0
-  __TEXT.__text: 0x11264
+38.0.0.0.0
+  __TEXT.__text: 0x11888
   __TEXT.__auth_stubs: 0x260
-  __TEXT.__objc_methlist: 0xbec
-  __TEXT.__const: 0xa0
-  __TEXT.__cstring: 0x1f7a
+  __TEXT.__objc_methlist: 0xc54
+  __TEXT.__const: 0xa8
+  __TEXT.__cstring: 0x201b
   __TEXT.__gcc_except_tab: 0x2c
-  __TEXT.__oslogstring: 0x11b7
-  __TEXT.__unwind_info: 0x2e8
-  __TEXT.__objc_classname: 0x3d3
-  __TEXT.__objc_methname: 0x2562
-  __TEXT.__objc_methtype: 0x37e
-  __TEXT.__objc_stubs: 0x2080
+  __TEXT.__oslogstring: 0x11ec
+  __TEXT.__unwind_info: 0x2f8
+  __TEXT.__objc_classname: 0x3ef
+  __TEXT.__objc_methname: 0x2636
+  __TEXT.__objc_methtype: 0x385
+  __TEXT.__objc_stubs: 0x2180
   __DATA_CONST.__got: 0x288
-  __DATA_CONST.__const: 0xe0
-  __DATA_CONST.__objc_classlist: 0xf0
+  __DATA_CONST.__const: 0xf0
+  __DATA_CONST.__objc_classlist: 0xf8
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x980
-  __DATA_CONST.__objc_superrefs: 0x98
-  __DATA_CONST.__objc_arraydata: 0x108
+  __DATA_CONST.__objc_selrefs: 0x9c0
+  __DATA_CONST.__objc_superrefs: 0xa0
+  __DATA_CONST.__objc_arraydata: 0x118
   __AUTH_CONST.__auth_got: 0x140
-  __AUTH_CONST.__const: 0x240
-  __AUTH_CONST.__cfstring: 0x25c0
-  __AUTH_CONST.__objc_const: 0x1e50
-  __AUTH_CONST.__objc_arrayobj: 0xd8
+  __AUTH_CONST.__const: 0x260
+  __AUTH_CONST.__cfstring: 0x2680
+  __AUTH_CONST.__objc_const: 0x1f68
+  __AUTH_CONST.__objc_arrayobj: 0xc0
+  __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_intobj: 0x18
-  __AUTH.__objc_data: 0x960
-  __DATA.__objc_ivar: 0xc0
-  __DATA.__data: 0x148
+  __AUTH.__objc_data: 0x9b0
+  __DATA.__objc_ivar: 0xc8
+  __DATA.__data: 0x140
   __DATA.__bss: 0xb0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreLocation.framework/Versions/A/CoreLocation

   - /System/Library/PrivateFrameworks/Trial.framework/Versions/A/Trial
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 304
-  Symbols:   912
-  CStrings:  879
+  Functions: 312
+  Symbols:   942
+  CStrings:  900
 
Symbols:
+ +[FedStatsCohortQueryLengthCappedField cohortQueryFieldWithKey:cap:]
+ +[FedStatsPluginMaskingDataParameters parametersWithConfiguration:error:]
+ -[FedStatsCohortQueryLengthCappedField .cxx_destruct]
+ -[FedStatsCohortQueryLengthCappedField cap]
+ -[FedStatsCohortQueryLengthCappedField cohortKeyForParameters:possibleError:]
+ -[FedStatsCohortQueryLengthCappedField initQueryFieldWithKey:cap:]
+ -[FedStatsCohortQueryLengthCappedField keyName]
+ -[FedStatsCohortQueryLengthCappedField padCohortValue:]
+ -[FedStatsPluginMaskingDataParameters .cxx_destruct]
+ -[FedStatsPluginMaskingDataParameters fieldValueSets]
+ -[FedStatsPluginMaskingDataParameters initWithResultCap:fieldValueSets:]
+ -[FedStatsPluginMaskingDataParameters maskedResultsFrom:]
+ -[FedStatsPluginMaskingDataParameters maskingData]
+ -[FedStatsPluginMaskingDataParameters resultCap]
+ -[FedStatsPluginRecipe initWithAssetProvider:recipeIdentifier:clientIdentifier:recordMetadata:dataTypeContent:sqlQuery:cohortNameList:defaultDonationParameters:maskingDataParameters:]
+ -[FedStatsPluginRecipe maskingDataParameters]
+ OBJC_IVAR_$_FedStatsCohortQueryLengthCappedField._cap
+ OBJC_IVAR_$_FedStatsCohortQueryLengthCappedField._keyName
+ OBJC_IVAR_$_FedStatsPluginMaskingDataParameters._fieldValueSets
+ OBJC_IVAR_$_FedStatsPluginMaskingDataParameters._resultCap
+ OBJC_IVAR_$_FedStatsPluginRecipe._maskingDataParameters
+ _OBJC_CLASS_$_FedStatsCohortQueryLengthCappedField
+ _OBJC_CLASS_$_FedStatsPluginMaskingDataParameters
+ _OBJC_CLASS_$_NSConstantDictionary
+ _OBJC_METACLASS_$_FedStatsCohortQueryLengthCappedField
+ _OBJC_METACLASS_$_FedStatsPluginMaskingDataParameters
+ _OUTLINED_FUNCTION_7
+ __OBJC_$_CLASS_METHODS_FedStatsCohortQueryLengthCappedField
+ __OBJC_$_CLASS_METHODS_FedStatsPluginMaskingDataParameters
+ __OBJC_$_INSTANCE_METHODS_FedStatsCohortQueryLengthCappedField
+ __OBJC_$_INSTANCE_METHODS_FedStatsPluginMaskingDataParameters
+ __OBJC_$_INSTANCE_VARIABLES_FedStatsCohortQueryLengthCappedField
+ __OBJC_$_INSTANCE_VARIABLES_FedStatsPluginMaskingDataParameters
+ __OBJC_$_PROP_LIST_FedStatsCohortQueryLengthCappedField
+ __OBJC_$_PROP_LIST_FedStatsPluginMaskingDataParameters
+ __OBJC_CLASS_PROTOCOLS_$_FedStatsCohortQueryLengthCappedField
+ __OBJC_CLASS_RO_$_FedStatsCohortQueryLengthCappedField
+ __OBJC_CLASS_RO_$_FedStatsPluginMaskingDataParameters
+ __OBJC_METACLASS_RO_$_FedStatsCohortQueryLengthCappedField
+ __OBJC_METACLASS_RO_$_FedStatsPluginMaskingDataParameters
+ ___35-[FedStatsPluginSQL initWithError:]_block_invoke_8
+ _checkMaskingDataRequirements
+ _kFedStatsCohortQueryLengthCappedFieldPad
+ _kFedStatsDataCohortSafetyDataVersionCap
+ _kFedStatsPluginMaskingDataSignifierKey
+ _objc_msgSend$addItems:
+ _objc_msgSend$cap
+ _objc_msgSend$cohortQueryFieldWithKey:cap:
+ _objc_msgSend$initQueryFieldWithKey:cap:
+ _objc_msgSend$initWithAssetProvider:recipeIdentifier:clientIdentifier:recordMetadata:dataTypeContent:sqlQuery:cohortNameList:defaultDonationParameters:maskingDataParameters:
+ _objc_msgSend$initWithResultCap:fieldValueSets:
+ _objc_msgSend$keyName
+ _objc_msgSend$maskedResultsFrom:
+ _objc_msgSend$maskingData
+ _objc_msgSend$maskingDataParameters
+ _objc_msgSend$padCohortValue:
+ _objc_msgSend$resultCap
+ _objc_msgSend$stringByPaddingToLength:withString:startingAtIndex:
+ _objc_msgSend$subsampleBooleanValue:samplingRateTrue:samplingRateFalse:error:
+ checkMaskingDataRequirements
- +[FedStatsPluginDummyDataInjectionParameters parametersWithConfiguration:error:]
- -[FedStatsPluginDummyDataInjectionParameters .cxx_destruct]
- -[FedStatsPluginDummyDataInjectionParameters dummyData]
- -[FedStatsPluginDummyDataInjectionParameters fieldValueSets]
- -[FedStatsPluginDummyDataInjectionParameters initWithInjectionRate:fieldValueSets:]
- -[FedStatsPluginDummyDataInjectionParameters injectionRate]
- -[FedStatsPluginDummyDataInjectionParameters shouldInjectDummyData]
- -[FedStatsPluginRecipe dummyDataInjectionParameters]
- -[FedStatsPluginRecipe initWithAssetProvider:recipeIdentifier:clientIdentifier:recordMetadata:dataTypeContent:sqlQuery:cohortNameList:defaultDonationParameters:dummyDataInjectionParameters:]
- OBJC_IVAR_$_FedStatsPluginDummyDataInjectionParameters._fieldValueSets
- OBJC_IVAR_$_FedStatsPluginDummyDataInjectionParameters._injectionRate
- OBJC_IVAR_$_FedStatsPluginRecipe._dummyDataInjectionParameters
- _OBJC_CLASS_$_FedStatsPluginDummyDataInjectionParameters
- _OBJC_CLASS_$_FedStatsUtilsUniformUnitIntervalDistribution
- _OBJC_METACLASS_$_FedStatsPluginDummyDataInjectionParameters
- __OBJC_$_CLASS_METHODS_FedStatsPluginDummyDataInjectionParameters
- __OBJC_$_INSTANCE_METHODS_FedStatsPluginDummyDataInjectionParameters
- __OBJC_$_INSTANCE_VARIABLES_FedStatsPluginDummyDataInjectionParameters
- __OBJC_$_PROP_LIST_FedStatsPluginDummyDataInjectionParameters
- __OBJC_CLASS_RO_$_FedStatsPluginDummyDataInjectionParameters
- __OBJC_METACLASS_RO_$_FedStatsPluginDummyDataInjectionParameters
- _checkDummyDataInjectionRequirements
- _kFedStatsPluginDummyDataInjectionRateLowerBound
- _objc_msgSend$dummyData
- _objc_msgSend$dummyDataInjectionParameters
- _objc_msgSend$initWithAssetProvider:recipeIdentifier:clientIdentifier:recordMetadata:dataTypeContent:sqlQuery:cohortNameList:defaultDonationParameters:dummyDataInjectionParameters:
- _objc_msgSend$initWithInjectionRate:fieldValueSets:
- _objc_msgSend$injectionRate
- _objc_msgSend$shouldInjectDummyData
- checkDummyDataInjectionRequirements
CStrings:
+ "%%FedStatsMaskingData%%"
+ "%@: cannot generate subsample decision"
+ "@\"FedStatsPluginMaskingDataParameters\""
+ "@32@0:8@16Q24"
+ "@32@0:8Q16@24"
+ "Adding masking results to actual query results."
+ "Cannot create masking data parameters from provided configuration"
+ "FedStatsCohortQueryLengthCappedField"
+ "FedStatsPluginMaskingDataParameters"
+ "Masking data = %@"
+ "Masking data parameters field names does not contain the data type '%@'"
+ "Masking data parameters required for this SQL query but not provided properly"
+ "No masking data parameters are available for this recipe."
+ "SQL query '%@' does not match any required pattern for masking data"
+ "SQL query '%@' matches the required pattern '%@' for masking data"
+ "T@\"FedStatsPluginMaskingDataParameters\",R,N,V_maskingDataParameters"
+ "T@\"NSString\",R,N,V_keyName"
+ "TQ,R,N,V_cap"
+ "TQ,R,N,V_resultCap"
+ "X"
+ "_cap"
+ "_keyName"
+ "_maskingDataParameters"
+ "_resultCap"
+ "`configuration['%@']` is not a non-negative number"
+ "addItems:"
+ "cap"
+ "cohortQueryFieldWithKey:cap:"
+ "com.apple.insights.other-analysis.analysisA"
+ "com.apple.insights.other-analysis.analysisB"
+ "fedstats:com.apple.insights.other-analysis.analysisA"
+ "fedstats:com.apple.insights.other-analysis.analysisB"
+ "initQueryFieldWithKey:cap:"
+ "initWithAssetProvider:recipeIdentifier:clientIdentifier:recordMetadata:dataTypeContent:sqlQuery:cohortNameList:defaultDonationParameters:maskingDataParameters:"
+ "initWithResultCap:fieldValueSets:"
+ "keyName"
+ "maskedResultsFrom:"
+ "maskingData"
+ "maskingDataParameters"
+ "padCohortValue:"
+ "resultCap"
+ "stringByPaddingToLength:withString:startingAtIndex:"
+ "subsample"
+ "subsampleBooleanValue:samplingRateTrue:samplingRateFalse:error:"
- "@\"FedStatsPluginDummyDataInjectionParameters\""
- "@32@0:8d16@24"
- "Cannot create dummy data injection parameters from provided configuration"
- "Dummy data = %@"
- "Dummy data injection parameters field names does not contain the data type '%@'"
- "Dummy data injection parameters required for this SQL query but not provided properly"
- "FedStatsPluginDummyDataInjectionParameters"
- "Overriding injection rate %.2f to %.2f"
- "SQL query '%@' does not match any required pattern for dummy data injection"
- "SQL query '%@' matches the required pattern '%@' for dummy data injection"
- "T@\"FedStatsPluginDummyDataInjectionParameters\",R,N,V_dummyDataInjectionParameters"
- "Td,R,N,V_injectionRate"
- "^.*RegionalSafetyAnalysis\\.Disablement.*$"
- "^.*RegionalSafetyAnalysis\\.KeywordID.*$"
- "_dummyDataInjectionParameters"
- "_injectionRate"
- "`configuration['%@']` is not in [0.0,1.0]"
- "dummyData"
- "dummyDataInjectionParameters"
- "initWithAssetProvider:recipeIdentifier:clientIdentifier:recordMetadata:dataTypeContent:sqlQuery:cohortNameList:defaultDonationParameters:dummyDataInjectionParameters:"
- "initWithInjectionRate:fieldValueSets:"
- "injectionRate"
- "shouldInjectDummyData"
```
