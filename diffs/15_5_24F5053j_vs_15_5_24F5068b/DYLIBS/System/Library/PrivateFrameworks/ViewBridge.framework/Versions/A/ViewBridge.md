## ViewBridge

> `/System/Library/PrivateFrameworks/ViewBridge.framework/Versions/A/ViewBridge`

```diff

-769.1.0.0.0
-  __TEXT.__text: 0xc46a8
+770.1.0.0.0
+  __TEXT.__text: 0xc4974
   __TEXT.__auth_stubs: 0x1730
   __TEXT.__init_offsets: 0x4
-  __TEXT.__objc_methlist: 0x7b1c
+  __TEXT.__objc_methlist: 0x7b2c
   __TEXT.__const: 0x229
-  __TEXT.__gcc_except_tab: 0x629c
-  __TEXT.__cstring: 0x22081
-  __TEXT.__oslogstring: 0xdfb9
-  __TEXT.__unwind_info: 0x39f8
+  __TEXT.__gcc_except_tab: 0x62c8
+  __TEXT.__cstring: 0x220ea
+  __TEXT.__oslogstring: 0xdfec
+  __TEXT.__unwind_info: 0x3a10
   __TEXT.__objc_classname: 0x11a0
-  __TEXT.__objc_methname: 0x129dd
-  __TEXT.__objc_methtype: 0x42f8
-  __TEXT.__objc_stubs: 0xf1a0
+  __TEXT.__objc_methname: 0x12a17
+  __TEXT.__objc_methtype: 0x42fb
+  __TEXT.__objc_stubs: 0xf1c0
   __DATA_CONST.__got: 0x628
-  __DATA_CONST.__const: 0x650
+  __DATA_CONST.__const: 0x658
   __DATA_CONST.__objc_classlist: 0x3a8
   __DATA_CONST.__objc_nlclslist: 0x8
   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0x168
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x47e0
+  __DATA_CONST.__objc_selrefs: 0x47e8
   __DATA_CONST.__objc_protorefs: 0xb0
   __DATA_CONST.__objc_superrefs: 0x358
   __DATA_CONST.__objc_arraydata: 0x70
   __AUTH_CONST.__auth_got: 0xbb0
   __AUTH_CONST.__const: 0x3b38
-  __AUTH_CONST.__cfstring: 0xfd40
-  __AUTH_CONST.__objc_const: 0xaaf8
+  __AUTH_CONST.__cfstring: 0xfd60
+  __AUTH_CONST.__objc_const: 0xab18
   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH.__objc_data: 0x2490
   __AUTH.__data: 0x8
-  __DATA.__objc_ivar: 0x758
+  __DATA.__objc_ivar: 0x75c
   __DATA.__data: 0x13d0
   __DATA.__crash_info: 0x40
   __DATA.__bss: 0x668

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 4830
-  Symbols:   8295
-  CStrings:  8147
+  Functions: 4833
+  Symbols:   8301
+  CStrings:  8153
 
Symbols:
+ -[NSVB_QueueingProxy queuedInvocationsAreSpecial:]
+ GCC_except_table448
+ GCC_except_table461
+ GCC_except_table464
+ GCC_except_table473
+ GCC_except_table479
+ GCC_except_table493
+ GCC_except_table541
+ OBJC_IVAR_$_NSVB_QueueingProxy._queuedInvocationsAreSpecial
+ ___54-[NSViewServiceMarshal invokeBlockViaFenceProxyIfAny:]_block_invoke
+ _kAssociateObjectKey_QueuedInvocationIsSpecial
+ _objc_msgSend$queuedInvocationsAreSpecial:
- GCC_except_table460
- GCC_except_table463
- GCC_except_table472
- GCC_except_table492
- GCC_except_table495
- GCC_except_table538
Functions:
~ -[NSViewServiceMarshal invokeBlockViaFenceProxyIfAny:] : 36 -> 260
+ ___54-[NSViewServiceMarshal invokeBlockViaFenceProxyIfAny:]_block_invoke
~ ___40-[NSVB_QueueingProxy forwardInvocation:]_block_invoke : 176 -> 220
~ -[NSVB_QueueingProxy _dispatchSuspendedMessages] : 748 -> 968
+ -[NSVB_QueueingProxy queuedInvocationsAreSpecial:]
+ -[NSViewServiceMarshal invokeBlockViaFenceProxyIfAny:].cold.1
CStrings:
+ "%@ abandoning any remaining invocations due to invalidation"
+ "%@ invalidated while forwarding invocation"
+ "-[NSViewServiceMarshal invokeBlockViaFenceProxyIfAny:]"
+ "AI"
+ "_queuedInvocationsAreSpecial"
+ "com.apple.PassKit.PaymentAuthorizationUIExtension"
+ "queuedInvocationsAreSpecial:"
- "%@ invalidated while dispatching suspended messages"
```
