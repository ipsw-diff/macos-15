## DeviceManagement

> `/System/Library/PrivateFrameworks/DeviceManagement.framework/Versions/A/DeviceManagement`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-221.4.7.0.0
-  __TEXT.__text: 0x3dbcc
+221.5.1.0.0
+  __TEXT.__text: 0x3da38
   __TEXT.__auth_stubs: 0x450
   __TEXT.__objc_methlist: 0x7314
-  __TEXT.__const: 0x90
-  __TEXT.__cstring: 0x5039
-  __TEXT.__oslogstring: 0xda1
+  __TEXT.__const: 0x98
+  __TEXT.__cstring: 0x5040
+  __TEXT.__oslogstring: 0xd91
   __TEXT.__ustring: 0xb64
-  __TEXT.__gcc_except_tab: 0x2f8
-  __TEXT.__unwind_info: 0xf30
+  __TEXT.__gcc_except_tab: 0x2e8
+  __TEXT.__unwind_info: 0xf38
   __TEXT.__objc_classname: 0x178e
-  __TEXT.__objc_methname: 0x9c05
-  __TEXT.__objc_methtype: 0xb24
-  __TEXT.__objc_stubs: 0x4c40
+  __TEXT.__objc_methname: 0x9bee
+  __TEXT.__objc_methtype: 0xb15
+  __TEXT.__objc_stubs: 0x4c60
   __DATA_CONST.__got: 0x368
-  __DATA_CONST.__const: 0xa08
+  __DATA_CONST.__const: 0xa10
   __DATA_CONST.__objc_classlist: 0x618
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x58

   __AUTH_CONST.__auth_got: 0x238
   __AUTH_CONST.__const: 0x9e0
   __AUTH_CONST.__cfstring: 0x7360
-  __AUTH_CONST.__objc_const: 0x102c8
+  __AUTH_CONST.__objc_const: 0x10298
   __AUTH_CONST.__objc_intobj: 0x1518
   __AUTH_CONST.__objc_arrayobj: 0x888
   __AUTH.__objc_data: 0x2a8
-  __DATA.__objc_ivar: 0x8d4
+  __DATA.__objc_ivar: 0x8d0
   __DATA.__data: 0x430
   __DATA.__bss: 0x188
   __DATA_DIRTY.__objc_data: 0x3a48

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 2359
-  Symbols:   5443
-  CStrings:  2795
+  Symbols:   5446
+  CStrings:  2794
 
Symbols:
+ -[DMFPolicyMonitor allExpiredScreenTimeBudgetsWithCompletionHandler:]
+ -[DMFPolicyMonitor allExpiredScreenTimeBudgetsWithError:]
+ GCC_except_table68
+ _DMFAppSourceDeclarativeManagement
+ _OUTLINED_FUNCTION_10
+ _OUTLINED_FUNCTION_9
+ __57-[DMFPolicyMonitor allExpiredScreenTimeBudgetsWithError:]_block_invoke
+ __69-[DMFPolicyMonitor allExpiredScreenTimeBudgetsWithCompletionHandler:]_block_invoke
+ ___57-[DMFPolicyMonitor allExpiredScreenTimeBudgetsWithError:]_block_invoke
+ ___69-[DMFPolicyMonitor allExpiredScreenTimeBudgetsWithCompletionHandler:]_block_invoke
+ ___block_descriptor_48_e8_32r40r_e29_v24?0"NSArray"8"NSError"16l
+ ___block_descriptor_48_e8_32s40bs_e29_v24?0"NSArray"8"NSError"16l
+ _objc_msgSend$allExpiredScreenTimeBudgetsShouldBeSynchronous:replyHandler:
+ _objc_msgSend$allExpiredScreenTimeBudgetsWithCompletionHandler:
+ _objc_msgSend$allExpiredScreenTimeBudgetsWithError:
- -[DMFMDMv1UpdateAppRequest ignoreNilConfiguration]
- -[DMFMDMv1UpdateAppRequest setIgnoreNilConfiguration:]
- GCC_except_table67
- OBJC_IVAR_$_DMFMDMv1UpdateAppRequest._ignoreNilConfiguration
- __64-[DMFPolicyMonitor filterForExpiredBudgetIdentifiers:withError:]_block_invoke
- __72-[DMFPolicyMonitor filterForExpiredBudgetIdentifiers:completionHandler:]_block_invoke
- ___64-[DMFPolicyMonitor filterForExpiredBudgetIdentifiers:withError:]_block_invoke
- ___72-[DMFPolicyMonitor filterForExpiredBudgetIdentifiers:completionHandler:]_block_invoke
- ___block_descriptor_56_e8_32s40r48r_e29_v24?0"NSArray"8"NSError"16l
- ___block_descriptor_56_e8_32s40s48bs_e29_v24?0"NSArray"8"NSError"16l
- _objc_msgSend$filterForExpiredBudgetIdentifiers:shouldBeSynchronous:replyHandler:
- _objc_msgSend$ignoreNilConfiguration
CStrings:
+ "Declarative Device Management"
+ "Failed to get identifiers with error: %{public}@"
+ "Successfully got identifiers. Result: %@{public}"
+ "allExpiredScreenTimeBudgetsShouldBeSynchronous:replyHandler:"
+ "allExpiredScreenTimeBudgetsWithCompletionHandler:"
+ "allExpiredScreenTimeBudgetsWithError:"
+ "v28@0:8B16@?20"
+ "v28@0:8B16@?<v@?@\"NSArray\"@\"NSError\">20"
- "Failed to filter %lu identifiers with error: %{public}@"
- "Successfully filtered %lu identifiers. Result: %@{public}"
- "TB,N,V_ignoreNilConfiguration"
- "_ignoreNilConfiguration"
- "filterForExpiredBudgetIdentifiers:shouldBeSynchronous:replyHandler:"
- "ignoreNilConfiguration"
- "setIgnoreNilConfiguration:"
- "v36@0:8@\"NSArray\"16B24@?<v@?@\"NSArray\"@\"NSError\">28"
- "v36@0:8@16B24@?28"
```
