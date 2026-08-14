## com.apple.AppleSystemPolicy

> `com.apple.AppleSystemPolicy`

```diff

-620.120.1.0.0
+620.120.4.0.0
   __TEXT.__const: 0x208
   __TEXT.__cstring: 0x2063
-  __TEXT.__os_log: 0x711
-  __TEXT_EXEC.__text: 0xc7fc
+  __TEXT.__os_log: 0x742
+  __TEXT_EXEC.__text: 0xc968
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x858
   __DATA.__common: 0x1aa
   __DATA.__bss: 0x74
-  __DATA_CONST.__auth_got: 0x490
+  __DATA_CONST.__auth_got: 0x498
   __DATA_CONST.__got: 0x70
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__mod_init_func: 0x10
   __DATA_CONST.__mod_term_func: 0x10
   __DATA_CONST.__const: 0x19e8
   __DATA_CONST.__kalloc_type: 0x180
-  Functions: 293
-  Symbols:   909
-  CStrings:  274
+  Functions: 294
+  Symbols:   912
+  CStrings:  275
 
Symbols:
+ _VNOP_IOCTL
+ __ZN17ASPEvaluationInfo21is_authapfs_protectedEb
+ __ZZN17AppleSystemPolicy22procNotifyExecCompleteEP4procE11_os_log_fmt_4
Functions:
+ __ZN17ASPEvaluationInfo21is_authapfs_protectedEb
~ __ZN17AppleSystemPolicy14evaluateScriptEP14ASPProcessInfoP13ASPScriptInfo : 2400 -> 2436
~ __ZN17AppleSystemPolicy22procNotifyExecCompleteEP4proc : 3976 -> 4016
~ __ZL28is_evaluation_exempt_processP14ASPProcessInfo : 68 -> 92
~ __ZN17AppleSystemPolicy16checkLibraryLoadEP14ASPProcessInfoP14ASPLibraryInfoxmb : 3556 -> 3612
CStrings:
+ "Checking library evaluation: %d (%d, %d) %s, %s"
+ "Skipping evaluation due to exemption: %s"
- "Checking library evaluation: %d, %s, %s"
```
