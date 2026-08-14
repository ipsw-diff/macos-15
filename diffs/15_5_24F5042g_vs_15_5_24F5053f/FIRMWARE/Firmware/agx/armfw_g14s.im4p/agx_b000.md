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

-  __TEXT.__text: 0x49f70
+  __TEXT.__text: 0x49f28
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1f88
+  __TEXT.__const: 0x1f90
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_ffffff8000003298 : 456 -> 460
~ sub_ffffff80000076ec -> sub_ffffff80000076f0 : 3452 -> 3448
~ sub_ffffff80000090a4 : 2096 -> 2100
~ sub_ffffff80000098d4 -> sub_ffffff80000098d8 : 5948 -> 5956
~ sub_ffffff800000f24c -> sub_ffffff800000f258 : 804 -> 808
~ sub_ffffff800001fb5c -> sub_ffffff800001fb6c : 928 -> 912
~ sub_ffffff80000225f4 : 684 -> 688
~ sub_ffffff8000022ab4 -> sub_ffffff8000022ab8 : 788 -> 792
~ sub_ffffff8000022e88 -> sub_ffffff8000022e90 : 18020 -> 17952
~ sub_ffffff8000029964 -> sub_ffffff8000029928 : 2880 -> 2876
~ sub_ffffff800002bc94 -> sub_ffffff800002bc54 : 984 -> 980
~ sub_ffffff8000035b3c -> sub_ffffff8000035af8 : 784 -> 788
~ sub_ffffff800003610c -> sub_ffffff80000360cc : 7064 -> 7056
~ sub_ffffff8000049e30 -> sub_ffffff8000049de8 : 320 -> 328
CStrings:
+ "Apr 10 2025 20:17:38"
- "Mar 26 2025 22:16:53"
```
