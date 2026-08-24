## kernel.release.vmapple

> `/System/Library/Kernels/kernel.release.vmapple`

### Sections with Same Size but Changed Content

- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__sdt_cstring`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__brk_desc`
- `__DATA.__data`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`

```diff

-11417.120.105.501.1
-  __TEXT.__const: 0x35960
+11417.121.6.0.0
+  __TEXT.__const: 0x35950
   __TEXT.__copyio_vectors: 0x120
   __TEXT.__cstring: 0x8c998
   __TEXT.__os_log: 0x2a50c

   __DATA_CONST.__const: 0x126688
   __DATA_CONST.__hib_const: 0x120
   __DATA_CONST.__sdt_cstring: 0x6a6a
-  __DATA_CONST.__sdt: 0x110e8
+  __DATA_CONST.__sdt: 0x11118
   __DATA_CONST.__kalloc_type: 0x16700
   __DATA_CONST.__kalloc_var: 0x8390
   __DATA_CONST.__assert: 0xf0
   __DATA_CONST.__brk_desc: 0x78
   __TEXT_EXEC.__hib_text: 0xde8
-  __TEXT_EXEC.__text: 0x8e18b0
+  __TEXT_EXEC.__text: 0x8e1a24
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xb0d8
   __LASTDATA_CONST.__mod_init_func: 0x8

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4dcb2
-  __CTF.__ctf: 0xd1028
+  __CTF.__ctf: 0xcf03b
   Functions: 20922
   Symbols:   6736
   CStrings:  21992
```
