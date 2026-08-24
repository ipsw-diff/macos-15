## aopfw-mac15saop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac15saop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_patchbay`
- `__DATA.__version`

```diff

   __TEXT.__text: 0x9b220
-  __TEXT.__const: 0x5410
+  __TEXT.__const: 0x5408
   __TEXT.__cstring: 0x5e6b
   __TEXT.__chain_starts: 0x3c
   __DATA._rtk_boot: 0x3000
Functions:
~ sub_100185c : 4692 -> 4676
~ sub_1003910 -> sub_1003900 : 176 -> 192
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
