## agx_a000

> `Firmware/agx/armfw_g13x.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4153c
+  __TEXT.__text: 0x4154c
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x12b8
   __TEXT.__gxf_code_pad: 0x0
Functions:
~ sub_ffffff800000e8d4 : 15712 -> 15720
~ sub_ffffff800001d8bc -> sub_ffffff800001d8c4 : 664 -> 672
CStrings:
+ "Apr 15 2025 21:25:56"
- "Apr 10 2025 20:13:34"
```
