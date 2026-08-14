## kernel

> `/System/Library/Kernels/kernel`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__brk_desc`
- `__DATA_CONST.__sdt`
- `__KLDDATA.__const`
- `__KLDDATA.__static_ifinit`
- `__HIB.__desc`
- `__VECTORS.__recover`
- `__LASTDATA_CONST.__mod_init_func`

```diff

-11417.120.80.501.1
-  __TEXT.__text: 0x86c060
-  __TEXT.__const: 0x42764
-  __TEXT.__cstring: 0x9605a
-  __TEXT.__os_log: 0x3150b
+11417.120.96.501.2
+  __TEXT.__text: 0x86c510
+  __TEXT.__const: 0x42794
+  __TEXT.__cstring: 0x95f4a
+  __TEXT.__os_log: 0x3151b
   __TEXT.__eh_frame: 0x118
   __DATA.__llvm_prf_cnts: 0x0
   __DATA.__llvm_prf_data: 0x0

   __DATA.__bss: 0x76950
   __DATA_CONST.__got: 0x70
   __DATA_CONST.__mod_init_func: 0x2c8
-  __DATA_CONST.__const: 0x9c0f0
+  __DATA_CONST.__const: 0x9c0b0
   __DATA_CONST.__kalloc_var: 0x8250
   __DATA_CONST.__kalloc_type: 0x16a80
   __DATA_CONST.__brk_desc: 0x60
   __DATA_CONST.__sdt_cstring: 0x6aaa
   __DATA_CONST.__sdt: 0x10fe0
-  __DATA_CONST.__assert: 0x208
-  __KLDDATA.__init: 0x22808
-  __KLDDATA.__init_entry_set: 0x11bf8
+  __DATA_CONST.__assert: 0xf0
+  __KLDDATA.__init: 0x22800
+  __KLDDATA.__init_entry_set: 0x11bc8
   __KLDDATA.__cstring: 0x79c
   __KLDDATA.__const: 0x88d0
   __KLDDATA.__mod_init_func: 0x8

   __LAST.__last: 0x0
   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0
-  __LINKINFO.__symbolsets: 0x4c4bd
-  __CTF.__ctf: 0xa7641
-  Functions: 26267
-  Symbols:   23399
-  CStrings:  23395
+  __LINKINFO.__symbolsets: 0x4c4e2
+  __CTF.__ctf: 0xa80a1
+  Functions: 26266
+  Symbols:   23403
+  CStrings:  23394
 
Symbols:
+ _hibernate_free_range
+ _hibernate_hash_insert_page
+ _hibernate_lookup_paddr
+ _hibernate_mark_as_unneeded
+ _hibernate_rebuild_needed
+ _hibernate_teardown_vm_structs
+ _ml_io_read_cpu_reg
+ _vm_page_get_memory_class
+ _vm_page_grab
+ _vm_page_put_list_on_free_queue
+ _vm_page_steal_free_page
- ___vm_cpu_free_count_early_storage
- _vm_cpu_free_count
- _vm_page_free_queue_enter
- _vm_page_free_queue_grab
- _vm_page_free_queue_init
- _vm_page_free_queue_remove
- _vm_page_free_wakeup
CStrings:
+ "%s: inpcb socket so_usecount underflow  when removing timer entry\n"
+ "%s:%d should not modify cpu->free_pages while hibernating @%s:%d"
+ "Unrecognized remove reason %u @%s:%d"
+ "tcp_remove_timer"
+ "vm_page_grab_options_internal"
- "!os_add_overflow(*__counter, 1, __counter)"
- "!os_sub_overflow(*__counter, 1, __counter)"
- "!os_sub_overflow(*__counter, list.vmpl_count, __counter)"
- "should not modify CPU free_pages while hibernating @%s:%d"
- "should not modify cpu->free_pages while hibernating @%s:%d"
- "v16@?0^{vm_page=(?={vm_page_packed_queue_entry=II}^{vm_page}){vm_page_packed_queue_entry=II}{vm_page_packed_queue_entry=II}IIQ(?=SS){?=b4b2b1b1}{?=b1b1b1b1b1b1b1b1}b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b4b4b4b1b1I}8"
```
