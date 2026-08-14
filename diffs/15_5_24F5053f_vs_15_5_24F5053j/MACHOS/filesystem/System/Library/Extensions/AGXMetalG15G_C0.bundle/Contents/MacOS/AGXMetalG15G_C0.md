## AGXMetalG15G_C0

> `/System/Library/Extensions/AGXMetalG15G_C0.bundle/Contents/MacOS/AGXMetalG15G_C0`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__DATA.__data`

```diff

-327.1.0.0.0
-  __TEXT.__text: 0x6cdb08
+327.5.0.0.0
+  __TEXT.__text: 0x6cdaf0
   __TEXT.__auth_stubs: 0xf80
   __TEXT.__objc_methlist: 0x8a14
-  __TEXT.__const: 0xbec8
+  __TEXT.__const: 0xbed8
   __TEXT.__gcc_except_tab: 0x87c8
   __TEXT.__cstring: 0x73a6
   __TEXT.__oslogstring: 0x143d
Functions:
~ __ZN3AGX11FramebufferINS_3G158EncodersENS1_7ClassesENS1_10ObjClassesEEC2EP19AGXG15GFamilyDevicePNS1_13CommandBufferERKNS1_23FramebufferDriverConfigEjjb : 16008 -> 16032
~ __ZN3AGX17FramebufferGen3_1INS_3G158EncodersENS1_7ClassesENS1_10ObjClassesEE20finalizeStoreActionsEv : 564 -> 504
~ __ZNK3AGX17FramebufferGen3_2INS_3G158EncodersENS1_7ClassesENS1_10ObjClassesEE21assignRenderRegistersEP15AGXTACommandRecP15AGX3DCommandRecbbPNS_11FramebufferIS2_S3_S4_E21DepthReadWriteWAStateE : 1124 -> 1120
~ __ZN3AGX17FramebufferGen3_2INS_3G158EncodersENS1_7ClassesENS1_10ObjClassesEE27allocateDatabufferResourcesEPNS1_19DataBufferAllocatorE : 624 -> 628
~ __ZN3AGX17FramebufferGen3_3INS_3G158EncodersENS1_7ClassesENS1_10ObjClassesEEC2EP19AGXG15GFamilyDevicePNS1_13CommandBufferERKNS1_23FramebufferDriverConfigEjjb : 2248 -> 2240
~ __ZN3AGX19BlitDispatchContextINS_3G158EncodersENS1_7ClassesENS1_10ObjClassesEE13renderTextureEPKPK18IOGPUMetalResourcePNS1_7TextureESC_SA_SC_RKNS_18FlagsConfigurationI13eAGXBlitFlagsEEjPKNS5_10BlitRegionEj : 2860 -> 2888
~ __ZN3AGX19BlitDispatchContextINS_3G158EncodersENS1_7ClassesENS1_10ObjClassesEE8render3DEPKPK18IOGPUMetalResourcePNS1_7TextureESA_SC_yPKvmRKNS5_12Blit3DConfigERKNS_18FlagsConfigurationI13eAGXBlitFlagsEE : 2452 -> 2444
~ __ZN3AGX23BlitDispatchContextGen2INS_3G158EncodersENS1_7ClassesENS1_10ObjClassesEE19renderMRCDownsampleEPK18IOGPUMetalResourcePNS1_7TextureE14_AGC3DBlitTypeRKNS_18FlagsConfigurationI13eAGXBlitFlagsEEjjjj : 2560 -> 2556
~ __ZN3AGX13RenderContextINS_3G158EncodersENS1_7ClassesENS1_10ObjClassesEE19endRenderPassCommonEbbbbb : 9904 -> 10020
~ __ZN3AGX13RenderContextINS_3G158EncodersENS1_7ClassesENS1_10ObjClassesEE15beginRenderPassEv : 8012 -> 7956
~ -[AGXG15GFamilyRenderContext setStencilCleared] : 200 -> 140
~ -[AGXG15GFamilyRenderContext setDepthCleared] : 200 -> 140
~ -[AGXG15GFamilyRenderContext setStencilResolveTexture:slice:depthPlane:level:yInvert:] : 688 -> 684
~ -[AGXG15GFamilyRenderContext setDepthResolveTexture:slice:depthPlane:level:yInvert:] : 560 -> 564
~ -[AGXG15GFamilyRenderContext setStencilResolveTexture:slice:depthPlane:level:] : 688 -> 684
~ -[AGXG15GFamilyRenderContext setDepthResolveTexture:slice:depthPlane:level:] : 560 -> 564
~ __ZN3AGX13RenderContextINS_3G158EncodersENS1_7ClassesENS1_10ObjClassesEE15encodeDepthCopyEbb : 2376 -> 2444
~ -[AGXG15GFamilyRenderContext initWithCommandBuffer:descriptor:subEncoderIndex:framebuffer:] : 7892 -> 7888
```
