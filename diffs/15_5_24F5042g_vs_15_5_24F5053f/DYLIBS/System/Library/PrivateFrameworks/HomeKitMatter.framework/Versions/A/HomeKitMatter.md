## HomeKitMatter

> `/System/Library/PrivateFrameworks/HomeKitMatter.framework/Versions/A/HomeKitMatter`

```diff

-1278.6.20.0.1
-  __TEXT.__text: 0x14f428
+1278.6.26.0.0
+  __TEXT.__text: 0x14fe9c
   __TEXT.__auth_stubs: 0x820
-  __TEXT.__objc_methlist: 0x9bd4
+  __TEXT.__objc_methlist: 0x9c4c
   __TEXT.__const: 0x150
   __TEXT.__dlopen_cstrs: 0x58
-  __TEXT.__gcc_except_tab: 0x2b60
-  __TEXT.__cstring: 0x6066
-  __TEXT.__oslogstring: 0x23d59
+  __TEXT.__gcc_except_tab: 0x2b38
+  __TEXT.__cstring: 0x5e18
+  __TEXT.__oslogstring: 0x23e67
   __TEXT.__ustring: 0x68
   __TEXT.__unwind_info: 0x2d08
   __TEXT.__objc_classname: 0x133c
-  __TEXT.__objc_methname: 0x235c3
-  __TEXT.__objc_methtype: 0x37f0
-  __TEXT.__objc_stubs: 0x14c40
-  __DATA_CONST.__got: 0x920
-  __DATA_CONST.__const: 0xb10
+  __TEXT.__objc_methname: 0x23845
+  __TEXT.__objc_methtype: 0x3832
+  __TEXT.__objc_stubs: 0x14dc0
+  __DATA_CONST.__got: 0x928
+  __DATA_CONST.__const: 0xaf0
   __DATA_CONST.__objc_classlist: 0x3e8
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x120
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6580
+  __DATA_CONST.__objc_selrefs: 0x65f0
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x2c8
   __DATA_CONST.__objc_arraydata: 0x220
   __AUTH_CONST.__auth_got: 0x420
-  __AUTH_CONST.__const: 0x5200
-  __AUTH_CONST.__cfstring: 0x6580
-  __AUTH_CONST.__objc_const: 0xea38
+  __AUTH_CONST.__const: 0x51c0
+  __AUTH_CONST.__cfstring: 0x63a0
+  __AUTH_CONST.__objc_const: 0xea50
   __AUTH_CONST.__objc_intobj: 0x15a8
   __AUTH_CONST.__objc_arrayobj: 0x168
   __AUTH_CONST.__objc_doubleobj: 0x20

   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 4147
-  Symbols:   9531
-  CStrings:  7997
+  Functions: 4153
+  Symbols:   9546
+  CStrings:  8003
 
Symbols:
+ +[HMMTRUtilities dateToMatterEpoch:withTimeZone:]
+ -[HMMTRAccessoryServer _fetchSupportedThreadFeatures]
+ -[HMMTRAccessoryServer _notifyDelegateOfMatterAccessoryIsWEDAccessory:]
+ -[HMMTRAccessoryServer _notifyDelegateOfMatterAccessoryThreadCapabilities:]
+ -[HMMTRAccessoryServer generateAccessoryConfigurationForReason:completionHandler:]
+ -[HMMTRAccessoryServer updateAllCharacteristicValuesPostHAPServiceEnumerationForAccessory:completion:]
+ -[HMMTRDescriptorClusterManager _endpointIncludingClusterID:amongEndpoints:device:error:]
+ -[HMMTRDescriptorClusterManager _fetchAccessoryConfigurationForDevice:endpointID:callbackQueue:]
+ -[HMMTRDescriptorClusterManager _fetchAccessoryConfigurationForDevice:endpointID:clusterID:callbackQueue:]
+ -[HMMTRDescriptorClusterManager endpointForClusterID:mtrDevice:]
+ -[HMMTRDescriptorClusterManager endpointsWithMTRDevice:endpointID:]
+ -[HMMTRDescriptorClusterManager fetchAccessoryConfigurationForDevice:nodeId:server:reasonString:callbackQueue:completionHandler:]
+ -[HMMTRSyncClusterDoorLock removeAllUsers]
+ -[HMMTRVendorMetadataProduct label]
+ -[HMMTRVendorMetadataProduct setLabel:]
+ -[HMMTRYearDaySchedule initWithStartTime:endTime:withTimeZone:]
+ GCC_except_table1020
+ GCC_except_table1091
+ GCC_except_table1142
+ GCC_except_table1149
+ GCC_except_table1200
+ GCC_except_table1208
+ GCC_except_table1245
+ GCC_except_table1282
+ GCC_except_table1501
+ GCC_except_table1542
+ GCC_except_table1692
+ GCC_except_table1693
+ GCC_except_table1714
+ GCC_except_table1715
+ GCC_except_table1716
+ GCC_except_table1725
+ GCC_except_table1726
+ GCC_except_table1789
+ GCC_except_table1797
+ GCC_except_table1874
+ GCC_except_table1997
+ GCC_except_table2024
+ GCC_except_table2057
+ GCC_except_table2067
+ GCC_except_table2069
+ GCC_except_table2123
+ GCC_except_table2172
+ GCC_except_table2240
+ GCC_except_table2490
+ GCC_except_table2496
+ GCC_except_table2545
+ GCC_except_table2555
+ GCC_except_table2588
+ GCC_except_table2628
+ GCC_except_table2653
+ GCC_except_table2654
+ GCC_except_table2678
+ GCC_except_table2679
+ GCC_except_table2693
+ GCC_except_table2712
+ GCC_except_table2727
+ GCC_except_table2733
+ GCC_except_table2746
+ GCC_except_table2749
+ GCC_except_table2753
+ GCC_except_table2765
+ GCC_except_table2771
+ GCC_except_table2790
+ GCC_except_table2796
+ GCC_except_table2803
+ GCC_except_table2816
+ GCC_except_table2869
+ GCC_except_table2870
+ GCC_except_table3232
+ GCC_except_table3234
+ GCC_except_table3237
+ GCC_except_table3243
+ GCC_except_table3246
+ GCC_except_table3260
+ GCC_except_table3276
+ GCC_except_table3337
+ GCC_except_table3338
+ GCC_except_table3363
+ GCC_except_table3364
+ GCC_except_table3400
+ GCC_except_table3403
+ GCC_except_table3412
+ GCC_except_table3431
+ GCC_except_table3434
+ GCC_except_table3473
+ GCC_except_table3477
+ GCC_except_table3494
+ GCC_except_table3496
+ GCC_except_table3519
+ GCC_except_table3578
+ GCC_except_table3622
+ GCC_except_table3639
+ GCC_except_table3665
+ GCC_except_table3669
+ GCC_except_table3684
+ GCC_except_table3685
+ GCC_except_table3697
+ GCC_except_table3737
+ GCC_except_table3757
+ GCC_except_table3810
+ GCC_except_table3815
+ GCC_except_table3818
+ GCC_except_table3896
+ GCC_except_table3897
+ GCC_except_table3954
+ GCC_except_table3957
+ GCC_except_table4070
+ GCC_except_table4081
+ GCC_except_table4085
+ GCC_except_table4109
+ GCC_except_table4132
+ GCC_except_table501
+ GCC_except_table668
+ GCC_except_table671
+ GCC_except_table731
+ GCC_except_table732
+ GCC_except_table733
+ GCC_except_table773
+ GCC_except_table838
+ GCC_except_table848
+ GCC_except_table858
+ GCC_except_table863
+ GCC_except_table906
+ GCC_except_table912
+ GCC_except_table914
+ OBJC_IVAR_$_HMMTRVendorMetadataProduct._label
+ _OBJC_CLASS_$_NSJSONSerialization
+ __102-[HMMTRAccessoryServer updateAllCharacteristicValuesPostHAPServiceEnumerationForAccessory:completion:]_block_invoke
+ __42-[HMMTRSyncClusterDoorLock removeAllUsers]_block_invoke
+ __82-[HMMTRAccessoryServer generateAccessoryConfigurationForReason:completionHandler:]_block_invoke
+ ___102-[HMMTRAccessoryServer updateAllCharacteristicValuesPostHAPServiceEnumerationForAccessory:completion:]_block_invoke
+ ___104-[HMMTRDescriptorClusterManager fetchEndpointsWithMTRDevice:endpointID:callbackQueue:completionHandler:]_block_invoke
+ ___113-[HMMTRDescriptorClusterManager _queryEndpointsForClusterID:endpoints:mtrDevice:callbackQueue:completionHandler:]_block_invoke
+ ___42-[HMMTRSyncClusterDoorLock removeAllUsers]_block_invoke
+ ___42-[HMMTRSyncClusterDoorLock removeAllUsers]_block_invoke_2
+ ___42-[HMMTRSyncClusterDoorLock removeAllUsers]_block_invoke_3
+ ___82-[HMMTRAccessoryServer generateAccessoryConfigurationForReason:completionHandler:]_block_invoke
+ ___82-[HMMTRAccessoryServer generateAccessoryConfigurationForReason:completionHandler:]_block_invoke_2
+ ___block_descriptor_40_e8_32bs_e18_v16?0"NSString"8l
+ ___block_descriptor_48_e8_32s40s_e30_v24?0"NSString"8"NSError"16l
+ _objc_msgSend$_endpointIncludingClusterID:amongEndpoints:device:error:
+ _objc_msgSend$_fetchAccessoryConfigurationForDevice:endpointID:callbackQueue:
+ _objc_msgSend$_fetchAccessoryConfigurationForDevice:endpointID:clusterID:callbackQueue:
+ _objc_msgSend$_fetchSupportedThreadFeatures
+ _objc_msgSend$_notifyDelegateOfMatterAccessoryIsWEDAccessory:
+ _objc_msgSend$_notifyDelegateOfMatterAccessoryThreadCapabilities:
+ _objc_msgSend$accessoryProductLabel
+ _objc_msgSend$dataWithJSONObject:options:error:
+ _objc_msgSend$dateToMatterEpoch:withTimeZone:
+ _objc_msgSend$endpointForClusterID:mtrDevice:
+ _objc_msgSend$endpointsWithMTRDevice:endpointID:
+ _objc_msgSend$fetchAccessoryConfigurationForDevice:nodeId:server:reasonString:callbackQueue:completionHandler:
+ _objc_msgSend$generateAccessoryConfigurationForReason:completionHandler:
+ _objc_msgSend$localizedDescription
+ _objc_msgSend$notifyMatterAccessoryIsWEDAccessory:
+ _objc_msgSend$notifyMatterAccessoryThreadCapabilities:
+ _objc_msgSend$readAttributeSupportedThreadFeaturesWithParams:
+ _objc_msgSend$secondsFromGMTForDate:
+ _objc_msgSend$updateAllCharacteristicValuesPostHAPServiceEnumerationForAccessory:completion:
+ logCategory._hmf_once_t194
+ logCategory._hmf_once_t274
+ logCategory._hmf_once_t580
+ logCategory._hmf_once_v195
+ logCategory._hmf_once_v275
+ logCategory._hmf_once_v581
- +[HMMTRUtilities dateToMatterEpoch:]
- -[HMMTRAccessoryServer generateStateCaptureInformationForReason:completionHandler:]
- -[HMMTRDescriptorClusterManager _fetchStateCaptureInformationForDevice:endpointID:callbackQueue:]
- -[HMMTRDescriptorClusterManager _fetchStateCaptureInformationForDevice:endpointID:clusterID:callbackQueue:]
- -[HMMTRDescriptorClusterManager fetchStateCaptureInformationForDevice:nodeId:server:callbackQueue:completionHandler:]
- -[HMMTRSyncClusterDoorLock removeHomeUser]
- -[HMMTRVendorMetadataProduct model]
- -[HMMTRVendorMetadataProduct setModel:]
- -[HMMTRYearDaySchedule initWithStartTime:endTime:]
- GCC_except_table1016
- GCC_except_table1087
- GCC_except_table1134
- GCC_except_table1145
- GCC_except_table1177
- GCC_except_table1203
- GCC_except_table1211
- GCC_except_table1248
- GCC_except_table1285
- GCC_except_table1504
- GCC_except_table1545
- GCC_except_table1696
- GCC_except_table1698
- GCC_except_table1719
- GCC_except_table1720
- GCC_except_table1731
- GCC_except_table1732
- GCC_except_table1733
- GCC_except_table1792
- GCC_except_table1800
- GCC_except_table1877
- GCC_except_table2000
- GCC_except_table2027
- GCC_except_table2060
- GCC_except_table2070
- GCC_except_table2072
- GCC_except_table2121
- GCC_except_table2170
- GCC_except_table2238
- GCC_except_table2488
- GCC_except_table2494
- GCC_except_table2543
- GCC_except_table2553
- GCC_except_table2586
- GCC_except_table2624
- GCC_except_table2650
- GCC_except_table2651
- GCC_except_table2670
- GCC_except_table2671
- GCC_except_table2689
- GCC_except_table2710
- GCC_except_table2725
- GCC_except_table2731
- GCC_except_table2744
- GCC_except_table2747
- GCC_except_table2751
- GCC_except_table2763
- GCC_except_table2767
- GCC_except_table2788
- GCC_except_table2794
- GCC_except_table2801
- GCC_except_table2814
- GCC_except_table2867
- GCC_except_table2868
- GCC_except_table3228
- GCC_except_table3229
- GCC_except_table3230
- GCC_except_table3239
- GCC_except_table3242
- GCC_except_table3256
- GCC_except_table3272
- GCC_except_table3333
- GCC_except_table3334
- GCC_except_table3359
- GCC_except_table3360
- GCC_except_table3396
- GCC_except_table3404
- GCC_except_table3423
- GCC_except_table3426
- GCC_except_table3464
- GCC_except_table3468
- GCC_except_table3484
- GCC_except_table3486
- GCC_except_table3509
- GCC_except_table3569
- GCC_except_table3613
- GCC_except_table3630
- GCC_except_table3656
- GCC_except_table3662
- GCC_except_table3677
- GCC_except_table3678
- GCC_except_table3683
- GCC_except_table3730
- GCC_except_table3750
- GCC_except_table3803
- GCC_except_table3808
- GCC_except_table3811
- GCC_except_table3889
- GCC_except_table3890
- GCC_except_table3947
- GCC_except_table3950
- GCC_except_table4064
- GCC_except_table4069
- GCC_except_table4079
- GCC_except_table4103
- GCC_except_table4126
- GCC_except_table497
- GCC_except_table664
- GCC_except_table667
- GCC_except_table727
- GCC_except_table728
- GCC_except_table729
- GCC_except_table769
- GCC_except_table834
- GCC_except_table840
- GCC_except_table842
- GCC_except_table859
- GCC_except_table902
- GCC_except_table908
- GCC_except_table910
- OBJC_IVAR_$_HMMTRVendorMetadataProduct._model
- __43-[HMMTRAccessoryServer _unpair:completion:]_block_invoke_2
- __83-[HMMTRAccessoryServer generateStateCaptureInformationForReason:completionHandler:]_block_invoke
- __92-[HMMTROTAProviderDelegate handleNotifyUpdateAppliedForNodeID:controller:params:completion:]_block_invoke
- ___42-[HMMTRSyncClusterDoorLock removeHomeUser]_block_invoke
- ___43-[HMMTRAccessoryServer _unpair:completion:]_block_invoke_3
- ___63-[HMMTRAccessoryServer removeAllPairingsWithCompletionHandler:]_block_invoke_3
- ___63-[HMMTRAccessoryServer removeAllPairingsWithCompletionHandler:]_block_invoke_4
- ___83-[HMMTRAccessoryServer generateStateCaptureInformationForReason:completionHandler:]_block_invoke
- ___92-[HMMTROTAProviderDelegate handleNotifyUpdateAppliedForNodeID:controller:params:completion:]_block_invoke
- ___92-[HMMTROTAProviderDelegate handleNotifyUpdateAppliedForNodeID:controller:params:completion:]_block_invoke_2
- ___97-[HMMTROTAProviderDelegate applyUpdateTimerExpiredForAccessoryServer:softwareVersion:didTimeout:]_block_invoke_3
- ___block_descriptor_32_e29_"HMFFuture"16?0"NSNumber"8l
- ___block_descriptor_64_e8_32s40s48s56bs_e18_v16?0"NSString"8l
- ___block_descriptor_64_e8_32s40s48s56bs_e31_{_HMFFutureBlockOutcome=q}8?0l
- _objc_msgSend$_fetchStateCaptureInformationForDevice:endpointID:callbackQueue:
- _objc_msgSend$_fetchStateCaptureInformationForDevice:endpointID:clusterID:callbackQueue:
- _objc_msgSend$dateToMatterEpoch:
- _objc_msgSend$fetchStateCaptureInformationForDevice:nodeId:server:callbackQueue:completionHandler:
- _objc_msgSend$generateStateCaptureInformationForReason:completionHandler:
- _objc_msgSend$model
- _objc_msgSend$runBlockForAllEndpointsWithClusterID:device:callbackQueue:block:
- logCategory._hmf_once_t193
- logCategory._hmf_once_t273
- logCategory._hmf_once_t29
- logCategory._hmf_once_t48
- logCategory._hmf_once_t571
- logCategory._hmf_once_v194
- logCategory._hmf_once_v274
- logCategory._hmf_once_v30
- logCategory._hmf_once_v49
- logCategory._hmf_once_v572
CStrings:
+ "%{public}@Accessory Configuration for %@/%@(%@) %@"
+ "%{public}@Accessory Configuration: Generate Accessory Configuration for '%@' by reason : %@"
+ "%{public}@Accessory Configuration: JSON conversion failed: %@"
+ "%{public}@Accessory Configuration: No Endpoints In Use at endpoint 0 of node %@"
+ "%{public}@Accessory Configuration: Setting timer to capture state information due to configuration change for accessory %@, timeout is %@"
+ "%{public}@Accessory Configuration: Setting timer to capture state information for %@ due to matter device reachable notification, timeout is %@"
+ "%{public}@Accessory Configuration: completed for server:%@ with Error: %@."
+ "%{public}@Accessory server operations disabled. Aborting generating accessory configuration information."
+ "%{public}@Characteristics Operation Queue: generate accessory configuration information job(%lu) complete."
+ "%{public}@Characteristics Operation Queue: generate accessory configuration information job(%lu) queued."
+ "%{public}@Characteristics Operation Queue: generate accessory configuration information job(%lu) started."
+ "%{public}@Failed to get endpoints for node %@"
+ "%{public}@No Matter device available to fetch SupportedThreadFeatures"
+ "%{public}@No Matter device controller available to generate accessory configuration information"
+ "%{public}@No endpoint found to contain Network Commissioning Cluster to fetch SupportedThreadFeatures"
+ "%{public}@No product label information available so using default name: %@"
+ "%{public}@Notifying delegate of Thread capabilities %@"
+ "%{public}@Notifying delegate of isWEDAccessory %@"
+ "%{public}@Processing handleNotifyUpdateAppliedForNodeID command {nodeID = %@, updateToken = %@, newVersion = %@}, is simply returning OK without performing any additional processing."
+ "%{public}@RockSetting was read with unexpected class type %@"
+ "%{public}@RockSupport was read with unexpected class type %@"
+ "%{public}@SupportedThreadFeatures attribute was nil"
+ "%{public}@Updating all characteristic values from MTRDevice cache for accessory %@"
+ "%{public}@Updating product label from %@ to %@"
+ "%{public}@Using metadata product label: %@ and vendor name: %@"
+ "%{public}@[Flow: %@] Failed to find current fabric index so not removing any users."
+ "%{public}@[NewFlow: %@] Removing all users"
+ "@48@0:8@16@24@32^@40"
+ "Accessory Configuration for %@/%@(%@)"
+ "Attributes"
+ "ClientClusters"
+ "ClusterID"
+ "ClusterInfo"
+ "ClusterRevision"
+ "DevicePaired"
+ "DeviceTypes"
+ "EndpointData"
+ "EndpointID"
+ "Endpoints"
+ "Events"
+ "Label"
+ "Reason"
+ "ServerClusters"
+ "T@\"NSString\",C,V_label"
+ "Time"
+ "_endpointIncludingClusterID:amongEndpoints:device:error:"
+ "_fetchAccessoryConfigurationForDevice:endpointID:callbackQueue:"
+ "_fetchAccessoryConfigurationForDevice:endpointID:clusterID:callbackQueue:"
+ "_fetchSupportedThreadFeatures"
+ "_label"
+ "_notifyDelegateOfMatterAccessoryIsWEDAccessory:"
+ "_notifyDelegateOfMatterAccessoryThreadCapabilities:"
+ "accessoryProductLabel"
+ "controller:commissioneeHasReceivedNetworkCredentials:"
+ "dataWithJSONObject:options:error:"
+ "dateToMatterEpoch:withTimeZone:"
+ "endpointForClusterID:mtrDevice:"
+ "endpointsWithMTRDevice:endpointID:"
+ "fetchAccessoryConfigurationForDevice:nodeId:server:reasonString:callbackQueue:completionHandler:"
+ "generateAccessoryConfigurationForReason:completionHandler:"
+ "hmmtr.descriptorClusterManager.temporary"
+ "initWithStartTime:endTime:withTimeZone:"
+ "localizedDescription"
+ "notifyMatterAccessoryIsWEDAccessory:"
+ "notifyMatterAccessoryThreadCapabilities:"
+ "readAttributeSupportedThreadFeaturesWithParams:"
+ "removeAllUsers"
+ "secondsFromGMTForDate:"
+ "supportedThreadFeatures"
+ "updateAllCharacteristicValuesPostHAPServiceEnumerationForAccessory:completion:"
+ "v32@0:8@\"MTRDeviceController\"16@\"NSNumber\"24"
+ "yyyy-MM-dd'T'HH:mm:ssZ"
- " %@ (revision %@), "
- " }; }; "
- "%{public}@Accessory server operations disabled. Aborting generating state capture information."
- "%{public}@Characteristics Operation Queue: generate state capture information job(%lu) complete."
- "%{public}@Characteristics Operation Queue: generate state capture information job(%lu) queued."
- "%{public}@Characteristics Operation Queue: generate state capture information job(%lu) started."
- "%{public}@No Matter device controller available to generate state capture information"
- "%{public}@No paired accessory found for nodeID %@ - ignore notification"
- "%{public}@No product name information available so using default name: %@"
- "%{public}@Processing handleNotifyUpdateAppliedForNodeID command {nodeID = %@, updateToken = %@, newVersion = %@}"
- "%{public}@Provided token %@ doesn't match assigned token %@ for accessory %@, accepting anyways"
- "%{public}@Received unexpected NotifyUpdateApplied when we were still waiting for ApplyUpdateRequest after BDX transfer completed for accessory %@"
- "%{public}@Request to generate state capture information"
- "%{public}@State Capture: Information for endpoint %@: %@"
- "%{public}@State Capture: Information for endpoint 0: %@"
- "%{public}@State Capture: Information generated for %@, triggered by reason %@ : %@"
- "%{public}@State Capture: No Endpoints In Use at endpoint 0 of node %@"
- "%{public}@State Capture: Setting timer to capture state information due to configuration change for accessory %@, timeout is %@"
- "%{public}@State Capture: Setting timer to capture state information for %@ due to matter device reachable notification, timeout is %@"
- "%{public}@State Capture: Timer expired, generate State Capture Information for Device Connected"
- "%{public}@State Capture: Timer expired, generate State Capture Information for configuration change"
- "%{public}@State Capture: completed for server:%@ with Error: %@."
- "%{public}@Updating product name from %@ to %@"
- "%{public}@Using metadata product name: %@ and vendor name: %@"
- "%{public}@[NewFlow: %@] Removing home user"
- "( ClusterID:%@ ClusterInfo: %@ ), "
- "( NodeID: %@; FabricID: %@, "
- "(AcceptedCommands: %@), "
- "(AcceptedCommands: ()), "
- "(Attributes: %@)"
- "(Attributes: ()), "
- "(ClientClusters: "
- "(ClientClusters: ()),"
- "(ClusterID : %@, ClusterInfo : %@), "
- "(ClusterRevision: %@), "
- "(DeviceTypes : ()), "
- "(DeviceTypes: "
- "(Events: %@), "
- "(Events: ()), "
- "(FeatureMap: %@), "
- "(GeneratedCommands: %@) "
- "(GeneratedCommands: ()), "
- "(PartsList: %@), "
- "(PartsList: ()), "
- "(ServerClusters : "
- "(ServerClusters : () ),"
- ")"
- "), "
- "HMMTRAccessoryServer State for %@/%@(%@)"
- "Model"
- "Name: %@, NodeID: %@, FabricID: %@, Category %@, ObjectID: %@, No state capture information available."
- "Name: %@, NodeID: %@, FabricID: %@, Category: %@, ObjectID: %@, State capture information: %@"
- "Reason: %@, Time: %@, Data: %@"
- "T@\"NSString\",C,V_model"
- "_fetchStateCaptureInformationForDevice:endpointID:callbackQueue:"
- "_fetchStateCaptureInformationForDevice:endpointID:clusterID:callbackQueue:"
- "_model"
- "dateToMatterEpoch:"
- "fetchStateCaptureInformationForDevice:nodeId:server:callbackQueue:completionHandler:"
- "generateStateCaptureInformationForReason:completionHandler:"
- "initWithStartTime:endTime:"
- "model"
- "removeHomeUser"
- "rockSettingValue"
- "{EndpointID: %@, EndpointData: %@}, "
- "{Endpoints: {EndpointID: %@, EndpointData: %@ }, "
```
