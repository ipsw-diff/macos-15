## fskit_agent

> `/usr/libexec/fskit_agent`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-531.120.13.0.0
-  __TEXT.__text: 0x1d1c
-  __TEXT.__auth_stubs: 0x1f0
+531.120.18.0.0
+  __TEXT.__text: 0x2328
+  __TEXT.__auth_stubs: 0x290
   __TEXT.__objc_stubs: 0x780
   __TEXT.__objc_methlist: 0x2b4
   __TEXT.__gcc_except_tab: 0x1f8
   __TEXT.__objc_methname: 0x89a
   __TEXT.__objc_classname: 0x84
   __TEXT.__objc_methtype: 0x2ff
-  __TEXT.__const: 0x30
-  __TEXT.__oslogstring: 0x207
-  __TEXT.__cstring: 0x1f7
-  __TEXT.__unwind_info: 0xf8
-  __DATA_CONST.__auth_got: 0x108
-  __DATA_CONST.__got: 0x50
+  __TEXT.__const: 0x40
+  __TEXT.__oslogstring: 0x397
+  __TEXT.__cstring: 0x214
+  __TEXT.__unwind_info: 0x100
+  __DATA_CONST.__auth_got: 0x158
+  __DATA_CONST.__got: 0x58
   __DATA_CONST.__const: 0x1c0
   __DATA_CONST.__cfstring: 0x40
   __DATA_CONST.__objc_classlist: 0x18

   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 42
-  Symbols:   50
-  CStrings:  177
+  Functions: 53
+  Symbols:   61
+  CStrings:  188
 
Symbols:
+ ___error
+ __os_log_default
+ __os_log_error_impl
+ __set_user_dir_suffix
+ _bzero
+ _confstr
+ _getenv
+ _getpwuid
+ _getuid
+ _realpath$DARWIN_EXTSN
+ _sandbox_init_with_parameters
CStrings:
+ "$HOME not set, falling back to using getpwuid"
+ "DARWIN_CACHE_DIR"
+ "Failed to enter sandbox: %{public}s"
+ "HOME"
+ "TMPDIR"
+ "failed to get passwd entry for uid %u"
+ "failed to initialize cache directory: %{darwin.errno}d"
+ "failed to initialize temporary directory: %{darwin.errno}d"
+ "failed to resolve cache directory: %{darwin.errno}d"
+ "failed to resolve temporary directory: %{darwin.errno}d"
+ "failed to resolve user's home directory: %{darwin.errno}d"
```
