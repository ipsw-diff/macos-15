## libsystem_coreservices.dylib

> `/usr/lib/system/libsystem_coreservices.dylib`

```diff

-178.0.0.0.0
-  __TEXT.__text: 0x4a30
-  __TEXT.__auth_stubs: 0x550
+178.1.0.0.0
+  __TEXT.__text: 0x5250
+  __TEXT.__auth_stubs: 0x590
   __TEXT.__const: 0xb8
-  __TEXT.__cstring: 0x43b
-  __TEXT.__oslogstring: 0x671
-  __TEXT.__unwind_info: 0x130
+  __TEXT.__cstring: 0x4f2
+  __TEXT.__oslogstring: 0x569
+  __TEXT.__unwind_info: 0x158
   __DATA_CONST.__got: 0x20
-  __DATA_CONST.__const: 0x928
-  __AUTH_CONST.__auth_got: 0x2a8
-  __AUTH_CONST.__const: 0x60
-  __DATA.__bss: 0x30
+  __DATA_CONST.__const: 0x8e8
+  __AUTH_CONST.__auth_got: 0x2c8
+  __AUTH_CONST.__const: 0x40
+  __DATA.__data: 0x20
+  __DATA.__bss: 0x20
   __DATA.__common: 0x88
   - /usr/lib/system/libcompiler_rt.dylib
   - /usr/lib/system/libdispatch.dylib

   - /usr/lib/system/libsystem_sandbox.dylib
   - /usr/lib/system/libsystem_trace.dylib
   - /usr/lib/system/libxpc.dylib
-  Functions: 92
-  Symbols:   205
-  CStrings:  108
+  Functions: 97
+  Symbols:   216
+  CStrings:  110
 
Symbols:
+ ___dirhelper_internal_server
+ ___dirhelper_internal_server_test
+ ___dirhelper_remove_test
+ __dirhelper_internal_client
+ __dirhelper_remove_test
+ __dirhelper_test
+ __dirhelper_userdir
+ __dyld_get_image_uuid
+ __dyld_get_shared_cache_range
+ __dyld_get_shared_cache_uuid
+ __os_log_simple
+ _append_path_component
+ _dirhelper_internal_client
+ _dirhelper_remove_test
+ _dirhelper_test
+ _dirhelper_userdir
+ _get_userdir_suffix_for_which
+ _getegid
+ _lchown
+ _makeDirectory
+ _makeDirectoryWithUIDAndGID
+ _strerror
+ _validate_user_dir_suffix
+ get_userdir_suffix_for_which
- _OUTLINED_FUNCTION_13
- _OUTLINED_FUNCTION_14
- ___dirhelper_mkdir_rootless
- ___isPreGlowHost_block_invoke
- ___makeDirectory
- ___makeRootlessDirectory
- ___strlcat_chk
- __makeDirectory
- __makeRootlessDirectory
- __os_log_debug_impl
- _sysctlbyname
- isPreGlowHost.isPreGlow
- isPreGlowHost.onceToken
CStrings:
+ "%s: __dirhelper_internal_server mach result=MIG_BAD_ID, path=%s"
+ "%s: __dirhelper_internal_server not permitted for %s, creating in-process"
+ "%s: __dirhelper_internal_server result: %{errno}d,  mach result: %s (%#x)"
+ "%s: chmod error: %s (%d)"
+ "%s: chown error for uid=%d, gid=%d: %s (%d)"
+ "%s: created %s"
+ "%s: mkdir: path=%s mode=%o: %s (%d)"
+ "%s: result=%s (%d) "
+ "%s: set uid=%d, gid=%d"
+ "_dirhelper_internal"
+ "_dirhelper_remove_test"
+ "_dirhelper_test"
+ "makeDirectoryWithUIDAndGID"
- "%s: __dirhelper_mkdir_rootless mach result=MIG_BAD_ID, path=%s"
- "%s: __dirhelper_mkdir_rootless not permitted for %s, creating in-process"
- "%s: __dirhelper_mkdir_rootless result: %{errno}d,  mach result: %s (%#x)"
- "%s: open failed: %{errno}d, rootpath=%s"
- "%s: path exists: %s"
- "%s: target path exceeds max path. path=%s, suffix=%s"
- "__makeDirectory: created %{public}s"
- "__makeRootlessDirectory"
- "illegal path traversal (..) pattern found in DIRHELPER_ENV_USER_DIR_SUFFIX"
- "kern.osproductversion"
- "mkdir: path=%{public}s mode= %{darwin.mode}d: %{darwin.errno}d"
```
