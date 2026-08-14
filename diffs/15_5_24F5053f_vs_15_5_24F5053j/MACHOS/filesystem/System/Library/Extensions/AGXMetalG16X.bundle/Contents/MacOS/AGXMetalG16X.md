## AGXMetalG16X

> `/System/Library/Extensions/AGXMetalG16X.bundle/Contents/MacOS/AGXMetalG16X`

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
-  __TEXT.__text: 0x6ce8ec
+327.5.0.0.0
+  __TEXT.__text: 0x6ce900
   __TEXT.__auth_stubs: 0xfb0
   __TEXT.__objc_methlist: 0x8a6c
-  __TEXT.__const: 0xc500
+  __TEXT.__const: 0xc510
   __TEXT.__gcc_except_tab: 0x8870
   __TEXT.__cstring: 0x73d4
   __TEXT.__oslogstring: 0x143d
Functions:
~ __ZN3AGX19BlitDispatchContextINS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE13renderTextureEPKPK18IOGPUMetalResourcePNS1_7TextureESC_SA_SC_RKNS_18FlagsConfigurationI13eAGXBlitFlagsEEjPKNS5_10BlitRegionEj : 2868 -> 2896
~ __ZN3AGX19BlitDispatchContextINS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE8render3DEPKPK18IOGPUMetalResourcePNS1_7TextureESA_SC_yPKvmRKNS5_12Blit3DConfigERKNS_18FlagsConfigurationI13eAGXBlitFlagsEE : 2460 -> 2452
~ __ZN3AGX23BlitDispatchContextGen2INS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE19renderMRCDownsampleEPK18IOGPUMetalResourcePNS1_7TextureE14_AGC3DBlitTypeRKNS_18FlagsConfigurationI13eAGXBlitFlagsEEjjjj : 2560 -> 2556
~ __ZN3AGX11FramebufferINS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEEC2EP19AGXG16XFamilyDevicePNS1_13CommandBufferERKNS1_23FramebufferDriverConfigEjjb : 16008 -> 16032
~ __ZN3AGX17FramebufferGen3_1INS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE20finalizeStoreActionsEv : 564 -> 504
~ __ZNK3AGX17FramebufferGen3_2INS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE21assignRenderRegistersEP15AGXTACommandRecP15AGX3DCommandRecbbPNS_11FramebufferIS2_S3_S4_E21DepthReadWriteWAStateE : 1124 -> 1120
~ __ZN3AGX17FramebufferGen3_2INS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE27allocateDatabufferResourcesEPNS1_19DataBufferAllocatorE : 624 -> 628
~ __ZN3AGX17FramebufferGen3_3INS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEEC2EP19AGXG16XFamilyDevicePNS1_13CommandBufferERKNS1_23FramebufferDriverConfigEjjb : 2248 -> 2240
~ __ZN3AGX13RenderContextINS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE19endRenderPassCommonEbbbbb : 11196 -> 11300
~ -[AGXG16XFamilyRenderContext setStencilCleared] : 200 -> 140
~ -[AGXG16XFamilyRenderContext setDepthCleared] : 200 -> 140
~ -[AGXG16XFamilyRenderContext setStencilResolveTexture:slice:depthPlane:level:yInvert:] : 688 -> 684
~ -[AGXG16XFamilyRenderContext setDepthResolveTexture:slice:depthPlane:level:yInvert:] : 560 -> 564
~ -[AGXG16XFamilyRenderContext setStencilResolveTexture:slice:depthPlane:level:] : 688 -> 684
~ -[AGXG16XFamilyRenderContext setDepthResolveTexture:slice:depthPlane:level:] : 560 -> 564
~ __ZN3AGX13RenderContextINS_6HAL2008EncodersENS1_7ClassesENS1_10ObjClassesEE15encodeDepthCopyEbb : 2376 -> 2444
~ -[AGXG16XFamilyRenderContext initWithCommandBuffer:descriptor:subEncoderIndex:framebuffer:] : 8056 -> 8052
```
