## aopfw-mac16gaop_l4.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16gaop_l4.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_patchbay`
- `__DATA.__version`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0xba880
+  __TEXT.__text: 0xba89c
   __TEXT.__const: 0xa284
   __TEXT.__cstring: 0x76d4
   __TEXT.__chain_starts: 0x5c
Functions:
~ sub_1020e5c : 1044 -> 1072
~ sub_10b7870 -> sub_10b788c : 172 -> 144
~ sub_10b791c : 188 -> 216
~ sub_10b79d8 -> sub_10b79f4 : 232 -> 216
~ sub_10b7ac0 -> sub_10b7acc : 40 -> 56
~ sub_10ba744 -> sub_10ba760 : 316 -> 324
CStrings:
+ "AppleSPUFirmware-2001.140.14~60"
- "AppleSPUFirmware-2001.140.13~61"
```
