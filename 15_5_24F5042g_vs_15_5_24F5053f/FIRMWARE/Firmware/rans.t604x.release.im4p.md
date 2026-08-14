## rans.t604x.release.im4p

> `Firmware/rans.t604x.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.idle_hooks`
- `__DATA.__const`
- `__DATA.__data`

```diff

   __TEXT.text_first: 0x4488
-  __TEXT.__text: 0x1e0b64
+  __TEXT.__text: 0x1e0bd8
   __TEXT.shared: 0xe954
   __TEXT.read: 0x75b0
-  __TEXT.__const: 0x6038
+  __TEXT.__const: 0x6078
   __TEXT.idle_hooks: 0x10
-  __TEXT.__cstring: 0x240f6
+  __TEXT.__cstring: 0x23fe5
   __TEXT.__chain_starts: 0x0
   __TEXT.__constructor: 0x0
   __TEXT._rtk_mtab: 0x540

   __DATA.core_globals: 0x15d
   __DATA.large_stacks: 0x20000
   __DATA.small_stacks: 0x2000
-  __DATA.__zerofill: 0x5b3298
+  __DATA.__zerofill: 0x5b32c8
   Functions: 0
   Symbols:   0
-  CStrings:  3928
+  CStrings:  3923
 
CStrings:
+ "2077.120.76"
+ "2077.120.76~86"
+ "AppleStorageFirmware-2077.120.76~86"
+ "Band is Invalid, bork: %d, dip: %d"
+ "MassScan: previous pilot scan was %lld seconds ago, avoid scan this time"
- "2077.120.68.0.1"
- "77.120.68.0.1~82"
- "AppleStorageFirmware-2077.120.68.0.1~82"
- "Band is Invalid."
- "ErrInj test random: %d %d %d"
- "ErrInj: %d excuting bit flip with values: %d, %d"
- "ErrInj: %d excuting bit flip with values: first Read: %d, reRead: %d, HardErr: %d"
- "ErrInj: %d excuting force read per plane in: %d, with: %d, %d, %d, %d"
- "ErrInj: %d excuting force read with random plane, plane chosen: %d, value: %d"
- "ErrInj: %d excuting force read with value: %d"
```
