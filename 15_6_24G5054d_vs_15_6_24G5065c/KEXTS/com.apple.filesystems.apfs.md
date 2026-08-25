## com.apple.filesystems.apfs

> `com.apple.filesystems.apfs`

```diff

-2332.140.8.0.1
+2332.140.11.0.0
   __TEXT.__const: 0xaf8
-  __TEXT.__cstring: 0x5769f
-  __TEXT_EXEC.__text: 0x1845b4
+  __TEXT.__cstring: 0x57690
+  __TEXT_EXEC.__text: 0x1845b8
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xd50
   __DATA.__bss: 0xb08

   __DATA_CONST.__assert: 0x294
   Functions: 2629
   Symbols:   4772
-  CStrings:  7507
+  CStrings:  7506
 
Symbols:
+ apfs_graft.kalloc_type_view_1003
+ apfs_graft.kalloc_type_view_1148
+ graft_state_smr_cb.kalloc_type_view_1462
+ vnoflush_drop.kalloc_type_view_524
+ vnoflush_take.kalloc_type_view_474
- apfs_graft.kalloc_type_view_1009
- apfs_graft.kalloc_type_view_1154
- graft_state_smr_cb.kalloc_type_view_1468
- vnoflush_drop.kalloc_type_view_528
- vnoflush_take.kalloc_type_view_476
Functions:
~ _apfs_graft_is_vnoflush : 132 -> 140
~ _set_parent_chain_noflush : 692 -> 688
CStrings:
+ "2025/06/22"
+ "21:37:58"
+ "2332.140.11"
+ "Jun 22 2025"
+ "apfs-2332.140.11"
- "2025/06/11"
- "21:16:46"
- "21:16:47"
- "2332.140.8.0.1"
- "Jun 11 2025"
- "apfs-2332.140.8.0.1"
```
