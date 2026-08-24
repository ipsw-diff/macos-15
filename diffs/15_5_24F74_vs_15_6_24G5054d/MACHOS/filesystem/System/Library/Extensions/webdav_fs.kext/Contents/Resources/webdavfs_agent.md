## webdavfs_agent

> `/System/Library/Extensions/webdav_fs.kext/Contents/Resources/webdavfs_agent`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

-399.0.0.0.0
-  __TEXT.__text: 0x156d4
+401.0.0.0.0
+  __TEXT.__text: 0x15718
   __TEXT.__auth_stubs: 0xe40
-  __TEXT.__cstring: 0x4576
+  __TEXT.__cstring: 0x45b7
   __TEXT.__const: 0x80
   __TEXT.__unwind_info: 0x3b8
   __DATA_CONST.__auth_got: 0x720

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libutil.dylib
   - /usr/lib/libxml2.2.dylib
-  Functions: 405
+  Functions: 406
   Symbols:   269
-  CStrings:  623
+  CStrings:  624
 
Functions:
~ sub_100002a50 : 432 -> 456
+ sub_10001103c
CStrings:
+ "(cur_ptr - (cur_node->name_length + 1)) >= pathbuf"
+ "(cur_ptr - (cur_node->redir_name_length + 1)) >= pathbuf"
+ "path_len + 1 <= 1024"
- "(cur_ptr - cur_node->name_length + 1) >= pathbuf"
- "(cur_ptr - cur_node->redir_name_length + 1) >= pathbuf"
```
