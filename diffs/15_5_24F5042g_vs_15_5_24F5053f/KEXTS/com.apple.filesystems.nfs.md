## com.apple.filesystems.nfs

> `com.apple.filesystems.nfs`

```diff

-327.100.3.0.0
+327.120.2.0.0
   __TEXT.__cstring: 0x8cc1
   __TEXT.__const: 0x3dc
-  __TEXT_EXEC.__text: 0x8c69c
+  __TEXT_EXEC.__text: 0x8c6e0
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xee0
   __DATA.__common: 0xc94
Symbols:
+ nfs4_create_rpc.kalloc_type_view_7355
+ nfs4_create_rpc.kalloc_type_view_7477
+ nfs4_open_rpc_internal.kalloc_type_view_5497
+ nfs4_open_rpc_internal.kalloc_type_view_5768
+ nfs4_vnop_rmdir.kalloc_type_view_7797
+ nfs4_vnop_rmdir.kalloc_type_view_7834
+ nfs_file_lock_alloc.kalloc_type_view_3691
+ nfs_file_lock_destroy.kalloc_type_view_3709
+ nfs_lock_owner_destroy.kalloc_type_view_3544
+ nfs_lock_owner_find.kalloc_type_view_3504
+ nfs_open_file_destroy.kalloc_type_view_2298
+ nfs_vnop_reclaim.kalloc_type_view_1129
- nfs4_create_rpc.kalloc_type_view_7345
- nfs4_create_rpc.kalloc_type_view_7467
- nfs4_open_rpc_internal.kalloc_type_view_5487
- nfs4_open_rpc_internal.kalloc_type_view_5758
- nfs4_vnop_rmdir.kalloc_type_view_7787
- nfs4_vnop_rmdir.kalloc_type_view_7824
- nfs_file_lock_alloc.kalloc_type_view_3681
- nfs_file_lock_destroy.kalloc_type_view_3699
- nfs_lock_owner_destroy.kalloc_type_view_3534
- nfs_lock_owner_find.kalloc_type_view_3494
- nfs_open_file_destroy.kalloc_type_view_2288
- nfs_vnop_reclaim.kalloc_type_view_1130
Functions:
~ _nfs_open_file_destroy : 208 -> 368
~ _nfs_vnop_reclaim : 3724 -> 3632
```
