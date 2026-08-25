## CoreAudio

> `/System/Library/Components/CoreAudio.component/Contents/MacOS/CoreAudio`

### Sections with Same Size but Changed Content

- `__TEXT.__dof_AudioTool`
- `__DATA_CONST.__const`
- `__DATA.__objc_selrefs`

```diff

-1456.701.0.0.0
+1456.703.0.0.0
   __TEXT.__text: 0x10ebe8
   __TEXT.__auth_stubs: 0x27c0
   __TEXT.__objc_stubs: 0x520
   __TEXT.__const: 0x7130
   __TEXT.__gcc_except_tab: 0x8970
   __TEXT.__cstring: 0x70c7
-  __TEXT.__oslogstring: 0xac94
+  __TEXT.__oslogstring: 0xb22a
   __TEXT.__objc_classname: 0x1
   __TEXT.__dlopen_cstrs: 0x8e
   __TEXT.__objc_methname: 0x2d5

   - /usr/lib/libobjc.A.dylib
   Functions: 3830
   Symbols:   862
-  CStrings:  1924
+  CStrings:  1939
 
CStrings:
+ "%25s:%-5d ASSERTION FAILURE [(!IsValid()) != 0 is false]: "
+ "%25s:%-5d ASSERTION FAILURE [(IsAnchorSampleTimeValid()) != 0 is false]: "
+ "%25s:%-5d ASSERTION FAILURE [(STIsGE(inSampleTime, 0.) && STIsLE(inSampleTime, kUnspecifiedSampleTime)) != 0 is false]: "
+ "%25s:%-5d ASSERTION FAILURE [(STIsGE(startSampleTime, 0.) && !STIsUnspecified(startSampleTime)) != 0 is false]: "
+ "%25s:%-5d ASSERTION FAILURE [(STIsGT(inSliceEndSampleTime, sliceStartSampleTime)) != 0 is false]: "
+ "%25s:%-5d ASSERTION FAILURE [(STIsLE(curRenderTime, sliceStartTime) && STIsLE(sliceEndTime, endRenderTime)) != 0 is false]: "
+ "%25s:%-5d ASSERTION FAILURE [(STIsLE(sliceStartTime, sliceEndTime)) != 0 is false]: "
+ "%25s:%-5d ASSERTION FAILURE [(mBufferCapacity == 0 || nBytes <= mBufferCapacity) != 0 is false]: "
+ "%25s:%-5d ASSERTION FAILURE [(mBufferMemory == __null) != 0 is false]: "
+ "%25s:%-5d ASSERTION FAILURE [(numberOfFrames > 0) != 0 is false]: "
+ "%25s:%-5d ASSERTION FAILURE [(outputFrames == nFrames) != 0 is false]: "
+ "%25s:%-5d ASSERTION FAILURE [(renderUntil <= SInt32(inNumberFrames)) != 0 is false]: "
+ "%25s:%-5d ASSERTION FAILURE [(srcABL.mNumberBuffers == destABL.mNumberBuffers) != 0 is false]: "
+ "%25s:%-5d ASSERTION FAILURE [(srcBuf->mNumberChannels == destBuf->mNumberChannels) != 0 is false]: "
+ "%25s:%-5d ASSERTION FAILURE [(tempABL->mNumberBuffers >= inbl->mNumberBuffers) != 0 is false]: "
+ "%25s:%-5d ASSERTION FAILURE [(tempABL->mNumberBuffers >= outbl->mNumberBuffers) != 0 is false]: "
- "%25s:%-5d ASSERTION FAILURE: "
```
