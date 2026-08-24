## aopfw-mac16gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16gaop.RELEASE.im4p`

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

-  __TEXT.__text: 0xba974
+  __TEXT.__text: 0xba98c
   __TEXT.__const: 0xa250
-  __TEXT.__cstring: 0x588d
+  __TEXT.__cstring: 0x5889
   __TEXT.__chain_starts: 0x5c
   __DATA._rtk_boot: 0x3000
   __DATA._rtk_page_tables: 0x5000

   __ETEXT.__eh_frame: 0x40
   __ETEXT.__StaticInit: 0x1fe4
   __ETEXT.__const: 0x530
-  __OS_LOG.__string: 0x29890
+  __OS_LOG.__string: 0x29891
   __MISC.__apf_list: 0x40
   __CMA.__cma_log_string: 0x11b3
   Functions: 2890
Functions:
~ sub_103ebf8 : 1152 -> 1176
~ sub_10b6604 -> sub_10b661c : 1052 -> 1064
~ sub_10b6a20 -> sub_10b6a44 : 336 -> 324
~ sub_10ba838 -> sub_10ba850 : 316 -> 324
CStrings:
+ "00:09:16"
+ "00:24:38"
+ "00:24:39"
+ "AppleSPUFirmware-2001.120.17~77"
+ "Apr 20 2025"
- "17:40:19"
- "17:45:35"
- "17:45:36"
- "AppleSPUFirmware-2001.120.16.0.1~56"
- "Apr  6 2025"
```
