## agx_a000

> `Firmware/agx/armfw_g15g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4b0fc
+  __TEXT.__text: 0x4b11c
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1230
+  __TEXT.__gxf_code: 0x1270
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x22ac
+  __TEXT.__const: 0x22a8
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc00000052d0 : 6040 -> 6044
~ sub_fffffc000002e460 -> sub_fffffc000002e464 : 1436 -> 1460
~ sub_fffffc000002f89c -> sub_fffffc000002f8b8 : 372 -> 376
~ sub_fffffc0000030048 -> sub_fffffc0000030068 : 756 -> 752
~ sub_fffffc0000030548 -> sub_fffffc0000030564 : 620 -> 616
~ sub_fffffc0000036474 -> sub_fffffc000003648c : 2132 -> 2136
~ sub_fffffc0000037c08 -> sub_fffffc0000037c24 : 6356 -> 6360
CStrings:
+ "Jun 11 2025 21:14:47"
- "Apr 22 2025 19:45:34"
```
