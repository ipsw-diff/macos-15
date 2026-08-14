## libsystem_kernel.dylib

> `/usr/lib/system/libsystem_kernel.dylib`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__AUTH_CONST.__const`
- `__DATA.__data`
- `__DATA_DIRTY.__data`

```diff

-11417.120.96.501.2
-  __TEXT.__text: 0x338e4
-  __TEXT.__const: 0xc90
+11417.120.105.501.1
+  __TEXT.__text: 0x33b48
+  __TEXT.__const: 0xc98
   __TEXT.__cstring: 0x5b94
-  __TEXT.__unwind_info: 0xb20
+  __TEXT.__unwind_info: 0xb28
   __DATA_CONST.__const: 0x2380
   __AUTH_CONST.__const: 0x120
   __DATA.__crash_info: 0x40

   __DATA_DIRTY.__data: 0x18
   __DATA_DIRTY.__bss: 0x34
   __DATA_DIRTY.__common: 0x67c
-  Functions: 1493
-  Symbols:   1668
+  Functions: 1495
+  Symbols:   1670
   CStrings:  736
 
Symbols:
+ __kernelrpc_mach_vm_update_pointers_with_remote_tags
+ _mach_vm_update_pointers_with_remote_tags
Functions:
+ _mach_vm_update_pointers_with_remote_tags
+ __kernelrpc_mach_vm_update_pointers_with_remote_tags
```
