## MediaRemote

> `/System/Library/PrivateFrameworks/MediaRemote.framework/Versions/A/MediaRemote`

```diff

-4024.600.5.0.0
-  __TEXT.__text: 0x2dd7a4
+4024.600.6.0.0
+  __TEXT.__text: 0x2de50c
   __TEXT.__auth_stubs: 0x13a0
   __TEXT.__objc_methlist: 0x2848c
   __TEXT.__const: 0x4f8
-  __TEXT.__cstring: 0x292ea
+  __TEXT.__cstring: 0x2939e
   __TEXT.__oslogstring: 0xbc11
   __TEXT.__gcc_except_tab: 0x5964
   __TEXT.__ustring: 0x12

   __DATA_CONST.__objc_arraydata: 0x228
   __AUTH_CONST.__auth_got: 0x9e0
   __AUTH_CONST.__const: 0x9470
-  __AUTH_CONST.__cfstring: 0x1fc20
+  __AUTH_CONST.__cfstring: 0x1fcc0
   __AUTH_CONST.__objc_const: 0x41938
   __AUTH_CONST.__objc_intobj: 0x498
   __AUTH_CONST.__objc_arrayobj: 0x150

   - /usr/lib/libobjc.A.dylib
   Functions: 19065
   Symbols:   32763
-  CStrings:  17360
+  CStrings:  17365
 
Functions:
~ -[MRAVEndpoint volumeCapabilities] : 72 -> 968
~ -[MRAVEndpoint setOutputDeviceVolume:outputDevice:details:queue:completion:] : 1220 -> 1232
~ -[MRAVEndpoint volume] : 72 -> 804
~ _OUTLINED_FUNCTION_12 -> _OUTLINED_FUNCTION_10 : 32 -> 16
~ _OUTLINED_FUNCTION_17 -> _OUTLINED_FUNCTION_15 : 12 -> 16
~ _OUTLINED_FUNCTION_20 -> _OUTLINED_FUNCTION_18 : 16 -> 24
~ _OUTLINED_FUNCTION_21 -> _OUTLINED_FUNCTION_22 : 12 -> 16
~ -[MRAVEndpoint _initiatorStringWithInitiator:uid:] : 188 -> 192
~ -[MRAVEndpoint migrateToOrSetOutputDevices:initiator:withReplyQueue:completion:] : 1720 -> 1716
~ -[MRAVEndpoint performMigrationToOutputDevices:request:initiator:queue:completion:] : 3244 -> 3236
~ -[MRAVEndpoint translateClusterUIDIfNeeded:] : 400 -> 404
~ -[MRAVEndpoint volumeControlCapabilitiesForOutputDeviceUID:] : 124 -> 1000
~ -[MRAVEndpoint volumeForOutputDeviceUID:] : 132 -> 1028
~ -[MRAVEndpoint volumeMutedForOutputDeviceUID:] : 124 -> 140
~ -[MRAVEndpoint _willStartingPlaybackToOutputDeviceInterruptPlayback:duration:requestID:queue:completion:] : 2116 -> 2108
~ __105-[MRAVEndpoint _willStartingPlaybackToOutputDeviceInterruptPlayback:duration:requestID:queue:completion:]_block_invoke.720 -> __105-[MRAVEndpoint _willStartingPlaybackToOutputDeviceInterruptPlayback:duration:requestID:queue:completion:]_block_invoke.735 : 256 -> 248
~ __64-[MRAVEndpoint requestGroupSessionWithDetails:queue:completion:]_block_invoke.cold.1 : 244 -> 252
~ __79-[MRAVEndpoint adjustOutputDeviceVolume:outputDevice:details:queue:completion:]_block_invoke.cold.1 : 240 -> 248
~ __68-[MRAVEndpoint modifyTopologyWithRequest:withReplyQueue:completion:]_block_invoke.cold.1 : 248 -> 256
CStrings:
+ "Endpoint.volumeCapabilities"
+ "Endpoint.volumeControlCapabilitiesForOutputDeviceUID"
+ "Endpoint.volumeForOutputDeviceUID"
+ "endpoint=%@, outputDevice=%@, volume=%lf"
+ "endpoint=%@, volume=%lf"
```
