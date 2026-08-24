## aopfw-mac13jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac13jaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA.__version`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x83e60
-  __TEXT.__const: 0x4bd8
+  __TEXT.__text: 0x83e58
+  __TEXT.__const: 0x4bd0
   __TEXT.__cstring: 0x12923
   __TEXT.__chain_starts: 0x44
   __DATA._rtk_boot: 0x2000
Functions:
~ sub_1001250 : 4192 -> 4176
~ sub_1003110 -> sub_1003100 : 176 -> 192
~ sub_102fd88 : 1812 -> 1816
~ sub_10320ec -> sub_10320f0 : 9624 -> 9628
~ sub_10408d4 -> sub_10408dc : 372 -> 364
~ sub_1040fdc : 156 -> 160
~ sub_10815a0 -> sub_10815a4 : 1276 -> 1268
~ sub_1081a9c -> sub_1081a98 : 1044 -> 1052
~ sub_1082798 -> sub_108279c : 2464 -> 2452
~ sub_1083d08 -> sub_1083d00 : 344 -> 352
CStrings:
+ "00:24:46"
+ "AppleSPUFirmware-2001.140.12~57"
+ "Jun  3 2025"
- "18:59:34"
- "AppleSPUFirmware-2001.120.17~59"
- "Apr 18 2025"
```
