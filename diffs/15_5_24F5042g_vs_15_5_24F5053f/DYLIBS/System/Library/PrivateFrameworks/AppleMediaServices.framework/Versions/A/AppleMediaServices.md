## AppleMediaServices

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/Versions/A/AppleMediaServices`

```diff

-8.5.2.1.1
-  __TEXT.__text: 0x869cec
-  __TEXT.__auth_stubs: 0x44a0
-  __TEXT.__objc_methlist: 0x20124
-  __TEXT.__const: 0xb5423
+8.5.5.0.0
+  __TEXT.__text: 0x86d068
+  __TEXT.__auth_stubs: 0x44e0
+  __TEXT.__objc_methlist: 0x20324
+  __TEXT.__const: 0xb5513
   __TEXT.__dlopen_cstrs: 0x705
-  __TEXT.__cstring: 0x285a1
-  __TEXT.__swift5_typeref: 0x3a09
-  __TEXT.__swift5_reflstr: 0x1b98
-  __TEXT.__swift5_assocty: 0x8e8
-  __TEXT.__constg_swiftt: 0x272c
+  __TEXT.__cstring: 0x28831
+  __TEXT.__swift5_typeref: 0x3a7f
+  __TEXT.__swift5_reflstr: 0x1be8
+  __TEXT.__swift5_assocty: 0x900
+  __TEXT.__constg_swiftt: 0x27dc
   __TEXT.__swift5_builtin: 0x1cc
-  __TEXT.__swift5_fieldmd: 0x2238
-  __TEXT.__swift5_proto: 0x5e8
-  __TEXT.__swift5_types: 0x2d4
+  __TEXT.__swift5_fieldmd: 0x2294
+  __TEXT.__swift5_proto: 0x5f4
+  __TEXT.__swift5_types: 0x2dc
   __TEXT.__swift_as_entry: 0x400
-  __TEXT.__swift_as_ret: 0x41c
+  __TEXT.__swift_as_ret: 0x420
   __TEXT.__swift5_capture: 0x1b04
   __TEXT.__swift5_mpenum: 0x48
   __TEXT.__swift5_protos: 0x7c
-  __TEXT.__oslogstring: 0x2b424
-  __TEXT.__gcc_except_tab: 0x1684c
+  __TEXT.__oslogstring: 0x2b4cb
+  __TEXT.__gcc_except_tab: 0x16854
   __TEXT.__ustring: 0x210
-  __TEXT.__unwind_info: 0x10e48
-  __TEXT.__eh_frame: 0xa604
-  __TEXT.__objc_classname: 0x3b6f
-  __TEXT.__objc_methname: 0x3f787
-  __TEXT.__objc_methtype: 0x7268
-  __TEXT.__objc_stubs: 0x2ba80
-  __DATA_CONST.__got: 0x1758
-  __DATA_CONST.__const: 0x5608
-  __DATA_CONST.__objc_classlist: 0x1260
+  __TEXT.__unwind_info: 0x10f20
+  __TEXT.__eh_frame: 0xa69c
+  __TEXT.__objc_classname: 0x3be4
+  __TEXT.__objc_methname: 0x3fa71
+  __TEXT.__objc_methtype: 0x72f8
+  __TEXT.__objc_stubs: 0x2bc40
+  __DATA_CONST.__got: 0x1768
+  __DATA_CONST.__const: 0x5638
+  __DATA_CONST.__objc_classlist: 0x1280
   __DATA_CONST.__objc_catlist: 0xf8
-  __DATA_CONST.__objc_protolist: 0x378
+  __DATA_CONST.__objc_protolist: 0x380
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xe2a8
-  __DATA_CONST.__objc_protorefs: 0x1a8
-  __DATA_CONST.__objc_superrefs: 0xc38
+  __DATA_CONST.__objc_selrefs: 0xe328
+  __DATA_CONST.__objc_protorefs: 0x1b0
+  __DATA_CONST.__objc_superrefs: 0xc40
   __DATA_CONST.__objc_arraydata: 0x390
-  __AUTH_CONST.__auth_got: 0x2268
-  __AUTH_CONST.__const: 0x3dc30
-  __AUTH_CONST.__cfstring: 0x207e0
-  __AUTH_CONST.__objc_const: 0x37150
+  __AUTH_CONST.__auth_got: 0x2288
+  __AUTH_CONST.__const: 0x3dd60
+  __AUTH_CONST.__cfstring: 0x209c0
+  __AUTH_CONST.__objc_const: 0x37640
   __AUTH_CONST.__objc_intobj: 0xc30
   __AUTH_CONST.__objc_arrayobj: 0xf0
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH.__objc_data: 0x6c38
-  __AUTH.__data: 0x1ba8
+  __AUTH.__objc_data: 0x6e50
+  __AUTH.__data: 0x1bc8
   __AUTH.__thread_vars: 0x30
   __AUTH.__thread_bss: 0x8
-  __DATA.__objc_ivar: 0x1dd4
-  __DATA.__data: 0x6230
-  __DATA.__bss: 0xc1f8
+  __DATA.__objc_ivar: 0x1df8
+  __DATA.__data: 0x6300
+  __DATA.__bss: 0xc388
   __DATA.__common: 0x1570
   __DATA_DIRTY.__objc_data: 0x5d70
   __DATA_DIRTY.__data: 0x70

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 21857
-  Symbols:   32646
-  CStrings:  19163
+  Functions: 21975
+  Symbols:   32752
+  CStrings:  19217
 
Symbols:
+ +[AMSDaemonConnectionInterface _onDeviceDataInterface]
+ +[AMSDefaults disableTapToRadar]
+ +[AMSDefaults setDisableTapToRadar:]
+ +[AMSLogConfig sharedTSDataSyncConfig]
+ +[AMSOnDeviceDataService recordSyncRequest:]
+ +[AMSOnDeviceDataSyncRequest supportsSecureCoding]
+ +[AMSSignInContext supportsSecureCoding]
+ -[AMSDaemonConnection onDeviceDataServiceProxy]
+ -[AMSOnDeviceDataSyncRequest .cxx_destruct]
+ -[AMSOnDeviceDataSyncRequest accountIdentity]
+ -[AMSOnDeviceDataSyncRequest afterDelay]
+ -[AMSOnDeviceDataSyncRequest copyWithZone:]
+ -[AMSOnDeviceDataSyncRequest datasetName]
+ -[AMSOnDeviceDataSyncRequest datasetNamespace]
+ -[AMSOnDeviceDataSyncRequest description]
+ -[AMSOnDeviceDataSyncRequest encodeWithCoder:]
+ -[AMSOnDeviceDataSyncRequest hash]
+ -[AMSOnDeviceDataSyncRequest idDomain]
+ -[AMSOnDeviceDataSyncRequest idSource]
+ -[AMSOnDeviceDataSyncRequest idSuffix]
+ -[AMSOnDeviceDataSyncRequest identifier]
+ -[AMSOnDeviceDataSyncRequest initWithCoder:]
+ -[AMSOnDeviceDataSyncRequest initWithNamespace:idSource:idDomain:identifier:accountID:datasetName:idSuffix:afterDelay:]
+ -[AMSOnDeviceDataSyncRequest isEqual:]
+ -[AMSProcessInfo processIdentifier]
+ -[AMSProcessInfo setProcessIdentifier:]
+ -[AMSSignInContext encodeWithCoder:]
+ -[AMSSignInContext initWithCoder:]
+ OBJC_IVAR_$_AMSOnDeviceDataSyncRequest._accountIdentity
+ OBJC_IVAR_$_AMSOnDeviceDataSyncRequest._afterDelay
+ OBJC_IVAR_$_AMSOnDeviceDataSyncRequest._datasetName
+ OBJC_IVAR_$_AMSOnDeviceDataSyncRequest._datasetNamespace
+ OBJC_IVAR_$_AMSOnDeviceDataSyncRequest._idDomain
+ OBJC_IVAR_$_AMSOnDeviceDataSyncRequest._idSource
+ OBJC_IVAR_$_AMSOnDeviceDataSyncRequest._idSuffix
+ OBJC_IVAR_$_AMSOnDeviceDataSyncRequest._identifier
+ OBJC_IVAR_$_AMSProcessInfo._processIdentifier
+ _OBJC_CLASS_$_AMSAuthenticationViewServiceLauncher
+ _OBJC_CLASS_$_AMSOnDeviceDataService
+ _OBJC_CLASS_$_AMSOnDeviceDataSyncRequest
+ _OBJC_CLASS_$_AMSRemoteSignInRequest
+ _OBJC_METACLASS_$_AMSAuthenticationViewServiceLauncher
+ _OBJC_METACLASS_$_AMSOnDeviceDataService
+ _OBJC_METACLASS_$_AMSOnDeviceDataSyncRequest
+ _OBJC_METACLASS_$_AMSRemoteSignInRequest
+ _PROTOCOLS_AMSRemoteSignInRequest
+ __44+[AMSOnDeviceDataService recordSyncRequest:]_block_invoke
+ __CLASS_METHODS_AMSRemoteSignInRequest
+ __CLASS_PROPERTIES_AMSRemoteSignInRequest
+ __DATA_AMSRemoteSignInRequest
+ __INSTANCE_METHODS_AMSRemoteSignInRequest
+ __IVARS_AMSRemoteSignInRequest
+ __METACLASS_DATA_AMSRemoteSignInRequest
+ __OBJC_$_CLASS_METHODS_AMSOnDeviceDataService
+ __OBJC_$_CLASS_METHODS_AMSOnDeviceDataSyncRequest
+ __OBJC_$_CLASS_METHODS_AMSSignInContext
+ __OBJC_$_CLASS_PROP_LIST_AMSOnDeviceDataSyncRequest
+ __OBJC_$_CLASS_PROP_LIST_AMSSignInContext
+ __OBJC_$_INSTANCE_METHODS_AMSOnDeviceDataSyncRequest
+ __OBJC_$_INSTANCE_VARIABLES_AMSOnDeviceDataSyncRequest
+ __OBJC_$_PROP_LIST_AMSOnDeviceDataSyncRequest
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AMSOnDeviceDataServiceInterface
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AMSOnDeviceDataServiceInterface
+ __OBJC_$_PROTOCOL_REFS_AMSOnDeviceDataServiceInterface
+ __OBJC_CLASS_PROTOCOLS_$_AMSOnDeviceDataSyncRequest
+ __OBJC_CLASS_RO_$_AMSAuthenticationViewServiceLauncher
+ __OBJC_CLASS_RO_$_AMSOnDeviceDataService
+ __OBJC_CLASS_RO_$_AMSOnDeviceDataSyncRequest
+ __OBJC_LABEL_PROTOCOL_$_AMSOnDeviceDataServiceInterface
+ __OBJC_METACLASS_RO_$_AMSAuthenticationViewServiceLauncher
+ __OBJC_METACLASS_RO_$_AMSOnDeviceDataService
+ __OBJC_METACLASS_RO_$_AMSOnDeviceDataSyncRequest
+ __OBJC_PROTOCOL_$_AMSOnDeviceDataServiceInterface
+ __OBJC_PROTOCOL_REFERENCE_$_AMSOnDeviceDataServiceInterface
+ __PROTOCOLS_AMSRemoteSignInRequest
+ ___38+[AMSLogConfig sharedTSDataSyncConfig]_block_invoke
+ ___44+[AMSOnDeviceDataService recordSyncRequest:]_block_invoke
+ ___47-[AMSDaemonConnection onDeviceDataServiceProxy]_block_invoke
+ ___47-[AMSDaemonConnection onDeviceDataServiceProxy]_block_invoke_2
+ ___block_descriptor_48_e8_32s40s_e75_v24?0"<AMSOnDeviceDataServiceInterface><NSXPCProxyCreating>"8"NSError"16l
+ ___block_descriptor_56_e8_32s40s_e55_v24?0"<AMSOnDeviceDataServiceInterface>"8"NSError"16l
+ _associated conformance 18AppleMediaServices13SignInRequestC11ServiceTypeOSHAASQ
+ _dynamic_cast_existential_0_class_conditional
+ _objc_msgSend$_onDeviceDataInterface
+ _objc_msgSend$accountIdentity
+ _objc_msgSend$afterDelay
+ _objc_msgSend$askToSync:reply:
+ _objc_msgSend$customHTTPHeaders
+ _objc_msgSend$datasetName
+ _objc_msgSend$datasetNamespace
+ _objc_msgSend$disableTapToRadar
+ _objc_msgSend$getOnDeviceDataServiceProxyWithReplyHandler:
+ _objc_msgSend$idDomain
+ _objc_msgSend$idSource
+ _objc_msgSend$idSuffix
+ _objc_msgSend$onDeviceDataServiceProxy
+ _objc_msgSend$sharedTSDataSyncConfig
+ _swift_isClassType
+ _symbolic Say_____G 18AppleMediaServices13SignInRequestC11ServiceTypeO
+ _symbolic So16AMSSignInContextCSg
+ _symbolic So8NSObjectCm
+ _symbolic _____ 18AppleMediaServices13SignInRequestC
+ _symbolic _____ 18AppleMediaServices13SignInRequestC11ServiceTypeO
+ _symbolic _____ySo8NSObjectCmG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 18AppleMediaServices13SignInRequestC11ServiceTypeO
+ _symbolic _____yyXlXpG s23_ContiguousArrayStorageC
CStrings:
+ " (datasetName: %@, namespace: %@, idSource: %@, idDomain: %@, identifier: %@, accountIdentity: %@, idSuffix: %@, afterDelay: %@)"
+ "%{public}@ [%{public}@] No on-device data sync request"
+ "%{public}@ [%{public}@] Recording on-device data sync request: %{public}@"
+ "%{public}@Privacy acknowledgement is not needed because AMSDevice.isRunningInStoreDemoMode is true."
+ "@\"AMSAccountIdentity\""
+ "AMSAuthenticationViewServiceLauncher"
+ "AMSDisableTapToRadar"
+ "AMSOnDeviceDataService"
+ "AMSOnDeviceDataServiceInterface"
+ "AMSOnDeviceDataSyncRequest"
+ "AMSRemoteSignInRequest"
+ "AppleMediaServices.SignInRequest"
+ "Missing on-device data sync request"
+ "T@\"AMSAccountIdentity\",R,N,V_accountIdentity"
+ "T@\"NSNumber\",&,V_processIdentifier"
+ "T@\"NSNumber\",R,N,V_afterDelay"
+ "T@\"NSString\",R,N,V_datasetName"
+ "T@\"NSString\",R,N,V_datasetNamespace"
+ "T@\"NSString\",R,N,V_idDomain"
+ "T@\"NSString\",R,N,V_idSource"
+ "T@\"NSString\",R,N,V_idSuffix"
+ "T@\"NSString\",R,N,V_identifier"
+ "_accountIdentity"
+ "_afterDelay"
+ "_datasetName"
+ "_datasetNamespace"
+ "_idDomain"
+ "_idSource"
+ "_idSuffix"
+ "_onDeviceDataInterface"
+ "accountIdentity"
+ "afterDelay"
+ "askToSync:reply:"
+ "datasetName"
+ "datasetNamespace"
+ "disableTapToRadar"
+ "getOnDeviceDataServiceProxyWithReplyHandler:"
+ "idDomain"
+ "idSource"
+ "idSuffix"
+ "initWithNamespace:idSource:idDomain:identifier:accountID:datasetName:idSuffix:afterDelay:"
+ "kCodingKeyAccountID"
+ "kCodingKeyAfterDelay"
+ "kCodingKeyDatasetName"
+ "kCodingKeyIDDomain"
+ "kCodingKeyIDSource"
+ "kCodingKeyIDSuffix"
+ "kCodingKeyNamespace"
+ "onDeviceDataServiceProxy"
+ "recordSyncRequest:"
+ "setDisableTapToRadar:"
+ "sharedTSDataSyncConfig"
+ "signInContext"
+ "v24@0:8@?<v@?@\"<AMSOnDeviceDataServiceInterface>\"@\"NSError\">16"
+ "v24@?0@\"<AMSOnDeviceDataServiceInterface>\"8@\"NSError\"16"
+ "v24@?0@\"<AMSOnDeviceDataServiceInterface><NSXPCProxyCreating>\"8@\"NSError\"16"
+ "v32@0:8@\"AMSOnDeviceDataSyncRequest\"16@?<v@?B@\"NSError\">24"
- "\r"
- "%{public}@: [%{public}@] The dialog was cancelled by the user"
- "Dialog cancelled"
```
