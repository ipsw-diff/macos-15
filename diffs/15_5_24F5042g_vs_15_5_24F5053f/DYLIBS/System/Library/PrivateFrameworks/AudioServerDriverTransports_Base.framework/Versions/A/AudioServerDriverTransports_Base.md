## AudioServerDriverTransports_Base

> `/System/Library/PrivateFrameworks/AudioServerDriverTransports_Base.framework/Versions/A/AudioServerDriverTransports_Base`

```diff

-250.2.0.0.0
-  __TEXT.__text: 0x49598
+250.3.0.0.0
+  __TEXT.__text: 0x48fd4
   __TEXT.__auth_stubs: 0xe60
-  __TEXT.__objc_methlist: 0x338c
-  __TEXT.__gcc_except_tab: 0x6370
-  __TEXT.__const: 0x55e
-  __TEXT.__cstring: 0x17a2
-  __TEXT.__oslogstring: 0x302e
-  __TEXT.__unwind_info: 0x2228
-  __TEXT.__objc_classname: 0x6dd
-  __TEXT.__objc_methname: 0x6ba7
+  __TEXT.__objc_methlist: 0x3314
+  __TEXT.__gcc_except_tab: 0x62e8
+  __TEXT.__const: 0x54e
+  __TEXT.__cstring: 0x1781
+  __TEXT.__oslogstring: 0x3052
+  __TEXT.__unwind_info: 0x21e0
+  __TEXT.__objc_classname: 0x6c8
+  __TEXT.__objc_methname: 0x6ae7
   __TEXT.__objc_methtype: 0x11be
-  __TEXT.__objc_stubs: 0x6420
+  __TEXT.__objc_stubs: 0x6340
   __DATA_CONST.__got: 0x2d8
   __DATA_CONST.__const: 0x520
-  __DATA_CONST.__objc_classlist: 0x1a8
+  __DATA_CONST.__objc_classlist: 0x1a0
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0xb0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1cb8
+  __DATA_CONST.__objc_selrefs: 0x1c78
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x160
   __DATA_CONST.__objc_arraydata: 0x60
   __AUTH_CONST.__auth_got: 0x748
-  __AUTH_CONST.__const: 0x770
-  __AUTH_CONST.__cfstring: 0x1880
-  __AUTH_CONST.__objc_const: 0x5268
+  __AUTH_CONST.__const: 0x740
+  __AUTH_CONST.__cfstring: 0x1860
+  __AUTH_CONST.__objc_const: 0x5168
   __AUTH_CONST.__objc_intobj: 0x288
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH.__objc_data: 0x1090
-  __DATA.__objc_ivar: 0x2f8
+  __AUTH.__objc_data: 0x1040
+  __DATA.__objc_ivar: 0x2f0
   __DATA.__data: 0x8b8
   __DATA.__bss: 0x98
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1836
-  Symbols:   3882
-  CStrings:  2120
+  Functions: 1823
+  Symbols:   3852
+  CStrings:  2105
 
Symbols:
- -[ASDTAudioDevice doTerminate]
- -[ASDTAudioDevice performTerminate]
- -[ASDTAudioDevice setTerminated:]
- -[ASDTAudioDevice terminate]
- -[ASDTAudioDevice terminated]
- -[ASDTDeviceManager terminateDevice:]
- -[MockASDTSystemStatus publishMicrophoneEnabled:]
- -[MockASDTSystemStatus publishedEnabled]
- -[MockASDTSystemStatus setPublishedEnabled:]
- OBJC_IVAR_$_ASDTAudioDevice._terminated
- OBJC_IVAR_$_MockASDTSystemStatus._publishedEnabled
- _OBJC_CLASS_$_MockASDTSystemStatus
- _OBJC_METACLASS_$_MockASDTSystemStatus
- __OBJC_$_INSTANCE_METHODS_MockASDTSystemStatus
- __OBJC_$_INSTANCE_VARIABLES_MockASDTSystemStatus
- __OBJC_$_PROP_LIST_MockASDTSystemStatus
- __OBJC_CLASS_RO_$_MockASDTSystemStatus
- __OBJC_METACLASS_RO_$_MockASDTSystemStatus
- ___28-[ASDTAudioDevice terminate]_block_invoke
- ___56-[ASDTDeviceManager ioServiceWillTerminate:withManager:]_block_invoke
- ___block_descriptor_64_ea8_32s40s48r56w_e5_v8?0l
- ___copy_helper_block_ea8_32s40s48r56w
- ___destroy_helper_block_ea8_32s40s48r56w
- _objc_msgSend$doTerminate
- _objc_msgSend$performTerminate
- _objc_msgSend$setPublishedEnabled:
- _objc_msgSend$setTerminated:
- _objc_msgSend$terminate
- _objc_msgSend$terminateDevice:
- _objc_msgSend$terminated
CStrings:
+ "%@: Cannot StartIO: device is sleeping."
+ "%@: Terminate notification incoming for '%@'."
+ "250.3"
- "%@: %@ Terminated."
- "%@: Cannot StartIO: device %s."
- "250.2"
- "MockASDTSystemStatus"
- "TB,N,V_publishedEnabled"
- "TB,N,V_terminated"
- "Terminate %@"
- "_publishedEnabled"
- "_terminated"
- "doTerminate"
- "performTerminate"
- "publishedEnabled"
- "setPublishedEnabled:"
- "setTerminated:"
- "sleeping"
- "terminate"
- "terminateDevice:"
- "terminated"
```
