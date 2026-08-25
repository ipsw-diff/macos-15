## sqlite3

> `/usr/bin/sqlite3`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-360.2.0.0.0
-  __TEXT.__text: 0x11e24c
+360.3.0.0.0
+  __TEXT.__text: 0x11e29c
   __TEXT.__auth_stubs: 0xdf0
   __TEXT.__const: 0x9928
-  __TEXT.__cstring: 0x17626
+  __TEXT.__cstring: 0x17643
   __TEXT.__oslogstring: 0x6d8
   __TEXT.__unwind_info: 0x2500
   __TEXT.__eh_frame: 0x50

   - /usr/lib/libz.1.dylib
   Functions: 3141
   Symbols:   263
-  CStrings:  3551
+  CStrings:  3552
 
Functions:
~ sub_10003e0ac : 468 -> 472
~ sub_10005fabc -> sub_10005fac0 : 3032 -> 3036
~ sub_100063718 -> sub_100063720 : 396 -> 392
~ sub_100068590 -> sub_100068594 : 33912 -> 33908
~ sub_100078688 : 820 -> 824
~ sub_10007b16c -> sub_10007b170 : 848 -> 844
~ sub_100089ed4 : 9952 -> 9948
~ sub_100099184 -> sub_100099180 : 5440 -> 5436
~ sub_1000b1c88 -> sub_1000b1c80 : 268 -> 264
~ sub_1000c2c24 -> sub_1000c2c18 : 660 -> 704
~ sub_1000c2eb8 -> sub_1000c2ed8 : 352 -> 392
~ sub_1000c3018 -> sub_1000c3060 : 152 -> 164
~ sub_1000c30b0 -> sub_1000c3104 : 128 -> 124
CStrings:
+ "more than %d aggregate terms"
```
