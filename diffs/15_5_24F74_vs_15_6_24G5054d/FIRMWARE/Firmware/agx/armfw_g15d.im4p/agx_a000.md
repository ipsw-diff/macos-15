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

-  __TEXT.__text: 0x4f0d0
+  __TEXT.__text: 0x4f0cc
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
~ sub_fffffc000002d67c -> sub_fffffc000002d680 : 1884 -> 1864
~ sub_fffffc0000032634 -> sub_fffffc0000032624 : 556 -> 560
~ sub_fffffc0000033384 -> sub_fffffc0000033378 : 876 -> 872
~ sub_fffffc00000338fc -> sub_fffffc00000338ec : 640 -> 636
~ sub_fffffc0000033ca4 -> sub_fffffc0000033c90 : 1624 -> 1628
~ sub_fffffc00000395dc -> sub_fffffc00000395cc : 2256 -> 2260
~ sub_fffffc000003ac70 -> sub_fffffc000003ac64 : 6096 -> 6104
~ sub_fffffc000004ef94 -> sub_fffffc000004ef90 : 316 -> 324
CStrings:
+ "Jun 11 2025 21:15:20"
- "Apr 22 2025 19:46:05"
```
