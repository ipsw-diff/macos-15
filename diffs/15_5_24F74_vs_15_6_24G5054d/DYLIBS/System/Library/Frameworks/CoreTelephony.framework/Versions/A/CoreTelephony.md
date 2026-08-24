## CoreTelephony

> `/System/Library/Frameworks/CoreTelephony.framework/Versions/A/CoreTelephony`

```diff

-12409.0.0.0.0
-  __TEXT.__text: 0x1391cc
-  __TEXT.__auth_stubs: 0x13d0
-  __TEXT.__objc_methlist: 0x12084
-  __TEXT.__cstring: 0x182bf
+12412.0.0.0.0
+  __TEXT.__text: 0x13b114
+  __TEXT.__auth_stubs: 0x13f0
+  __TEXT.__objc_methlist: 0x120ac
+  __TEXT.__cstring: 0x18420
   __TEXT.__const: 0xfc5
-  __TEXT.__gcc_except_tab: 0x13e98
-  __TEXT.__oslogstring: 0x3214
-  __TEXT.__unwind_info: 0x8d58
+  __TEXT.__gcc_except_tab: 0x13f58
+  __TEXT.__oslogstring: 0x36af
+  __TEXT.__unwind_info: 0x8d80
   __TEXT.__objc_classname: 0x3c84
-  __TEXT.__objc_methname: 0x19334
-  __TEXT.__objc_methtype: 0x6563
-  __TEXT.__objc_stubs: 0x10120
+  __TEXT.__objc_methname: 0x19368
+  __TEXT.__objc_methtype: 0x65d2
+  __TEXT.__objc_stubs: 0x101e0
   __DATA_CONST.__got: 0x7d8
-  __DATA_CONST.__const: 0x4b98
+  __DATA_CONST.__const: 0x4c08
   __DATA_CONST.__objc_classlist: 0xe08
   __DATA_CONST.__objc_protolist: 0x1f8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5878
+  __DATA_CONST.__objc_selrefs: 0x5888
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0xe48
   __DATA_CONST.__objc_arraydata: 0x20
-  __AUTH_CONST.__auth_got: 0xa00
-  __AUTH_CONST.__const: 0x3018
-  __AUTH_CONST.__cfstring: 0x15920
-  __AUTH_CONST.__objc_const: 0x20370
+  __AUTH_CONST.__auth_got: 0xa10
+  __AUTH_CONST.__const: 0x3068
+  __AUTH_CONST.__cfstring: 0x15980
+  __AUTH_CONST.__objc_const: 0x20380
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH.__objc_data: 0x6fe0

   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0x1c70
   __DATA_DIRTY.__data: 0x40
-  __DATA_DIRTY.__bss: 0x74
+  __DATA_DIRTY.__bss: 0x84
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libTelephonyUtilDynamic.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 7999
-  Symbols:   17638
-  CStrings:  9571
+  Functions: 8019
+  Symbols:   17677
+  CStrings:  9617
 
Symbols:
+ -[CoreTelephonyClient(SMS) injectMTsms:smsData:completion:]
+ _CTServerConnectionGetCommCenterInitializationState
+ _CTServerConnectionRegisterForEvent
+ _CTServerConnectionUnregisterForAllNotifications
+ _CTServerConnectionUnregisterForEvent
+ _OUTLINED_FUNCTION_7
+ _OUTLINED_FUNCTION_8
+ _Z25SendXpcMessageWithCachingP20__CTServerConnectionRKN3xpc4dictERS2_20CTFeatureRequirement
+ _ZL17logBlockedRequestPKcRKN3xpc4dictEP20__CTServerConnection20CTFeatureRequirement
+ _ZL25_HandlePrepWorkBeforeSendP20__CTServerConnectionRN3xpc4dictEb
+ _ZN12_GLOBAL__N_128ReregisterClientForAllEventsEP20__CTServerConnection
+ _ZN13MMSPduDecoder19decodeEncodedHeaderEPK20MMSHeaderEncodingMap
+ _ZN9CCMonitor10initializeEv
+ _ZN9CCMonitor17handleDaemonReadyEv
+ _ZZN8dispatch5asyncIZN9CCMonitor10initializeEvE3$_0EEvP16dispatch_queue_sNSt3__110unique_ptrIT_NS5_14default_deleteIS7_EEEEENUlPvE_8__invokeESB_
+ _ZZN8dispatch5asyncIZN9CCMonitor10initializeEvE3$_1EEvP16dispatch_queue_sNSt3__110unique_ptrIT_NS5_14default_deleteIS7_EEEEENUlPvE_8__invokeESB_
+ _ZZN8dispatch5asyncIZZN9CCMonitor10initializeEvEUb_E3$_0EEvP16dispatch_queue_sNSt3__110unique_ptrIT_NS5_14default_deleteIS7_EEEEENUlPvE_8__invokeESB_
+ __ZL17logBlockedRequestPKcRKN3xpc4dictEP20__CTServerConnection20CTFeatureRequirement
+ __ZZN8dispatch5asyncIZN9CCMonitor10initializeEvE3$_1EEvP16dispatch_queue_sNSt3__110unique_ptrIT_NS5_14default_deleteIS7_EEEEENUlPvE_8__invokeESB_
+ __ZZN8dispatch5asyncIZZN9CCMonitor10initializeEvEUb_E3$_0EEvP16dispatch_queue_sNSt3__110unique_ptrIT_NS5_14default_deleteIS7_EEEEENUlPvE_8__invokeESB_
+ __ZZN9CCMonitor9getLoggerEvE10sOnceToken
+ __ZZN9CCMonitor9getLoggerEvE7sLogger
+ ___55-[CoreTelephonyClient(Stewie) testStewieCommand:error:]_block_invoke
+ ___55-[CoreTelephonyClient(Stewie) testStewieCommand:error:]_block_invoke_2
+ ___59-[CoreTelephonyClient(SMS) injectMTsms:smsData:completion:]_block_invoke
+ ___60-[CoreTelephonyClient(Stewie) testStewieCommand:completion:]_block_invoke
+ ___ZL30_CTServerConnectionReEstablishP20__CTServerConnection_block_invoke
+ ___ZN9CCMonitor9getLoggerEv_block_invoke
+ ____ZN9CCMonitor10initializeEv_block_invoke
+ ____ZN9CCMonitor9getLoggerEv_block_invoke
+ ___block_descriptor_48_e8_32r40r_e34_v24?0"NSError"8"NSDictionary"16l
+ _notify_get_state
+ _notify_register_dispatch
+ _objc_msgSend$epki
+ _objc_msgSend$injectMTsms:smsData:completion:
+ _objc_msgSend$setEpki:
+ _objc_msgSend$setShared:
+ _objc_msgSend$shared
+ _objc_msgSend$testStewieCommand:completion:
CStrings:
+ "#D "
+ "#D %s"
+ "#D Body:"
+ "#D DataLen = %u"
+ "#D HeadersLen = %u"
+ "#D Part %u"
+ "#D nEntries = %u"
+ ", epki=%@, shared=%@"
+ "12412"
+ "12412~189"
+ "Attempt to connect to CT from %s blocked, use _CTServerConnectionAddIdentifierException to add exception"
+ "Available features: [%s]"
+ "Blocking %s (request: '%s', state: %s, required: %s, %p)"
+ "CTStewieRequestReasonAnywhere"
+ "CTStewieRequestReasonAnywhereTest"
+ "CTStewieRequestReasonTest"
+ "CommCenter is always-on. CCMonitor is NOT used"
+ "Communication blocked but cached value found. Request: '%s'. Reply: '%s'"
+ "CoreTelephony logging is %s by default"
+ "Daemon becomes ready..."
+ "Failed to create notify token for '%s'. Logging is %s by default"
+ "Failed to re-register notifications in _HandleConnectionReEstablished(). Error: {domain=%d, error=%d}"
+ "Failed to re-register notifications in _HandlePrepWorkBeforeSend(). Error: {domain=%d, error=%d}"
+ "Logging is %s"
+ "OS log created"
+ "ReregisterClientForAllEvents request is not allowed at this time. Registration is delayed"
+ "XPC message"
+ "XPC message with reply"
+ "_CTServerConnectionGetCommCenterInitializationState request is not allowed at this time"
+ "_CTServerConnectionRegisterForEvent request is not allowed at this time. Registration is delayed"
+ "_CTServerConnectionUnregisterForAllNotifications request is not allowed at this time"
+ "_CTServerConnectionUnregisterForEvent request is not allowed at this time"
+ "async XPC message"
+ "com.apple.CoreTelephony.LoggingEnabled"
+ "injectMTsms:smsData:completion:"
+ "invalidateKey:with:"
+ "kBaseband"
+ "kDaemonRunning"
+ "kDefaultAllowed"
+ "kNotRunning"
+ "kRunning"
+ "kTestBlocked"
+ "kThumper"
+ "kUnknown"
+ "v12@?0i8"
+ "v24@?0@\"NSError\"8@\"NSDictionary\"16"
+ "v32@0:8@\"NSData\"16@?<v@?@\"NSError\">24"
+ "v40@0:8@\"CTXPCServiceSubscriptionContext\"16@\"CTSMSDataType\"24@?<v@?^@>32"
- "12409"
- "12409~40"
```
