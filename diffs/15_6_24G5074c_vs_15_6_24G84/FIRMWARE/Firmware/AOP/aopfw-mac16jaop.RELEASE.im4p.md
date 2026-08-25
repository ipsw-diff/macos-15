## aopfw-mac16jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16jaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_patchbay`

```diff

   __TEXT.__text: 0xd12d0
   __TEXT.__const: 0x9904
-  __TEXT.__cstring: 0x5050
+  __TEXT.__cstring: 0x505a
   __TEXT.__chain_starts: 0x58
   __DATA._rtk_boot: 0x2000
   __DATA._rtk_page_tables: 0x5000

   __CMA.__cma_log_string: 0x11b3
   Functions: 2670
   Symbols:   0
-  CStrings:  960
+  CStrings:  961
 
CStrings:
+ "16:58:01"
+ "17:04:18"
+ "17:04:19"
+ "AppleSPUFirmware-2001.140.14~125"
+ "Jul 11 2025"
- "00:24:24"
- "00:35:29"
- "AppleSPUFirmware-2001.140.14~60"
- "Jun  3 2025"
```
