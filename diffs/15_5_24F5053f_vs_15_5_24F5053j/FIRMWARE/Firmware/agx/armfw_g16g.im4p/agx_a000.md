## agx_a000

> `Firmware/agx/armfw_g16g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4e270
+  __TEXT.__text: 0x4e26c
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1458
   __TEXT.__gxf_code_pad: 0x0
Functions:
~ sub_fffffc0000028cf4 : 400 -> 396
~ sub_fffffc000004e134 -> sub_fffffc000004e130 : 316 -> 324
CStrings:
+ "Apr 15 2025 21:26:47"
- "Apr 10 2025 20:14:26"
```
