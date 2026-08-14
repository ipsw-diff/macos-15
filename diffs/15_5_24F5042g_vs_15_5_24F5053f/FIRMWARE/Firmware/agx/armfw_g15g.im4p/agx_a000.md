## agx_a000

> `Firmware/agx/armfw_g15g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4b198
+  __TEXT.__text: 0x4b100
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x22a8
+  __TEXT.__const: 0x22ac
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000008820 : 16764 -> 16760
~ sub_fffffc000000e168 -> sub_fffffc000000e164 : 736 -> 740
~ sub_fffffc000000e448 : 1808 -> 1812
~ sub_fffffc000000eb58 -> sub_fffffc000000eb5c : 4416 -> 4424
~ sub_fffffc0000013660 -> sub_fffffc000001366c : 804 -> 808
~ sub_fffffc0000026868 -> sub_fffffc0000026878 : 18432 -> 18380
~ sub_fffffc000002c6a8 -> sub_fffffc000002c684 : 6592 -> 6460
~ sub_fffffc0000037cb4 -> sub_fffffc0000037c0c : 6340 -> 6356
~ sub_fffffc000004b058 -> sub_fffffc000004afc0 : 328 -> 320
CStrings:
+ "Apr 10 2025 20:14:13"
- "Mar 26 2025 22:13:25"
```
