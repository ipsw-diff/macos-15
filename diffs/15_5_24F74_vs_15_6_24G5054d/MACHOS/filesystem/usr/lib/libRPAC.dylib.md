## libRPAC.dylib

> `/usr/lib/libRPAC.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__AUTH_CONST.__interpose`
- `__DATA.__objc_selrefs`

```diff

-88.0.0.0.0
-  __TEXT.__text: 0x8e278
-  __TEXT.__auth_stubs: 0x790
+95.0.0.0.0
+  __TEXT.__text: 0x8e61c
+  __TEXT.__auth_stubs: 0x7f0
   __TEXT.__objc_stubs: 0x1a0
   __TEXT.__init_offsets: 0x4
-  __TEXT.__cstring: 0x49ee
-  __TEXT.__gcc_except_tab: 0x44
+  __TEXT.__cstring: 0x4a9d
+  __TEXT.__gcc_except_tab: 0xbc
   __TEXT.__const: 0x1d60
   __TEXT.__objc_methname: 0x13b
   __TEXT.__oslogstring: 0x1d
   __TEXT.__objc_classname: 0x1
-  __TEXT.__unwind_info: 0x298
-  __DATA_CONST.__auth_got: 0x3e0
-  __DATA_CONST.__got: 0x80
+  __TEXT.__unwind_info: 0x2c0
+  __DATA_CONST.__auth_got: 0x410
+  __DATA_CONST.__got: 0x88
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__const: 0x3b8
   __DATA_CONST.__cfstring: 0x260

   __DATA_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__interpose: 0x90
   __DATA.__objc_selrefs: 0x88
-  __DATA.__data: 0x7c4
-  __DATA.__common: 0x800e8
-  __DATA.__bss: 0x580430
+  __DATA.__data: 0x7cc
+  __DATA.__common: 0x80168
+  __DATA.__bss: 0x580338
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/ImageIO.framework/Versions/A/ImageIO
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 197
-  Symbols:   510
-  CStrings:  538
+  Functions: 198
+  Symbols:   524
+  CStrings:  543
 
Symbols:
+ GCC_except_table14
+ GCC_except_table2
+ GCC_except_table3
+ __ZTISt9exception
+ __ZZ22initializePrimitiveMapvE22initialization_success
+ ___cxa_begin_catch
+ ___cxa_end_catch
+ _atoll
+ _dispatch_queue_attr_make_with_qos_class
+ _dispatch_queue_create
+ _dispatch_sync
+ _envDisableXPCChecks
+ _envPriorityInversionDetectionOnMainThreadOnly
+ _envXPCWaitThreshold
+ _strnstr
+ generateCulledBacktrace.issueQueueOrWorkloop
- _dispatch_async_and_wait
- generateCulledBacktrace.issueWorkloop
Functions:
~ __replacement_NSURLConnection_sendSynchronousRequest_returningResponse_error : 88 -> 200
~ _GetThreadLocalData : 164 -> 168
~ ___library_initializer : 2116 -> 2368
~ _interposed_dispatch_group_wait : 336 -> 364
~ _shouldFlag : 256 -> 272
~ _isSystemFrame : 128 -> 160
~ ___simpleFlaggingPolicy_block_invoke : 56 -> 68
~ _custom_xpc_connection_send_message_with_reply_sync : 228 -> 248
~ __replacement_NSCondition_wait : 372 -> 388
~ __replacement_NSCondition_waitUntilDate : 412 -> 428
~ _initializeNSConditionSwizzling : 240 -> 256
~ __Z22initializePrimitiveMapv : 52 -> 64
~ ____Z22initializePrimitiveMapv_block_invoke : 112 -> 168
~ _createPrimitiveEntry : 180 -> 224
~ _findPrimitiveInfoNoAssert : 164 -> 184
~ _qosWaiterSignallerInvariantCheck : 2296 -> 2436
~ _checkAndGenerateBT : 368 -> 372
~ ___generateCulledBacktrace_block_invoke : 216 -> 292
~ _checkUnconditionally : 284 -> 288
~ qosWaiterSignallerInvariantCheck.cold.1 : 44 -> 52
+ generateCulledBacktrace.cold.1
CStrings:
+ "Exception generated in qosWaiterSignallerInvariantCheck. Catching it\n"
+ "PERFC_DISABLE_XPC_CHECKS"
+ "PERFC_ENABLE_PRIORITY_INVERSION_DETECTION_MAIN_THREAD_ONLY"
+ "PERFC_XPC_WAIT_THRESHOLD"
+ "TPC issue queue"
+ "XCTestCore"
- "RPAC issue generation workloop"
```
