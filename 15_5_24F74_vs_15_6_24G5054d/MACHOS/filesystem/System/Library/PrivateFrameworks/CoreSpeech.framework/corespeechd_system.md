## corespeechd_system

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/corespeechd_system`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3405.29.3.0.0
-  __TEXT.__text: 0x65b8
-  __TEXT.__auth_stubs: 0x3b0
-  __TEXT.__objc_stubs: 0xf40
-  __TEXT.__objc_methlist: 0x7cc
+3406.12.1.0.0
+  __TEXT.__text: 0x6cb4
+  __TEXT.__auth_stubs: 0x3d0
+  __TEXT.__objc_stubs: 0xfe0
+  __TEXT.__objc_methlist: 0x7fc
   __TEXT.__const: 0x30
   __TEXT.__gcc_except_tab: 0x130
-  __TEXT.__objc_methname: 0x1a94
-  __TEXT.__cstring: 0xeac
-  __TEXT.__oslogstring: 0xc3e
+  __TEXT.__objc_methname: 0x1b56
+  __TEXT.__cstring: 0x100b
+  __TEXT.__oslogstring: 0xd9b
   __TEXT.__objc_classname: 0x16b
   __TEXT.__objc_methtype: 0x7e5
-  __TEXT.__unwind_info: 0x218
-  __DATA_CONST.__auth_got: 0x1e8
-  __DATA_CONST.__got: 0xe8
+  __TEXT.__unwind_info: 0x238
+  __DATA_CONST.__auth_got: 0x1f8
+  __DATA_CONST.__got: 0xf0
   __DATA_CONST.__const: 0x298
   __DATA_CONST.__cfstring: 0x80
   __DATA_CONST.__objc_classlist: 0x38

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x38
   __DATA.__objc_const: 0xbc0
-  __DATA.__objc_selrefs: 0x5f8
+  __DATA.__objc_selrefs: 0x620
   __DATA.__objc_ivar: 0x54
   __DATA.__objc_data: 0x230
   __DATA.__data: 0x180
   __DATA.__bss: 0x18
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
+  - /System/Library/Frameworks/CoreAudio.framework/Versions/A/CoreAudio
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/PrivateFrameworks/CoreSpeechFoundation.framework/Versions/A/CoreSpeechFoundation
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 143
-  Symbols:   97
-  CStrings:  468
+  Functions: 148
+  Symbols:   100
+  CStrings:  487
 
Symbols:
+ _AudioDeviceDuck
+ _OBJC_CLASS_$_NSURL
+ _xpc_dictionary_get_double
CStrings:
+ "%s CSLaunchDaemonAudioProvidingProxy %{public}p deallocated"
+ "%s Call AudioDeviceDuck with deviceID : %{public}u, duckedLevel %{public}f, rampDuration %{public}f"
+ "%s Calling AVVC setAlertSoundFromURL: %@, forType: %{public}lu"
+ "%s Failed to setAlertSoundFromURL with error: %{public}@"
+ "%s resetting AVVC"
+ "%s setAlertSoundFromURL elapsed time = %{public}lf"
+ "-[CSLaunchDaemonAudioProvidingProxy _handleDuckAudioDeviceMessage:messageBody:client:]"
+ "-[CSLaunchDaemonAudioProvidingProxy _handleResetAVVCMessage:messageBody:client:]"
+ "-[CSLaunchDaemonAudioProvidingProxy _handleSetAlertSoundFromURLMessage:messageBody:client:]"
+ "-[CSLaunchDaemonAudioProvidingProxy dealloc]"
+ "URLWithString:"
+ "_handleDuckAudioDeviceMessage:messageBody:client:"
+ "_handleResetAVVCMessage:messageBody:client:"
+ "_handleSetAlertSoundFromURLMessage:messageBody:client:"
+ "alertURL"
+ "audioDeviceID"
+ "duckLevel"
+ "rampDuration"
+ "setAlertSoundFromURL:forType:"
```
