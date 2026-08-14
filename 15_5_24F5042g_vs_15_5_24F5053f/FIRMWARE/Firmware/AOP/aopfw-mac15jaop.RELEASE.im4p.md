## aopfw-mac15jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac15jaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_mtab`
- `__DATA.__version`

```diff

-  __TEXT.__text: 0xac0d4
+  __TEXT.__text: 0xac108
   __TEXT.__const: 0x53d8
-  __TEXT.__cstring: 0x5e7f
+  __TEXT.__cstring: 0x5e80
   __TEXT.__chain_starts: 0x44
   __DATA._rtk_boot: 0x3000
   __DATA.__mod_init_func: 0x120

   __DATA.__zerofill: 0xb9c60
   __ETEXT.__StaticInit: 0x2cac
   __ETEXT.__eh_frame: 0x40
-  __ETEXT.__text: 0x16060
+  __ETEXT.__text: 0x16070
   __ETEXT.__const: 0xb61
   __OS_LOG.__string: 0x124ac
   __MISC.__apf_list: 0x70
Functions:
~ sub_102dd34 : 256 -> 232
~ sub_102df1c -> sub_102df04 : 132 -> 140
~ sub_1044f2c -> sub_1044f1c : 96 -> 108
~ sub_1044f8c -> sub_1044f88 : 72 -> 76
~ sub_1045018 : 348 -> 396
~ sub_10487e0 -> sub_1048810 : 356 -> 360
~ sub_1048944 -> sub_1048978 : 516 -> 520
~ sub_104e3dc -> sub_104e414 : 2108 -> 2116
~ sub_104ec18 -> sub_104ec58 : 1680 -> 1648
~ sub_104f344 -> sub_104f364 : 644 -> 656
~ sub_105d798 -> sub_105d7c4 : 408 -> 412
~ sub_10a8920 -> sub_10a8950 : 348 -> 332
~ sub_10a8d0c -> sub_10a8d2c : 1608 -> 1624
~ sub_10a93e0 -> sub_10a9410 : 572 -> 560
~ sub_10a961c -> sub_10a9640 : 120 -> 132
~ sub_10a9694 -> sub_10a96c4 : 1052 -> 1064
~ sub_10aad4c -> sub_10aad88 : 1160 -> 1152
~ sub_10abf7c -> sub_10abfb0 : 344 -> 352
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
