## agx_a000

> `Firmware/agx/armfw_g15c.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4e508
+  __TEXT.__text: 0x4e494
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1040
+  __TEXT.__const: 0x1048
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000007d34 : 17928 -> 17924
~ sub_fffffc000000d220 -> sub_fffffc000000d21c : 2096 -> 2100
~ sub_fffffc000000da50 : 4688 -> 4696
~ sub_fffffc0000012ab0 -> sub_fffffc0000012ab8 : 804 -> 808
~ sub_fffffc0000023c98 -> sub_fffffc0000023ca4 : 1160 -> 1136
~ sub_fffffc000002a798 -> sub_fffffc000002a78c : 6584 -> 6452
~ sub_fffffc000002c30c -> sub_fffffc000002c27c : 1628 -> 1636
~ sub_fffffc000003a1e4 -> sub_fffffc000003a15c : 5780 -> 5800
~ sub_fffffc000004e3cc -> sub_fffffc000004e358 : 324 -> 316
CStrings:
+ "Apr 10 2025 20:14:53"
- "Mar 26 2025 22:14:06"
```
