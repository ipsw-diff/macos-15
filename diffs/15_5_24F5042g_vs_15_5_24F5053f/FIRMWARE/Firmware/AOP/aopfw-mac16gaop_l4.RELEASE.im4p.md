## aopfw-mac16gaop_l4.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16gaop_l4.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__DATA.__const`
- `__DATA.__data`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA.__version`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0xba728
-  __TEXT.__const: 0xa294
-  __TEXT.__cstring: 0x76c5
+  __TEXT.__text: 0xba770
+  __TEXT.__const: 0xa288
+  __TEXT.__cstring: 0x76cf
   __TEXT.__chain_starts: 0x5c
   __DATA._rtk_boot: 0x3000
   __DATA._rtk_page_tables: 0x5000

   __DATA._rtk_mtab: 0x5d0
   __DATA.__zerofill: 0xaa0d8
   __ETEXT.__eh_frame: 0x40
-  __ETEXT.__text: 0x11f38
+  __ETEXT.__text: 0x11f48
   __ETEXT.__StaticInit: 0x1fe4
   __ETEXT.__const: 0x4ed
   __OS_LOG.__string: 0x2649b

   __CMA.__cma_log_string: 0x11b3
   Functions: 2880
   Symbols:   0
-  CStrings:  1210
+  CStrings:  1211
 
Functions:
~ sub_1027848 : 96 -> 108
~ sub_10278a8 -> sub_10278b4 : 72 -> 76
~ sub_1027934 -> sub_1027944 : 348 -> 396
~ sub_10295c0 -> sub_1029600 : 456 -> 464
~ sub_102b0f0 -> sub_102b138 : 356 -> 360
~ sub_102b254 -> sub_102b2a0 : 516 -> 520
~ sub_1030cd4 -> sub_1030d24 : 2124 -> 2132
~ sub_1031520 -> sub_1031578 : 1672 -> 1648
~ sub_1031c44 -> sub_1031c84 : 636 -> 652
~ sub_104b030 -> sub_104b080 : 1088 -> 1084
~ sub_104b470 -> sub_104b4bc : 1264 -> 1260
~ sub_108e414 -> sub_108e45c : 1620 -> 1616
~ sub_10b5584 -> sub_10b55c8 : 248 -> 232
~ sub_10b5d7c -> sub_10b5db0 : 876 -> 892
~ sub_10b68e8 -> sub_10b692c : 264 -> 240
~ sub_10b69f0 -> sub_10b6a1c : 248 -> 260
~ sub_10b6ae8 -> sub_10b6b20 : 128 -> 140
~ sub_10b6b68 -> sub_10b6bac : 624 -> 584
~ sub_10b6dd8 -> sub_10b6df4 : 108 -> 132
~ sub_10b6e44 -> sub_10b6e78 : 56 -> 72
~ sub_10b77a8 -> sub_10b77ec : 216 -> 200
~ sub_10b7880 -> sub_10b78b4 : 176 -> 204
~ sub_10b7930 -> sub_10b7980 : 84 -> 56
~ sub_10b7984 -> sub_10b79b8 : 28 -> 44
~ sub_10b90e0 -> sub_10b9124 : 2436 -> 2392
~ sub_10b9a64 -> sub_10b9a7c : 496 -> 516
~ sub_10b9f70 -> sub_10b9f9c : 44 -> 72
~ sub_10ba00c -> sub_10ba054 : 80 -> 40
~ sub_10ba05c -> sub_10ba07c : 28 -> 68
~ sub_10ba5ec -> sub_10ba634 : 324 -> 316
CStrings:
+ "17:40:09"
+ "17:45:35"
+ "17:45:36"
+ "AppleSPUFirmware-2001.120.14~251"
+ "Apr  6 2025"
- "18:20:21"
- "18:26:50"
- "AppleSPUFirmware-2001.120.9~127"
- "Mar 21 2025"
```
