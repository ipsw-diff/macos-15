## MPSNDArray

> `/System/Library/Frameworks/MetalPerformanceShaders.framework/Versions/A/Frameworks/MPSNDArray.framework/Versions/A/MPSNDArray`

```diff

-128.5.2.0.0
-  __TEXT.__text: 0xdccb4
-  __TEXT.__auth_stubs: 0x950
-  __TEXT.__objc_methlist: 0x69e4
-  __TEXT.__const: 0x44880
-  __TEXT.__gcc_except_tab: 0x305c
-  __TEXT.__cstring: 0xbe66
-  __TEXT.__unwind_info: 0x1718
+128.6.1.0.0
+  __TEXT.__text: 0xe290c
+  __TEXT.__auth_stubs: 0x970
+  __TEXT.__objc_methlist: 0x69fc
+  __TEXT.__const: 0x448b0
+  __TEXT.__gcc_except_tab: 0x3364
+  __TEXT.__cstring: 0xc914
+  __TEXT.__unwind_info: 0x1760
   __TEXT.__eh_frame: 0x68
   __TEXT.__objc_classname: 0x1c3b
-  __TEXT.__objc_methname: 0x68aa
+  __TEXT.__objc_methname: 0x68d0
   __TEXT.__objc_methtype: 0x1e06
-  __TEXT.__objc_stubs: 0x2ee0
+  __TEXT.__objc_stubs: 0x2f40
   __DATA_CONST.__got: 0x2a0
-  __DATA_CONST.__const: 0xe090
+  __DATA_CONST.__const: 0xe690
   __DATA_CONST.__objc_classlist: 0x840
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1440
+  __DATA_CONST.__objc_selrefs: 0x1450
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x818
-  __AUTH_CONST.__auth_got: 0x4b8
+  __AUTH_CONST.__auth_got: 0x4c8
   __AUTH_CONST.__const: 0x3aa0
-  __AUTH_CONST.__cfstring: 0x5800
+  __AUTH_CONST.__cfstring: 0x5aa0
   __AUTH_CONST.__objc_const: 0xe5d8
   __AUTH.__objc_data: 0x1270
   __DATA.__objc_ivar: 0x66c
   __DATA.__data: 0x9c0
-  __DATA.__bss: 0xe8
+  __DATA.__bss: 0xf0
   __DATA_DIRTY.__objc_data: 0x4010
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2165
-  Symbols:   781
-  CStrings:  2501
+  Functions: 2172
+  Symbols:   783
+  CStrings:  2543
 
Symbols:
+ __ZNSt3__19to_stringEf
+ _puts
CStrings:
+ " -kernelType 0 -packed 3"
+ " -layout "
+ "-alpha "
+ "Default Encoder: Encoding 8x8 TEC based SDPA kernel\n"
+ "Default Encoder: Encoding vector based SDPA\n"
+ "Default Encoder: Failed, fall back to vector based SDPA kernel\n"
+ "Encoding 8x8 TEC based QuantizedSDPA kernel\n"
+ "Encoding failed, fall back to vector based QuantizedSDPA kernel\n"
+ "Encoding vector based QuantizedSDPA kernel\n"
+ "MPSNDArrayQuantizedScaledDotProductAttentionTest"
+ "MPSNDArrayScaledDotProductAttentionTest"
+ "Quantized tensor should be in int8"
+ "QuantizedSDPA: Q is not quantized, Batches=%lu, PromptSize=%lu, Contexts=%lu, Heads=%lu, Features=%lu, Q Datatype: %s, K Datatype: %s, V Datatype: %s, Mask Datatype: %s, KScale Datatype: %s, VScale Datatype: %s, Dest Datatype: %s\t"
+ "QuantizedSDPA: Q is quantized, Batches=%lu, PromptSize=%lu, Contexts=%lu, Heads=%lu, Features=%lu, Q Datatype: %s, K Datatype: %s, V Datatype: %s, Mask Datatype: %s, QScale Datatype: %s, KScale Datatype: %s, VScale Datatype: %s, Dest Datatype: %s\t"
+ "QuantizedSDPA: f16Ops=%f, f32Ops=%f, BytesRead=%f, BytesWritten=%f, OpsPerByte=%f\n"
+ "QuantizedSDPA: kernel %s is encoded, threadsPerGroup: (%lu, %lu, %lu), threadGroups: (%lu, %lu, %lu)\n"
+ "SDPA: Batches=%lu, PromptSize=%lu, Contexts=%lu, Heads=%lu, Features=%lu, Q Datatype: %s, K Datatype: %s, V Datatype: %s, Mask Datatype: %s, Dest Datatype: %s\t"
+ "SDPA: f16Ops=%f, f32Ops=%f, BytesRead=%f, BytesWritten=%f, OpsPerByte=%f\n"
+ "SDPA: kernel %s is encoded, threadsPerGroup: (%lu, %lu, %lu), threadGroups: (%lu, %lu, %lu)\n"
+ "Scale tensor should be in fp16 or fp32"
+ "Source tensor data type should be fp16 or fp32 when is it not quantized"
+ "UTF8String"
+ "batch size in the scale array should equal to 1 or match the quantized array"
+ "could not find index %lu in the placeholder list"
+ "destination must be float16 or float32"
+ "feature length in the scale array should be 1"
+ "maxThreadgroupMemoryLength"
+ "number of heads in the scale array should equal to 1 or match the quantized array"
+ "number of tokens in the scale array should equal to 1 or match the quantized array"
+ "per_tensor_quantized_sdpa_tile_fwd_16x16x16_doEdgeCheck"
+ "per_tensor_quantized_sdpa_tile_fwd_16x16x16_noEdgeCheck"
+ "per_tensor_quantized_sdpa_tile_fwd_8x8x8_doEdgeCheck"
+ "per_tensor_quantized_sdpa_tile_fwd_8x8x8_noEdgeCheck"
+ "quantized_sdpa_fwdNew"
+ "quantized_sdpa_tile_fwd_16x16x16_doEdgeCheck"
+ "quantized_sdpa_tile_fwd_16x16x16_noEdgeCheck"
+ "quantized_sdpa_tile_fwd_8x8x8_doEdgeCheck"
+ "quantized_sdpa_tile_fwd_8x8x8_noEdgeCheck"
+ "sdpa_tile_fwd_16x16x16_doEdgeCheck"
+ "sdpa_tile_fwd_16x16x16_noEdgeCheck"
+ "sdpa_tile_fwd_8x8x8_doEdgeCheck"
+ "sdpa_tile_fwd_8x8x8_noEdgeCheck"
+ "too much threadgroup memory usage. Fallback"
- "sdpa_tile_fwd"
```
