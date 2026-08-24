## com.apple.filesystems.acfs

> `com.apple.filesystems.acfs`

```diff

-782.120.2.0.0
-  __TEXT.__cstring: 0x37081
-  __TEXT.__const: 0x3697
-  __TEXT_EXEC.__text: 0xd7e6c
+782.140.2.0.0
+  __TEXT.__cstring: 0x37212
+  __TEXT.__const: 0x36a0
+  __TEXT_EXEC.__text: 0xd7ea8
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x12498
   __DATA.__common: 0x613c

   __DATA_CONST.__kalloc_type: 0x2c0
   Functions: 3882
   Symbols:   3102
-  CStrings:  5145
+  CStrings:  5146
 
Functions:
~ _dmfs_write_dispatch : 1228 -> 1288
CStrings:
+ "dmfs_write_dispatch: dmcli_data_offset(%u) + dmcli_data_length(%u) overflow"
```
