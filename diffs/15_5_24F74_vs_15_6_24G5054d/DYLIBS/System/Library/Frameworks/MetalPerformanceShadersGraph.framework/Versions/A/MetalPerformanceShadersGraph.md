## MetalPerformanceShadersGraph

> `/System/Library/Frameworks/MetalPerformanceShadersGraph.framework/Versions/A/MetalPerformanceShadersGraph`

```diff

-5.4.11.0.0
-  __TEXT.__text: 0xf9370c
+5.6.2.0.0
+  __TEXT.__text: 0xf93718
   __TEXT.__auth_stubs: 0x2790
   __TEXT.__mpsgraph_init_: 0xc
   __TEXT.__objc_methlist: 0x68cc
   __TEXT.__const: 0x3d31c
-  __TEXT.__cstring: 0x8ab99
+  __TEXT.__cstring: 0x8ae31
   __TEXT.__gcc_except_tab: 0x596cc
   __TEXT.__oslogstring: 0x32
   __TEXT.__unwind_info: 0x27620

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libncurses.5.4.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 59453
+  Functions: 59452
   Symbols:   86058
   CStrings:  13741
 
Functions:
~ __ZNK4mlir3mps12_GLOBAL__N_137CanonicalizeMatMulExpandSqueezeBinaryINS0_5AddOpEE15matchAndRewriteENS0_9ReshapeOpERNS_15PatternRewriterE : 788 -> 768
~ _OUTLINED_FUNCTION_10 : 12 -> 36
~ _OUTLINED_FUNCTION_12 : 36 -> 12
~ _OUTLINED_FUNCTION_14 : 12 -> 20
~ _OUTLINED_FUNCTION_15 : 20 -> 32
- _OUTLINED_FUNCTION_17
~ __ZN4mlir21createRawElementsAttrENS_16RankedTensorTypeEN4llvm8ArrayRefIcEE : 328 -> 400
~ __Z10mpsFileLocPcS_ : 352 -> 364
~ -[MPSGraphExecutable initWithMPSGraphPackageAtURLCommon:compilationDescriptor:error:] : 10908 -> 10920
~ __ZNK4mlir3mps12_GLOBAL__N_112AddSubConsts15matchAndRewriteENS0_5AddOpERNS_15PatternRewriterE : 372 -> 376
~ __ZNK4mlir3mps12_GLOBAL__N_136CanonicalizeMatMulExpandSqueezeUnaryINS0_6ReluOpEE15matchAndRewriteENS0_9ReshapeOpERNS_15PatternRewriterE : 744 -> 680
~ __ZNK4mlir3mps12_GLOBAL__N_123FuseBinaryWithConstantsINS0_5AddOpELb1EE15matchAndRewriteES3_RNS_15PatternRewriterE : 400 -> 404
~ __ZNK4mlir3mps12_GLOBAL__N_123FuseBinaryWithConstantsINS0_10MultiplyOpELb1EE15matchAndRewriteES3_RNS_15PatternRewriterE : 400 -> 404
CStrings:
+ "150600"
+ "5.6.2"
- "150500"
- "5.4.11"
```
