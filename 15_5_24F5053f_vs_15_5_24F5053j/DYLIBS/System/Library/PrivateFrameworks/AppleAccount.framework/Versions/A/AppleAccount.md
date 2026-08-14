## AppleAccount

> `/System/Library/PrivateFrameworks/AppleAccount.framework/Versions/A/AppleAccount`

```diff

-1007.475.0.0.0
-  __TEXT.__text: 0x1bfd18
+1007.476.0.0.0
+  __TEXT.__text: 0x1c01fc
   __TEXT.__auth_stubs: 0xa30
-  __TEXT.__objc_methlist: 0x9e40
+  __TEXT.__objc_methlist: 0x9ea0
   __TEXT.__const: 0x44d10
-  __TEXT.__cstring: 0xd11e
-  __TEXT.__oslogstring: 0xdc2c
+  __TEXT.__cstring: 0xd37e
+  __TEXT.__oslogstring: 0xdc45
   __TEXT.__gcc_except_tab: 0x20a0
   __TEXT.__dlopen_cstrs: 0x287
-  __TEXT.__unwind_info: 0x2908
+  __TEXT.__unwind_info: 0x2918
   __TEXT.__eh_frame: 0xb8
   __TEXT.__objc_classname: 0x1ca0
-  __TEXT.__objc_methname: 0x138f7
-  __TEXT.__objc_methtype: 0x2bae
-  __TEXT.__objc_stubs: 0xaf80
-  __DATA_CONST.__got: 0xb58
-  __DATA_CONST.__const: 0x2410
+  __TEXT.__objc_methname: 0x13a45
+  __TEXT.__objc_methtype: 0x2bca
+  __TEXT.__objc_stubs: 0xb0e0
+  __DATA_CONST.__got: 0xb60
+  __DATA_CONST.__const: 0x2420
   __DATA_CONST.__objc_classlist: 0x740
   __DATA_CONST.__objc_catlist: 0x98
   __DATA_CONST.__objc_protolist: 0x168
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x47a8
+  __DATA_CONST.__objc_selrefs: 0x4810
   __DATA_CONST.__objc_protorefs: 0x40
   __DATA_CONST.__objc_superrefs: 0x518
   __DATA_CONST.__objc_arraydata: 0xc0
   __AUTH_CONST.__auth_got: 0x528
   __AUTH_CONST.__const: 0xb5d0
-  __AUTH_CONST.__cfstring: 0xb980
-  __AUTH_CONST.__objc_const: 0x20890
+  __AUTH_CONST.__cfstring: 0xba20
+  __AUTH_CONST.__objc_const: 0x208d0
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__objc_intobj: 0xf0
+  __AUTH_CONST.__objc_intobj: 0x108
   __AUTH_CONST.__objc_arrayobj: 0xd8
   __AUTH.__objc_data: 0x1f10
   __AUTH.__data: 0x28
-  __DATA.__objc_ivar: 0xad0
+  __DATA.__objc_ivar: 0xad4
   __DATA.__data: 0x1468
   __DATA.__bss: 0x400
   __DATA.__common: 0xa20

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 4274
-  Symbols:   9064
-  CStrings:  6362
+  Functions: 4283
+  Symbols:   9090
+  CStrings:  6384
 
Symbols:
+ +[AAFollowUpUtilities followUpPostAnalyticsInfoWithContext:identifier:error:]
+ -[AACustodianshipInfo description]
+ -[AAFollowUpController .cxx_destruct]
+ -[AAFollowUpController analyticsInfo]
+ -[AAFollowUpController setAnalyticsInfo:]
+ -[AAFollowUpController(Convenience) reportPostCFUEvent]
+ -[AALocalContactInfo description]
+ -[AATrustedContact description]
+ GCC_except_table74
+ GCC_except_table77
+ GCC_except_table90
+ OBJC_IVAR_$_AAFollowUpController._analyticsInfo
+ _OBJC_CLASS_$_AAAFollowUpAnalyticsInfo
+ __95-[AAFollowUpController(Convenience) postFollowUpWithIdentifier:forAccount:userInfo:completion:]_block_invoke
+ __OBJC_$_INSTANCE_VARIABLES_AAFollowUpController
+ __OBJC_$_PROP_LIST_AAFollowUpController
+ _kAAAnalyticsEventCustodianRecoveryExperimentalCustodianRecordNotFoundFetchFromCloud
+ _kAAAnalyticsEventCustodianRecoveryExperimentalCustodianshipInfoRecordNotFoundFetchFromCloud
+ _objc_msgSend$_proxiedAppBundleID
+ _objc_msgSend$analyticsInfo
+ _objc_msgSend$cfuReasonAnalyticsEvent
+ _objc_msgSend$proxiedDevice
+ _objc_msgSend$reportPostCFUEvent
+ _objc_msgSend$setCfuType:
+ _objc_msgSend$setDeviceSessionID:
+ _objc_msgSend$setFlowID:
+ _objc_msgSend$setHasProxiedDevice:
+ _objc_msgSend$setPostedReasonError:
+ _objc_msgSend$setProxiedBundleID:
- GCC_except_table69
- GCC_except_table72
- ___95-[AAFollowUpController(Convenience) postFollowUpWithIdentifier:forAccount:userInfo:completion:]_block_invoke_2
CStrings:
+ "<CustodinshipInfo: CustodianID: %@, status: %ld, owner: %@>"
+ "<LocalContactInfo: CustodianID: %@, status: %ld, handle: %@, firstName: %@, lastName: %@, familyDSID: %@, familyMemberType: %@, isChild: %@, acceptedAndShared: %@, serverConfirmed: %@>"
+ "<TrustedContact: CustodianID: %@, status: %ld, handle: %@, firstName: %@, lastName: %@, displayName: %@, acceptedAndShared: %@, serverConfirmed: %@, build: %@>"
+ "@\"AAAFollowUpAnalyticsInfo\""
+ "Reporting post cfu event"
+ "T@\"AAAFollowUpAnalyticsInfo\",C,N,V_analyticsInfo"
+ "_analyticsInfo"
+ "_proxiedAppBundleID"
+ "analyticsInfo"
+ "cfuReasonAnalyticsEvent"
+ "com.apple.appleaccount.custodian.recovery.experimental.custodianRecordNotFoundFetchFromCloud"
+ "com.apple.appleaccount.custodian.recovery.experimental.custodianshipInfoRecordNotFoundFetchFromCloud"
+ "followUpPostAnalyticsInfoWithContext:identifier:error:"
+ "proxiedDevice"
+ "reportPostCFUEvent"
+ "setAnalyticsInfo:"
+ "setCfuType:"
+ "setDeviceSessionID:"
+ "setFlowID:"
+ "setHasProxiedDevice:"
+ "setPostedReasonError:"
+ "setProxiedBundleID:"
```
