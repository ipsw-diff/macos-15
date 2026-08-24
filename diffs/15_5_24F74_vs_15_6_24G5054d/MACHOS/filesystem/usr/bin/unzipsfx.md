## unzipsfx

> `/usr/bin/unzipsfx`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__got`
- `__DATA.__data`

```diff

-27.0.0.0.0
-  __TEXT.__text: 0xb35c
-  __TEXT.__auth_stubs: 0x400
-  __TEXT.__const: 0x128b
-  __TEXT.__cstring: 0x487
-  __TEXT.__unwind_info: 0x148
-  __DATA_CONST.__auth_got: 0x200
+29.0.0.0.0
+  __TEXT.__text: 0xb578
+  __TEXT.__auth_stubs: 0x450
+  __TEXT.__const: 0x12bb
+  __TEXT.__cstring: 0x42a
+  __TEXT.__unwind_info: 0x140
+  __DATA_CONST.__auth_got: 0x228
   __DATA_CONST.__got: 0x28
   __DATA.__data: 0x30
   __DATA.__bss: 0x8
-  __DATA.__common: 0xccc70
+  __DATA.__common: 0xccc78
   - /usr/lib/libSystem.B.dylib
-  Functions: 66
-  Symbols:   264
-  CStrings:  60
+  Functions: 67
+  Symbols:   271
+  CStrings:  59
 
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
- "checkdir error:  cannot enter %s\n                 %s\n                 unable to process %s.\n"
```
