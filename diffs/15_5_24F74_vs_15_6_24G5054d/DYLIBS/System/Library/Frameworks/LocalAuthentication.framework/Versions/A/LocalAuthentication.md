## LocalAuthentication

> `/System/Library/Frameworks/LocalAuthentication.framework/Versions/A/LocalAuthentication`

```diff

-1656.120.6.0.0
-  __TEXT.__text: 0x3bbe8
+1656.140.3.0.0
+  __TEXT.__text: 0x3bc34
   __TEXT.__auth_stubs: 0x920
   __TEXT.__objc_methlist: 0x3470
   __TEXT.__const: 0x2f0
   __TEXT.__gcc_except_tab: 0x1330
   __TEXT.__cstring: 0x1b18
   __TEXT.__dlopen_cstrs: 0x177
-  __TEXT.__oslogstring: 0x2cb9
+  __TEXT.__oslogstring: 0x2cea
   __TEXT.__swift5_typeref: 0x6e
   __TEXT.__constg_swiftt: 0x38
   __TEXT.__swift5_builtin: 0x14

   __TEXT.__swift5_types: 0x4
   __TEXT.__unwind_info: 0x1368
   __TEXT.__eh_frame: 0x48
-  __TEXT.__objc_classname: 0x901
-  __TEXT.__objc_methname: 0x68f5
-  __TEXT.__objc_methtype: 0x1e6d
-  __TEXT.__objc_stubs: 0x4720
-  __DATA_CONST.__got: 0x4c8
+  __TEXT.__objc_classname: 0x91e
+  __TEXT.__objc_methname: 0x687d
+  __TEXT.__objc_methtype: 0x1e75
+  __TEXT.__objc_stubs: 0x46c0
+  __DATA_CONST.__got: 0x4b0
   __DATA_CONST.__const: 0x3a8
-  __DATA_CONST.__objc_classlist: 0x238
+  __DATA_CONST.__objc_classlist: 0x240
   __DATA_CONST.__objc_protolist: 0xf8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1b08
+  __DATA_CONST.__objc_selrefs: 0x1af0
   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__objc_superrefs: 0x1c8
   __DATA_CONST.__objc_arraydata: 0x18
   __AUTH_CONST.__auth_got: 0x4a0
   __AUTH_CONST.__const: 0x20e0
   __AUTH_CONST.__cfstring: 0x1940
-  __AUTH_CONST.__objc_const: 0x7dc0
+  __AUTH_CONST.__objc_const: 0x7e50
   __AUTH_CONST.__objc_intobj: 0x210
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH.__objc_data: 0x1630
+  __AUTH.__objc_data: 0x1680
   __DATA.__objc_ivar: 0x28c
   __DATA.__data: 0xc10
   __DATA.__bss: 0x488

   - /usr/lib/swift/libswift_time.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1507
-  Symbols:   3420
-  CStrings:  2020
+  Functions: 1509
+  Symbols:   3419
+  CStrings:  2019
 
Symbols:
+ -[LAEnvironmentServiceXPCClient _bootstrapServiceType:completion:]
+ -[LAEnvironmentServiceXPCClient _createConnectionToDaemon]
+ -[LAEnvironmentServiceXPCClient _synchronousProxyToEnvironmentServiceWithEndpoint:completion:]
+ -[LAEnvironmentServiceXPCClient synchronousProxyToEnvironmentServiceWithCompletion:]
+ GCC_except_table21
+ OBJC_IVAR_$_LAEnvironment._xpcClient
+ _OBJC_CLASS_$_LACXPCInterface
+ _OBJC_CLASS_$_LAEnvironmentServiceXPCClient
+ _OBJC_METACLASS_$_LAEnvironmentServiceXPCClient
+ __29-[LAEnvironment _updateState]_block_invoke
+ __OBJC_$_INSTANCE_METHODS_LAEnvironmentServiceXPCClient
+ __OBJC_CLASS_RO_$_LAEnvironmentServiceXPCClient
+ __OBJC_METACLASS_RO_$_LAEnvironmentServiceXPCClient
+ ___66-[LAEnvironmentServiceXPCClient _bootstrapServiceType:completion:]_block_invoke
+ ___84-[LAEnvironmentServiceXPCClient synchronousProxyToEnvironmentServiceWithCompletion:]_block_invoke
+ ___94-[LAEnvironmentServiceXPCClient _synchronousProxyToEnvironmentServiceWithEndpoint:completion:]_block_invoke
+ ___block_descriptor_48_e8_32r40r_e43_v24?0"NSXPCListenerEndpoint"8"NSError"16l
+ _objc_msgSend$interfaceForXPCProtocol:
+ _objc_msgSend$synchronousProxyToEnvironmentServiceWithCompletion:
- -[LAEnvironment _bootstrapServiceType:completion:]
- -[LAEnvironment _createConnectionToDaemon]
- -[LAEnvironment _environmentServiceEndpointWithCompletion:]
- -[LAEnvironment _synchronousProxyToEnvironmentServiceWithCompletion:]
- -[LAEnvironment _synchronousProxyToEnvironmentServiceWithEndpoint:completion:]
- GCC_except_table35
- OBJC_IVAR_$_LAEnvironment._environmentServiceEndpoint
- _OBJC_CLASS_$_LACEnvironmentMechanismBiometry
- _OBJC_CLASS_$_LACEnvironmentMechanismCompanion
- _OBJC_CLASS_$_LACEnvironmentMechanismUserPassword
- _OBJC_CLASS_$_LACEnvironmentState
- ___50-[LAEnvironment _bootstrapServiceType:completion:]_block_invoke
- ___69-[LAEnvironment _synchronousProxyToEnvironmentServiceWithCompletion:]_block_invoke
- ___78-[LAEnvironment _synchronousProxyToEnvironmentServiceWithEndpoint:completion:]_block_invoke
- ___block_descriptor_48_e8_32bs40w_e43_v24?0"NSXPCListenerEndpoint"8"NSError"16l
- _objc_msgSend$_environmentServiceEndpointWithCompletion:
- _objc_msgSend$_synchronousProxyToEnvironmentServiceWithCompletion:
- _objc_msgSend$remoteObjectInterface
- _objc_msgSend$setClasses:forSelector:argumentIndex:ofReply:
- _objc_msgSend$setWithObjects:
CStrings:
+ "@\"LAEnvironmentServiceXPCClient\""
+ "Failed to obtain environment endpoint %{public}@"
+ "LAEnvironmentServiceXPCClient"
+ "_xpcClient"
+ "interfaceForXPCProtocol:"
+ "synchronousProxyToEnvironmentServiceWithCompletion:"
- "@\"NSXPCListenerEndpoint\""
- "_environmentServiceEndpoint"
- "_environmentServiceEndpointWithCompletion:"
- "_synchronousProxyToEnvironmentServiceWithCompletion:"
- "remoteObjectInterface"
- "setClasses:forSelector:argumentIndex:ofReply:"
- "setWithObjects:"
```
