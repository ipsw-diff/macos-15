## kernel.release.t6041

> `/System/Library/Kernels/kernel.release.t6041`

### Sections with Same Size but Changed Content

- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__hib_const`
- `__DATA_CONST.__sdt_cstring`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__brk_desc`
- `__LASTDATA_CONST.__mod_init_func`
- `__KLDDATA.__const`
- `__KLDDATA.__mod_init_func`
- `__KLDDATA.__mod_term_func`
- `__DATA.__data`
- `__HIBDATA.__data`
- `__BOOTDATA.__init_entry_set`
- `__BOOTDATA.__static_ifinit`

```diff

-11417.120.80.501.1
-  __TEXT.__const: 0x35ba0
+11417.120.96.501.2
+  __TEXT.__const: 0x35bd0
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x943b0
-  __TEXT.__os_log: 0x2a80f
+  __TEXT.__cstring: 0x941d7
+  __TEXT.__os_log: 0x2a7db
   __TEXT.__eh_frame: 0x610
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__mod_init_func: 0x2d8
-  __DATA_CONST.__const: 0x124758
+  __DATA_CONST.__const: 0x124748
   __DATA_CONST.__hib_const: 0x308
   __DATA_CONST.__sdt_cstring: 0x6acc
-  __DATA_CONST.__sdt: 0x10f68
+  __DATA_CONST.__sdt: 0x11148
   __DATA_CONST.__kalloc_type: 0x169c0
   __DATA_CONST.__kalloc_var: 0x8430
-  __DATA_CONST.__assert: 0x1e0
+  __DATA_CONST.__assert: 0xf0
   __DATA_CONST.__brk_desc: 0x78
   __DATA_SPTM.__const: 0x54000
   __TEXT_EXEC.__hib_text: 0x1720
-  __TEXT_EXEC.__text: 0x8fcc78
+  __TEXT_EXEC.__text: 0x9023d8
   __TEXT_EXEC.__commpage_text: 0x2dc
   __TEXT_BOOT_EXEC.__bootcode: 0x514c
   __KLD.__text: 0xafe8

   __KLDDATA.__mod_term_func: 0x8
   __KLDDATA.__bss: 0x1
   __DATA.__data: 0x20909
-  __DATA.__lock_grp: 0x16578
+  __DATA.__lock_grp: 0x166c0
   __DATA.__percpu: 0x6410
-  __DATA.__common: 0x7f018
-  __DATA.__bss: 0x46d90
+  __DATA.__common: 0x7efd8
+  __DATA.__bss: 0x46be0
   __HIBDATA.__data: 0x31
   __HIBDATA.__bss: 0x660
   __HIBDATA.__common: 0x108
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__init: 0x5bb88
+  __BOOTDATA.__init: 0x5bb80
   __BOOTDATA.__init_entry_set: 0x11b08
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0

   __PLK_DATA_CONST.__data: 0x0
   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
-  __LINKINFO.__symbolsets: 0x4e13a
-  __CTF.__ctf: 0xe2f0d
-  Functions: 21552
-  Symbols:   6757
-  CStrings:  22824
+  __LINKINFO.__symbolsets: 0x4e15f
+  __CTF.__ctf: 0xdec09
+  Functions: 21546
+  Symbols:   6758
+  CStrings:  22817
 
Symbols:
+ _ml_io_read_cpu_reg
CStrings:
+ "%s: inpcb socket so_usecount underflow  when removing timer entry\n"
+ "%s:%d should not modify cpu->free_pages while hibernating @%s:%d"
+ "necp_get_tlv_at_offset buffer is NULL"
+ "site.u_int8_t * __attribute__((__indexable__))"
+ "tcp_remove_timer"
+ "vm_page_grab_options_internal"
- "!os_add_overflow(*__counter, 1, __counter)"
- "!os_sub_overflow(*__counter, 1, __counter)"
- "!os_sub_overflow(*__counter, list.vmpl_count, __counter)"
- "81112"
- "Invalid relocation reason %u @%s:%d"
- "memorystatus_kill_on_zone_map_exhaustion: failed to allocate jetsam reason\n"
- "should not modify CPU free_pages while hibernating @%s:%d"
- "should not modify cpu->free_pages while hibernating @%s:%d"
- "site.u_int8_t *"
- "thread_group_clear_flags: Invalid flags %u @%s:%d"
- "unknown vmp_q_state %d @%s:%d"
- "v16@?0^{vm_page=(?={vm_page_packed_queue_entry=II}^{vm_page}){vm_page_packed_queue_entry=II}{vm_page_packed_queue_entry=II}IIQ(?=SS){?=b4b2b1b1}{?=b1b1b1b1b1b1b1b1}b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b4b4b4b1b1}8"
- "vm_ecc_error(): in the compressor"
```
