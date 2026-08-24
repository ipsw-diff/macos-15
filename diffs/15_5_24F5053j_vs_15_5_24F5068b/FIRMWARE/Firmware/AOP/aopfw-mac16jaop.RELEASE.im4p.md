## aopfw-mac16jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16jaop.RELEASE.im4p`

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

-  __TEXT.__text: 0xd129c
+  __TEXT.__text: 0xd12b4
   __TEXT.__const: 0x9908
-  __TEXT.__cstring: 0x505d
+  __TEXT.__cstring: 0x5059
   __TEXT.__chain_starts: 0x58
   __DATA._rtk_boot: 0x2000
   __DATA._rtk_page_tables: 0x5000

   __ETEXT.__text: 0x10fb0
   __ETEXT.__StaticInit: 0x1b08
   __ETEXT.__const: 0x43a
-  __OS_LOG.__string: 0x2969c
+  __OS_LOG.__string: 0x2969d
   __MISC.__apf_list: 0x80
   __CMA.__cma_log_string: 0x11b3
   Functions: 2670
Functions:
~ sub_10909cc : 1192 -> 1216
~ sub_10ce5e4 -> sub_10ce5fc : 204 -> 192
~ sub_10ce6b0 -> sub_10ce6bc : 748 -> 760
~ sub_10d1160 -> sub_10d1178 : 324 -> 316
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
