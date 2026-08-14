## agx_a000

> `Firmware/agx/armfw_g15s.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4b608
+  __TEXT.__text: 0x4b5a8
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0xfb8
+  __TEXT.__const: 0xfc0
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000007ac8 : 17600 -> 17596
~ sub_fffffc000000cba4 -> sub_fffffc000000cba0 : 816 -> 820
~ sub_fffffc000000ced4 : 1784 -> 1788
~ sub_fffffc000000d5cc -> sub_fffffc000000d5d0 : 4524 -> 4536
~ sub_fffffc0000012108 -> sub_fffffc0000012118 : 804 -> 808
~ sub_fffffc00000296d8 -> sub_fffffc00000296ec : 6584 -> 6452
~ sub_fffffc0000038210 -> sub_fffffc00000381a0 : 4448 -> 4464
CStrings:
+ "Apr 10 2025 20:14:49"
- "Mar 26 2025 22:14:00"
```
