## bluetoothd

> `/usr/sbin/bluetoothd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-185.4.0.0.0
-  __TEXT.__text: 0x7ab3ac
+185.6.1.0.1
+  __TEXT.__text: 0x7ac970
   __TEXT.__auth_stubs: 0x4000
   __TEXT.__objc_stubs: 0x102c0
   __TEXT.__init_offsets: 0x54
   __TEXT.__objc_methlist: 0x5a3c
-  __TEXT.__gcc_except_tab: 0x5d974
+  __TEXT.__gcc_except_tab: 0x5da44
   __TEXT.__const: 0x7ecc
-  __TEXT.__cstring: 0x9fa95
-  __TEXT.__oslogstring: 0xa3894
+  __TEXT.__cstring: 0x9fe29
+  __TEXT.__oslogstring: 0xa3b6d
   __TEXT.__objc_methname: 0x13128
   __TEXT.__objc_classname: 0x60a
   __TEXT.__objc_methtype: 0x3d66
   __TEXT.__ustring: 0x2c
-  __TEXT.__unwind_info: 0x1e9a0
+  __TEXT.__unwind_info: 0x1e9d0
   __TEXT.__eh_frame: 0xc0
   __DATA_CONST.__auth_got: 0x2018
   __DATA_CONST.__got: 0x800
   __DATA_CONST.__auth_ptr: 0x190
-  __DATA_CONST.__const: 0x2ab38
-  __DATA_CONST.__cfstring: 0x1d900
+  __DATA_CONST.__const: 0x2abd0
+  __DATA_CONST.__cfstring: 0x1daa0
   __DATA_CONST.__objc_classlist: 0x1c0
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x68

   __DATA.__objc_data: 0x1180
   __DATA.__data: 0x4328
   __DATA.__crash_info: 0x40
-  __DATA.__bss: 0x1e9d2
+  __DATA.__bss: 0x1ea12
   __DATA.__common: 0x64e8
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts
   - /System/Library/Frameworks/CoreAudio.framework/Versions/A/CoreAudio

   - /usr/lib/libiconv.2.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 29855
+  Functions: 29871
   Symbols:   1299
-  CStrings:  34238
+  CStrings:  34278
 
CStrings:
+ "20:50:46"
+ "Apr 10 2025"
+ "CBClassicMsgIdAppTCCCheckComplete"
+ "CBClassicMsgIdCheckAppTCC"
+ "CBClassicMsgIdPairingAgentRemoveGlobalLTK"
+ "CBClassicMsgIdPairingAgentSetGlobalLTK"
+ "CBLePipeMsgIdAppTCCCheckComplete"
+ "CBLePipeMsgIdCheckAppTCC"
+ "CBMsgIdAppTCCCheckComplete"
+ "CBMsgIdCheckAppTCC"
+ "CBMsgIdPairingAgentRemoveGlobalLTK"
+ "CBMsgIdPairingAgentSetGlobalLTK"
+ "ChipBootFailureChipBootFailureOperationNotSupported"
+ "ChipBootFailureDeviceFatalError"
+ "ChipBootFailureInvalidExtension"
+ "ChipBootFailureInvalidFilePointer"
+ "ChipBootFailureInvalidFileSize"
+ "ChipBootFailureUnableToAllocateMemory"
+ "ChipBootFailureUnableToFLR"
+ "ChipBootFailureUnableToFindService"
+ "ChipBootFailureUnableToOpenFile"
+ "ChipBootFailureUnableToReadFile"
+ "ChipBootFailureUnableToSendFWImage"
+ "Clearing default LTK security keys"
+ "Failed to configureRSSIIntentforAOP for handle:0x%02X - device not yet added"
+ "Found %lu paired LE device%{public}s in synced keychain, total paired LE devices %lu"
+ "Invalid Handle, allow %d"
+ "LPMSU params not set"
+ "NSDictionary<NSUUID *,NSNumber *> *BT::_BTKCGetAllLEAddressesAndUuidsFromService(CFStringRef, bool, int, BTAddress)"
+ "OverrideMaxLESyncedDevices"
+ "Session \"%{public}s\" is asking to clear LTK"
+ "Session \"%{public}s\" is asking to set LTK size %d useCase %s result %d"
+ "Setting default LTK security keys (lengh:%d)"
+ "TCC Done session:%s fDeviceAccessForMediaSession:%d fDeviceAccessForMediaExtension:%d fDeviceAccessPerAccessorySession:%d fDeviceAccessPerAccessoryExtension:%d sessionType:%d"
+ "Warning: Setting default LTK security keys twice"
+ "We can have up to %d paired devices, %d synced LE devices"
+ "deviceIdLength invalid: %d"
+ "findResponseByHCIHandle response is NULL, lmHandle invalid"
+ "findResponseByHCIHandle session is NULL, lmHandle invalid"
+ "init cloud - found %lu paired LE device%{public}s in local keychain"
+ "kCBGlobalTemporaryLTK"
+ "kCBMsgArgFakeLeDeviceIgnoreMaxLimit"
+ "kCBMsgArgFakeLeDeviceSynced"
+ "lpmFlag1 or lpmFlag2 not supported for this platform."
+ "prkLength invalid: %d"
+ "statedump: Default Temporary LTK:"
+ "statedump: Usecase %lld, TemporaryLTK %{private}.16P"
+ "using default temporary keys for device \"%{public}@\", keyLen %d"
+ "vseLpmDebugDeviceIdEvent - DeviceId: %@, prk: %@, timestamp: 0x%08X"
- "22:49:06"
- "Found %lu paired LE device%{public}s in local keychain, loaded %lu"
- "Invalid Handle"
- "Mar 26 2025"
- "NSDictionary<NSUUID *,NSNumber *> *BT::_BTKCGetAllLEAddressesAndUuidsFromService(CFStringRef, bool, BTAddress)"
- "We can have up to %d paired devices"
- "handleTCCDone fDeviceAccessForMediaSession:%d fDeviceAccessForMediaExtension:%d fDeviceAccessPerAccessorySession:%d fDeviceAccessPerAccessoryExtension:%d sessionType:%d"
- "kCBMsgArgTCCLEDevicesAroundDetails"
- "kCBMsgArgTCCLELocalizedCenterLabel"
```
