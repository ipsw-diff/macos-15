## agx_b000

> `Firmware/agx/armfw_g15c.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4e08c
+  __TEXT.__text: 0x4e018
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1040
+  __TEXT.__const: 0x1048
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000007d34 : 18064 -> 18060
~ sub_fffffc000000d2a8 -> sub_fffffc000000d2a4 : 2096 -> 2100
~ sub_fffffc000000dad8 : 4688 -> 4696
~ sub_fffffc0000012b38 -> sub_fffffc0000012b40 : 804 -> 808
~ sub_fffffc0000023cf8 -> sub_fffffc0000023d04 : 1160 -> 1136
~ sub_fffffc000002a7f4 -> sub_fffffc000002a7e8 : 6584 -> 6452
~ sub_fffffc000002c368 -> sub_fffffc000002c2d8 : 1628 -> 1636
~ sub_fffffc0000039d68 -> sub_fffffc0000039ce0 : 5780 -> 5800
CStrings:
+ "Apr 10 2025 20:19:16"
- "Mar 26 2025 22:18:22"
```
