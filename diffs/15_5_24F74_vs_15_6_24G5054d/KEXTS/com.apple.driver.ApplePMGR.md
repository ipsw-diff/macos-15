## com.apple.driver.ApplePMGR

> `com.apple.driver.ApplePMGR`

```diff

-1555.120.3.0.0
+1555.140.4.0.0
   __TEXT.__const: 0x258
-  __TEXT.__cstring: 0xeca4
-  __TEXT_EXEC.__text: 0x57be8
+  __TEXT.__cstring: 0xed94
+  __TEXT_EXEC.__text: 0x5934c
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x100
   __DATA.__common: 0x470

   __DATA_CONST.__mod_term_func: 0x18
   __DATA_CONST.__const: 0xa4f0
   __DATA_CONST.__kalloc_type: 0x700
-  __DATA_CONST.__kalloc_var: 0xe60
-  Functions: 2179
-  Symbols:   2271
-  CStrings:  1615
+  __DATA_CONST.__kalloc_var: 0xf00
+  Functions: 2188
+  Symbols:   2276
+  CStrings:  1624
 
Symbols:
+ _OUTLINED_FUNCTION_2
+ _ZN9ApplePMGR22_setPwrGateRetentionV2Etbj
+ __ZN9ApplePMGR22_setPwrGateRetentionV2Etbj
+ __ZZN28ApplePMGRFunctionISPRefClock27initWithTargetDataAndSymbolEP9IOServicePK6OSDataPK8OSSymbolE22kalloc_type_view_15789
+ __ZZN9ApplePMGR10_initPMPv2EvE21kalloc_type_view_9875
+ __ZZN9ApplePMGR10_initPMPv2EvE21kalloc_type_view_9948
+ __ZZN9ApplePMGR10initDriverEP9IOServiceE21kalloc_type_view_3017
+ __ZZN9ApplePMGR10initDriverEP9IOServiceE21kalloc_type_view_3030
+ __ZZN9ApplePMGR15_initGenericPTDEvE21kalloc_type_view_9829
+ __ZZN9ApplePMGR19_initPerfCountersV1EP9IOServiceE22kalloc_type_view_17252
+ __ZZN9ApplePMGR19_initPerfCountersV1EP9IOServiceE22kalloc_type_view_17280
+ __ZZN9ApplePMGR19_initPerfCountersV1EP9IOServiceE22kalloc_type_view_17323
+ __ZZN9ApplePMGR19_initPerfCountersV1EP9IOServiceE22kalloc_type_view_17387
+ __ZZN9ApplePMGR19_initPerfCountersV2EP9IOServiceE22kalloc_type_view_18028
+ __ZZN9ApplePMGR19_initPerfCountersV2EP9IOServiceE22kalloc_type_view_18045
+ __ZZN9ApplePMGR24_initFreeRunningCountersEP9IOServiceE22kalloc_type_view_18236
+ __ZZN9ApplePMGR32_pmpWriteDashBoardSetDeviceStateEtjjE22kalloc_type_view_10318
- __ZZN28ApplePMGRFunctionISPRefClock27initWithTargetDataAndSymbolEP9IOServicePK6OSDataPK8OSSymbolE22kalloc_type_view_15726
- __ZZN9ApplePMGR10_initPMPv2EvE21kalloc_type_view_9812
- __ZZN9ApplePMGR10_initPMPv2EvE21kalloc_type_view_9885
- __ZZN9ApplePMGR15_initGenericPTDEvE21kalloc_type_view_9766
- __ZZN9ApplePMGR19_initPerfCountersV1EP9IOServiceE22kalloc_type_view_17189
- __ZZN9ApplePMGR19_initPerfCountersV1EP9IOServiceE22kalloc_type_view_17217
- __ZZN9ApplePMGR19_initPerfCountersV1EP9IOServiceE22kalloc_type_view_17260
- __ZZN9ApplePMGR19_initPerfCountersV1EP9IOServiceE22kalloc_type_view_17324
- __ZZN9ApplePMGR19_initPerfCountersV2EP9IOServiceE22kalloc_type_view_17965
- __ZZN9ApplePMGR19_initPerfCountersV2EP9IOServiceE22kalloc_type_view_17982
- __ZZN9ApplePMGR24_initFreeRunningCountersEP9IOServiceE22kalloc_type_view_18160
- __ZZN9ApplePMGR32_pmpWriteDashBoardSetDeviceStateEtjjE22kalloc_type_view_10255
CStrings:
+ "ApplePMGR: [Die %d] PwrGateRetentionV2 devID:0x%x reg:0x%x, %s data:0x%x\n"
+ "OFF"
+ "ON"
+ "_retentFFData"
+ "_retentMemData"
+ "retention_config_ff"
+ "retention_config_mem"
+ "site.PwrgateRetentionData"
+ "void ApplePMGR::_setPwrGateRetentionV2(DeviceID, bool, UInt32)"
```
