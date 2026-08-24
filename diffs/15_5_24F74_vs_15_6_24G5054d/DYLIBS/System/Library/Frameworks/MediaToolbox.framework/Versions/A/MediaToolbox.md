## MediaToolbox

> `/System/Library/Frameworks/MediaToolbox.framework/Versions/A/MediaToolbox`

```diff

-3225.7.1.0.0
-  __TEXT.__text: 0x85f90c
+3235.8.2.0.0
+  __TEXT.__text: 0x85ffd0
   __TEXT.__auth_stubs: 0xa930
   __TEXT.__objc_methlist: 0x1c84
   __TEXT.__const: 0x1c610
   __TEXT.__gcc_except_tab: 0xe84
-  __TEXT.__oslogstring: 0x3f85f
-  __TEXT.__cstring: 0x5488f
+  __TEXT.__oslogstring: 0x3f91f
+  __TEXT.__cstring: 0x5490d
   __TEXT.__ustring: 0x1f8
   __TEXT.__dlopen_cstrs: 0xaa
-  __TEXT.__unwind_info: 0x10940
+  __TEXT.__unwind_info: 0x10948
   __TEXT.__eh_frame: 0x1a04
   __TEXT.__objc_classname: 0x763
   __TEXT.__objc_methname: 0x48cf
   __TEXT.__objc_methtype: 0x1b8e
   __TEXT.__objc_stubs: 0x45e0
   __DATA_CONST.__got: 0x2f88
-  __DATA_CONST.__const: 0x1d128
+  __DATA_CONST.__const: 0x1d148
   __DATA_CONST.__objc_classlist: 0x1d8
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arraydata: 0x30
   __AUTH_CONST.__auth_got: 0x54b0
   __AUTH_CONST.__const: 0x361e0
-  __AUTH_CONST.__cfstring: 0x4c320
+  __AUTH_CONST.__cfstring: 0x4c380
   __AUTH_CONST.__objc_const: 0x3ea8
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__objc_doubleobj: 0x10

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libnetwork.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 27914
-  Symbols:   12921
-  CStrings:  17438
+  Functions: 27920
+  Symbols:   12925
+  CStrings:  17443
 
Symbols:
+ _kFigAssetReaderExtractionOption_DecompressionProperties
+ _kFigEndpointStreamAudioEngineSampleBufferAttachmentKey_FlushRangeEnd
+ _kFigRenderPipelineProperty_DecompressionSessionProperties
+ _kVideoMediaConverter2Property_DecompressionSessionProperties
CStrings:
+ "<<<< FigBufferedAirPlayAudioChainSubPipeTranscode >>>> %s: [%p] %{public}s Found FlushRangeEnd sbuf %p, sending sample buffer marker with OPTS=%1.3f"
+ "<<<< FigStreamPlayer >>>> %s: [%p|%{public}s] <%p|%{public}s>: AbandonSync of new track %d [%.2f - %.2f buffered]; old track already ended"
+ "AssetReader_DecompressionProperties"
+ "DecompressionSessionProperties"
+ "FlushRangeEnd"
+ "bapspTranscode_processFlushRangeEndIfPresent"
- "<<<< FigStreamPlayer >>>> %s: [%p|%{public}s] <%p|%{public}s>: AbandonSync of new track %d; old track already ended"
```
