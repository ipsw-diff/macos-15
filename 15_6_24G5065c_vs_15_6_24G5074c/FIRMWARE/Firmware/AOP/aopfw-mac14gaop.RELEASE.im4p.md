## aopfw-mac14gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac14gaop.RELEASE.im4p`

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

-  __TEXT.__text: 0x8ce48
+  __TEXT.__text: 0x8ce64
   __TEXT.__const: 0x4fd0
   __TEXT.__cstring: 0x6118
   __TEXT.__chain_starts: 0x40
Functions:
~ sub_101f80c : 972 -> 1000
~ sub_108ccf0 -> sub_108cd0c : 352 -> 344
CStrings:
+ "AppleSPUFirmware-2001.140.14~60"
- "AppleSPUFirmware-2001.140.13~61"
```
