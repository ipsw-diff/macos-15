## agx_b000

> `Firmware/agx/armfw_g14c.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4a2a4
+  __TEXT.__text: 0x4a254
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
~ sub_ffffff80000078b4 -> sub_ffffff80000078b8 : 3436 -> 3432
~ sub_ffffff800000925c : 2096 -> 2100
~ sub_ffffff8000009a8c -> sub_ffffff8000009a90 : 5948 -> 5956
~ sub_ffffff800000f404 -> sub_ffffff800000f410 : 804 -> 808
~ sub_ffffff800001fd14 -> sub_ffffff800001fd24 : 928 -> 912
~ sub_ffffff8000023150 : 18024 -> 17956
~ sub_ffffff8000029c30 -> sub_ffffff8000029bec : 2880 -> 2876
~ sub_ffffff800002bf60 -> sub_ffffff800002bf18 : 996 -> 992
~ sub_ffffff8000035e74 -> sub_ffffff8000035e28 : 784 -> 788
~ sub_ffffff8000036444 -> sub_ffffff80000363fc : 7060 -> 7052
CStrings:
+ "Apr 10 2025 20:17:37"
- "Mar 26 2025 22:16:52"
```
