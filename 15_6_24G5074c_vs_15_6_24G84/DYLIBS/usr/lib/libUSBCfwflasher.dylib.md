## libUSBCfwflasher.dylib

> `/usr/lib/libUSBCfwflasher.dylib`

```diff

 33.0.0.0.0
-  __TEXT.__text: 0x2202c
+  __TEXT.__text: 0x223e0
   __TEXT.__auth_stubs: 0xc70
   __TEXT.__init_offsets: 0x18
   __TEXT.__objc_methlist: 0x4fc
-  __TEXT.__cstring: 0x8cde
+  __TEXT.__cstring: 0x8f14
+  __TEXT.__const: 0x320
   __TEXT.__gcc_except_tab: 0xb1c
-  __TEXT.__const: 0x310
   __TEXT.__oslogstring: 0x20cb
   __TEXT.__unwind_info: 0x5d8
   __TEXT.__objc_classname: 0x50

   __DATA_CONST.__objc_superrefs: 0x20
   __AUTH_CONST.__auth_got: 0x648
   __AUTH_CONST.__const: 0x238
-  __AUTH_CONST.__cfstring: 0x3020
+  __AUTH_CONST.__cfstring: 0x3160
   __AUTH_CONST.__objc_const: 0x720
   __AUTH_CONST.__objc_intobj: 0x30
   __AUTH.__objc_data: 0x190

   - /usr/lib/libobjc.A.dylib
   Functions: 392
   Symbols:   966
-  CStrings:  1478
+  CStrings:  1488
 
Functions:
~ -[iecsUpdater flash:andErrorResponse:] : 10872 -> 11820
CStrings:
+ "2846.140.4b304"
+ "AstrisArmProbeServer-2846.140.4~304 (GlowG tools)"
+ "Attempting to un-bork firmware... status = 0x%X"
+ "Command set required to update this HW is not available.  Update process is forced to abort."
+ "Failed to write \"MAGIC\" data or send memory modify command. status=0x%02x"
+ "Firmware appears to be within the range known to have a broken update path.  Attempting to fix"
+ "MEMm response: %02X %02X %02X %02X"
+ "Memory modify failed and out of retries.  Aborting as retries were exhausted"
+ "Modifying memory..."
+ "Retrying memory modify command as it looks like it didn't execute..."
+ "Should think SFWu now usable"
+ "useBorkedSFWWorkarounds: %s"
- "2846.140.4b21"
- "AstrisArmProbeServer-2846.140.4~21 (GlowGSeed tools)"
```
