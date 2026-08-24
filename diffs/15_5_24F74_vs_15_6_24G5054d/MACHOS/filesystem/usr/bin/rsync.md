## rsync

> `/usr/bin/rsync`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`

```diff

-146.120.5.0.0
-  __TEXT.__text: 0x48ea8
-  __TEXT.__auth_stubs: 0xca0
+146.140.11.0.1
+  __TEXT.__text: 0x48cb8
+  __TEXT.__auth_stubs: 0xcb0
   __TEXT.__const: 0x57d8
-  __TEXT.__cstring: 0x77aa
-  __TEXT.__oslogstring: 0x2d88
+  __TEXT.__cstring: 0x7832
+  __TEXT.__oslogstring: 0x2db8
   __TEXT.__unwind_info: 0x5f0
   __TEXT.__eh_frame: 0x48
-  __DATA_CONST.__auth_got: 0x650
+  __DATA_CONST.__auth_got: 0x658
   __DATA_CONST.__got: 0x48
   __DATA_CONST.__auth_ptr: 0x20
-  __DATA_CONST.__const: 0x1888
+  __DATA_CONST.__const: 0x18c8
   __DATA.__data: 0x760
-  __DATA.__bss: 0xbc1
+  __DATA.__bss: 0xbd1
   __DATA.__common: 0x100
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libresolv.9.dylib
   - /usr/lib/libsbuf.dylib
   - /usr/lib/libutil.dylib
-  Functions: 1143
-  Symbols:   226
-  CStrings:  1494
+  Functions: 1147
+  Symbols:   227
+  CStrings:  1501
 
Symbols:
+ _warn
CStrings:
+ " (xfer#%zu, to-check=%zu/%zu)\n"
+ "%s %11.0jd %s %s%s%s"
+ "%s: fchown to %d.%d"
+ "%s: ftruncate"
+ "%s: unable to escalate mode"
+ "%zu\n"
+ "Failed to set --no-cache"
+ "fl.flp != NULL || fl.sz == 0"
+ "flist_assert_wpath_len"
+ "pathname too long"
+ "wpath != NULL"
+ "wpath[0] != '\\0'"
- " (xfer#%zu, to-check=%d/%d)\n"
- "%llu\n"
- "%s %11.0lld %s %s%s%s"
- "%s: unable to escalate dir mode"
- "f->wpath[0] != '\\0'"
```
