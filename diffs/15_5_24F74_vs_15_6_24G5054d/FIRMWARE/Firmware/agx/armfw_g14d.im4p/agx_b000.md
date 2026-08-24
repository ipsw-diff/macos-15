## agx_b000

> `Firmware/agx/armfw_g14d.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`

```diff

   __TEXT.__text: 0x4ab28
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1230
+  __TEXT.__gxf_code: 0x1270
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1fc8
+  __TEXT.__const: 0x1fc0
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_ffffff8000004aa8 : 5228 -> 5232
~ sub_ffffff8000022438 -> sub_ffffff800002243c : 520 -> 528
~ sub_ffffff8000022640 -> sub_ffffff800002264c : 380 -> 388
~ sub_ffffff800002cab8 -> sub_ffffff800002cacc : 1840 -> 1820
~ sub_ffffff800002eb5c : 556 -> 560
~ sub_ffffff800002fa54 -> sub_ffffff800002fa58 : 780 -> 776
~ sub_ffffff800002ff6c : 620 -> 616
~ sub_ffffff8000030300 -> sub_ffffff80000302fc : 1528 -> 1524
~ sub_ffffff8000031694 -> sub_ffffff800003168c : 7892 -> 7896
~ sub_ffffff8000035b4c -> sub_ffffff8000035b48 : 1252 -> 1256
CStrings:
+ "Jun 11 2025 21:17:21"
- "Apr 22 2025 19:48:22"
```
