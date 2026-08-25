## deviceinterfaced

> `/System/Library/Templates/Data/Library/Apple/System/Library/PrivateFrameworks/DeviceInterface.framework/Support/deviceinterfaced`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`

```diff

-208.140.8.0.0
-  __TEXT.__text: 0x81c0
+208.140.9.0.0
+  __TEXT.__text: 0x8270
   __TEXT.__auth_stubs: 0x480
   __TEXT.__objc_stubs: 0x460
   __TEXT.__objc_methlist: 0x320
-  __TEXT.__cstring: 0x3de6
+  __TEXT.__cstring: 0x3e58
   __TEXT.__objc_classname: 0x1a
-  __TEXT.__objc_methname: 0x1666
+  __TEXT.__objc_methname: 0x1672
   __TEXT.__objc_methtype: 0x65c
   __TEXT.__unwind_info: 0xa8
   __TEXT.__eh_frame: 0xb4

   - /usr/lib/libobjc.A.dylib
   Functions: 121
   Symbols:   91
-  CStrings:  444
+  CStrings:  446
 
Functions:
~ sub_100002df8 : 1188 -> 1320
~ sub_100006fb8 -> sub_10000703c : 3032 -> 3076
CStrings:
+ "%s *rsmInterfaceListener = rsm_interface_listener_kis_create_with_manager(self.kisInterfaceManager, deviceQueue);"
+ "%s device_interface_listener_register_callbacks(self.rsmInterfaceListener, &rsmListenerInterfaceCallbacks);"
+ "%s device_interface_manager_t *rsmInterfaceManager = device_interface_manager_create(managerQueue);"
+ "%s managerQueue %@ deviceQueue %@"
+ "-[DeviceInterfaceArbitrator setUpRSMInterface:deviceQueue:]"
+ "setUpRSMInterface:deviceQueue:"
+ "setUpRSMInterface_device_deviceinterfaced_queue"
+ "setUpRSMInterface_manager_deviceinterfaced_queue"
- "%s *rsmInterfaceListener = kis_interface_listener_debug_usb_create_with_manager(self.debugUSBInterfaceManager, self.debugUSBDeviceManager);"
- "%s device_interface_manager_t *rsmInterfaceManager = device_interface_manager_create(queue);"
- "%s rsm_interface_listener_kis_create_with_manager(self.kisInterfaceManager);"
- "-[DeviceInterfaceArbitrator setUpRSMInterface:]"
- "setUpRSMInterface:"
- "setUpRSMInterface_deviceinterfaced_queue"
```
