## kernel.release.t6031

> `/System/Library/Kernels/kernel.release.t6031`

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
- `__PPLDATA_CONST.__const`
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
-  __TEXT.__const: 0x36310
+11417.120.96.501.2
+  __TEXT.__const: 0x36340
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x9d37f
-  __TEXT.__os_log: 0x2a835
+  __TEXT.__cstring: 0x9d159
+  __TEXT.__os_log: 0x2a801
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__mod_init_func: 0x2d8
-  __DATA_CONST.__const: 0x178f38
+  __DATA_CONST.__const: 0x178f28
   __DATA_CONST.__hib_const: 0x6b8
   __DATA_CONST.__sdt_cstring: 0x6acc
-  __DATA_CONST.__sdt: 0x10fe0
+  __DATA_CONST.__sdt: 0x111c0
   __DATA_CONST.__kalloc_type: 0x169c0
   __DATA_CONST.__kalloc_var: 0x84d0
-  __DATA_CONST.__assert: 0x1e0
+  __DATA_CONST.__assert: 0xf0
   __DATA_CONST.__brk_desc: 0x78
   __TEXT_EXEC.__hib_text: 0x4088
-  __TEXT_EXEC.__text: 0x8ef2d8
+  __TEXT_EXEC.__text: 0x8f6be4
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xafe8
   __PPLTEXT.__text: 0x315c4

   __KLDDATA.__mod_term_func: 0x8
   __KLDDATA.__bss: 0x1
   __DATA.__data: 0x20781
-  __DATA.__lock_grp: 0x161a0
-  __DATA.__percpu: 0x3a90
-  __DATA.__common: 0x7ecb8
-  __DATA.__bss: 0x52460
+  __DATA.__lock_grp: 0x162e8
+  __DATA.__percpu: 0x3ad0
+  __DATA.__common: 0x7ec78
+  __DATA.__bss: 0x524b0
   __HIBDATA.__data: 0x41
   __HIBDATA.__common: 0x120
   __HIBDATA.__bss: 0x660
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__init: 0x5bb38
+  __BOOTDATA.__init: 0x5bb30
   __BOOTDATA.__init_entry_set: 0x11c70
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0

   __PLK_DATA_CONST.__data: 0x0
   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
-  __LINKINFO.__symbolsets: 0x4e13a
-  __CTF.__ctf: 0xe139b
-  Functions: 21893
-  Symbols:   6757
-  CStrings:  23470
+  __LINKINFO.__symbolsets: 0x4e15f
+  __CTF.__ctf: 0xda91c
+  Functions: 21890
+  Symbols:   6758
+  CStrings:  23461
 
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
- "Failed to set up ktriage for VM sanitization. @%s:%d"
- "Invalid relocation reason %u @%s:%d"
- "memorystatus_kill_on_zone_map_exhaustion: failed to allocate jetsam reason\n"
- "should not modify CPU free_pages while hibernating @%s:%d"
- "should not modify cpu->free_pages while hibernating @%s:%d"
- "site.u_int8_t *"
- "thread_group_clear_flags: Invalid flags %u @%s:%d"
- "unknown vmp_q_state %d @%s:%d"
- "v16@?0^{vm_page=(?={vm_page_packed_queue_entry=II}^{vm_page}){vm_page_packed_queue_entry=II}{vm_page_packed_queue_entry=II}IIQ(?=SS){?=b4b2b1b1}{?=b1b1b1b1b1b1b1b1}b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b4b4b4b1b1}8"
- "vm_ecc_error(): in the compressor"
- "vm_sanitize_telemetry.c"
```
