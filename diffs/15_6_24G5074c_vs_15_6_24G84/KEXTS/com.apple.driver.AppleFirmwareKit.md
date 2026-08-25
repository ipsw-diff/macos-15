## com.apple.driver.AppleFirmwareKit

> `com.apple.driver.AppleFirmwareKit`

```diff

-531.120.3.0.0
+531.141.2.0.0
   __TEXT.__cstring: 0x3682
   __TEXT.__os_log: 0xce2
   __TEXT.__const: 0xa8
-  __TEXT_EXEC.__text: 0x32580
+  __TEXT_EXEC.__text: 0x32544
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x4b8
   __DATA.__common: 0x548

   __DATA_CONST.__mod_term_func: 0xb8
   __DATA_CONST.__const: 0xfa90
   __DATA_CONST.__kalloc_type: 0x15c0
-  Functions: 1665
-  Symbols:   2455
+  Functions: 1667
+  Symbols:   2457
   CStrings:  533
 
Symbols:
+ _ZN16AFKEPInterfaceV211sendMessageEPKN5AFKEP7MessageEmP14AFKEPInterfacePK16AFKEPSendOptions
+ __ZN16AFKEPInterfaceV211sendMessageEPKN5AFKEP7MessageEmP14AFKEPInterfacePK16AFKEPSendOptions
Functions:
+ __ZN16AFKEPInterfaceV211sendMessageEPKN5AFKEP7MessageEmP14AFKEPInterfacePK16AFKEPSendOptions
~ __ZN16AFKEPInterfaceV215enqueueResponseEPviyPN5AFKEP7MessageEmPK16AFKEPSendOptions : 620 -> 512
~ __ZN16AFKEPInterfaceV213enqueueReportEhyPN5AFKEP7MessageEmPK16AFKEPSendOptions : 524 -> 456
~ __ZN16AFKEPInterfaceV214enqueueCommandEPvhyPN5AFKEP7MessageEmS0_jPK16AFKEPSendOptions : 692 -> 572
+ _ZN16AFKEPInterfaceV213handleUnknownEP23AFKEPInterfaceServiceV2PKN5AFKEP11MessageInfoEPKNS2_7MessageEm.cold.3
```
