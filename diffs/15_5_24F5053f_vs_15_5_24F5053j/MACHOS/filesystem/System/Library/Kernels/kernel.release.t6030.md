## kernel.release.t6030

> `/System/Library/Kernels/kernel.release.t6030`

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
- `__PPLDATA_CONST.__const`
- `__LASTDATA_CONST.__mod_init_func`
- `__KLDDATA.__const`
- `__DATA.__data`
- `__BOOTDATA.__static_ifinit`

```diff

-11417.120.96.501.2
-  __TEXT.__const: 0x36310
+11417.120.105.501.1
+  __TEXT.__const: 0x36320
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x9b672
-  __TEXT.__os_log: 0x2a7a7
+  __TEXT.__cstring: 0x9b6cd
+  __TEXT.__os_log: 0x2a7cd
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__mod_init_func: 0x2d8
-  __DATA_CONST.__const: 0x178210
+  __DATA_CONST.__const: 0x178350
   __DATA_CONST.__hib_const: 0x6b8
   __DATA_CONST.__sdt_cstring: 0x6acc
   __DATA_CONST.__sdt: 0x111f0

   __DATA_CONST.__assert: 0xf0
   __DATA_CONST.__brk_desc: 0x78
   __TEXT_EXEC.__hib_text: 0x3fe0
-  __TEXT_EXEC.__text: 0x8f2408
+  __TEXT_EXEC.__text: 0x8f27f8
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xafe8
   __PPLTEXT.__text: 0x2d6b0

   __KLDDATA.__bss: 0x1
   __DATA.__data: 0x20781
   __DATA.__lock_grp: 0x161a0
-  __DATA.__percpu: 0x3ad0
-  __DATA.__common: 0x7e938
+  __DATA.__percpu: 0x3ae0
+  __DATA.__common: 0x7e958
   __DATA.__bss: 0x45b30
   __HIBDATA.__data: 0x31
   __HIBDATA.__common: 0x120
   __HIBDATA.__bss: 0x660
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__init: 0x5bac0
-  __BOOTDATA.__init_entry_set: 0x11aa8
+  __BOOTDATA.__init: 0x5bab8
+  __BOOTDATA.__init_entry_set: 0x11b08
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0
   __PRELINK_TEXT.__text: 0x0

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4e15f
-  __CTF.__ctf: 0xd7359
+  __CTF.__ctf: 0xd8fc1
   Functions: 21822
   Symbols:   6758
-  CStrings:  23319
+  CStrings:  23323
 
CStrings:
+ "%s: %s TX gso size %d mss %d nsegs %d"
+ "object_pageout_active_local"
+ "object_pageout_not_on_queue"
+ "object_pageout_not_pageable"
+ "object_pageout_pageable"
- "kmem_iokit_range"
```
