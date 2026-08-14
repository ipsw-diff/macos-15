## SiriCrossDeviceArbitration

> `/System/Library/PrivateFrameworks/SiriCrossDeviceArbitration.framework/Versions/A/SiriCrossDeviceArbitration`

```diff

-3405.7.2.0.0
-  __TEXT.__text: 0x33218
-  __TEXT.__auth_stubs: 0x660
-  __TEXT.__objc_methlist: 0x3004
+3405.11.1.0.0
+  __TEXT.__text: 0x332f0
+  __TEXT.__auth_stubs: 0x670
+  __TEXT.__objc_methlist: 0x302c
   __TEXT.__dlopen_cstrs: 0xc2
   __TEXT.__const: 0x1f0
   __TEXT.__gcc_except_tab: 0x420
-  __TEXT.__oslogstring: 0x527d
-  __TEXT.__cstring: 0x5998
-  __TEXT.__unwind_info: 0xcb8
+  __TEXT.__oslogstring: 0x52ad
+  __TEXT.__cstring: 0x59f2
+  __TEXT.__unwind_info: 0xcc0
   __TEXT.__objc_classname: 0x6a9
-  __TEXT.__objc_methname: 0x7c0c
+  __TEXT.__objc_methname: 0x7c6c
   __TEXT.__objc_methtype: 0x192e
-  __TEXT.__objc_stubs: 0x5ac0
-  __DATA_CONST.__got: 0x310
+  __TEXT.__objc_stubs: 0x5b20
+  __DATA_CONST.__got: 0x320
   __DATA_CONST.__const: 0x640
   __DATA_CONST.__objc_classlist: 0x170
   __DATA_CONST.__objc_protolist: 0x88
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1d08
+  __DATA_CONST.__objc_selrefs: 0x1d28
   __DATA_CONST.__objc_superrefs: 0x150
   __DATA_CONST.__objc_arraydata: 0xa8
-  __AUTH_CONST.__auth_got: 0x340
+  __AUTH_CONST.__auth_got: 0x348
   __AUTH_CONST.__const: 0xf60
-  __AUTH_CONST.__cfstring: 0x26a0
+  __AUTH_CONST.__cfstring: 0x26c0
   __AUTH_CONST.__objc_const: 0x5860
   __AUTH_CONST.__objc_intobj: 0x1c8
   __AUTH_CONST.__objc_dictobj: 0x78

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1202
-  Symbols:   3059
-  CStrings:  2573
+  Functions: 1204
+  Symbols:   3065
+  CStrings:  2580
 
Symbols:
+ +[SCDACoordinator audioHashFileBaseDirectory]
+ +[SCDACoordinator audioHashFilePath]
+ +[SCDACoordinator safelyGetAudioData]
+ GCC_except_table1112
+ _NSHomeDirectory
+ _objc_msgSend$audioHashFilePath
+ _objc_msgSend$safelyGetAudioData
+ _objc_msgSend$stringByAppendingPathComponent:
- GCC_except_table1113
- _safelyGetAudioData
CStrings:
+ "%s #scda election time remaining from a file is too old, Siri might respond from multiple devices"
+ "%s #scda endTime from a file is good, electionTimeRemaining=%f"
+ "%s BTLE audio hash base directory %{private}@"
+ "%s Voice trigger time not found in file."
+ "%s data=%@, voiceTriggerTimeRaw=%llu, electionTimeRemaining=%f"
+ "+[SCDACoordinator audioHashFileBaseDirectory]"
+ "+[SCDACoordinator audioHashFilePath]"
+ "+[SCDACoordinator safelyGetAudioData]"
+ "Library/VoiceTrigger"
+ "audioHashFileBaseDirectory"
+ "audioHashFilePath"
+ "stringByAppendingPathComponent:"
- "%s #scda endTime from a file is good, secondsSinceTrigger=%f"
- "%s #scda endTime from a file is too old, secondsSinceTrigger=%f; Siri might respond from multiple devices"
- "%s data=%@, voiceTriggerTimeRaw=%f"
- "%s data=%@, voiceTriggerTimeRaw=%llu, secondsSinceTrigger=%f"
- "SCDACoordinatorAudioHashFilePath"
```
