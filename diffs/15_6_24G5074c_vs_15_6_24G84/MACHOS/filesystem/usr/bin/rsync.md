## rsync

> `/usr/bin/rsync`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-146.140.14.0.0
-  __TEXT.__text: 0x48da8
+146.140.15.0.0
+  __TEXT.__text: 0x48df8
   __TEXT.__auth_stubs: 0xcb0
   __TEXT.__const: 0x57d8
-  __TEXT.__cstring: 0x7821
+  __TEXT.__cstring: 0x7834
   __TEXT.__oslogstring: 0x2dc4
   __TEXT.__unwind_info: 0x5f0
   __TEXT.__eh_frame: 0x48

   - /usr/lib/libresolv.9.dylib
   - /usr/lib/libsbuf.dylib
   - /usr/lib/libutil.dylib
-  Functions: 1146
+  Functions: 1147
   Symbols:   227
-  CStrings:  1499
+  CStrings:  1500
 
Functions:
~ sub_10001febc : 592 -> 628
+ sub_100044778
CStrings:
+ "log_file != stdout"
```
