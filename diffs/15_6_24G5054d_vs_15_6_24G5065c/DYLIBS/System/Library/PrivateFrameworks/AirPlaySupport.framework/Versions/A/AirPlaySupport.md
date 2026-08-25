## AirPlaySupport

> `/System/Library/PrivateFrameworks/AirPlaySupport.framework/Versions/A/AirPlaySupport`

```diff

-870.8.1.0.0
-  __TEXT.__text: 0x6d5f4
+870.10.1.0.0
+  __TEXT.__text: 0x6d824
   __TEXT.__auth_stubs: 0x2b60
   __TEXT.__const: 0xd00
   __TEXT.__dlopen_cstrs: 0x54
   __TEXT.__gcc_except_tab: 0x1c4
-  __TEXT.__cstring: 0x1c255
+  __TEXT.__cstring: 0x1c4a1
   __TEXT.__unwind_info: 0x1238
   __TEXT.__objc_classname: 0x1
   __TEXT.__objc_methname: 0x330

   - /usr/lib/libobjc.A.dylib
   Functions: 1530
   Symbols:   3157
-  CStrings:  2729
+  CStrings:  2753
 
Symbols:
+ _FigSignalErrorAt3
- _FigSignalErrorAt
Functions:
~ _APSSharedRingBuffer_CreateWithBufferAndState : 568 -> 820
~ _APSSharedRingBuffer_Create : 928 -> 1032
~ _APSAPAPExtensionConvertLoudnessInfoDictLoudnessParametersToBBuf : 536 -> 696
~ _APSAudioFormatDescriptionCreateWithAudioFormatIndex : 624 -> 640
~ _APSAudioFormatDescriptionListCreate : 448 -> 476
CStrings:
+ "%s%s%s signalled err=%d (%s) (%s) at %s:%d"
+ "(Fig)"
+ "-108"
+ "-877"
+ "-878"
+ "-879"
+ "-880"
+ "APSAPAPExtensionLoudnessInfoUtils.c"
+ "APSAudioFormatDescription.c"
+ "APSAudioFormatDescriptionList.c"
+ "APSSharedRingBuffer.c"
+ "Could not allocate APSAudioFormatDescription"
+ "Could not allocate APSAudioFormatDescriptionList"
+ "Failed to create bufferMemObject"
+ "Failed to create stateMemObject"
+ "bufferMemory region maps to NULL"
+ "bufferMemorySize is zero"
+ "kCMBaseObjectError_AllocationFailed"
+ "kParamErr"
+ "loudness key missing"
+ "sample peak key missing"
+ "stateMemObject maps to NULL"
+ "stateMemoryLength < sizeof(RingState)"
+ "true peak key missing"
```
