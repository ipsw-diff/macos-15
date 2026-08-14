## com.apple.filesystems.lifs

> `com.apple.filesystems.lifs`

```diff

-531.120.18.0.0
+531.120.18.0.2
   __TEXT.__os_log: 0x12db
   __TEXT.__cstring: 0x2167
   __TEXT.__const: 0x2c0
-  __TEXT_EXEC.__text: 0x1b390
+  __TEXT_EXEC.__text: 0x1b3a4
   __TEXT_EXEC.__auth_stubs: 0x0
   __DATA.__data: 0x5d0
   __DATA.__common: 0x138
Symbols:
+ lifs_fsync_internal.kalloc_type_view_3703
+ lifs_reclaim_done.kalloc_type_view_4615
+ lifs_setfsattr_done.kalloc_type_view_3634
+ lifs_vnop_reclaim.kalloc_type_view_4659
+ lifs_vnop_reclaim.kalloc_type_view_4713
- lifs_fsync_internal.kalloc_type_view_3694
- lifs_reclaim_done.kalloc_type_view_4606
- lifs_setfsattr_done.kalloc_type_view_3625
- lifs_vnop_reclaim.kalloc_type_view_4650
- lifs_vnop_reclaim.kalloc_type_view_4704
Functions:
~ _lifs_vnop_remove : 688 -> 708
```
