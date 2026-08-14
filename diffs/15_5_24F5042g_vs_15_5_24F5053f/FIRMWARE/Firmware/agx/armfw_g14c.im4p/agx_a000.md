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

-  __TEXT.__text: 0x4a758
+  __TEXT.__text: 0x4a708
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1fa0
+  __TEXT.__const: 0x1fa8
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_ffffff8000003298 : 456 -> 460
~ sub_ffffff80000078b4 -> sub_ffffff80000078b8 : 3408 -> 3404
~ sub_ffffff8000009240 : 2096 -> 2100
~ sub_ffffff8000009a70 -> sub_ffffff8000009a74 : 5948 -> 5956
~ sub_ffffff800000f3e8 -> sub_ffffff800000f3f4 : 804 -> 808
~ sub_ffffff800001fef8 -> sub_ffffff800001ff08 : 928 -> 912
~ sub_ffffff8000023334 : 18024 -> 17956
~ sub_ffffff8000029e14 -> sub_ffffff8000029dd0 : 2880 -> 2876
~ sub_ffffff800002c144 -> sub_ffffff800002c0fc : 996 -> 992
~ sub_ffffff80000362cc -> sub_ffffff8000036280 : 784 -> 788
~ sub_ffffff800003689c -> sub_ffffff8000036854 : 7152 -> 7144
CStrings:
+ "Apr 10 2025 20:14:14"
- "Mar 26 2025 22:13:26"
```
