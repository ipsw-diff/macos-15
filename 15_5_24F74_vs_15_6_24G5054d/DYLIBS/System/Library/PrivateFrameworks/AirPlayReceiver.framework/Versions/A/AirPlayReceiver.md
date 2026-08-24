## AirPlayReceiver

> `/System/Library/PrivateFrameworks/AirPlayReceiver.framework/Versions/A/AirPlayReceiver`

```diff

-860.7.1.0.0
-  __TEXT.__text: 0xd2d80
+870.8.1.0.0
+  __TEXT.__text: 0xd2c48
   __TEXT.__auth_stubs: 0x3370
   __TEXT.__objc_methlist: 0x8e4
   __TEXT.__const: 0xd2c5
   __TEXT.__dlopen_cstrs: 0xad
   __TEXT.__gcc_except_tab: 0x710
-  __TEXT.__cstring: 0x275d3
-  __TEXT.__unwind_info: 0x1088
+  __TEXT.__cstring: 0x275af
+  __TEXT.__unwind_info: 0x1080
   __TEXT.__objc_classname: 0x12c
   __TEXT.__objc_methname: 0x1e06
   __TEXT.__objc_methtype: 0x1482

   - /System/Library/PrivateFrameworks/WiFiPeerToPeer.framework/Versions/A/WiFiPeerToPeer
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1265
-  Symbols:   3191
-  CStrings:  4606
+  Functions: 1264
+  Symbols:   3190
+  CStrings:  4605
 
Symbols:
+ GCC_except_table1007
+ GCC_except_table1009
+ GCC_except_table474
+ GCC_except_table478
+ GCC_except_table485
+ GCC_except_table493
+ GCC_except_table873
+ GCC_except_table892
+ GCC_except_table943
+ GCC_except_table947
+ GCC_except_table999
+ _APSCopyPairingIdentity
- GCC_except_table1000
- GCC_except_table1008
- GCC_except_table1010
- GCC_except_table475
- GCC_except_table479
- GCC_except_table486
- GCC_except_table494
- GCC_except_table874
- GCC_except_table893
- GCC_except_table944
- GCC_except_table948
- _PairingSessionCopyIdentity
- _sysInfo_copyPairingIdentity
Functions:
~ _audioSession_performPeriodicTasks : 3840 -> 3828
~ _APReceiverAudioSessionRealTimeLogEnded : 6564 -> 6552
- _sysInfo_copyPairingIdentity
~ _AirPlayReceiverServerCreate : 9200 -> 9196
CStrings:
+ "870.8.1"
+ "Failed to get public AirPlay pairing identity: %#m\n"
+ "Failed to get public system pairing identity: %#m\n"
- "### Failed to get public AirPlay pairing identity: %#m\n"
- "### Failed to get public system pairing identity: %#m\n"
- "860.7.1"
- "sysInfo_copyPairingIdentity"
```
