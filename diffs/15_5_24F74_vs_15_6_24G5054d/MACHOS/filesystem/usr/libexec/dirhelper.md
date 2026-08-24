## dirhelper

> `/usr/libexec/dirhelper`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__got`

```diff

-178.0.0.0.0
-  __TEXT.__text: 0x399c
-  __TEXT.__auth_stubs: 0x4e0
-  __TEXT.__const: 0xa0
-  __TEXT.__cstring: 0x1fc
-  __TEXT.__oslogstring: 0x573
-  __TEXT.__unwind_info: 0x120
-  __DATA_CONST.__auth_got: 0x270
+178.1.0.0.0
+  __TEXT.__text: 0x484c
+  __TEXT.__auth_stubs: 0x5c0
+  __TEXT.__const: 0xa8
+  __TEXT.__cstring: 0x423
+  __TEXT.__oslogstring: 0x4c5
+  __TEXT.__unwind_info: 0x138
+  __DATA_CONST.__auth_got: 0x2e0
   __DATA_CONST.__got: 0x48
-  __DATA_CONST.__const: 0x1c0
-  __DATA.__data: 0x18
+  __DATA_CONST.__const: 0x238
+  __DATA.__data: 0x38
   __DATA.__bss: 0x10
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
-  Functions: 55
-  Symbols:   148
-  CStrings:  73
+  Functions: 63
+  Symbols:   179
+  CStrings:  88
 
Symbols:
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Binaries/libcoreservices_executables/install/TempContent/Objects/libcoreservices.build/dirhelper.build/Objects-normal/arm64e/utilities.o
+ /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/libcoreservices_executables/common/
+ _OUTLINED_FUNCTION_4
+ __X__dirhelper_internal_server
+ __X__dirhelper_internal_server_test
+ __X__dirhelper_remove_test
+ __dirhelper_internal_server
+ __dyld_get_image_uuid
+ __dyld_get_shared_cache_range
+ __dyld_get_shared_cache_uuid
+ __os_log_simple
+ _access
+ _chmod
+ _do___dirhelper_internal_server
+ _do___dirhelper_internal_server_test
+ _do___dirhelper_remove_test
+ _is_app_sandboxed_with_audit_token
+ _makeDirectoryWithUIDAndGID
+ _mkdir
+ _mkdir_rootless
+ _modes
+ _os_variant_has_internal_content
+ _removefile
+ _removefile_state_alloc
+ _removefile_state_free
+ _sandbox_container_path_for_audit_token
+ _strlcat
+ _strlcpy
+ _strnstr
+ _subdirs
+ _validate_user_dir_suffix
+ mkdir_rootless
+ utilities.c
- _fcntl
- do___dirhelper_mkdir_rootless
CStrings:
+ "%s: access: %s: %s (%d)"
+ "%s: chmod error: %s (%d)"
+ "%s: chown error for uid=%d, gid=%d: %s (%d)"
+ "%s: created %s"
+ "%s: mkdir: path=%s mode=%o: %s (%d)"
+ "%s: set uid=%d, gid=%d"
+ "/../"
+ "/tmp/"
+ "Out of range: which=%d"
+ "_dirhelper_userdir"
+ "buffer too small: pathlen=%zu path=%s userdir_suffix=%s"
+ "buffer too small: pathlen=%zu userdir=%s subdirs[%d]=%s"
+ "com.apple.dirhelper"
+ "com.apple.libcoreservices"
+ "container_name not set"
+ "error making suffix dir %s%s: %s (%d)"
+ "illegal path traversal (..) pattern found in DIRHELPER_ENV_USER_DIR_SUFFIX"
+ "makeDirectoryWithUIDAndGID"
+ "sandboxed process asked for translocation directory"
+ "stat: %s: %s (%d)"
+ "tmp/"
- "%s: error getting path for file descriptor %d: %{errono}d"
- "%s: file descriptor could not be obtained"
- "%s: path plus suffix exceeds max path: %s"
- "%s: suffix contains a slash: %s"
- "create user local suffix directory"
- "do___dirhelper_mkdir_rootless"
```
