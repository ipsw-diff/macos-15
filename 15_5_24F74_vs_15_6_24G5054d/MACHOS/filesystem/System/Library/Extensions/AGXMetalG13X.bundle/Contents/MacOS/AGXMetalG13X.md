## AGXMetalG13X

> `/System/Library/Extensions/AGXMetalG13X.bundle/Contents/MacOS/AGXMetalG13X`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH.__objc_data`
- `__DATA.__data`

```diff

-327.5.0.0.0
-  __TEXT.__text: 0x636b48
+329.1.0.0.0
+  __TEXT.__text: 0x636dc4
   __TEXT.__auth_stubs: 0xf80
   __TEXT.__objc_methlist: 0x8814
   __TEXT.__const: 0x9a40
-  __TEXT.__gcc_except_tab: 0x7cbc
-  __TEXT.__cstring: 0x6aff
+  __TEXT.__gcc_except_tab: 0x7cc0
+  __TEXT.__cstring: 0x6b13
   __TEXT.__oslogstring: 0x13b5
-  __TEXT.__unwind_info: 0x3ca8
+  __TEXT.__unwind_info: 0x3cb0
   __TEXT.__eh_frame: 0xc0
   __TEXT.__objc_classname: 0xb40
   __TEXT.__objc_methname: 0x133f7

   __DATA_CONST.__objc_arraydata: 0x58
   __AUTH_CONST.__auth_got: 0x7d0
   __AUTH_CONST.__const: 0x3770
-  __AUTH_CONST.__cfstring: 0x3560
+  __AUTH_CONST.__cfstring: 0x3580
   __AUTH_CONST.__objc_const: 0xcae8
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_dictobj: 0x50

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 5177
-  Symbols:   9319
-  CStrings:  4454
+  Functions: 5178
+  Symbols:   9320
+  CStrings:  4455
 
Symbols:
+ GCC_except_table3723
+ GCC_except_table3733
+ GCC_except_table3739
+ GCC_except_table3745
+ GCC_except_table3751
+ GCC_except_table3753
+ GCC_except_table3758
+ GCC_except_table3762
+ GCC_except_table3765
+ GCC_except_table3768
+ GCC_except_table3774
+ GCC_except_table3780
+ GCC_except_table3786
+ GCC_except_table3792
+ GCC_except_table3798
+ GCC_except_table3802
+ GCC_except_table3808
+ GCC_except_table3812
+ GCC_except_table3818
+ GCC_except_table3822
+ GCC_except_table3828
+ GCC_except_table3833
+ GCC_except_table3839
+ GCC_except_table3843
+ GCC_except_table3849
+ GCC_except_table3854
+ GCC_except_table3860
+ GCC_except_table3864
+ GCC_except_table3868
+ GCC_except_table3874
+ GCC_except_table3877
+ GCC_except_table5310
+ GCC_except_table5334
+ GCC_except_table5406
+ GCC_except_table5498
+ __ZL25applyWorkaroundForAppListRKNSt3__16vectorI13AppBundleInfoNS_9allocatorIS1_EEEE
- GCC_except_table3721
- GCC_except_table3728
- GCC_except_table3738
- GCC_except_table3743
- GCC_except_table3747
- GCC_except_table3752
- GCC_except_table3757
- GCC_except_table3760
- GCC_except_table3764
- GCC_except_table3766
- GCC_except_table3773
- GCC_except_table3778
- GCC_except_table3785
- GCC_except_table3790
- GCC_except_table3797
- GCC_except_table3800
- GCC_except_table3807
- GCC_except_table3810
- GCC_except_table3817
- GCC_except_table3820
- GCC_except_table3827
- GCC_except_table3832
- GCC_except_table3838
- GCC_except_table3841
- GCC_except_table3848
- GCC_except_table3853
- GCC_except_table3859
- GCC_except_table3862
- GCC_except_table3866
- GCC_except_table3873
- GCC_except_table3876
- GCC_except_table5309
- GCC_except_table5333
- GCC_except_table5405
- GCC_except_table5497
Functions:
~ __ZN3AGX11BlitContextINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE11fillTextureEP20AGXG13XFamilyTexturejjj9MTLRegionPKvm : 6052 -> 6056
~ -[AGXG13XFamilyBlitContext generateMipmapsForTexture:] : 3304 -> 3336
~ __ZN3AGX19BlitDispatchContextINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE13renderTextureEPKPK18IOGPUMetalResourcePNS1_7TextureESC_SA_SC_RKNS_18FlagsConfigurationI13eAGXBlitFlagsEEjPKNS5_10BlitRegionEj : 3028 -> 3032
~ __ZN3AGX19BlitDispatchContextINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE8render3DEPKPK18IOGPUMetalResourcePNS1_7TextureESA_SC_yPKvmRKNS5_12Blit3DConfigERKNS_18FlagsConfigurationI13eAGXBlitFlagsEE : 2604 -> 2608
~ __ZN3AGX19BlitDispatchContextINS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE7blitCDMEPKPK18IOGPUMetalResourcePNS1_7TextureEySA_SC_yRKNS_18FlagsConfigurationI13eAGXBlitFlagsEEjPKNS5_10BlitRegionE21_AGCBlitTextureFormatmmPKvNS5_11BarrierModeE : 4120 -> 4124
~ -[BVHDescriptor maxInnerNodeCount] : 480 -> 736
~ __ZN3AGX24RayTracingGPUBuilderGen1INS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE14calcRiaBvhSizeEPU19objcproto9MTLDevice11objc_objectPK13BVHDescriptorP34MTLAccelerationStructureDescriptorjPy : 3776 -> 3852
~ __ZN3AGX24RayTracingGPUBuilderGen1INS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE26encodeBuildAndEncodeRiaBvhEPK13BVHDescriptorPNS5_16ScratchAllocatorEPKvyyP44AGXG13XFamilyRayTracingAccelerationStructureP34MTLAccelerationStructureDescriptorP19AGXG13XFamilyBufferm : 27688 -> 27708
~ __ZN3AGX24RayTracingGPUBuilderGen1INS_3G138EncodersENS1_7ClassesENS1_10ObjClassesEE22setSmallBVHBuildParamsEP34MTLAccelerationStructureDescriptorPK13BVHDescriptorR19BVHSmallBuildParamsRKNS5_15PLOCScratchInfoERKNS5_13BuilderBufferE : 4000 -> 4012
~ ____ZL19gatherDeviceOptionsPN3AGX3G136DeviceEPP8NSStringS5__block_invoke : 4536 -> 4444
+ __ZL25applyWorkaroundForAppListRKNSt3__16vectorI13AppBundleInfoNS_9allocatorIS1_EEEE
CStrings:
+ "com.thqnordic.elex2"
```
