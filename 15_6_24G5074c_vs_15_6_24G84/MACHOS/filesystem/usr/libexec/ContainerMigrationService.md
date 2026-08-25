## ContainerMigrationService

> `/usr/libexec/ContainerMigrationService`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA.__objc_selrefs`

```diff

-153.100.10.0.0
-  __TEXT.__text: 0xdf8
-  __TEXT.__auth_stubs: 0x270
+153.140.2.0.0
+  __TEXT.__text: 0x1028
+  __TEXT.__auth_stubs: 0x2d0
   __TEXT.__objc_stubs: 0x100
   __TEXT.__const: 0x30
-  __TEXT.__gcc_except_tab: 0xb0
-  __TEXT.__cstring: 0x87
-  __TEXT.__oslogstring: 0x21e
+  __TEXT.__gcc_except_tab: 0xb8
+  __TEXT.__cstring: 0xb1
+  __TEXT.__oslogstring: 0x282
   __TEXT.__objc_methname: 0x124
   __TEXT.__unwind_info: 0xa0
-  __DATA_CONST.__auth_got: 0x148
+  __DATA_CONST.__auth_got: 0x178
   __DATA_CONST.__got: 0x60
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__objc_imageinfo: 0x8

   - /System/Library/PrivateFrameworks/SecCodeWrapper.framework/Versions/A/SecCodeWrapper
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 10
-  Symbols:   56
-  CStrings:  23
+  Functions: 15
+  Symbols:   62
+  CStrings:  26
 
Symbols:
+ __qtn_proc_alloc
+ __qtn_proc_apply_to_self
+ __qtn_proc_free
+ __qtn_proc_set_flags
+ __qtn_proc_set_identifier
+ _sandbox_init
CStrings:
+ "%{public}s[uid=%u] failed to enter sandbox: %s"
+ "%{public}s[uid=%u] failed to quarantine self with %d"
+ "(version 1)(allow default)(deny qtn-user)"
```
