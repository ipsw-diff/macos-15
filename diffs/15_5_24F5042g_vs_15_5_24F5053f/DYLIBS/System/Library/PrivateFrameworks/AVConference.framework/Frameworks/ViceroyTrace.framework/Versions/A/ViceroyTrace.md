## ViceroyTrace

> `/System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ViceroyTrace.framework/Versions/A/ViceroyTrace`

```diff

-2115.2.1.0.0
-  __TEXT.__text: 0xa16f4
+2115.4.1.0.0
+  __TEXT.__text: 0xa176c
   __TEXT.__auth_stubs: 0xc10
-  __TEXT.__objc_methlist: 0x85d0
+  __TEXT.__objc_methlist: 0x85b0
   __TEXT.__const: 0x21a0
-  __TEXT.__cstring: 0xcd0b
-  __TEXT.__oslogstring: 0xc18d
+  __TEXT.__cstring: 0xcd40
+  __TEXT.__oslogstring: 0xc1fc
   __TEXT.__gcc_except_tab: 0x354
   __TEXT.__dlopen_cstrs: 0x4e
-  __TEXT.__unwind_info: 0x14f0
+  __TEXT.__unwind_info: 0x14e0
   __TEXT.__eh_frame: 0x48
   __TEXT.__objc_classname: 0x501
-  __TEXT.__objc_methname: 0x19cd3
-  __TEXT.__objc_methtype: 0x20f0
-  __TEXT.__objc_stubs: 0xde00
+  __TEXT.__objc_methname: 0x19cf9
+  __TEXT.__objc_methtype: 0x2107
+  __TEXT.__objc_stubs: 0xdde0
   __DATA_CONST.__got: 0x210
   __DATA_CONST.__const: 0x4c0
   __DATA_CONST.__objc_classlist: 0x1b0
   __DATA_CONST.__objc_protolist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3e70
+  __DATA_CONST.__objc_selrefs: 0x3e68
   __DATA_CONST.__objc_superrefs: 0x178
   __DATA_CONST.__objc_arraydata: 0x210
   __AUTH_CONST.__auth_got: 0x618
   __AUTH_CONST.__const: 0xb30
-  __AUTH_CONST.__cfstring: 0xcd60
-  __AUTH_CONST.__objc_const: 0x153b0
+  __AUTH_CONST.__cfstring: 0xcda0
+  __AUTH_CONST.__objc_const: 0x153d0
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_intobj: 0x3f0
   __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH.__objc_data: 0x1090
   __AUTH.__data: 0x30
-  __DATA.__objc_ivar: 0x1e30
+  __DATA.__objc_ivar: 0x1e34
   __DATA.__data: 0x628
   __DATA.__bss: 0xb8
   __DATA.__common: 0x23

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 3733
-  Symbols:   7892
-  CStrings:  6932
+  Functions: 3731
+  Symbols:   7890
+  CStrings:  6935
 
Symbols:
+ -[VCAggregatorFaceTime dispatchedUpdateRoleModeTransport:deviceRole:transportType:isInitiator:isWalkieTalkieMode:]
+ OBJC_IVAR_$_VCAggregator._isWalkieTalkieMode
+ __62-[VCAggregatorFaceTime processEventWithCategory:type:payload:]_block_invoke
+ __62-[VCAggregatorFaceTime processEventWithCategory:type:payload:]_block_invoke_2
+ ___block_descriptor_58_e8_32o40o_e5_v8?0l
+ _objc_msgSend$dispatchedUpdateRoleModeTransport:deviceRole:transportType:isInitiator:isWalkieTalkieMode:
- -[VCAggregatorFaceTime updateRoleModeTransport:deviceRole:transportType:isInitiator:]
- -[VCRelayData isRelayDeviceRole:]
- -[VCVideoFECData updateWithPayload:blockFecLevels:]
- ___62-[VCAggregatorFaceTime processEventWithCategory:type:payload:]_block_invoke_5
- ___85-[VCAggregatorFaceTime updateRoleModeTransport:deviceRole:transportType:isInitiator:]_block_invoke
- ___block_descriptor_47_e8_32o_e5_v8?0l
- _objc_msgSend$isRelayDeviceRole:
- _objc_msgSend$updateWithPayload:blockFecLevels:
CStrings:
+ " [%s] %s:%d VCAggregator: Current call has mode=%d, role=%d, transport=%d, initiator=%d, isWalkieTalkieMode=%d"
+ "-[VCAggregatorFaceTime dispatchedUpdateRoleModeTransport:deviceRole:transportType:isInitiator:isWalkieTalkieMode:]"
+ "IsRelayDeviceRole"
+ "IsWalkieTalkieMode"
+ "dispatchedUpdateRoleModeTransport:deviceRole:transportType:isInitiator:isWalkieTalkieMode:"
+ "v36@0:8S16S20S24B28B32"
- "-[VCAggregatorFaceTime updateRoleModeTransport:deviceRole:transportType:isInitiator:]_block_invoke"
- "isRelayDeviceRole:"
- "updateWithPayload:blockFecLevels:"
```
