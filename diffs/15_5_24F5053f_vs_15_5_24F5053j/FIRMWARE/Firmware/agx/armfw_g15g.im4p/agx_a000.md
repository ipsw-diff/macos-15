## agx_a000

> `Firmware/agx/armfw_g15g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4b100
+  __TEXT.__text: 0x4b0fc
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
Functions:
~ sub_fffffc000002631c : 392 -> 388
~ sub_fffffc000004afc0 -> sub_fffffc000004afbc : 320 -> 328
CStrings:
+ "Apr 15 2025 21:26:33"
- "Apr 10 2025 20:14:13"
```
