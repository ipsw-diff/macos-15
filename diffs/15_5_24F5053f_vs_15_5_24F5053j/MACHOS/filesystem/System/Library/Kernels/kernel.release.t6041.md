## kernel.release.t6041

> `/System/Library/Kernels/kernel.release.t6041`

### Sections with Same Size but Changed Content

- `__TEXT.__copyio_vectors`
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
-  __TEXT.__cstring: 0x941d7
-  __TEXT.__os_log: 0x2a7db
+  __TEXT.__cstring: 0x94232
+  __TEXT.__os_log: 0x2a801
   __TEXT.__eh_frame: 0x610
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__mod_init_func: 0x2d8
-  __DATA_CONST.__const: 0x124748
+  __DATA_CONST.__const: 0x124888
   __DATA_CONST.__hib_const: 0x308
   __DATA_CONST.__sdt_cstring: 0x6acc
   __DATA_CONST.__sdt: 0x11148

   __DATA_CONST.__brk_desc: 0x78
   __DATA_SPTM.__const: 0x54000
   __TEXT_EXEC.__hib_text: 0x1720
-  __TEXT_EXEC.__text: 0x9023d8
+  __TEXT_EXEC.__text: 0x9027e4
   __TEXT_EXEC.__commpage_text: 0x2dc
   __TEXT_BOOT_EXEC.__bootcode: 0x514c
   __KLD.__text: 0xafe8

   __DATA.__data: 0x20909
   __DATA.__lock_grp: 0x166c0
   __DATA.__percpu: 0x6410
-  __DATA.__common: 0x7efd8
+  __DATA.__common: 0x7eff8
   __DATA.__bss: 0x46be0
   __HIBDATA.__data: 0x31
   __HIBDATA.__bss: 0x660
   __HIBDATA.__common: 0x108
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__init: 0x5bb80
-  __BOOTDATA.__init_entry_set: 0x11b08
+  __BOOTDATA.__init: 0x5bb78
+  __BOOTDATA.__init_entry_set: 0x11b68
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0
   __PRELINK_TEXT.__text: 0x0

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4e15f
-  __CTF.__ctf: 0xdec09
+  __CTF.__ctf: 0xe1d89
   Functions: 21546
   Symbols:   6758
-  CStrings:  22817
+  CStrings:  22821
 
CStrings:
+ "%s: %s TX gso size %d mss %d nsegs %d"
+ "object_pageout_active_local"
+ "object_pageout_not_on_queue"
+ "object_pageout_not_pageable"
+ "object_pageout_pageable"
- "kmem_iokit_range"
```
