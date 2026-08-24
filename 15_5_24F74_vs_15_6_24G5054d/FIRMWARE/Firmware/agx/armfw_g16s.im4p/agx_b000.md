## agx_b000

> `Firmware/agx/armfw_g16s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4a350
+  __TEXT.__text: 0x4a254
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1230
+  __TEXT.__gxf_code: 0x1270
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1198
+  __TEXT.__const: 0x1194
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x6a0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000003664 : 4852 -> 4856
~ sub_fffffc0000004958 -> sub_fffffc000000495c : 5072 -> 5076
~ sub_fffffc000000f120 -> sub_fffffc000000f128 : 668 -> 664
~ sub_fffffc0000011a90 -> sub_fffffc0000011a94 : 12304 -> 12296
~ sub_fffffc0000014aa0 -> sub_fffffc0000014a9c : 332 -> 320
~ sub_fffffc0000014bec -> sub_fffffc0000014bdc : 1804 -> 1768
~ sub_fffffc0000015748 -> sub_fffffc0000015714 : 9000 -> 8944
~ sub_fffffc000002f2a0 -> sub_fffffc000002f234 : 528 -> 532
~ sub_fffffc000002fd60 -> sub_fffffc000002fcf8 : 636 -> 632
~ sub_fffffc00000301e8 -> sub_fffffc000003017c : 640 -> 636
~ sub_fffffc0000030590 -> sub_fffffc0000030520 : 1880 -> 1884
~ sub_fffffc00000312d4 -> sub_fffffc0000031268 : 2252 -> 2256
~ sub_fffffc000003234c -> sub_fffffc00000322e4 : 7052 -> 7048
~ sub_fffffc00000353a0 -> sub_fffffc0000035334 : 6088 -> 6096
~ sub_fffffc0000037254 -> sub_fffffc00000371f0 : 3164 -> 3012
CStrings:
+ "Jun 11 2025 21:18:22"
- "Apr 22 2025 19:49:20"
```
