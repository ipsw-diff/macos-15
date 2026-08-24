## aopfw-mac15jaop.RELEASE.im4p

> `Firmware/AOP/aopfw-mac15jaop.RELEASE.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._spu_service`
- `__DATA._spu_endpoint`
- `__DATA._rtk_patchbay`
- `__DATA.__version`

```diff

   __TEXT.__text: 0xac1e8
-  __TEXT.__const: 0x53e0
+  __TEXT.__const: 0x53d8
   __TEXT.__cstring: 0x5e8e
   __TEXT.__chain_starts: 0x44
   __DATA._rtk_boot: 0x3000
Functions:
~ sub_101becc : 3044 -> 3028
~ sub_101d910 -> sub_101d900 : 176 -> 192
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
