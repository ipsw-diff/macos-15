## agx_a000

> `Firmware/agx/armfw_g14c.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4a704
+  __TEXT.__text: 0x4a71c
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1230
+  __TEXT.__gxf_code: 0x1270
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1fa8
+  __TEXT.__const: 0x1fa0
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_ffffff8000004994 : 5212 -> 5216
~ sub_ffffff8000021f80 -> sub_ffffff8000021f84 : 372 -> 380
~ sub_ffffff80000220f4 -> sub_ffffff8000022100 : 380 -> 388
~ sub_ffffff800002c4d8 -> sub_ffffff800002c4ec : 1696 -> 1676
~ sub_ffffff800002e690 : 556 -> 560
~ sub_ffffff800002f588 -> sub_ffffff800002f58c : 780 -> 776
~ sub_ffffff800002faa0 : 672 -> 668
~ sub_ffffff800002fe68 -> sub_ffffff800002fe64 : 1628 -> 1636
~ sub_ffffff8000031230 -> sub_ffffff8000031234 : 7892 -> 7896
~ sub_ffffff80000356e8 -> sub_ffffff80000356f0 : 1252 -> 1256
~ sub_ffffff8000036850 -> sub_ffffff800003685c : 7144 -> 7156
~ sub_ffffff800004a5c4 -> sub_ffffff800004a5dc : 320 -> 328
CStrings:
+ "Jun 11 2025 21:14:48"
- "Apr 22 2025 19:45:34"
```
