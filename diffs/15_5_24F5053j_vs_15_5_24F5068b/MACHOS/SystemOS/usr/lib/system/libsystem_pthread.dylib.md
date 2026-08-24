## libsystem_pthread.dylib

> `/usr/lib/system/libsystem_pthread.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_DIRTY.__data`

```diff

 536.0.0.0.0
-  __TEXT.__text: 0xaa90
+  __TEXT.__text: 0xaa98
   __TEXT.__auth_stubs: 0x460
   __TEXT.__const: 0x120
   __TEXT.__cstring: 0xdce
Functions:
~ _pthread_jit_write_protect_np : 520 -> 524
~ _pthread_jit_write_with_callback_np : 664 -> 668
```
