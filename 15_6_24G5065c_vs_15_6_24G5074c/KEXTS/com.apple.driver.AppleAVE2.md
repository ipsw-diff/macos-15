## com.apple.driver.AppleAVE2

> `com.apple.driver.AppleAVE2`

```diff

-803.71.1.0.0
+803.73.1.0.0
   __TEXT.__const: 0x2ef60
-  __TEXT.__cstring: 0x353af
-  __TEXT.__os_log: 0x409be
-  __TEXT_EXEC.__text: 0x14a1dc
+  __TEXT.__cstring: 0x35402
+  __TEXT.__os_log: 0x409fa
+  __TEXT_EXEC.__text: 0x14a2ac
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x290
   __DATA.__common: 0x130

   __DATA_CONST.__kalloc_type: 0x3f80
   __DATA_CONST.__kalloc_var: 0x1b80
   Functions: 2450
-  Symbols:   8466
-  CStrings:  6955
+  Symbols:   8467
+  CStrings:  6957
 
Symbols:
+ __Z24AVE_Client_CheckPriorityP35AVE_SessionSettings_UserKernel_Data
+ __ZZN7AVE_HwC18ProcessIntr_CmdAckEmiE11_os_log_fmt_2
- __Z24AVE_Client_CheckPriorityP13_S_AVE_Client
Functions:
~ __ZN7AVE_HwC18ProcessIntr_CmdAckEmi : 808 -> 1048
~ __ZN7AVE_HwC15ProcessIntr_CmdEmij : 6660 -> 6620
~ ___chkstk_darwin_probe : 44 -> 52
CStrings:
+ "%lld %d AVE %s: %s::%s:%d %s | wrong command %p 0x%lx %d %d"
+ "%lld %d AVE %s: %s::%s:%d %s | wrong command %p 0x%lx %d %d\n"
+ "(cmd > AVE_Cmd_None && cmd < AVE_Cmd_Max)"
+ "18:48:41"
+ "803.73.1"
+ "Jul  6 2025"
- "22:30:20"
- "803.71.1"
- "Jun 17 2025"
- "cmd != AVE_Cmd_None"
```
