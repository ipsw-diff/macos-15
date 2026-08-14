## sptm.t8112.release.im4p

> `Firmware/sptm.t8112.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__LATE_CONST.__late_const`
- `__DATA.__auth_ptr`

```diff

-392.120.14.0.0
-  __TEXT.__cstring: 0xd992
+392.120.16.0.0
+  __TEXT.__cstring: 0xd96f
   __TEXT.__binname: 0x40
   __TEXT.__const: 0xb00
   __TEXT.__chain_starts: 0x74
   __DATA_CONST.__const: 0x6498
   __LATE_CONST.__late_const: 0x5d610
-  __TEXT_EXEC.__text: 0x4c68c
+  __TEXT_EXEC.__text: 0x4c6cc
   __LAST.__pinst: 0x8
   __DATA.__auth_ptr: 0x18
   __DATA.__data: 0x6

   __BOOTDATA.__data: 0x14000
   Functions: 334
   Symbols:   1
-  CStrings:  1689
+  CStrings:  1688
 
Functions:
~ sub_fffffff027081068 : 44852 -> 44876
~ sub_fffffff02708c0c0 -> sub_fffffff02708c0d8 : 320 -> 328
~ sub_fffffff02708f1d8 -> sub_fffffff02708f1f8 : 6368 -> 6400
CStrings:
- "VIOLATION_ILLEGAL_UNTAGGED_MAPPING"
```
