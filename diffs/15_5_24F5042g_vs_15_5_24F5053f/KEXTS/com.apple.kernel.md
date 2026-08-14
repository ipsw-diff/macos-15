## com.apple.kernel

> `com.apple.kernel`

```diff

-11417.120.80.501.1
-  __TEXT.__const: 0x362f0
+11417.120.96.501.2
+  __TEXT.__const: 0x36330
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x98f96
-  __TEXT.__os_log: 0x2a7b5
+  __TEXT.__cstring: 0x98dd4
+  __TEXT.__os_log: 0x2a781
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__mod_init_func: 0x2d8
-  __DATA_CONST.__const: 0x177e38
+  __DATA_CONST.__const: 0x177e28
   __DATA_CONST.__hib_const: 0x6b8
   __DATA_CONST.__sdt_cstring: 0x6acc
-  __DATA_CONST.__sdt: 0x11010
+  __DATA_CONST.__sdt: 0x111d8
   __DATA_CONST.__kalloc_type: 0x16940
   __DATA_CONST.__kalloc_var: 0x82f0
-  __DATA_CONST.__assert: 0x1cc
+  __DATA_CONST.__assert: 0xf0
   __DATA_CONST.__brk_desc: 0x78
   __TEXT_EXEC.__hib_text: 0x3f88
-  __TEXT_EXEC.__text: 0x904790
+  __TEXT_EXEC.__text: 0x90bc1c
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xb0d8
   __PPLTEXT.__text: 0x2bc88

   __DATA.__lock_grp: 0x15dc8
   __DATA.__percpu: 0x3a50
   __DATA.__common: 0x7e868
-  __DATA.__bss: 0x399a8
+  __DATA.__bss: 0x399f8
   __HIBDATA.__data: 0x31
   __HIBDATA.__common: 0x120
   __HIBDATA.__bss: 0x660
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__init: 0x5ba60
-  __BOOTDATA.__init_entry_set: 0x119e8
+  __BOOTDATA.__init: 0x5ba58
+  __BOOTDATA.__init_entry_set: 0x119b8
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0
   __PRELINK_TEXT.__text: 0x0

   __PLK_DATA_CONST.__data: 0x0
   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
-  __LINKINFO.__symbolsets: 0x4e13a
+  __LINKINFO.__symbolsets: 0x4e15f
   __CTF.__ctf: 0x0
-  Functions: 21777
-  Symbols:   6757
-  CStrings:  23103
+  Functions: 21776
+  Symbols:   6758
+  CStrings:  23097
 
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
