## agx_b000

> `Firmware/agx/armfw_g16s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4a3a4
+  __TEXT.__text: 0x4a350
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1194
+  __TEXT.__const: 0x1198
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x6a0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc00000069c8 : 19024 -> 19020
~ sub_fffffc000000bdc4 -> sub_fffffc000000bdc0 : 736 -> 740
~ sub_fffffc000000c0a4 : 2148 -> 2152
~ sub_fffffc000000c908 -> sub_fffffc000000c90c : 4880 -> 4888
~ sub_fffffc000000dc50 -> sub_fffffc000000dc5c : 1256 -> 1260
~ sub_fffffc0000010ca0 -> sub_fffffc0000010cb0 : 804 -> 808
~ sub_fffffc0000020d04 -> sub_fffffc0000020d18 : 416 -> 428
~ sub_fffffc00000281d8 -> sub_fffffc00000281f8 : 6580 -> 6448
~ sub_fffffc0000035404 -> sub_fffffc00000353a0 : 6072 -> 6088
CStrings:
+ "Apr 10 2025 20:19:10"
- "Mar 26 2025 22:18:16"
```
