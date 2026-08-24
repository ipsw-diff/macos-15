## agx_c000

> `Firmware/agx/armfw_g13x.im4p/agx_c000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x41508
+  __TEXT.__text: 0x4154c
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x12b8
+  __TEXT.__gxf_code: 0x12f8
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1fa0
+  __TEXT.__const: 0x1f98
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x1e8
   __TEXT.__chain_starts: 0x24
Functions:
~ sub_ffffff800000460c : 6832 -> 6836
~ sub_ffffff8000006c18 -> sub_ffffff8000006c1c : 3564 -> 3592
~ sub_ffffff8000022cec -> sub_ffffff8000022d0c : 1648 -> 1672
~ sub_ffffff8000025990 -> sub_ffffff80000259c8 : 228 -> 232
~ sub_ffffff8000026254 -> sub_ffffff8000026290 : 720 -> 716
~ sub_ffffff8000026730 -> sub_ffffff8000026768 : 620 -> 616
~ sub_ffffff8000026ad8 -> sub_ffffff8000026b0c : 1152 -> 1156
~ sub_ffffff800002dbe0 -> sub_ffffff800002dc18 : 1100 -> 1104
~ sub_ffffff800002ec70 -> sub_ffffff800002ecac : 4284 -> 4292
CStrings:
+ "Jun 11 2025 21:16:13"
- "Apr 22 2025 19:47:00"
```
