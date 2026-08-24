## agx_b000

> `Firmware/agx/armfw_g14s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x49f24
+  __TEXT.__text: 0x49f20
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1230
+  __TEXT.__gxf_code: 0x1270
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1f90
+  __TEXT.__const: 0x1f88
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_ffffff8000004994 : 5212 -> 5216
~ sub_ffffff8000021be4 -> sub_ffffff8000021be8 : 300 -> 308
~ sub_ffffff8000021d10 -> sub_ffffff8000021d1c : 380 -> 388
~ sub_ffffff800002c024 -> sub_ffffff800002c038 : 1628 -> 1604
~ sub_ffffff800002dfd0 -> sub_ffffff800002dfcc : 556 -> 560
~ sub_ffffff800002eec8 : 780 -> 776
~ sub_ffffff800002f3e0 -> sub_ffffff800002f3dc : 620 -> 616
~ sub_ffffff800002f774 -> sub_ffffff800002f76c : 1532 -> 1528
~ sub_ffffff8000030abc -> sub_ffffff8000030ab0 : 7892 -> 7896
~ sub_ffffff8000034f74 -> sub_ffffff8000034f6c : 1252 -> 1256
CStrings:
+ "Jun 11 2025 21:17:15"
- "Apr 22 2025 19:48:17"
```
