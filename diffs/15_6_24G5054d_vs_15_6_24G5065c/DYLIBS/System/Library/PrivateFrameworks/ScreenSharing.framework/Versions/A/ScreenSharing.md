## ScreenSharing

> `/System/Library/PrivateFrameworks/ScreenSharing.framework/Versions/A/ScreenSharing`

```diff

-714.5.1.0.0
-  __TEXT.__text: 0x11610c
+714.6.2.0.0
+  __TEXT.__text: 0x1179c4
   __TEXT.__auth_stubs: 0x2930
-  __TEXT.__objc_methlist: 0xdea8
-  __TEXT.__cstring: 0x29f30
+  __TEXT.__objc_methlist: 0xdf40
+  __TEXT.__cstring: 0x2a1b9
   __TEXT.__const: 0x33d0
-  __TEXT.__oslogstring: 0x13e37
+  __TEXT.__oslogstring: 0x140d7
   __TEXT.__gcc_except_tab: 0xf0c
   __TEXT.__ustring: 0x166
-  __TEXT.__unwind_info: 0x28c8
+  __TEXT.__unwind_info: 0x28e8
   __TEXT.__objc_classname: 0xe26
-  __TEXT.__objc_methname: 0x2465a
+  __TEXT.__objc_methname: 0x248d1
   __TEXT.__objc_methtype: 0x5d13
-  __TEXT.__objc_stubs: 0x19e80
-  __DATA_CONST.__got: 0xbc0
+  __TEXT.__objc_stubs: 0x19fc0
+  __DATA_CONST.__got: 0xbd0
   __DATA_CONST.__const: 0x5b0
   __DATA_CONST.__objc_classlist: 0x320
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x1b8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x84c0
+  __DATA_CONST.__objc_selrefs: 0x8530
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x300
   __DATA_CONST.__objc_arraydata: 0x3b8
   __AUTH_CONST.__auth_got: 0x14a8
   __AUTH_CONST.__const: 0x1510
-  __AUTH_CONST.__cfstring: 0x7840
-  __AUTH_CONST.__objc_const: 0x12100
+  __AUTH_CONST.__cfstring: 0x7880
+  __AUTH_CONST.__objc_const: 0x12190
   __AUTH_CONST.__objc_intobj: 0xf0
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_floatobj: 0x10
   __AUTH.__objc_data: 0x1ef0
   __AUTH.__data: 0x18
-  __DATA.__objc_ivar: 0x100c
+  __DATA.__objc_ivar: 0x1014
   __DATA.__data: 0x1770
   __DATA.__bss: 0x7bc
   __DATA.__common: 0x2

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 5301
-  Symbols:   11624
-  CStrings:  11691
+  Functions: 5320
+  Symbols:   11650
+  CStrings:  11730
 
Symbols:
+ -[ODHelper localUserRecordByShortName:]
+ -[ODHelper localUserUIDs]
+ -[ODHelper newLocalUserWithName:attributes:password:]
+ -[ODHelper setARDPrivileges:forUserRecord:]
+ -[SSConnectionOptions idsDeviceAudioStreamPausedAtStart]
+ -[SSConnectionOptions setIdsDeviceAudioStreamPausedAtStart:]
+ -[SSSession isDeviceAudioStreamPaused]
+ -[SSSession isDeviceAudioStreamSupported]
+ -[SSSession setDeviceAudioStreamPaused:]
+ -[SSSessionView isDeviceAudioStreamPaused]
+ -[SSSessionView isDeviceAudioStreamSupported]
+ -[SSSessionView setDeviceAudioStreamPaused:]
+ GCC_except_table297
+ GCC_except_table298
+ GCC_except_table306
+ GCC_except_table404
+ GCC_except_table405
+ GCC_except_table740
+ GCC_except_table741
+ GCC_except_table742
+ GCC_except_table768
+ GCC_except_table769
+ OBJC_IVAR_$_SSConnectionOptions._idsDeviceAudioStreamPausedAtStart
+ OBJC_IVAR_$_SSSession._deviceAudioStreamPaused
+ _kODAttributeTypeAllTypes
+ _kODAttributeTypeUniqueID
+ _objc_msgSend$changePassword:toPassword:error:
+ _objc_msgSend$createRecordWithRecordType:name:attributes:error:
+ _objc_msgSend$idsDeviceAudioStreamPausedAtStart
+ _objc_msgSend$isDeviceAudioStreamPaused
+ _objc_msgSend$isDeviceAudioStreamSupported
+ _objc_msgSend$pause
+ _objc_msgSend$setDeviceAudioStreamPaused:
+ _objc_msgSend$setIdsDeviceAudioStreamPausedAtStart:
+ _objc_msgSend$setValue:forAttribute:error:
+ _objc_msgSend$synchronizeAndReturnError:
- GCC_except_table294
- GCC_except_table295
- GCC_except_table303
- GCC_except_table401
- GCC_except_table402
- GCC_except_table730
- GCC_except_table731
- GCC_except_table732
- GCC_except_table763
- GCC_except_table764
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
