## agx_a000

> `Firmware/agx/armfw_g14d.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4aff0
+  __TEXT.__text: 0x4b008
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1230
+  __TEXT.__gxf_code: 0x1270
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1fe8
+  __TEXT.__const: 0x1fe0
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_ffffff8000004aa8 : 5228 -> 5232
~ sub_ffffff8000022630 -> sub_ffffff8000022634 : 520 -> 528
~ sub_ffffff8000022838 -> sub_ffffff8000022844 : 380 -> 388
~ sub_ffffff800002ccb0 -> sub_ffffff800002ccc4 : 1840 -> 1820
~ sub_ffffff800002ef1c : 556 -> 560
~ sub_ffffff800002fe14 -> sub_ffffff800002fe18 : 780 -> 776
~ sub_ffffff800003032c : 672 -> 668
~ sub_ffffff80000306f4 -> sub_ffffff80000306f0 : 1628 -> 1636
~ sub_ffffff8000031aec -> sub_ffffff8000031af0 : 7892 -> 7896
~ sub_ffffff8000035fa4 -> sub_ffffff8000035fac : 1252 -> 1256
~ sub_ffffff800003710c -> sub_ffffff8000037118 : 7192 -> 7204
~ sub_ffffff800004aeb0 -> sub_ffffff800004aec8 : 320 -> 328
CStrings:
+ "Jun 11 2025 21:14:50"
- "Apr 22 2025 19:45:36"
```
