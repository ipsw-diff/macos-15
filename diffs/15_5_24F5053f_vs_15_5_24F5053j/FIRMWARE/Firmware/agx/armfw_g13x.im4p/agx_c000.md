## agx_c000

> `Firmware/agx/armfw_g13x.im4p/agx_c000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x414f8
+  __TEXT.__text: 0x41508
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x12b8
   __TEXT.__gxf_code_pad: 0x0
Functions:
~ sub_ffffff800000e944 : 15532 -> 15540
~ sub_ffffff800001d878 -> sub_ffffff800001d880 : 664 -> 672
CStrings:
+ "Apr 15 2025 21:28:12"
- "Apr 10 2025 20:16:02"
```
