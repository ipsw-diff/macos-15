## agx_a000

> `Firmware/agx/armfw_g13x.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x41534
+  __TEXT.__text: 0x4153c
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x12b8
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1f98
+  __TEXT.__const: 0x1fa0
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x1e8
   __TEXT.__chain_starts: 0x24
Functions:
~ sub_ffffff8000006b74 : 3620 -> 3616
~ sub_ffffff8000008518 -> sub_ffffff8000008514 : 812 -> 816
~ sub_ffffff8000008844 : 1520 -> 1524
~ sub_ffffff8000008e34 -> sub_ffffff8000008e38 : 3592 -> 3628
~ sub_ffffff800000c970 -> sub_ffffff800000c998 : 1528 -> 1532
~ sub_ffffff800001a358 -> sub_ffffff800001a384 : 936 -> 940
~ sub_ffffff800001def8 -> sub_ffffff800001df28 : 3852 -> 3800
~ sub_ffffff8000021700 -> sub_ffffff80000216fc : 4152 -> 4148
~ sub_ffffff800002ecac -> sub_ffffff800002eca4 : 4268 -> 4284
~ sub_ffffff80000413f4 -> sub_ffffff80000413fc : 320 -> 328
CStrings:
+ "Apr 10 2025 20:13:34"
- "Mar 26 2025 22:12:43"
```
