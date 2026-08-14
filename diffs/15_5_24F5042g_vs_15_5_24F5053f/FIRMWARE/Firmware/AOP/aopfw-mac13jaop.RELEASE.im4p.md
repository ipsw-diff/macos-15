## aopfw-mac13jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac13jaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA.__mod_init_func`
- `__DATA.__version`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x83d6c
+  __TEXT.__text: 0x83db8
   __TEXT.__const: 0x4bd0
-  __TEXT.__cstring: 0x12923
+  __TEXT.__cstring: 0x12924
   __TEXT.__chain_starts: 0x44
   __DATA._rtk_boot: 0x2000
   __DATA._rtk_page_tables: 0x4000

   __DATA._rtk_mtab: 0x610
   __DATA.__zerofill: 0x6ef90
   __ETEXT.__eh_frame: 0x40
-  __ETEXT.__text: 0xe6a8
+  __ETEXT.__text: 0xe6b8
   __ETEXT.__StaticInit: 0x744c
   __ETEXT.__const: 0x43a
   __OS_LOG.__string: 0x8a0
Functions:
~ sub_1011ee0 : 644 -> 660
~ sub_1024f08 -> sub_1024f18 : 96 -> 108
~ sub_1024f68 -> sub_1024f84 : 72 -> 76
~ sub_1024ff4 -> sub_1025014 : 348 -> 396
~ sub_1026c80 -> sub_1026cd0 : 448 -> 464
~ sub_10287b8 -> sub_1028818 : 356 -> 360
~ sub_102891c -> sub_1028980 : 516 -> 520
~ sub_102e3c0 -> sub_102e428 : 2084 -> 2092
~ sub_102ebe4 -> sub_102ec54 : 1664 -> 1648
~ sub_102f300 -> sub_102f360 : 644 -> 656
~ sub_1047aa0 -> sub_1047b0c : 1300 -> 1316
~ sub_10806e4 -> sub_1080760 : 1012 -> 996
~ sub_1080c00 -> sub_1080c6c : 2172 -> 2188
~ sub_1082674 -> sub_10826f0 : 2452 -> 2464
~ sub_1083008 -> sub_1083090 : 2256 -> 2244
~ sub_10838d8 -> sub_1083954 : 140 -> 92
CStrings:
+ "17:40:23"
+ "AppleSPUFirmware-2001.120.14~251"
+ "Apr  6 2025"
- "18:20:36"
- "AppleSPUFirmware-2001.120.9~127"
- "Mar 21 2025"
```
