## HomeKitDaemon

> `/System/Library/PrivateFrameworks/HomeKitDaemon.framework/Versions/A/HomeKitDaemon`

```diff

-1278.7.19.0.0
-  __TEXT.__text: 0xe74078
+1278.7.22.0.0
+  __TEXT.__text: 0xe74288
   __TEXT.__auth_stubs: 0x55d0
   __TEXT.__objc_methlist: 0x8aef4
   __TEXT.__dlopen_cstrs: 0x54

   __TEXT.__swift5_proto: 0x554
   __TEXT.__swift5_types: 0x2bc
   __TEXT.__swift5_capture: 0x1a78
-  __TEXT.__oslogstring: 0x1200c6
+  __TEXT.__oslogstring: 0x12011f
   __TEXT.__swift_as_entry: 0x360
   __TEXT.__swift_as_ret: 0x374
   __TEXT.__swift5_protos: 0xb8

   __TEXT.__unwind_info: 0x26db0
   __TEXT.__eh_frame: 0xb170
   __TEXT.__objc_classname: 0x1831b
-  __TEXT.__objc_methname: 0x1420b7
+  __TEXT.__objc_methname: 0x1420a2
   __TEXT.__objc_methtype: 0x29055
-  __TEXT.__objc_stubs: 0xb59e0
+  __TEXT.__objc_stubs: 0xb5980
   __DATA_CONST.__got: 0x6710
   __DATA_CONST.__const: 0x59f8
   __DATA_CONST.__objc_classlist: 0x44b8
   __DATA_CONST.__objc_catlist: 0x270
   __DATA_CONST.__objc_protolist: 0x1f58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x35a48
+  __DATA_CONST.__objc_selrefs: 0x35a40
   __DATA_CONST.__objc_protorefs: 0x658
   __DATA_CONST.__objc_superrefs: 0x3258
   __DATA_CONST.__objc_arraydata: 0x3270

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 53683
-  Symbols:   112390
+  Symbols:   112387
   CStrings:  76609
 
Symbols:
- _objc_msgSend$decodeXPCReadParams:
- _objc_msgSend$invokeCommand:fields:expectedValues:source:completion:
- _objc_msgSend$writeAttribute:value:timedWriteTimeout:completion:
Functions:
~ -[HMDHome(CHIP) invokeCommandWithNodeId:endpointId:clusterId:commandId:fields:timedInvokeTimeout:source:completion:] : 724 -> 908
~ -[HMDHome(CHIP) writeAttributeWithNodeId:endpointId:clusterId:attributeId:value:timedWriteTimeout:completion:] : 744 -> 932
~ -[HMDHome(CHIP) readAttributeWithNodeId:endpointId:clusterId:attributeId:params:completion:] : 620 -> 776
CStrings:
+ "%{public}@HMDHome+CHIP Matter API is not supported for accessories that use MatterPlugin"
- "decodeXPCReadParams:"
```
