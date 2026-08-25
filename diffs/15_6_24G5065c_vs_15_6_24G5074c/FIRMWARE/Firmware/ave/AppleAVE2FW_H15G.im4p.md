## AppleAVE2FW_H15G.im4p

> `Firmware/ave/AppleAVE2FW_H15G.im4p`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_mtab`
- `__DATA.__const`
- `__DATA.__data`

```diff

-  __TEXT.__text: 0xd7ebc
+  __TEXT.__text: 0xd768c
   __TEXT._rtk_mtab: 0x320
   __TEXT.__const: 0x1d2d0
-  __TEXT.__cstring: 0x127ff
+  __TEXT.__cstring: 0x12783
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0
   __DATA.__const: 0x28c8

   __DATA.__zerofill: 0xc68b8
   Functions: 0
   Symbols:   1451
-  CStrings:  2252
+  CStrings:  2250
 
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
