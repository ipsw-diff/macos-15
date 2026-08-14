## agx_b000

> `Firmware/agx/armfw_g15d.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4f248
+  __TEXT.__text: 0x4f244
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
Functions:
~ sub_fffffc000002845c : 392 -> 388
~ sub_fffffc000004f10c -> sub_fffffc000004f108 : 324 -> 316
CStrings:
+ "Apr 15 2025 21:30:45"
- "Apr 10 2025 20:19:20"
```
