## kernel.release.vmapple

> `/System/Library/Kernels/kernel.release.vmapple`

### Sections with Same Size but Changed Content

- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__KLDDATA.__const`
- `__KLDDATA.__mod_init_func`
- `__KLDDATA.__mod_term_func`
- `__BOOTDATA.__static_ifinit`

```diff

-11417.121.6.0.0
-  __TEXT.__const: 0x35950
+11417.140.62.501.1
+  __TEXT.__const: 0x35cb0
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x8c957
-  __TEXT.__os_log: 0x2a50c
+  __TEXT.__cstring: 0x8cf59
+  __TEXT.__os_log: 0x2a4fe
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__mod_init_func: 0x2d0
-  __DATA_CONST.__const: 0x126688
+  __DATA_CONST.__const: 0x126798
   __DATA_CONST.__hib_const: 0x120
-  __DATA_CONST.__sdt_cstring: 0x6a6a
-  __DATA_CONST.__sdt: 0x11118
+  __DATA_CONST.__sdt_cstring: 0x6aad
+  __DATA_CONST.__sdt: 0x11148
   __DATA_CONST.__kalloc_type: 0x16700
   __DATA_CONST.__kalloc_var: 0x8390
-  __DATA_CONST.__assert: 0xf0
-  __DATA_CONST.__brk_desc: 0x60
+  __DATA_CONST.__assert: 0x1cc
+  __DATA_CONST.__brk_desc: 0x78
   __TEXT_EXEC.__hib_text: 0xde8
-  __TEXT_EXEC.__text: 0x8e13b8
+  __TEXT_EXEC.__text: 0x8ea638
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xb0d8
   __LASTDATA_CONST.__mod_init_func: 0x8

   __KLDDATA.__mod_init_func: 0x8
   __KLDDATA.__mod_term_func: 0x8
   __KLDDATA.__bss: 0x1
-  __DATA.__data: 0x20601
+  __DATA.__data: 0x20641
   __DATA.__lock_grp: 0x15760
   __DATA.__percpu: 0x3660
-  __DATA.__common: 0x7e7a8
+  __DATA.__common: 0x7e7e8
   __DATA.__bss: 0x3c060
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__init: 0x5b6e8
-  __BOOTDATA.__init_entry_set: 0x112c8
+  __BOOTDATA.__init: 0x5b6f0
+  __BOOTDATA.__init_entry_set: 0x11310
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0
   __PRELINK_TEXT.__text: 0x0

   __PLK_DATA_CONST.__data: 0x0
   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
-  __LINKINFO.__symbolsets: 0x4dcb2
-  __CTF.__ctf: 0xce4aa
-  Functions: 20919
-  Symbols:   6736
-  CStrings:  21991
+  __LINKINFO.__symbolsets: 0x4dd00
+  __CTF.__ctf: 0xc99b3
+  Functions: 20932
+  Symbols:   6738
+  CStrings:  22004
 
Symbols:
+ _apt_allocate_va_buffer
+ _apt_free_va_buffer
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
- "%s:%d %u return NULL\n"
- "/var/run"
- "/var/run/.vfs_rsrc_streams_%p%x"
- "bad select_conflict_queue @%s:%d"
- "bad wait queue for waitq_wakeup64_all %p (%sfp:%p) @%s:%d"
- "guarded "
- "kern_close_file_for_direct_io(%p)\n"
```
