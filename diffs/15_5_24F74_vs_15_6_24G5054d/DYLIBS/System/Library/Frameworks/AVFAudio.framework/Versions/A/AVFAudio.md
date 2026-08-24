## AVFAudio

> `/System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio`

```diff

-684.603.0.0.0
-  __TEXT.__text: 0xe8358
+684.701.0.0.0
+  __TEXT.__text: 0xe838c
   __TEXT.__auth_stubs: 0x1dc0
   __TEXT.__objc_methlist: 0x4b0c
   __TEXT.__const: 0x788
   __TEXT.__dlopen_cstrs: 0x56
-  __TEXT.__gcc_except_tab: 0xe620
-  __TEXT.__cstring: 0xcef8
-  __TEXT.__oslogstring: 0x127c4
+  __TEXT.__gcc_except_tab: 0xe61c
+  __TEXT.__cstring: 0xcf6b
+  __TEXT.__oslogstring: 0x127d8
   __TEXT.__unwind_info: 0x4c80
   __TEXT.__objc_classname: 0x8f3
   __TEXT.__objc_methname: 0x99e8
Functions:
~ __ZN19AVVCRecordingEngineC2E27AVVoiceControllerClientType : 940 -> 944
~ +[AVVCAudioDeviceManager GetDevicesForActivationMode:outRecordDevice:outPlaybackDevice:] : 2020 -> 2052
~ ____ZN14ControllerImpl35configureAlertModeFromModeAndEngineE21AVVoiceActivationModeNSt3__110shared_ptrI19AVVCRecordingEngineEEU13block_pointerFviE_block_invoke_2 : 1756 -> 1772
CStrings:
+ "%25s:%-5d GetDevicesForActivationMode: HomeButtonPress/UIButtonPress/Dictation"
+ "%25s:%-5d configureAlertModeFromModeAndEngine: HomeButtonPress/MicrophoneUIButtonPress/Dictation"
- "%25s:%-5d GetDevicesForActivationMode: HomeButtonPress/UIButtonPress"
- "%25s:%-5d configureAlertModeFromModeAndEngine: HomeButtonPress/MicrophoneUIButtonPress"
```
