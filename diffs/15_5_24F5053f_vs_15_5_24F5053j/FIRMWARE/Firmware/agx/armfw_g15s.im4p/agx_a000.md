## agx_a000

> `Firmware/agx/armfw_g15s.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4b5a8
+  __TEXT.__text: 0x4b5a4
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
Functions:
~ sub_fffffc0000026bbc : 392 -> 388
~ sub_fffffc000004b468 -> sub_fffffc000004b464 : 328 -> 320
CStrings:
+ "Apr 15 2025 21:27:09"
- "Apr 10 2025 20:14:49"
```
