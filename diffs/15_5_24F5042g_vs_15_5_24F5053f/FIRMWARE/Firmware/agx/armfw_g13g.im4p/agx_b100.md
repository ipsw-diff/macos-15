## agx_b100

> `Firmware/agx/armfw_g13g.im4p/agx_b100`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x3db20
+  __TEXT.__text: 0x3db04
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x12b8
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1d50
+  __TEXT.__const: 0x1d54
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x1e8
   __TEXT.__chain_starts: 0x20
Functions:
~ sub_ffffff8000006b10 : 3288 -> 3284
~ sub_ffffff80000082f4 -> sub_ffffff80000082f0 : 812 -> 816
~ sub_ffffff8000008620 : 1496 -> 1500
~ sub_ffffff8000008bf8 -> sub_ffffff8000008bfc : 3096 -> 3092
~ sub_ffffff8000019c84 : 824 -> 832
~ sub_ffffff800001d390 -> sub_ffffff800001d398 : 3952 -> 3900
~ sub_ffffff800001fec0 -> sub_ffffff800001fe94 : 4044 -> 4040
~ sub_ffffff800002c9dc -> sub_ffffff800002c9ac : 4824 -> 4844
CStrings:
+ "Apr 10 2025 20:19:07"
- "Mar 26 2025 22:18:18"
```
