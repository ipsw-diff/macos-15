## agx_b000

> `Firmware/agx/armfw_g15d.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4f2bc
+  __TEXT.__text: 0x4f248
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1140
+  __TEXT.__const: 0x1148
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000008230 : 19700 -> 19696
~ sub_fffffc000000ddd4 -> sub_fffffc000000ddd0 : 2016 -> 2020
~ sub_fffffc000000e5b4 : 4676 -> 4684
~ sub_fffffc0000013594 -> sub_fffffc000001359c : 804 -> 808
~ sub_fffffc00000248dc -> sub_fffffc00000248e8 : 1160 -> 1136
~ sub_fffffc000002b6ac -> sub_fffffc000002b6a0 : 6584 -> 6452
~ sub_fffffc000002d220 -> sub_fffffc000002d190 : 1628 -> 1636
~ sub_fffffc000003ae70 -> sub_fffffc000003ade8 : 6076 -> 6096
CStrings:
+ "Apr 10 2025 20:19:20"
- "Mar 26 2025 22:18:25"
```
