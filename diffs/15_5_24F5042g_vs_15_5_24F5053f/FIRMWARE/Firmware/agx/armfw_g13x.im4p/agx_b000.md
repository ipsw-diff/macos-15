## agx_b000

> `Firmware/agx/armfw_g13x.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x414f0
+  __TEXT.__text: 0x414f8
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x12b8
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1f98
+  __TEXT.__const: 0x1fa0
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x1e8
   __TEXT.__chain_starts: 0x24
Functions:
~ sub_ffffff8000006c18 : 3568 -> 3564
~ sub_ffffff8000008588 -> sub_ffffff8000008584 : 812 -> 816
~ sub_ffffff80000088b4 : 1520 -> 1524
~ sub_ffffff8000008ea4 -> sub_ffffff8000008ea8 : 3592 -> 3628
~ sub_ffffff800000c9e0 -> sub_ffffff800000ca08 : 1528 -> 1532
~ sub_ffffff800001a314 -> sub_ffffff800001a340 : 936 -> 940
~ sub_ffffff800001deb4 -> sub_ffffff800001dee4 : 3852 -> 3800
~ sub_ffffff80000216bc -> sub_ffffff80000216b8 : 4152 -> 4148
~ sub_ffffff800002ec68 -> sub_ffffff800002ec60 : 4268 -> 4284
~ sub_ffffff80000413b0 -> sub_ffffff80000413b8 : 320 -> 328
CStrings:
+ "Apr 10 2025 20:16:02"
- "Mar 26 2025 22:15:13"
```
