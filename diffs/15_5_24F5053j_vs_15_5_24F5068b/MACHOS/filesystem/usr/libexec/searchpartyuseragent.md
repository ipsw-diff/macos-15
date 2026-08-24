## searchpartyuseragent

> `/usr/libexec/searchpartyuseragent`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-396.25.2.11.18
-  __TEXT.__text: 0x11c0cb0
+396.25.2.11.23
+  __TEXT.__text: 0x11c0510
   __TEXT.__auth_stubs: 0x6e80
   __TEXT.__objc_stubs: 0x40
-  __TEXT.__objc_methlist: 0x3774
+  __TEXT.__objc_methlist: 0x376c
   __TEXT.__objc_classname: 0x4cb
   __TEXT.__objc_methname: 0xd497
   __TEXT.__objc_methtype: 0x4593
   __TEXT.__const: 0x54ef0
-  __TEXT.__oslogstring: 0x39c04
-  __TEXT.__cstring: 0x321f3
+  __TEXT.__oslogstring: 0x39d44
+  __TEXT.__cstring: 0x321e3
   __TEXT.__swift5_typeref: 0x1e858
-  __TEXT.__constg_swiftt: 0x1b4a4
+  __TEXT.__constg_swiftt: 0x1b494
   __TEXT.__swift5_reflstr: 0x1c0cb
   __TEXT.__swift5_fieldmd: 0x1e280
   __TEXT.__swift5_builtin: 0x870

   __TEXT.__eh_frame: 0x933b8
   __DATA_CONST.__auth_got: 0x3748
   __DATA_CONST.__got: 0x2c38
-  __DATA_CONST.__auth_ptr: 0x52c0
-  __DATA_CONST.__const: 0x65d08
+  __DATA_CONST.__auth_ptr: 0x5150
+  __DATA_CONST.__const: 0x65cf8
   __DATA_CONST.__objc_classlist: 0x6b8
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x2c8

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 53131
+  Functions: 53130
   Symbols:   3652
-  CStrings:  10946
+  CStrings:  10948
 
CStrings:
+ "Untracked peripheral canSendDataTo!: <CBPeripheral>"
+ "Untracked peripheral didConnect!: <CBPeripheral>"
+ "Untracked peripheral didDisconnectPeripheral!: <CBPeripheral>"
+ "Untracked peripheral didFailToConnect!: <CBPeripheral>"
+ "Untracked peripheral didReceive!: <CBPeripheral>"
+ "Untracked peripheral didSendBytes!: <CBPeripheral>"
+ "[%@] Removing <CBPeripheral> from cache"
+ "[%@] Removing <CBPeripheral> from peripheralCache"
+ "[%@] centralManager didConnect: <CBPeripheral>"
+ "[%@] centralManager didDisconnectPeripheral: <CBPeripheral>"
+ "[%@] centralManager didDiscover: <CBPeripheral> %s"
+ "centralManager canSendDataTo <CBPeripheral>"
+ "centralManager connectionEventDidOccur: %ld for peripheral: <CBPeripheral>"
+ "centralManager didFailToConnect: <CBPeripheral>"
+ "centralManager didReceive %s from <CBPeripheral>"
+ "centralManager didSendBytes %@ to <CBPeripheral> with error"
+ "centralManager didUpdateFindMyPeripherals: <CBPeripheral>"
- "Untracked peripheral canSendDataTo!: %@"
- "Untracked peripheral didConnect!: %@"
- "Untracked peripheral didDisconnectPeripheral!: %@"
- "Untracked peripheral didFailToConnect!: %@"
- "Untracked peripheral didReceive!: %@"
- "Untracked peripheral didSendBytes!: %@"
- "[%@] Removing %@ from cache"
- "[%@] Removing %@ from peripheralCache"
- "[%@] centralManager didDiscover: %@ %s"
- "centralManager canSendDataTo %@"
- "centralManager connectionEventDidOccur: %ld for peripheral: %@"
- "centralManager didFailToConnect: %@"
- "centralManager didReceive %s from %@"
- "centralManager didSendBytes %@ to %@ with error"
- "centralManager didUpdateFindMyPeripherals: %s"
```
