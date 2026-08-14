## kernel.release.vmapple

> `/System/Library/Kernels/kernel.release.vmapple`

### Sections with Same Size but Changed Content

- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__sdt_cstring`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__brk_desc`
- `__LASTDATA_CONST.__mod_init_func`
- `__KLDDATA.__const`
- `__KLDDATA.__mod_init_func`
- `__KLDDATA.__mod_term_func`
- `__DATA.__data`
- `__BOOTDATA.__static_ifinit`

```diff

-11417.120.80.501.1
-  __TEXT.__const: 0x35920
+11417.120.96.501.2
+  __TEXT.__const: 0x35960
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x8c949
-  __TEXT.__os_log: 0x2a4ce
+  __TEXT.__cstring: 0x8c93d
+  __TEXT.__os_log: 0x2a4e6
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__mod_init_func: 0x2d0
-  __DATA_CONST.__const: 0x126558
+  __DATA_CONST.__const: 0x126548
   __DATA_CONST.__hib_const: 0x120
   __DATA_CONST.__sdt_cstring: 0x6a6a
-  __DATA_CONST.__sdt: 0x11118
+  __DATA_CONST.__sdt: 0x110e8
   __DATA_CONST.__kalloc_type: 0x16700
   __DATA_CONST.__kalloc_var: 0x8390
-  __DATA_CONST.__assert: 0x1cc
+  __DATA_CONST.__assert: 0xf0
   __DATA_CONST.__brk_desc: 0x78
   __TEXT_EXEC.__hib_text: 0xde8
-  __TEXT_EXEC.__text: 0x8dcce0
+  __TEXT_EXEC.__text: 0x8e1504
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xb0d8
   __LASTDATA_CONST.__mod_init_func: 0x8

   __DATA.__data: 0x20601
   __DATA.__lock_grp: 0x15760
   __DATA.__percpu: 0x3660
-  __DATA.__common: 0x7e7c8
-  __DATA.__bss: 0x3c010
+  __DATA.__common: 0x7e788
+  __DATA.__bss: 0x3c060
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__init: 0x5b6f8
-  __BOOTDATA.__init_entry_set: 0x11298
+  __BOOTDATA.__init: 0x5b6f0
+  __BOOTDATA.__init_entry_set: 0x11268
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0
   __PRELINK_TEXT.__text: 0x0

   __PLK_DATA_CONST.__data: 0x0
   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
-  __LINKINFO.__symbolsets: 0x4dc8d
-  __CTF.__ctf: 0xd0f40
-  Functions: 20913
-  Symbols:   6735
-  CStrings:  21989
+  __LINKINFO.__symbolsets: 0x4dcb2
+  __CTF.__ctf: 0xd0b8b
+  Functions: 20922
+  Symbols:   6736
+  CStrings:  21988
 
Symbols:
+ _ml_io_read_cpu_reg
CStrings:
+ "%s: inpcb socket so_usecount underflow  when removing timer entry\n"
+ "necp_get_tlv_at_offset buffer is NULL"
+ "site.u_int8_t * __attribute__((__indexable__))"
+ "tcp_remove_timer"
- "!os_add_overflow(*__counter, 1, __counter)"
- "!os_sub_overflow(*__counter, 1, __counter)"
- "!os_sub_overflow(*__counter, list.vmpl_count, __counter)"
- "81112"
- "site.u_int8_t *"
```
