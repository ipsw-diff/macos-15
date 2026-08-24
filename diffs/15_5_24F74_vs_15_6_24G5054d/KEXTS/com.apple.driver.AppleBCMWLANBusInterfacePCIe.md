## com.apple.driver.AppleBCMWLANBusInterfacePCIe

> `com.apple.driver.AppleBCMWLANBusInterfacePCIe`

```diff

-1425.45.0.0.0
+1435.2.0.0.0
   __TEXT.__const: 0x1e4c
   __TEXT.__os_log: 0x7a0
-  __TEXT.__cstring: 0x14a0a
-  __TEXT_EXEC.__text: 0x647ec
+  __TEXT.__cstring: 0x14a78
+  __TEXT_EXEC.__text: 0x649e8
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xc4
   __DATA.__common: 0x298
   __DATA.__bss: 0x4e8
   __DATA_CONST.__auth_got: 0xc68
-  __DATA_CONST.__got: 0x1f8
+  __DATA_CONST.__got: 0x1f0
   __DATA_CONST.__mod_init_func: 0x130
   __DATA_CONST.__mod_term_func: 0x128
   __DATA_CONST.__const: 0x9758
   __DATA_CONST.__kalloc_type: 0x1ec0
   __DATA_CONST.__kalloc_var: 0x410
-  Functions: 1125
+  Functions: 1126
   Symbols:   2504
-  CStrings:  2094
+  CStrings:  2096
 
Symbols:
+ __ZN40AppleBCMWLANPCIeSkywalkTxSubmissionQueue15validateMacAddrEP29AppleBCMWLANPCIeSkywalkPacketP28AppleBCMWLANSkywalkInterface
+ __ZZN40AppleBCMWLANPCIeSkywalkTxSubmissionQueue31initProviderAndPoolAndQueueInfoEP28AppleBCMWLANBusInterfacePCIeP8OSObjectP33AppleBCMWLANPCIeSkywalkPacketPooltj17apple80211_wme_acjP11CCLogStreamP15CCFaultReporterE20kalloc_type_view_124
+ __ZZN40AppleBCMWLANPCIeSkywalkTxSubmissionQueue4freeEvE20kalloc_type_view_245
+ __ZZN40AppleBCMWLANPCIeSkywalkTxSubmissionQueue6enableEvE20kalloc_type_view_176
+ __ZZN40AppleBCMWLANPCIeSkywalkTxSubmissionQueue7disableEvE20kalloc_type_view_191
- __ZN28AppleBCMWLANSkywalkInterface9metaClassE
- __ZZN40AppleBCMWLANPCIeSkywalkTxSubmissionQueue31initProviderAndPoolAndQueueInfoEP28AppleBCMWLANBusInterfacePCIeP8OSObjectP33AppleBCMWLANPCIeSkywalkPacketPooltj17apple80211_wme_acjP11CCLogStreamP15CCFaultReporterE20kalloc_type_view_123
- __ZZN40AppleBCMWLANPCIeSkywalkTxSubmissionQueue4freeEvE20kalloc_type_view_242
- __ZZN40AppleBCMWLANPCIeSkywalkTxSubmissionQueue6enableEvE20kalloc_type_view_173
- __ZZN40AppleBCMWLANPCIeSkywalkTxSubmissionQueue7disableEvE20kalloc_type_view_188
Functions:
~ __ZN40AppleBCMWLANPCIeSkywalkTxSubmissionQueue31withProviderAndQueueInfoAndPoolEP28AppleBCMWLANBusInterfacePCIeP8OSObjecttj17apple80211_wme_acjP33AppleBCMWLANPCIeSkywalkPacketPoolP11CCLogStreamP15CCFaultReporter : 916 -> 940
+ __ZN40AppleBCMWLANPCIeSkywalkTxSubmissionQueue15validateMacAddrEP29AppleBCMWLANPCIeSkywalkPacketP28AppleBCMWLANSkywalkInterface
~ __ZN40AppleBCMWLANPCIeSkywalkTxSubmissionQueue14dequeuePacketsEP8OSObjectPP20IO80211NetworkPacketjPv : 9280 -> 9340
~ __ZN23AppleBCMWLANPCIeSkywalk24attachTxSubmissionQueuesEP23IO80211SkywalkInterface : 1092 -> 972
CStrings:
+ "111121111111111111111222122222111111111111111112222222"
+ "[ik] %s@%d:Mac adress mismatch local %02x:%02x:%02x:%02x:%02x:%02x  packet %02x:%02x:%02x:%02x:%02x:%02x \n"
+ "validateMacAddr"
+ "wlan.validateMacAddrOption"
- "11112111111111111111122212222211111111111111111222222"
- "[ik] %s@%d:Request to attach, while not connected\n"
```
