## agx_b000

> `Firmware/agx/armfw_g15s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4b128
+  __TEXT.__text: 0x4b150
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1230
+  __TEXT.__gxf_code: 0x1270
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0xfc0
+  __TEXT.__const: 0xfb8
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000004e44 : 5340 -> 5344
~ sub_fffffc000002b51c -> sub_fffffc000002b520 : 1532 -> 1556
~ sub_fffffc000002fd28 -> sub_fffffc000002fd44 : 448 -> 452
~ sub_fffffc0000030634 -> sub_fffffc0000030654 : 872 -> 868
~ sub_fffffc0000030ba8 -> sub_fffffc0000030bc4 : 640 -> 636
~ sub_fffffc0000030f50 -> sub_fffffc0000030f68 : 1396 -> 1400
~ sub_fffffc000003678c -> sub_fffffc00000367a8 : 2256 -> 2260
~ sub_fffffc0000037d20 -> sub_fffffc0000037d40 : 4464 -> 4472
~ sub_fffffc000004afe8 -> sub_fffffc000004b010 : 328 -> 320
CStrings:
+ "Jun 11 2025 21:18:17"
- "Apr 22 2025 19:49:18"
```
