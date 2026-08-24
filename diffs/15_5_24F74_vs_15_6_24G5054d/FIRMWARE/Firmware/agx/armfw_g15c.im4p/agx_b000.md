## agx_b000

> `Firmware/agx/armfw_g15c.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA.__mod_init_func`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x4e014
+  __TEXT.__text: 0x4e010
   __TEXT.__gxf_shr_code: 0x55c
-  __TEXT.__gxf_code: 0x1230
+  __TEXT.__gxf_code: 0x1270
   __TEXT.__gxf_code_pad: 0x0
-  __TEXT.__const: 0x1048
+  __TEXT.__const: 0x1040
   __TEXT._rtk_patchbay: 0x228
   __TEXT._rtk_tunables: 0x5b0
   __TEXT.__chain_starts: 0x28
Functions:
~ sub_fffffc0000004e64 : 5352 -> 5356
~ sub_fffffc000002c938 -> sub_fffffc000002c93c : 1756 -> 1736
~ sub_fffffc00000316cc -> sub_fffffc00000316bc : 556 -> 560
~ sub_fffffc000003241c -> sub_fffffc0000032410 : 876 -> 872
~ sub_fffffc0000032994 -> sub_fffffc0000032984 : 640 -> 636
~ sub_fffffc0000032d3c -> sub_fffffc0000032d28 : 1624 -> 1628
~ sub_fffffc00000386a8 -> sub_fffffc0000038698 : 2256 -> 2260
~ sub_fffffc0000039cdc -> sub_fffffc0000039cd0 : 5800 -> 5808
CStrings:
+ "Jun 11 2025 21:18:29"
- "Apr 22 2025 19:49:27"
```
