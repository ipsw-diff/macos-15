## com.apple.driver.AppleBCMWLANCore

> `com.apple.driver.AppleBCMWLANCore`

```diff

-1425.45.0.0.0
+1435.2.0.0.0
   __TEXT.__os_log: 0x74ef
-  __TEXT.__const: 0x2496
-  __TEXT.__cstring: 0x6b944
-  __TEXT_EXEC.__text: 0x22eeb4
+  __TEXT.__const: 0x24b6
+  __TEXT.__cstring: 0x6ba13
+  __TEXT_EXEC.__text: 0x22f4a0
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x492
   __DATA.__common: 0x478
   __DATA.__bss: 0xde8
-  __DATA_CONST.__auth_got: 0xd78
+  __DATA_CONST.__auth_got: 0xd80
   __DATA_CONST.__got: 0x258
   __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__mod_init_func: 0x208

   __DATA_CONST.__const: 0x1e830
   __DATA_CONST.__kalloc_type: 0x4440
   __DATA_CONST.__kalloc_var: 0x230
-  Functions: 4258
-  Symbols:   6849
-  CStrings:  11188
+  Functions: 4259
+  Symbols:   6851
+  CStrings:  11191
 
Symbols:
+ __Z40IO80211CalculateMaxNSSAndVHTMCSForMCSMaptPjS_
+ __ZN21AppleBCMWLANCommander20checkCurrentCmdStuckEP18IO80211TimerSource
+ __ZZN21AppleBCMWLANCommander14initWithConfigEP16AppleBCMWLANCoreP24AppleBCMWLANBusInterfacejE20kalloc_type_view_688
+ __ZZN21AppleBCMWLANCommander4freeEvE21kalloc_type_view_1463
- __ZZN21AppleBCMWLANCommander14initWithConfigEP16AppleBCMWLANCoreP24AppleBCMWLANBusInterfacejE20kalloc_type_view_686
- __ZZN21AppleBCMWLANCommander4freeEvE21kalloc_type_view_1450
Functions:
~ __ZN28AppleBCMWLANSkywalkInterface14enableDatapathEv : 1732 -> 1712
~ __ZN28AppleBCMWLANSkywalkInterface19setCurrentApAddressEP10ether_addr : 1040 -> 1088
~ __ZN28AppleBCMWLANSkywalkInterface13setMacAddressER10ether_addr : 124 -> 260
~ __ZN30AppleBCMWLANProximityInterface21setPEER_CACHE_CONTROLEP29apple80211_peer_cache_control : 3256 -> 3576
~ __ZN21AppleBCMWLANCommander14initWithConfigEP16AppleBCMWLANCoreP24AppleBCMWLANBusInterfacej : 3336 -> 3456
+ __ZN21AppleBCMWLANCommander20checkCurrentCmdStuckEP18IO80211TimerSource
~ __ZN21AppleBCMWLANCommander12issueCommandERK9CommandIDRK16CommandTxPayloadP16CommandRxPayloadRK17CommandRxExpectedRK17CommandCompletion20CommandBusPreference : 6556 -> 6568
~ __ZN21AppleBCMWLANCommander4freeEv : 1056 -> 1180
~ __ZN21AppleBCMWLANCommander7quiesceEv : 1012 -> 1076
~ __ZN21AppleBCMWLANCommander6wakeupEv : 144 -> 212
~ __ZN21AppleBCMWLANCommander5resetEv : 824 -> 888
CStrings:
+ "\"AppleBCMWLANV3_Drivers-1435.2\""
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX15.6.Internal.sdk/System/Library/Frameworks/Kernel.framework/PrivateHeaders/IOKit/apple80211/IO80211Util.h"
+ "11211222111111111122221111111122222111212222212222"
+ "AppleBCMWLANV3_Drivers-1435.2"
+ "Jun 11 2025 21:15:11"
+ "[ik] %s@%d:%s::%s adding HE IE \n"
+ "[ik] %s@%d:cmd is stuck more than diff<%llu> now<%llu> qTime<%llu> \n"
+ "checkCurrentCmdStuck"
- "\"AppleBCMWLANV3_Drivers-1425.45\""
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX15.5.Internal.sdk/System/Library/Frameworks/Kernel.framework/PrivateHeaders/IOKit/apple80211/IO80211Util.h"
- "1121122211111111112222111111122222111212222212222"
- "AppleBCMWLANV3_Drivers-1425.45"
- "Apr 22 2025 19:45:37"
```
