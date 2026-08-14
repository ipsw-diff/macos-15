## rsync

> `/usr/bin/rsync`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA.__data`

```diff

-146.120.3.0.0
-  __TEXT.__text: 0x48c70
+146.120.5.0.0
+  __TEXT.__text: 0x48ea8
   __TEXT.__auth_stubs: 0xca0
   __TEXT.__const: 0x57d8
-  __TEXT.__cstring: 0x7741
-  __TEXT.__oslogstring: 0x2d3c
+  __TEXT.__cstring: 0x77aa
+  __TEXT.__oslogstring: 0x2d88
   __TEXT.__unwind_info: 0x5f0
   __TEXT.__eh_frame: 0x48
   __DATA_CONST.__auth_got: 0x650
   __DATA_CONST.__got: 0x48
   __DATA_CONST.__auth_ptr: 0x20
-  __DATA_CONST.__const: 0x1868
+  __DATA_CONST.__const: 0x1888
   __DATA.__data: 0x760
   __DATA.__bss: 0xbc1
   __DATA.__common: 0x100

   - /usr/lib/libresolv.9.dylib
   - /usr/lib/libsbuf.dylib
   - /usr/lib/libutil.dylib
-  Functions: 1141
+  Functions: 1143
   Symbols:   226
-  CStrings:  1489
+  CStrings:  1494
 
CStrings:
+ "%llu\n"
+ "%s: created directory"
+ "%s: found close match in %s"
+ "%s: root directory opened"
+ "%s: unable to escalate dir mode"
+ "print-flist-chunk-size"
- "%s: unable to preserve dir mode"
```
