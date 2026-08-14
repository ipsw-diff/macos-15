## ssh-keysign

> `/usr/libexec/ssh-keysign`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-346.120.1.0.0
-  __TEXT.__text: 0x1cf10
+346.120.3.0.0
+  __TEXT.__text: 0x1d05c
   __TEXT.__auth_stubs: 0xdc0
   __TEXT.__const: 0x1bf50
-  __TEXT.__cstring: 0x4539
+  __TEXT.__cstring: 0x457a
   __TEXT.__unwind_info: 0x4a0
   __DATA_CONST.__auth_got: 0x6e0
   __DATA_CONST.__got: 0x30

   - /usr/lib/libpam.2.dylib
   - /usr/lib/libresolv.9.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 367
+  Functions: 368
   Symbols:   250
-  CStrings:  745
+  CStrings:  752
 
Functions:
~ sub_100005cec : 3000 -> 3220
+ sub_10000d988
CStrings:
+ "exec="
+ "host="
+ "localnetwork="
+ "localuser="
+ "originalhost="
+ "tagged="
+ "user="
```
