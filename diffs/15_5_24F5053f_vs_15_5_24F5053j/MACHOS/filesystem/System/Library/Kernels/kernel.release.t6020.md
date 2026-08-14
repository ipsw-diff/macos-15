## kernel.release.t6020

> `/System/Library/Kernels/kernel.release.t6020`

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
- `__PPLDATA_CONST.__const`
- `__LASTDATA_CONST.__mod_init_func`
- `__KLDDATA.__const`
- `__DATA.__data`
- `__BOOTDATA.__static_ifinit`

```diff

-11417.120.96.501.2
-  __TEXT.__const: 0x36340
+11417.120.105.501.1
+  __TEXT.__const: 0x36360
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x9d175
-  __TEXT.__os_log: 0x2a801
+  __TEXT.__cstring: 0x9d1d0
+  __TEXT.__os_log: 0x2a827
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__mod_init_func: 0x2d8
-  __DATA_CONST.__const: 0x178b38
+  __DATA_CONST.__const: 0x178c78
   __DATA_CONST.__hib_const: 0x6b8
   __DATA_CONST.__sdt_cstring: 0x6acc
   __DATA_CONST.__sdt: 0x111c0

   __DATA_CONST.__assert: 0xf0
   __DATA_CONST.__brk_desc: 0x78
   __TEXT_EXEC.__hib_text: 0x4048
-  __TEXT_EXEC.__text: 0x8f5924
+  __TEXT_EXEC.__text: 0x8f5ca4
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xafe8
   __PPLTEXT.__text: 0x315e4

   __KLDDATA.__bss: 0x1
   __DATA.__data: 0x20781
   __DATA.__lock_grp: 0x161a0
-  __DATA.__percpu: 0x3a70
-  __DATA.__common: 0x7ebf8
+  __DATA.__percpu: 0x3a80
+  __DATA.__common: 0x7ec18
   __DATA.__bss: 0x522b0
   __HIBDATA.__data: 0x41
   __HIBDATA.__common: 0x120
   __HIBDATA.__bss: 0x660
   __BOOTDATA.__data: 0x18000
-  __BOOTDATA.__init: 0x5bb30
-  __BOOTDATA.__init_entry_set: 0x11c28
+  __BOOTDATA.__init: 0x5bb28
+  __BOOTDATA.__init_entry_set: 0x11c88
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0
   __PRELINK_TEXT.__text: 0x0

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4e15f
-  __CTF.__ctf: 0xd923f
+  __CTF.__ctf: 0xd90a9
   Functions: 21892
   Symbols:   6758
-  CStrings:  23460
+  CStrings:  23464
 
CStrings:
+ "%s: %s TX gso size %d mss %d nsegs %d"
+ "object_pageout_active_local"
+ "object_pageout_not_on_queue"
+ "object_pageout_not_pageable"
+ "object_pageout_pageable"
- "kmem_iokit_range"
```
