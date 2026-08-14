## aopfw-mac15saop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac15saop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA.__version`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x9b100
+  __TEXT.__text: 0x9b134
   __TEXT.__const: 0x5408
-  __TEXT.__cstring: 0x5e5c
+  __TEXT.__cstring: 0x5e5d
   __TEXT.__chain_starts: 0x3c
   __DATA._rtk_boot: 0x3000
   __DATA._rtk_page_tables: 0x5000

   __DATA._rtk_mtab: 0x628
   __DATA.__zerofill: 0xb9360
   __ETEXT.__eh_frame: 0x40
-  __ETEXT.__text: 0x16084
+  __ETEXT.__text: 0x16094
   __ETEXT.__StaticInit: 0x2bb8
   __ETEXT.__const: 0xb61
   __OS_LOG.__string: 0x123f1
Functions:
~ sub_1013d38 : 256 -> 232
~ sub_1013f20 -> sub_1013f08 : 132 -> 140
~ sub_102af28 -> sub_102af18 : 96 -> 108
~ sub_102af88 -> sub_102af84 : 72 -> 76
~ sub_102b014 : 348 -> 396
~ sub_102e7dc -> sub_102e80c : 356 -> 360
~ sub_102e940 -> sub_102e974 : 516 -> 520
~ sub_10343d8 -> sub_1034410 : 2108 -> 2116
~ sub_1034c14 -> sub_1034c54 : 1680 -> 1648
~ sub_1035340 -> sub_1035360 : 644 -> 656
~ sub_1044568 -> sub_1044594 : 408 -> 412
~ sub_109767c -> sub_10976ac : 156 -> 140
~ sub_1097b10 -> sub_1097b30 : 1844 -> 1860
~ sub_10984ec -> sub_109851c : 1000 -> 1024
~ sub_10988d4 -> sub_109891c : 320 -> 308
~ sub_1099cc4 -> sub_1099d00 : 1228 -> 1248
~ sub_109a190 -> sub_109a1e0 : 2904 -> 2876
CStrings:
+ "17:40:09"
+ "17:45:33"
+ "AppleSPUFirmware-2001.120.14~251"
+ "Apr  6 2025"
- "18:20:21"
- "18:26:46"
- "AppleSPUFirmware-2001.120.9~127"
- "Mar 21 2025"
```
