## HomeKitMatter

> `/System/Library/PrivateFrameworks/HomeKitMatter.framework/Versions/A/HomeKitMatter`

```diff

-1278.6.30.0.0
-  __TEXT.__text: 0x14fe9c
+1278.6.31.0.0
+  __TEXT.__text: 0x150688
   __TEXT.__auth_stubs: 0x820
   __TEXT.__objc_methlist: 0x9c4c
   __TEXT.__const: 0x150
   __TEXT.__dlopen_cstrs: 0x58
   __TEXT.__gcc_except_tab: 0x2b38
   __TEXT.__cstring: 0x5e18
-  __TEXT.__oslogstring: 0x23e67
+  __TEXT.__oslogstring: 0x23ffe
   __TEXT.__ustring: 0x68
   __TEXT.__unwind_info: 0x2d08
   __TEXT.__objc_classname: 0x133c

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 4153
-  Symbols:   9546
-  CStrings:  8003
+  Symbols:   9548
+  CStrings:  8006
 
Symbols:
+ logCategory._hmf_once_t195
+ logCategory._hmf_once_t23
+ logCategory._hmf_once_t44
+ logCategory._hmf_once_v196
+ logCategory._hmf_once_v24
+ logCategory._hmf_once_v45
- logCategory._hmf_once_t194
- logCategory._hmf_once_t21
- logCategory._hmf_once_v195
- logCategory._hmf_once_v22
Functions:
~ -[HMMTRSyncClusterNitrogenDioxideConcentrationMeasurement updatedValuePluginMeasuredValueForAttributeReport:responseHandler:] : 2116 -> 2244
~ -[HMMTRSyncClusterNitrogenDioxideConcentrationMeasurement readAttributePluginMeasuredValueWithParams:] : 1896 -> 2008
~ -[HMMTRSyncClusterPM25ConcentrationMeasurement updatedValuePluginMeasuredValueForAttributeReport:responseHandler:] : 2116 -> 2244
~ -[HMMTRSyncClusterPM25ConcentrationMeasurement readAttributePluginMeasuredValueWithParams:] : 1896 -> 2008
~ -[HMMTRSyncClusterTotalVolatileOrganicCompoundsConcentrationMeasurement updatedValuePluginMeasuredValueForAttributeReport:responseHandler:] : 2116 -> 2244
~ -[HMMTRSyncClusterTotalVolatileOrganicCompoundsConcentrationMeasurement readAttributePluginMeasuredValueWithParams:] : 1896 -> 2008
~ -[HMMTRSyncClusterCarbonMonoxideConcentrationMeasurement updatedValuePluginPeakMeasuredValueForAttributeReport:responseHandler:] : 1972 -> 2168
~ -[HMMTRSyncClusterCarbonMonoxideConcentrationMeasurement readAttributePluginPeakMeasuredValueWithParams:] : 1840 -> 1944
~ -[HMMTRSyncClusterCarbonMonoxideConcentrationMeasurement updatedValuePluginMeasuredValueForAttributeReport:responseHandler:] : 2108 -> 2116
~ -[HMMTRSyncClusterCarbonMonoxideConcentrationMeasurement readAttributePluginMeasuredValueWithParams:] : 1900 -> 1912
~ -[HMMTRSyncClusterOzoneConcentrationMeasurement updatedValuePluginMeasuredValueForAttributeReport:responseHandler:] : 2116 -> 2244
~ -[HMMTRSyncClusterOzoneConcentrationMeasurement readAttributePluginMeasuredValueWithParams:] : 1896 -> 2008
~ -[HMMTRSyncClusterCarbonDioxideConcentrationMeasurement updatedValuePluginMeasuredValueForAttributeReport:responseHandler:] : 2108 -> 2236
~ -[HMMTRSyncClusterCarbonDioxideConcentrationMeasurement readAttributePluginMeasuredValueWithParams:] : 1900 -> 2012
~ -[HMMTRSyncClusterPM10ConcentrationMeasurement updatedValuePluginMeasuredValueForAttributeReport:responseHandler:] : 2116 -> 2244
~ -[HMMTRSyncClusterPM10ConcentrationMeasurement readAttributePluginMeasuredValueWithParams:] : 1896 -> 2008
~ -[HMMTRDescriptorClusterManager _verifyHAPCharacteristicSupportWithRequiredAttributeValuesAtCHIPEndpoint:device:callbackQueue:hapServicesToCheckForRequiredAttributeValues:hapCharacteristicsToCheckForRequiredAttributeValues:attributeValuesSupportedDict:attributeValuesRetrievedDict:deviceTopology:server:lastError:completionHandler:] : 2056 -> 2300
~ -[HMMTRDescriptorClusterManager _queryAttributeValueFromClusterAtCHIPEndpoint:device:attributeValuesToCheckDict:attributeValuesSupportedDict:attributeValuesRetrievedDict:callbackQueue:clusterClassName:completionHandler:] : 2236 -> 2260
CStrings:
+ "%{public}@Handling Measured value = %@, Measurement Unit = %@"
+ "%{public}@Read Measured value = %@, Measurement Unit = %@"
+ "%{public}@verifyHAPCharacteristicSupportWithRequiredAttributeValuesAtCHIPEndpoint shortCharacteristicKey = %@, clusterClassName = %@,  hapServicesToCheckForRequiredAttributeValues = %@, hapCharacteristicsToCheckForRequiredAttributeValues = %@, curHAPCharacteristicAttributesToCheck = %@"
```
