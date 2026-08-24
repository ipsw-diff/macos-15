## zipinfo

> `/usr/bin/zipinfo`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-27.0.0.0.0
-  __TEXT.__text: 0x15cfc
-  __TEXT.__auth_stubs: 0x480
-  __TEXT.__const: 0x4a4f
-  __TEXT.__cstring: 0x3014
-  __TEXT.__unwind_info: 0x1a8
-  __DATA_CONST.__auth_got: 0x240
+29.0.0.0.0
+  __TEXT.__text: 0x15f18
+  __TEXT.__auth_stubs: 0x4d0
+  __TEXT.__const: 0x4a7f
+  __TEXT.__cstring: 0x2fb7
+  __TEXT.__unwind_info: 0x1a0
+  __DATA_CONST.__auth_got: 0x268
   __DATA_CONST.__got: 0x28
   __DATA_CONST.__const: 0x9e0
   __DATA.__data: 0x38
   __DATA.__bss: 0x8
-  __DATA.__common: 0xf0cc0
+  __DATA.__common: 0xf0cc8
   - /usr/lib/libSystem.B.dylib
-  Functions: 97
-  Symbols:   630
-  CStrings:  327
+  Functions: 98
+  Symbols:   637
+  CStrings:  326
 
Symbols:
+ _CannotEnterDir
+ ___open_outfile
+ _fdopen
+ _fstatat
+ _mkdirat
+ _openat
+ _renameat
+ _unlinkat
- _rename
Functions:
~ _open_outfile : 888 -> 380
+ ___open_outfile
~ _globalsCtor : 240 -> 252
~ _mapname : 1388 -> 1408
~ _checkdir : 2228 -> 2048
~ _mkdir_qtn : 128 -> 344
CStrings:
+ "Jun  3 2025"
- "Apr 18 2025"
- "checkdir error:  cannot enter %s\n                 %s\n                 unable to process %s.\n"
```
