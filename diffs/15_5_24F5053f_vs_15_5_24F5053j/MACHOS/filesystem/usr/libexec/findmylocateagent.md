## findmylocateagent

> `/usr/libexec/findmylocateagent`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__linkguard`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-93.25.2.11.12
-  __TEXT.__text: 0x4a5330
-  __TEXT.__auth_stubs: 0x4b90
+93.25.2.11.15
+  __TEXT.__text: 0x4a5f84
+  __TEXT.__auth_stubs: 0x4ba0
   __TEXT.__objc_methlist: 0x99c
   __TEXT.__const: 0x13880
   __TEXT.__cstring: 0xc50b

   __TEXT.__objc_methtype: 0x6fe
   __TEXT.__swift5_protos: 0x50
   __TEXT.__swift5_mpenum: 0x20
-  __TEXT.__oslogstring: 0x135b1
+  __TEXT.__oslogstring: 0x13621
   __TEXT.__swift_as_entry: 0x109c
   __TEXT.__swift_as_ret: 0x1b5c
   __TEXT.__swift5_capture: 0x44c4
   __TEXT.__swift5_entry: 0x8
   __TEXT.__unwind_info: 0x11b88
   __TEXT.__eh_frame: 0x35f18
-  __DATA_CONST.__auth_got: 0x25c8
+  __DATA_CONST.__auth_got: 0x25d0
   __DATA_CONST.__got: 0x1880
-  __DATA_CONST.__auth_ptr: 0x1a20
+  __DATA_CONST.__auth_ptr: 0x1a88
   __DATA_CONST.__const: 0x13fe8
   __DATA_CONST.__objc_classlist: 0x1b0
   __DATA_CONST.__objc_protolist: 0xe0

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 14648
-  Symbols:   2417
-  CStrings:  3046
+  Symbols:   2418
+  CStrings:  3048
 
Symbols:
+ _$s10Foundation4DateV13distantFutureACvgZ
Functions:
~ sub_100288194 : 956 -> 1176
~ sub_100288550 -> sub_10028862c : 2676 -> 4004
~ sub_100289130 -> sub_10028973c : 404 -> 468
~ sub_1002892c4 -> sub_100289910 : 1560 -> 1584
~ sub_1002898dc -> sub_100289f40 : 5024 -> 5780
~ sub_10028ad8c -> sub_10028b6e4 : 4812 -> 5568
~ sub_10028c1c4 -> sub_10028ce10 : 604 -> 612
CStrings:
+ "    Invalid next scheduled date: %{public}s.     FenceID: %{public}s"
+ "Invalid invite timer date: %s"
```
