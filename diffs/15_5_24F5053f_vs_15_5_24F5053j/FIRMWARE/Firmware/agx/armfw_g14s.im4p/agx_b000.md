## agx_b000

> `Firmware/agx/armfw_g14s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x49f28
+  __TEXT.__text: 0x49f24
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
Functions:
~ sub_ffffff8000021e8c : 400 -> 396
~ sub_ffffff8000049de8 -> sub_ffffff8000049de4 : 328 -> 320
CStrings:
+ "Apr 15 2025 21:29:28"
- "Apr 10 2025 20:17:38"
```
