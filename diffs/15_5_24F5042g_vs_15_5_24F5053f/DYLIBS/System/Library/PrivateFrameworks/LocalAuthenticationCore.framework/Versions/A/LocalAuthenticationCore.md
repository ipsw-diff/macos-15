## LocalAuthenticationCore

> `/System/Library/PrivateFrameworks/LocalAuthenticationCore.framework/Versions/A/LocalAuthenticationCore`

```diff

-1656.120.2.0.0
-  __TEXT.__text: 0xd2a38
+1656.120.5.0.0
+  __TEXT.__text: 0xd3690
   __TEXT.__auth_stubs: 0x1e60
-  __TEXT.__objc_methlist: 0x79d8
+  __TEXT.__objc_methlist: 0x7a68
   __TEXT.__const: 0x3ac4
-  __TEXT.__cstring: 0xb0c6
-  __TEXT.__oslogstring: 0x5428
-  __TEXT.__gcc_except_tab: 0x10e4
+  __TEXT.__cstring: 0xb0f6
+  __TEXT.__oslogstring: 0x5488
+  __TEXT.__gcc_except_tab: 0x1104
   __TEXT.__dlopen_cstrs: 0x1b0
   __TEXT.__swift5_typeref: 0x148d
   __TEXT.__constg_swiftt: 0xd48

   __TEXT.__swift_as_entry: 0xc8
   __TEXT.__swift_as_ret: 0xd4
   __TEXT.__swift5_mpenum: 0x14
-  __TEXT.__unwind_info: 0x37c0
+  __TEXT.__unwind_info: 0x3818
   __TEXT.__eh_frame: 0x20e8
-  __TEXT.__objc_classname: 0x1cfc
-  __TEXT.__objc_methname: 0xbd30
-  __TEXT.__objc_methtype: 0x3307
-  __TEXT.__objc_stubs: 0x84e0
+  __TEXT.__objc_classname: 0x1d14
+  __TEXT.__objc_methname: 0xbdde
+  __TEXT.__objc_methtype: 0x3342
+  __TEXT.__objc_stubs: 0x8600
   __DATA_CONST.__got: 0x8b0
   __DATA_CONST.__const: 0x2158
-  __DATA_CONST.__objc_classlist: 0x6f8
+  __DATA_CONST.__objc_classlist: 0x700
   __DATA_CONST.__objc_protolist: 0x518
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2d70
+  __DATA_CONST.__objc_selrefs: 0x2d88
   __DATA_CONST.__objc_protorefs: 0x220
-  __DATA_CONST.__objc_superrefs: 0x440
+  __DATA_CONST.__objc_superrefs: 0x448
   __DATA_CONST.__objc_arraydata: 0x40
   __AUTH_CONST.__auth_got: 0xf40
-  __AUTH_CONST.__const: 0x4e78
+  __AUTH_CONST.__const: 0x4fe8
   __AUTH_CONST.__cfstring: 0x4d00
-  __AUTH_CONST.__objc_const: 0x2ff78
+  __AUTH_CONST.__objc_const: 0x30168
   __AUTH_CONST.__objc_intobj: 0x270
   __AUTH_CONST.__objc_arrayobj: 0x78
-  __AUTH.__objc_data: 0x4d48
+  __AUTH.__objc_data: 0x4d98
   __AUTH.__data: 0xcd0
-  __DATA.__objc_ivar: 0x708
+  __DATA.__objc_ivar: 0x714
   __DATA.__data: 0x41d8
-  __DATA.__bss: 0x2091
+  __DATA.__bss: 0x20a1
   __DATA.__common: 0xb8
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 5226
-  Symbols:   11845
-  CStrings:  4651
+  Functions: 5251
+  Symbols:   11897
+  CStrings:  4663
 
Symbols:
+ -[LACAgentProxyXPCWrapper .cxx_destruct]
+ -[LACAgentProxyXPCWrapper _agentProxy:]
+ -[LACAgentProxyXPCWrapper delegate]
+ -[LACAgentProxyXPCWrapper dumpStatusWithCompletion:]
+ -[LACAgentProxyXPCWrapper initWithConnection:]
+ -[LACAgentProxyXPCWrapper queryUuid:completionHandler:]
+ -[LACAgentProxyXPCWrapper registerAcmExternalizedFormHash:uuid:completionHandler:]
+ -[LACAgentProxyXPCWrapper registerContextWithUuid:ownership:description:originalUuid:originalAcmHash:completionHandler:]
+ -[LACAgentProxyXPCWrapper remoteAuthenticationInProgressWithPriority:reply:]
+ -[LACAgentProxyXPCWrapper setDelegate:]
+ -[LACAgentProxyXPCWrapper setFUSDisabled:completionHandler:]
+ LACLogServer
+ LACLogServer.__logObj
+ LACLogServer.onceToken
+ OBJC_IVAR_$_LACAgentProxyXPCWrapper._agentProxy
+ OBJC_IVAR_$_LACAgentProxyXPCWrapper._connection
+ OBJC_IVAR_$_LACAgentProxyXPCWrapper._delegate
+ _LACLogServer
+ _OBJC_CLASS_$_LACAgentProxyXPCWrapper
+ _OBJC_METACLASS_$_LACAgentProxyXPCWrapper
+ __39-[LACAgentProxyXPCWrapper _agentProxy:]_block_invoke
+ __OBJC_$_INSTANCE_METHODS_LACAgentProxyXPCWrapper
+ __OBJC_$_INSTANCE_VARIABLES_LACAgentProxyXPCWrapper
+ __OBJC_$_PROP_LIST_LACAgentProxyXPCWrapper
+ __OBJC_CLASS_PROTOCOLS_$_LACAgentProxyXPCWrapper
+ __OBJC_CLASS_RO_$_LACAgentProxyXPCWrapper
+ __OBJC_METACLASS_RO_$_LACAgentProxyXPCWrapper
+ ___120-[LACAgentProxyXPCWrapper registerContextWithUuid:ownership:description:originalUuid:originalAcmHash:completionHandler:]_block_invoke
+ ___39-[LACAgentProxyXPCWrapper _agentProxy:]_block_invoke
+ ___52-[LACAgentProxyXPCWrapper dumpStatusWithCompletion:]_block_invoke
+ ___55-[LACAgentProxyXPCWrapper queryUuid:completionHandler:]_block_invoke
+ ___60-[LACAgentProxyXPCWrapper setFUSDisabled:completionHandler:]_block_invoke
+ ___76-[LACAgentProxyXPCWrapper remoteAuthenticationInProgressWithPriority:reply:]_block_invoke
+ ___82-[LACAgentProxyXPCWrapper registerAcmExternalizedFormHash:uuid:completionHandler:]_block_invoke
+ ___LACLogServer_block_invoke
+ ___block_descriptor_40_e8_32bs_e40_v24?0"<LACAgentProxyXPC>"8"NSError"16l
+ ___block_descriptor_41_e8_32bs_e40_v24?0"<LACAgentProxyXPC>"8"NSError"16l
+ ___block_descriptor_48_e8_32bs40w_e40_v24?0"<LACAgentProxyXPC>"8"NSError"16l
+ ___block_descriptor_48_e8_32bs_e40_v24?0"<LACAgentProxyXPC>"8"NSError"16l
+ ___block_descriptor_48_e8_32s40bs_e40_v24?0"<LACAgentProxyXPC>"8"NSError"16l
+ ___block_descriptor_56_e8_32s40bs_e40_v24?0"<LACAgentProxyXPC>"8"NSError"16l
+ ___block_descriptor_80_e8_32s40s48s56s64bs_e40_v24?0"<LACAgentProxyXPC>"8"NSError"16l
+ ___copy_helper_block_e8_32s40s48s56s64b
+ _objc_msgSend$_agentProxy:
+ _objc_msgSend$agentProxyWrapper:didFailToObtainRemoteProxyWithError:
+ _objc_msgSend$dumpStatusWithCompletion:
+ _objc_msgSend$queryUuid:completionHandler:
+ _objc_msgSend$registerAcmExternalizedFormHash:uuid:completionHandler:
+ _objc_msgSend$registerAgentProxyWithCompletionHandler:
+ _objc_msgSend$registerContextWithUuid:ownership:description:originalUuid:originalAcmHash:completionHandler:
+ _objc_msgSend$remoteAuthenticationInProgressWithPriority:reply:
+ _objc_msgSend$setFUSDisabled:completionHandler:
CStrings:
+ "@\"<LACAgentProxyXPC>\""
+ "@\"<LACAgentProxyXPCWrapperDelegate>\""
+ "Error on connection to system daemon: %{public}@"
+ "Failed to register agent proxy: %{public}@"
+ "LACAgentProxyXPCWrapper"
+ "Server"
+ "T@\"<LACAgentProxyXPCWrapperDelegate>\",W,N,V_delegate"
+ "_agentProxy"
+ "_agentProxy:"
+ "agentProxyWrapper:didFailToObtainRemoteProxyWithError:"
+ "registerAgentProxyWithCompletionHandler:"
+ "v24@?0@\"<LACAgentProxyXPC>\"8@\"NSError\"16"
```
