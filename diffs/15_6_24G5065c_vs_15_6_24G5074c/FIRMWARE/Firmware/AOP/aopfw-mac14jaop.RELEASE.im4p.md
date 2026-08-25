## aopfw-mac14jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac14jaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_mtab`
- `__DATA.__version`

```diff

-  __TEXT.__text: 0x8945c
+  __TEXT.__text: 0x89478
   __TEXT.__const: 0x4d60
   __TEXT.__cstring: 0x5886
   __TEXT.__chain_starts: 0x48
Functions:
~ sub_101f790 : 972 -> 1000
~ sub_1088504 -> sub_1088520 : 2240 -> 2220
~ sub_1088dc4 -> sub_1088dcc : 688 -> 708
CStrings:
+ "AppleSPUFirmware-2001.140.14~60"
- "AppleSPUFirmware-2001.140.13~61"
```
