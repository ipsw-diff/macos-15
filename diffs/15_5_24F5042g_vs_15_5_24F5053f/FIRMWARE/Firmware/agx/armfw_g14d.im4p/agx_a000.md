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

-  __TEXT.__text: 0x4b044
+  __TEXT.__text: 0x4aff4
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1fe0
+  __TEXT.__const: 0x1fe8
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_ffffff8000003298 : 456 -> 460
~ sub_ffffff8000007e54 -> sub_ffffff8000007e58 : 3508 -> 3504
~ sub_ffffff8000009844 : 2096 -> 2100
~ sub_ffffff800000a074 -> sub_ffffff800000a078 : 5948 -> 5956
~ sub_ffffff800000fa38 -> sub_ffffff800000fa44 : 804 -> 808
~ sub_ffffff80000205a8 -> sub_ffffff80000205b8 : 928 -> 912
~ sub_ffffff8000023aa0 : 18024 -> 17956
~ sub_ffffff800002a580 -> sub_ffffff800002a53c : 2880 -> 2876
~ sub_ffffff800002c8b0 -> sub_ffffff800002c868 : 1104 -> 1100
~ sub_ffffff8000036b88 -> sub_ffffff8000036b3c : 784 -> 788
~ sub_ffffff8000037158 -> sub_ffffff8000037110 : 7200 -> 7192
CStrings:
+ "Apr 10 2025 20:14:17"
- "Mar 26 2025 22:13:27"
```
