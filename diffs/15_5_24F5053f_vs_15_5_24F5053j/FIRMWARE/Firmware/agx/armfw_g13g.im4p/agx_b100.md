## agx_b100

> `Firmware/agx/armfw_g13g.im4p/agx_b100`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x3db04
+  __TEXT.__text: 0x3db18
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x12b8
   __TEXT.__gxf_code_pad: 0x0
Functions:
~ sub_ffffff800000e120 : 15396 -> 15408
~ sub_ffffff800001cd2c -> sub_ffffff800001cd38 : 664 -> 672
~ sub_ffffff800003d9c4 -> sub_ffffff800003d9d8 : 320 -> 328
CStrings:
+ "Apr 15 2025 21:30:39"
- "Apr 10 2025 20:19:07"
```
