## kernel.release.t8132

> `/System/Library/Kernels/kernel.release.t8132`

### Sections with Same Size but Changed Content

- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__hib_const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__brk_desc`
- `__KLDDATA.__const`
- `__DATA.__data`

```diff

-11417.120.96.501.2
-  __TEXT.__const: 0x35bd0
+11417.120.105.501.1
+  __TEXT.__const: 0x35bf0
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x938d9
-  __TEXT.__os_log: 0x2a7a7
+  __TEXT.__cstring: 0x93934
+  __TEXT.__os_log: 0x2a7cd
   __TEXT.__eh_frame: 0x610
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__mod_init_func: 0x2d8
-  __DATA_CONST.__const: 0x1241f0
+  __DATA_CONST.__const: 0x124330
   __DATA_CONST.__hib_const: 0x308
   __DATA_CONST.__sdt_cstring: 0x6acc
   __DATA_CONST.__sdt: 0x11178

   __DATA_CONST.__brk_desc: 0x78
   __DATA_SPTM.__const: 0x54000
   __TEXT_EXEC.__hib_text: 0x1720
-  __TEXT_EXEC.__text: 0x8fe1f0
+  __TEXT_EXEC.__text: 0x8fe67c
   __TEXT_EXEC.__commpage_text: 0x2dc
   __TEXT_BOOT_EXEC.__bootcode: 0x514c
   __KLD.__text: 0xafe8

   __KLDDATA.__bss: 0x1
   __DATA.__data: 0x20909
   __DATA.__lock_grp: 0x166c0
-  __DATA.__percpu: 0x6e80
-  __DATA.__common: 0x7edd8
+  __DATA.__percpu: 0x6e90
+  __DATA.__common: 0x7ee38
   __DATA.__bss: 0x46a90
   __HIBDATA.__data: 0x31
   __HIBDATA.__bss: 0x660
   __HIBDATA.__common: 0x108
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__init: 0x5bb10
-  __BOOTDATA.__init_entry_set: 0x119b8
+  __BOOTDATA.__init: 0x5bb08
+  __BOOTDATA.__init_entry_set: 0x11a18
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0
   __PRELINK_TEXT.__text: 0x0

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4e15f
-  __CTF.__ctf: 0xdf9d1
+  __CTF.__ctf: 0xe1c3a
   Functions: 21514
   Symbols:   6758
-  CStrings:  22750
+  CStrings:  22754
 
CStrings:
+ "%s: %s TX gso size %d mss %d nsegs %d"
+ "object_pageout_active_local"
+ "object_pageout_not_on_queue"
+ "object_pageout_not_pageable"
+ "object_pageout_pageable"
- "kmem_iokit_range"
```
