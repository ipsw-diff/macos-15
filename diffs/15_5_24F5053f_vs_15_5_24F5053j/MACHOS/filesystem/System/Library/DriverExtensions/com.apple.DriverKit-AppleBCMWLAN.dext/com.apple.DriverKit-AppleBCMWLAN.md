## com.apple.DriverKit-AppleBCMWLAN

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__osclassinfo`
- `__DATA.__data`

```diff

-1425.43.0.0.0
-  __TEXT.__text: 0x2ad67c
-  __TEXT.__auth_stubs: 0x24e0
+1425.45.0.0.0
+  __TEXT.__text: 0x2ad734
+  __TEXT.__auth_stubs: 0x24f0
   __TEXT.__init_offsets: 0x1c0
-  __TEXT.__cstring: 0x7e256
+  __TEXT.__cstring: 0x7e27c
   __TEXT.__const: 0x3d0b0
   __TEXT.__unwind_info: 0x5db0
   __TEXT.__eh_frame: 0x38
   __TEXT.__oslogstring: 0x1ea5
-  __DATA_CONST.__auth_got: 0x1270
+  __DATA_CONST.__auth_got: 0x1278
   __DATA_CONST.__got: 0x108
   __DATA_CONST.__const: 0x20368
   __DATA_CONST.__osclassinfo: 0x390

   - /System/DriverKit/System/Library/PrivateFrameworks/IOFileValidation.framework/IOFileValidation
   - /System/DriverKit/System/Library/PrivateFrameworks/OLYHALDriverKit.framework/OLYHALDriverKit
   - /System/DriverKit/usr/lib/libc++.dylib
-  Functions: 13068
-  Symbols:   11457
-  CStrings:  12651
+  Functions: 13069
+  Symbols:   11458
+  CStrings:  12652
 
Symbols:
+ __ZN28AppleOLYHALPortInterfacePCIe10isChipUpDKEPFiP15OSMetaClassBase5IORPCE
Functions:
~ __ZN28AppleBCMWLANBusInterfacePCIe13deferredStartEv : 3212 -> 3256
~ __ZN28AppleBCMWLANBusInterfacePCIe17prepareFRCallbackEPK13CCFaultReport : 872 -> 876
~ __ZN28AppleBCMWLANBusInterfacePCIe13loadChipImageEPK21AppleBCMWLANChipImage : 3496 -> 3504
~ __ZN28AppleBCMWLANBusInterfacePCIe21createFirmwarePCIeIPCEP22AppleBCMWLANChipMemory : 4536 -> 4552
~ __ZNK28AppleBCMWLANBusInterfacePCIe21checkAPBAccessibilityEbb : 452 -> 504
+ _ZNK28AppleBCMWLANBusInterfacePCIe21checkTCMAccessibilityEv.cold.4
CStrings:
+ "\"AppleBCMWLANV3_driverkit-1425.45\""
+ "AppleBCMWLANV3_driverkit-1425.45"
+ "Apr 14 2025 23:28:42"
+ "[dk] %s@%d:Skip APB accessible check\n"
- "\"AppleBCMWLANV3_driverkit-1425.43\""
- "AppleBCMWLANV3_driverkit-1425.43"
- "Apr  3 2025 23:24:34"
```
