## DeviceInterface

> `/System/Library/Templates/Data/Library/Apple/System/Library/PrivateFrameworks/DeviceInterface.framework/Versions/A/DeviceInterface`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH.__objc_data`
- `__DATA.__data`

```diff

-208.120.5.0.0
-  __TEXT.__text: 0x85abc
+208.120.7.0.0
+  __TEXT.__text: 0x86fa8
   __TEXT.__auth_stubs: 0x640
-  __TEXT.__objc_methlist: 0x5b6c
+  __TEXT.__objc_methlist: 0x5c3c
   __TEXT.__const: 0x64
+  __TEXT.__oslogstring: 0x4003
   __TEXT.__cstring: 0x4821
   __TEXT.__gcc_except_tab: 0x8a4
-  __TEXT.__oslogstring: 0x3e95
-  __TEXT.__unwind_info: 0x1380
-  __TEXT.__objc_classname: 0xd4b
-  __TEXT.__objc_methname: 0xd38e
-  __TEXT.__objc_methtype: 0x642f
+  __TEXT.__unwind_info: 0x1388
+  __TEXT.__objc_classname: 0xd4a
+  __TEXT.__objc_methname: 0xd55f
+  __TEXT.__objc_methtype: 0x696b
   __TEXT.__objc_stubs: 0x62e0
   __DATA_CONST.__got: 0x240
   __DATA_CONST.__const: 0x60

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2260
+  __DATA_CONST.__objc_selrefs: 0x2270
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x2d0
   __AUTH_CONST.__auth_got: 0x330
   __AUTH_CONST.__const: 0x7c0
   __AUTH_CONST.__cfstring: 0x620
-  __AUTH_CONST.__objc_const: 0xc3c0
+  __AUTH_CONST.__objc_const: 0xc4b0
   __AUTH_CONST.__objc_intobj: 0x120
   __AUTH.__objc_data: 0x1cc0
-  __AUTH.__data: 0x4a8
-  __DATA.__objc_ivar: 0xa64
+  __AUTH.__data: 0x4f0
+  __DATA.__objc_ivar: 0xa78
   __DATA.__data: 0x4b0
   __DATA.__bss: 0xa0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpcap.A.dylib
-  Functions: 2487
-  Symbols:   4915
-  CStrings:  3221
+  Functions: 2518
+  Symbols:   4954
+  CStrings:  3232
 
Symbols:
+ -[DebugUSBInterfaceIOUSBHost active]
+ -[DebugUSBInterfaceIOUSBHost statusLock]
+ -[DockChannelProbeListenerProbeState stopListeningForTermination]
+ -[DockChannelSystemServiceClientWrapper initWithService:description:]
+ -[DockChannelSystemServiceClientWrapper registerCallbacks:]
+ -[DockChannelSystemServiceClientWrapper startListening]
+ -[DockChannelSystemServiceClientWrapper stopListening]
+ -[DockChannelSystemServiceIOService createClientWithDescription:]
+ -[DockChannelSystemServiceUSBDeviceClientWrapper initWithService:description:]
+ -[DockChannelSystemServiceUSBDeviceIOUSBHost initWithService:serviceID:description:queue:]
+ -[DockChannelSystemServiceUSBDeviceIOUSBHost notificationsActive]
+ -[DockChannelSystemServiceUSBDeviceIOUSBHost registerCallbacks:]
+ -[DockChannelSystemServiceUSBDeviceIOUSBHost startListening]
+ -[DockChannelSystemServiceUSBDeviceIOUSBHost stopListening]
+ -[DockChannelSystemServiceUSBHostPortClientWrapper initWithService:description:]
+ -[DockChannelSystemServiceUSBHostPortIOUSBHost initWithService:serviceID:description:queue:]
+ -[DockChannelSystemServiceUSBHostPortIOUSBHost notificationsActive]
+ -[DockChannelSystemServiceUSBHostPortIOUSBHost registerCallbacks:]
+ -[DockChannelSystemServiceUSBHostPortIOUSBHost startListening]
+ -[DockChannelSystemServiceUSBHostPortIOUSBHost stopListening]
+ -[DockChannelSystemServiceUSBHubPortClientWrapper initWithService:description:]
+ -[DockChannelSystemServiceUSBHubPortIOUSBHost initWithService:serviceID:description:queue:]
+ -[DockChannelSystemServiceUSBHubPortIOUSBHost notificationsActive]
+ -[DockChannelSystemServiceUSBHubPortIOUSBHost registerCallbacks:]
+ -[DockChannelSystemServiceUSBHubPortIOUSBHost startListening]
+ -[DockChannelSystemServiceUSBHubPortIOUSBHost stopListening]
+ -[DockChannelSystemServiceWrapper createClientWithDescription:]
+ -[DockChannelSystemServiceWrapper createUSBDeviceClientWithDescription:]
+ -[DockChannelSystemServiceWrapper createUSBHostPortClientWithDescription:]
+ -[DockChannelSystemServiceWrapper createUSBHubPortClientWithDescription:]
+ OBJC_IVAR_$_DebugUSBInterfaceIOUSBHost._active
+ OBJC_IVAR_$_DebugUSBInterfaceIOUSBHost._statusLock
+ OBJC_IVAR_$_DockChannelSystemServiceUSBDeviceIOUSBHost._notificationsActive
+ OBJC_IVAR_$_DockChannelSystemServiceUSBHostPortIOUSBHost._notificationsActive
+ OBJC_IVAR_$_DockChannelSystemServiceUSBHubPortIOUSBHost._notificationsActive
+ ___36-[RSMInterfaceKIS processDoorbells:]_block_invoke
+ ___59-[DockChannelSystemServiceUSBDeviceIOUSBHost stopListening]_block_invoke
+ ___60-[DockChannelSystemServiceUSBHubPortIOUSBHost stopListening]_block_invoke
+ ___61-[DockChannelSystemServiceUSBHostPortIOUSBHost stopListening]_block_invoke
+ ___os_log_helper_16_2_3_8_0_8_32_4_0
+ _dock_channel_system_service_client_register_callbacks
+ _dock_channel_system_service_client_start_listening
+ _dock_channel_system_service_client_stop_listening
+ _dock_channel_system_service_usb_device_iousbhost_base_client_functions
+ _dock_channel_system_service_usb_device_iousbhost_register_callbacks_function
+ _dock_channel_system_service_usb_device_iousbhost_start_listening_function
+ _dock_channel_system_service_usb_device_iousbhost_stop_listening_function
+ _dock_channel_system_service_usb_host_port_iousbhost_base_client_functions
+ _dock_channel_system_service_usb_host_port_iousbhost_register_callbacks_function
+ _dock_channel_system_service_usb_host_port_iousbhost_start_listening_function
+ _dock_channel_system_service_usb_host_port_iousbhost_stop_listening_function
+ _dock_channel_system_service_usb_hub_port_iousbhost_base_client_functions
+ _dock_channel_system_service_usb_hub_port_iousbhost_register_callbacks_function
+ _dock_channel_system_service_usb_hub_port_iousbhost_start_listening_function
+ _dock_channel_system_service_usb_hub_port_iousbhost_stop_listening_function
+ _objc_msgSend$createUSBDeviceClientWithDescription:
+ _objc_msgSend$createUSBHostPortClientWithDescription:
+ _objc_msgSend$createUSBHubPortClientWithDescription:
+ _objc_msgSend$initWithService:description:
+ _objc_msgSend$initWithService:serviceID:description:queue:
+ _objc_msgSend$stopListeningForTermination
- -[DockChannelProbeListenerProbeState dealloc]
- -[DockChannelSystemServiceClientWrapper initWithService:description:terminationCallback:terminationContext:]
- -[DockChannelSystemServiceIOService createClientWithDescription:terminationCallback:terminationContext:]
- -[DockChannelSystemServiceUSBDeviceClientWrapper initWithService:description:terminationCallback:terminationContext:]
- -[DockChannelSystemServiceUSBDeviceIOUSBHost initWithService:serviceID:description:terminationCallback:terminationContext:queue:]
- -[DockChannelSystemServiceUSBHostPortClientWrapper initWithService:description:terminationCallback:terminationContext:]
- -[DockChannelSystemServiceUSBHostPortIOUSBHost initWithService:serviceID:description:terminationCallback:terminationContext:queue:]
- -[DockChannelSystemServiceUSBHubPortClientWrapper initWithService:description:terminationCallback:terminationContext:]
- -[DockChannelSystemServiceUSBHubPortIOUSBHost initWithService:serviceID:description:terminationCallback:terminationContext:queue:]
- -[DockChannelSystemServiceWrapper createClientWithDescription:terminationCallback:terminationContext:]
- -[DockChannelSystemServiceWrapper createUSBDeviceClientWithDescription:terminationCallback:terminationContext:]
- -[DockChannelSystemServiceWrapper createUSBHostPortClientWithDescription:terminationCallback:terminationContext:]
- -[DockChannelSystemServiceWrapper createUSBHubPortClientWithDescription:terminationCallback:terminationContext:]
- ___53-[DockChannelSystemServiceUSBDeviceIOUSBHost dealloc]_block_invoke
- ___54-[DockChannelSystemServiceUSBHubPortIOUSBHost dealloc]_block_invoke
- ___55-[DockChannelSystemServiceUSBHostPortIOUSBHost dealloc]_block_invoke
- _objc_msgSend$createClientWithDescription:terminationCallback:terminationContext:
- _objc_msgSend$createUSBDeviceClientWithDescription:terminationCallback:terminationContext:
- _objc_msgSend$createUSBHostPortClientWithDescription:terminationCallback:terminationContext:
- _objc_msgSend$createUSBHubPortClientWithDescription:terminationCallback:terminationContext:
- _objc_msgSend$initWithService:description:terminationCallback:terminationContext:
- _objc_msgSend$initWithService:serviceID:description:terminationCallback:terminationContext:queue:
CStrings:
+ "2"
+ "@44@0:8I16Q20r*28@36"
+ "B24@0:8^{dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}16"
+ "B24@0:8r^{dock_channel_system_service_client_callbacks_t=^?^v}16"
+ "T@\"NSLock\",R,N,V_statusLock"
+ "TB,R,N,V_notificationsActive"
+ "T^{dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}},R,N,V_client"
+ "T^{dock_channel_system_service_usb_device_client_t={dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}^{dock_channel_system_service_usb_device_client_functions_t}},R,N,V_usbDeviceClient"
+ "T^{dock_channel_system_service_usb_host_port_client_t={dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}^{dock_channel_system_service_usb_host_port_client_functions_t}},R,N,V_usbHostPortClient"
+ "T^{dock_channel_system_service_usb_hub_port_client_t={dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}^{dock_channel_system_service_usb_hub_port_client_functions_t}},R,N,V_usbHubPortClient"
+ "T{dock_channel_system_service_usb_device_client_t={dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}^{dock_channel_system_service_usb_device_client_functions_t}},R,N,V_externalInterface"
+ "T{dock_channel_system_service_usb_host_port_client_t={dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}^{dock_channel_system_service_usb_host_port_client_functions_t}},R,N,V_externalInterface"
+ "T{dock_channel_system_service_usb_hub_port_client_t={dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}^{dock_channel_system_service_usb_hub_port_client_functions_t}},R,N,V_externalInterface"
+ "USBDevice[0x%llx] failed to add interest notification: %s (0x%x)."
+ "USBDevice[0x%llx] failed to create notification port."
+ "USBHostPort[0x%llx] failed to add interest notification: %s (0x%x)."
+ "USBHostPort[0x%llx] failed to create notification port."
+ "USBHubPort[0x%llx] failed to add interest notification: %s (0x%x)."
+ "USBHubPort[0x%llx] failed to create notification port."
+ "^{dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}"
+ "^{dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}16@0:8"
+ "^{dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}24@0:8r*16"
+ "^{dock_channel_system_service_usb_device_client_t={dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}^{dock_channel_system_service_usb_device_client_functions_t}}"
+ "^{dock_channel_system_service_usb_device_client_t={dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}^{dock_channel_system_service_usb_device_client_functions_t}}16@0:8"
+ "^{dock_channel_system_service_usb_host_port_client_t={dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}^{dock_channel_system_service_usb_host_port_client_functions_t}}"
+ "^{dock_channel_system_service_usb_host_port_client_t={dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}^{dock_channel_system_service_usb_host_port_client_functions_t}}16@0:8"
+ "^{dock_channel_system_service_usb_hub_port_client_t={dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}^{dock_channel_system_service_usb_hub_port_client_functions_t}}"
+ "^{dock_channel_system_service_usb_hub_port_client_t={dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}^{dock_channel_system_service_usb_hub_port_client_functions_t}}16@0:8"
+ "_notificationsActive"
+ "_statusLock"
+ "createUSBDeviceClientWithDescription:"
+ "createUSBHostPortClientWithDescription:"
+ "createUSBHubPortClientWithDescription:"
+ "initWithService:description:"
+ "initWithService:serviceID:description:queue:"
+ "notificationsActive"
+ "statusLock"
+ "stopListeningForTermination"
+ "{dock_channel_system_service_usb_device_client_t=\"_base_client\"{dock_channel_system_service_client_t=\"_data\"^v\"_functions\"^{dock_channel_system_service_client_functions_t}}\"_functions\"^{dock_channel_system_service_usb_device_client_functions_t}}"
+ "{dock_channel_system_service_usb_device_client_t={dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}^{dock_channel_system_service_usb_device_client_functions_t}}16@0:8"
+ "{dock_channel_system_service_usb_host_port_client_t=\"_base_client\"{dock_channel_system_service_client_t=\"_data\"^v\"_functions\"^{dock_channel_system_service_client_functions_t}}\"_functions\"^{dock_channel_system_service_usb_host_port_client_functions_t}}"
+ "{dock_channel_system_service_usb_host_port_client_t={dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}^{dock_channel_system_service_usb_host_port_client_functions_t}}16@0:8"
+ "{dock_channel_system_service_usb_hub_port_client_t=\"_base_client\"{dock_channel_system_service_client_t=\"_data\"^v\"_functions\"^{dock_channel_system_service_client_functions_t}}\"_functions\"^{dock_channel_system_service_usb_hub_port_client_functions_t}}"
+ "{dock_channel_system_service_usb_hub_port_client_t={dock_channel_system_service_client_t=^v^{dock_channel_system_service_client_functions_t}}^{dock_channel_system_service_usb_hub_port_client_functions_t}}16@0:8"
- "!1"
- "@40@0:8r*16^?24r^v32"
- "@48@0:8@16r*24^?32r^v40"
- "@60@0:8I16Q20r*28^?36r^v44@52"
- "B24@0:8^{dock_channel_system_service_client_t=}16"
- "T^{dock_channel_system_service_client_t=},R,N,V_client"
- "T^{dock_channel_system_service_usb_device_client_t=^v^{dock_channel_system_service_usb_device_client_functions_t}},R,N,V_usbDeviceClient"
- "T^{dock_channel_system_service_usb_host_port_client_t=^v^{dock_channel_system_service_usb_host_port_client_functions_t}},R,N,V_usbHostPortClient"
- "T^{dock_channel_system_service_usb_hub_port_client_t=^v^{dock_channel_system_service_usb_hub_port_client_functions_t}},R,N,V_usbHubPortClient"
- "T{dock_channel_system_service_usb_device_client_t=^v^{dock_channel_system_service_usb_device_client_functions_t}},R,N,V_externalInterface"
- "T{dock_channel_system_service_usb_host_port_client_t=^v^{dock_channel_system_service_usb_host_port_client_functions_t}},R,N,V_externalInterface"
- "T{dock_channel_system_service_usb_hub_port_client_t=^v^{dock_channel_system_service_usb_hub_port_client_functions_t}},R,N,V_externalInterface"
- "^{dock_channel_system_service_client_t=}"
- "^{dock_channel_system_service_client_t=}16@0:8"
- "^{dock_channel_system_service_client_t=}40@0:8r*16^?24r^v32"
- "^{dock_channel_system_service_usb_device_client_t=^v^{dock_channel_system_service_usb_device_client_functions_t}}"
- "^{dock_channel_system_service_usb_device_client_t=^v^{dock_channel_system_service_usb_device_client_functions_t}}16@0:8"
- "^{dock_channel_system_service_usb_host_port_client_t=^v^{dock_channel_system_service_usb_host_port_client_functions_t}}"
- "^{dock_channel_system_service_usb_host_port_client_t=^v^{dock_channel_system_service_usb_host_port_client_functions_t}}16@0:8"
- "^{dock_channel_system_service_usb_hub_port_client_t=^v^{dock_channel_system_service_usb_hub_port_client_functions_t}}"
- "^{dock_channel_system_service_usb_hub_port_client_t=^v^{dock_channel_system_service_usb_hub_port_client_functions_t}}16@0:8"
- "createClientWithDescription:terminationCallback:terminationContext:"
- "createUSBDeviceClientWithDescription:terminationCallback:terminationContext:"
- "createUSBHostPortClientWithDescription:terminationCallback:terminationContext:"
- "createUSBHubPortClientWithDescription:terminationCallback:terminationContext:"
- "initWithService:description:terminationCallback:terminationContext:"
- "initWithService:serviceID:description:terminationCallback:terminationContext:queue:"
- "{dock_channel_system_service_usb_device_client_t=\"_data\"^v\"_functions\"^{dock_channel_system_service_usb_device_client_functions_t}}"
- "{dock_channel_system_service_usb_device_client_t=^v^{dock_channel_system_service_usb_device_client_functions_t}}16@0:8"
- "{dock_channel_system_service_usb_host_port_client_t=\"_data\"^v\"_functions\"^{dock_channel_system_service_usb_host_port_client_functions_t}}"
- "{dock_channel_system_service_usb_host_port_client_t=^v^{dock_channel_system_service_usb_host_port_client_functions_t}}16@0:8"
- "{dock_channel_system_service_usb_hub_port_client_t=\"_data\"^v\"_functions\"^{dock_channel_system_service_usb_hub_port_client_functions_t}}"
- "{dock_channel_system_service_usb_hub_port_client_t=^v^{dock_channel_system_service_usb_hub_port_client_functions_t}}16@0:8"
```
