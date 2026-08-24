## appleaccountd

> `/usr/libexec/appleaccountd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`

```diff

-1007.476.0.0.0
-  __TEXT.__text: 0x325930
+1007.477.0.0.0
+  __TEXT.__text: 0x327f6c
   __TEXT.__auth_stubs: 0x25d0
   __TEXT.__objc_methlist: 0xe08
-  __TEXT.__cstring: 0x8383
+  __TEXT.__cstring: 0x8393
   __TEXT.__objc_methname: 0x44c2
-  __TEXT.__swift5_typeref: 0x5f8c
+  __TEXT.__swift5_typeref: 0x5f8a
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__const: 0xc5d8
-  __TEXT.__constg_swiftt: 0xa32c
-  __TEXT.__swift5_reflstr: 0x5307
-  __TEXT.__swift5_fieldmd: 0x51d8
+  __TEXT.__const: 0xc768
+  __TEXT.__constg_swiftt: 0xa3b8
+  __TEXT.__swift5_reflstr: 0x5347
+  __TEXT.__swift5_fieldmd: 0x5284
   __TEXT.__swift5_builtin: 0x1e0
-  __TEXT.__swift5_assocty: 0x698
-  __TEXT.__swift5_proto: 0x990
-  __TEXT.__swift5_types: 0x4d4
+  __TEXT.__swift5_assocty: 0x6b0
+  __TEXT.__swift5_proto: 0x9a4
+  __TEXT.__swift5_types: 0x4d8
   __TEXT.__objc_classname: 0x216
   __TEXT.__objc_methtype: 0x1587
-  __TEXT.__swift5_capture: 0x57c4
-  __TEXT.__oslogstring: 0x190a3
+  __TEXT.__swift5_capture: 0x57c0
+  __TEXT.__oslogstring: 0x195f3
   __TEXT.__swift5_protos: 0x1d0
   __TEXT.__swift_as_entry: 0x254
   __TEXT.__swift_as_ret: 0x2e0
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x5d58
-  __TEXT.__eh_frame: 0x95b8
+  __TEXT.__unwind_info: 0x5d98
+  __TEXT.__eh_frame: 0x97a0
   __DATA_CONST.__auth_got: 0x12e8
   __DATA_CONST.__got: 0xea8
-  __DATA_CONST.__auth_ptr: 0x1f98
-  __DATA_CONST.__const: 0x10b70
+  __DATA_CONST.__auth_ptr: 0x1818
+  __DATA_CONST.__const: 0x10bd8
   __DATA_CONST.__objc_classlist: 0x4d0
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x170
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0xb8
-  __DATA.__objc_const: 0x18418
+  __DATA.__objc_const: 0x184b8
   __DATA.__objc_selrefs: 0x1418
   __DATA.__objc_data: 0x2980
-  __DATA.__data: 0x107f8
+  __DATA.__data: 0x108b8
   __DATA.__objc_stublist: 0x68
-  __DATA.__bss: 0xea00
-  __DATA.__common: 0x3c0
+  __DATA.__bss: 0xec80
+  __DATA.__common: 0x3e8
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 8200
+  Functions: 8215
   Symbols:   1255
-  CStrings:  3428
+  CStrings:  3444
 
CStrings:
+ "CustodianRecord found on the local disk, after fetching from cloud"
+ "CustodianRecord found on the local disk, no need to fetch from cloud"
+ "CustodianRecord not found on the local disk, Fetching the record from cloud"
+ "CustodianRecoveryInfoRecord found on the local disk, after fetching from cloud"
+ "CustodianRecoveryInfoRecord found on the local disk, no need to fetch from cloud"
+ "CustodianRecoveryInfoRecord not found on the local disk, fetching the record from cloud"
+ "CustodianshipInfoRecord found on the local disk, after fetching from cloud"
+ "CustodianshipInfoRecord found on the local disk, no need to fetch from cloud"
+ "CustodianshipInfoRecord not found on the local disk, Fetching the record from cloud"
+ "Error fetching CustodianRecord from the local disk, after fetching from cloud: %@"
+ "Error fetching CustodianRecoveryInfoRecord from the local disk, after fetching from cloud: %@"
+ "Error fetching CustodianshipInfoRecord from the local disk, after fetching from cloud: %@"
+ "Error occured fetching CustodianRecoveryInfoRecord from local disk %@"
+ "Fetching CustodianRecord from local disk"
+ "Fetching CustodianRecord from local disk after fetching from cloud"
+ "Fetching CustodianRecoveryInfoRecord from local disk"
+ "Fetching CustodianRecoveryInfoRecord from local disk after fetching from cloud"
+ "Fetching CustodianshipInfoRecord from local disk"
+ "Fetching CustodianshipInfoRecord from local disk after fetching from cloud"
+ "contextType"
+ "flow"
+ "process(_:originalStatus:postCFU:telemetryFlowID:flow:)"
+ "🚨 CustodianRecord still not found on the local disk, even after fetching from cloud"
+ "🚨 CustodianRecoveryInfoRecord not found on the local disk, even after fetching from cloud"
+ "🚨 CustodianshipInfoRecord found on the local disk, even after fetching from cloud"
- "Custodian record not found. Fetching the record from cloud."
- "CustodianshipInfo record not found. Fetching the record from cloud."
- "Error fetching recovery info from cloud %@"
- "Fetching custodian record from local disk"
- "Fetching custodian record from local disk after cloud pull"
- "Fetching custodianinfo record from local disk"
- "Fetching custodianinfo record from local disk after cloud pull"
- "Recovery Info record not found. Fetching the record from cloud."
- "process(_:originalStatus:postCFU:telemetryFlowID:)"
```
