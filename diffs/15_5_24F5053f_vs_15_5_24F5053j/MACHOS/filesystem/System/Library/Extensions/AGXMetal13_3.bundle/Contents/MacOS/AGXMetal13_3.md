## AGXMetal13_3

> `/System/Library/Extensions/AGXMetal13_3.bundle/Contents/MacOS/AGXMetal13_3`

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
-  __TEXT.__text: 0x635c58
+327.5.0.0.0
+  __TEXT.__text: 0x635c84
   __TEXT.__auth_stubs: 0xf80
   __TEXT.__objc_methlist: 0x8804
-  __TEXT.__const: 0x99f0
+  __TEXT.__const: 0x9a00
   __TEXT.__gcc_except_tab: 0x7cbc
   __TEXT.__cstring: 0x6ae7
   __TEXT.__oslogstring: 0x13b5
Functions:
~ __ZN3AGX23BlitDispatchContextGen2INS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE19renderMRCDownsampleEPK18IOGPUMetalResourcePNS1_7TextureE14_AGC3DBlitTypeRKNS_18FlagsConfigurationI13eAGXBlitFlagsEEjjjj : 2932 -> 2920
~ __ZN3AGX11FramebufferINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEEC2EP19AGXG13GFamilyDevicePNS1_13CommandBufferERKNS1_23FramebufferDriverConfigEjjb : 16048 -> 16100
~ __ZN3AGX17FramebufferGen3_1INS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE20finalizeStoreActionsEv : 564 -> 504
~ __ZN3AGX17FramebufferGen3_2INS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEEC2EP19AGXG13GFamilyDevicePNS1_13CommandBufferERKNS1_23FramebufferDriverConfigEjjb : 1608 -> 1604
~ __ZN3AGX17FramebufferGen3_2INS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE27allocateDatabufferResourcesEPNS1_19DataBufferAllocatorE : 624 -> 628
~ __ZN3AGX13RenderContextINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE19endRenderPassCommonEbbbbb : 8900 -> 9028
~ __ZN3AGX13RenderContextINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE15beginRenderPassEv : 8464 -> 8456
~ -[AGXG13GFamilyRenderContext setStencilCleared] : 200 -> 140
~ -[AGXG13GFamilyRenderContext setDepthCleared] : 200 -> 140
~ -[AGXG13GFamilyRenderContext setStencilResolveTexture:slice:depthPlane:level:yInvert:] : 688 -> 684
~ -[AGXG13GFamilyRenderContext setDepthResolveTexture:slice:depthPlane:level:yInvert:] : 560 -> 564
~ -[AGXG13GFamilyRenderContext setStencilResolveTexture:slice:depthPlane:level:] : 688 -> 684
~ -[AGXG13GFamilyRenderContext setDepthResolveTexture:slice:depthPlane:level:] : 560 -> 564
~ __ZN3AGX13RenderContextINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE15encodeDepthCopyEbb : 2292 -> 2360
~ -[AGXG13GFamilyRenderContext initWithCommandBuffer:descriptor:subEncoderIndex:framebuffer:] : 7908 -> 7904
```
