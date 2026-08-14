## libdispatch.dylib

> `/usr/lib/system/introspection/libdispatch.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__dof_dispatch`
- `__TEXT.__dof_voucher`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`
- `__DATA_DIRTY.__data`

```diff

-1521.120.2.0.0
-  __TEXT.__text: 0x49284
+1521.120.4.0.0
+  __TEXT.__text: 0x492bc
   __TEXT.__auth_stubs: 0xd00
   __TEXT.__objc_stubs: 0x1e0
   __TEXT.__objc_methlist: 0x684

   - /usr/lib/system/libsystem_platform.dylib
   - /usr/lib/system/libsystem_pthread.dylib
   - /usr/lib/system/libunwind.dylib
-  Functions: 1511
-  Symbols:   2177
+  Functions: 1512
+  Symbols:   2178
   CStrings:  631
 
Symbols:
+ __dispatch_event_update_all_deferred
Functions:
~ __dispatch_mach_send_drain : 1164 -> 1196
+ __dispatch_event_update_all_deferred
```
