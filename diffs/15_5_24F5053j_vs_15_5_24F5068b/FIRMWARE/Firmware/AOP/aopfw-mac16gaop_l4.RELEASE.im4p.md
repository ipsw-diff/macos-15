## aopfw-mac16gaop_l4.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16gaop_l4.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_patchbay`
- `__DATA.__version`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0xba868
+  __TEXT.__text: 0xba880
   __TEXT.__const: 0xa288
-  __TEXT.__cstring: 0x76e1
+  __TEXT.__cstring: 0x76dd
   __TEXT.__chain_starts: 0x5c
   __DATA._rtk_boot: 0x3000
   __DATA._rtk_page_tables: 0x5000

   __ETEXT.__text: 0x11f68
   __ETEXT.__StaticInit: 0x1fe4
   __ETEXT.__const: 0x4ed
-  __OS_LOG.__string: 0x2649b
+  __OS_LOG.__string: 0x2649c
   __MISC.__apf_list: 0x40
   __CMA.__cma_log_string: 0x11b3
   Functions: 2882
Functions:
~ sub_1057aec : 1192 -> 1216
~ sub_10ba72c -> sub_10ba744 : 324 -> 316
CStrings:
+ "00:09:01"
+ "00:24:38"
+ "00:24:39"
+ "AppleSPUFirmware-2001.120.17~77"
+ "Apr 20 2025"
- "17:40:09"
- "17:45:35"
- "17:45:36"
- "AppleSPUFirmware-2001.120.16.0.1~56"
- "Apr  6 2025"
```
