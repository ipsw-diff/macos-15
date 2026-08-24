## kernel

> `/System/Library/Kernels/kernel`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__brk_desc`
- `__KLDDATA.__const`
- `__KLDDATA.__mod_init_func`
- `__KLDDATA.__mod_term_func`
- `__KLDDATA.__static_ifinit`
- `__HIB.__desc`
- `__VECTORS.__recover`
- `__LASTDATA_CONST.__mod_init_func`
- `__LINKINFO.__symbolsets`

```diff

-11417.121.6.0.0
-  __TEXT.__text: 0x86c8d0
-  __TEXT.__const: 0x42774
-  __TEXT.__cstring: 0x95f9a
-  __TEXT.__os_log: 0x3154b
+11417.140.62.501.1
+  __TEXT.__text: 0x871090
+  __TEXT.__const: 0x42b04
+  __TEXT.__cstring: 0x96655
+  __TEXT.__os_log: 0x3152b
   __TEXT.__eh_frame: 0x118
   __DATA.__llvm_prf_cnts: 0x0
   __DATA.__llvm_prf_data: 0x0

   __DATA.__bss: 0x76950
   __DATA_CONST.__got: 0x70
   __DATA_CONST.__mod_init_func: 0x2c8
-  __DATA_CONST.__const: 0x9c1f0
+  __DATA_CONST.__const: 0x9c340
   __DATA_CONST.__kalloc_var: 0x8250
   __DATA_CONST.__kalloc_type: 0x16a80
   __DATA_CONST.__brk_desc: 0x60
-  __DATA_CONST.__sdt_cstring: 0x6aaa
-  __DATA_CONST.__sdt: 0x11010
-  __DATA_CONST.__assert: 0xf0
-  __KLDDATA.__init: 0x22800
-  __KLDDATA.__init_entry_set: 0x11c28
+  __DATA_CONST.__sdt_cstring: 0x6aed
+  __DATA_CONST.__sdt: 0x11040
+  __DATA_CONST.__assert: 0x208
+  __KLDDATA.__init: 0x22808
+  __KLDDATA.__init_entry_set: 0x11c70
   __KLDDATA.__cstring: 0x79c
   __KLDDATA.__const: 0x88d0
   __KLDDATA.__mod_init_func: 0x8

   __HIB.__desc: 0x8b000
   __HIB.__data: 0x4070
   __HIB.__const: 0x104
-  __HIB.__cstring: 0x134
+  __HIB.__cstring: 0x139
   __HIB.__bss: 0x200
   __HIB.__common: 0x114
   __VECTORS.__recover: 0x150

   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0
   __LINKINFO.__symbolsets: 0x4c4e2
-  __CTF.__ctf: 0xa85ec
+  __CTF.__ctf: 0xa61a8
   Functions: 26272
-  Symbols:   23413
-  CStrings:  23400
+  Symbols:   23408
+  CStrings:  23411
 
Symbols:
+ ___vm_cpu_free_count_early_storage
+ _vm_cpu_free_count
+ _vm_page_free_queue_enter
+ _vm_page_free_queue_grab
+ _vm_page_free_queue_init
+ _vm_page_free_queue_remove
+ _vm_page_free_wakeup
+ _vm_page_grab_options_for_object
- _hibernate_free_range
- _hibernate_hash_insert_page
- _hibernate_lookup_paddr
- _hibernate_mark_as_unneeded
- _hibernate_rebuild_needed
- _hibernate_teardown_vm_structs
- _thread_wakeup_identify
- _thread_wakeup_one_with_pri
- _vm_page_alloc
- _vm_page_get_memory_class
- _vm_page_grab
- _vm_page_put_list_on_free_queue
- _vm_page_steal_free_page
CStrings:
+ "!os_add_overflow(*__counter, 1, __counter)"
+ "!os_sub_overflow(*__counter, 1, __counter)"
+ "!os_sub_overflow(*__counter, list.vmpl_count, __counter)"
+ "/private/var/run"
+ "Existing agent registration UUID conflicts with new agent registration"
+ "ch__drain__na__inactive"
+ "ch__drain__na__invalid"
+ "ch__drain__na__null"
+ "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
+ "com.apple.private.security.nvram.fmm"
+ "extended_idle_timeout"
+ "fmm-computer-name"
+ "fmm-mobileme-token-FMM"
+ "fmm-mobileme-token-FMM-BridgeHasAccount"
+ "kern_close_file_for_direct_io(%p) %qd\n"
+ "netagent_handle_register_inner"
+ "ptmx_get_ioctl failed because minor number %d was out of range\n"
+ "ptmx_get_ioctl failed due to ptmx_max limit %d\n"
+ "pty_get_ioctl failed because minor number %d exceeded %d\n"
+ "pty_get_ioctl: driver->open returned NULL\n"
+ "should not modify CPU free_pages while hibernating @%s:%d"
+ "should not modify cpu->free_pages while hibernating @%s:%d"
+ "v16@?0^{vm_page=(?={vm_page_packed_queue_entry=II}^{vm_page}){vm_page_packed_queue_entry=II}{vm_page_packed_queue_entry=II}IIQ(?=SS){?=b4b2b1b1}{?=b1b1b1b1b1b1b1b1}b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b4b4b4b1b1I}8"
- "%s:%d %u return NULL\n"
- "%s:%d should not modify cpu->free_pages while hibernating @%s:%d"
- "/var/run"
- "/var/run/.vfs_rsrc_streams_%p%x"
- "Unrecognized remove reason %u @%s:%d"
- "bad select_conflict_queue @%s:%d"
- "bad wait queue for waitq_wakeup64_all %p (%sfp:%p) @%s:%d"
- "guarded "
- "kern_close_file_for_direct_io(%p)\n"
- "thread_wakeup_identify"
- "thread_wakeup_one_with_pri"
- "vm_page_grab_options_internal"
```
