## Shared Screen Viewer

> `/System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Support/Shared Screen Viewer.app/Contents/MacOS/Shared Screen Viewer`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methtype`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_classrefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_floatobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-709.5.2.0.0
-  __TEXT.__text: 0x108370
+709.6.2.0.0
+  __TEXT.__text: 0x109c28
   __TEXT.__auth_stubs: 0x2420
-  __TEXT.__objc_stubs: 0x189c0
-  __TEXT.__objc_methlist: 0xd840
+  __TEXT.__objc_stubs: 0x18b00
+  __TEXT.__objc_methlist: 0xd8d8
   __TEXT.__objc_classname: 0xcea
-  __TEXT.__objc_methname: 0x23098
+  __TEXT.__objc_methname: 0x2330f
   __TEXT.__objc_methtype: 0x5dfe
-  __TEXT.__cstring: 0x27b29
-  __TEXT.__oslogstring: 0x135ad
+  __TEXT.__cstring: 0x27db2
   __TEXT.__const: 0x3340
+  __TEXT.__oslogstring: 0x1384d
   __TEXT.__gcc_except_tab: 0xd90
   __TEXT.__ustring: 0x126
-  __TEXT.__unwind_info: 0x2578
+  __TEXT.__unwind_info: 0x2598
   __DATA_CONST.__auth_got: 0x1220
-  __DATA_CONST.__got: 0x930
+  __DATA_CONST.__got: 0x940
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__const: 0x1498
-  __DATA_CONST.__cfstring: 0x6e20
+  __DATA_CONST.__cfstring: 0x6e60
   __DATA_CONST.__objc_classlist: 0x2d0
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x1b8

   __DATA_CONST.__objc_intobj: 0xf0
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA_CONST.__objc_floatobj: 0x10
-  __DATA.__objc_const: 0x111e0
-  __DATA.__objc_selrefs: 0x7f50
-  __DATA.__objc_ivar: 0xf1c
+  __DATA.__objc_const: 0x11270
+  __DATA.__objc_selrefs: 0x7fc0
+  __DATA.__objc_ivar: 0xf24
   __DATA.__objc_data: 0x1c20
   __DATA.__data: 0x1750
   __DATA.__bss: 0x724

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 4960
-  Symbols:   896
-  CStrings:  11147
+  Functions: 4979
+  Symbols:   898
+  CStrings:  11186
 
Symbols:
+ _kODAttributeTypeAllTypes
+ _kODAttributeTypeUniqueID
CStrings:
+ "%@, minimumEncryptionLevel: %lu, shouldGetUserInfo: %d, controlType: %ld, sessionSelectionAction: %ld, panningMode: %ld, screenQualityMode: %ld, maxSize: %@, restoreWindowFrame: %@, selectedScreen: %lu, scalingMode: %d, shouldCurtainScreen: %d, shouldSharePasteboard: %d, shouldFallbackToObserve: %d, authMethod: %ld, hints: %@, videoEncodings:%@, openInFullScreen: %d, showConnectionProgress: %d, skipUserPassDialogIfPossible: %d, recoveryAction: %ld, noReconnect: %d, sourceAppWindowRect: %@, windowAlignment: %ld, numVirtualDisplays: %ld, hdr: %d, displayID: %u, inviterAppIsMessages: %d, idsDeviceAudioStreamPausedAtStart: %d"
+ "-[ODHelper localUserRecordByShortName:]"
+ "-[ODHelper localUserUIDs]"
+ "-[ODHelper newLocalUserWithName:attributes:password:]"
+ "-[ODHelper setARDPrivileges:forUserRecord:]"
+ "-[SSSession setDeviceAudioStreamPaused:]"
+ "Done initializing the streams, pause audio flag: %d"
+ "TB,N,GisDeviceAudioStreamPaused"
+ "TB,N,GisDeviceAudioStreamPaused,V_deviceAudioStreamPaused"
+ "TB,N,V_idsDeviceAudioStreamPausedAtStart"
+ "_deviceAudioStreamPaused"
+ "_idsDeviceAudioStreamPausedAtStart"
+ "changePassword error %s"
+ "changePassword:toPassword:error:"
+ "createRecordWithRecordType error %s"
+ "createRecordWithRecordType:name:attributes:error:"
+ "created user %s"
+ "device audio not active"
+ "device audio state is already %d"
+ "deviceAudioStreamPaused"
+ "idsDeviceAudioStreamPausedAtStart"
+ "ignore - session: %p isSessionTerminated %d"
+ "isDeviceAudioStreamPaused"
+ "isDeviceAudioStreamSupported"
+ "localUserRecordByShortName:"
+ "localUserUIDs"
+ "naprivs"
+ "newLocalUserWithName:attributes:password:"
+ "no record name"
+ "pause"
+ "recordWithRecordType error %s"
+ "setARDPrivileges:forUserRecord:"
+ "setDeviceAudioStreamPaused %d"
+ "setDeviceAudioStreamPaused:"
+ "setIdsDeviceAudioStreamPausedAtStart:"
+ "setValue:forAttribute: error %s"
+ "setValue:forAttribute:error:"
+ "synchronizeAndReturnError %s"
+ "synchronizeAndReturnError:"
+ "unable to create new user"
+ "unable to set new user password"
- "%@, minimumEncryptionLevel: %lu, shouldGetUserInfo: %d, controlType: %ld, sessionSelectionAction: %ld, panningMode: %ld, screenQualityMode: %ld, maxSize: %@, restoreWindowFrame: %@, selectedScreen: %lu, scalingMode: %d, shouldCurtainScreen: %d, shouldSharePasteboard: %d, shouldFallbackToObserve: %d, authMethod: %ld, hints: %@, videoEncodings:%@, openInFullScreen: %d, showConnectionProgress: %d, skipUserPassDialogIfPossible: %d, recoveryAction: %ld, noReconnect: %d, sourceAppWindowRect: %@, windowAlignment: %ld, numVirtualDisplays: %ld, hdr: %d, displayID: %u, inviterAppIsMessages: %d"
- "done initializing streams"
```
