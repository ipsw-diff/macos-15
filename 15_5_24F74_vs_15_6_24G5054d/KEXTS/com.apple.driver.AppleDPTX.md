## com.apple.driver.AppleDPTX

> `com.apple.driver.AppleDPTX`

```diff

-360.100.14.0.0
-  __TEXT.__cstring: 0x4fb8
-  __TEXT.__os_log: 0x65b6
+360.140.2.0.0
+  __TEXT.__cstring: 0x4fe1
+  __TEXT.__os_log: 0x65b7
   __TEXT.__const: 0x170
-  __TEXT_EXEC.__text: 0x3a950
+  __TEXT_EXEC.__text: 0x3a988
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x248
   __DATA.__common: 0x1f0

   __DATA_CONST.__kalloc_type: 0x300
   Functions: 1224
   Symbols:   2130
-  CStrings:  1010
+  CStrings:  1012
 
Functions:
~ __ZN24AppleDPTXHDCP2Controller16protectLinkGatedEP10IODPDevice : 624 -> 628
~ __ZN19AppleDPTXController23addDeviceCompletedGatedEP10IODPDevicebPv : 176 -> 228
CStrings:
+ "IOAV[%d] %s<0x%llx>::%s: signaling _port->inactiveSinkDetected()\n"
+ "signaling _port->inactiveSinkDetected()\n"
```
