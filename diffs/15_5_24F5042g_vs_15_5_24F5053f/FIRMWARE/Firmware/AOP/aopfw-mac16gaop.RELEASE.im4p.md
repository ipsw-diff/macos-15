## aopfw-mac16gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16gaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__DATA.__const`
- `__DATA.__data`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_patchbay`
- `__DATA.__mod_init_func`
- `__DATA.__version`
- `__DATA._rtk_mtab`
- `__ETEXT.__eh_frame`

```diff

-  __TEXT.__text: 0xba814
-  __TEXT.__const: 0xa254
-  __TEXT.__cstring: 0x5871
+  __TEXT.__text: 0xba85c
+  __TEXT.__const: 0xa248
+  __TEXT.__cstring: 0x587b
   __TEXT.__chain_starts: 0x5c
   __DATA._rtk_boot: 0x3000
   __DATA._rtk_page_tables: 0x5000

   __DATA.__constructor: 0x0
   __DATA._rtk_mtab: 0x5d0
   __DATA.__zerofill: 0xaa0d8
-  __ETEXT.__text: 0x12184
+  __ETEXT.__text: 0x12194
   __ETEXT.__eh_frame: 0x40
   __ETEXT.__StaticInit: 0x1fe4
   __ETEXT.__const: 0x530

   __CMA.__cma_log_string: 0x11b3
   Functions: 2888
   Symbols:   0
-  CStrings:  1015
+  CStrings:  1016
 
Functions:
~ sub_10754cc : 1636 -> 1652
~ sub_108e580 -> sub_108e590 : 96 -> 108
~ sub_108e5e0 -> sub_108e5fc : 72 -> 76
~ sub_108e66c -> sub_108e68c : 348 -> 396
~ sub_10902f4 -> sub_1090344 : 456 -> 464
~ sub_1091e24 -> sub_1091e7c : 356 -> 360
~ sub_1091f88 -> sub_1091fe4 : 516 -> 520
~ sub_1097a00 -> sub_1097a60 : 2124 -> 2132
~ sub_109824c -> sub_10982b4 : 1672 -> 1648
~ sub_1098970 -> sub_10989c0 : 648 -> 664
~ sub_10b55f0 -> sub_10b5650 : 248 -> 232
~ sub_10b5d64 -> sub_10b5db4 : 1172 -> 1188
~ sub_10b646c -> sub_10b64cc : 1052 -> 1040
~ sub_10b6888 -> sub_10b68dc : 336 -> 348
~ sub_10b7828 -> sub_10b7888 : 44 -> 28
~ sub_10b7854 -> sub_10b78a4 : 308 -> 340
~ sub_10b7e24 -> sub_10b7e94 : 228 -> 212
~ sub_10b8164 -> sub_10b81c4 : 3820 -> 3828
~ sub_10b9050 -> sub_10b90b8 : 304 -> 296
~ sub_10ba1bc -> sub_10ba21c : 148 -> 124
~ sub_10ba6d8 -> sub_10ba720 : 316 -> 324
CStrings:
+ "17:40:19"
+ "17:45:35"
+ "17:45:36"
+ "AppleSPUFirmware-2001.120.14~251"
+ "Apr  6 2025"
- "18:20:32"
- "18:26:50"
- "AppleSPUFirmware-2001.120.9~127"
- "Mar 21 2025"
```
