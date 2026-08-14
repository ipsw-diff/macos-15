## com.apple.filesystems.apfs

> `com.apple.filesystems.apfs`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-2332.120.27.0.0
+2332.120.29.0.0
   __TEXT.__const: 0xaf8
   __TEXT.__cstring: 0x5771a
-  __TEXT_EXEC.__text: 0x18464c
+  __TEXT_EXEC.__text: 0x184634
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xd50
   __DATA.__bss: 0xb08
Functions:
~ _apfs_vnop_exchange : 3972 -> 3948
CStrings:
+ "2025/04/10"
+ "20:18:06"
+ "20:18:07"
+ "2332.120.29"
+ "Apr 10 2025"
+ "apfs-2332.120.29"
- "2025/03/26"
- "22:13:31"
- "22:13:32"
- "2332.120.27"
- "Mar 26 2025"
- "apfs-2332.120.27"
```
