## agx_b000

> `Firmware/agx/armfw_g16c.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4a538
+  __TEXT.__text: 0x4a4e4
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1194
+  __TEXT.__const: 0x1198
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x6a0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000006b40 : 18612 -> 18608
~ sub_fffffc000000bda0 -> sub_fffffc000000bd9c : 736 -> 740
~ sub_fffffc000000c080 : 2148 -> 2152
~ sub_fffffc000000c8e4 -> sub_fffffc000000c8e8 : 4880 -> 4888
~ sub_fffffc000000dc2c -> sub_fffffc000000dc38 : 1256 -> 1260
~ sub_fffffc0000010c7c -> sub_fffffc0000010c8c : 804 -> 808
~ sub_fffffc0000020d88 -> sub_fffffc0000020d9c : 416 -> 428
~ sub_fffffc00000282a4 -> sub_fffffc00000282c4 : 6580 -> 6448
~ sub_fffffc0000035598 -> sub_fffffc0000035534 : 6072 -> 6088
~ sub_fffffc000004a3fc -> sub_fffffc000004a3a8 : 324 -> 316
CStrings:
+ "Apr 10 2025 20:19:09"
- "Mar 26 2025 22:18:16"
```
