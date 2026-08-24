## aopfw-mac16jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16jaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA.__const`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_power`
- `__DATA._rtk_patchbay`
- `__DATA.__version`

```diff

   __TEXT.__text: 0xd12b4
-  __TEXT.__const: 0x9908
-  __TEXT.__cstring: 0x5059
+  __TEXT.__const: 0x9904
+  __TEXT.__cstring: 0x5050
   __TEXT.__chain_starts: 0x58
   __DATA._rtk_boot: 0x2000
   __DATA._rtk_page_tables: 0x5000

   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x2de20
   __DATA.__const: 0xd698
-  __DATA.__data: 0x6e58
+  __DATA.__data: 0x6e50
   __DATA._spu_service: 0x300
   __DATA._spu_endpoint: 0x48
   __DATA._rtk_power: 0x3b8

   __CMA.__cma_log_string: 0x11b3
   Functions: 2670
   Symbols:   0
-  CStrings:  961
+  CStrings:  960
 
Functions:
~ sub_1001250 : 4192 -> 4176
~ sub_1002ab0 -> sub_1002aa0 : 208 -> 224
CStrings:
+ "00:24:24"
+ "00:35:29"
+ "AppleSPUFirmware-2001.140.12~57"
+ "Jun  3 2025"
- "18:59:18"
- "19:41:29"
- "19:41:30"
- "AppleSPUFirmware-2001.120.17~59"
- "Apr 18 2025"
```
