## ansf.t8132_ASP3.release.im4p

> `Firmware/ansf.t8132_ASP3.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.idle_hooks`
- `__DATA.__const`

```diff

   __TEXT.text_first: 0x4488
-  __TEXT.__text: 0x1d93dc
+  __TEXT.__text: 0x1d94c8
   __TEXT.shared: 0xe8bc
   __TEXT.read: 0x7610
-  __TEXT.__const: 0x5c38
+  __TEXT.__const: 0x5c78
   __TEXT.idle_hooks: 0x10
-  __TEXT.__cstring: 0x23d02
+  __TEXT.__cstring: 0x23bf1
   __TEXT.__chain_starts: 0x0
   __TEXT.__constructor: 0x0
   __TEXT._rtk_mtab: 0x540

   __DATA._rtk_patchbay: 0x3ff
   __DATA._rtk_tunables: 0x6a0
   __DATA.__const: 0x24a8
-  __DATA.__data: 0x7a90
+  __DATA.__data: 0x7a88
   __DATA._rtk_init_stack: 0x1000
   __DATA._rtk_irq_stack: 0x1000
   __DATA._rtk_exc_stack: 0x1000

   __DATA.core_globals: 0x15d
   __DATA.large_stacks: 0x20000
   __DATA.small_stacks: 0x2000
-  __DATA.__zerofill: 0x3c5cf8
+  __DATA.__zerofill: 0x3c5d28
   Functions: 0
   Symbols:   0
-  CStrings:  3898
+  CStrings:  3893
 
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
