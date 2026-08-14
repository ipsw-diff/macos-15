## AGXMetalG13X

> `/System/Library/Extensions/AGXMetalG13X.bundle/Contents/MacOS/AGXMetalG13X`

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
-  __TEXT.__text: 0x636b1c
+327.5.0.0.0
+  __TEXT.__text: 0x636b48
   __TEXT.__auth_stubs: 0xf80
   __TEXT.__objc_methlist: 0x8814
-  __TEXT.__const: 0x9a30
+  __TEXT.__const: 0x9a40
   __TEXT.__gcc_except_tab: 0x7cbc
   __TEXT.__cstring: 0x6aff
   __TEXT.__oslogstring: 0x13b5
Functions:
~ __ZN3AGX23BlitDispatchContextGen2INS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE19renderMRCDownsampleEPK18IOGPUMetalResourcePNS1_7TextureE14_AGC3DBlitTypeRKNS_18FlagsConfigurationI13eAGXBlitFlagsEEjjjj : 2932 -> 2920
~ __ZN3AGX11FramebufferINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEEC2EP19AGXG13XFamilyDevicePNS1_13CommandBufferERKNS1_23FramebufferDriverConfigEjjb : 16048 -> 16100
~ __ZN3AGX17FramebufferGen3_1INS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE20finalizeStoreActionsEv : 564 -> 504
~ __ZN3AGX17FramebufferGen3_2INS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEEC2EP19AGXG13XFamilyDevicePNS1_13CommandBufferERKNS1_23FramebufferDriverConfigEjjb : 1608 -> 1604
~ __ZN3AGX17FramebufferGen3_2INS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE27allocateDatabufferResourcesEPNS1_19DataBufferAllocatorE : 624 -> 628
~ __ZN3AGX13RenderContextINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE19endRenderPassCommonEbbbbb : 8964 -> 9092
~ __ZN3AGX13RenderContextINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE15beginRenderPassEv : 8468 -> 8460
~ -[AGXG13XFamilyRenderContext setStencilCleared] : 200 -> 140
~ -[AGXG13XFamilyRenderContext setDepthCleared] : 200 -> 140
~ -[AGXG13XFamilyRenderContext setStencilResolveTexture:slice:depthPlane:level:yInvert:] : 688 -> 684
~ -[AGXG13XFamilyRenderContext setDepthResolveTexture:slice:depthPlane:level:yInvert:] : 560 -> 564
~ -[AGXG13XFamilyRenderContext setStencilResolveTexture:slice:depthPlane:level:] : 688 -> 684
~ -[AGXG13XFamilyRenderContext setDepthResolveTexture:slice:depthPlane:level:] : 560 -> 564
~ __ZN3AGX13RenderContextINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE15encodeDepthCopyEbb : 2292 -> 2360
~ -[AGXG13XFamilyRenderContext initWithCommandBuffer:descriptor:subEncoderIndex:framebuffer:] : 7900 -> 7896
```
