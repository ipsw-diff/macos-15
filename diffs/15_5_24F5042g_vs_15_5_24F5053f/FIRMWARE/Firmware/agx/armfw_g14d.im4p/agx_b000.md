## agx_b000

> `Firmware/agx/armfw_g14d.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4ab7c
+  __TEXT.__text: 0x4ab2c
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1fc0
+  __TEXT.__const: 0x1fc8
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_ffffff8000003298 : 456 -> 460
~ sub_ffffff8000007e54 -> sub_ffffff8000007e58 : 3524 -> 3520
~ sub_ffffff8000009854 : 2096 -> 2100
~ sub_ffffff800000a084 -> sub_ffffff800000a088 : 5948 -> 5956
~ sub_ffffff800000fa48 -> sub_ffffff800000fa54 : 804 -> 808
~ sub_ffffff80000203b0 -> sub_ffffff80000203c0 : 928 -> 912
~ sub_ffffff80000238a8 : 18024 -> 17956
~ sub_ffffff800002a388 -> sub_ffffff800002a344 : 2880 -> 2876
~ sub_ffffff800002c6b8 -> sub_ffffff800002c670 : 1104 -> 1100
~ sub_ffffff800003671c -> sub_ffffff80000366d0 : 784 -> 788
~ sub_ffffff8000036cec -> sub_ffffff8000036ca4 : 7108 -> 7100
CStrings:
+ "Apr 10 2025 20:17:48"
- "Mar 26 2025 22:16:58"
```
