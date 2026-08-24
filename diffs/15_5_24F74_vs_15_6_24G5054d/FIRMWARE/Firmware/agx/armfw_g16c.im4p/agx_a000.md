## agx_a000

> `Firmware/agx/armfw_g16c.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4a56c
+  __TEXT.__text: 0x4a470
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
~ sub_fffffc0000003664 : 4836 -> 4840
~ sub_fffffc0000004948 -> sub_fffffc000000494c : 5072 -> 5076
~ sub_fffffc000000f070 -> sub_fffffc000000f078 : 668 -> 664
~ sub_fffffc0000011ba4 -> sub_fffffc0000011ba8 : 8848 -> 8840
~ sub_fffffc0000014b04 -> sub_fffffc0000014b00 : 332 -> 320
~ sub_fffffc0000014c50 -> sub_fffffc0000014c40 : 1804 -> 1768
~ sub_fffffc00000157ac -> sub_fffffc0000015778 : 9000 -> 8944
~ sub_fffffc000002f460 -> sub_fffffc000002f3f4 : 528 -> 532
~ sub_fffffc000002ff20 -> sub_fffffc000002feb8 : 636 -> 632
~ sub_fffffc00000303a8 -> sub_fffffc000003033c : 640 -> 636
~ sub_fffffc0000030750 -> sub_fffffc00000306e0 : 1880 -> 1884
~ sub_fffffc00000314f0 -> sub_fffffc0000031484 : 2252 -> 2256
~ sub_fffffc0000032568 -> sub_fffffc0000032500 : 7052 -> 7048
~ sub_fffffc00000355bc -> sub_fffffc0000035550 : 6088 -> 6096
~ sub_fffffc0000037470 -> sub_fffffc000003740c : 3164 -> 3012
~ sub_fffffc000004a430 -> sub_fffffc000004a334 : 324 -> 316
CStrings:
+ "Jun 11 2025 21:15:20"
- "Apr 22 2025 19:46:04"
```
