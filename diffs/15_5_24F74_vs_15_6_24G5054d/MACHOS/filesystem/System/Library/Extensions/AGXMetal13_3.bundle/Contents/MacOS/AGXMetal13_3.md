## AGXMetal13_3

> `/System/Library/Extensions/AGXMetal13_3.bundle/Contents/MacOS/AGXMetal13_3`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH_CONST.__objc_dictobj`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH.__objc_data`
- `__DATA.__data`

```diff

-327.5.0.0.0
-  __TEXT.__text: 0x635c84
+329.1.0.0.0
+  __TEXT.__text: 0x635f00
   __TEXT.__auth_stubs: 0xf80
   __TEXT.__objc_methlist: 0x8804
   __TEXT.__const: 0x9a00
-  __TEXT.__gcc_except_tab: 0x7cbc
-  __TEXT.__cstring: 0x6ae7
+  __TEXT.__gcc_except_tab: 0x7cc0
+  __TEXT.__cstring: 0x6afb
   __TEXT.__oslogstring: 0x13b5
   __TEXT.__unwind_info: 0x3ca8
   __TEXT.__eh_frame: 0xc0

   __DATA_CONST.__objc_arraydata: 0x58
   __AUTH_CONST.__auth_got: 0x7d0
   __AUTH_CONST.__const: 0x3770
-  __AUTH_CONST.__cfstring: 0x3500
+  __AUTH_CONST.__cfstring: 0x3520
   __AUTH_CONST.__objc_const: 0xcae8
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_dictobj: 0x50

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 5175
-  Symbols:   9316
-  CStrings:  4451
+  Functions: 5176
+  Symbols:   9317
+  CStrings:  4452
 
Symbols:
+ GCC_except_table3721
+ GCC_except_table3731
+ GCC_except_table3737
+ GCC_except_table3743
+ GCC_except_table3749
+ GCC_except_table3751
+ GCC_except_table3756
+ GCC_except_table3760
+ GCC_except_table3763
+ GCC_except_table3766
+ GCC_except_table3772
+ GCC_except_table3778
+ GCC_except_table3784
+ GCC_except_table3790
+ GCC_except_table3796
+ GCC_except_table3800
+ GCC_except_table3806
+ GCC_except_table3810
+ GCC_except_table3816
+ GCC_except_table3820
+ GCC_except_table3826
+ GCC_except_table3831
+ GCC_except_table3837
+ GCC_except_table3841
+ GCC_except_table3847
+ GCC_except_table3852
+ GCC_except_table3858
+ GCC_except_table3862
+ GCC_except_table3866
+ GCC_except_table3872
+ GCC_except_table3875
+ GCC_except_table5308
+ GCC_except_table5332
+ GCC_except_table5404
+ GCC_except_table5496
+ __ZL25applyWorkaroundForAppListRKNSt3__16vectorI13AppBundleInfoNS_9allocatorIS1_EEEE
- GCC_except_table3719
- GCC_except_table3726
- GCC_except_table3736
- GCC_except_table3741
- GCC_except_table3745
- GCC_except_table3750
- GCC_except_table3755
- GCC_except_table3758
- GCC_except_table3762
- GCC_except_table3764
- GCC_except_table3771
- GCC_except_table3776
- GCC_except_table3783
- GCC_except_table3788
- GCC_except_table3795
- GCC_except_table3798
- GCC_except_table3805
- GCC_except_table3808
- GCC_except_table3815
- GCC_except_table3818
- GCC_except_table3825
- GCC_except_table3830
- GCC_except_table3836
- GCC_except_table3839
- GCC_except_table3846
- GCC_except_table3851
- GCC_except_table3857
- GCC_except_table3860
- GCC_except_table3864
- GCC_except_table3871
- GCC_except_table3874
- GCC_except_table5307
- GCC_except_table5331
- GCC_except_table5403
- GCC_except_table5495
Functions:
~ __ZN3AGX11BlitContextINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE11fillTextureEP20AGXG13GFamilyTexturejjj9MTLRegionPKvm : 6052 -> 6056
~ -[AGXG13GFamilyBlitContext generateMipmapsForTexture:] : 3304 -> 3336
~ __ZN3AGX19BlitDispatchContextINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE13renderTextureEPKPK18IOGPUMetalResourcePNS1_7TextureESC_SA_SC_RKNS_18FlagsConfigurationI13eAGXBlitFlagsEEjPKNS5_10BlitRegionEj : 3028 -> 3032
~ __ZN3AGX19BlitDispatchContextINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE8render3DEPKPK18IOGPUMetalResourcePNS1_7TextureESA_SC_yPKvmRKNS5_12Blit3DConfigERKNS_18FlagsConfigurationI13eAGXBlitFlagsEE : 2604 -> 2608
~ __ZN3AGX19BlitDispatchContextINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE7blitCDMEPKPK18IOGPUMetalResourcePNS1_7TextureEySA_SC_yRKNS_18FlagsConfigurationI13eAGXBlitFlagsEEjPKNS5_10BlitRegionE21_AGCBlitTextureFormatmmPKvNS5_11BarrierModeE : 4120 -> 4124
~ -[BVHDescriptor maxInnerNodeCount] : 480 -> 736
~ __ZN3AGX24RayTracingGPUBuilderGen1INS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE14calcRiaBvhSizeEPU19objcproto9MTLDevice11objc_objectPK13BVHDescriptorP34MTLAccelerationStructureDescriptorjPy : 3776 -> 3852
~ __ZN3AGX24RayTracingGPUBuilderGen1INS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE26encodeBuildAndEncodeRiaBvhEPK13BVHDescriptorPNS5_16ScratchAllocatorEPKvyyP44AGXG13GFamilyRayTracingAccelerationStructureP34MTLAccelerationStructureDescriptorP19AGXG13GFamilyBufferm : 27688 -> 27708
~ __ZN3AGX24RayTracingGPUBuilderGen1INS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE22setSmallBVHBuildParamsEP34MTLAccelerationStructureDescriptorPK13BVHDescriptorR19BVHSmallBuildParamsRKNS5_15PLOCScratchInfoERKNS5_13BuilderBufferE : 4000 -> 4012
~ ____ZL19gatherDeviceOptionsPN3AGX3G136DeviceEPP8NSStringS5__block_invoke : 4536 -> 4444
+ __ZL25applyWorkaroundForAppListRKNSt3__16vectorI13AppBundleInfoNS_9allocatorIS1_EEEE
CStrings:
+ "com.thqnordic.elex2"
```
