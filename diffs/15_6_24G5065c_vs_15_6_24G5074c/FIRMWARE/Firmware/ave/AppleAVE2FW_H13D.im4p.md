## AppleAVE2FW_H13D.im4p

> `Firmware/ave/AppleAVE2FW_H13D.im4p`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_mtab`
- `__DATA.__const`
- `__DATA._rtk_patchbay`
- `__DATA.__data`
- `__DATA._rtk_power`

```diff

-  __TEXT.__text: 0xe6350
+  __TEXT.__text: 0xe5ae0
   __TEXT._rtk_mtab: 0x2b8
   __TEXT.__const: 0x1ed38
-  __TEXT.__cstring: 0x12e56
+  __TEXT.__cstring: 0x12dda
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0
   __DATA.__const: 0x2950

   __DATA.__zerofill: 0xd03d8
   Functions: 0
   Symbols:   1462
-  CStrings:  2287
+  CStrings:  2285
 
Symbols:
+ __ZN16LinearRegression4initEffff
- __ZN16LinearRegression4initEfff
CStrings:
+ "%s::%s:%d wrong start point %d %d"
+ "8002.47.0"
- "%s::%s:%d BITBOX OVERFLOW (QPMODOFF) Frame# %d - ABR: %d HRD: %d"
- "%s::%s:%d BITBOX OVERFLOW (QPMODON) Frame# %d - ABR: %d HRD: %d qpModLevel %d"
- "8002.46.0"
- "start_pt < 128"
```
