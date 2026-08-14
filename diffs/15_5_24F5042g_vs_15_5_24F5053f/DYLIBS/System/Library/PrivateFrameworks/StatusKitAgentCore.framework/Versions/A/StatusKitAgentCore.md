## StatusKitAgentCore

> `/System/Library/PrivateFrameworks/StatusKitAgentCore.framework/Versions/A/StatusKitAgentCore`

```diff

-80.500.181.0.0
-  __TEXT.__text: 0xc8d88
+80.600.1.0.0
+  __TEXT.__text: 0xc8e7c
   __TEXT.__auth_stubs: 0x15d0
   __TEXT.__objc_methlist: 0x7388
   __TEXT.__const: 0x6a4
   __TEXT.__cstring: 0x2dba
-  __TEXT.__oslogstring: 0x1093d
+  __TEXT.__oslogstring: 0x109ad
   __TEXT.__gcc_except_tab: 0xe34
   __TEXT.__swift5_typeref: 0x9d0
   __TEXT.__swift5_capture: 0x488

   __TEXT.__swift_as_entry: 0x70
   __TEXT.__swift_as_ret: 0x4c
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x21f8
+  __TEXT.__unwind_info: 0x2200
   __TEXT.__eh_frame: 0x12d8
   __TEXT.__objc_classname: 0xe24
   __TEXT.__objc_methname: 0xfee9

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 3597
+  Functions: 3598
   Symbols:   5744
-  CStrings:  3955
+  CStrings:  3956
 
Functions:
~ -[SKAPresenceManager _presentDevicesChangedForChannel:] : 1048 -> 1144
+ -[SKAPresenceManager _presentDevicesChangedForChannel:].cold.4
CStrings:
+ "There is no active subscription or assertion for presenceIdentifier %@, not informing delegate of present device changes"
```
