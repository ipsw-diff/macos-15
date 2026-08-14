## AGXMetalG14X

> `/System/Library/Extensions/AGXMetalG14X.bundle/Contents/MacOS/AGXMetalG14X`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__DATA.__data`

```diff

-327.1.0.0.0
-  __TEXT.__text: 0x6a7fd4
+327.5.0.0.0
+  __TEXT.__text: 0x6a7f4c
   __TEXT.__auth_stubs: 0xf80
   __TEXT.__objc_methlist: 0x8874
-  __TEXT.__const: 0xaea0
+  __TEXT.__const: 0xaeb0
   __TEXT.__gcc_except_tab: 0x7cb4
   __TEXT.__cstring: 0x6b71
   __TEXT.__oslogstring: 0x13b5
Functions:
~ __ZN3AGX23BlitDispatchContextGen2INS_4G14X8EncodersENS1_7ClassesENS1_10ObjClassesEE19renderMRCDownsampleEPK18IOGPUMetalResourcePNS1_7TextureE14_AGC3DBlitTypeRKNS_18FlagsConfigurationI13eAGXBlitFlagsEEjjjj : 2932 -> 2920
~ __ZN3AGX11FramebufferINS_4G14X8EncodersENS1_7ClassesENS1_10ObjClassesEEC2EP19AGXG14XFamilyDevicePNS1_13CommandBufferERKNS1_23FramebufferDriverConfigEjjb : 16284 -> 16180
~ __ZN3AGX17FramebufferGen3_1INS_4G14X8EncodersENS1_7ClassesENS1_10ObjClassesEE20finalizeStoreActionsEv : 564 -> 504
~ __ZNK3AGX17FramebufferGen3_2INS_4G14X8EncodersENS1_7ClassesENS1_10ObjClassesEE21assignRenderRegistersEP15AGXTACommandRecP15AGX3DCommandRecbbPNS_11FramebufferIS2_S3_S4_E21DepthReadWriteWAStateE : 1100 -> 1096
~ __ZN3AGX17FramebufferGen3_2INS_4G14X8EncodersENS1_7ClassesENS1_10ObjClassesEE27allocateDatabufferResourcesEPNS1_19DataBufferAllocatorE : 624 -> 628
~ __ZN3AGX17FramebufferGen3_3INS_4G14X8EncodersENS1_7ClassesENS1_10ObjClassesEEC2EP19AGXG14XFamilyDevicePNS1_13CommandBufferERKNS1_23FramebufferDriverConfigEjjb : 2284 -> 2276
~ __ZN3AGX13RenderContextINS_4G14X8EncodersENS1_7ClassesENS1_10ObjClassesEE19endRenderPassCommonEbbbbb : 8976 -> 9084
~ __ZN3AGX13RenderContextINS_4G14X8EncodersENS1_7ClassesENS1_10ObjClassesEE15beginRenderPassEv : 8252 -> 8248
~ -[AGXG14XFamilyRenderContext setStencilCleared] : 200 -> 140
~ -[AGXG14XFamilyRenderContext setDepthCleared] : 200 -> 140
~ -[AGXG14XFamilyRenderContext setStencilResolveTexture:slice:depthPlane:level:yInvert:] : 688 -> 684
~ -[AGXG14XFamilyRenderContext setDepthResolveTexture:slice:depthPlane:level:yInvert:] : 560 -> 564
~ -[AGXG14XFamilyRenderContext setStencilResolveTexture:slice:depthPlane:level:] : 688 -> 684
~ -[AGXG14XFamilyRenderContext setDepthResolveTexture:slice:depthPlane:level:] : 560 -> 564
~ __ZN3AGX13RenderContextINS_4G14X8EncodersENS1_7ClassesENS1_10ObjClassesEE15encodeDepthCopyEbb : 2372 -> 2440
~ -[AGXG14XFamilyRenderContext initWithCommandBuffer:descriptor:subEncoderIndex:framebuffer:] : 7924 -> 7920
```
