## rsync

> `/usr/bin/rsync`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-146.140.13.0.0
-  __TEXT.__text: 0x48d60
+146.140.14.0.0
+  __TEXT.__text: 0x48da8
   __TEXT.__auth_stubs: 0xcb0
   __TEXT.__const: 0x57d8
-  __TEXT.__cstring: 0x7815
-  __TEXT.__oslogstring: 0x2db8
+  __TEXT.__cstring: 0x7821
+  __TEXT.__oslogstring: 0x2dc4
   __TEXT.__unwind_info: 0x5f0
   __TEXT.__eh_frame: 0x48
   __DATA_CONST.__auth_got: 0x658

   - /usr/lib/libutil.dylib
   Functions: 1146
   Symbols:   227
-  CStrings:  1498
+  CStrings:  1499
 
Functions:
~ sub_10000f4a0 : 1484 -> 1540
~ sub_100041d5c -> sub_100041d94 : 44 -> 60
CStrings:
+ "no map file"
```
