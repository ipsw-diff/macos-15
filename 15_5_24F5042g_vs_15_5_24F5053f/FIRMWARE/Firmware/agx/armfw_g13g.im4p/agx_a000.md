## agx_a000

> `Firmware/agx/armfw_g13g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x3dab0
+  __TEXT.__text: 0x3da94
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x12b8
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1d50
+  __TEXT.__const: 0x1d54
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x1e8
   __TEXT.__chain_starts: 0x20
Functions:
~ sub_ffffff8000006b10 : 3200 -> 3196
~ sub_ffffff800000829c -> sub_ffffff8000008298 : 812 -> 816
~ sub_ffffff80000085c8 : 1496 -> 1500
~ sub_ffffff8000008ba0 -> sub_ffffff8000008ba4 : 3096 -> 3092
~ sub_ffffff8000019c2c : 824 -> 832
~ sub_ffffff800001d338 -> sub_ffffff800001d340 : 3928 -> 3876
~ sub_ffffff800001fe50 -> sub_ffffff800001fe24 : 4044 -> 4040
~ sub_ffffff800002c96c -> sub_ffffff800002c93c : 4824 -> 4844
CStrings:
+ "Apr 10 2025 20:13:30"
- "Mar 26 2025 22:12:39"
```
