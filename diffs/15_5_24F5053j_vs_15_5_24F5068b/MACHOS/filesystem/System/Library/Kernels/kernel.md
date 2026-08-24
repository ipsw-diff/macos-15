## kernel

> `/System/Library/Kernels/kernel`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__brk_desc`
- `__DATA_CONST.__sdt_cstring`
- `__DATA_CONST.__assert`
- `__KLDDATA.__init`
- `__KLDDATA.__init_entry_set`
- `__KLDDATA.__static_ifinit`

```diff

-11417.120.105.501.1
-  __TEXT.__text: 0x86c9c0
-  __TEXT.__const: 0x42794
-  __TEXT.__cstring: 0x95fba
+11417.121.6.0.0
+  __TEXT.__text: 0x86ca30
+  __TEXT.__const: 0x42774
+  __TEXT.__cstring: 0x95fda
   __TEXT.__os_log: 0x3154b
   __TEXT.__eh_frame: 0x118
   __DATA.__llvm_prf_cnts: 0x0

   __DATA_CONST.__kalloc_type: 0x16a80
   __DATA_CONST.__brk_desc: 0x60
   __DATA_CONST.__sdt_cstring: 0x6aaa
-  __DATA_CONST.__sdt: 0x10fe0
+  __DATA_CONST.__sdt: 0x11010
   __DATA_CONST.__assert: 0xf0
   __KLDDATA.__init: 0x22800
   __KLDDATA.__init_entry_set: 0x11c28

   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0
   __LINKINFO.__symbolsets: 0x4c4e2
-  __CTF.__ctf: 0xa69c9
-  Functions: 26271
-  Symbols:   23412
-  CStrings:  23399
+  __CTF.__ctf: 0xa73b4
+  Functions: 26272
+  Symbols:   23413
+  CStrings:  23401
 
Symbols:
+ _vm_object_cache_evict_all
CStrings:
+ "%s: freed %d\n"
+ "vm_object_cache_evict_all"
```
