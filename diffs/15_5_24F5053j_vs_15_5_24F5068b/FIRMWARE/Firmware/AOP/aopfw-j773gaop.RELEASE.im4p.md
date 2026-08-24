## aopfw-j773gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-j773gaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._spu_service`
- `__DATA._rtk_patchbay`
- `__DATA.__version`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x93e70
+  __TEXT.__text: 0x93e88
   __TEXT.__const: 0x7cf8
-  __TEXT.__cstring: 0x4a0f
+  __TEXT.__cstring: 0x4a0b
   __TEXT.__chain_starts: 0x58
   __DATA._rtk_boot: 0x3000
   __DATA._rtk_page_tables: 0x5000

   __ETEXT.__text: 0x503c
   __ETEXT.__StaticInit: 0xdf8
   __ETEXT.__const: 0x11e
-  __OS_LOG.__string: 0x26a85
+  __OS_LOG.__string: 0x26a86
   __MISC.__apf_list: 0x40
   Functions: 2285
   Symbols:   0
Functions:
~ sub_103b134 : 1164 -> 1188
~ sub_1093d34 -> sub_1093d4c : 316 -> 324
CStrings:
+ "00:09:16"
+ "00:24:35"
+ "AppleSPUFirmware-2001.120.17~77"
+ "Apr 20 2025"
- "17:40:19"
- "17:45:33"
- "AppleSPUFirmware-2001.120.16.0.1~56"
- "Apr  6 2025"
```
