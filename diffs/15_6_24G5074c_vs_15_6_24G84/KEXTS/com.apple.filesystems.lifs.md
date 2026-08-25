## com.apple.filesystems.lifs

> `com.apple.filesystems.lifs`

```diff

-531.140.7.0.2
+531.140.9.0.3
   __TEXT.__os_log: 0x12db
-  __TEXT.__cstring: 0x2167
+  __TEXT.__cstring: 0x2184
   __TEXT.__const: 0x2c0
   __TEXT_EXEC.__text: 0x1b3a4
   __TEXT_EXEC.__auth_stubs: 0x0
CStrings:
+ "%s: client %p pid: %d pidversion: %d supportBlockResource: %d\n"
+ "ALUC:clientDied(pid: %d pidversion: %d), fskitd_entitled %d fsmodule_entitled %d support_block_resource %d\n"
+ "ALUC:init(pid: %d pidversion: %d), fskitd_entitled %d fsmodule_entitled %d support_block_resource %d\n"
- "%s: client %p pid: %d pidversion: %d supportKOIO: %d\n"
- "ALUC:clientDied(pid: %d pidversion: %d), fskitd_entitled %d fsmodule_entitled %d support_koio %d\n"
- "ALUC:init(pid: %d pidversion: %d), fskitd_entitled %d fsmodule_entitled %d support_koio %d\n"
```
