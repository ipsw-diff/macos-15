## TimeMachine

> `/System/Library/PrivateFrameworks/TimeMachine.framework/Versions/A/TimeMachine`

```diff

-2432.0.0.0.0
-  __TEXT.__text: 0xd8b4c
+2433.0.0.0.0
+  __TEXT.__text: 0xd8ca4
   __TEXT.__auth_stubs: 0x26a0
   __TEXT.__objc_methlist: 0x5810
   __TEXT.__const: 0x27c4
-  __TEXT.__cstring: 0xb5dc
+  __TEXT.__cstring: 0xb66c
   __TEXT.__gcc_except_tab: 0x1e8c
   __TEXT.__dlopen_cstrs: 0xb0
   __TEXT.__ustring: 0x4

   __DATA_CONST.__objc_selrefs: 0x3250
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x220
-  __DATA_CONST.__objc_arraydata: 0xd8
+  __DATA_CONST.__objc_arraydata: 0x108
   __AUTH_CONST.__auth_got: 0x1368
   __AUTH_CONST.__const: 0x5470
-  __AUTH_CONST.__cfstring: 0x7f80
+  __AUTH_CONST.__cfstring: 0x7fa0
   __AUTH_CONST.__objc_const: 0x8958
-  __AUTH_CONST.__objc_intobj: 0x1f8
-  __AUTH_CONST.__objc_arrayobj: 0x60
+  __AUTH_CONST.__objc_intobj: 0x270
+  __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH.__objc_data: 0x15f8
   __AUTH.__data: 0x388

   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 3884
   Symbols:   5752
-  CStrings:  3870
+  CStrings:  3871
 
Functions:
~ -[TMDisk(NetworkOperations) configureReconnectTimeoutsDisablePrimaryReconnect:disableNetworkQoS:] : 1156 -> 1500
CStrings:
+ "Current network volume options for '%@' are {disablePrimaryReconnect: %d, disableSecondaryReconnect: %d, reconnectTimeOut: %d, QoS: 0x%X, attributes: 0x%X}"
+ "Fsctl reported error while setting network volume options for '%@', error: %d %s"
+ "Initial network volume options for '%@' are {disablePrimaryReconnect: %d, disableSecondaryReconnect: %d, reconnectTimeOut: %d, QoS: 0x%X, attributes: 0x%X}"
+ "Setting network volume options for '%@' to {disablePrimaryReconnect: %d, disableSecondaryReconnect: %d, reconnectTimeOut: %d, QoS: 0x%X, attributes: 0x%X}"
- "Configured network volume options for '%@' {disablePrimaryReconnect: %d, disableSecondaryReconnect: %d, reconnectTimeOut: %d, QoS: 0x%X, attributes: 0x%X}"
- "Fsctl reported error while configuring network volume options for '%@', error: %d %s"
- "Initial network volume options for '%@' {disablePrimaryReconnect: %d, disableSecondaryReconnect: %d, reconnectTimeOut: %d, QoS: 0x%X, attributes: 0x%X}"
```
