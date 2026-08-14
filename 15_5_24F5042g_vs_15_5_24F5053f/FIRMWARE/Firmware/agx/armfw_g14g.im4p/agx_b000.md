## agx_b000

> `Firmware/agx/armfw_g14g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4da3c
+  __TEXT.__text: 0x4d99c
   __TEXT.__gxf_shr_code: 0x55c
   __TEXT.__gxf_code: 0x1230
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1eb0
+  __TEXT.__const: 0x1eb4
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_ffffff8000006e20 : 10908 -> 10904
~ sub_ffffff800000a3c8 -> sub_ffffff800000a3c4 : 812 -> 816
~ sub_ffffff800000a6f4 : 1856 -> 1860
~ sub_ffffff800000ae34 -> sub_ffffff800000ae38 : 3756 -> 3764
~ sub_ffffff800000ef48 -> sub_ffffff800000ef54 : 764 -> 768
~ sub_ffffff800001d22c -> sub_ffffff800001d23c : 980 -> 984
~ sub_ffffff8000023c8c -> sub_ffffff8000023ca0 : 7044 -> 6908
~ sub_ffffff8000029fbc -> sub_ffffff8000029f48 : 22704 -> 22640
~ sub_ffffff800003a670 -> sub_ffffff800003a5bc : 6172 -> 6192
CStrings:
+ "Apr 10 2025 20:16:46"
- "Mar 26 2025 22:16:00"
```
