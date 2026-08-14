## LocationSupport

> `/System/Library/PrivateFrameworks/LocationSupport.framework/Versions/A/LocationSupport`

```diff

-2960.0.61.0.0
-  __TEXT.__text: 0x26364
+2964.0.3.0.0
+  __TEXT.__text: 0x2661c
   __TEXT.__auth_stubs: 0xdc0
   __TEXT.__objc_methlist: 0x1764
   __TEXT.__const: 0x28d
-  __TEXT.__cstring: 0x1e47
+  __TEXT.__cstring: 0x1e4f
   __TEXT.__gcc_except_tab: 0x167c
-  __TEXT.__oslogstring: 0x633a
-  __TEXT.__unwind_info: 0xc58
+  __TEXT.__oslogstring: 0x6508
+  __TEXT.__unwind_info: 0xc50
   __TEXT.__objc_classname: 0x412
   __TEXT.__objc_methname: 0x2a21
   __TEXT.__objc_methtype: 0x858

   - /usr/lib/libobjc.A.dylib
   Functions: 763
   Symbols:   465
-  CStrings:  1192
+  CStrings:  1197
 
Functions:
~ sub_1929754c4 -> sub_1921b44c4 : 1668 -> 1664
~ sub_192975b48 -> sub_1921b4b44 : 652 -> 1348
~ _CLLogEncryptData : 1752 -> 1756
CStrings:
+ "#LogEncryption Can't create the new encryption key dir"
+ "#LogEncryption Can't persist the new log encryption key"
+ "%04d_%03d"
+ "CLLogKeyStorePath == nullptr && __c11_atomic_compare_exchange_strong(&CLLogAtomicKeyUpdateInProgress, &expected, true, 5, 5) && __c11_atomic_load(&CLLogAtomicKeyCreationTime, 5) == 0"
+ "{\"msg%{public}.0s\":\"#LogEncryption Can't create the new encryption key dir\", \"directory\":%{public, location:escape_only}s, \"error\":%{public, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#LogEncryption Can't persist the new log encryption key\", \"fileName\":%{public, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#LogEncryption New log encryption key created\", \"fileName\":%{public, location:escape_only}s}"
- "#LogEncryption New log encryption key created: %@"
- "CLLogKeyStorePath == nullptr && __c11_atomic_compare_exchange_strong(&CLLogAtomicKeyUpdateInProgress, &expected, true, 5, 5) && __c11_atomic_load(&CLLogAtomicKeyExpirationTime, 5) == 0"
```
