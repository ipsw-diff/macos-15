## aopfw-mac16gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16gaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__const`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_power`
- `__DATA._rtk_patchbay`
- `__DATA.__version`

```diff

   __TEXT.__text: 0xba98c
-  __TEXT.__const: 0xa250
-  __TEXT.__cstring: 0x5889
+  __TEXT.__const: 0xa244
+  __TEXT.__cstring: 0x5880
   __TEXT.__chain_starts: 0x5c
   __DATA._rtk_boot: 0x3000
   __DATA._rtk_page_tables: 0x5000

   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x1c640
   __DATA.__const: 0xe540
-  __DATA.__data: 0x6c58
+  __DATA.__data: 0x6c50
   __DATA._spu_service: 0x390
   __DATA._spu_endpoint: 0x30
   __DATA._rtk_power: 0x3b8

   __CMA.__cma_log_string: 0x11b3
   Functions: 2890
   Symbols:   0
-  CStrings:  1017
+  CStrings:  1016
 
Functions:
~ sub_1001250 : 4192 -> 4176
~ sub_1002ab0 -> sub_1002aa0 : 208 -> 224
~ sub_10b79d8 : 28 -> 44
~ sub_10b79f4 -> sub_10b7a04 : 340 -> 324
~ sub_10b7fe4 : 176 -> 224
~ sub_10b8094 -> sub_10b80c4 : 564 -> 516
CStrings:
+ "00:24:40"
+ "00:35:29"
+ "AppleSPUFirmware-2001.140.12~57"
+ "Jun  3 2025"
- "18:59:30"
- "19:41:29"
- "19:41:30"
- "AppleSPUFirmware-2001.120.17~59"
- "Apr 18 2025"
```
