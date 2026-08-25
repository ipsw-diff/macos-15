## searchpartyd

> `/usr/libexec/searchpartyd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_entry`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__linkguard`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-396.26.4.2.5
-  __TEXT.__text: 0x1290614
+396.26.4.2.8
+  __TEXT.__text: 0x1292678
   __TEXT.__auth_stubs: 0x70e0
   __TEXT.__objc_stubs: 0x40
   __TEXT.__objc_methlist: 0x3c14
-  __TEXT.__const: 0x5d080
-  __TEXT.__oslogstring: 0x3be8d
+  __TEXT.__const: 0x5d0b0
+  __TEXT.__oslogstring: 0x3bfbd
   __TEXT.__objc_classname: 0x51b
   __TEXT.__objc_methname: 0xd9bb
   __TEXT.__objc_methtype: 0x4730
-  __TEXT.__cstring: 0x331cd
-  __TEXT.__swift5_typeref: 0x1edf0
-  __TEXT.__swift5_fieldmd: 0x1ee64
+  __TEXT.__cstring: 0x332cd
+  __TEXT.__swift5_typeref: 0x1edf8
+  __TEXT.__swift5_fieldmd: 0x1ee7c
   __TEXT.__constg_swiftt: 0x1c4f4
   __TEXT.__swift5_builtin: 0x898
   __TEXT.__swift5_reflstr: 0x1cdff

   __TEXT.__swift5_protos: 0x2cc
   __TEXT.__swift5_proto: 0x52f0
   __TEXT.__swift5_types: 0x1ab8
-  __TEXT.__swift_as_entry: 0x219c
+  __TEXT.__swift_as_entry: 0x21a0
   __TEXT.__swift5_capture: 0x190a4
-  __TEXT.__swift_as_ret: 0x452c
+  __TEXT.__swift_as_ret: 0x4530
   __TEXT.__swift5_mpenum: 0x5ec
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__unwind_info: 0x35fa0
-  __TEXT.__eh_frame: 0x9f4f8
+  __TEXT.__unwind_info: 0x35fa8
+  __TEXT.__eh_frame: 0x9f5c0
   __DATA_CONST.__auth_got: 0x3878
-  __DATA_CONST.__got: 0x2d48
-  __DATA_CONST.__auth_ptr: 0x51a0
+  __DATA_CONST.__got: 0x2d50
+  __DATA_CONST.__auth_ptr: 0x50b0
   __DATA_CONST.__const: 0x6b4c0
   __DATA_CONST.__objc_classlist: 0x740
   __DATA_CONST.__objc_catlist: 0x10

   __DATA.__objc_const: 0x17710
   __DATA.__objc_selrefs: 0x2f98
   __DATA.__objc_data: 0x3740
-  __DATA.__data: 0x34af0
+  __DATA.__data: 0x34b00
   __DATA.__bss: 0x9ea60
   __DATA.__common: 0x2630
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 55737
-  Symbols:   3727
-  CStrings:  11251
+  Functions: 55742
+  Symbols:   3728
+  CStrings:  11261
 
Symbols:
+ _$s15FindMyBluetooth11CBDiscoveryC7devices4withSayAA6DeviceVGAC14DiscoveryFlagsV_tYaKFZ
+ _$s15FindMyBluetooth11CBDiscoveryC7devices4withSayAA6DeviceVGAC14DiscoveryFlagsV_tYaKFZTu
- _$s15FindMyBluetooth11CBDiscoveryC7devices4withSayAA6DeviceVGAC14DiscoveryFlagsV_tKFZ
CStrings:
+ "        OwnerSessionProtocol: updateBatteryStatus %hhu for beacon %{private,mask.hash}s."
+ "%s Error getting paired devices %{public}@"
+ "%s Unable to retrieve paired devices %{public}@"
+ "%s Unable to retrieve paired devices: %{public}@"
+ "Could not convert findMyVersion data to VersionNumber [%s]"
+ "Missing BT device for %@"
+ "Not posting low battery notification for unsupported battery type: %{public}s. Beacon %{private,mask.hash}s."
+ "bluetoothDevice(for:)"
+ "forcePairLE(beacon:completion:)"
+ "forcePairLE(serialNumber:beaconGroup:completion:)"
+ "handleUnpair(peripheral:macAddress:)"
+ "pairAirPods(service:peripheral:bluetoothDevice:isRetry:forcePairSNs:)"
- "        OwnerSessionProtocol: updateBatteryStatus %hhufor beacon %{private,mask.hash}s."
- "Could not convert protocolVersion data to VersionNumber [%s]"
```
