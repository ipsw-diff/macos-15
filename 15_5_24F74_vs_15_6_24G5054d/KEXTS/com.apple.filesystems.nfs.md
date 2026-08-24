## com.apple.filesystems.nfs

> `com.apple.filesystems.nfs`

```diff

-327.120.3.0.0
+327.140.2.0.0
   __TEXT.__cstring: 0x8cc1
   __TEXT.__const: 0x3dc
-  __TEXT_EXEC.__text: 0x8c69c
+  __TEXT_EXEC.__text: 0x8c6ec
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0xee0
   __DATA.__common: 0xc94
Symbols:
+ nfs4_create_rpc.kalloc_type_view_7356
+ nfs4_create_rpc.kalloc_type_view_7478
+ nfs4_open_rpc_internal.kalloc_type_view_5498
+ nfs4_open_rpc_internal.kalloc_type_view_5769
+ nfs4_vnop_rmdir.kalloc_type_view_7798
+ nfs4_vnop_rmdir.kalloc_type_view_7835
+ nfs_file_lock_alloc.kalloc_type_view_3692
+ nfs_file_lock_destroy.kalloc_type_view_3710
+ nfs_lock_owner_destroy.kalloc_type_view_3545
+ nfs_lock_owner_find.kalloc_type_view_3505
+ nfs_open_file_destroy.kalloc_type_view_2299
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
~ _nfs_open_file_find_internal : 520 -> 532
~ _nfs_open_file_destroy : 208 -> 368
~ _nfs_vnop_reclaim : 3724 -> 3632
```
