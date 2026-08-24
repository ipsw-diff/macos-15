## agx_a000

> `Firmware/agx/armfw_g15s.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4b5a4
+  __TEXT.__text: 0x4b5cc
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
~ sub_fffffc000002b4c0 -> sub_fffffc000002b4c4 : 1532 -> 1556
~ sub_fffffc0000030198 -> sub_fffffc00000301b4 : 448 -> 452
~ sub_fffffc0000030aa4 -> sub_fffffc0000030ac4 : 872 -> 868
~ sub_fffffc0000031018 -> sub_fffffc0000031034 : 640 -> 636
~ sub_fffffc00000313c0 -> sub_fffffc00000313d8 : 1396 -> 1400
~ sub_fffffc0000036c08 -> sub_fffffc0000036c24 : 2256 -> 2260
~ sub_fffffc000003819c -> sub_fffffc00000381bc : 4464 -> 4472
~ sub_fffffc000004b464 -> sub_fffffc000004b48c : 320 -> 328
CStrings:
+ "Jun 11 2025 21:15:17"
- "Apr 22 2025 19:46:01"
```
