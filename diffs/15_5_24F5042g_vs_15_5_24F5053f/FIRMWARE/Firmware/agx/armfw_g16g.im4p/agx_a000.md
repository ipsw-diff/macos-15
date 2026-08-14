## agx_a000

> `Firmware/agx/armfw_g16g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4e218
+  __TEXT.__text: 0x4e270
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1458
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1c48
+  __TEXT.__const: 0x1c4c
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x6a0
   __TEXT.__chain_starts: 0x30
Functions:
~ sub_fffffc00000089a4 : 17108 -> 17104
~ sub_fffffc000000e644 -> sub_fffffc000000e640 : 736 -> 740
~ sub_fffffc000000e924 : 1596 -> 1600
~ sub_fffffc000000ef60 -> sub_fffffc000000ef64 : 4716 -> 4768
~ sub_fffffc0000013c14 -> sub_fffffc0000013c4c : 916 -> 924
~ sub_fffffc0000024944 -> sub_fffffc0000024984 : 1364 -> 1504
~ sub_fffffc000002bce8 -> sub_fffffc000002bdb4 : 6592 -> 6460
~ sub_fffffc0000039f90 -> sub_fffffc0000039fd8 : 5144 -> 5160
~ sub_fffffc000004e0dc -> sub_fffffc000004e134 : 324 -> 316
CStrings:
+ "Apr 10 2025 20:14:26"
- "Mar 26 2025 22:13:41"
```
