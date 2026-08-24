## agx_c000

> `Firmware/agx/armfw_g15g.im4p/agx_c000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4f5a8
+  __TEXT.__text: 0x4f5c8
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1230
+  __TEXT.__gxf_code: 0x1270
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x22cc
+  __TEXT.__const: 0x22c8
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28

   __DATA.__constructor: 0x0
   __DATA.__xnu_shared: 0x3c000
   __DATA._rtk_mtab: 0x390
-  __DATA.__zerofill: 0x67598
+  __DATA.__zerofill: 0x675b8
   Functions: 491
   Symbols:   227
   CStrings:  261
Functions:
~ sub_fffffc0000005318 : 6060 -> 6064
~ sub_fffffc0000030068 -> sub_fffffc000003006c : 1476 -> 1500
~ sub_fffffc000003433c -> sub_fffffc0000034358 : 372 -> 376
~ sub_fffffc0000034ae8 -> sub_fffffc0000034b08 : 756 -> 752
~ sub_fffffc0000034fe8 -> sub_fffffc0000035004 : 640 -> 636
~ sub_fffffc000003ac50 -> sub_fffffc000003ac68 : 2132 -> 2136
~ sub_fffffc000003c434 -> sub_fffffc000003c450 : 5356 -> 5360
CStrings:
+ "Jun 11 2025 21:18:58"
- "Apr 22 2025 19:49:58"
```
