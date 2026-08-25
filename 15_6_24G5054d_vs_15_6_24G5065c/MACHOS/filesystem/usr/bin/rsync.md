## rsync

> `/usr/bin/rsync`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-146.140.11.0.1
-  __TEXT.__text: 0x48cb8
+146.140.13.0.0
+  __TEXT.__text: 0x48d60
   __TEXT.__auth_stubs: 0xcb0
   __TEXT.__const: 0x57d8
-  __TEXT.__cstring: 0x7832
+  __TEXT.__cstring: 0x7815
   __TEXT.__oslogstring: 0x2db8
   __TEXT.__unwind_info: 0x5f0
   __TEXT.__eh_frame: 0x48

   __DATA_CONST.__auth_ptr: 0x20
   __DATA_CONST.__const: 0x18c8
   __DATA.__data: 0x760
-  __DATA.__bss: 0xbd1
+  __DATA.__bss: 0xbc9
   __DATA.__common: 0x100
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libresolv.9.dylib
   - /usr/lib/libsbuf.dylib
   - /usr/lib/libutil.dylib
-  Functions: 1147
+  Functions: 1146
   Symbols:   227
-  CStrings:  1501
+  CStrings:  1498
 
CStrings:
+ "log_format_type"
- "%i %n"
- "%n%L"
- "log_format"
- "log_sess->mplex_writes"
```
