## aopfw-mac15gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac15gaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_patchbay`
- `__DATA.__version`

```diff

   __TEXT.__text: 0x9087c
-  __TEXT.__const: 0x50b0
+  __TEXT.__const: 0x50a8
   __TEXT.__cstring: 0x6322
   __TEXT.__chain_starts: 0x48
   __DATA._rtk_boot: 0x3000
Functions:
~ sub_10017b4 : 4860 -> 4844
~ sub_1003910 -> sub_1003900 : 176 -> 192
~ sub_108dd98 : 536 -> 524
~ sub_108dfb0 -> sub_108dfa4 : 240 -> 252
CStrings:
+ "00:24:24"
+ "00:35:26"
+ "AppleSPUFirmware-2001.140.12~57"
+ "Jun  3 2025"
- "18:59:18"
- "19:41:26"
- "AppleSPUFirmware-2001.120.17~59"
- "Apr 18 2025"
```
