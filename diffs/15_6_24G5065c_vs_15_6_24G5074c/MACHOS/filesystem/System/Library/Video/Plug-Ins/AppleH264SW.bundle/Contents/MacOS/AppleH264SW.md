## AppleH264SW

> `/System/Library/Video/Plug-Ins/AppleH264SW.bundle/Contents/MacOS/AppleH264SW`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-818.2.0.0.0
-  __TEXT.__text: 0x1ba434
+818.3.0.0.0
+  __TEXT.__text: 0x1ba420
   __TEXT.__auth_stubs: 0xab0
   __TEXT.__const: 0x15200
-  __TEXT.__cstring: 0x15b0
+  __TEXT.__cstring: 0x1512
   __TEXT.__gcc_except_tab: 0x90
   __TEXT.__unwind_info: 0xf68
   __TEXT.__eh_frame: 0x728

   - /usr/lib/libc++.1.dylib
   Functions: 1831
   Symbols:   324
-  CStrings:  325
+  CStrings:  323
 
Functions:
~ sub_7c3c : 836 -> 876
~ sub_8360 -> sub_8388 : 768 -> 780
~ sub_9254 -> sub_9288 : 432 -> 456
~ sub_35944 -> sub_35990 : 524 -> 488
~ sub_8e61c -> sub_8e644 : 212 -> 200
~ sub_8e78c -> sub_8e7a8 : 472 -> 448
~ sub_8e964 -> sub_8e968 : 472 -> 448
CStrings:
- "{OptimizedCabacDecoder::EndSliceBody} bitstream parsing error!!!!!!!!!!!!!!"
- "{OptimizedCabacDecoder::UpdateBitStreamPtr} bitstream parsing error!!!!!!!!!!!!!!"
```
