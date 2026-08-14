## agx_b000

> `Firmware/agx/armfw_g16g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4dd90
+  __TEXT.__text: 0x4dde8
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1458
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1c88
+  __TEXT.__const: 0x1c8c
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x6a0
   __TEXT.__chain_starts: 0x30
Functions:
~ sub_fffffc00000088d0 : 17252 -> 17248
~ sub_fffffc000000e600 -> sub_fffffc000000e5fc : 736 -> 740
~ sub_fffffc000000e8e0 : 1596 -> 1600
~ sub_fffffc000000ef1c -> sub_fffffc000000ef20 : 4716 -> 4768
~ sub_fffffc0000013bd0 -> sub_fffffc0000013c08 : 916 -> 924
~ sub_fffffc0000024540 -> sub_fffffc0000024580 : 1364 -> 1504
~ sub_fffffc000002b90c -> sub_fffffc000002b9d8 : 6592 -> 6460
~ sub_fffffc0000039b08 -> sub_fffffc0000039b50 : 5144 -> 5160
~ sub_fffffc000004dc54 -> sub_fffffc000004dcac : 316 -> 324
CStrings:
+ "Apr 10 2025 20:18:17"
- "Mar 26 2025 22:17:30"
```
