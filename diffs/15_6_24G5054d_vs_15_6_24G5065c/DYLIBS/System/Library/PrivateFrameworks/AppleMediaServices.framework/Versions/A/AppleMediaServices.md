## AppleMediaServices

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/Versions/A/AppleMediaServices`

```diff

-8.6.6.0.0
-  __TEXT.__text: 0x6fc264
+8.6.7.0.0
+  __TEXT.__text: 0x6fdbec
   __TEXT.__auth_stubs: 0x3dc0
-  __TEXT.__objc_methlist: 0x2030c
-  __TEXT.__const: 0xaa64c
+  __TEXT.__objc_methlist: 0x202e4
+  __TEXT.__const: 0xaa65c
   __TEXT.__dlopen_cstrs: 0x705
-  __TEXT.__cstring: 0x2408c
+  __TEXT.__cstring: 0x241bf
   __TEXT.__swift5_typeref: 0x3b0f
-  __TEXT.__swift5_reflstr: 0x1c48
+  __TEXT.__swift5_reflstr: 0x1c78
   __TEXT.__swift5_assocty: 0x900
   __TEXT.__constg_swiftt: 0x2888
   __TEXT.__swift5_builtin: 0x1cc
-  __TEXT.__swift5_fieldmd: 0x2318
+  __TEXT.__swift5_fieldmd: 0x2324
   __TEXT.__swift5_proto: 0x604
   __TEXT.__swift5_types: 0x2e4
   __TEXT.__swift_as_entry: 0x42c

   __TEXT.__swift5_capture: 0x1cac
   __TEXT.__swift5_mpenum: 0x48
   __TEXT.__swift5_protos: 0x80
-  __TEXT.__oslogstring: 0x2b508
-  __TEXT.__gcc_except_tab: 0x7b60
+  __TEXT.__oslogstring: 0x2b619
+  __TEXT.__gcc_except_tab: 0x7c64
   __TEXT.__ustring: 0x210
-  __TEXT.__unwind_info: 0xcc58
+  __TEXT.__unwind_info: 0xcc78
   __TEXT.__eh_frame: 0xac3c
-  __TEXT.__objc_classname: 0x3bd9
-  __TEXT.__objc_methname: 0x3f76c
-  __TEXT.__objc_methtype: 0x71e6
-  __TEXT.__objc_stubs: 0x2b940
+  __TEXT.__objc_classname: 0x3bcd
+  __TEXT.__objc_methname: 0x3f906
+  __TEXT.__objc_methtype: 0x71fc
+  __TEXT.__objc_stubs: 0x2b960
   __DATA_CONST.__got: 0x1698
-  __DATA_CONST.__const: 0x5048
-  __DATA_CONST.__objc_classlist: 0x1280
+  __DATA_CONST.__const: 0x5068
+  __DATA_CONST.__objc_classlist: 0x1278
   __DATA_CONST.__objc_catlist: 0xf8
   __DATA_CONST.__objc_protolist: 0x388
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xe268
+  __DATA_CONST.__objc_selrefs: 0xe270
   __DATA_CONST.__objc_protorefs: 0x1b0
   __DATA_CONST.__objc_superrefs: 0xc38
   __DATA_CONST.__objc_arraydata: 0x398
   __AUTH_CONST.__auth_got: 0x1ef8
-  __AUTH_CONST.__const: 0x372c8
-  __AUTH_CONST.__cfstring: 0x20900
-  __AUTH_CONST.__objc_const: 0x37600
+  __AUTH_CONST.__const: 0x373a8
+  __AUTH_CONST.__cfstring: 0x20960
+  __AUTH_CONST.__objc_const: 0x37538
   __AUTH_CONST.__objc_intobj: 0xc30
   __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH.__objc_data: 0x6dc0
+  __AUTH.__objc_data: 0x6d70
   __AUTH.__data: 0x1ca0
-  __DATA.__objc_ivar: 0x1de8
+  __DATA.__objc_ivar: 0x1df0
   __DATA.__data: 0x57f0
   __DATA.__bss: 0xb360
   __DATA.__common: 0x1574

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 19457
-  Symbols:   27672
-  CStrings:  18541
+  Functions: 19460
+  Symbols:   27675
+  CStrings:  18560
 
Symbols:
+ -[AMSURLProtocolHandler fraudReportRefreshScoreBlock]
+ -[AMSURLProtocolHandler fraudReportStateStorageFactoryBlock]
+ -[AMSURLProtocolHandler initWithFraudReportRefreshScoreBlock:fraudReportStateStorageFactoryBlock:]
+ -[AMSURLProtocolHandler initWithMetricsHandler:fairPlayDeviceIdentity:fraudReportRefreshScoreBlock:fraudReportStateStorageFactoryBlock:]
+ -[AMSURLRequestProperties hash]
+ -[AMSURLRequestProperties isEqual:]
+ GCC_except_table106
+ GCC_except_table88
+ OBJC_IVAR_$_AMSURLProtocolHandler._fraudReportRefreshScoreBlock
+ OBJC_IVAR_$_AMSURLProtocolHandler._fraudReportStateStorageFactoryBlock
+ _AMSFraudReportFallbackAccountForAccount
+ _AMSFraudReportHandleResponseWithDetachedHandling
+ _AMSFraudReportResponseHandlingDefaultRefreshScoreBlock_block_invoke
+ _AMSFraudReportResponseHandlingDefaultStateStorageFactoryBlock_block_invoke_2
+ _AMSFraudReportUpdateInitURLStateStorage
+ __AMSFraudReportHandleInitURLFraudReportResponse_block_invoke
+ ___AMSFraudReportHandleResponseWithDetachedHandling_block_invoke
+ ___AMSFraudReportHandleResponse_block_invoke
+ ___block_descriptor_32_e41_"AMSFraudReportDatabaseStateStorage"8?0l
+ ___block_descriptor_40_e8_32s_e52_"AMSBinaryPromise"24?0"AMSURLResult"8"NSError"16l
+ ___block_descriptor_56_e8_32s40s48bs_e46_"AMSPromise"24?0"NSDictionary"8"NSError"16l
+ ___block_descriptor_56_e8_32s40s48bs_e52_"AMSBinaryPromise"24?0"AMSURLResult"8"NSError"16l
+ ___block_descriptor_80_e8_32s40s48s56s64s72bs_e52_"AMSBinaryPromise"24?0"NSDictionary"8"NSError"16l
+ ___block_descriptor_88_e8_32s40s48s56s64s72bs80bs_e30_"AMSPromise"16?0"NSNumber"8l
+ ___block_descriptor_97_e8_32s40s48s56s64s72s80bs88bs_e36_"AMSBinaryPromise"16?0"NSNumber"8l
+ ___copy_helper_block_e8_32s40s48s56s64s72b
+ _objc_msgSend$initWithMetricsHandler:fairPlayDeviceIdentity:fraudReportRefreshScoreBlock:fraudReportStateStorageFactoryBlock:
- +[AMSFraudReport bagKeySet]
- +[AMSFraudReport bagSubProfileVersion]
- +[AMSFraudReport bagSubProfile]
- +[AMSFraudReport createBagForSubProfile]
- +[AMSFraudReport(Deprecated) addDeviceIdentityCertificateAndSignatureToRequest:parameters:bag:]
- +[AMSFraudReport(Deprecated) handleResponse:account:bag:]
- +[AMSFraudReport(Deprecated) isFeatureSupportedForBag:]
- -[AMSURLRequest setProperties:]
- GCC_except_table107
- GCC_except_table89
- _AMSFraudReportHandleResponseDefaultRefreshScoreBlock_block_invoke
- _OBJC_CLASS_$_AMSFraudReport
- _OBJC_METACLASS_$_AMSFraudReport
- __OBJC_$_CLASS_METHODS_AMSFraudReport(Deprecated)
- __OBJC_$_CLASS_PROP_LIST_AMSFraudReport
- __OBJC_$_PROP_LIST_AMSFraudReport
- __OBJC_CLASS_PROTOCOLS_$_AMSFraudReport
- __OBJC_CLASS_RO_$_AMSFraudReport
- __OBJC_METACLASS_RO_$_AMSFraudReport
- ___95+[AMSFraudReport(Deprecated) addDeviceIdentityCertificateAndSignatureToRequest:parameters:bag:]_block_invoke
- ___AMSFraudReportShouldCallInitURL_block_invoke
- ____AMSFraudReportHandleResponse_block_invoke
- ___block_descriptor_64_e8_32s40s48s56s_e46_"AMSPromise"24?0"NSDictionary"8"NSError"16l
- ___block_descriptor_88_e8_32s40s48s56s64s72s80bs_e30_"AMSPromise"16?0"NSNumber"8l
CStrings:
+ "@\"AMSBinaryPromise\"16@?0@\"NSNumber\"8"
+ "@\"AMSBinaryPromise\"24@?0@\"AMSURLResult\"8@\"NSError\"16"
+ "@\"AMSFraudReportDatabaseStateStorage\"8@?0"
+ "@48@0:8@16@24@?32@?40"
+ "AMSFraudReport [%{public}@] Calling callback URL."
+ "AMSFraudReport [%{public}@] Calling init URL."
+ "AMSFraudReport [%{public}@] Failed to report new fraud score to the callback url: %{public}@."
+ "AMSFraudReport [%{public}@] Retrying original request with updated score."
+ "AMSFraudReport [%{public}@] Successfully reported new fraud score to the callback url."
+ "AMSFraudReport: [%{public}@] Skipping fraud report score refresh because fraud report is not enabled in the bag."
+ "AMSFraudReport: [%{public}@] Updated Init URL persistent state."
+ "AMSFraudReportInitURLPersistenceKey"
+ "AMSFraudReportInitURLUpdatedState"
+ "FSR callback URL not found in response"
+ "FSR init URL not found in response"
+ "T@\"AMSFairPlayDeviceIdentity\",R,N,V_fairPlayDeviceIdentity"
+ "T@\"AMSKeychainOptions\",C,V_keychainOptions"
+ "T@\"AMSURLMetricsLoadURLHandler\",R,N,V_metricsHandler"
+ "T@\"AMSURLRequestProperties\",R,N,V_properties"
+ "T@\"NSString\",C,V_gsTokenIdentifier"
+ "T@?,R,N,V_fraudReportRefreshScoreBlock"
+ "T@?,R,N,V_fraudReportStateStorageFactoryBlock"
+ "TSDataSyncMetricsErrorEnhancements"
+ "_fraudReportRefreshScoreBlock"
+ "_fraudReportStateStorageFactoryBlock"
+ "fraudReportRefreshScoreBlock"
+ "fraudReportStateStorageFactoryBlock"
+ "initWithFraudReportRefreshScoreBlock:fraudReportStateStorageFactoryBlock:"
+ "initWithMetricsHandler:fairPlayDeviceIdentity:fraudReportRefreshScoreBlock:fraudReportStateStorageFactoryBlock:"
- "AMSFraudReport [%{public}@] Failed reporting the new fraud score to the callback url: %{public}@."
- "AMSFraudReport [%{public}@] Successfully reported the new fraud score to the callback url."
- "AMSFraudReport: [%{public}@] Skipping fraud report score refresh."
- "Deprecated"
- "FraudScoreReport"
- "T@\"AMSFairPlayDeviceIdentity\",R,V_fairPlayDeviceIdentity"
- "T@\"AMSURLMetricsLoadURLHandler\",R,V_metricsHandler"
- "addDeviceIdentityCertificateAndSignatureToRequest:parameters:bag:"
- "handleResponse:account:bag:"
- "isFeatureSupportedForBag:"
```
