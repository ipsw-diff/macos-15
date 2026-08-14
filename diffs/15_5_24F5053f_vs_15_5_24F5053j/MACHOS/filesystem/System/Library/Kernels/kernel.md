## kernel

> `/System/Library/Kernels/kernel`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__brk_desc`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__assert`
- `__KLDDATA.__init`
- `__KLDDATA.__const`
- `__KLDDATA.__static_ifinit`

```diff

-11417.120.96.501.2
-  __TEXT.__text: 0x86c510
+11417.120.105.501.1
+  __TEXT.__text: 0x86c9c0
   __TEXT.__const: 0x42794
-  __TEXT.__cstring: 0x95f4a
-  __TEXT.__os_log: 0x3151b
+  __TEXT.__cstring: 0x95fba
+  __TEXT.__os_log: 0x3154b
   __TEXT.__eh_frame: 0x118
   __DATA.__llvm_prf_cnts: 0x0
   __DATA.__llvm_prf_data: 0x0

   __DATA.__llvm_prf_vns: 0x0
   __DATA.__llvm_prf_vtab: 0x0
   __DATA.__llvm_orderfile: 0x0
-  __DATA.__common: 0x1926d0
+  __DATA.__common: 0x1926f0
   __DATA.__bss: 0x76950
   __DATA_CONST.__got: 0x70
   __DATA_CONST.__mod_init_func: 0x2c8
-  __DATA_CONST.__const: 0x9c0b0
+  __DATA_CONST.__const: 0x9c1f0
   __DATA_CONST.__kalloc_var: 0x8250
   __DATA_CONST.__kalloc_type: 0x16a80
   __DATA_CONST.__brk_desc: 0x60

   __DATA_CONST.__sdt: 0x10fe0
   __DATA_CONST.__assert: 0xf0
   __KLDDATA.__init: 0x22800
-  __KLDDATA.__init_entry_set: 0x11bc8
+  __KLDDATA.__init_entry_set: 0x11c28
   __KLDDATA.__cstring: 0x79c
   __KLDDATA.__const: 0x88d0
   __KLDDATA.__mod_init_func: 0x8

   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0
   __LINKINFO.__symbolsets: 0x4c4e2
-  __CTF.__ctf: 0xa80a1
-  Functions: 26266
-  Symbols:   23403
-  CStrings:  23394
+  __CTF.__ctf: 0xa69c9
+  Functions: 26271
+  Symbols:   23412
+  CStrings:  23399
 
Symbols:
+ _lookup_check_for_resolve_prefix
+ _mach_vm_update_pointers_with_remote_tags
+ _vm_map_assign_serial
+ _vm_map_maybe_serial_id
+ _vm_map_serial_generate
+ _vm_object_pageout_active_local
+ _vm_object_pageout_not_on_queue
+ _vm_object_pageout_not_pageable
+ _vm_object_pageout_pageable
CStrings:
+ "%s: %s TX gso size %d mss %d nsegs %d"
+ "object_pageout_active_local"
+ "object_pageout_not_on_queue"
+ "object_pageout_not_pageable"
+ "object_pageout_pageable"
```
