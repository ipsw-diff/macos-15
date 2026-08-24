## aopfw-mac14gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac14gaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA._rtk_power`
- `__DATA._rtk_patchbay`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA.__version`

```diff

   __TEXT.__text: 0x8ce48
-  __TEXT.__const: 0x4fd8
+  __TEXT.__const: 0x4fd0
   __TEXT.__cstring: 0x6118
   __TEXT.__chain_starts: 0x40
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x17f68
   __DATA.__const: 0x8848
-  __DATA.__data: 0x9468
+  __DATA.__data: 0x9460
   __DATA._rtk_power: 0x3b8
   __DATA._rtk_patchbay: 0x2f9
   __DATA._spu_service: 0x300
Functions:
~ sub_1001250 : 4192 -> 4176
~ sub_1003110 -> sub_1003100 : 176 -> 192
CStrings:
+ "00:24:24"
+ "AppleSPUFirmware-2001.140.12~57"
+ "Jun  3 2025"
- "18:59:18"
- "AppleSPUFirmware-2001.120.17~59"
- "Apr 18 2025"
```
