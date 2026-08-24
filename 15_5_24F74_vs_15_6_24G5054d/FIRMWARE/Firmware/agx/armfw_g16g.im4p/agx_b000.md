## agx_b000

> `Firmware/agx/armfw_g16g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4dde4
+  __TEXT.__text: 0x4de00
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1458
+  __TEXT.__gxf_code: 0x1498
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1c8c
+  __TEXT.__const: 0x1c88
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x6a0
   __TEXT.__chain_starts: 0x30
Functions:
~ sub_fffffc00000054dc : 6068 -> 6072
~ sub_fffffc000002d98c -> sub_fffffc000002d990 : 1480 -> 1504
~ sub_fffffc00000319e4 -> sub_fffffc0000031a00 : 372 -> 376
~ sub_fffffc0000032098 -> sub_fffffc00000320b8 : 784 -> 780
~ sub_fffffc00000325b4 -> sub_fffffc00000325d0 : 620 -> 616
~ sub_fffffc0000033bf4 -> sub_fffffc0000033c0c : 8620 -> 8616
~ sub_fffffc000003836c -> sub_fffffc0000038380 : 2132 -> 2136
~ sub_fffffc0000039b4c -> sub_fffffc0000039b64 : 5160 -> 5164
CStrings:
+ "Jun 11 2025 21:17:46"
- "Apr 22 2025 19:48:48"
```
