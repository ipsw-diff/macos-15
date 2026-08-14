## agx_b000

> `Firmware/agx/armfw_g15s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4b18c
+  __TEXT.__text: 0x4b12c
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0xfb8
+  __TEXT.__const: 0xfc0
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000007ac8 : 17736 -> 17732
~ sub_fffffc000000cc2c -> sub_fffffc000000cc28 : 816 -> 820
~ sub_fffffc000000cf5c : 1784 -> 1788
~ sub_fffffc000000d654 -> sub_fffffc000000d658 : 4524 -> 4536
~ sub_fffffc0000012190 -> sub_fffffc00000121a0 : 804 -> 808
~ sub_fffffc0000029734 -> sub_fffffc0000029748 : 6584 -> 6452
~ sub_fffffc0000037d94 -> sub_fffffc0000037d24 : 4448 -> 4464
CStrings:
+ "Apr 10 2025 20:19:04"
- "Mar 26 2025 22:18:11"
```
