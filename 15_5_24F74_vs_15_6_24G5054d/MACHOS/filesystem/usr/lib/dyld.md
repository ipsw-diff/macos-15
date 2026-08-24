## dyld

> `/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA.__data`
- `__DATA_DIRTY.__all_image_info`

```diff

-1285.19.0.0.0
+1286.9.0.0.0
   __TEXT.__text: 0x8767c
-  __TEXT.__const: 0x23c0
-  __TEXT.__cstring: 0x10102
+  __TEXT.__const: 0x2420
+  __TEXT.__cstring: 0x1010c
   __TEXT.__unwind_info: 0x4a8
   __DATA_CONST.__auth_ptr: 0x80
   __DATA_CONST.__const: 0x76e0
Functions:
~ __ZN5dyld39MachOFile15PointerMetaDataC1Ev : 16 -> 8
~ __ZN12_GLOBAL__N_19quickSortIPPN12PropertyList4DataEEEvT_S5_ : 336 -> 344
CStrings:
+ "1286.9"
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Wed Jun 11 21:16:08 PDT 2025; root:libignition-56~62282/libignition_core/RELEASE_ARM64E"
+ "Darwin Ignition Sequence Version 1.0.0: Wed Jun 11 21:16:08 PDT 2025; root:libignition-56~62282/libignition_core/RELEASE_ARM64E"
+ "v28@?0I8{PointerMetaData=b16b8b1b2b1b4}12Q16B24"
+ "v32@?0Q8{PointerMetaData=b16b8b1b2b1b4}16Q20B28"
+ "v48@?0r^v8{PointerMetaData=b16b8b1b2b1b4}16r^v20r^{Header={mach_header=IiiIIII}}28i36^B40"
- "1285.19"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Fri Apr 25 17:51:08 PDT 2025; root:libignition-56~61884/libignition_core/RELEASE_ARM64E"
- "Darwin Ignition Sequence Version 1.0.0: Fri Apr 25 17:51:08 PDT 2025; root:libignition-56~61884/libignition_core/RELEASE_ARM64E"
- "v28@?0I8{PointerMetaData=b16b8b1b2b1}12Q16B24"
- "v32@?0Q8{PointerMetaData=b16b8b1b2b1}16Q20B28"
- "v48@?0r^v8{PointerMetaData=b16b8b1b2b1}16r^v20r^{Header={mach_header=IiiIIII}}28i36^B40"
```
