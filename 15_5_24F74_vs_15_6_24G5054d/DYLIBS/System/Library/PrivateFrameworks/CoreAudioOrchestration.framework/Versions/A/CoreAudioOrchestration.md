## CoreAudioOrchestration

> `/System/Library/PrivateFrameworks/CoreAudioOrchestration.framework/Versions/A/CoreAudioOrchestration`

```diff

-35.0.0.0.0
-  __TEXT.__text: 0x5dbd0
-  __TEXT.__auth_stubs: 0x1370
-  __TEXT.__objc_methlist: 0x4b4
-  __TEXT.__const: 0x8674
-  __TEXT.__gcc_except_tab: 0x2f0
-  __TEXT.__cstring: 0x1f33
-  __TEXT.__oslogstring: 0x1095
-  __TEXT.__constg_swiftt: 0x2c70
-  __TEXT.__swift5_typeref: 0x1e4f
-  __TEXT.__swift5_reflstr: 0xd9e
-  __TEXT.__swift5_fieldmd: 0x1e84
+44.0.0.0.0
+  __TEXT.__text: 0x6736c
+  __TEXT.__auth_stubs: 0x15e0
+  __TEXT.__objc_methlist: 0x764
+  __TEXT.__const: 0x8c84
+  __TEXT.__gcc_except_tab: 0x4ec
+  __TEXT.__cstring: 0x2433
+  __TEXT.__oslogstring: 0x1365
+  __TEXT.__constg_swiftt: 0x2f28
+  __TEXT.__swift5_typeref: 0x209f
+  __TEXT.__swift5_reflstr: 0xf4e
+  __TEXT.__swift5_fieldmd: 0x1ff0
   __TEXT.__swift5_builtin: 0xa0
-  __TEXT.__swift5_assocty: 0x190
-  __TEXT.__swift5_proto: 0x8bc
-  __TEXT.__swift5_types: 0x300
-  __TEXT.__swift5_protos: 0x20
+  __TEXT.__swift5_assocty: 0x220
+  __TEXT.__swift5_proto: 0x904
+  __TEXT.__swift5_types: 0x324
+  __TEXT.__swift5_protos: 0x24
   __TEXT.__swift5_mpenum: 0x48
-  __TEXT.__swift5_capture: 0x16c
-  __TEXT.__unwind_info: 0x1dc0
-  __TEXT.__eh_frame: 0x2a38
-  __TEXT.__objc_classname: 0xdd
-  __TEXT.__objc_methname: 0x6d4
-  __TEXT.__objc_methtype: 0xefc
-  __TEXT.__objc_stubs: 0x260
-  __DATA_CONST.__got: 0x228
-  __DATA_CONST.__const: 0x90
-  __DATA_CONST.__objc_classlist: 0x198
-  __DATA_CONST.__objc_protolist: 0x38
+  __TEXT.__swift5_capture: 0x2a4
+  __TEXT.__swift_as_entry: 0x2c
+  __TEXT.__swift_as_ret: 0x1c
+  __TEXT.__unwind_info: 0x20f8
+  __TEXT.__eh_frame: 0x2f40
+  __TEXT.__objc_classname: 0x194
+  __TEXT.__objc_methname: 0xb73
+  __TEXT.__objc_methtype: 0x105d
+  __TEXT.__objc_stubs: 0x4e0
+  __DATA_CONST.__got: 0x2b0
+  __DATA_CONST.__const: 0x98
+  __DATA_CONST.__objc_classlist: 0x1d8
+  __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x250
-  __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x20
-  __AUTH_CONST.__auth_got: 0x9c8
-  __AUTH_CONST.__const: 0x4f58
-  __AUTH_CONST.__cfstring: 0x60
-  __AUTH_CONST.__objc_const: 0x2eb0
-  __AUTH.__objc_data: 0x2a0
-  __AUTH.__data: 0x3110
-  __DATA.__objc_ivar: 0x30
-  __DATA.__data: 0x1c20
-  __DATA.__bss: 0x11420
-  __DATA.__common: 0x30
+  __DATA_CONST.__objc_selrefs: 0x3a0
+  __DATA_CONST.__objc_protorefs: 0x28
+  __DATA_CONST.__objc_superrefs: 0x28
+  __AUTH_CONST.__auth_got: 0xb00
+  __AUTH_CONST.__const: 0x55c8
+  __AUTH_CONST.__cfstring: 0x160
+  __AUTH_CONST.__objc_const: 0x3b20
+  __AUTH.__objc_data: 0x828
+  __AUTH.__data: 0x32e0
+  __DATA.__objc_ivar: 0x3c
+  __DATA.__data: 0x1ef0
+  __DATA.__bss: 0x11d20
+  __DATA.__common: 0x50
   - /System/Library/Frameworks/CoreAudio.framework/Versions/A/CoreAudio
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
+  - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
   - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/PrivateFrameworks/FeatureFlags.framework/Versions/A/FeatureFlags
   - /System/Library/PrivateFrameworks/caulk.framework/Versions/A/caulk

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
+  - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswift_errno.dylib
   - /usr/lib/swift/libswift_math.dylib
   - /usr/lib/swift/libswift_signal.dylib

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 2527
-  Symbols:   1363
-  CStrings:  459
+  Functions: 2735
+  Symbols:   1584
+  CStrings:  575
 
Symbols:
+ +[ExclaveAudioFormatBase createFrom:forUseCase:error:]
+ -[DSPController adaptToConfigurationChange:error:inputStreamIndicesInIOProc:outputStreamIndicesInIOProc:frameBufferSize:]
+ -[ExclaveAudioFormatBase .cxx_destruct]
+ -[ExclaveAudioFormatBase channels]
+ -[ExclaveAudioFormatBase framesPerIO]
+ -[ExclaveAudioFormatBase initWithExclaveUseCaseFormat:]
+ -[ExclaveAudioFormatBase initWithSampleRate:andChannels:andFrameSize:]
+ -[ExclaveAudioFormatBase isEqual:]
+ -[ExclaveAudioFormatBase sampleRate]
+ -[IORegistryEmbeddedDeviceTreeAudioInfo createCFTypeRefForKey:atPath:error:]
+ -[NonARCCoreAudioOrchestrationDelegate activateConfiguration:]
+ -[NonARCCoreAudioOrchestrationDelegate createConfiguration:]
+ -[NonARCCoreAudioOrchestrationDelegate deactivateConfiguration:]
+ -[NonARCCoreAudioOrchestrationDelegate destroyConfiguration:]
+ -[NonARCCoreAudioOrchestrationDelegate getProperty:]
+ -[NonARCCoreAudioOrchestrationDelegate registerEventCallback:]
+ -[NonARCCoreAudioOrchestrationDelegate setProperty:]
+ -[NonARCCoreAudioOrchestrationDelegate subscribeToConfigurationEventNotifications:with:]
+ -[NonARCCoreAudioOrchestrationDelegate subscribeToEvent:]
+ -[NonARCCoreAudioOrchestrationDelegate unsubscribeFromConfigurationEventNotifications:]
+ -[NonARCCoreAudioOrchestrationDelegate unsubscribeFromEvent:]
+ GCC_except_table10
+ GCC_except_table9
+ OBJC_IVAR_$_ExclaveAudioFormatBase._channels
+ OBJC_IVAR_$_ExclaveAudioFormatBase._framesPerIO
+ OBJC_IVAR_$_ExclaveAudioFormatBase._sampleRate
+ _CFDataGetBytes
+ _CFDataGetLength
+ _CFDataGetTypeID
+ _CFGetTypeID
+ _CFRelease
+ _EDTReadingErrorDomain
+ _GetCAOrchestrator
+ _IOMainPort
+ _IOObjectRelease
+ _IORegistryEntryCreateCFProperty
+ _IORegistryEntryFromPath
+ _NSLocalizedDescriptionKey
+ _OBJC_CLASS_$_ExclaveAudioFormatBase
+ _OBJC_CLASS_$_IORegistryEmbeddedDeviceTreeAudioInfo
+ _OBJC_CLASS_$_NSError
+ _OBJC_CLASS_$_NSLock
+ _OBJC_CLASS_$_NSNumber
+ _OBJC_CLASS_$_NSString
+ _OBJC_CLASS_$_NSXPCInterface
+ _OBJC_CLASS_$_NSXPCListener
+ _OBJC_CLASS_$_NonARCCoreAudioOrchestrationDelegate
+ _OBJC_CLASS_$__TtC22CoreAudioOrchestration10Stravinsky
+ _OBJC_CLASS_$__TtC22CoreAudioOrchestration12NSXPCService
+ _OBJC_CLASS_$__TtC22CoreAudioOrchestration18ExclaveAudioFormat
+ _OBJC_CLASS_$__TtC22CoreAudioOrchestration29ClientSharedAudioNSXPCService
+ _OBJC_CLASS_$__TtC22CoreAudioOrchestration30CoreAudioOrchestrationDelegate
+ _OBJC_METACLASS_$_ExclaveAudioFormatBase
+ _OBJC_METACLASS_$_IORegistryEmbeddedDeviceTreeAudioInfo
+ _OBJC_METACLASS_$_NonARCCoreAudioOrchestrationDelegate
+ _OBJC_METACLASS_$__TtC22CoreAudioOrchestration10Stravinsky
+ _OBJC_METACLASS_$__TtC22CoreAudioOrchestration12NSXPCService
+ _OBJC_METACLASS_$__TtC22CoreAudioOrchestration18ExclaveAudioFormat
+ _OBJC_METACLASS_$__TtC22CoreAudioOrchestration29ClientSharedAudioNSXPCService
+ _OBJC_METACLASS_$__TtC22CoreAudioOrchestration30CoreAudioOrchestrationDelegate
+ _PROTOCOLS__TtC22CoreAudioOrchestration12NSXPCService
+ _PROTOCOLS__TtC22CoreAudioOrchestration26MicActivityServiceDelegate
+ __Block_copy
+ __Block_release
+ __CLASS_METHODS__TtC22CoreAudioOrchestration10Stravinsky
+ __DATA__TtC22CoreAudioOrchestration10Stravinsky
+ __DATA__TtC22CoreAudioOrchestration12NSXPCService
+ __DATA__TtC22CoreAudioOrchestration18ExclaveAudioFormat
+ __DATA__TtC22CoreAudioOrchestration19MicActivityDService
+ __DATA__TtC22CoreAudioOrchestration26MicActivityServiceDelegate
+ __DATA__TtC22CoreAudioOrchestration26OrchestrationClientService
+ __DATA__TtC22CoreAudioOrchestration29ClientSharedAudioNSXPCService
+ __INSTANCE_METHODS__TtC22CoreAudioOrchestration10Stravinsky
+ __INSTANCE_METHODS__TtC22CoreAudioOrchestration12NSXPCService
+ __INSTANCE_METHODS__TtC22CoreAudioOrchestration18ExclaveAudioFormat
+ __INSTANCE_METHODS__TtC22CoreAudioOrchestration26MicActivityServiceDelegate
+ __INSTANCE_METHODS__TtC22CoreAudioOrchestration29ClientSharedAudioNSXPCService
+ __IVARS__TtC22CoreAudioOrchestration12NSXPCService
+ __IVARS__TtC22CoreAudioOrchestration26OrchestrationClientService
+ __IVARS__TtC22CoreAudioOrchestration29ClientSharedAudioNSXPCService
+ __METACLASS_DATA__TtC22CoreAudioOrchestration10Stravinsky
+ __METACLASS_DATA__TtC22CoreAudioOrchestration12NSXPCService
+ __METACLASS_DATA__TtC22CoreAudioOrchestration18ExclaveAudioFormat
+ __METACLASS_DATA__TtC22CoreAudioOrchestration19MicActivityDService
+ __METACLASS_DATA__TtC22CoreAudioOrchestration26MicActivityServiceDelegate
+ __METACLASS_DATA__TtC22CoreAudioOrchestration26OrchestrationClientService
+ __METACLASS_DATA__TtC22CoreAudioOrchestration29ClientSharedAudioNSXPCService
+ __NSConcreteStackBlock
+ __OBJC_$_CLASS_METHODS_ExclaveAudioFormatBase
+ __OBJC_$_INSTANCE_METHODS_ExclaveAudioFormatBase
+ __OBJC_$_INSTANCE_METHODS_IORegistryEmbeddedDeviceTreeAudioInfo
+ __OBJC_$_INSTANCE_METHODS_NonARCCoreAudioOrchestrationDelegate
+ __OBJC_$_INSTANCE_VARIABLES_ExclaveAudioFormatBase
+ __OBJC_$_PROP_LIST_ExclaveAudioFormatBase
+ __OBJC_$_PROP_LIST_IORegistryEmbeddedDeviceTreeAudioInfo
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CAOrchestrator
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CAOrchestratorEventCallback
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_EmbeddedDeviceTreeAudioInfo
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MicActivityClientProtocol
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSXPCListenerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CAOrchestrator
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CAOrchestratorEventCallback
+ __OBJC_$_PROTOCOL_METHOD_TYPES_EmbeddedDeviceTreeAudioInfo
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MicActivityClientProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSXPCListenerDelegate
+ __OBJC_$_PROTOCOL_REFS_EmbeddedDeviceTreeAudioInfo
+ __OBJC_$_PROTOCOL_REFS_NSXPCListenerDelegate
+ __OBJC_CLASS_PROTOCOLS_$_IORegistryEmbeddedDeviceTreeAudioInfo
+ __OBJC_CLASS_PROTOCOLS_$_NonARCCoreAudioOrchestrationDelegate
+ __OBJC_CLASS_RO_$_ExclaveAudioFormatBase
+ __OBJC_CLASS_RO_$_IORegistryEmbeddedDeviceTreeAudioInfo
+ __OBJC_CLASS_RO_$_NonARCCoreAudioOrchestrationDelegate
+ __OBJC_LABEL_PROTOCOL_$_CAOrchestrator
+ __OBJC_LABEL_PROTOCOL_$_CAOrchestratorEventCallback
+ __OBJC_LABEL_PROTOCOL_$_EmbeddedDeviceTreeAudioInfo
+ __OBJC_LABEL_PROTOCOL_$_MicActivityClientProtocol
+ __OBJC_LABEL_PROTOCOL_$_NSXPCListenerDelegate
+ __OBJC_METACLASS_RO_$_ExclaveAudioFormatBase
+ __OBJC_METACLASS_RO_$_IORegistryEmbeddedDeviceTreeAudioInfo
+ __OBJC_METACLASS_RO_$_NonARCCoreAudioOrchestrationDelegate
+ __OBJC_PROTOCOL_$_CAOrchestrator
+ __OBJC_PROTOCOL_$_CAOrchestratorEventCallback
+ __OBJC_PROTOCOL_$_EmbeddedDeviceTreeAudioInfo
+ __OBJC_PROTOCOL_$_MicActivityClientProtocol
+ __OBJC_PROTOCOL_$_NSXPCListenerDelegate
+ __PROTOCOLS__TtC22CoreAudioOrchestration12NSXPCService
+ __PROTOCOLS__TtC22CoreAudioOrchestration26MicActivityServiceDelegate
+ __Z15GetEntryForPathPKcPU15__autoreleasingP7NSError
+ __Z25ExADUseCaseFormatsFromEDTPU38objcproto27EmbeddedDeviceTreeAudioInfo11objc_objectPU15__autoreleasingP7NSError
+ __Z34ExADUseCaseFormatForUseCaseFromEDTPU38objcproto27EmbeddedDeviceTreeAudioInfo11objc_objectjPU15__autoreleasingP7NSError
+ __ZN10applesauce2CF7DataRefD1Ev
+ __ZN10applesauce2CF9ObjectRefIPK8__CFDataED1Ev
+ __ZN13RegistryEntryD2Ev
+ __ZNKSt3__16vectorI17ExADUseCaseFormatNS_9allocatorIS1_EEE20__throw_length_errorB8ne190102Ev
+ __ZNSt13runtime_errorC1EPKc
+ __ZNSt13runtime_errorD1Ev
+ __ZNSt3__119__allocate_at_leastB8ne190102INS_9allocatorI17ExADUseCaseFormatEEEENS_19__allocation_resultINS_16allocator_traitsIT_E7pointerEEERS6_m
+ __ZNSt3__16vectorI17ExADUseCaseFormatNS_9allocatorIS1_EEE11__vallocateB8ne190102Em
+ __ZNSt3__16vectorI17ExADUseCaseFormatNS_9allocatorIS1_EEEC2B8ne190102Em
+ __ZTISt13runtime_error
+ ___swift_allocate_boxed_opaque_existential_0
+ ___swift_async_entry_functlets
+ ___swift_async_ret_functlets
+ ___swift_memcpy89_8
+ ___swift_project_boxed_opaque_existential_0
+ ___swift_project_boxed_opaque_existential_1Tm
+ __swift_stdlib_bridgeErrorToNSError
+ __swift_stdlib_reportUnimplementedInitializer
+ _associated conformance 22CoreAudioOrchestration07ExclaveB6FormatC10CodingKeysOSHAASQ
+ _associated conformance 22CoreAudioOrchestration07ExclaveB6FormatC10CodingKeysOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 22CoreAudioOrchestration07ExclaveB6FormatC10CodingKeysOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 22CoreAudioOrchestration0abC12FeatureFlagsOSHAASQ
+ _associated conformance 22CoreAudioOrchestration18XPCConnectionErrorOSHAASQ
+ _associated conformance 22CoreAudioOrchestration20HardwareAvailabilityOSHAASQ
+ _associated conformance 22CoreAudioOrchestration27XPCConnectionRegistrarErrorOSHAASQ
+ _associated conformance 22CoreAudioOrchestration9ClientUIDOSHAASQ
+ _block_copy_helper
+ _block_descriptor
+ _block_destroy_helper
+ _bootstrap_port
+ _flat unique So27CAOrchestratorEventCallback_p
+ _kCFAllocatorDefault
+ _objc_alloc_init
+ _objc_autorelease
+ _objc_msgSend$GetOrchestrationDelegate
+ _objc_msgSend$UTF8String
+ _objc_msgSend$activateConfigurationWithDescription:
+ _objc_msgSend$channels
+ _objc_msgSend$createCFTypeRefForKey:atPath:error:
+ _objc_msgSend$createConfigurationWithDescription:
+ _objc_msgSend$deactivateConfigurationWithDescription:
+ _objc_msgSend$destroyConfigurationWithDescription:
+ _objc_msgSend$errorWithDomain:code:userInfo:
+ _objc_msgSend$framesPerIO
+ _objc_msgSend$getPropertyWithDescription:
+ _objc_msgSend$initWithExclaveUseCaseFormat:
+ _objc_msgSend$isEqualToNumber:
+ _objc_msgSend$numberWithUnsignedInt:
+ _objc_msgSend$registerWithEventCallback:
+ _objc_msgSend$sampleRate
+ _objc_msgSend$setPropertyWithDescription:
+ _objc_msgSend$stringByAppendingString:
+ _objc_msgSend$stringWithFormat:
+ _objc_msgSend$subscribeToEventWithDescription:
+ _objc_msgSend$unsubscribeFromEventWithDescription:
+ _objc_opt_class
+ _objc_opt_isKindOfClass
+ _objc_retainAutorelease
+ _objc_retainAutoreleaseReturnValue
+ _printf
+ _swift_deletedAsyncMethodErrorTu
+ _swift_isaMask
+ _swift_lookUpClassMethod
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _symbolic $s22CoreAudioOrchestration13ClientServiceP
+ _symbolic $s22CoreAudioOrchestration14MessagePayloadP
+ _symbolic IeAgH_
+ _symbolic IeghH_
+ _symbolic SDy_____SgShySiGG 22CoreAudioOrchestration9ClientUIDO
+ _symbolic SDy__________G 22CoreAudioOrchestration9ClientUIDO AA0D13XPCConnectionC
+ _symbolic SDy___________pG 22CoreAudioOrchestration9ClientUIDO AA0D7ServiceP
+ _symbolic ScA_pSg
+ _symbolic ScPSg
+ _symbolic Shy_____G s5Int32V
+ _symbolic So13NSXPCListenerC
+ _symbolic So14NSXPCInterfaceC
+ _symbolic So21NSXPCListenerEndpointCSg
+ _symbolic So22ExclaveAudioFormatBaseC
+ _symbolic So6NSLockC
+ _symbolic So8NSObjectCSg
+ _symbolic _____ 22CoreAudioOrchestration012ClientSharedB12NSXPCServiceC
+ _symbolic _____ 22CoreAudioOrchestration07ExclaveB6FormatC
+ _symbolic _____ 22CoreAudioOrchestration07ExclaveB6FormatC10CodingKeysO
+ _symbolic _____ 22CoreAudioOrchestration0C13ClientServiceC
+ _symbolic _____ 22CoreAudioOrchestration0abC12FeatureFlagsO
+ _symbolic _____ 22CoreAudioOrchestration10StravinskyC
+ _symbolic _____ 22CoreAudioOrchestration12NSXPCServiceC
+ _symbolic _____ 22CoreAudioOrchestration18XPCConnectionErrorO
+ _symbolic _____ 22CoreAudioOrchestration19MicActivityDServiceC
+ _symbolic _____ 22CoreAudioOrchestration20HardwareAvailabilityO
+ _symbolic _____ 22CoreAudioOrchestration26MicActivityServiceDelegateC
+ _symbolic _____ 22CoreAudioOrchestration27XPCConnectionRegistrarErrorO
+ _symbolic _____ 22CoreAudioOrchestration9ClientUIDO
+ _symbolic _____IeyBy_Sg s5Int32V
+ _symbolic _____Sg 22CoreAudioOrchestration9ClientUIDO
+ _symbolic _____SgXw 22CoreAudioOrchestration12NSXPCServiceC
+ _symbolic _____SgXwz_Xx 22CoreAudioOrchestration12NSXPCServiceC
+ _symbolic ____________pt 22CoreAudioOrchestration9ClientUIDO AA0D7ServiceP
+ _symbolic ______p 22CoreAudioOrchestration14MessagePayloadP
+ _symbolic ______pSg 22CoreAudioOrchestration13ClientServiceP
+ _symbolic ______pSg 22CoreAudioOrchestration14MessagePayloadP
+ _symbolic ______pSg So27CAOrchestratorEventCallbackP
+ _symbolic _____y_____G s11_SetStorageC s5Int32V
+ _symbolic _____y_____G s22KeyedDecodingContainerV 22CoreAudioOrchestration07ExclaveE6FormatC10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 22CoreAudioOrchestration07ExclaveE6FormatC10CodingKeysO
+ _symbolic _____y_____SSG s18_DictionaryStorageC 22CoreAudioOrchestration9ClientUIDO
+ _symbolic _____y_____SgShySiGG s18_DictionaryStorageC 22CoreAudioOrchestration9ClientUIDO
+ _symbolic _____y______GSg 22CoreAudioOrchestration0aB15OrchestratorXPCC8ResponseO AA0B10SystemInfoC
+ _symbolic _____y______GSg 22CoreAudioOrchestration0aB15OrchestratorXPCC8ResponseO s5Int32V
+ _symbolic _____y______SgGSg 22CoreAudioOrchestration0aB15OrchestratorXPCC8ResponseO 10Foundation4DataV
+ _symbolic _____y______SgGSg 22CoreAudioOrchestration0aB15OrchestratorXPCC8ResponseO AA3ADMV05AdaptF0V
+ _symbolic _____y______SgGSg 22CoreAudioOrchestration0aB15OrchestratorXPCC8ResponseO AA3ADMV09NegotiateF0V
+ _symbolic _____y__________G s18_DictionaryStorageC 22CoreAudioOrchestration9ClientUIDO AC0F13XPCConnectionC
+ _symbolic _____y__________G s18_DictionaryStorageC 22CoreAudioOrchestration9ClientUIDO AC5RouteC
+ _symbolic _____y___________pG s18_DictionaryStorageC 22CoreAudioOrchestration9ClientUIDO AC0F7ServiceP
+ _symbolic _____y___________tG s23_ContiguousArrayStorageC 22CoreAudioOrchestration9ClientUIDO AC5RouteC
+ _symbolic yp
+ _symbolic ypm
+ _symbolic ytIeAgHr_
+ block_copy_helper
+ block_descriptor
+ block_destroy_helper
+ objectdestroy.8Tm
- -[DSPController adaptToConfigurationChange:error:inputStreamIndicesInIOProc:outputStreamIndicesInIOProc:]
- _OBJC_CLASS_$__TtC22CoreAudioOrchestration28CoreAudioOrchestratorFactory
- _OBJC_METACLASS_$__TtC22CoreAudioOrchestration28CoreAudioOrchestratorFactory
- _PROTOCOLS__TtC22CoreAudioOrchestration30CoreAudioOrchestrationDelegate
- __CLASS_METHODS__TtC22CoreAudioOrchestration28CoreAudioOrchestratorFactory
- __DATA__TtC22CoreAudioOrchestration24StravinskyClientServices
- __DATA__TtC22CoreAudioOrchestration28CoreAudioOrchestratorFactory
- __INSTANCE_METHODS__TtC22CoreAudioOrchestration28CoreAudioOrchestratorFactory
- __IVARS__TtC22CoreAudioOrchestration24StravinskyClientServices
- __METACLASS_DATA__TtC22CoreAudioOrchestration24StravinskyClientServices
- __METACLASS_DATA__TtC22CoreAudioOrchestration28CoreAudioOrchestratorFactory
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_CoreAudioOrchestrationEventCallback
- __OBJC_$_PROTOCOL_METHOD_TYPES_CoreAudioOrchestrationEventCallback
- __OBJC_LABEL_PROTOCOL_$_CoreAudioOrchestrationEventCallback
- __OBJC_PROTOCOL_$_CoreAudioOrchestrationEventCallback
- __PROTOCOLS__TtC22CoreAudioOrchestration30CoreAudioOrchestrationDelegate
- ___swift_memcpy105_8
- ___swift_project_boxed_opaque_existential_0Tm
- _associated conformance 22CoreAudioOrchestration29IsolatedUseCaseServiceWasLostV10CodingKeys33_7F44CEDF6732FB2CDE4A26681F34ABDELLOSHAASQ
- _associated conformance 22CoreAudioOrchestration29IsolatedUseCaseServiceWasLostV10CodingKeys33_7F44CEDF6732FB2CDE4A26681F34ABDELLOs0J3KeyAAs23CustomStringConvertible
- _associated conformance 22CoreAudioOrchestration29IsolatedUseCaseServiceWasLostV10CodingKeys33_7F44CEDF6732FB2CDE4A26681F34ABDELLOs0J3KeyAAs28CustomDebugStringConvertible
- _flat unique So35CoreAudioOrchestrationEventCallback_p
- _objc_msgSend$GetOrchestrator
- _swift_unexpectedError
- _symbolic $s22CoreAudioOrchestration14ClientServicesP
- _symbolic SDySSSgShySiGG
- _symbolic SDySS_____G 22CoreAudioOrchestration19ClientXPCConnectionC
- _symbolic _____ 22CoreAudioOrchestration0aB19OrchestratorFactoryC
- _symbolic _____ 22CoreAudioOrchestration24StravinskyClientServicesC
- _symbolic _____ 22CoreAudioOrchestration29IsolatedUseCaseServiceWasLostV
- _symbolic _____ 22CoreAudioOrchestration29IsolatedUseCaseServiceWasLostV10CodingKeys33_7F44CEDF6732FB2CDE4A26681F34ABDELLO
- _symbolic ______p 22CoreAudioOrchestration14ClientServicesP
- _symbolic ______pSg So35CoreAudioOrchestrationEventCallbackP
- _symbolic _____m 22CoreAudioOrchestration29IsolatedUseCaseServiceWasLostV
- _symbolic _____ySSSgShySiGG s18_DictionaryStorageC
- _symbolic _____ySS_____G s18_DictionaryStorageC 22CoreAudioOrchestration19ClientXPCConnectionC
- _symbolic _____y_____G s22KeyedDecodingContainerV 22CoreAudioOrchestration29IsolatedUseCaseServiceWasLostV10CodingKeys33_7F44CEDF6732FB2CDE4A26681F34ABDELLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 22CoreAudioOrchestration29IsolatedUseCaseServiceWasLostV10CodingKeys33_7F44CEDF6732FB2CDE4A26681F34ABDELLO
CStrings:
+ " does not conform to MessagePayload"
+ "%s: Failed to get IOMainPort.\n"
+ "%s: Invalid argumnents: %p\n"
+ "@\"NSDictionary\"24@0:8@\"<CAOrchestratorEventCallback>\"16"
+ "@\"NSNumber\""
+ "@24@0:8r^{ExADUseCaseFormat=IIII[4I]}16"
+ "@28@0:8I16I20I24"
+ "@36@0:8@16I24^@28"
+ "@56@0:8@16^@24@32@40Q48"
+ "ADM not used, featureflag set: CoreAudioOrchestration_DisableADM"
+ "Activating connection for: %d"
+ "AudioHAL"
+ "B32@0:8@\"NSXPCListener\"16@\"NSXPCConnection\"24"
+ "B32@0:8@16@24"
+ "CAOrchestrator"
+ "CAOrchestratorEventCallback"
+ "Client arrived, but failed to initialize use case availability: %@"
+ "Connection interrupted for: %d"
+ "Connection invalidated for: %d"
+ "CoreAudioOrchestration.ExclaveAudioFormat"
+ "CoreAudioOrchestration.NSXPCService"
+ "CoreAudioOrchestration_DisableADM"
+ "Could not construct"
+ "Disabling mic activity detection"
+ "EDTReadingErrorDomain"
+ "EmbeddedDeviceTreeAudioInfo"
+ "Enabling mic activity detection"
+ "Error getting ExclaveAudioFormat from EDT: %s"
+ "ExclaveAudioFormatBase"
+ "Failed to parse unserializable "
+ "GetEntryForPath"
+ "GetOrchestrationDelegate"
+ "HAD"
+ "HAD is not connected"
+ "HADHardwareAvailability"
+ "HADuniqueAggregate"
+ "Hardware unavailable for: "
+ "IODeviceTree:/product/audio"
+ "IORegistryEmbeddedDeviceTreeAudioInfo"
+ "Listening for mic activity detection"
+ "MicActivityClientProtocol"
+ "NSXPCListenerDelegate"
+ "NonARCCoreAudioOrchestrationDelegate"
+ "Received CreateOrchestratorClientPortalForMAD"
+ "ServerRegistrarXPCService dropped an event: clientArrived(%s)"
+ "ServerRegistrarXPCService dropped an event: clientDied(%s)"
+ "ServerRegistrarXPCService dropped an event: propagateHardwareAvailability(%s, %{bool}d)"
+ "Size error: %ld , expecting a multiple >0 of : %lu"
+ "Something went wrong when attempting to launch %s!"
+ "Stop listenting for mic activity detection"
+ "T@\"NSNumber\",R,N,V_channels"
+ "T@\"NSNumber\",R,N,V_framesPerIO"
+ "T@\"NSNumber\",R,N,V_sampleRate"
+ "UTF8String"
+ "Unimplemented handleActivation for: %d"
+ "Unimplemented handleInterruption for: %d"
+ "Unimplemented handleInvalidation for: %d"
+ "^v40@0:8@\"NSString\"16@\"NSString\"24^@32"
+ "^v40@0:8@16@24^@32"
+ "_TtC22CoreAudioOrchestration10Stravinsky"
+ "_TtC22CoreAudioOrchestration12NSXPCService"
+ "_TtC22CoreAudioOrchestration18ExclaveAudioFormat"
+ "_TtC22CoreAudioOrchestration19MicActivityDService"
+ "_TtC22CoreAudioOrchestration26MicActivityServiceDelegate"
+ "_TtC22CoreAudioOrchestration26OrchestrationClientService"
+ "_TtC22CoreAudioOrchestration29ClientSharedAudioNSXPCService"
+ "_channels"
+ "_framesPerIO"
+ "_sampleRate"
+ "activate"
+ "activateConfigurationWithDescription:"
+ "adaptToConfigurationChange:error:inputStreamIndicesInIOProc:outputStreamIndicesInIOProc:frameBufferSize:"
+ "channels"
+ "clientServiceUID"
+ "clientUIDMap"
+ "com.apple.audio.isolated.micactivityd"
+ "com.apple.private.audio.orchestration.micactivityd"
+ "createCFTypeRefForKey:atPath:error:"
+ "createConfigurationWithDescription:"
+ "createFrom:forUseCase:error:"
+ "deactivateConfigurationWithDescription:"
+ "destroyConfigurationWithDescription:"
+ "disableMicrophoneActivityDetection:"
+ "enableMicrophoneActivityDetection:"
+ "endpoint"
+ "errorWithDomain:code:userInfo:"
+ "exclaveAudioFormat"
+ "frameSize"
+ "framesPerIO"
+ "getPropertyWithDescription:"
+ "init()"
+ "initWithExclaveUseCaseFormat:"
+ "initWithMachServiceName:"
+ "initWithSampleRate:andChannels:andFrameSize:"
+ "interface"
+ "interfaceDelegate"
+ "interfaceWithProtocol:"
+ "isEqualToNumber:"
+ "isValidJSONObject:"
+ "key not found: "
+ "listenForMicrophoneActivity:reply:"
+ "listener:shouldAcceptNewConnection:"
+ "localizedDescription"
+ "lock"
+ "numberWithUnsignedInt:"
+ "path not found: "
+ "processIdentifier"
+ "registerWithEventCallback:"
+ "sampleRate"
+ "setDelegate:"
+ "setExportedInterface:"
+ "setExportedObject:"
+ "setInterruptionHandler:"
+ "setInvalidationHandler:"
+ "setPropertyWithDescription:"
+ "stopListeningForMicrophoneActivity:"
+ "stringByAppendingString:"
+ "stringWithFormat:"
+ "subscribeToEventWithDescription:"
+ "uid"
+ "unlock"
+ "unsignedIntValue"
+ "unspecified type"
+ "unsubscribeFromEventWithDescription:"
+ "use-case-client-format"
+ "useCaseID not found in EDT table"
+ "v24@0:8@?16"
+ "v24@0:8@?<v@?i>16"
+ "v32@0:8@\"NSXPCListenerEndpoint\"16@?<v@?i>24"
+ "v32@0:8@16@?24"
+ "v8@?0"
+ "wrong data type, expecting CFData"
- "@48@0:8@16^@24@32@40"
- "CoreAudioOrchestration/HALAudioDeviceInfo.swift"
- "CoreAudioOrchestrationEventCallback"
- "GetOrchestrator"
- "ServerRegistrarXPCService dropped an event: serviceWasLost"
- "ServerRegistrarXPCService dropped an event: setHardwareAvailability"
- "Something went wrong when attempting to launch the service!"
- "_TtC22CoreAudioOrchestration24StravinskyClientServices"
- "_TtC22CoreAudioOrchestration28CoreAudioOrchestratorFactory"
- "adaptToConfigurationChange:error:inputStreamIndicesInIOProc:outputStreamIndicesInIOProc:"
- "clientIDMap"
- "clientServiceUUID"
- "defaultInputDevice - ok"
- "hadSession"
- "isHADHardwareAvailable"
- "uuid"
```
