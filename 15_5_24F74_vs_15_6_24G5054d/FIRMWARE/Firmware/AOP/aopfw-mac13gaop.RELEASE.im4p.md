## aopfw-mac13gaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac13gaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__chain_starts`
- `__DATA.__const`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_patchbay`
- `__DATA.__version`
- `__DATA._rtk_mtab`
- `__ETEXT.__eh_frame`

```diff

-  __TEXT.__text: 0x77f58
-  __TEXT.__const: 0x41a0
+  __TEXT.__text: 0x77f48
+  __TEXT.__const: 0x4198
   __TEXT.__cstring: 0x13d1f
   __TEXT.__chain_starts: 0x44
   __DATA._rtk_boot: 0x3000

   __DATA._rtk_ext_stack: 0x1800
   __DATA._rtk_heap: 0x11b68
   __DATA.__const: 0x7450
-  __DATA.__data: 0x8780
+  __DATA.__data: 0x8778
   __DATA._spu_service: 0x210
   __DATA._spu_endpoint: 0x30
   __DATA._rtk_patchbay: 0x326
Functions:
~ sub_1001250 : 4192 -> 4176
CStrings:
+ "00:24:46"
+ "AppleSPUFirmware-2001.140.12~57"
+ "Jun  3 2025"
- "18:59:34"
- "AppleSPUFirmware-2001.120.17~59"
- "Apr 18 2025"
```
