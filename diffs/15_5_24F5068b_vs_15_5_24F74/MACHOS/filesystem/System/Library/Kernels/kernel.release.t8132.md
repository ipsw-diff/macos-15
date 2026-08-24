## kernel.release.t8132

> `/System/Library/Kernels/kernel.release.t8132`

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
- `__DATA.__data`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`

```diff

 11417.121.6.0.0
   __TEXT.__const: 0x35be0
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x93934
+  __TEXT.__cstring: 0x938f3
   __TEXT.__os_log: 0x2a7cd
   __TEXT.__eh_frame: 0x610
   __DATA_CONST.__auth_ptr: 0x10

   __DATA_CONST.__kalloc_type: 0x16940
   __DATA_CONST.__kalloc_var: 0x82f0
   __DATA_CONST.__assert: 0xf0
-  __DATA_CONST.__brk_desc: 0x78
+  __DATA_CONST.__brk_desc: 0x60
   __DATA_SPTM.__const: 0x54000
   __TEXT_EXEC.__hib_text: 0x1720
-  __TEXT_EXEC.__text: 0x8fe7f0
+  __TEXT_EXEC.__text: 0x8fe11c
   __TEXT_EXEC.__commpage_text: 0x2dc
   __TEXT_BOOT_EXEC.__bootcode: 0x514c
   __KLD.__text: 0xafe8

   __DATA.__lock_grp: 0x166c0
   __DATA.__percpu: 0x6e90
   __DATA.__common: 0x7ee38
-  __DATA.__bss: 0x46a90
+  __DATA.__bss: 0x46a80
   __HIBDATA.__data: 0x31
   __HIBDATA.__bss: 0x660
   __HIBDATA.__common: 0x108

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4e15f
-  __CTF.__ctf: 0xe189f
-  Functions: 21514
+  __CTF.__ctf: 0xdefd8
+  Functions: 21511
   Symbols:   6758
-  CStrings:  22754
+  CStrings:  22753
 
CStrings:
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
