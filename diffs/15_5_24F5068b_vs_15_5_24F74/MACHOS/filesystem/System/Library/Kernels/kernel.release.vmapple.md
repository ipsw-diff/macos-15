## kernel.release.vmapple

> `/System/Library/Kernels/kernel.release.vmapple`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__copyio_vectors`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__assert`
- `__DATA.__data`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`
- `__BOOTDATA.__static_ifinit`

```diff

 11417.121.6.0.0
   __TEXT.__const: 0x35950
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x8c998
+  __TEXT.__cstring: 0x8c957
   __TEXT.__os_log: 0x2a50c
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0

   __DATA_CONST.__kalloc_type: 0x16700
   __DATA_CONST.__kalloc_var: 0x8390
   __DATA_CONST.__assert: 0xf0
-  __DATA_CONST.__brk_desc: 0x78
+  __DATA_CONST.__brk_desc: 0x60
   __TEXT_EXEC.__hib_text: 0xde8
-  __TEXT_EXEC.__text: 0x8e1a24
+  __TEXT_EXEC.__text: 0x8e13b8
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xb0d8
   __LASTDATA_CONST.__mod_init_func: 0x8

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4dcb2
-  __CTF.__ctf: 0xcf03b
-  Functions: 20922
+  __CTF.__ctf: 0xce4aa
+  Functions: 20919
   Symbols:   6736
-  CStrings:  21992
+  CStrings:  21991
 
CStrings:
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
