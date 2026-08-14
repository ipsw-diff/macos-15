## agx_a000

> `Firmware/agx/armfw_g15d.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4f148
+  __TEXT.__text: 0x4f0d4
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1140
+  __TEXT.__const: 0x1148
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000008230 : 19304 -> 19300
~ sub_fffffc000000dc48 -> sub_fffffc000000dc44 : 2016 -> 2020
~ sub_fffffc000000e428 : 4676 -> 4684
~ sub_fffffc0000013408 -> sub_fffffc0000013410 : 804 -> 808
~ sub_fffffc0000024764 -> sub_fffffc0000024770 : 1160 -> 1136
~ sub_fffffc000002b538 -> sub_fffffc000002b52c : 6584 -> 6452
~ sub_fffffc000002d0ac -> sub_fffffc000002d01c : 1628 -> 1636
~ sub_fffffc000003acfc -> sub_fffffc000003ac74 : 6076 -> 6096
~ sub_fffffc000004f00c -> sub_fffffc000004ef98 : 324 -> 316
CStrings:
+ "Apr 10 2025 20:14:53"
- "Mar 26 2025 22:14:07"
```
