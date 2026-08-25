## DeviceInterface

> `/System/Library/Templates/Data/Library/Apple/System/Library/PrivateFrameworks/DeviceInterface.framework/Versions/A/DeviceInterface`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__objc_protorefs`
- `__DATA.__objc_superrefs`
- `__DATA.__data`

```diff

-208.140.8.0.0
-  __TEXT.__text: 0x73cd8
+208.140.9.0.0
+  __TEXT.__text: 0x73d74
   __TEXT.__auth_stubs: 0x690
-  __TEXT.__objc_methlist: 0x5d1c
+  __TEXT.__objc_methlist: 0x5d2c
   __TEXT.__const: 0x64
-  __TEXT.__cstring: 0x8e36
+  __TEXT.__cstring: 0x8e42
   __TEXT.__gcc_except_tab: 0x418
   __TEXT.__unwind_info: 0x1158
   __TEXT.__eh_frame: 0xfc
-  __TEXT.__objc_classname: 0xd4a
-  __TEXT.__objc_methname: 0xd766
-  __TEXT.__objc_methtype: 0x696b
-  __TEXT.__objc_stubs: 0x6420
+  __TEXT.__objc_classname: 0xd4d
+  __TEXT.__objc_methname: 0xd772
+  __TEXT.__objc_methtype: 0x69bf
+  __TEXT.__objc_stubs: 0x6440
   __DATA_CONST.__got: 0x50
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__objc_classlist: 0x2e0

   __AUTH_CONST.__auth_got: 0x358
   __AUTH_CONST.__const: 0x7c0
   __AUTH_CONST.__cfstring: 0x620
-  __AUTH_CONST.__objc_const: 0xc578
+  __AUTH_CONST.__objc_const: 0xc5a8
   __AUTH.__objc_data: 0x1cc0
   __AUTH.__data: 0x4f0
   __DATA.__objc_protorefs: 0x20
   __DATA.__objc_classrefs: 0x380
   __DATA.__objc_superrefs: 0x2d0
-  __DATA.__objc_ivar: 0xa88
+  __DATA.__objc_ivar: 0xa8c
   __DATA.__data: 0x4b0
   __DATA.__bss: 0xc8
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpcap.A.dylib
-  Functions: 2474
-  Symbols:   4929
-  CStrings:  3300
+  Functions: 2475
+  Symbols:   4932
+  CStrings:  3301
 
Symbols:
+ -[RSMInterfaceListenerKIS deviceQueue]
+ -[RSMInterfaceListenerKIS initWithKISInterfaceManager:deviceQueue:]
+ OBJC_IVAR_$_RSMInterfaceListenerKIS._deviceQueue
+ _objc_msgSend$deviceQueue
+ _objc_msgSend$initWithKISInterfaceManager:deviceQueue:
- -[RSMInterfaceListenerKIS initWithKISInterfaceManager:]
- _objc_msgSend$initWithKISInterfaceManager:
Functions:
+ -[RSMInterfaceListenerKIS initWithKISInterfaceManager:deviceQueue:]
- -[RSMInterfaceListenerKIS initWithKISInterfaceManagerClient:]
+ -[RSMInterfaceListenerKIS deviceQueue]
~ -[RSMInterfaceListenerKIS .cxx_destruct] : 76 -> 92
~ _rsm_interface_listener_kis_create_with_manager : 384 -> 416
CStrings:
+ "-[RSMInterfaceListenerKIS initWithKISInterfaceManager:deviceQueue:]"
+ "@32@0:8^{device_interface_manager_t=^v^{device_interface_manager_functions_t}}16@24"
+ "initWithKISInterfaceManager:deviceQueue:"
- "-[RSMInterfaceListenerKIS initWithKISInterfaceManager:]"
- "initWithKISInterfaceManager:"
```
