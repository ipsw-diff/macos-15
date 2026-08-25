## DeviceInterfaceClient

> `/System/Library/Templates/Data/Library/Apple/System/Library/PrivateFrameworks/DeviceInterfaceClient.framework/Versions/A/DeviceInterfaceClient`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_protolist`
- `__AUTH.__objc_data`
- `__DATA.__data`

```diff

-208.140.7.0.0
-  __TEXT.__text: 0x4d58
-  __TEXT.__auth_stubs: 0x200
-  __TEXT.__objc_methlist: 0x3b4
+208.140.8.0.0
+  __TEXT.__text: 0x41f4
+  __TEXT.__auth_stubs: 0x230
+  __TEXT.__objc_methlist: 0x404
   __TEXT.__const: 0x40
-  __TEXT.__gcc_except_tab: 0xc8
-  __TEXT.__cstring: 0x870
-  __TEXT.__oslogstring: 0x289
-  __TEXT.__unwind_info: 0xf0
-  __TEXT.__objc_classname: 0x95
-  __TEXT.__objc_methname: 0xba5
-  __TEXT.__objc_methtype: 0x509
-  __TEXT.__objc_stubs: 0x760
-  __DATA_CONST.__got: 0x70
-  __DATA_CONST.__const: 0x60
+  __TEXT.__gcc_except_tab: 0x104
+  __TEXT.__cstring: 0xfaf
+  __TEXT.__unwind_info: 0x108
+  __TEXT.__eh_frame: 0xfc
+  __TEXT.__objc_classname: 0x96
+  __TEXT.__objc_methname: 0xc60
+  __TEXT.__objc_methtype: 0x527
+  __TEXT.__objc_stubs: 0x820
+  __DATA_CONST.__got: 0x28
+  __DATA_CONST.__const: 0x80
   __DATA_CONST.__objc_classlist: 0x10
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2e8
-  __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x10
-  __AUTH_CONST.__auth_got: 0x110
-  __AUTH_CONST.__const: 0x230
-  __AUTH_CONST.__cfstring: 0x40
-  __AUTH_CONST.__objc_const: 0x5a0
+  __DATA_CONST.__objc_selrefs: 0x320
+  __AUTH_CONST.__auth_got: 0x128
+  __AUTH_CONST.__const: 0x250
+  __AUTH_CONST.__cfstring: 0x20
+  __AUTH_CONST.__objc_const: 0x5d8
   __AUTH.__objc_data: 0xa0
-  __DATA.__objc_ivar: 0x38
+  __DATA.__objc_protorefs: 0x10
+  __DATA.__objc_classrefs: 0x50
+  __DATA.__objc_superrefs: 0x10
+  __DATA.__objc_ivar: 0x3c
   __DATA.__data: 0x121
-  __DATA.__bss: 0x8
+  __DATA.__bss: 0x40
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 85
-  Symbols:   259
-  CStrings:  249
+  Functions: 95
+  Symbols:   281
+  CStrings:  288
 
Symbols:
+ +[DeviceInterfaceClientXPCClient sharedXPCClient]
+ -[DeviceInterfaceClientXPCClient _init]
+ -[DeviceInterfaceClientXPCClient checkInWithServerAsync]
+ -[DeviceInterfaceClientXPCClient checkInWithServer]
+ -[DeviceInterfaceClientXPCClient getConnectionToXPCService]
+ -[DeviceInterfaceClientXPCClient setConnectionToXPCService:]
+ -[DeviceInterfaceClientXPCClient xpcConnectionLock]
+ GCC_except_table20
+ GCC_except_table29
+ GCC_except_table3
+ GCC_except_table9
+ OBJC_IVAR_$_DeviceInterfaceClientXPCClient._xpcConnectionLock
+ _OBJC_CLASS_$_NSLock
+ _OUTLINED_FUNCTION_0
+ _OUTLINED_FUNCTION_1
+ __MergedGlobals
+ __OBJC_$_CLASS_METHODS_DeviceInterfaceClientXPCClient
+ ___130-[DeviceInterfaceClientXPCClient transferData:inputCount:inputStruct:inputStructCount:outputStruct:outputStructCount:interfaceID:]_block_invoke_2
+ ___49+[DeviceInterfaceClientXPCClient sharedXPCClient]_block_invoke
+ ___51-[DeviceInterfaceClientXPCClient checkInWithServer]_block_invoke
+ ___51-[DeviceInterfaceClientXPCClient checkInWithServer]_block_invoke_2
+ ___56-[DeviceInterfaceClientXPCClient checkInWithServerAsync]_block_invoke
+ ___56-[DeviceInterfaceClientXPCClient stmDestroyDockChannel:]_block_invoke_2
+ ___59-[DeviceInterfaceClientXPCClient updatePortalAvailability:]_block_invoke_2
+ ___62-[DeviceInterfaceClientXPCClient exclusiveAccess:interfaceID:]_block_invoke_2
+ ___64-[DeviceInterfaceClientXPCClient portalTransaction:interfaceID:]_block_invoke_2
+ ___85-[DeviceInterfaceClientXPCClient stmCreateDockChannel:suffix:suffixSize:interfaceID:]_block_invoke_2
+ ___assert_rtn
+ ___block_descriptor_40_e5_v8?0l
+ ___device_interface_user_client_should_use_kext_block_invoke
+ ___isPlatformOrVariantPlatformVersionAtLeast
+ __availability_version_check
+ __initializeAvailabilityCheck
+ __isPlatformOrVariantPlatformVersionAtLeast
+ __os_log_internal
+ _checkInWithServerAsync
+ _compatibilityInitializeAvailabilityCheck
+ _dispatch_once_f
+ _dlsym
+ _fclose
+ _fopen
+ _fread
+ _free
+ _fseek
+ _ftell
+ _initializeAvailabilityCheck
+ _malloc
+ _objc_msgSend$_init
+ _objc_msgSend$checkInWithServer
+ _objc_msgSend$checkInWithServerAsync
+ _objc_msgSend$description
+ _objc_msgSend$getConnectionToXPCService
+ _objc_msgSend$init
+ _objc_msgSend$invalidate
+ _objc_msgSend$setupWithReply:
+ _objc_msgSend$sharedXPCClient
+ _objc_retainAutoreleaseReturnValue
+ _rewind
+ _sscanf
+ device_interface_user_client_should_use_kext.onceToken
+ device_interface_user_client_should_use_kext.shouldUseKext
+ sharedXPCClient.onceToken
+ sharedXPCClient.sharedClient
- -[DeviceInterfaceClientXPCClient init]
- -[DeviceInterfaceClientXPCClient pingServer]
- GCC_except_table1
- GCC_except_table14
- GCC_except_table27
- _IOObjectRelease
- _IORegistryEntryCreateCFProperty
- _IOServiceGetMatchingService
- _IOServiceMatching
- __130-[DeviceInterfaceClientXPCClient transferData:inputCount:inputStruct:inputStructCount:outputStruct:outputStructCount:interfaceID:]_block_invoke
- __56-[DeviceInterfaceClientXPCClient stmDestroyDockChannel:]_block_invoke
- __59-[DeviceInterfaceClientXPCClient updatePortalAvailability:]_block_invoke
- __62-[DeviceInterfaceClientXPCClient exclusiveAccess:interfaceID:]_block_invoke
- __64-[DeviceInterfaceClientXPCClient portalTransaction:interfaceID:]_block_invoke
- __85-[DeviceInterfaceClientXPCClient stmCreateDockChannel:suffix:suffixSize:interfaceID:]_block_invoke
- ___44-[DeviceInterfaceClientXPCClient pingServer]_block_invoke
- ___os_log_helper_16_0_0
- ___os_log_helper_16_2_2_8_32_4_0
- ___os_log_helper_16_2_3_8_32_4_0_4_0
- ___os_log_helper_16_2_3_8_32_4_0_8_64
- ___os_log_helper_16_2_4_8_32_4_0_8_0_8_64
- ___shouldUseKext_block_invoke
- __os_log_debug_impl
- __os_log_error_impl
- __os_log_impl
- _createDeviceInterfaceClientXPCClient
- _kCFAllocatorDefault
- _kIOMainPortDefault
- _objc_alloc_init
- _objc_msgSend$pingServer
- _objc_msgSend$unsignedIntValue
- _objc_msgSend$xpcClientPtr
- _objc_opt_class
- _objc_opt_isKindOfClass
- _os_log_type_enabled
- _os_parse_boot_arg_int
- _pingServer
- _rsm_channel_controller_version
- _shouldUseKext
- shouldUseKext.onceToken
- shouldUseKext.shouldUseKext
CStrings:
+ "%d.%d.%d"
+ "%s Received reply, error: %@"
+ "%s failed to create DeviceInterfaceXPCClient"
+ "%s remote %@"
+ "%s setupWithReply received success %d"
+ "%s:%d: Calling _deviceAddedCallback: %@"
+ "%s:%d: Check in with server not supported"
+ "%s:%d: Connection invalidated from remote side."
+ "-[DeviceInterfaceClientXPCClient _init]"
+ "-[DeviceInterfaceClientXPCClient checkInWithServerAsync]"
+ "-[DeviceInterfaceClientXPCClient checkInWithServerAsync]_block_invoke"
+ "-[DeviceInterfaceClientXPCClient checkInWithServer]"
+ "-[DeviceInterfaceClientXPCClient checkInWithServer]_block_invoke"
+ "-[DeviceInterfaceClientXPCClient checkInWithServer]_block_invoke_2"
+ "-[DeviceInterfaceClientXPCClient deviceAdded:]"
+ "-[DeviceInterfaceClientXPCClient exclusiveAccess:interfaceID:]_block_invoke_2"
+ "-[DeviceInterfaceClientXPCClient portalTransaction:interfaceID:]_block_invoke_2"
+ "-[DeviceInterfaceClientXPCClient stmCreateDockChannel:suffix:suffixSize:interfaceID:]_block_invoke_2"
+ "-[DeviceInterfaceClientXPCClient stmDestroyDockChannel:]_block_invoke_2"
+ "-[DeviceInterfaceClientXPCClient updatePortalAvailability:]_block_invoke_2"
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
+ "Platform2 == PLATFORM_MACOS && \"unexpected platform\""
+ "ProductVersion"
+ "T@\"NSLock\",R,N,V_xpcConnectionLock"
+ "T@\"NSXPCConnection\",&,N,V_connectionToXPCService"
+ "__isPlatformOrVariantPlatformVersionAtLeast"
+ "_init"
+ "_xpcConnectionLock"
+ "checkInWithServer"
+ "checkInWithServerAsync"
+ "getConnectionToXPCService"
+ "invalidate"
+ "kCFAllocatorNull"
+ "os_version_check.c"
+ "r"
+ "setConnectionToXPCService:"
+ "setupWithReply:"
+ "sharedXPCClient"
+ "v24@0:8@?16"
+ "v24@0:8@?<v@?B>16"
+ "xpcConnectionLock"
- "%s:%d: Connection invalidated"
- "%s:%d: Ping not supported"
- "-[DeviceInterfaceClientXPCClient pingServer]"
- "-[DeviceInterfaceClientXPCClient pingServer]_block_invoke"
- "AppleRSMChannelController"
- "AppleRSMChannelControllerMajorVersion"
- "RSM Channel Controller service not found!"
- "T@\"NSXPCConnection\",R,N,V_connectionToXPCService"
- "kis-kext"
- "pingServer"
- "unsignedIntValue"
```
