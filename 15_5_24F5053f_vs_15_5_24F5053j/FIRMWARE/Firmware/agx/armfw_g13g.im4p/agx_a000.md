## agx_a000

> `Firmware/agx/armfw_g13g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x3da94
+  __TEXT.__text: 0x3daa8
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x12b8
   __TEXT.__gxf_code_pad: 0x0
Functions:
~ sub_ffffff800000e0c8 : 15396 -> 15408
~ sub_ffffff800001ccd4 -> sub_ffffff800001cce0 : 664 -> 672
~ sub_ffffff800003d954 -> sub_ffffff800003d968 : 320 -> 328
CStrings:
+ "Apr 15 2025 21:25:51"
- "Apr 10 2025 20:13:30"
```
