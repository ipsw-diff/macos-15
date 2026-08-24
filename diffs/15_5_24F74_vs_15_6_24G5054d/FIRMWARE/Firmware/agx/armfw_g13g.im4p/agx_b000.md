## agx_b000

> `Firmware/agx/armfw_g13g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x3db18
+  __TEXT.__text: 0x3db38
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x12b8
+  __TEXT.__gxf_code: 0x12f8
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1d54
+  __TEXT.__const: 0x1d50
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x1e8
   __TEXT.__chain_starts: 0x20

   __DATA.__constructor: 0x0
   __DATA.__xnu_shared: 0x3c000
   __DATA._rtk_mtab: 0x260
-  __DATA.__zerofill: 0x51f98
+  __DATA.__zerofill: 0x51fb8
   Functions: 406
   Symbols:   213
   CStrings:  203
Functions:
~ sub_ffffff800000453c : 6776 -> 6780
~ sub_ffffff8000006b10 -> sub_ffffff8000006b14 : 3284 -> 3316
~ sub_ffffff8000021430 -> sub_ffffff8000021454 : 1428 -> 1420
~ sub_ffffff8000023868 -> sub_ffffff8000023884 : 228 -> 232
~ sub_ffffff8000023e48 -> sub_ffffff8000023e68 : 652 -> 648
~ sub_ffffff80000242e0 -> sub_ffffff80000242fc : 620 -> 616
~ sub_ffffff800002b98c -> sub_ffffff800002b9a4 : 1100 -> 1104
~ sub_ffffff800002c9c0 -> sub_ffffff800002c9dc : 4844 -> 4848
CStrings:
+ "Jun 11 2025 21:16:06"
- "Apr 22 2025 19:46:49"
```
