## AppleAVE2FW_H13S.im4p

> `Firmware/ave/AppleAVE2FW_H13S.im4p`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_mtab`
- `__DATA.__const`
- `__DATA.__data`

```diff

-  __TEXT.__text: 0xcb800
+  __TEXT.__text: 0xcaf70
   __TEXT._rtk_mtab: 0x308
   __TEXT.__const: 0x1e5e0
-  __TEXT.__cstring: 0x1142d
+  __TEXT.__cstring: 0x113b1
   __TEXT.__constructor: 0x0
   __TEXT.__chain_starts: 0x0
   __DATA.__const: 0x27f8

   __DATA.__zerofill: 0xc68b8
   Functions: 0
   Symbols:   1371
-  CStrings:  2114
+  CStrings:  2112
 
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
