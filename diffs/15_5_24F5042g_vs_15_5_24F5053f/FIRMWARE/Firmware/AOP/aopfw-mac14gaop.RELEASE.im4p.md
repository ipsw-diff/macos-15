## aopfw-mac14gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac14gaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA._rtk_power`
- `__DATA._rtk_patchbay`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA.__mod_init_func`
- `__DATA.__version`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x8cd20
+  __TEXT.__text: 0x8cd5c
   __TEXT.__const: 0x4fd0
-  __TEXT.__cstring: 0x6109
+  __TEXT.__cstring: 0x610a
   __TEXT.__chain_starts: 0x40
   __DATA._rtk_boot: 0x3000
   __DATA._rtk_page_tables: 0x5000

   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x17f68
   __DATA.__const: 0x8848
-  __DATA.__data: 0x9460
+  __DATA.__data: 0x9468
   __DATA._rtk_power: 0x3b8
   __DATA._rtk_patchbay: 0x2f9
   __DATA._spu_service: 0x300

   __DATA._rtk_mtab: 0x6a8
   __DATA.__zerofill: 0x72118
   __ETEXT.__eh_frame: 0x40
-  __ETEXT.__text: 0x118d0
+  __ETEXT.__text: 0x118e0
   __ETEXT.__StaticInit: 0x78b8
   __ETEXT.__const: 0x43a
   __OS_LOG.__string: 0x10f19
Functions:
~ sub_10264a8 : 96 -> 108
~ sub_1026508 -> sub_1026514 : 72 -> 76
~ sub_1026594 -> sub_10265a4 : 348 -> 396
~ sub_1029d5c -> sub_1029d9c : 356 -> 360
~ sub_1029ec0 -> sub_1029f04 : 516 -> 520
~ sub_102f960 -> sub_102f9a8 : 2108 -> 2116
~ sub_103019c -> sub_10301ec : 1680 -> 1648
~ sub_10308c8 -> sub_10308f8 : 644 -> 656
~ sub_1089930 -> sub_108996c : 372 -> 356
~ sub_1089c40 -> sub_1089c6c : 164 -> 156
~ sub_1089ce4 -> sub_1089d08 : 1560 -> 1584
~ sub_108b5ec -> sub_108b628 : 2404 -> 2432
~ sub_108bf50 -> sub_108bfa8 : 1580 -> 1552
~ sub_108c908 -> sub_108c944 : 32 -> 28
~ sub_108c928 -> sub_108c960 : 28 -> 32
~ sub_108cbc8 -> sub_108cc04 : 344 -> 352
CStrings:
+ "17:40:09"
+ "AppleSPUFirmware-2001.120.14~251"
+ "Apr  6 2025"
- "18:20:21"
- "AppleSPUFirmware-2001.120.9~127"
- "Mar 21 2025"
```
