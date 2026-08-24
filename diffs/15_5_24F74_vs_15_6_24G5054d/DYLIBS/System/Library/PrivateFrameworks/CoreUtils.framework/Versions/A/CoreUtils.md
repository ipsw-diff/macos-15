## CoreUtils

> `/System/Library/PrivateFrameworks/CoreUtils.framework/Versions/A/CoreUtils`

```diff

-780.15.0.0.0
-  __TEXT.__text: 0x11d450
+790.21.0.0.0
+  __TEXT.__text: 0x120178
   __TEXT.__auth_stubs: 0x2af0
-  __TEXT.__objc_methlist: 0x9e80
-  __TEXT.__cstring: 0x217ed
-  __TEXT.__const: 0x2350
+  __TEXT.__objc_methlist: 0x9f20
+  __TEXT.__cstring: 0x21e33
+  __TEXT.__const: 0x23b8
   __TEXT.__gcc_except_tab: 0x1d1c
-  __TEXT.__oslogstring: 0xdef
-  __TEXT.__unwind_info: 0x3958
+  __TEXT.__oslogstring: 0xe8a
+  __TEXT.__unwind_info: 0x3988
   __TEXT.__eh_frame: 0x50
-  __TEXT.__objc_classname: 0xcdf
-  __TEXT.__objc_methname: 0x16333
-  __TEXT.__objc_methtype: 0x44fb
-  __TEXT.__objc_stubs: 0xa420
-  __DATA_CONST.__got: 0x640
+  __TEXT.__objc_classname: 0xce2
+  __TEXT.__objc_methname: 0x165c0
+  __TEXT.__objc_methtype: 0x453a
+  __TEXT.__objc_stubs: 0xa540
+  __DATA_CONST.__got: 0x658
   __DATA_CONST.__const: 0x1490
   __DATA_CONST.__objc_classlist: 0x360
   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x150
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4e80
+  __DATA_CONST.__objc_selrefs: 0x4ee8
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x248
   __DATA_CONST.__objc_arraydata: 0x8
   __AUTH_CONST.__auth_got: 0x1588
-  __AUTH_CONST.__const: 0x38f0
-  __AUTH_CONST.__cfstring: 0x3fa0
-  __AUTH_CONST.__objc_const: 0x13b00
+  __AUTH_CONST.__const: 0x3f70
+  __AUTH_CONST.__cfstring: 0x3fc0
+  __AUTH_CONST.__objc_const: 0x13bb8
   __AUTH_CONST.__objc_intobj: 0x180
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH.__objc_data: 0x5f0
-  __AUTH.__data: 0x1f0
-  __DATA.__objc_ivar: 0x14ec
+  __AUTH.__data: 0x1f8
+  __DATA.__objc_ivar: 0x14fc
   __DATA.__data: 0x3130
-  __DATA.__bss: 0xf70
+  __DATA.__bss: 0x1120
   __DATA.__common: 0x2a
   __DATA_DIRTY.__objc_data: 0x1bd0
   __DATA_DIRTY.__data: 0xa38

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 5724
-  Symbols:   11382
-  CStrings:  9366
+  Functions: 5797
+  Symbols:   11519
+  CStrings:  9425
 
Symbols:
+ +[CUFile realPath:dispatchQueue:completionHandler:]
+ +[CUFile realPath:error:]
+ +[CUPairingManager copySystemPairingIdentifierWithFlags:error:]
+ -[CUFile _getLengthWithCompletionHandler:]
+ -[CUFile getLengthWithCompletionHandler:]
+ -[CUNANDataSession setWfaConnectionMode:]
+ -[CUNANDataSession setWfaServiceSpecificInfo:]
+ -[CUNANDataSession wfaConnectionMode]
+ -[CUNANDataSession wfaServiceSpecificInfo]
+ -[CUNANSubscriber setWfaDiscoveryMode:]
+ -[CUNANSubscriber wfaDiscoveryMode]
+ -[CUWiFiManager _wifiHandleEvent:]
+ GCC_except_table1234
+ GCC_except_table1315
+ GCC_except_table1321
+ GCC_except_table1322
+ GCC_except_table1325
+ GCC_except_table1398
+ GCC_except_table1399
+ GCC_except_table1430
+ GCC_except_table1433
+ GCC_except_table1439
+ GCC_except_table1444
+ GCC_except_table1447
+ GCC_except_table1498
+ GCC_except_table1499
+ GCC_except_table1536
+ GCC_except_table1590
+ GCC_except_table1592
+ GCC_except_table1597
+ GCC_except_table1609
+ GCC_except_table1611
+ GCC_except_table1623
+ GCC_except_table2110
+ GCC_except_table2150
+ GCC_except_table2180
+ GCC_except_table2335
+ GCC_except_table2336
+ GCC_except_table2355
+ GCC_except_table2390
+ GCC_except_table2465
+ GCC_except_table2489
+ GCC_except_table2523
+ GCC_except_table2527
+ GCC_except_table2590
+ GCC_except_table2591
+ GCC_except_table2593
+ GCC_except_table2594
+ GCC_except_table2596
+ GCC_except_table2601
+ GCC_except_table2604
+ GCC_except_table2607
+ GCC_except_table2610
+ GCC_except_table2613
+ GCC_except_table2620
+ GCC_except_table2623
+ GCC_except_table2692
+ GCC_except_table3010
+ GCC_except_table3011
+ GCC_except_table3070
+ GCC_except_table3141
+ GCC_except_table3145
+ GCC_except_table3189
+ GCC_except_table3192
+ GCC_except_table3193
+ GCC_except_table3195
+ GCC_except_table3478
+ GCC_except_table3909
+ GCC_except_table4196
+ GCC_except_table4204
+ GCC_except_table4212
+ GCC_except_table4364
+ GCC_except_table4368
+ GCC_except_table4370
+ GCC_except_table4372
+ GCC_except_table4395
+ GCC_except_table4479
+ GCC_except_table4481
+ GCC_except_table4482
+ GCC_except_table4515
+ GCC_except_table4517
+ GCC_except_table4518
+ GCC_except_table4520
+ GCC_except_table4521
+ GCC_except_table4522
+ GCC_except_table4524
+ GCC_except_table4525
+ GCC_except_table4526
+ GCC_except_table4527
+ GCC_except_table4528
+ GCC_except_table4529
+ GCC_except_table4537
+ GCC_except_table4539
+ GCC_except_table4540
+ GCC_except_table4543
+ GCC_except_table4546
+ GCC_except_table4547
+ GCC_except_table4548
+ GCC_except_table4549
+ GCC_except_table4550
+ GCC_except_table4551
+ GCC_except_table4553
+ GCC_except_table4554
+ GCC_except_table4555
+ GCC_except_table4556
+ GCC_except_table4557
+ GCC_except_table4558
+ GCC_except_table4559
+ GCC_except_table4560
+ GCC_except_table4561
+ GCC_except_table4562
+ GCC_except_table4563
+ GCC_except_table4564
+ GCC_except_table4565
+ GCC_except_table4567
+ GCC_except_table4568
+ GCC_except_table4569
+ GCC_except_table4571
+ GCC_except_table5212
+ GCC_except_table5217
+ GCC_except_table5221
+ GCC_except_table5288
+ GCC_except_table5298
+ GCC_except_table5308
+ GCC_except_table5317
+ GCC_except_table5641
+ GCC_except_table5642
+ GCC_except_table5655
+ GCC_except_table689
+ GCC_except_table776
+ GCC_except_table791
+ GCC_except_table793
+ GCC_except_table796
+ GCC_except_table995
+ OBJC_IVAR_$_CUNANDataSession._wfaConnectionMode
+ OBJC_IVAR_$_CUNANDataSession._wfaServiceSpecificInfo
+ OBJC_IVAR_$_CUNANSubscriber._wfaDiscoveryMode
+ OBJC_IVAR_$_CUWiFiManager._wifiInterface
+ _AWDLTrafficRegistrationServiceMacVirtualDisplayFunction
+ _HTTPClientSetClientContext
+ __OBJC_$_CLASS_METHODS_CUFile
+ __SetupClientAuthenticationFailed
+ __SetupServerAuthenticationFailed
+ ___41-[CUFile getLengthWithCompletionHandler:]_block_invoke
+ ___51+[CUFile realPath:dispatchQueue:completionHandler:]_block_invoke
+ ___initValAWDLTrafficRegistrationServiceAirPlay_block_invoke
+ ___initValAWDLTrafficRegistrationServiceDeviceToDeviceMigration_block_invoke
+ ___initValAWDLTrafficRegistrationServiceMPRemoteCamera_block_invoke
+ ___initValAWDLTrafficRegistrationServiceMacVirtualDisplay_block_invoke
+ ___initValAWDLTrafficRegistrationServiceRemoteCamera_block_invoke
+ ___initValAWDLTrafficRegistrationServiceRemoteScreen_block_invoke
+ ___initValAWDLTrafficRegistrationServiceSidecar_block_invoke
+ ___initValAWDLTrafficRegistrationServiceTVRemoteCamera_block_invoke
+ ___initValAWDLTrafficRegistrationServiceUniversalControl_block_invoke
+ ___initValCBAdvertisementDataAppleMfgData_block_invoke
+ ___initValCBAdvertisementDataDeviceAddress_block_invoke
+ ___initValCBAdvertisementDataIsConnectable_block_invoke
+ ___initValCBAdvertisementDataManufacturerDataKey_block_invoke
+ ___initValCBCentralManagerOptionShowPowerAlertKey_block_invoke
+ ___initValCBCentralManagerScanOptionActive_block_invoke
+ ___initValCBCentralManagerScanOptionAllowDuplicatesKey_block_invoke
+ ___initValCBCentralManagerScanOptionMatchingRuleKey_block_invoke
+ ___initValCBCentralManagerScanOptionMatchingRuleMaskKey_block_invoke
+ ___initValCBCentralManagerScanOptionMatchingRulePayloadKey_block_invoke
+ ___initValCBCentralManagerScanOptionMatchingRuleRSSIKey_block_invoke
+ ___initValCBCentralManagerScanOptionMatchingRuleTypeKey_block_invoke
+ ___initValCBCentralManagerScanOptionScanInterval_block_invoke
+ ___initValCBCentralManagerScanOptionScanWindow_block_invoke
+ ___initValCBConnectPeripheralOptionClientBundleID_block_invoke
+ ___initValCBConnectPeripheralOptionConnectionUseCase_block_invoke
+ ___initValCBManagerIsPrivilegedDaemonKey_block_invoke
+ ___initValCBManagerNeedsRestrictedStateOperation_block_invoke
+ ___initValCBPeripheralManagerOptionShowPowerAlertKey_block_invoke
+ ___initValEasyConfigKey_DeviceID_block_invoke
+ ___initValEasyConfigKey_Flags_block_invoke
+ ___initValEasyConfigKey_ReasonError_block_invoke
+ ___initValFBSDisplayLayoutElementControlCenterIdentifier_block_invoke
+ ___initValFBSDisplayLayoutElementLockScreenIdentifier_block_invoke
+ ___initValFBSDisplayLayoutElementNotificationCenterIdentifier_block_invoke
+ ___initValFBSDisplayLayoutElementSiriIdentifier_block_invoke
+ ___initValFMFDevicesChangedNotification_block_invoke
+ ___initValFMFMeDeviceChangedNotification_block_invoke
+ ___initValNSFontAttributeName_block_invoke
+ ___initValRPOptionTimeoutSeconds_block_invoke
+ ___initValTUCallCenterCallConnectedNotification_block_invoke
+ ___initValTUCallCenterCallStatusChangedNotification_block_invoke
+ ___initValTUCallCenterVideoCallStatusChangedNotification_block_invoke
+ ___initValUNNotificationDefaultActionIdentifier_block_invoke
+ ___initValUNNotificationDismissActionIdentifier_block_invoke
+ ___initValkCAMediaTimingFunctionEaseIn_block_invoke
+ ___initValkCAMediaTimingFunctionEaseOut_block_invoke
+ ___initValkSLSPowerStateNotificationCallbackOptions_block_invoke
+ ___initValkSLSPowerStateNotificationRegistrationID_block_invoke
+ ___initValkSLSPowerStateNotificationRegistrationState_block_invoke
+ __initValCBManagerIsPrivilegedDaemonKey_block_invoke
+ __initValCBManagerNeedsRestrictedStateOperation_block_invoke
+ _constantValAWDLTrafficRegistrationServiceMacVirtualDisplay
+ _getAWDLTrafficRegistrationServiceMacVirtualDisplay
+ _initValAWDLTrafficRegistrationServiceMacVirtualDisplay
+ _objc_msgSend$_getLengthWithCompletionHandler:
+ _objc_msgSend$copySystemPairingIdentifierWithFlags:error:
+ _objc_msgSend$finishAndReturnError:
+ _objc_msgSend$finishWithM3:error:
+ _objc_msgSend$generateM1AndReturnError:
+ _objc_msgSend$generateM2WithM1:error:
+ _objc_msgSend$generateM3WithM2:error:
+ _objc_msgSend$initWithPasswordPtr:passwordLength:
+ _objc_msgSend$pairingIdentityWithPrivateKey:attemptToReadFromKeychain:completionHandler:
+ _objc_msgSend$realPath:error:
+ _softLinkOnceAWDLTrafficRegistrationServiceAirPlay
+ _softLinkOnceAWDLTrafficRegistrationServiceDeviceToDeviceMigration
+ _softLinkOnceAWDLTrafficRegistrationServiceMPRemoteCamera
+ _softLinkOnceAWDLTrafficRegistrationServiceMacVirtualDisplay
+ _softLinkOnceAWDLTrafficRegistrationServiceRemoteCamera
+ _softLinkOnceAWDLTrafficRegistrationServiceRemoteScreen
+ _softLinkOnceAWDLTrafficRegistrationServiceSidecar
+ _softLinkOnceAWDLTrafficRegistrationServiceTVRemoteCamera
+ _softLinkOnceAWDLTrafficRegistrationServiceUniversalControl
+ _softLinkOnceCBAdvertisementDataAppleMfgData
+ _softLinkOnceCBAdvertisementDataDeviceAddress
+ _softLinkOnceCBAdvertisementDataIsConnectable
+ _softLinkOnceCBAdvertisementDataManufacturerDataKey
+ _softLinkOnceCBCentralManagerOptionShowPowerAlertKey
+ _softLinkOnceCBCentralManagerScanOptionActive
+ _softLinkOnceCBCentralManagerScanOptionAllowDuplicatesKey
+ _softLinkOnceCBCentralManagerScanOptionMatchingRuleKey
+ _softLinkOnceCBCentralManagerScanOptionMatchingRuleMaskKey
+ _softLinkOnceCBCentralManagerScanOptionMatchingRulePayloadKey
+ _softLinkOnceCBCentralManagerScanOptionMatchingRuleRSSIKey
+ _softLinkOnceCBCentralManagerScanOptionMatchingRuleTypeKey
+ _softLinkOnceCBCentralManagerScanOptionScanInterval
+ _softLinkOnceCBCentralManagerScanOptionScanWindow
+ _softLinkOnceCBConnectPeripheralOptionClientBundleID
+ _softLinkOnceCBConnectPeripheralOptionConnectionUseCase
+ _softLinkOnceCBManagerIsPrivilegedDaemonKey
+ _softLinkOnceCBManagerNeedsRestrictedStateOperation
+ _softLinkOnceCBPeripheralManagerOptionShowPowerAlertKey
+ _softLinkOnceEasyConfigKey_DeviceID
+ _softLinkOnceEasyConfigKey_Flags
+ _softLinkOnceEasyConfigKey_ReasonError
+ _softLinkOnceFBSDisplayLayoutElementControlCenterIdentifier
+ _softLinkOnceFBSDisplayLayoutElementLockScreenIdentifier
+ _softLinkOnceFBSDisplayLayoutElementNotificationCenterIdentifier
+ _softLinkOnceFBSDisplayLayoutElementSiriIdentifier
+ _softLinkOnceFMFDevicesChangedNotification
+ _softLinkOnceFMFMeDeviceChangedNotification
+ _softLinkOnceNSFontAttributeName
+ _softLinkOnceRPOptionTimeoutSeconds
+ _softLinkOnceTUCallCenterCallConnectedNotification
+ _softLinkOnceTUCallCenterCallStatusChangedNotification
+ _softLinkOnceTUCallCenterVideoCallStatusChangedNotification
+ _softLinkOnceUNNotificationDefaultActionIdentifier
+ _softLinkOnceUNNotificationDismissActionIdentifier
+ _softLinkOncekCAMediaTimingFunctionEaseIn
+ _softLinkOncekCAMediaTimingFunctionEaseOut
+ _softLinkOncekSLSPowerStateNotificationCallbackOptions
+ _softLinkOncekSLSPowerStateNotificationRegistrationID
+ _softLinkOncekSLSPowerStateNotificationRegistrationState
+ softLinkOnceCBManagerIsPrivilegedDaemonKey
+ softLinkOnceCBManagerNeedsRestrictedStateOperation
- GCC_except_table1210
- GCC_except_table1291
- GCC_except_table1297
- GCC_except_table1298
- GCC_except_table1301
- GCC_except_table1374
- GCC_except_table1375
- GCC_except_table1406
- GCC_except_table1409
- GCC_except_table1415
- GCC_except_table1420
- GCC_except_table1423
- GCC_except_table1474
- GCC_except_table1475
- GCC_except_table1512
- GCC_except_table1542
- GCC_except_table1565
- GCC_except_table1572
- GCC_except_table1584
- GCC_except_table1586
- GCC_except_table1598
- GCC_except_table2085
- GCC_except_table2125
- GCC_except_table2155
- GCC_except_table2306
- GCC_except_table2307
- GCC_except_table2326
- GCC_except_table2361
- GCC_except_table2434
- GCC_except_table2458
- GCC_except_table2492
- GCC_except_table2496
- GCC_except_table2559
- GCC_except_table2560
- GCC_except_table2562
- GCC_except_table2563
- GCC_except_table2565
- GCC_except_table2570
- GCC_except_table2573
- GCC_except_table2576
- GCC_except_table2579
- GCC_except_table2582
- GCC_except_table2589
- GCC_except_table2592
- GCC_except_table2661
- GCC_except_table2978
- GCC_except_table2979
- GCC_except_table3038
- GCC_except_table3109
- GCC_except_table3113
- GCC_except_table3157
- GCC_except_table3160
- GCC_except_table3161
- GCC_except_table3163
- GCC_except_table3437
- GCC_except_table3865
- GCC_except_table4133
- GCC_except_table4141
- GCC_except_table4149
- GCC_except_table4301
- GCC_except_table4305
- GCC_except_table4307
- GCC_except_table4309
- GCC_except_table4332
- GCC_except_table4416
- GCC_except_table4417
- GCC_except_table4418
- GCC_except_table4419
- GCC_except_table4421
- GCC_except_table4423
- GCC_except_table4425
- GCC_except_table4427
- GCC_except_table4431
- GCC_except_table4433
- GCC_except_table4445
- GCC_except_table4452
- GCC_except_table4454
- GCC_except_table4455
- GCC_except_table4457
- GCC_except_table4458
- GCC_except_table4459
- GCC_except_table4461
- GCC_except_table4462
- GCC_except_table4463
- GCC_except_table4464
- GCC_except_table4465
- GCC_except_table4466
- GCC_except_table4474
- GCC_except_table4476
- GCC_except_table4477
- GCC_except_table4483
- GCC_except_table4485
- GCC_except_table4487
- GCC_except_table4491
- GCC_except_table4492
- GCC_except_table4493
- GCC_except_table4495
- GCC_except_table4497
- GCC_except_table4498
- GCC_except_table4499
- GCC_except_table4500
- GCC_except_table4501
- GCC_except_table4502
- GCC_except_table4504
- GCC_except_table4505
- GCC_except_table4506
- GCC_except_table5142
- GCC_except_table5147
- GCC_except_table5151
- GCC_except_table5218
- GCC_except_table5228
- GCC_except_table5237
- GCC_except_table5245
- GCC_except_table5569
- GCC_except_table5570
- GCC_except_table5583
- GCC_except_table686
- GCC_except_table771
- GCC_except_table785
- GCC_except_table787
- GCC_except_table790
- GCC_except_table973
- _objc_msgSend$pairingIdentityWithPrivateKey:completionHandler:
CStrings:
+ "### PairSetup SPAKE2 get M1 SharePData failed: %d"
+ "### PairSetup SPAKE2 get M2 ConfirmVData failed: %d"
+ "### PairSetup SPAKE2 get M2 ShareVData failed: %d"
+ "### PairSetup SPAKE2 get M3 failed: %d"
+ "### PairSetup client M2 bad status: 0x%X, %#m\n"
+ "### PairSetup client M4 bad status: 0x%X, %#m\n"
+ "### PairSetup client M6 bad status: 0x%X, %#m\n"
+ "### PairSetup client SPAKE2 add M1 SharePData TLV failed: %d"
+ "### PairSetup client SPAKE2 add M3 ConfirmPData TLV failed: %d"
+ "### PairSetup client SPAKE2 finish failed: %@"
+ "### PairSetup client SPAKE2 generate M1 failed: %@"
+ "### PairSetup client SPAKE2 generate M3 failed: %@"
+ "### PairSetup client SPAKE2 malloc secret failed"
+ "### PairSetup client SPAKE2 start failed: no password"
+ "### PairSetup client SPAKE2 verify failed: no prover"
+ "### PairSetup client bad state: %d\n"
+ "### PairSetup client state %d failed: %#m\n%?{end}%1{tlv8}\n"
+ "### PairSetup client wrong setup code"
+ "### PairSetup client: server not allowed: %#m\n"
+ "### PairSetup server SPAKE2 add M2 ConfirmVData TLV failed: %d"
+ "### PairSetup server SPAKE2 add M2 RetryDelay TLV failed: %d"
+ "### PairSetup server SPAKE2 add M2 ShareVData TLV failed: %d"
+ "### PairSetup server SPAKE2 finish failed: %@"
+ "### PairSetup server SPAKE2 generate M2 failed: %@"
+ "### PairSetup server SPAKE2 malloc secret failed"
+ "### PairSetup server SPAKE2 start failed: no password"
+ "### PairSetup server SPAKE2 verify failed: %@"
+ "### PairSetup server SPAKE2 verify failed: no verifier"
+ "### PairSetup server bad signature: %#m\n"
+ "### PairSetup server bad state: %d\n"
+ "### PairSetup server disabled after too many attempts\n"
+ "### PairSetup server save peer failed: %#m\n"
+ "### PairSetup server state %d failed: %#m\n%?{end}%1{tlv8}\n"
+ "### PairSetup server unsupported method: %u\n"
+ "### PairSetup server wrong setup code"
+ "### PairSetup server: client not allowed: %#m\n"
+ "### PairVerify client -- server lacks ACL: %@\n"
+ "### PairVerify client M2 failed: find peer failed, %#m\n"
+ "### PairVerify client M2 failed: get PK, %#m\n"
+ "### PairVerify client M2 failed: get encrypted data, %#m\n"
+ "### PairVerify client M2 failed: get identifier failed, %#m\n"
+ "### PairVerify client M2 failed: get signature failed, %#m\n"
+ "### PairVerify client M2 verify signature failed: %#m\n"
+ "### PairVerify client M3 sign failed: %#m\n"
+ "### PairVerify client M4 bad status: 0x%X, %#m\n"
+ "### PairVerify client bad state: %d\n"
+ "### PairVerify client state %d failed: %#m\n%?{end}%1{tlv8}\n"
+ "### PairVerify server -- client lacks ACL: %@\n"
+ "### PairVerify server M2 failed: copy identity, %#m\n"
+ "### PairVerify server M2 sign failed: %#m\n"
+ "### PairVerify server M3 bad status: 0x%X, %#m\n"
+ "### PairVerify server M3 verify signature failed: %#m\n"
+ "### PairVerify server M5 requested ACL not allowed: %#m, %@\n"
+ "### PairVerify server bad auth tag\n"
+ "### PairVerify server bad signature: %#m\n"
+ "### PairVerify server bad state: %d\n"
+ "### PairVerify server state %d failed: %#m\n%?{end}%1{tlv8}\n"
+ "### PairVerify server unknown peer: %.*s\n"
+ "### PairVerify server unsupported method: %u\n"
+ "+[CUPairingManager copySystemPairingIdentifierWithFlags:error:]"
+ "-[CUWiFiManager _wifiHandleEvent:]"
+ "@\"CWFInterface\""
+ "@\"WiFiAwarePublishDatapathServiceSpecificInfo\""
+ "AWDLTrafficRegistrationServiceMacVirtualDisplay"
+ "BonjourDevice_GetDNSName failed: %#m"
+ "Create path string failed"
+ "MacVirtualDisplay"
+ "No UTF8 path"
+ "OSStatus BonjourDevice_GetDNSName(CFDictionaryRef, uint64_t, char *, size_t)"
+ "OSStatus _SetupClientAuthenticationFailed(PairingSessionRef, const uint8_t *, const uint8_t *const)"
+ "OSStatus _SetupClientSPAKE2Start(PairingSessionRef, TLV8Buffer *)"
+ "OSStatus _SetupClientSPAKE2Verify(PairingSessionRef, const uint8_t *, const uint8_t *const, TLV8Buffer *)"
+ "OSStatus _SetupServerAuthenticationFailed(PairingSessionRef, uint8_t, TLV8Buffer *, uint8_t **, size_t *)"
+ "OSStatus _SetupServerSPAKE2Start(PairingSessionRef, const uint8_t *, const uint8_t *const, TLV8Buffer *)"
+ "OSStatus _SetupServerSPAKE2Verify(PairingSessionRef, const uint8_t *, const uint8_t *const)"
+ "Pair-resume client M2 for ID %llu failed %#m...doing PairVerify\n"
+ "Pair-resume server M1 for ID %llu failed %#m...doing PairVerify\n"
+ "PairSetup  client M3 -- verify request\n%?{end}%1{tlv8}\n"
+ "PairSetup client M1 -- start request\n%?{end}%1{tlv8}\n"
+ "PairSetup client M2 -- start response\n%?{end}%1{tlv8}\n"
+ "PairSetup client M4 -- verify response\n%?{end}%1{tlv8}\n"
+ "PairSetup client M5 -- exchange request\n%?{end}%1{tlv8}\n"
+ "PairSetup client M6 -- exchange response\n%?{end}%1{tlv8}\n"
+ "PairSetup client SPAKE2 start"
+ "PairSetup client done -- server authenticated\n"
+ "PairSetup server M1 -- start request\n%?{end}%1{tlv8}\n"
+ "PairSetup server M2 -- start response\n%?{end}%1{tlv8}\n"
+ "PairSetup server M3 -- verify request\n%?{end}%1{tlv8}\n"
+ "PairSetup server M4 -- verify response\n%?{end}%1{tlv8}\n"
+ "PairSetup server M5 -- exchange request\n%?{end}%1{tlv8}\n"
+ "PairSetup server M6 -- exchange response\n%?{end}%1{tlv8}\n"
+ "PairSetup server SPAKE2 start"
+ "PairSetup server done -- client authenticated\n"
+ "PairSetup server throttling for %d second(s)\n"
+ "PairSetup transient client done -- server authenticated\n"
+ "PairSetup transient server done -- client authenticated\n"
+ "PairVerify client M1 -- start request\n%?{end}%1{tlv8}\n"
+ "PairVerify client M2 -- start response\n%?{end}%1{tlv8}\n"
+ "PairVerify client M3 -- finish request\n%?{end}%1{tlv8}\n"
+ "PairVerify client M4 -- finish response\n%?{end}%1{tlv8}\n"
+ "PairVerify client done\n"
+ "PairVerify server M1 -- start request\n%?{end}%1{tlv8}\n"
+ "PairVerify server M2 -- start response\n%?{end}%1{tlv8}\n"
+ "PairVerify server M3 -- finish request\n%?{end}%1{tlv8}\n"
+ "PairVerify server M4 -- finish response\n%?{end}%1{tlv8}\n"
+ "PairVerify server done\n"
+ "T@\"NSObject<OS_dispatch_queue>\",&,V_dispatchQueue"
+ "T@\"WiFiAwarePublishDatapathServiceSpecificInfo\",&,N,V_wfaServiceSpecificInfo"
+ "T@?,C,V_invalidationHandler"
+ "Tq,N,V_wfaConnectionMode"
+ "Tq,N,V_wfaDiscoveryMode"
+ "WiFi SSID changed: '%@'"
+ "WiFi SSID changed: NULL"
+ "WiFi event:type=%ld"
+ "WiFi join started: SSID '%@'"
+ "WiFi join started: SSID NULL"
+ "WiFi state changed: %s -> %s, flags=%@, ssid=%@\n"
+ "_getLengthWithCompletionHandler:"
+ "_wfaConnectionMode"
+ "_wfaDiscoveryMode"
+ "_wfaServiceSpecificInfo"
+ "_wifiHandleEvent:"
+ "_wifiInterface"
+ "accessory:didUpdateHH1EOLEnabled:"
+ "copySystemPairingIdentifierWithFlags:error:"
+ "getLengthWithCompletionHandler:"
+ "pairingIdentityWithPrivateKey:attemptToReadFromKeychain:completionHandler:"
+ "realPath:dispatchQueue:completionHandler:"
+ "realPath:error:"
+ "realpath failed"
+ "setWfaConnectionMode:"
+ "setWfaDiscoveryMode:"
+ "setWfaServiceSpecificInfo:"
+ "stat failed"
+ "wfaConnectionMode"
+ "wfaDiscoveryMode"
+ "wfaServiceSpecificInfo"
+ "\xe1"
- "### Pair-setup client M2 bad status: 0x%X, %#m\n"
- "### Pair-setup client M4 bad status: 0x%X, %#m\n"
- "### Pair-setup client M6 bad status: 0x%X, %#m\n"
- "### Pair-setup client bad state: %d\n"
- "### Pair-setup client state %d failed: %#m\n%?{end}%1{tlv8}\n"
- "### Pair-setup client wrong setup code\n"
- "### Pair-setup client: server not allowed: %#m\n"
- "### Pair-setup server bad signature: %#m\n"
- "### Pair-setup server bad state: %d\n"
- "### Pair-setup server disabled after too many attempts\n"
- "### Pair-setup server save peer failed: %#m\n"
- "### Pair-setup server state %d failed: %#m\n%?{end}%1{tlv8}\n"
- "### Pair-setup server unsupported method: %u\n"
- "### Pair-setup server wrong setup code\n"
- "### Pair-setup server: client not allowed: %#m\n"
- "### Pair-verify client -- server lacks ACL: %@\n"
- "### Pair-verify client M2 failed: find peer failed, %#m\n"
- "### Pair-verify client M2 failed: get PK, %#m\n"
- "### Pair-verify client M2 failed: get encrypted data, %#m\n"
- "### Pair-verify client M2 failed: get identifier failed, %#m\n"
- "### Pair-verify client M2 failed: get signature failed, %#m\n"
- "### Pair-verify client M2 verify signature failed: %#m\n"
- "### Pair-verify client M3 sign failed: %#m\n"
- "### Pair-verify client M4 bad status: 0x%X, %#m\n"
- "### Pair-verify client bad state: %d\n"
- "### Pair-verify client state %d failed: %#m\n%?{end}%1{tlv8}\n"
- "### Pair-verify server -- client lacks ACL: %@\n"
- "### Pair-verify server M2 failed: copy identity, %#m\n"
- "### Pair-verify server M2 sign failed: %#m\n"
- "### Pair-verify server M3 bad status: 0x%X, %#m\n"
- "### Pair-verify server M3 verify signature failed: %#m\n"
- "### Pair-verify server M5 requested ACL not allowed: %#m, %@\n"
- "### Pair-verify server bad auth tag\n"
- "### Pair-verify server bad signature: %#m\n"
- "### Pair-verify server bad state: %d\n"
- "### Pair-verify server state %d failed: %#m\n%?{end}%1{tlv8}\n"
- "### Pair-verify server unknown peer: %.*s\n"
- "### Pair-verify server unsupported method: %u\n"
- "+[CUPairingManager copySystemPairingIdentifierAndReturnError:]"
- "-[CUWiFiManager joinDidStartForWiFiInterfaceWithName:ssid:]_block_invoke"
- "-[CUWiFiManager ssidDidChangeForWiFiInterfaceWithName:]_block_invoke"
- "No HomeKit Self Accessory Identity SPI"
- "Pair-resume client M2 for ID %llu failed %#m...doing pair-verify\n"
- "Pair-resume server M1 for ID %llu failed %#m...doing pair-verify\n"
- "Pair-setup  client M3 -- verify request\n%?{end}%1{tlv8}\n"
- "Pair-setup client M1 -- start request\n%?{end}%1{tlv8}\n"
- "Pair-setup client M2 -- start response\n%?{end}%1{tlv8}\n"
- "Pair-setup client M4 -- verify response\n%?{end}%1{tlv8}\n"
- "Pair-setup client M5 -- exchange request\n%?{end}%1{tlv8}\n"
- "Pair-setup client M6 -- exchange response\n%?{end}%1{tlv8}\n"
- "Pair-setup client done -- server authenticated\n"
- "Pair-setup server M1 -- start request\n%?{end}%1{tlv8}\n"
- "Pair-setup server M2 -- start response\n%?{end}%1{tlv8}\n"
- "Pair-setup server M3 -- verify request\n%?{end}%1{tlv8}\n"
- "Pair-setup server M4 -- verify response\n%?{end}%1{tlv8}\n"
- "Pair-setup server M5 -- exchange request\n%?{end}%1{tlv8}\n"
- "Pair-setup server M6 -- exchange response\n%?{end}%1{tlv8}\n"
- "Pair-setup server done -- client authenticated\n"
- "Pair-setup server throttling for %d second(s)\n"
- "Pair-setup transient client done -- server authenticated\n"
- "Pair-setup transient server done -- client authenticated\n"
- "Pair-verify client M1 -- start request\n%?{end}%1{tlv8}\n"
- "Pair-verify client M2 -- start response\n%?{end}%1{tlv8}\n"
- "Pair-verify client M3 -- finish request\n%?{end}%1{tlv8}\n"
- "Pair-verify client M4 -- finish response\n%?{end}%1{tlv8}\n"
- "Pair-verify client done\n"
- "Pair-verify server M1 -- start request\n%?{end}%1{tlv8}\n"
- "Pair-verify server M2 -- start response\n%?{end}%1{tlv8}\n"
- "Pair-verify server M3 -- finish request\n%?{end}%1{tlv8}\n"
- "Pair-verify server M4 -- finish response\n%?{end}%1{tlv8}\n"
- "Pair-verify server done\n"
- "WiFi SSID changed: %''@\n"
- "WiFi SSID changed: NULL\n"
- "WiFi join started: SSID %''@\n"
- "WiFi join started: SSID NULL\n"
- "WiFi state changed: %s -> %s, %#{flags} %?''@\n"
- "WiFi state changed: %s, %#{flags}\n"
- "pairingIdentityWithPrivateKey:completionHandler:"
- "\xd1"
```
