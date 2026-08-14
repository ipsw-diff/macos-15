## kernel.release.t8122

> `/System/Library/Kernels/kernel.release.t8122`

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
-  __TEXT.__const: 0x362d0
+11417.120.96.501.2
+  __TEXT.__const: 0x36310
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x9b849
-  __TEXT.__os_log: 0x2a7db
+  __TEXT.__cstring: 0x9b687
+  __TEXT.__os_log: 0x2a7a7
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__mod_init_func: 0x2d8
-  __DATA_CONST.__const: 0x178040
+  __DATA_CONST.__const: 0x178030
   __DATA_CONST.__hib_const: 0x6b8
   __DATA_CONST.__sdt_cstring: 0x6acc
-  __DATA_CONST.__sdt: 0x11010
+  __DATA_CONST.__sdt: 0x111f0
   __DATA_CONST.__kalloc_type: 0x16940
   __DATA_CONST.__kalloc_var: 0x82f0
-  __DATA_CONST.__assert: 0x1cc
+  __DATA_CONST.__assert: 0xf0
   __DATA_CONST.__brk_desc: 0x78
   __TEXT_EXEC.__hib_text: 0x3fc0
-  __TEXT_EXEC.__text: 0x8eacb8
+  __TEXT_EXEC.__text: 0x8f2478
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xafe8
   __PPLTEXT.__text: 0x2d6a4

   __KLDDATA.__mod_term_func: 0x8
   __KLDDATA.__bss: 0x1
   __DATA.__data: 0x20781
-  __DATA.__lock_grp: 0x16058
-  __DATA.__percpu: 0x3a90
+  __DATA.__lock_grp: 0x161a0
+  __DATA.__percpu: 0x3ad0
   __DATA.__common: 0x7e8f8
-  __DATA.__bss: 0x45ae0
+  __DATA.__bss: 0x45b30
   __HIBDATA.__data: 0x31
   __HIBDATA.__common: 0x120
   __HIBDATA.__bss: 0x660
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__init: 0x5bac8
+  __BOOTDATA.__init: 0x5bac0
   __BOOTDATA.__init_entry_set: 0x11aa8
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0

   __PLK_DATA_CONST.__data: 0x0
   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
-  __LINKINFO.__symbolsets: 0x4e13a
-  __CTF.__ctf: 0xdcb5a
-  Functions: 21824
-  Symbols:   6757
-  CStrings:  23326
+  __LINKINFO.__symbolsets: 0x4e15f
+  __CTF.__ctf: 0xd8741
+  Functions: 21822
+  Symbols:   6758
+  CStrings:  23320
 
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
- "memorystatus_kill_on_zone_map_exhaustion: failed to allocate jetsam reason\n"
- "should not modify CPU free_pages while hibernating @%s:%d"
- "should not modify cpu->free_pages while hibernating @%s:%d"
- "site.u_int8_t *"
- "thread_group_clear_flags: Invalid flags %u @%s:%d"
- "v16@?0^{vm_page=(?={vm_page_packed_queue_entry=II}^{vm_page}){vm_page_packed_queue_entry=II}{vm_page_packed_queue_entry=II}IIQ(?=SS){?=b4b2b1b1}{?=b1b1b1b1b1b1b1b1}b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b4b4b4b1b1}8"
- "vm_sanitize_telemetry.c"
```
