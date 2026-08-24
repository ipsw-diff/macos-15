## agx_a000

> `Firmware/agx/armfw_g16s.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4a3d4
+  __TEXT.__text: 0x4a2d8
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1230
+  __TEXT.__gxf_code: 0x1270
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1198
+  __TEXT.__const: 0x1194
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x6a0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000003664 : 4852 -> 4856
~ sub_fffffc0000004958 -> sub_fffffc000000495c : 5072 -> 5076
~ sub_fffffc000000f090 -> sub_fffffc000000f098 : 668 -> 664
~ sub_fffffc0000011bc4 -> sub_fffffc0000011bc8 : 8848 -> 8840
~ sub_fffffc0000014b24 -> sub_fffffc0000014b20 : 332 -> 320
~ sub_fffffc0000014c70 -> sub_fffffc0000014c60 : 1804 -> 1768
~ sub_fffffc00000157cc -> sub_fffffc0000015798 : 9000 -> 8944
~ sub_fffffc000002f324 -> sub_fffffc000002f2b8 : 528 -> 532
~ sub_fffffc000002fde4 -> sub_fffffc000002fd7c : 636 -> 632
~ sub_fffffc000003026c -> sub_fffffc0000030200 : 640 -> 636
~ sub_fffffc0000030614 -> sub_fffffc00000305a4 : 1880 -> 1884
~ sub_fffffc0000031358 -> sub_fffffc00000312ec : 2252 -> 2256
~ sub_fffffc00000323d0 -> sub_fffffc0000032368 : 7052 -> 7048
~ sub_fffffc0000035424 -> sub_fffffc00000353b8 : 6088 -> 6096
~ sub_fffffc00000372d8 -> sub_fffffc0000037274 : 3164 -> 3012
~ sub_fffffc000004a298 -> sub_fffffc000004a19c : 316 -> 324
CStrings:
+ "Jun 11 2025 21:15:20"
- "Apr 22 2025 19:46:03"
```
