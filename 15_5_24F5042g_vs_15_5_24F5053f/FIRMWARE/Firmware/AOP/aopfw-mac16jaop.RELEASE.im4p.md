## aopfw-mac16jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16jaop.RELEASE.im4p`

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

-  __TEXT.__text: 0xd1164
-  __TEXT.__const: 0x993c
-  __TEXT.__cstring: 0x5041
+  __TEXT.__text: 0xd11ac
+  __TEXT.__const: 0x9938
+  __TEXT.__cstring: 0x504b
   __TEXT.__chain_starts: 0x58
   __DATA._rtk_boot: 0x2000
   __DATA._rtk_page_tables: 0x5000

   __DATA._rtk_mtab: 0x5e8
   __DATA.__zerofill: 0xaf9f8
   __ETEXT.__eh_frame: 0x40
-  __ETEXT.__text: 0x10f80
+  __ETEXT.__text: 0x10f90
   __ETEXT.__StaticInit: 0x1b08
   __ETEXT.__const: 0x43a
   __OS_LOG.__string: 0x2969c

   __CMA.__cma_log_string: 0x11b3
   Functions: 2668
   Symbols:   0
-  CStrings:  959
+  CStrings:  960
 
Functions:
~ sub_1026b5c : 96 -> 108
~ sub_1026bbc -> sub_1026bc8 : 72 -> 76
~ sub_1026c48 -> sub_1026c58 : 348 -> 396
~ sub_10288d8 -> sub_1028918 : 456 -> 464
~ sub_102a408 -> sub_102a450 : 356 -> 360
~ sub_102a56c -> sub_102a5b8 : 512 -> 516
~ sub_1030010 -> sub_1030060 : 2124 -> 2132
~ sub_103085c -> sub_10308b4 : 1672 -> 1648
~ sub_1030f80 -> sub_1030fc0 : 640 -> 656
~ sub_10a93dc -> sub_10a942c : 1636 -> 1652
~ sub_10cd3e0 -> sub_10cd440 : 220 -> 204
~ sub_10cd6d0 -> sub_10cd720 : 348 -> 356
~ sub_10cd82c -> sub_10cd884 : 308 -> 300
~ sub_10cddd8 -> sub_10cde28 : 176 -> 192
~ sub_10cdfc4 -> sub_10ce024 : 808 -> 796
~ sub_10ce2ec -> sub_10ce340 : 400 -> 412
~ sub_10ce53c -> sub_10ce59c : 776 -> 760
~ sub_10ce844 -> sub_10ce894 : 64 -> 80
~ sub_10cf468 -> sub_10cf4c8 : 1180 -> 1168
~ sub_10cf904 -> sub_10cf958 : 2092 -> 2104
~ sub_10d01f8 -> sub_10d0258 : 2744 -> 2720
~ sub_10d1028 -> sub_10d1070 : 316 -> 324
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
