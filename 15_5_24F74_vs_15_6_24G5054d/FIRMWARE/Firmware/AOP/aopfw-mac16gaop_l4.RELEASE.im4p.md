## aopfw-mac16gaop_l4.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16gaop_l4.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__DATA.__const`
- `__DATA.__data`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_patchbay`
- `__DATA.__version`

```diff

   __TEXT.__text: 0xba880
-  __TEXT.__const: 0xa288
-  __TEXT.__cstring: 0x76dd
+  __TEXT.__const: 0xa284
+  __TEXT.__cstring: 0x76d4
   __TEXT.__chain_starts: 0x5c
   __DATA._rtk_boot: 0x3000
   __DATA._rtk_page_tables: 0x5000

   __CMA.__cma_log_string: 0x11b3
   Functions: 2882
   Symbols:   0
-  CStrings:  1212
+  CStrings:  1211
 
Functions:
~ sub_1001250 : 4192 -> 4176
~ sub_1002ab0 -> sub_1002aa0 : 208 -> 224
~ sub_10b79d8 : 216 -> 232
~ sub_10b7ab0 -> sub_10b7ac0 : 56 -> 40
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
