## ModuleBase

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/ModuleBase.framework/Versions/A/ModuleBase`

```diff

-1656.120.2.0.0
-  __TEXT.__text: 0x83c0
-  __TEXT.__auth_stubs: 0x320
-  __TEXT.__objc_methlist: 0x9f4
+1656.120.5.0.0
+  __TEXT.__text: 0x8608
+  __TEXT.__auth_stubs: 0x330
+  __TEXT.__objc_methlist: 0xa8c
   __TEXT.__const: 0xe8
-  __TEXT.__cstring: 0x935
+  __TEXT.__cstring: 0x92b
   __TEXT.__ustring: 0xc
-  __TEXT.__gcc_except_tab: 0xa0
-  __TEXT.__oslogstring: 0x752
-  __TEXT.__unwind_info: 0x270
-  __TEXT.__objc_classname: 0x152
-  __TEXT.__objc_methname: 0x201a
-  __TEXT.__objc_methtype: 0xcdc
-  __TEXT.__objc_stubs: 0x1620
-  __DATA_CONST.__got: 0x168
-  __DATA_CONST.__const: 0x88
-  __DATA_CONST.__objc_classlist: 0x40
-  __DATA_CONST.__objc_protolist: 0x40
+  __TEXT.__gcc_except_tab: 0xbc
+  __TEXT.__oslogstring: 0x727
+  __TEXT.__unwind_info: 0x288
+  __TEXT.__objc_classname: 0x199
+  __TEXT.__objc_methname: 0x20b4
+  __TEXT.__objc_methtype: 0xd35
+  __TEXT.__objc_stubs: 0x16a0
+  __DATA_CONST.__got: 0x178
+  __DATA_CONST.__const: 0x48
+  __DATA_CONST.__objc_classlist: 0x48
+  __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x828
+  __DATA_CONST.__objc_selrefs: 0x860
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x40
-  __AUTH_CONST.__auth_got: 0x1a0
-  __AUTH_CONST.__const: 0x370
+  __AUTH_CONST.__auth_got: 0x1a8
+  __AUTH_CONST.__const: 0x360
   __AUTH_CONST.__cfstring: 0xa20
-  __AUTH_CONST.__objc_const: 0x13a8
+  __AUTH_CONST.__objc_const: 0x1530
   __AUTH_CONST.__objc_intobj: 0xd8
-  __AUTH.__objc_data: 0x280
-  __DATA.__objc_ivar: 0xd0
-  __DATA.__data: 0x300
+  __AUTH.__objc_data: 0x2d0
+  __DATA.__objc_ivar: 0xd8
+  __DATA.__data: 0x3c0
   __DATA.__bss: 0x88
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /System/Library/PrivateFrameworks/LocalAuthenticationCore.framework/Versions/A/LocalAuthenticationCore
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 201
-  Symbols:   645
-  CStrings:  637
+  Functions: 209
+  Symbols:   676
+  CStrings:  651
 
Symbols:
+ +[AgentProxy _remoteSystemDaemon]
+ +[DaemonProxy sharedInstance]
+ -[DaemonProxy .cxx_destruct]
+ -[DaemonProxy agentProxyWrapper:didFailToObtainRemoteProxyWithError:]
+ -[DaemonProxy agentProxy]
+ -[DaemonProxy connection]
+ -[DaemonProxy reset]
+ -[DaemonProxy setConnection:]
+ OBJC_IVAR_$_DaemonProxy._agentProxy
+ OBJC_IVAR_$_DaemonProxy._connection
+ _LACLogServer
+ _OBJC_CLASS_$_DaemonProxy
+ _OBJC_CLASS_$_LACAgentProxyXPCWrapper
+ _OBJC_METACLASS_$_DaemonProxy
+ __OBJC_$_CLASS_METHODS_DaemonProxy
+ __OBJC_$_INSTANCE_METHODS_DaemonProxy
+ __OBJC_$_INSTANCE_VARIABLES_DaemonProxy
+ __OBJC_$_PROP_LIST_DaemonProxy
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_LACAgentProxyRegistering
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_LACAgentProxyXPCWrapperDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_LACAgentProxyRegistering
+ __OBJC_$_PROTOCOL_METHOD_TYPES_LACAgentProxyXPCWrapperDelegate
+ __OBJC_$_PROTOCOL_REFS_LACAgentProxyRegistering
+ __OBJC_$_PROTOCOL_REFS_LACAgentProxyXPCWrapperDelegate
+ __OBJC_CLASS_PROTOCOLS_$_DaemonProxy
+ __OBJC_CLASS_RO_$_DaemonProxy
+ __OBJC_LABEL_PROTOCOL_$_LACAgentProxyRegistering
+ __OBJC_LABEL_PROTOCOL_$_LACAgentProxyXPCWrapperDelegate
+ __OBJC_METACLASS_RO_$_DaemonProxy
+ __OBJC_PROTOCOL_$_LACAgentProxyRegistering
+ __OBJC_PROTOCOL_$_LACAgentProxyXPCWrapperDelegate
+ ___25-[DaemonProxy agentProxy]_block_invoke
+ ___25-[DaemonProxy connection]_block_invoke
+ ___29+[DaemonProxy sharedInstance]_block_invoke
+ ___block_descriptor_40_e8_32s_e30_"LACAgentProxyXPCWrapper"8?0l
+ _objc_alloc_init
+ _objc_msgSend$_remoteSystemDaemon
+ _objc_msgSend$agentProxy
+ _objc_msgSend$connection
+ _objc_msgSend$initWithConnection:
+ _objc_msgSend$reset
+ _objc_msgSend$setDelegate:
- __38+[AgentProxy agentProxyInSystemDaemon]_block_invoke
- __38+[AgentProxy agentProxyInSystemDaemon]_block_invoke_2
- ___38+[AgentProxy agentProxyInSystemDaemon]_block_invoke
- ___38+[AgentProxy agentProxyInSystemDaemon]_block_invoke_2
- ___block_descriptor_32_e17_v16?0"NSError"8l
- ___block_descriptor_32_e40_v24?0"<LACAgentProxyXPC>"8"NSError"16l
- __agentProxy
- __os_log_fault_impl
- __systemDaemonConnection
- _objc_msgSend$registerAgentProxyWithCompletionHandler:
- _objc_msgSend$synchronousRemoteObjectProxyWithErrorHandler:
CStrings:
+ "@\"<LACAgentProxyXPC>\""
+ "@\"LACAgentProxyXPCWrapper\"8@?0"
+ "@\"NSXPCConnection\""
+ "DaemonProxy"
+ "LACAgentProxyRegistering"
+ "LACAgentProxyXPCWrapperDelegate"
+ "T@\"NSXPCConnection\",&,N,V_connection"
+ "_connection"
+ "_remoteSystemDaemon"
+ "agentProxy"
+ "agentProxyWrapper:didFailToObtainRemoteProxyWithError:"
+ "connection"
+ "initWithConnection:"
+ "reset"
+ "setConnection:"
+ "setDelegate:"
+ "v32@0:8@\"LACAgentProxyXPCWrapper\"16@\"NSError\"24"
- "Failed to register agent proxy: %{public}@"
- "synchronousRemoteObjectProxyWithErrorHandler:"
- "v24@?0@\"<LACAgentProxyXPC>\"8@\"NSError\"16"
```
