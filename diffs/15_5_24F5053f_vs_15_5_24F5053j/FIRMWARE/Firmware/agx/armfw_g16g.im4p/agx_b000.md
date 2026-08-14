## agx_b000

> `Firmware/agx/armfw_g16g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4dde8
+  __TEXT.__text: 0x4dde4
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1458
   __TEXT.__gxf_code_pad: 0x0
Functions:
~ sub_fffffc00000288f0 : 400 -> 396
~ sub_fffffc000004dcac -> sub_fffffc000004dca8 : 324 -> 316
CStrings:
+ "Apr 15 2025 21:29:58"
- "Apr 10 2025 20:18:17"
```
