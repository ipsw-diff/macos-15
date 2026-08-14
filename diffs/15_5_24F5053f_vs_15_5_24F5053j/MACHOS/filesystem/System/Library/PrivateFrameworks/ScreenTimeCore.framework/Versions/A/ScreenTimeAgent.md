## ScreenTimeAgent

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/Versions/A/ScreenTimeAgent`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-537.5.5.0.0
-  __TEXT.__text: 0x26fcb0
+537.5.7.0.0
+  __TEXT.__text: 0x26fe84
   __TEXT.__auth_stubs: 0x2860
-  __TEXT.__objc_stubs: 0x109e0
+  __TEXT.__objc_stubs: 0x10a40
   __TEXT.__objc_methlist: 0x9a60
-  __TEXT.__const: 0x3b80
+  __TEXT.__const: 0x3b90
   __TEXT.__cstring: 0xda0c
-  __TEXT.__oslogstring: 0x1b2db
+  __TEXT.__oslogstring: 0x1b38b
   __TEXT.__gcc_except_tab: 0x21b8
-  __TEXT.__objc_methname: 0x1abf8
+  __TEXT.__objc_methname: 0x1ac5e
   __TEXT.__objc_classname: 0x1f22
   __TEXT.__objc_methtype: 0x510f
   __TEXT.__constg_swiftt: 0x2b8c

   __TEXT.__eh_frame: 0xef70
   __DATA_CONST.__auth_got: 0x1440
   __DATA_CONST.__got: 0x1360
-  __DATA_CONST.__auth_ptr: 0x758
+  __DATA_CONST.__auth_ptr: 0x780
   __DATA_CONST.__const: 0xea78
   __DATA_CONST.__cfstring: 0x4b20
   __DATA_CONST.__objc_classlist: 0x620

   __DATA_CONST.__objc_arrayobj: 0xa8
   __DATA_CONST.__objc_dictobj: 0x78
   __DATA.__objc_const: 0x1cd78
-  __DATA.__objc_selrefs: 0x53c0
+  __DATA.__objc_selrefs: 0x53d8
   __DATA.__objc_ivar: 0x7e8
   __DATA.__objc_data: 0x4340
   __DATA.__data: 0x85a8

   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 7985
   Symbols:   1395
-  CStrings:  7561
+  CStrings:  7566
 
Functions:
~ sub_100038bc8 : 1076 -> 1248
~ sub_10003a15c -> sub_10003a208 : 96 -> 144
~ sub_10003a1bc -> sub_10003a298 : 1488 -> 1620
~ sub_10006398c -> sub_100063aec : 1836 -> 1952
CStrings:
+ "Local device does not support passcode activity"
+ "Received a passcode activity payload without a last passcode use date. Setting the last passcode use date to %{public}@"
+ "Screen Time passcode enabled: %{public}d. Should enable denyHistoryClearing and denyPrivateBrowsing: %{public}d"
+ "handlePasscodePayload:context:nowReference:"
+ "initWithTimeIntervalSinceReferenceDate:"
+ "setLastPasscodeUseDate:"
+ "supportsPasscodeActivity"
- "Failed to fetch local user-device state to post passcode activity user notification: %{public}@"
- "handlePasscodePayload:context:"
```
