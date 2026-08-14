## CloudSubscriptionFeatures

> `/System/Library/PrivateFrameworks/CloudSubscriptionFeatures.framework/Versions/A/CloudSubscriptionFeatures`

```diff

-301.22.5.2.0
-  __TEXT.__text: 0xf9d60
+301.22.5.4.0
+  __TEXT.__text: 0x10498c
   __TEXT.__auth_stubs: 0x1ca0
-  __TEXT.__objc_methlist: 0xe40
-  __TEXT.__const: 0x7528
+  __TEXT.__objc_methlist: 0xe5c
+  __TEXT.__const: 0x7658
   __TEXT.__gcc_except_tab: 0x70
-  __TEXT.__cstring: 0x511d
-  __TEXT.__oslogstring: 0x6d81
+  __TEXT.__cstring: 0x551d
+  __TEXT.__oslogstring: 0x7381
   __TEXT.__dlopen_cstrs: 0xc4
-  __TEXT.__swift5_typeref: 0x22a8
-  __TEXT.__constg_swiftt: 0x2488
-  __TEXT.__swift5_reflstr: 0x1a2d
-  __TEXT.__swift5_fieldmd: 0x21fc
+  __TEXT.__swift5_typeref: 0x230a
+  __TEXT.__constg_swiftt: 0x2500
+  __TEXT.__swift5_reflstr: 0x1b1d
+  __TEXT.__swift5_fieldmd: 0x2288
   __TEXT.__swift5_builtin: 0xdc
-  __TEXT.__swift5_assocty: 0x378
-  __TEXT.__swift5_capture: 0x13a4
-  __TEXT.__swift5_proto: 0x698
-  __TEXT.__swift5_types: 0x2a0
-  __TEXT.__swift_as_entry: 0x348
-  __TEXT.__swift_as_ret: 0x3c4
+  __TEXT.__swift5_assocty: 0x390
+  __TEXT.__swift5_capture: 0x1438
+  __TEXT.__swift5_proto: 0x6a8
+  __TEXT.__swift5_types: 0x2a8
+  __TEXT.__swift_as_entry: 0x374
+  __TEXT.__swift_as_ret: 0x3ec
   __TEXT.__swift5_protos: 0x88
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__unwind_info: 0x3cf8
-  __TEXT.__eh_frame: 0x9cd0
+  __TEXT.__unwind_info: 0x3ef8
+  __TEXT.__eh_frame: 0xa4b8
   __TEXT.__objc_classname: 0x144
-  __TEXT.__objc_methname: 0x1db8
+  __TEXT.__objc_methname: 0x1dec
   __TEXT.__objc_methtype: 0x2be
   __TEXT.__objc_stubs: 0xc40
-  __DATA_CONST.__got: 0x548
-  __DATA_CONST.__const: 0x330
+  __DATA_CONST.__got: 0x550
+  __DATA_CONST.__const: 0x340
   __DATA_CONST.__objc_classlist: 0x150
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x908
+  __DATA_CONST.__objc_selrefs: 0x910
   __DATA_CONST.__objc_protorefs: 0x40
   __DATA_CONST.__objc_superrefs: 0x28
   __AUTH_CONST.__auth_got: 0xe60
-  __AUTH_CONST.__const: 0x7010
+  __AUTH_CONST.__const: 0x7238
   __AUTH_CONST.__cfstring: 0x480
-  __AUTH_CONST.__objc_const: 0x3420
-  __AUTH.__objc_data: 0x12c8
-  __AUTH.__data: 0x1700
+  __AUTH_CONST.__objc_const: 0x3468
+  __AUTH.__objc_data: 0x12d0
+  __AUTH.__data: 0x1750
   __DATA.__objc_ivar: 0x34
-  __DATA.__data: 0x26a0
-  __DATA.__bss: 0xbd10
+  __DATA.__data: 0x2760
+  __DATA.__bss: 0xbf10
   __DATA.__common: 0x58
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 4517
-  Symbols:   1622
-  CStrings:  1372
+  Functions: 4618
+  Symbols:   1630
+  CStrings:  1423
 
Symbols:
+ _associated conformance 25CloudSubscriptionFeatures8FollowUpC28WaitlistCFUEligibilityResultOSHAASQ
+ _symbolic ScCy___________pG 25CloudSubscriptionFeatures8FollowUpC28WaitlistCFUEligibilityResultO s5ErrorP
+ _symbolic SiSo7NSErrorCSgIegyg_
+ _symbolic SiSo7NSErrorCSgIeyByy_
+ _symbolic _____ 25CloudSubscriptionFeatures0C18LoggerWithCategoryV
+ _symbolic _____ 25CloudSubscriptionFeatures8FollowUpC28WaitlistCFUEligibilityResultO
+ _symbolic _____ 2os23OSSignpostIntervalStateC
+ _symbolic _____Sg 25CloudSubscriptionFeatures0A7FeatureC
+ objectdestroy.153Tm
- objectdestroy.138Tm
CStrings:
+ "%{public}llu [Finish] [Async] FAILURE %{public}s"
+ "%{public}llu [Finish] [Async] SUCCESS %{public}s"
+ "%{public}llu [Finish] [Sync] FAILURE %{public}s"
+ "%{public}llu [Finish] [Sync] SUCCESS %{public}s"
+ "%{public}llu [Start] [Async] %{public}s"
+ "%{public}llu [Start] [Sync] %{public}s"
+ "%{public}s Attempted to post waitlist CFU on invalid configuration."
+ "%{public}s Posting CFU"
+ "%{public}s Setting ADM bypass to %{bool,public}d."
+ "%{public}s Setting AFM bypass to %{bool,public}d."
+ "%{public}s Successfully posted waitlist CFU."
+ "%{public}s Unable to create FollowUp controller."
+ "%{public}s Unable to post waitlist CFU: %@"
+ "%{public}s Updating availability with bypass enabled."
+ "Attempted to determine device waitlist CFU eligibility on ineligible configuration."
+ "Cached new waitlist result: %{public}s - %{public}s"
+ "Determining if device has feature access."
+ "Device does not have access. Do not post the CFU."
+ "Device does not have cached LLM feature, device is likely missing HW support."
+ "Does have ticket? %{bool,public}d. Has ticket cache ticket? %{bool,public}d. Has waitlist cache ticket? %{bool,public}d"
+ "GM_CFU_ACTION_TEXT"
+ "GM_CFU_DESCRIPTION"
+ "Unable to init UserDefaults, will not read hasSentWaitlistCFUDate and will return false. Use may see CFU erroneously."
+ "Unable to init UserDefaults, will not update hasSentWaitlistCFUDate."
+ "Updating UserDefaults for key %{public}s to value: %{public}s"
+ "[%{public}s] No valid cache value for %{public}s."
+ "doesNotHaveAccess"
+ "doesNotHaveTicket"
+ "hasSentCFUPreviously"
+ "hasSentWaitlistFollowUp"
+ "ineligibleConfiguration"
+ "postWaitlistCFU()"
+ "postWaitlistCFUIfEligible(hasFeatureAccess:hasExistingTicket:)"
+ "requestFeature"
+ "requestFeature.callCompletion"
+ "requestFeature.fetchAccount"
+ "requestFeature.fetchDeviceUnlocked"
+ "requestFeature.fetchFromCache"
+ "requestFeature.fetchTaskLimiter"
+ "requestFeature.isFeatureSupported"
+ "requestFeature.processResponse"
+ "requestFeature.taskLimiterPerformRequest"
+ "setADMBypass(_:)"
+ "setGMEligibilityBypass(_:)"
+ "setGMEligibilityBypassAndWait(_:)"
+ "stubbedFeature=1"
+ "unableToDetermineAccountEligibility"
+ "updateAFMAvailability(bypass:)"
+ "v24@0:8@?<v@?q@\"NSError\">16"
+ "verifyDeviceIsEligibleForWaitlistCFU(completion:)"
+ "verifyDeviceIsEligibleForWaitlistCFUWithCompletion:"
+ "x-apple.systempreferences:com.apple.Siri-Settings.extension?gmCFU"
- "[%{public}s] No valid cache value for %{public}s"
```
