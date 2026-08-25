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

```diff

-11417.140.62.501.1
+11417.140.64.0.1
   __TEXT.__const: 0x35cb0
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x8cf59
-  __TEXT.__os_log: 0x2a4fe
+  __TEXT.__cstring: 0x8cf84
+  __TEXT.__os_log: 0x2a531
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0
   __DATA_CONST.__auth_ptr: 0x10

   __DATA_CONST.__kalloc_type: 0x16700
   __DATA_CONST.__kalloc_var: 0x8390
   __DATA_CONST.__assert: 0x1cc
-  __DATA_CONST.__brk_desc: 0x78
+  __DATA_CONST.__kern_brk_desc: 0x78
   __TEXT_EXEC.__hib_text: 0xde8
-  __TEXT_EXEC.__text: 0x8ea638
+  __TEXT_EXEC.__text: 0x8e9d28
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xb0d8
   __LASTDATA_CONST.__mod_init_func: 0x8

   __PLK_DATA_CONST.__data: 0x0
   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
-  __LINKINFO.__symbolsets: 0x4dd00
-  __CTF.__ctf: 0xc99b3
-  Functions: 20932
-  Symbols:   6738
-  CStrings:  22004
+  __LINKINFO.__symbolsets: 0x4dd32
+  __CTF.__ctf: 0xcd2f8
+  Functions: 20931
+  Symbols:   6739
+  CStrings:  22006
 
Symbols:
+ _address_space_debugged_state
+ _is_address_space_debugged
- _address_space_debugged
CStrings:
+ "%s: process %s[%d] hit an unrecoverable exception\n"
+ "address_space_debugged_state"
+ "maybe_unrecoverable_exception_triage"
- "address_space_debugged"
```
