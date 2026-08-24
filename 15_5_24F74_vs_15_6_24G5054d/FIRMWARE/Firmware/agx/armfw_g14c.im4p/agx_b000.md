## agx_b000

> `Firmware/agx/armfw_g14c.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`

```diff

   __TEXT.__text: 0x4a250
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1230
+  __TEXT.__gxf_code: 0x1270
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1f90
+  __TEXT.__const: 0x1f88
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_ffffff8000004994 : 5212 -> 5216
~ sub_ffffff8000021d9c -> sub_ffffff8000021da0 : 372 -> 380
~ sub_ffffff8000021f10 -> sub_ffffff8000021f1c : 380 -> 388
~ sub_ffffff800002c2f4 -> sub_ffffff800002c308 : 1696 -> 1676
~ sub_ffffff800002e2e4 : 556 -> 560
~ sub_ffffff800002f1dc -> sub_ffffff800002f1e0 : 780 -> 776
~ sub_ffffff800002f6f4 : 620 -> 616
~ sub_ffffff800002fa88 -> sub_ffffff800002fa84 : 1528 -> 1524
~ sub_ffffff8000030dec -> sub_ffffff8000030de4 : 7892 -> 7896
~ sub_ffffff80000352a4 -> sub_ffffff80000352a0 : 1252 -> 1256
CStrings:
+ "Jun 11 2025 21:17:16"
- "Apr 22 2025 19:48:18"
```
