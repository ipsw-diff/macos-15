## agx_b000

> `Firmware/agx/armfw_g16c.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4a4e4
+  __TEXT.__text: 0x4a3e8
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
~ sub_fffffc0000003664 : 4836 -> 4840
~ sub_fffffc0000004948 -> sub_fffffc000000494c : 5072 -> 5076
~ sub_fffffc000000f0fc -> sub_fffffc000000f104 : 668 -> 664
~ sub_fffffc0000011a6c -> sub_fffffc0000011a70 : 12304 -> 12296
~ sub_fffffc0000014a7c -> sub_fffffc0000014a78 : 332 -> 320
~ sub_fffffc0000014bc8 -> sub_fffffc0000014bb8 : 1804 -> 1768
~ sub_fffffc0000015724 -> sub_fffffc00000156f0 : 9000 -> 8944
~ sub_fffffc000002f3d8 -> sub_fffffc000002f36c : 528 -> 532
~ sub_fffffc000002fe98 -> sub_fffffc000002fe30 : 636 -> 632
~ sub_fffffc0000030320 -> sub_fffffc00000302b4 : 640 -> 636
~ sub_fffffc00000306c8 -> sub_fffffc0000030658 : 1880 -> 1884
~ sub_fffffc0000031468 -> sub_fffffc00000313fc : 2252 -> 2256
~ sub_fffffc00000324e0 -> sub_fffffc0000032478 : 7052 -> 7048
~ sub_fffffc0000035534 -> sub_fffffc00000354c8 : 6088 -> 6096
~ sub_fffffc00000373e8 -> sub_fffffc0000037384 : 3164 -> 3012
~ sub_fffffc000004a3a8 -> sub_fffffc000004a2ac : 316 -> 324
CStrings:
+ "Jun 11 2025 21:18:22"
- "Apr 22 2025 19:49:21"
```
