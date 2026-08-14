## CoreBluetooth

> `/System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`

```diff

-185.4.0.0.0
-  __TEXT.__text: 0x9fd4c
+185.6.1.0.1
+  __TEXT.__text: 0x9ff08
   __TEXT.__auth_stubs: 0x10d0
-  __TEXT.__objc_methlist: 0x8cdc
-  __TEXT.__const: 0x2503
-  __TEXT.__oslogstring: 0x269a
-  __TEXT.__cstring: 0x12457
+  __TEXT.__objc_methlist: 0x8d34
+  __TEXT.__const: 0x250b
+  __TEXT.__oslogstring: 0x2644
+  __TEXT.__cstring: 0x1246f
   __TEXT.__gcc_except_tab: 0x2428
   __TEXT.__ustring: 0x72
-  __TEXT.__unwind_info: 0x1d08
+  __TEXT.__unwind_info: 0x1d20
   __TEXT.__objc_classname: 0x6c3
-  __TEXT.__objc_methname: 0x14be0
-  __TEXT.__objc_methtype: 0x2266
-  __TEXT.__objc_stubs: 0x8e40
+  __TEXT.__objc_methname: 0x14c35
+  __TEXT.__objc_methtype: 0x2285
+  __TEXT.__objc_stubs: 0x8e80
   __DATA_CONST.__got: 0x360
   __DATA_CONST.__const: 0x3b60
   __DATA_CONST.__objc_classlist: 0x1d0
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0xe8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x45d8
+  __DATA_CONST.__objc_selrefs: 0x4600
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x120
   __DATA_CONST.__objc_arraydata: 0x130
   __AUTH_CONST.__auth_got: 0x878
   __AUTH_CONST.__const: 0x1220
-  __AUTH_CONST.__cfstring: 0xaf20
-  __AUTH_CONST.__objc_const: 0x10988
-  __AUTH_CONST.__objc_intobj: 0x8d0
+  __AUTH_CONST.__cfstring: 0xaf40
+  __AUTH_CONST.__objc_const: 0x109a8
+  __AUTH_CONST.__objc_intobj: 0x8e8
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH.__objc_data: 0x1220

   - /System/Library/PrivateFrameworks/TCC.framework/Versions/A/TCC
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3758
-  Symbols:   7083
-  CStrings:  7591
+  Functions: 3765
+  Symbols:   7092
+  CStrings:  7596
 
Symbols:
+ -[CBCentralManager createOfflineLEPairing:synced:ignoreMaxLimit:]
+ -[CBConnection setTempLTK:]
+ -[CBConnection tempLTK]
+ -[CBManager checkBTTCCAuth]
+ -[CBManager checkForTCC]
+ -[CBManager performTCCCheck]
+ -[CBPairingAgent removeGlobalTemporaryLTK]
+ -[CBPairingAgent setGlobalTemporaryLTK:useCase:]
+ -[CBServer setTempLTK:]
+ -[CBServer tempLTK]
+ OBJC_IVAR_$_CBConnection._tempLTK
+ OBJC_IVAR_$_CBServer._tempLTK
+ ___24-[CBManager checkForTCC]_block_invoke
+ _objc_msgSend$checkBTTCCAuth
+ _objc_msgSend$checkForTCC
+ _objc_msgSend$removeGlobalTemporaryLTK
+ _objc_msgSend$setGlobalTemporaryLTK:useCase:
- -[CBCentralManager createOfflineLEPairing:]
- -[CBManager checkForTCCWithDeviceCount]
- -[CBManager performTCCCheck:]
- OBJC_IVAR_$_CBManager.btGlobalTCCCenterLabel
- OBJC_IVAR_$_CBManager.devicesAroundUsDetails
- ___39-[CBManager checkForTCCWithDeviceCount]_block_invoke
- _objc_msgSend$checkForTCCWithDeviceCount
- _objc_msgSend$performTCCCheck:
CStrings:
+ "Maestro"
+ "T@\"NSData\",&,N,V_tempLTK"
+ "TCC available %d, req %d complete %d"
+ "_tempLTK"
+ "authStatus: CBManagerAuthorizationAllowedAlways"
+ "authStatus: CBManagerAuthorizationDenied"
+ "authStatus: CBManagerAuthorizationNotDetermined"
+ "checkBTTCCAuth"
+ "checkForTCC"
+ "createOfflineLEPairing:synced:ignoreMaxLimit:"
+ "kCBGlobalTemporaryLTK"
+ "kCBMsgArgFakeLeDeviceIgnoreMaxLimit"
+ "kCBMsgArgFakeLeDeviceSynced"
+ "performTCCCheck"
+ "removeGlobalTemporaryLTK"
+ "setGlobalTemporaryLTK:useCase:"
+ "setTempLTK:"
+ "tempLTK"
+ "v28@0:8@16I24"
+ "v28@0:8S16B20B24"
- "Received CBMsgIdReadyForTCC"
- "Running performTccCheck CBManager tccAvail %d, tccRequired %d"
- "TCC is already complete"
- "TCC not required"
- "TCC required"
- "authStatus: kTCCAccessPreflightDenied"
- "authStatus: kTCCAccessPreflightGranted"
- "authStatus: kTCCAccessPreflightUnknown"
- "btGlobalTCCCenterLabel"
- "checkForTCCWithDeviceCount"
- "createOfflineLEPairing:"
- "devicesAroundUsDetails"
- "kCBMsgArgTCCLEDevicesAroundDetails"
- "kCBMsgArgTCCLELocalizedCenterLabel"
- "performTCCCheck:"
```
