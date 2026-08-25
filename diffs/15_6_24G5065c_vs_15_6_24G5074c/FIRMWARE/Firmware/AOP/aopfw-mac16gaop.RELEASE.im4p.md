## aopfw-mac16gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16gaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__chain_starts`
- `__DATA.__const`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_power`
- `__DATA._rtk_patchbay`
- `__DATA.__version`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0xba98c
+  __TEXT.__text: 0xba9a8
   __TEXT.__const: 0xa244
   __TEXT.__cstring: 0x5880
   __TEXT.__chain_starts: 0x5c

   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x1c640
   __DATA.__const: 0xe540
-  __DATA.__data: 0x6c50
+  __DATA.__data: 0x6c58
   __DATA._spu_service: 0x390
   __DATA._spu_endpoint: 0x30
   __DATA._rtk_power: 0x3b8
Functions:
~ sub_1020e60 : 1044 -> 1072
~ sub_10b79d8 -> sub_10b79f4 : 44 -> 28
~ sub_10b7a04 -> sub_10b7a10 : 324 -> 340
~ sub_10b7fe4 -> sub_10b8000 : 224 -> 176
~ sub_10b80c4 -> sub_10b80b0 : 516 -> 564
CStrings:
+ "AppleSPUFirmware-2001.140.14~60"
- "AppleSPUFirmware-2001.140.13~61"
```
