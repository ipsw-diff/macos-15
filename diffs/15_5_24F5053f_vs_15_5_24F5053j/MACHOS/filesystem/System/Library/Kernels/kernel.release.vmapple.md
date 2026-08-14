## kernel.release.vmapple

> `/System/Library/Kernels/kernel.release.vmapple`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__copyio_vectors`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__brk_desc`
- `__KLDDATA.__const`
- `__DATA.__data`
- `__BOOTDATA.__static_ifinit`

```diff

-11417.120.96.501.2
+11417.120.105.501.1
   __TEXT.__const: 0x35960
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x8c93d
-  __TEXT.__os_log: 0x2a4e6
+  __TEXT.__cstring: 0x8c998
+  __TEXT.__os_log: 0x2a50c
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__mod_init_func: 0x2d0
-  __DATA_CONST.__const: 0x126548
+  __DATA_CONST.__const: 0x126688
   __DATA_CONST.__hib_const: 0x120
   __DATA_CONST.__sdt_cstring: 0x6a6a
   __DATA_CONST.__sdt: 0x110e8

   __DATA_CONST.__assert: 0xf0
   __DATA_CONST.__brk_desc: 0x78
   __TEXT_EXEC.__hib_text: 0xde8
-  __TEXT_EXEC.__text: 0x8e1504
+  __TEXT_EXEC.__text: 0x8e18b0
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xb0d8
   __LASTDATA_CONST.__mod_init_func: 0x8

   __DATA.__data: 0x20601
   __DATA.__lock_grp: 0x15760
   __DATA.__percpu: 0x3660
-  __DATA.__common: 0x7e788
+  __DATA.__common: 0x7e7a8
   __DATA.__bss: 0x3c060
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__init: 0x5b6f0
-  __BOOTDATA.__init_entry_set: 0x11268
+  __BOOTDATA.__init: 0x5b6e8
+  __BOOTDATA.__init_entry_set: 0x112c8
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0
   __PRELINK_TEXT.__text: 0x0

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4dcb2
-  __CTF.__ctf: 0xd0b8b
+  __CTF.__ctf: 0xd1028
   Functions: 20922
   Symbols:   6736
-  CStrings:  21988
+  CStrings:  21992
 
CStrings:
+ "%s: %s TX gso size %d mss %d nsegs %d"
+ "object_pageout_active_local"
+ "object_pageout_not_on_queue"
+ "object_pageout_not_pageable"
+ "object_pageout_pageable"
- "kmem_iokit_range"
```
