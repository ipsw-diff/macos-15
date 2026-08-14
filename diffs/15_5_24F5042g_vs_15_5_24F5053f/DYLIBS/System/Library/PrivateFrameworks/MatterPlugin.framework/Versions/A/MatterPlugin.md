## MatterPlugin

> `/System/Library/PrivateFrameworks/MatterPlugin.framework/Versions/A/MatterPlugin`

```diff

-49.6.11.0.0
-  __TEXT.__text: 0x4ad10
+49.6.13.0.0
+  __TEXT.__text: 0x4c370
   __TEXT.__auth_stubs: 0x5d0
-  __TEXT.__objc_methlist: 0x46a4
-  __TEXT.__const: 0xf0
-  __TEXT.__cstring: 0x11e0
-  __TEXT.__oslogstring: 0x502a
-  __TEXT.__gcc_except_tab: 0x1ce8
-  __TEXT.__unwind_info: 0x1180
-  __TEXT.__objc_classname: 0x9a1
-  __TEXT.__objc_methname: 0x74f1
-  __TEXT.__objc_methtype: 0x1536
-  __TEXT.__objc_stubs: 0x5900
+  __TEXT.__objc_methlist: 0x46dc
+  __TEXT.__const: 0xf8
+  __TEXT.__cstring: 0x11fd
+  __TEXT.__oslogstring: 0x5467
+  __TEXT.__gcc_except_tab: 0x1d20
+  __TEXT.__unwind_info: 0x1190
+  __TEXT.__objc_classname: 0x9a2
+  __TEXT.__objc_methname: 0x7781
+  __TEXT.__objc_methtype: 0x15d8
+  __TEXT.__objc_stubs: 0x5a00
   __DATA_CONST.__got: 0x460
   __DATA_CONST.__const: 0x210
   __DATA_CONST.__objc_classlist: 0x218
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1b18
+  __DATA_CONST.__objc_selrefs: 0x1b60
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x180
   __DATA_CONST.__objc_arraydata: 0x40
   __AUTH_CONST.__auth_got: 0x2f8
-  __AUTH_CONST.__const: 0x9a0
+  __AUTH_CONST.__const: 0xa00
   __AUTH_CONST.__cfstring: 0x18c0
-  __AUTH_CONST.__objc_const: 0x6708
+  __AUTH_CONST.__objc_const: 0x6798
   __AUTH_CONST.__objc_intobj: 0x438
   __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH.__objc_data: 0x14f0
-  __DATA.__objc_ivar: 0x368
+  __DATA.__objc_ivar: 0x36c
   __DATA.__data: 0x600
   __DATA.__bss: 0xf0
   __DATA.__common: 0x8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1637
-  Symbols:   3379
-  CStrings:  1963
+  Functions: 1644
+  Symbols:   3399
+  CStrings:  1996
 
Symbols:
+ -[MTRPluginClientConnection _deliverMessagePayloadToPrimaryResident:timeout:responseHandler:]
+ -[MTRPluginDeviceControllerRegistry _forceUpdateRunningModeForController:]
+ -[MTRPluginDeviceControllerRegistry devicesChangedForController:]
+ -[MTRPluginLocalClient _deviceForControllerUUID:nodeID:requestedViaDelegate:]
+ -[MTRPluginLocalClient _registerDevice:addedViaDelegate:]
+ -[MTRPluginLocalClient setTemporarilyRegisteredNodeIDs:]
+ -[MTRPluginLocalClient setTemporaryDeviceCleanupSource:]
+ -[MTRPluginLocalClient temporarilyRegisteredNodeIDs]
+ -[MTRPluginLocalClient temporaryDeviceCleanupSource]
+ -[MTRPluginProtobufOverModernTransport _sendMessageToPrimaryHomeHub:timeout:]
+ -[MTRPluginProtobufOverModernTransport _sendMessageToRemotePeer:peerDestination:timeout:]
+ -[MTRPluginProtobufOverModernTransport sendMessageToPrimaryHomeHub:timeout:]
+ -[MTRPluginProtobufOverModernTransport sendMessageToRemotePeer:peerDestination:timeout:]
+ -[MTRPluginRemoteClient sendMessageToHomeWithID:messageType:pbCodable:timeout:metrics:errorBlock:replyBlock:]
+ -[MTRPluginRemoteClient sendOnewayMessageToHomeWithID:messageType:pbCodable:timeout:]
+ -[MTRPluginResidentClientSession _sendMessageToHomeWithID:messageType:pbCodable:timeout:metric:errorBlock:replyBlock:]
+ -[MTRPluginServer _deliverMessageToDelegate:homeUUID:timeout:]
+ GCC_except_table22
+ GCC_except_table28
+ GCC_except_table31
+ GCC_except_table35
+ GCC_except_table39
+ GCC_except_table45
+ GCC_except_table53
+ OBJC_IVAR_$_MTRPluginLocalClient._temporarilyRegisteredNodeIDs
+ OBJC_IVAR_$_MTRPluginLocalClient._temporaryDeviceCleanupSource
+ _MTRPluginDefaultTimeoutKey
+ __109-[MTRPluginRemoteClient sendMessageToHomeWithID:messageType:pbCodable:timeout:metrics:errorBlock:replyBlock:]_block_invoke
+ __118-[MTRPluginResidentClientSession _sendMessageToHomeWithID:messageType:pbCodable:timeout:metric:errorBlock:replyBlock:]_block_invoke
+ __57-[MTRPluginLocalClient _registerDevice:addedViaDelegate:]_block_invoke
+ __62-[MTRPluginServer _deliverMessageToDelegate:homeUUID:timeout:]_block_invoke
+ __93-[MTRPluginClientConnection _deliverMessagePayloadToPrimaryResident:timeout:responseHandler:]_block_invoke
+ __OBJC_CLASS_PROTOCOLS_$_MTRPluginDeviceControllerRegistry
+ ___109-[MTRPluginRemoteClient sendMessageToHomeWithID:messageType:pbCodable:timeout:metrics:errorBlock:replyBlock:]_block_invoke
+ ___118-[MTRPluginResidentClientSession _sendMessageToHomeWithID:messageType:pbCodable:timeout:metric:errorBlock:replyBlock:]_block_invoke
+ ___57-[MTRPluginLocalClient _registerDevice:addedViaDelegate:]_block_invoke
+ ___62-[MTRPluginServer _deliverMessageToDelegate:homeUUID:timeout:]_block_invoke
+ ___77-[MTRPluginProtobufOverModernTransport _sendMessageToPrimaryHomeHub:timeout:]_block_invoke
+ ___89-[MTRPluginProtobufOverModernTransport _sendMessageToRemotePeer:peerDestination:timeout:]_block_invoke
+ ___93-[MTRPluginClientConnection _deliverMessagePayloadToPrimaryResident:timeout:responseHandler:]_block_invoke
+ ___block_descriptor_49_e8_32s40s_e5_v8?0l
+ ___block_descriptor_64_e8_32s40s48bs_e5_v8?0l
+ _objc_msgSend$_deliverMessagePayloadToPrimaryResident:timeout:responseHandler:
+ _objc_msgSend$_deliverMessageToDelegate:homeUUID:timeout:
+ _objc_msgSend$_deviceForControllerUUID:nodeID:requestedViaDelegate:
+ _objc_msgSend$_forceUpdateRunningModeForController:
+ _objc_msgSend$_registerDevice:addedViaDelegate:
+ _objc_msgSend$_sendMessageToHomeWithID:messageType:pbCodable:timeout:metric:errorBlock:replyBlock:
+ _objc_msgSend$_sendMessageToPrimaryHomeHub:timeout:
+ _objc_msgSend$_sendMessageToRemotePeer:peerDestination:timeout:
+ _objc_msgSend$connection:sendMessagePayloadToPrimaryResident:responseHandler:timeout:error:
+ _objc_msgSend$devices
+ _objc_msgSend$moveItemAtURL:toURL:error:
+ _objc_msgSend$sendMessage:homeUUID:timeout:error:
+ _objc_msgSend$sendMessageToHomeWithID:messageType:pbCodable:timeout:metrics:errorBlock:replyBlock:
+ _objc_msgSend$sendMessageToPrimaryHomeHub:timeout:
+ _objc_msgSend$sendMessageToRemotePeer:peerDestination:timeout:
+ _objc_msgSend$sendOnewayMessageToHomeWithID:messageType:pbCodable:timeout:
+ _objc_msgSend$setTemporarilyRegisteredNodeIDs:
+ _objc_msgSend$setTemporaryDeviceCleanupSource:
+ _objc_msgSend$temporarilyRegisteredNodeIDs
+ _objc_msgSend$temporaryDeviceCleanupSource
- -[MTRPluginClient registeredNodeIDs]
- -[MTRPluginClient setRegisteredNodeIDs:]
- -[MTRPluginClientConnection _deliverMessagePayloadToPrimaryResident:responseHandler:]
- -[MTRPluginLocalClient _deviceForControllerUUID:nodeID:]
- -[MTRPluginLocalClient _registerDevice:]
- -[MTRPluginProtobufOverModernTransport _sendMessageToPrimaryHomeHub:]
- -[MTRPluginProtobufOverModernTransport _sendMessageToRemotePeer:peerDestination:]
- -[MTRPluginProtobufOverModernTransport sendMessageToPrimaryHomeHub:]
- -[MTRPluginProtobufOverModernTransport sendMessageToRemotePeer:peerDestination:]
- -[MTRPluginRemoteClient sendMessageToHomeWithID:messageType:pbCodable:metrics:errorBlock:replyBlock:]
- -[MTRPluginRemoteClient sendOnewayMessageToHomeWithID:messageType:pbCodable:]
- -[MTRPluginResidentClientSession _sendMessageToHomeWithID:messageType:pbCodable:metric:errorBlock:replyBlock:]
- -[MTRPluginServer _deliverMessageToDelegate:homeUUID:]
- GCC_except_table26
- GCC_except_table30
- GCC_except_table38
- GCC_except_table50
- GCC_except_table56
- OBJC_IVAR_$_MTRPluginClient._registeredNodeIDs
- __101-[MTRPluginRemoteClient sendMessageToHomeWithID:messageType:pbCodable:metrics:errorBlock:replyBlock:]_block_invoke
- __110-[MTRPluginResidentClientSession _sendMessageToHomeWithID:messageType:pbCodable:metric:errorBlock:replyBlock:]_block_invoke
- __54-[MTRPluginServer _deliverMessageToDelegate:homeUUID:]_block_invoke
- __85-[MTRPluginClientConnection _deliverMessagePayloadToPrimaryResident:responseHandler:]_block_invoke
- ___101-[MTRPluginRemoteClient sendMessageToHomeWithID:messageType:pbCodable:metrics:errorBlock:replyBlock:]_block_invoke
- ___110-[MTRPluginResidentClientSession _sendMessageToHomeWithID:messageType:pbCodable:metric:errorBlock:replyBlock:]_block_invoke
- ___40-[MTRPluginLocalClient _registerDevice:]_block_invoke
- ___54-[MTRPluginServer _deliverMessageToDelegate:homeUUID:]_block_invoke
- ___69-[MTRPluginProtobufOverModernTransport _sendMessageToPrimaryHomeHub:]_block_invoke
- ___81-[MTRPluginProtobufOverModernTransport _sendMessageToRemotePeer:peerDestination:]_block_invoke
- ___85-[MTRPluginClientConnection _deliverMessagePayloadToPrimaryResident:responseHandler:]_block_invoke
- _objc_msgSend$_deliverMessagePayloadToPrimaryResident:responseHandler:
- _objc_msgSend$_deliverMessageToDelegate:homeUUID:
- _objc_msgSend$_deviceForControllerUUID:nodeID:
- _objc_msgSend$_registerDevice:
- _objc_msgSend$_sendMessageToHomeWithID:messageType:pbCodable:metric:errorBlock:replyBlock:
- _objc_msgSend$_sendMessageToPrimaryHomeHub:
- _objc_msgSend$_sendMessageToRemotePeer:peerDestination:
- _objc_msgSend$copyItemAtURL:toURL:error:
- _objc_msgSend$sendMessageToHomeWithID:messageType:pbCodable:metrics:errorBlock:replyBlock:
- _objc_msgSend$sendMessageToPrimaryHomeHub:
- _objc_msgSend$sendMessageToRemotePeer:peerDestination:
- _objc_msgSend$sendOnewayMessageToHomeWithID:messageType:pbCodable:
CStrings:
+ " => Device wasn't registered in temporary list, ignoring"
+ "%@  => *** Not cleaning up temporary device, as it's permanent now: %@"
+ "%@  => registering device: %@ addedViaDelegate: %@"
+ "%@  => registering temporary device: %@ addedViaDelegate: %@"
+ "%@  => unregistering temporary device: %@"
+ "%@ => Delivering message: %@ to delegate: %@ timeout: %f homeUUID: %@"
+ "%@ => Done cleaning up temporary nodeIDs: %@"
+ "%@ Cleaning up temporary nodeIDs: %@  (permanent ones: %@)"
+ "%@ Device controller delegate devices changed for controller UUID %@ devices count %lu"
+ "%@ Setting running mode for controller: %@ to local (forced pairing mode), unsuspending controller (devices count %lu)"
+ "%@ Setting running mode for controller: %@ to local, but no active devices, suspending controller (devices count %lu)"
+ "%@ Setting running mode for controller: %@ to local, resuming controller because we have active devices (devices count %lu)"
+ "%@ Setting running mode for controller: %@ to remote, suspending controller (devices count %lu)"
+ "%@ Setting running mode for controller: %@ to unknown, but no active devices, suspending controller (devices count %lu)"
+ "%@ Setting running mode for controller: %@ to unknown, resuming controller because we have active devices (devices count %lu)"
+ "%@ _forceUpdateRunningModeForController for controller %@"
+ "%@ _forceUpdateRunningModeForController found controller UUID %@ homeUUID %@ current running mode %@"
+ "<%@: %p xpc %p pid: %d, clientType: %@ registeredNodeIDs: %@>"
+ "@\"NSSet\""
+ "@36@0:8@16@24B32"
+ "B40@0:8@16@24d32"
+ "B40@0:8@16d24@?32"
+ "T@\"NSMutableSet\",&,V_temporarilyRegisteredNodeIDs"
+ "T@\"NSObject<OS_dispatch_source>\",&,V_temporaryDeviceCleanupSource"
+ "T@\"NSSet\",C,V_registeredNodeIDs"
+ "_deliverMessagePayloadToPrimaryResident:timeout:responseHandler:"
+ "_deliverMessageToDelegate:homeUUID:timeout:"
+ "_deviceForControllerUUID:nodeID:requestedViaDelegate:"
+ "_forceUpdateRunningModeForController:"
+ "_registerDevice:addedViaDelegate:"
+ "_sendMessageToHomeWithID:messageType:pbCodable:timeout:metric:errorBlock:replyBlock:"
+ "_sendMessageToPrimaryHomeHub:timeout:"
+ "_sendMessageToRemotePeer:peerDestination:timeout:"
+ "_temporarilyRegisteredNodeIDs"
+ "_temporaryDeviceCleanupSource"
+ "attributeCounter"
+ "connection:sendMessagePayloadToPrimaryResident:responseHandler:timeout:error:"
+ "controller:commissioneeHasReceivedNetworkCredentials:"
+ "devices"
+ "eventCounter"
+ "moveItemAtURL:toURL:error:"
+ "sendMessage:homeUUID:timeout:error:"
+ "sendMessageToHomeWithID:messageType:pbCodable:timeout:metrics:errorBlock:replyBlock:"
+ "sendMessageToPrimaryHomeHub:timeout:"
+ "sendMessageToRemotePeer:peerDestination:timeout:"
+ "sendOnewayMessageToHomeWithID:messageType:pbCodable:timeout:"
+ "setTemporarilyRegisteredNodeIDs:"
+ "setTemporaryDeviceCleanupSource:"
+ "temporarilyRegisteredNodeIDs"
+ "temporaryDeviceCleanupSource"
+ "v32@0:8@\"MTRDeviceController\"16@\"NSNumber\"24"
+ "v32@0:8@\"MTRPluginProtobufMessage\"16d24"
+ "v32@0:8@16d24"
+ "v40@0:8@\"MTRPluginProtobufMessage\"16@24d32"
+ "v40@0:8@16@24d32"
+ "v44@0:8@16i24@28d36"
+ "v68@0:8@16i24@28d36@44@?52@?60"
- "%@  => controller: %@ self.pluginClient.registeredNodeIDs: %@"
- "%@  => registering device: %@"
- "%@ Setting running mode for controller: %@ to local, unsuspending controller"
- "%@ Setting running mode for controller: %@ to remote, suspending controller"
- "%@ Setting running mode for controller: %@ to unknown, resuming controller"
- "<%@: %p xpc %p pid: %d, clientType: %@>"
- "B32@0:8@16@?24"
- "_deliverMessagePayloadToPrimaryResident:responseHandler:"
- "_deliverMessageToDelegate:homeUUID:"
- "_deviceForControllerUUID:nodeID:"
- "_registerDevice:"
- "_sendMessageToHomeWithID:messageType:pbCodable:metric:errorBlock:replyBlock:"
- "_sendMessageToPrimaryHomeHub:"
- "_sendMessageToRemotePeer:peerDestination:"
- "copyItemAtURL:toURL:error:"
- "eventCount"
- "reportCount"
- "sendMessageToHomeWithID:messageType:pbCodable:metrics:errorBlock:replyBlock:"
- "sendMessageToPrimaryHomeHub:"
- "sendMessageToRemotePeer:peerDestination:"
- "sendOnewayMessageToHomeWithID:messageType:pbCodable:"
- "v24@0:8@\"MTRPluginProtobufMessage\"16"
- "v32@0:8@\"MTRPluginProtobufMessage\"16@24"
- "v36@0:8@16i24@28"
```
