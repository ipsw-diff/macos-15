## AGXMetalG14G

> `/System/Library/Extensions/AGXMetalG14G.bundle/Contents/MacOS/AGXMetalG14G`

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
-  __TEXT.__text: 0x6a6d70
+329.1.0.0.0
+  __TEXT.__text: 0x6a6fec
   __TEXT.__auth_stubs: 0xf80
   __TEXT.__objc_methlist: 0x8804
   __TEXT.__const: 0xaee0
-  __TEXT.__gcc_except_tab: 0x7cb4
-  __TEXT.__cstring: 0x6b4b
+  __TEXT.__gcc_except_tab: 0x7cb8
+  __TEXT.__cstring: 0x6b5f
   __TEXT.__oslogstring: 0x13b5
   __TEXT.__unwind_info: 0x4048
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
-  Functions: 5403
-  Symbols:   9692
-  CStrings:  4452
+  Functions: 5404
+  Symbols:   9693
+  CStrings:  4453
 
Symbols:
+ GCC_except_table4084
+ GCC_except_table4094
+ GCC_except_table4100
+ GCC_except_table4106
+ GCC_except_table4112
+ GCC_except_table4114
+ GCC_except_table4119
+ GCC_except_table4123
+ GCC_except_table4126
+ GCC_except_table4129
+ GCC_except_table4135
+ GCC_except_table4141
+ GCC_except_table4147
+ GCC_except_table4153
+ GCC_except_table4159
+ GCC_except_table4163
+ GCC_except_table4169
+ GCC_except_table4173
+ GCC_except_table4179
+ GCC_except_table4183
+ GCC_except_table4189
+ GCC_except_table4194
+ GCC_except_table4200
+ GCC_except_table4204
+ GCC_except_table4210
+ GCC_except_table4215
+ GCC_except_table4221
+ GCC_except_table4225
+ GCC_except_table4229
+ GCC_except_table4235
+ GCC_except_table4238
+ GCC_except_table5671
+ GCC_except_table5695
+ GCC_except_table5766
+ GCC_except_table5858
+ __ZL25applyWorkaroundForAppListRKNSt3__16vectorI13AppBundleInfoNS_9allocatorIS1_EEEE
- GCC_except_table4082
- GCC_except_table4089
- GCC_except_table4099
- GCC_except_table4104
- GCC_except_table4108
- GCC_except_table4113
- GCC_except_table4118
- GCC_except_table4121
- GCC_except_table4125
- GCC_except_table4127
- GCC_except_table4134
- GCC_except_table4139
- GCC_except_table4146
- GCC_except_table4151
- GCC_except_table4158
- GCC_except_table4161
- GCC_except_table4168
- GCC_except_table4171
- GCC_except_table4178
- GCC_except_table4181
- GCC_except_table4188
- GCC_except_table4193
- GCC_except_table4199
- GCC_except_table4202
- GCC_except_table4209
- GCC_except_table4214
- GCC_except_table4220
- GCC_except_table4223
- GCC_except_table4227
- GCC_except_table4234
- GCC_except_table4237
- GCC_except_table5670
- GCC_except_table5694
- GCC_except_table5765
- GCC_except_table5857
Functions:
~ __ZN3AGX11BlitContextINS_3G148EncodersENS1_7ClassesENS1_10ObjClassesEE11fillTextureEP20AGXG14GFamilyTexturejjj9MTLRegionPKvm : 6052 -> 6056
~ -[AGXG14GFamilyBlitContext generateMipmapsForTexture:] : 3304 -> 3336
~ __ZN3AGX19BlitDispatchContextINS_3G148EncodersENS1_7ClassesENS1_10ObjClassesEE13renderTextureEPKPK18IOGPUMetalResourcePNS1_7TextureESC_SA_SC_RKNS_18FlagsConfigurationI13eAGXBlitFlagsEEjPKNS5_10BlitRegionEj : 3028 -> 3032
~ __ZN3AGX19BlitDispatchContextINS_3G148EncodersENS1_7ClassesENS1_10ObjClassesEE8render3DEPKPK18IOGPUMetalResourcePNS1_7TextureESA_SC_yPKvmRKNS5_12Blit3DConfigERKNS_18FlagsConfigurationI13eAGXBlitFlagsEE : 2604 -> 2608
~ __ZN3AGX19BlitDispatchContextINS_3G148EncodersENS1_7ClassesENS1_10ObjClassesEE7blitCDMEPKPK18IOGPUMetalResourcePNS1_7TextureEySA_SC_yRKNS_18FlagsConfigurationI13eAGXBlitFlagsEEjPKNS5_10BlitRegionE21_AGCBlitTextureFormatmmPKvNS5_11BarrierModeE : 4120 -> 4124
~ -[BVHDescriptor maxInnerNodeCount] : 480 -> 736
~ __ZN3AGX24RayTracingGPUBuilderGen1INS_3G148EncodersENS1_7ClassesENS1_10ObjClassesEE14calcRiaBvhSizeEPU19objcproto9MTLDevice11objc_objectPK13BVHDescriptorP34MTLAccelerationStructureDescriptorjPy : 3776 -> 3852
~ __ZN3AGX24RayTracingGPUBuilderGen1INS_3G148EncodersENS1_7ClassesENS1_10ObjClassesEE26encodeBuildAndEncodeRiaBvhEPK13BVHDescriptorPNS5_16ScratchAllocatorEPKvyyP44AGXG14GFamilyRayTracingAccelerationStructureP34MTLAccelerationStructureDescriptorP19AGXG14GFamilyBufferm : 27688 -> 27708
~ __ZN3AGX24RayTracingGPUBuilderGen1INS_3G148EncodersENS1_7ClassesENS1_10ObjClassesEE22setSmallBVHBuildParamsEP34MTLAccelerationStructureDescriptorPK13BVHDescriptorR19BVHSmallBuildParamsRKNS5_15PLOCScratchInfoERKNS5_13BuilderBufferE : 4000 -> 4012
~ ____ZL19gatherDeviceOptionsPN3AGX3G146DeviceEPP8NSStringS5__block_invoke : 4536 -> 4444
+ __ZL25applyWorkaroundForAppListRKNSt3__16vectorI13AppBundleInfoNS_9allocatorIS1_EEEE
CStrings:
+ "com.thqnordic.elex2"
```
