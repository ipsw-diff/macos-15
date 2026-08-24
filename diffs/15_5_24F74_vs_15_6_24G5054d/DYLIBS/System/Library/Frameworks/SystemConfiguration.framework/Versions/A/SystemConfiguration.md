## SystemConfiguration

> `/System/Library/Frameworks/SystemConfiguration.framework/Versions/A/SystemConfiguration`

```diff

-1351.120.3.0.0
-  __TEXT.__text: 0x83714
-  __TEXT.__auth_stubs: 0x2080
+1351.140.5.0.0
+  __TEXT.__text: 0x83670
+  __TEXT.__auth_stubs: 0x2090
   __TEXT.__const: 0x2c0
   __TEXT.__cstring: 0x673c
   __TEXT.__oslogstring: 0x5ea9
   __TEXT.__unwind_info: 0xd68
   __DATA_CONST.__got: 0x190
-  __DATA_CONST.__const: 0x2b00
-  __AUTH_CONST.__auth_got: 0x1040
+  __DATA_CONST.__const: 0x2af0
+  __AUTH_CONST.__auth_got: 0x1048
   __AUTH_CONST.__const: 0xff0
-  __AUTH_CONST.__cfstring: 0x72e0
+  __AUTH_CONST.__cfstring: 0x72c0
   __DATA.__data: 0x4d8
   __DATA.__crash_info: 0x40
   __DATA.__common: 0x8

   - /System/Library/PrivateFrameworks/AppleSystemInfo.framework/Versions/A/AppleSystemInfo
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
-  Functions: 1366
+  Functions: 1365
   Symbols:   2752
   CStrings:  2131
 
Symbols:
+ _IOBSDNameMatching
- __SC_IONetworkInterfaceBSDNameMatching
Functions:
- __SC_IONetworkInterfaceBSDNameMatching
~ _SCNetworkInterfaceCopyMTU : 1484 -> 1492
~ __SCNetworkInterfaceCreateWithEntity : 4560 -> 4572
```
