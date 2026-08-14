## agx_b000

> `Firmware/agx/armfw_g15g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__chain_starts`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_power`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4fac0
+  __TEXT.__text: 0x4fa28
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x22c8
+  __TEXT.__const: 0x22cc
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000008950 : 17448 -> 17444
~ sub_fffffc000000e738 -> sub_fffffc000000e734 : 736 -> 740
~ sub_fffffc000000ea18 : 1672 -> 1676
~ sub_fffffc000000f0a0 -> sub_fffffc000000f0a4 : 4552 -> 4560
~ sub_fffffc00000140dc -> sub_fffffc00000140e8 : 804 -> 808
~ sub_fffffc0000028204 -> sub_fffffc0000028214 : 16448 -> 16396
~ sub_fffffc000002e2a0 -> sub_fffffc000002e27c : 6592 -> 6460
~ sub_fffffc000003c94c -> sub_fffffc000003c8a4 : 5356 -> 5372
~ sub_fffffc000004f980 -> sub_fffffc000004f8e8 : 320 -> 328
CStrings:
+ "Apr 10 2025 20:17:48"
- "Mar 26 2025 22:17:04"
```
