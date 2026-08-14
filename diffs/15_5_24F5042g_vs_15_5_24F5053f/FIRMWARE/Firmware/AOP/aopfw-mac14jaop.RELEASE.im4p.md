## aopfw-mac14jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac14jaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_mtab`
- `__DATA.__version`

```diff

-  __TEXT.__text: 0x89378
+  __TEXT.__text: 0x893b4
   __TEXT.__const: 0x4d60
-  __TEXT.__cstring: 0x5886
+  __TEXT.__cstring: 0x5887
   __TEXT.__chain_starts: 0x48
   __DATA._rtk_boot: 0x2000
   __DATA.__mod_init_func: 0x120

   __DATA.__zerofill: 0x6feb8
   __ETEXT.__StaticInit: 0x877c
   __ETEXT.__eh_frame: 0x40
-  __ETEXT.__text: 0x10ddc
+  __ETEXT.__text: 0x10dec
   __ETEXT.__const: 0x43a
   __OS_LOG.__string: 0x10dbd
   __MISC.__apf_list: 0x70
Functions:
~ sub_1025cdc : 96 -> 108
~ sub_1025d3c -> sub_1025d48 : 72 -> 76
~ sub_1025dc8 -> sub_1025dd8 : 348 -> 396
~ sub_1029594 -> sub_10295d4 : 356 -> 360
~ sub_10296f8 -> sub_102973c : 516 -> 520
~ sub_102f19c -> sub_102f1e4 : 2084 -> 2092
~ sub_102f9c0 -> sub_102fa10 : 1680 -> 1648
~ sub_10300ec -> sub_103011c : 644 -> 656
~ sub_1085f7c -> sub_1085fb8 : 336 -> 320
~ sub_108631c -> sub_1086348 : 1528 -> 1544
~ sub_1086af0 -> sub_1086b2c : 440 -> 420
~ sub_1086ca8 -> sub_1086cd0 : 764 -> 784
~ sub_1087c60 -> sub_1087c9c : 1972 -> 1984
~ sub_1088414 -> sub_108845c : 2252 -> 2240
~ sub_1089220 -> sub_108925c : 352 -> 344
CStrings:
+ "17:40:09"
+ "AppleSPUFirmware-2001.120.14~251"
+ "Apr  6 2025"
- "18:20:21"
- "AppleSPUFirmware-2001.120.9~127"
- "Mar 21 2025"
```
