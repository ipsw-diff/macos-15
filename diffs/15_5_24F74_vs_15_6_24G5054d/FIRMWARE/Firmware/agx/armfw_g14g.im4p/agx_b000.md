## agx_b000

> `Firmware/agx/armfw_g14g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4d9b0
+  __TEXT.__text: 0x4d9d0
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1230
+  __TEXT.__gxf_code: 0x1270
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1eb4
+  __TEXT.__const: 0x1eb0
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_ffffff80000045c8 : 7400 -> 7404
~ sub_ffffff8000026018 -> sub_ffffff800002601c : 1408 -> 1432
~ sub_ffffff800003115c -> sub_ffffff8000031178 : 372 -> 376
~ sub_ffffff8000031964 -> sub_ffffff8000031984 : 652 -> 648
~ sub_ffffff8000031dfc -> sub_ffffff8000031e18 : 620 -> 616
~ sub_ffffff8000039548 -> sub_ffffff8000039560 : 1100 -> 1104
~ sub_ffffff800003a5d0 -> sub_ffffff800003a5ec : 6192 -> 6196
CStrings:
+ "Jun 11 2025 21:16:41"
- "Apr 22 2025 19:47:38"
```
