## kernel.release.t8103

> `/System/Library/Kernels/kernel.release.t8103`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__copyio_vectors`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__hib_const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__assert`
- `__PPLDATA_CONST.__const`
- `__DATA.__data`
- `__BOOTDATA.__init`
- `__BOOTDATA.__static_ifinit`

```diff

-11417.140.66.0.0
+11417.140.69.0.0
   __TEXT.__const: 0x366a0
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x99618
+  __TEXT.__cstring: 0x995f3
   __TEXT.__os_log: 0x2a888
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0

   __DATA_CONST.__kalloc_type: 0x16940
   __DATA_CONST.__kalloc_var: 0x82f0
   __DATA_CONST.__assert: 0x1cc
-  __DATA_CONST.__kern_brk_desc: 0x78
+  __DATA_CONST.__kern_brk_desc: 0x60
   __TEXT_EXEC.__hib_text: 0x3f88
-  __TEXT_EXEC.__text: 0x9117f4
+  __TEXT_EXEC.__text: 0x910e2c
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xb0d8
   __PPLTEXT.__text: 0x2bc88

   __LAST.__last: 0x0
   __PPLDATA.__data: 0x4ca8
   __KLDDATA.__cstring: 0x71f
-  __KLDDATA.__const: 0x8e20
+  __KLDDATA.__const: 0x8e90
   __KLDDATA.__mod_init_func: 0x8
   __KLDDATA.__mod_term_func: 0x8
   __KLDDATA.__bss: 0x1

   __HIBDATA.__bss: 0x660
   __BOOTDATA.__data: 0x18000
   __BOOTDATA.__init: 0x5ba58
-  __BOOTDATA.__init_entry_set: 0x11a60
+  __BOOTDATA.__init_entry_set: 0x11a90
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0
   __PRELINK_TEXT.__text: 0x0

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4e1df
-  __CTF.__ctf: 0xdbcf0
-  Functions: 21797
+  __CTF.__ctf: 0xdaa9e
+  Functions: 21794
   Symbols:   6761
   CStrings:  23124
 
CStrings:
+ "unrestricted-subsystem-root"
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
