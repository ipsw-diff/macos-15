## com.apple.driver.AppleSDXC

> `com.apple.driver.AppleSDXC`

```diff

-336.120.2.0.0
-  __TEXT.__cstring: 0x21ee
+336.140.2.0.0
+  __TEXT.__cstring: 0x21ef
   __TEXT.__const: 0x600
-  __TEXT.__os_log: 0x100a
-  __TEXT_EXEC.__text: 0x23344
+  __TEXT.__os_log: 0x1277
+  __TEXT_EXEC.__text: 0x23594
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x118
   __DATA.__common: 0x108

   __DATA_CONST.__mod_term_func: 0x30
   __DATA_CONST.__const: 0x30b0
   __DATA_CONST.__kalloc_type: 0x180
-  Functions: 695
-  Symbols:   1343
-  CStrings:  435
+  Functions: 694
+  Symbols:   1349
+  CStrings:  442
 
Symbols:
+ __ZZN13AppleSDXCSlot11ThreadEntryEvE11_os_log_fmt_2
+ __ZZN13AppleSDXCSlot13SoftwareResetEhE11_os_log_fmt
+ __ZZN13AppleSDXCSlot15HandleInterruptEP22IOInterruptEventSourceiE11_os_log_fmt
+ __ZZN13AppleSDXCSlot22ValidateUHSTwoResponseEjE11_os_log_fmt
+ __ZZN13AppleSDXCSlot23EnableHighSpeedHostModeEvE11_os_log_fmt
+ __ZZN13AppleSDXCSlot24DisableHighSpeedHostModeEvE11_os_log_fmt
+ __ZZN13AppleSDXCSlot26HandleErrorInterruptStatusEtjE11_os_log_fmt_1
- _OUTLINED_FUNCTION_196
CStrings:
+ "12111112122212121111112111112122222222112211111112122112212121211122121122212222222222222222222212222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222112221112"
+ "Downtrain error ABC trigger signaled\n"
+ "SDXC: 2TB+ supported card.\n"
+ "SDXC: Configure card failed on wake from sleep with status=0x%x.\n"
+ "SDXC: DisableHighSpeedHostMode: CMD6 Busy: status=0x%x, counter=%d, Busy1=%d\n"
+ "SDXC: EnableHighSpeedHostMode: CMD6 Busy: status=0x%x, counter=%d, Busy1=%d, Info1=%d\n"
+ "SDXC: HandleErrorInterrupt: EI=0x%x, U2EI=0x%x, fUseAutoCmd12ErrorRecovery=%d, response0=0x%lx, lastcmds=0x%llx\n"
+ "SDXC: HandleErrorInterruptStatus: exiting with status=0x%x\n"
+ "SDXC: HandleInterrupt failed with status=0x%x\n"
+ "SDXC: PrintLogStatus: PresentState=0x%x\n"
+ "SDXC: Software Timeout: cmd=%p, fCurrentState=%d, fPowerOrdinal=%d, fSoftwareTimeoutCount=%d, lastcmds=0x%llx\n"
+ "SDXC: SoftwareReset returning %x, waited=%u, reset type=%u\n"
+ "SDXC: SoftwareTimeout: cmd=%p, reseting with=0x%x\n"
+ "SDXC: UHS-II Configuration failed. status=0x%x, cleanup=0x%x, fc=%d, retryCount=%d, lastcmds=0x%llx\n"
+ "SDXC: invalid uhs-ii response: registerToRead=0x%x, headerResponse=0x%x, argumentResponse=0x%x, status=0x%x\n"
- " Downtrain error ABC trigger signaled "
- "1211111212221212111111211111212222222211221111111212211221212121112212112221222222222222222222212222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222112221112"
- "AppleSDXC: SoftwareTimeout: cmd=%p, count=%d\n"
- "AppleSDXC: SoftwareTimeout: cmd=%p, resting with=0x%x\n"
- "SDXC: 2TB+ supported card."
- "SDXC: HandleErrorInterrupt: EI=0x%x, U2EI=0x%x, lastcmds=0x%llx\n"
- "SDXC: PrintLogStatus: fPresentStateRegister=0x%x\n"
- "SDXC: UHS-II Configuration failed. status=0x%x, fc=%d, retryCount=%d, lastcmds=0x%llx\n"
```
