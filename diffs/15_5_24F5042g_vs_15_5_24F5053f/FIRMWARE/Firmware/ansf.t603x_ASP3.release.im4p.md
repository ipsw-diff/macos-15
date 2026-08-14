## ansf.t603x_ASP3.release.im4p

> `Firmware/ansf.t603x_ASP3.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.idle_hooks`
- `__DATA.__const`

```diff

   __TEXT.text_first: 0x4488
-  __TEXT.__text: 0x1e7600
+  __TEXT.__text: 0x1e7704
   __TEXT.shared: 0xeb2c
   __TEXT.read: 0x75ec
-  __TEXT.__const: 0x65b8
+  __TEXT.__const: 0x65f8
   __TEXT.idle_hooks: 0x10
-  __TEXT.__cstring: 0x245af
+  __TEXT.__cstring: 0x2449e
   __TEXT.__chain_starts: 0x0
   __TEXT.__constructor: 0x0
   __TEXT._rtk_mtab: 0x540

   __DATA._rtk_patchbay: 0x3ff
   __DATA._rtk_tunables: 0x5b0
   __DATA.__const: 0x3910
-  __DATA.__data: 0x8800
+  __DATA.__data: 0x87f8
   __DATA._rtk_init_stack: 0x1000
   __DATA._rtk_irq_stack: 0x1000
   __DATA._rtk_exc_stack: 0x1000

   __DATA.core_globals: 0x15d
   __DATA.large_stacks: 0x20000
   __DATA.small_stacks: 0x2000
-  __DATA.__zerofill: 0x5a0a88
+  __DATA.__zerofill: 0x5a0ab8
   Functions: 0
   Symbols:   0
-  CStrings:  4008
+  CStrings:  4003
 
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
