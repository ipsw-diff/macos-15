## agx_a000

> `Firmware/agx/armfw_g16s.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4a428
+  __TEXT.__text: 0x4a3d4
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1194
+  __TEXT.__const: 0x1198
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x6a0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc00000069c8 : 18880 -> 18876
~ sub_fffffc000000bd34 -> sub_fffffc000000bd30 : 736 -> 740
~ sub_fffffc000000c014 : 2148 -> 2152
~ sub_fffffc000000c878 -> sub_fffffc000000c87c : 4880 -> 4888
~ sub_fffffc000000dbc0 -> sub_fffffc000000dbcc : 1256 -> 1260
~ sub_fffffc0000010c10 -> sub_fffffc0000010c20 : 804 -> 808
~ sub_fffffc0000020d88 -> sub_fffffc0000020d9c : 416 -> 428
~ sub_fffffc000002825c -> sub_fffffc000002827c : 6580 -> 6448
~ sub_fffffc0000035488 -> sub_fffffc0000035424 : 6072 -> 6088
~ sub_fffffc000004a2ec -> sub_fffffc000004a298 : 324 -> 316
CStrings:
+ "Apr 10 2025 20:14:53"
- "Mar 26 2025 22:14:02"
```
