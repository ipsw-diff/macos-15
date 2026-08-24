## kernel.release.t6020

> `/System/Library/Kernels/kernel.release.t6020`

### Sections with Same Size but Changed Content

- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__hib_const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__PPLDATA_CONST.__const`
- `__LASTDATA_CONST.__mod_init_func`
- `__KLDDATA.__const`
- `__KLDDATA.__mod_init_func`
- `__KLDDATA.__mod_term_func`
- `__DATA.__data`
- `__HIBDATA.__data`
- `__BOOTDATA.__static_ifinit`

```diff

-11417.121.6.0.0
-  __TEXT.__const: 0x36350
+11417.140.62.501.1
+  __TEXT.__const: 0x366d0
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x9d18f
-  __TEXT.__os_log: 0x2a827
+  __TEXT.__cstring: 0x9d9ab
+  __TEXT.__os_log: 0x2a865
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__mod_init_func: 0x2d8
-  __DATA_CONST.__const: 0x178c78
+  __DATA_CONST.__const: 0x178d88
   __DATA_CONST.__hib_const: 0x6b8
-  __DATA_CONST.__sdt_cstring: 0x6acc
-  __DATA_CONST.__sdt: 0x111f0
+  __DATA_CONST.__sdt_cstring: 0x6b0f
+  __DATA_CONST.__sdt: 0x11010
   __DATA_CONST.__kalloc_type: 0x169c0
   __DATA_CONST.__kalloc_var: 0x84d0
-  __DATA_CONST.__assert: 0xf0
-  __DATA_CONST.__brk_desc: 0x60
+  __DATA_CONST.__assert: 0x1e0
+  __DATA_CONST.__brk_desc: 0x78
   __TEXT_EXEC.__hib_text: 0x4048
-  __TEXT_EXEC.__text: 0x8f579c
+  __TEXT_EXEC.__text: 0x8fb85c
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xafe8
   __PPLTEXT.__text: 0x315e4

   __DATA.__data: 0x20781
   __DATA.__lock_grp: 0x161a0
   __DATA.__percpu: 0x3a80
-  __DATA.__common: 0x7ec18
+  __DATA.__common: 0x7ec78
   __DATA.__bss: 0x522b0
   __HIBDATA.__data: 0x41
   __HIBDATA.__common: 0x120
   __HIBDATA.__bss: 0x660
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__init: 0x5bb28
-  __BOOTDATA.__init_entry_set: 0x11c88
+  __BOOTDATA.__init: 0x5bb30
+  __BOOTDATA.__init_entry_set: 0x11cd0
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0
   __PRELINK_TEXT.__text: 0x0

   __PLK_DATA_CONST.__data: 0x0
   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
-  __LINKINFO.__symbolsets: 0x4e15f
-  __CTF.__ctf: 0xd7ae9
-  Functions: 21889
-  Symbols:   6758
-  CStrings:  23463
+  __LINKINFO.__symbolsets: 0x4e1ad
+  __CTF.__ctf: 0xd7fca
+  Functions: 21916
+  Symbols:   6760
+  CStrings:  23484
 
Symbols:
+ _apt_allocate_va_buffer
+ _apt_free_va_buffer
CStrings:
+ "!os_add_overflow(*__counter, 1, __counter)"
+ "!os_sub_overflow(*__counter, 1, __counter)"
+ "!os_sub_overflow(*__counter, list.vmpl_count, __counter)"
+ "/private/var/run"
+ "Existing agent registration UUID conflicts with new agent registration"
+ "Failed to set up ktriage for VM sanitization. @%s:%d"
+ "Invalid relocation reason %u @%s:%d"
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
+ "memorystatus_kill_on_zone_map_exhaustion: failed to allocate jetsam reason\n"
+ "netagent_handle_register_inner"
+ "ptmx_get_ioctl failed because minor number %d was out of range\n"
+ "ptmx_get_ioctl failed due to ptmx_max limit %d\n"
+ "pty_get_ioctl failed because minor number %d exceeded %d\n"
+ "pty_get_ioctl: driver->open returned NULL\n"
+ "should not modify CPU free_pages while hibernating @%s:%d"
+ "should not modify cpu->free_pages while hibernating @%s:%d"
+ "thread_group_clear_flags: Invalid flags %u @%s:%d"
+ "unknown vmp_q_state %d @%s:%d"
+ "v16@?0^{vm_page=(?={vm_page_packed_queue_entry=II}^{vm_page}){vm_page_packed_queue_entry=II}{vm_page_packed_queue_entry=II}IIQ(?=SS){?=b4b2b1b1}{?=b1b1b1b1b1b1b1b1}b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b4b4b4b1b1}8"
+ "vm_ecc_error(): in the compressor"
+ "vm_sanitize_telemetry.c"
- "%s:%d %u return NULL\n"
- "%s:%d should not modify cpu->free_pages while hibernating @%s:%d"
- "/var/run"
- "/var/run/.vfs_rsrc_streams_%p%x"
- "bad select_conflict_queue @%s:%d"
- "bad wait queue for waitq_wakeup64_all %p (%sfp:%p) @%s:%d"
- "guarded "
- "kern_close_file_for_direct_io(%p)\n"
- "vm_page_grab_options_internal"
```
