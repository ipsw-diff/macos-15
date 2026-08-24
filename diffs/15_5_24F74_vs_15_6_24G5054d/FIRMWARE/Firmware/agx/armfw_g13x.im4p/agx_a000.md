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

-  __TEXT.__text: 0x4154c
+  __TEXT.__text: 0x41590
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x12b8
+  __TEXT.__gxf_code: 0x12f8
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1fa0
+  __TEXT.__const: 0x1f98
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x1e8
   __TEXT.__chain_starts: 0x24

   __DATA.__constructor: 0x0
   __DATA.__xnu_shared: 0x3c000
   __DATA._rtk_mtab: 0x378
-  __DATA.__zerofill: 0x52778
+  __DATA.__zerofill: 0x52798
   Functions: 457
   Symbols:   217
   CStrings:  226
Functions:
~ sub_ffffff8000004568 : 6832 -> 6836
~ sub_ffffff8000006b74 -> sub_ffffff8000006b78 : 3616 -> 3644
~ sub_ffffff8000022d30 -> sub_ffffff8000022d50 : 1648 -> 1672
~ sub_ffffff80000259d4 -> sub_ffffff8000025a0c : 228 -> 232
~ sub_ffffff8000026298 -> sub_ffffff80000262d4 : 720 -> 716
~ sub_ffffff8000026774 -> sub_ffffff80000267ac : 620 -> 616
~ sub_ffffff8000026b1c -> sub_ffffff8000026b50 : 1152 -> 1156
~ sub_ffffff800002dc24 -> sub_ffffff800002dc5c : 1100 -> 1104
~ sub_ffffff800002ecb4 -> sub_ffffff800002ecf0 : 4284 -> 4292
~ sub_ffffff800004140c -> sub_ffffff8000041450 : 328 -> 320
CStrings:
+ "Jun 11 2025 21:14:16"
- "Apr 22 2025 19:45:02"
```
