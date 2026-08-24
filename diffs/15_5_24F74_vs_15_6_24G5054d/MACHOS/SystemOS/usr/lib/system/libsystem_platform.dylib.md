## libsystem_platform.dylib

> `/usr/lib/system/libsystem_platform.dylib`

### Sections with Same Size but Changed Content

- `__AUTH_CONST.__const`
- `__DATA_DIRTY.__la_resolver`

```diff

-349.0.0.0.0
-  __TEXT.__text: 0x6538
+349.140.6.0.0
+  __TEXT.__text: 0x6738
   __TEXT.__stubs: 0x30
-  __TEXT.__auth_stubs: 0x220
+  __TEXT.__auth_stubs: 0x230
   __TEXT.__resolver_help: 0x1b0
-  __TEXT.__const: 0x70
-  __TEXT.__cstring: 0x78d
-  __TEXT.__unwind_info: 0x218
+  __TEXT.__const: 0x78
+  __TEXT.__cstring: 0x7c4
+  __TEXT.__unwind_info: 0x228
   __DATA_CONST.__got: 0x20
-  __AUTH_CONST.__auth_got: 0x110
+  __AUTH_CONST.__auth_got: 0x118
   __AUTH_CONST.__const: 0x108
   __DATA.__crash_info: 0x40
   __DATA_DIRTY.__la_resolver: 0x20
+  __DATA_DIRTY.__data: 0x8
   __DATA_DIRTY.__common: 0x14
   - /usr/lib/system/libsystem_kernel.dylib
-  Functions: 254
-  Symbols:   312
-  CStrings:  63
+  Functions: 259
+  Symbols:   319
+  CStrings:  65
 
Symbols:
+ ___os_security_config_init
+ ___security_config
+ __os_security_config_init
+ _os_security_config_get
+ _os_security_config_get_for_proc
+ _os_security_config_get_for_task
+ _task_info
CStrings:
+ "Could not parse security_config string"
+ "security_config"
```
