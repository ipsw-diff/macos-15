## kernel.release.t8112

> `/System/Library/Kernels/kernel.release.t8112`

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
- `__KLDDATA.__const`
- `__KLDDATA.__mod_init_func`
- `__KLDDATA.__mod_term_func`
- `__DATA.__data`
- `__HIBDATA.__data`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`
- `__BOOTDATA.__static_ifinit`

```diff

 11417.121.6.0.0
   __TEXT.__const: 0x36300
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x9a10f
+  __TEXT.__cstring: 0x9a0ce
   __TEXT.__os_log: 0x2a7a7
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0

   __DATA_CONST.__kalloc_type: 0x16940
   __DATA_CONST.__kalloc_var: 0x82f0
   __DATA_CONST.__assert: 0xf0
-  __DATA_CONST.__brk_desc: 0x78
+  __DATA_CONST.__brk_desc: 0x60
   __TEXT_EXEC.__hib_text: 0x3fc0
-  __TEXT_EXEC.__text: 0x8eff70
+  __TEXT_EXEC.__text: 0x8ef8f4
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xafe8
   __PPLTEXT.__text: 0x2d678

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4e15f
-  __CTF.__ctf: 0xdd541
-  Functions: 21793
+  __CTF.__ctf: 0xe07fa
+  Functions: 21790
   Symbols:   6758
-  CStrings:  23188
+  CStrings:  23187
 
CStrings:
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
