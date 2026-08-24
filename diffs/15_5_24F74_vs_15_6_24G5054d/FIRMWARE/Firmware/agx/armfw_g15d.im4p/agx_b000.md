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

-  __TEXT.__text: 0x4f244
+  __TEXT.__text: 0x4f240
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1230
+  __TEXT.__gxf_code: 0x1270
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1148
+  __TEXT.__const: 0x1140
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000004ecc : 5352 -> 5356
~ sub_fffffc000002d7f0 -> sub_fffffc000002d7f4 : 1884 -> 1864
~ sub_fffffc00000327a8 -> sub_fffffc0000032798 : 556 -> 560
~ sub_fffffc00000334f8 -> sub_fffffc00000334ec : 876 -> 872
~ sub_fffffc0000033a70 -> sub_fffffc0000033a60 : 640 -> 636
~ sub_fffffc0000033e18 -> sub_fffffc0000033e04 : 1624 -> 1628
~ sub_fffffc0000039750 -> sub_fffffc0000039740 : 2256 -> 2260
~ sub_fffffc000003ade4 -> sub_fffffc000003add8 : 6096 -> 6104
CStrings:
+ "Jun 11 2025 21:18:31"
- "Apr 22 2025 19:49:28"
```
