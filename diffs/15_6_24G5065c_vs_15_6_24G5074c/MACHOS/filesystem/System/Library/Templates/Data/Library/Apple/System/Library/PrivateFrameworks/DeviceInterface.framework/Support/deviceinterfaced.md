## deviceinterfaced

> `/System/Library/Templates/Data/Library/Apple/System/Library/PrivateFrameworks/DeviceInterface.framework/Support/deviceinterfaced`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-208.140.7.0.0
-  __TEXT.__text: 0xe858
-  __TEXT.__auth_stubs: 0x3f0
-  __TEXT.__objc_stubs: 0x400
+208.140.8.0.0
+  __TEXT.__text: 0x81c0
+  __TEXT.__auth_stubs: 0x480
+  __TEXT.__objc_stubs: 0x460
   __TEXT.__objc_methlist: 0x320
-  __TEXT.__oslogstring: 0x2dcf
-  __TEXT.__cstring: 0xe07
-  __TEXT.__objc_classname: 0x1b
-  __TEXT.__objc_methname: 0x1624
+  __TEXT.__cstring: 0x3de6
+  __TEXT.__objc_classname: 0x1a
+  __TEXT.__objc_methname: 0x1666
   __TEXT.__objc_methtype: 0x65c
-  __TEXT.__unwind_info: 0xf8
-  __DATA_CONST.__auth_got: 0x200
-  __DATA_CONST.__got: 0x58
-  __DATA_CONST.__const: 0x100
-  __DATA_CONST.__cfstring: 0xc0
+  __TEXT.__unwind_info: 0xa8
+  __TEXT.__eh_frame: 0xb4
+  __DATA_CONST.__auth_got: 0x248
+  __DATA_CONST.__got: 0x50
+  __DATA_CONST.__auth_ptr: 0x8
+  __DATA_CONST.__const: 0x170
+  __DATA_CONST.__cfstring: 0x120
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA.__objc_const: 0x5b0
-  __DATA.__objc_selrefs: 0x218
+  __DATA.__objc_selrefs: 0x230
+  __DATA.__objc_classrefs: 0x10
   __DATA.__objc_ivar: 0x6c
   __DATA.__objc_data: 0x50
   __DATA.__data: 0x3
-  __DATA.__bss: 0x40
+  __DATA.__bss: 0x68
   - /Library/Apple/System/Library/PrivateFrameworks/DeviceInterface.framework/Versions/A/DeviceInterface
   - /Library/Apple/System/Library/PrivateFrameworks/DeviceInterfaceClient.framework/Versions/A/DeviceInterfaceClient
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 116
-  Symbols:   82
-  CStrings:  419
+  Functions: 121
+  Symbols:   91
+  CStrings:  444
 
Symbols:
+ _KextManagerLoadKextWithIdentifier
+ _OBJC_CLASS_$_NSArray
+ ___NSArray0__
+ __availability_version_check
+ __os_log_internal
+ __xpc_error_connection_invalid
+ _dispatch_once_f
+ _dlsym
+ _fclose
+ _fopen
+ _fread
+ _free
+ _fseek
+ _ftell
+ _mach_error_string
+ _malloc
+ _memset
+ _objc_alloc
+ _objc_enumerationMutation
+ _objc_retainAutorelease
+ _os_parse_boot_arg_int
+ _rewind
+ _sscanf
+ _sysctlbyname
+ _xpc_connection_activate
+ _xpc_connection_cancel
+ _xpc_connection_create_mach_service
+ _xpc_connection_set_event_handler
- _CFRelease
- _IOIteratorNext
- _IONotificationPortCreate
- _IONotificationPortDestroy
- _IONotificationPortSetDispatchQueue
- _IOObjectRelease
- _IORegistryEntryCreateCFProperty
- _IOServiceAddMatchingNotification
- _IOServiceMatching
- _OBJC_CLASS_$_NSNumber
- __os_log_error_impl
- __os_log_impl
- _dispatch_async
- _kCFAllocatorDefault
- _kIOMainPortDefault
- _objc_alloc_init
- _objc_opt_class
- _objc_opt_isKindOfClass
- _os_log_type_enabled
CStrings:
+ "%@ invalidated"
+ "%d.%d.%d"
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
+ "KIS kext failed to load: %{public}s (%#x)"
+ "KIS kext is %s"
+ "KIS kext is forced %s"
+ "KIS kext loaded"
+ "ProductVersion"
+ "UTF8String"
+ "applekis.enabled"
+ "arrayWithObjects:count:"
+ "com.apple.deviceinterfaced.device-interface-client"
+ "com.apple.deviceinterfaced.tadfu-transport-server"
+ "com.apple.driver.AppleKIS"
+ "com.apple.driver.kis.AppleKIS"
+ "countByEnumeratingWithState:objects:count:"
+ "deviceinterfaced is disabled: AppleKIS kext is active"
+ "deviceinterfaced is disabled: not supported on this OS"
+ "deviceinterfaced is enabled"
+ "deviceinterfaced_os_is_supported"
+ "init"
+ "kCFAllocatorNull"
+ "kis-kext"
+ "r"
- "%s controller found %d version %d"
- "AppleRSMChannelController"
- "AppleRSMChannelControllerMajorVersion"
- "IOServiceFirstPublish"
- "deviceinterfaced_can_start"
- "deviceinterfaced_requires_async_start"
- "rsm_channel_controller_services_discovered"
- "unsignedIntValue"
```
