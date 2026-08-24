## com.apple.DriverKit-AppleBCMWLAN

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__osclassinfo`
- `__DATA.__data`

```diff

-1425.45.0.0.0
-  __TEXT.__text: 0x2ad734
-  __TEXT.__auth_stubs: 0x24f0
+1435.2.0.0.0
+  __TEXT.__text: 0x2add98
+  __TEXT.__auth_stubs: 0x2500
   __TEXT.__init_offsets: 0x1c0
-  __TEXT.__cstring: 0x7e27c
-  __TEXT.__const: 0x3d0b0
-  __TEXT.__unwind_info: 0x5db0
+  __TEXT.__cstring: 0x7e3b7
+  __TEXT.__const: 0x3d0c0
+  __TEXT.__unwind_info: 0x5db8
   __TEXT.__eh_frame: 0x38
   __TEXT.__oslogstring: 0x1ea5
-  __DATA_CONST.__auth_got: 0x1278
+  __DATA_CONST.__auth_got: 0x1280
   __DATA_CONST.__got: 0x108
-  __DATA_CONST.__const: 0x20368
+  __DATA_CONST.__const: 0x202e8
   __DATA_CONST.__osclassinfo: 0x390
   __DATA.__data: 0x388
   __DATA.__bss: 0x960

   - /System/DriverKit/System/Library/PrivateFrameworks/IOFileValidation.framework/IOFileValidation
   - /System/DriverKit/System/Library/PrivateFrameworks/OLYHALDriverKit.framework/OLYHALDriverKit
   - /System/DriverKit/usr/lib/libc++.dylib
-  Functions: 13069
+  Functions: 13070
   Symbols:   11458
-  CStrings:  12652
+  CStrings:  12657
 
Symbols:
+ __Z40IO80211CalculateMaxNSSAndVHTMCSForMCSMaptPjS_
+ __ZN21AppleBCMWLANCommander20checkCurrentCmdStuckEP18IO80211TimerSource
+ __ZN40AppleBCMWLANPCIeSkywalkTxSubmissionQueue15validateMacAddrEP29AppleBCMWLANPCIeSkywalkPacketP28AppleBCMWLANSkywalkInterface
- _ZN40AppleBCMWLANPCIeSkywalkTxSubmissionQueue18dequeueInfraPacketEP29AppleBCMWLANPCIeSkywalkPacketb
- __ZN24IOUserNetworkPacketQueue12SetDataQueueEP25IODataQueueDispatchSource
- __ZThn40_N24IOUserNetworkPacketQueue12SetDataQueueEP25IODataQueueDispatchSource
CStrings:
+ "\"AppleBCMWLANV3_driverkit-1435.2\""
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/DriverKit.platform/Developer/SDKs/DriverKit.MacOSX24.6.Internal.sdk/System/DriverKit/System/Library/PrivateFrameworks/IO80211DriverKit.framework/PrivateHeaders/IO80211Util.h"
+ "AppleBCMWLANV3_driverkit-1435.2"
+ "Jun  8 2025 18:54:38"
+ "[dk] %s@%d:%s::%s adding HE IE \n"
+ "[dk] %s@%d:Mac adress mismatch local %02x:%02x:%02x:%02x:%02x:%02x  packet %02x:%02x:%02x:%02x:%02x:%02x \n"
+ "[dk] %s@%d:cmd is stuck more than diff<%llu> now<%llu> qTime<%llu> \n"
+ "checkCurrentCmdStuck"
+ "validateMacAddr"
+ "wlan.validateMacAddrOption"
- "\"AppleBCMWLANV3_driverkit-1425.45\""
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/DriverKit.platform/Developer/SDKs/DriverKit.MacOSX24.5.Internal.sdk/System/DriverKit/System/Library/PrivateFrameworks/IO80211DriverKit.framework/PrivateHeaders/IO80211Util.h"
- "AppleBCMWLANV3_driverkit-1425.45"
- "Apr 18 2025 20:06:20"
- "[dk] %s@%d:Request to attach, while not connected\n"
```
