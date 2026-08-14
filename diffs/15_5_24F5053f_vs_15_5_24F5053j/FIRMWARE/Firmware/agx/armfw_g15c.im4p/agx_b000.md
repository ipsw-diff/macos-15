## agx_b000

> `Firmware/agx/armfw_g15c.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4e018
+  __TEXT.__text: 0x4e014
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
Functions:
~ sub_fffffc00000277e4 : 392 -> 388
~ sub_fffffc000004dedc -> sub_fffffc000004ded8 : 324 -> 316
CStrings:
+ "Apr 15 2025 21:30:44"
- "Apr 10 2025 20:19:16"
```
