## aopfw-mac16jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac16jaop.RELEASE.im4p`

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

-  __TEXT.__text: 0xd12b4
+  __TEXT.__text: 0xd12d0
   __TEXT.__const: 0x9904
   __TEXT.__cstring: 0x5050
   __TEXT.__chain_starts: 0x58

   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x2de20
   __DATA.__const: 0xd698
-  __DATA.__data: 0x6e50
+  __DATA.__data: 0x6e58
   __DATA._spu_service: 0x300
   __DATA._spu_endpoint: 0x48
   __DATA._rtk_power: 0x3b8
Functions:
~ sub_1020128 : 1044 -> 1072
~ sub_10ce144 -> sub_10ce160 : 808 -> 796
~ sub_10ce46c -> sub_10ce47c : 400 -> 412
~ sub_10ce5fc -> sub_10ce618 : 192 -> 204
~ sub_10ce6bc -> sub_10ce6e4 : 760 -> 748
CStrings:
+ "AppleSPUFirmware-2001.140.14~60"
- "AppleSPUFirmware-2001.140.13~61"
```
