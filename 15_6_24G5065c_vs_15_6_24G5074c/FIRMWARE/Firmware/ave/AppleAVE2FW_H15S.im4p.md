## AppleAVE2FW_H15S.im4p

> `Firmware/ave/AppleAVE2FW_H15S.im4p`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_mtab`
- `__DATA.__const`
- `__DATA.__data`

```diff

-  __TEXT.__text: 0xf2174
+  __TEXT.__text: 0xf18d4
   __TEXT._rtk_mtab: 0x2d0
   __TEXT.__const: 0x219b8
-  __TEXT.__cstring: 0x14054
+  __TEXT.__cstring: 0x13fd8
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0
   __DATA.__const: 0x2a20

   __DATA.__zerofill: 0xc9318
   Functions: 0
   Symbols:   1535
-  CStrings:  2419
+  CStrings:  2417
 
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
