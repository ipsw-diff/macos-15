## com.apple.filesystems.apfs

> `com.apple.filesystems.apfs`

```diff

-2332.140.12.0.0
+2332.140.13.0.0
   __TEXT.__const: 0xaf8
-  __TEXT.__cstring: 0x57699
-  __TEXT_EXEC.__text: 0x1845b8
+  __TEXT.__cstring: 0x57719
+  __TEXT_EXEC.__text: 0x184a98
   __TEXT_EXEC.__auth_stubs: 0x0
-  __DATA.__data: 0xd50
-  __DATA.__bss: 0xb08
-  __DATA_CONST.__auth_got: 0x12e0
+  __DATA.__data: 0xd48
+  __DATA.__bss: 0xb10
+  __DATA_CONST.__auth_got: 0x12e8
   __DATA_CONST.__got: 0x1b8
   __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__mod_init_func: 0x10

   __DATA_CONST.__kalloc_type: 0x6180
   __DATA_CONST.__kalloc_var: 0x3250
   __DATA_CONST.__assert: 0x294
-  Functions: 2629
-  Symbols:   4772
-  CStrings:  7507
+  Functions: 2630
+  Symbols:   4774
+  CStrings:  7510
 
Symbols:
+ _block_is_unwritten
+ _ubc_was_mapped_writable
+ apfs_drop_allocated_unwritten_ranges.kalloc_type_view_16101
+ apfs_drop_rangelist_entries.kalloc_type_view_9057
+ apfs_drop_rangelist_entry.kalloc_type_view_9004
+ apfs_find_gaps_in_rangelist.kalloc_type_view_11867
+ apfs_flush_allocated_unwritten_ranges.kalloc_type_view_13531
+ apfs_flush_allocated_unwritten_ranges.kalloc_type_view_13589
+ apfs_io_common.kalloc_type_view_18289
+ apfs_io_common.kalloc_type_view_18327
+ apfs_io_common.kalloc_type_view_18338
+ apfs_io_common.kalloc_type_view_18356
+ apfs_io_common.kalloc_type_view_18374
+ apfs_io_common.kalloc_type_view_18390
+ apfs_io_common.kalloc_type_view_18414
+ apfs_io_common.kalloc_type_view_18497
+ apfs_io_common.kalloc_type_view_18518
+ apfs_io_common.kalloc_type_view_18529
+ apfs_io_common.kalloc_type_view_18547
+ apfs_io_common.kalloc_type_view_18566
+ apfs_io_common.kalloc_type_view_18579
+ apfs_io_common.kalloc_type_view_18600
+ apfs_io_common.kalloc_type_view_18612
+ apfs_io_common.kalloc_type_view_18619
+ apfs_iodone.kalloc_type_view_17751
+ apfs_iodone.kalloc_type_view_17790
+ apfs_record_intention_to_allocate.kalloc_type_view_8944
+ apfs_release_all_reserved_space.kalloc_type_view_4528
+ apfs_release_io_context.kalloc_type_view_17989
+ apfs_release_io_context.kalloc_type_view_17998
+ apfs_trim_ranges_in_region.kalloc_type_view_16803
+ apfs_update_ranges_on_allocation.kalloc_type_view_16894
+ apfs_vnop_blockmap.kalloc_type_view_17309
+ apfs_vnop_blockmap.kalloc_type_view_17670
+ apfs_vnop_getattrlistbulk.kalloc_type_view_19353
+ apfs_vnop_getattrlistbulk.kalloc_type_view_19360
+ apfs_vnop_getattrlistbulk.kalloc_type_view_19427
+ apfs_vnop_getattrlistbulk.kalloc_type_view_19451
+ apfs_vnop_readdir.kalloc_type_view_15706
+ apfs_vnop_readdir.kalloc_type_view_15722
+ apfs_vnop_readdir.kalloc_type_view_15841
+ apfs_vnop_readdir.kalloc_type_view_15851
+ apfs_vnop_readdir.kalloc_type_view_15872
+ ier_alloc_tls.kalloc_type_view_28047
+ ier_alloc_tls.kalloc_type_view_28054
+ ier_alloc_tls.kalloc_type_view_28100
+ ier_alloc_tls.kalloc_type_view_28102
+ ier_free_tls.kalloc_type_view_28129
+ ier_free_tls.kalloc_type_view_28133
+ ier_ierso_free.kalloc_type_view_27222
+ ier_ierso_load.kalloc_type_view_27236
+ ier_ierso_load.kalloc_type_view_27248
+ ier_ierso_new.kalloc_type_view_26931
+ ier_ierso_new.kalloc_type_view_26964
+ ier_ierto_free.kalloc_type_view_24826
+ ier_ierto_new.kalloc_type_view_24812
+ pfkur_pfkurso_free.kalloc_type_view_36290
+ pfkur_pfkurso_new.kalloc_type_view_34690
+ update_parent_xattr.kalloc_type_view_20557
+ update_parent_xattr.kalloc_type_view_20687
- apfs_drop_allocated_unwritten_ranges.kalloc_type_view_15930
- apfs_drop_rangelist_entries.kalloc_type_view_9055
- apfs_drop_rangelist_entry.kalloc_type_view_9002
- apfs_find_gaps_in_rangelist.kalloc_type_view_11732
- apfs_flush_allocated_unwritten_ranges.kalloc_type_view_13360
- apfs_flush_allocated_unwritten_ranges.kalloc_type_view_13418
- apfs_io_common.kalloc_type_view_18118
- apfs_io_common.kalloc_type_view_18156
- apfs_io_common.kalloc_type_view_18167
- apfs_io_common.kalloc_type_view_18185
- apfs_io_common.kalloc_type_view_18203
- apfs_io_common.kalloc_type_view_18219
- apfs_io_common.kalloc_type_view_18243
- apfs_io_common.kalloc_type_view_18326
- apfs_io_common.kalloc_type_view_18347
- apfs_io_common.kalloc_type_view_18358
- apfs_io_common.kalloc_type_view_18376
- apfs_io_common.kalloc_type_view_18395
- apfs_io_common.kalloc_type_view_18408
- apfs_io_common.kalloc_type_view_18429
- apfs_io_common.kalloc_type_view_18441
- apfs_io_common.kalloc_type_view_18448
- apfs_iodone.kalloc_type_view_17580
- apfs_iodone.kalloc_type_view_17619
- apfs_record_intention_to_allocate.kalloc_type_view_8942
- apfs_release_all_reserved_space.kalloc_type_view_4526
- apfs_release_io_context.kalloc_type_view_17818
- apfs_release_io_context.kalloc_type_view_17827
- apfs_trim_ranges_in_region.kalloc_type_view_16632
- apfs_update_ranges_on_allocation.kalloc_type_view_16723
- apfs_vnop_blockmap.kalloc_type_view_17138
- apfs_vnop_blockmap.kalloc_type_view_17499
- apfs_vnop_getattrlistbulk.kalloc_type_view_19182
- apfs_vnop_getattrlistbulk.kalloc_type_view_19189
- apfs_vnop_getattrlistbulk.kalloc_type_view_19256
- apfs_vnop_getattrlistbulk.kalloc_type_view_19280
- apfs_vnop_readdir.kalloc_type_view_15535
- apfs_vnop_readdir.kalloc_type_view_15551
- apfs_vnop_readdir.kalloc_type_view_15670
- apfs_vnop_readdir.kalloc_type_view_15680
- apfs_vnop_readdir.kalloc_type_view_15701
- ier_alloc_tls.kalloc_type_view_27841
- ier_alloc_tls.kalloc_type_view_27848
- ier_alloc_tls.kalloc_type_view_27894
- ier_alloc_tls.kalloc_type_view_27896
- ier_free_tls.kalloc_type_view_27923
- ier_free_tls.kalloc_type_view_27927
- ier_ierso_free.kalloc_type_view_27016
- ier_ierso_load.kalloc_type_view_27030
- ier_ierso_load.kalloc_type_view_27042
- ier_ierso_new.kalloc_type_view_26725
- ier_ierso_new.kalloc_type_view_26758
- ier_ierto_free.kalloc_type_view_24620
- ier_ierto_new.kalloc_type_view_24606
- pfkur_pfkurso_free.kalloc_type_view_36084
- pfkur_pfkurso_new.kalloc_type_view_34484
- update_parent_xattr.kalloc_type_view_20386
- update_parent_xattr.kalloc_type_view_20516
Functions:
~ _prepare_write_and_lock : 7176 -> 7236
~ _ino_shrink : 4316 -> 4448
~ _apfs_truncate_locked : 3616 -> 4304
+ _block_is_unwritten
CStrings:
+ "%s:%d: %s cannot zero out prealloc'ed region [%lld, %lld) of ino %llu; old_eof=%lld, error=%d\n"
+ "2025/07/14"
+ "2332.140.13"
+ "23:35:30"
+ "23:35:31"
+ "Jul 14 2025"
+ "apfs-2332.140.13"
+ "block_is_unwritten"
+ "need_zerofill"
- "2025/07/02"
- "22:44:53"
- "22:44:54"
- "2332.140.12"
- "Jul  2 2025"
- "apfs-2332.140.12"
```
