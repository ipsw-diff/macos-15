## aopfw-mac14jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac14jaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA.__version`

```diff

   __TEXT.__text: 0x8945c
-  __TEXT.__const: 0x4d68
+  __TEXT.__const: 0x4d60
   __TEXT.__cstring: 0x5886
   __TEXT.__chain_starts: 0x48
   __DATA._rtk_boot: 0x2000
Functions:
~ sub_10017b4 : 4860 -> 4844
~ sub_1003910 -> sub_1003900 : 176 -> 192
CStrings:
+ "00:24:24"
+ "AppleSPUFirmware-2001.140.12~57"
+ "Jun  3 2025"
- "18:59:18"
- "AppleSPUFirmware-2001.120.17~59"
- "Apr 18 2025"
```
