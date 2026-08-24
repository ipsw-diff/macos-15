## searchpartyd

> `/usr/libexec/searchpartyd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-396.25.2.11.18
-  __TEXT.__text: 0x128e6f4
+396.25.2.11.23
+  __TEXT.__text: 0x128df54
   __TEXT.__auth_stubs: 0x70a0
   __TEXT.__objc_stubs: 0x40
-  __TEXT.__objc_methlist: 0x3c8c
+  __TEXT.__objc_methlist: 0x3c84
   __TEXT.__const: 0x57700
-  __TEXT.__oslogstring: 0x3b5dd
+  __TEXT.__oslogstring: 0x3b71d
   __TEXT.__objc_classname: 0x51b
   __TEXT.__objc_methname: 0xdae0
   __TEXT.__objc_methtype: 0x474c
-  __TEXT.__cstring: 0x33eed
+  __TEXT.__cstring: 0x33edd
   __TEXT.__swift5_typeref: 0x1f0f2
   __TEXT.__swift5_fieldmd: 0x1f1e0
-  __TEXT.__constg_swiftt: 0x1c9b4
+  __TEXT.__constg_swiftt: 0x1c9a4
   __TEXT.__swift5_builtin: 0x898
   __TEXT.__swift5_reflstr: 0x1d1cf
   __TEXT.__swift5_assocty: 0x25c0

   __TEXT.__eh_frame: 0x9ed18
   __DATA_CONST.__auth_got: 0x3858
   __DATA_CONST.__got: 0x2d20
-  __DATA_CONST.__auth_ptr: 0x5338
-  __DATA_CONST.__const: 0x68158
+  __DATA_CONST.__auth_ptr: 0x4288
+  __DATA_CONST.__const: 0x68148
   __DATA_CONST.__objc_classlist: 0x758
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x2f8

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 55559
+  Functions: 55558
   Symbols:   3713
-  CStrings:  11305
+  CStrings:  11307
 
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
