## kernel.release.t6041

> `/System/Library/Kernels/kernel.release.t6041`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__hib_const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__assert`
- `__KLDDATA.__mod_init_func`
- `__KLDDATA.__mod_term_func`
- `__DATA.__data`
- `__HIBDATA.__data`
- `__BOOTDATA.__init`
- `__BOOTDATA.__static_ifinit`

```diff

-11417.140.66.0.0
+11417.140.69.0.0
   __TEXT.__const: 0x35f50
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x94a9f
+  __TEXT.__cstring: 0x94a7a
   __TEXT.__os_log: 0x2a8e2
   __TEXT.__eh_frame: 0x610
   __DATA_CONST.__auth_ptr: 0x10

   __DATA_CONST.__kalloc_type: 0x169c0
   __DATA_CONST.__kalloc_var: 0x8430
   __DATA_CONST.__assert: 0x1e0
-  __DATA_CONST.__kern_brk_desc: 0x78
+  __DATA_CONST.__kern_brk_desc: 0x60
   __DATA_SPTM.__const: 0x54000
   __TEXT_EXEC.__hib_text: 0x1720
-  __TEXT_EXEC.__text: 0x905f30
+  __TEXT_EXEC.__text: 0x9054f0
   __TEXT_EXEC.__commpage_text: 0x2dc
   __TEXT_BOOT_EXEC.__bootcode: 0x514c
   __KLD.__text: 0xafe8

   __LAST.__pinst: 0x8
   __LAST.__last: 0x0
   __KLDDATA.__cstring: 0x71f
-  __KLDDATA.__const: 0x8ed0
+  __KLDDATA.__const: 0x8f40
   __KLDDATA.__mod_init_func: 0x8
   __KLDDATA.__mod_term_func: 0x8
   __KLDDATA.__bss: 0x1

   __DATA.__lock_grp: 0x166c0
   __DATA.__percpu: 0x6410
   __DATA.__common: 0x7f058
-  __DATA.__bss: 0x46de0
+  __DATA.__bss: 0x46dd0
   __HIBDATA.__data: 0x31
   __HIBDATA.__bss: 0x660
   __HIBDATA.__common: 0x108
   __BOOTDATA.__data: 0x18000
   __BOOTDATA.__init: 0x5bb80
-  __BOOTDATA.__init_entry_set: 0x11bb0
+  __BOOTDATA.__init_entry_set: 0x11be0
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0
   __PRELINK_TEXT.__text: 0x0

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4e1df
-  __CTF.__ctf: 0xdff87
-  Functions: 21567
+  __CTF.__ctf: 0xe2689
+  Functions: 21564
   Symbols:   6761
   CStrings:  22849
 
CStrings:
+ "unrestricted-subsystem-root"
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
