## agx_b000

> `Firmware/agx/armfw_g14g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4d99c
+  __TEXT.__text: 0x4d9b0
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
Functions:
~ sub_ffffff8000010ee8 : 16920 -> 16932
~ sub_ffffff8000020d2c -> sub_ffffff8000020d38 : 952 -> 960
~ sub_ffffff800004d85c -> sub_ffffff800004d870 : 328 -> 320
CStrings:
+ "Apr 15 2025 21:28:48"
- "Apr 10 2025 20:16:46"
```
