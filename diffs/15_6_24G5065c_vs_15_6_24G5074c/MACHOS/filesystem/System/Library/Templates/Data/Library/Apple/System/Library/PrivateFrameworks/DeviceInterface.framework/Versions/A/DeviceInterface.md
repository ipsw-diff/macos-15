## DeviceInterface

> `/System/Library/Templates/Data/Library/Apple/System/Library/PrivateFrameworks/DeviceInterface.framework/Versions/A/DeviceInterface`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methtype`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__data`

```diff

-208.140.7.0.0
-  __TEXT.__text: 0x89140
-  __TEXT.__auth_stubs: 0x640
+208.140.8.0.0
+  __TEXT.__text: 0x73cd8
+  __TEXT.__auth_stubs: 0x690
   __TEXT.__objc_methlist: 0x5d1c
   __TEXT.__const: 0x64
-  __TEXT.__oslogstring: 0x4356
-  __TEXT.__cstring: 0x48c5
-  __TEXT.__gcc_except_tab: 0x8a4
-  __TEXT.__unwind_info: 0x13c0
+  __TEXT.__cstring: 0x8e36
+  __TEXT.__gcc_except_tab: 0x418
+  __TEXT.__unwind_info: 0x1158
+  __TEXT.__eh_frame: 0xfc
   __TEXT.__objc_classname: 0xd4a
-  __TEXT.__objc_methname: 0xd819
+  __TEXT.__objc_methname: 0xd766
   __TEXT.__objc_methtype: 0x696b
-  __TEXT.__objc_stubs: 0x63e0
-  __DATA_CONST.__got: 0x240
+  __TEXT.__objc_stubs: 0x6420
+  __DATA_CONST.__got: 0x50
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__objc_classlist: 0x2e0
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x22f8
-  __DATA_CONST.__objc_protorefs: 0x20
-  __DATA_CONST.__objc_superrefs: 0x2d0
-  __AUTH_CONST.__auth_got: 0x330
+  __DATA_CONST.__objc_selrefs: 0x22e8
+  __AUTH_CONST.__auth_got: 0x358
   __AUTH_CONST.__const: 0x7c0
   __AUTH_CONST.__cfstring: 0x620
-  __AUTH_CONST.__objc_const: 0xc5a0
-  __AUTH_CONST.__objc_intobj: 0x120
+  __AUTH_CONST.__objc_const: 0xc578
   __AUTH.__objc_data: 0x1cc0
   __AUTH.__data: 0x4f0
-  __DATA.__objc_ivar: 0xa8c
+  __DATA.__objc_protorefs: 0x20
+  __DATA.__objc_classrefs: 0x380
+  __DATA.__objc_superrefs: 0x2d0
+  __DATA.__objc_ivar: 0xa88
   __DATA.__data: 0x4b0
-  __DATA.__bss: 0xa0
+  __DATA.__bss: 0xc8
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpcap.A.dylib
-  Functions: 2539
-  Symbols:   4988
-  CStrings:  3283
+  Functions: 2474
+  Symbols:   4929
+  CStrings:  3300
 
Symbols:
+ -[DeviceInterfaceClientXPCServer interfaceIDsLock]
+ -[DeviceInterfaceClientXPCServer interfaceIDs]
+ -[DeviceInterfaceClientXPCServer setInterfaceIDs:]
+ -[DeviceInterfaceClientXPCServer setInterfaceIDsLock:]
+ -[DeviceInterfaceClientXPCServer setupWithReply:]
+ GCC_except_table11
+ GCC_except_table13
+ GCC_except_table24
+ GCC_except_table3
+ GCC_except_table34
+ GCC_except_table6
+ GCC_except_table7
+ OBJC_IVAR_$_DeviceInterfaceClientXPCServer._interfaceIDs
+ OBJC_IVAR_$_DeviceInterfaceClientXPCServer._interfaceIDsLock
+ _OUTLINED_FUNCTION_0
+ _OUTLINED_FUNCTION_1
+ __MergedGlobals
+ ___49-[DockChannelProbeNexus startListeningForClient:]_block_invoke_2
+ ___56-[DebugUSBDeviceInterfaceIOUSBHost startWithCompletion:]_block_invoke_2
+ ___59-[TADFUTransportServer listener:shouldAcceptNewConnection:]_block_invoke_2
+ ___73-[DockChannelSerialInterfaceIOUserDockChannelSerial startWithCompletion:]_block_invoke_2
+ ___73-[DockChannelSerialInterfaceIOUserDockChannelSerial startWithCompletion:]_block_invoke_3
+ ___assert_rtn
+ ___isPlatformOrVariantPlatformVersionAtLeast
+ __availability_version_check
+ __initializeAvailabilityCheck
+ __isPlatformOrVariantPlatformVersionAtLeast
+ __os_log_internal
+ _compatibilityInitializeAvailabilityCheck
+ _dispatch_once_f
+ _dlsym
+ _fclose
+ _fopen
+ _fread
+ _fseek
+ _ftell
+ _initializeAvailabilityCheck
+ _malloc
+ _objc_msgSend$class
+ _objc_msgSend$init
+ _objc_msgSend$isKindOfClass:
+ _objc_msgSend$new
+ _rewind
+ _sscanf
+ _tadfu_transport_client_usable
- -[DeviceInterfaceClientXPCServer externaInterfaceClients]
- -[DeviceInterfaceClientXPCServer externalInterfaceClientsLock]
- -[DeviceInterfaceClientXPCServer interfaces]
- -[DeviceInterfaceClientXPCServer setExternaInterfaceClients:]
- -[DeviceInterfaceClientXPCServer setExternalInterfaceClientsLock:]
- -[DeviceInterfaceClientXPCServer setInterfaces:]
- GCC_except_table12
- GCC_except_table20
- GCC_except_table23
- GCC_except_table25
- GCC_except_table29
- GCC_except_table40
- GCC_except_table5
- OBJC_IVAR_$_DeviceInterfaceClientXPCServer._externaInterfaceClients
- OBJC_IVAR_$_DeviceInterfaceClientXPCServer._externalInterfaceClientsLock
- OBJC_IVAR_$_DeviceInterfaceClientXPCServer._interfaces
- _OBJC_CLASS_$_NSConstantIntegerNumber
- __49-[DockChannelProbeNexus startListeningForClient:]_block_invoke
- __56-[DebugUSBDeviceInterfaceIOUSBHost startWithCompletion:]_block_invoke
- __73-[DockChannelSerialInterfaceIOUserDockChannelSerial startWithCompletion:]_block_invoke
- ___os_log_helper_16_0_0
- ___os_log_helper_16_0_1_4_0
- ___os_log_helper_16_0_1_8_0
- ___os_log_helper_16_0_2_4_0_4_0
- ___os_log_helper_16_0_2_8_0_4_0
- ___os_log_helper_16_0_3_8_0_4_0_4_0
- ___os_log_helper_16_0_3_8_0_8_0_4_0
- ___os_log_helper_16_0_4_8_0_4_0_4_0_4_0
- ___os_log_helper_16_2_10_8_32_8_0_8_0_8_0_4_0_4_0_4_0_4_0_4_0_4_0
- ___os_log_helper_16_2_11_8_32_8_32_8_0_8_0_8_0_4_0_4_0_4_0_4_0_4_0_4_0
- ___os_log_helper_16_2_1_8_32
- ___os_log_helper_16_2_1_8_64
- ___os_log_helper_16_2_2_4_0_8_32
- ___os_log_helper_16_2_2_4_0_8_64
- ___os_log_helper_16_2_2_8_0_8_64
- ___os_log_helper_16_2_2_8_32_4_0
- ___os_log_helper_16_2_2_8_32_8_0
- ___os_log_helper_16_2_2_8_32_8_32
- ___os_log_helper_16_2_2_8_32_8_64
- ___os_log_helper_16_2_2_8_64_8_64
- ___os_log_helper_16_2_3_8_0_8_0_8_32
- ___os_log_helper_16_2_3_8_0_8_32_4_0
- ___os_log_helper_16_2_3_8_0_8_64_4_0
- ___os_log_helper_16_2_3_8_0_8_64_8_0
- ___os_log_helper_16_2_3_8_0_8_64_8_32
- ___os_log_helper_16_2_3_8_0_8_64_8_64
- ___os_log_helper_16_2_3_8_32_4_0_4_0
- ___os_log_helper_16_2_3_8_32_4_0_8_64
- ___os_log_helper_16_2_3_8_32_8_0_4_0
- ___os_log_helper_16_2_3_8_32_8_0_8_0
- ___os_log_helper_16_2_3_8_32_8_0_8_32
- ___os_log_helper_16_2_3_8_32_8_0_8_64
- ___os_log_helper_16_2_3_8_32_8_32_4_0
- ___os_log_helper_16_2_3_8_32_8_32_8_0
- ___os_log_helper_16_2_3_8_32_8_32_8_32
- ___os_log_helper_16_2_3_8_32_8_64_4_0
- ___os_log_helper_16_2_3_8_32_8_64_8_0
- ___os_log_helper_16_2_3_8_32_8_64_8_32
- ___os_log_helper_16_2_3_8_32_8_64_8_64
- ___os_log_helper_16_2_3_8_64_8_0_8_0
- ___os_log_helper_16_2_3_8_64_8_64_8_0
- ___os_log_helper_16_2_4_8_0_8_64_8_64_4_0
- ___os_log_helper_16_2_4_8_32_4_0_4_0_8_64
- ___os_log_helper_16_2_4_8_32_4_0_8_64_8_64
- ___os_log_helper_16_2_4_8_32_8_0_4_0_4_0
- ___os_log_helper_16_2_4_8_32_8_0_4_0_8_0
- ___os_log_helper_16_2_4_8_32_8_0_8_0_8_0
- ___os_log_helper_16_2_4_8_32_8_0_8_0_8_64
- ___os_log_helper_16_2_4_8_32_8_0_8_32_4_0
- ___os_log_helper_16_2_4_8_32_8_0_8_32_8_32
- ___os_log_helper_16_2_4_8_32_8_0_8_32_8_64
- ___os_log_helper_16_2_4_8_32_8_32_4_0_4_0
- ___os_log_helper_16_2_4_8_32_8_32_4_0_8_32
- ___os_log_helper_16_2_4_8_32_8_32_8_0_4_0
- ___os_log_helper_16_2_4_8_32_8_32_8_32_4_0
- ___os_log_helper_16_2_4_8_32_8_32_8_32_8_32
- ___os_log_helper_16_2_4_8_32_8_64_4_0_4_0
- ___os_log_helper_16_2_4_8_32_8_64_8_0_4_0
- ___os_log_helper_16_2_4_8_32_8_64_8_0_8_0
- ___os_log_helper_16_2_4_8_32_8_64_8_32_8_64
- ___os_log_helper_16_2_4_8_32_8_64_8_64_8_64
- ___os_log_helper_16_2_5_8_0_4_0_4_0_4_0_8_32
- ___os_log_helper_16_2_5_8_0_8_64_8_64_4_0_8_0
- ___os_log_helper_16_2_5_8_0_8_64_8_64_8_32_4_0
- ___os_log_helper_16_2_5_8_32_4_0_8_0_8_64_8_64
- ___os_log_helper_16_2_5_8_32_4_0_8_64_8_64_8_64
- ___os_log_helper_16_2_5_8_32_8_0_4_0_4_0_8_64
- ___os_log_helper_16_2_5_8_32_8_0_8_0_4_0_4_0
- ___os_log_helper_16_2_5_8_32_8_0_8_32_8_32_8_32
- ___os_log_helper_16_2_5_8_32_8_32_8_0_8_0_8_32
- ___os_log_helper_16_2_5_8_32_8_32_8_32_8_0_8_0
- ___os_log_helper_16_2_5_8_32_8_32_8_32_8_32_8_32
- ___os_log_helper_16_2_7_8_32_4_0_4_0_8_0_8_0_4_0_4_0
- ___os_log_helper_16_2_8_8_32_4_0_4_0_8_0_8_0_4_0_4_0_8_32
- ___os_log_helper_16_2_9_8_32_8_0_8_0_8_0_4_0_4_0_4_0_4_0_4_0
- __os_log_error_impl
- __os_log_impl
- _objc_alloc_init
- _objc_msgSend$allKeys
- _objc_msgSend$value:withObjCType:
- _objc_opt_class
- _objc_opt_isKindOfClass
- _objc_opt_new
- _os_log_type_enabled
CStrings:
+ "%d.%d.%d"
+ "%s:%d: Calling deviceAdded for interfaceID: %@"
+ "%s:%d: Calling deviceAdded for interfaceID: %@ for client: %@"
+ "-[DeviceInterfaceClientXPCServer device_added:]"
+ "-[DeviceInterfaceClientXPCServer setupWithReply:]"
+ "/System/Library/CoreServices/SystemVersion.plist"
+ "CFDataCreateWithBytesNoCopy"
+ "CFDictionaryGetValue"
+ "CFGetTypeID"
+ "CFPropertyListCreateFromXMLData"
+ "CFPropertyListCreateWithData"
+ "CFRelease"
+ "CFStringCreateWithCStringNoCopy"
+ "CFStringGetCString"
+ "CFStringGetTypeID"
+ "IOServiceFirstMatch"
+ "Platform2 == PLATFORM_MACOS && \"unexpected platform\""
+ "ProductVersion"
+ "T@\"NSLock\",&,N,V_interfaceIDsLock"
+ "T@\"NSMutableSet\",&,N,V_interfaceIDs"
+ "__isPlatformOrVariantPlatformVersionAtLeast"
+ "_interfaceIDs"
+ "_interfaceIDsLock"
+ "interfaceIDs"
+ "interfaceIDsLock"
+ "kCFAllocatorNull"
+ "new"
+ "os_version_check.c"
+ "r"
+ "setInterfaceIDs:"
+ "setInterfaceIDsLock:"
- "IOServiceFirstPublish"
- "T@\"NSLock\",&,N,V_externalInterfaceClientsLock"
- "T@\"NSMutableDictionary\",&,N,V_externaInterfaceClients"
- "T@\"NSMutableDictionary\",&,N,V_interfaces"
- "_externaInterfaceClients"
- "_externalInterfaceClientsLock"
- "allKeys"
- "externaInterfaceClients"
- "externalInterfaceClientsLock"
- "setExternaInterfaceClients:"
- "setExternalInterfaceClientsLock:"
- "setInterfaces:"
- "value:withObjCType:"
- "{external_interface_client_t=^v^{external_interface_client_functions_t}}"
```
