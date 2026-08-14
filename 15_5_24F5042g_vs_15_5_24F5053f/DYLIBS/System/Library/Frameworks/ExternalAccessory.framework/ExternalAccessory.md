## ExternalAccessory

> `/System/Library/Frameworks/ExternalAccessory.framework/ExternalAccessory`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-453.0.0.0.0
-  __TEXT.__text: 0xbc08
+454.0.0.0.0
+  __TEXT.__text: 0xbd40
   __TEXT.__auth_stubs: 0x7e0
   __TEXT.__objc_methlist: 0x12c0
   __TEXT.__cstring: 0x4a97
   __TEXT.__const: 0x70
   __TEXT.__gcc_except_tab: 0x7c
-  __TEXT.__unwind_info: 0x3e0
+  __TEXT.__unwind_info: 0x3d8
   __TEXT.__objc_classname: 0xb6
   __TEXT.__objc_methname: 0x391f
   __TEXT.__objc_methtype: 0x4f0

   __DATA_CONST.__objc_superrefs: 0x40
   __AUTH_CONST.__auth_got: 0x408
   __AUTH_CONST.__const: 0x1e0
-  __AUTH_CONST.__cfstring: 0x2d80
+  __AUTH_CONST.__cfstring: 0x2f80
   __AUTH_CONST.__objc_const: 0x1908
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH.__objc_data: 0x50

   - /usr/lib/libobjc.A.dylib
   Functions: 433
   Symbols:   1363
-  CStrings:  1095
+  CStrings:  1111
 
Functions:
~ -[EAAccessoryManager _notifyObserversThatAccessoryDisconnectedWithUserInfo:] : 156 -> 176
~ -[EAAccessoryManager _externalAccessoryConnected:] : 1240 -> 1256
~ ___50-[EAAccessoryManager _externalAccessoryConnected:]_block_invoke : 460 -> 484
~ ___50-[EAAccessoryManager _externalAccessoryConnected:]_block_invoke_2 : 188 -> 196
~ -[EAAccessoryManager _integrateSequesteredAccessories] : 252 -> 260
~ ___54-[EAAccessoryManager _integrateSequesteredAccessories]_block_invoke : 116 -> 124
~ -[EAInputStream processIncomingAccessoryData:] : 168 -> 188
~ ___46-[EAInputStream processIncomingAccessoryData:]_block_invoke : 164 -> 172
~ -[EAAccessory description] : 420 -> 600
~ -[EAAccessory protocolStrings] : 324 -> 336
~ -[EAAccessory allPublicProtocolStrings] : 544 -> 552
CStrings:
+ "  certData: %lu bytes \n"
+ "  certSerial: %lu bytes \n"
+ "  connected:%@ \n"
+ "  connectionID:%lu \n"
+ "  dockType: %@ \n"
+ "  firmwareRevisionActive: %@ \n"
+ "  firmwareRevisionPending: %@ \n"
+ "  hardwareRevision: %@ \n"
+ "  manufacturer: %@ \n"
+ "  modelNumber: %@ \n"
+ "  name: %@ \n"
+ "  ppid: %@ \n"
+ "  protocols: %@ \n"
+ "  regioncode: %@ \n"
+ "  serialNumber: %@ \n"
+ "%@ { \n"
+ "}"
- "%@ { \n  connected:%@ \n  connectionID:%lu \n  name: %@ \n  manufacturer: %@ \n  modelNumber: %@ \n  serialNumber: %@ \n  ppid: %@ \n  regioncode: %@ \n  firmwareRevisionActive: %@ \n  firmwareRevisionPending: %@ \n  hardwareRevision: %@ \n  dockType: %@ \n  certSerial: %lu bytes \n  certData: %lu bytes \n  protocols: %@ \n  delegate: %@ \n}"
```
