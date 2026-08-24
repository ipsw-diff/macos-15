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

-  __TEXT.__text: 0x4e26c
+  __TEXT.__text: 0x4e288
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1458
+  __TEXT.__gxf_code: 0x1498
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1c4c
+  __TEXT.__const: 0x1c48
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x6a0
   __TEXT.__chain_starts: 0x30

   __DATA.__constructor: 0x0
   __DATA.__xnu_shared: 0x3c000
   __DATA._rtk_mtab: 0x400
-  __DATA.__zerofill: 0x70038
+  __DATA.__zerofill: 0x70058
   Functions: 518
   Symbols:   235
   CStrings:  279
Functions:
~ sub_fffffc00000054dc : 6068 -> 6072
~ sub_fffffc000002dd68 -> sub_fffffc000002dd6c : 1480 -> 1504
~ sub_fffffc0000031e44 -> sub_fffffc0000031e60 : 372 -> 376
~ sub_fffffc00000324f8 -> sub_fffffc0000032518 : 784 -> 780
~ sub_fffffc0000032a14 -> sub_fffffc0000032a30 : 640 -> 636
~ sub_fffffc0000034068 -> sub_fffffc0000034080 : 8620 -> 8616
~ sub_fffffc00000387e0 -> sub_fffffc00000387f4 : 2132 -> 2136
~ sub_fffffc0000039fd4 -> sub_fffffc0000039fec : 5160 -> 5164
CStrings:
+ "Jun 11 2025 21:15:01"
- "Apr 22 2025 19:45:44"
```
