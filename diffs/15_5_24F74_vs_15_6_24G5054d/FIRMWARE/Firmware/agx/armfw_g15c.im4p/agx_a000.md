## agx_a000

> `Firmware/agx/armfw_g15c.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4e490
+  __TEXT.__text: 0x4e48c
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1230
+  __TEXT.__gxf_code: 0x1270
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1048
+  __TEXT.__const: 0x1040
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000004e64 : 5352 -> 5356
~ sub_fffffc000002c8dc -> sub_fffffc000002c8e0 : 1756 -> 1736
~ sub_fffffc0000031b3c -> sub_fffffc0000031b2c : 556 -> 560
~ sub_fffffc000003288c -> sub_fffffc0000032880 : 876 -> 872
~ sub_fffffc0000032e04 -> sub_fffffc0000032df4 : 640 -> 636
~ sub_fffffc00000331ac -> sub_fffffc0000033198 : 1624 -> 1628
~ sub_fffffc0000038b24 -> sub_fffffc0000038b14 : 2256 -> 2260
~ sub_fffffc000003a158 -> sub_fffffc000003a14c : 5800 -> 5808
~ sub_fffffc000004e354 -> sub_fffffc000004e350 : 316 -> 324
CStrings:
+ "Jun 11 2025 21:15:19"
- "Apr 22 2025 19:46:05"
```
