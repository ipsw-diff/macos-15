## agx_b000

> `Firmware/agx/armfw_g15g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4fa24
+  __TEXT.__text: 0x4fa44
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1230
+  __TEXT.__gxf_code: 0x1270
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x22cc
+  __TEXT.__const: 0x22c8
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000005318 : 6060 -> 6064
~ sub_fffffc0000030058 -> sub_fffffc000003005c : 1476 -> 1500
~ sub_fffffc0000034790 -> sub_fffffc00000347ac : 372 -> 376
~ sub_fffffc0000034f3c -> sub_fffffc0000034f5c : 756 -> 752
~ sub_fffffc000003543c -> sub_fffffc0000035458 : 640 -> 636
~ sub_fffffc000003b0bc -> sub_fffffc000003b0d4 : 2132 -> 2136
~ sub_fffffc000003c8a0 -> sub_fffffc000003c8bc : 5372 -> 5376
CStrings:
+ "Jun 11 2025 21:17:23"
- "Apr 22 2025 19:48:27"
```
