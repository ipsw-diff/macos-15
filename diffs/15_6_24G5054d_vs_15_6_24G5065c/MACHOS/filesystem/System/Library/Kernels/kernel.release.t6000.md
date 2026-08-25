## kernel.release.t6000

> `/System/Library/Kernels/kernel.release.t6000`

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
- `__PPLDATA_CONST.__const`
- `__DATA.__data`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`

```diff

-11417.140.62.501.1
+11417.140.64.0.1
   __TEXT.__const: 0x36690
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x9b8ee
-  __TEXT.__os_log: 0x2a80b
+  __TEXT.__cstring: 0x9b919
+  __TEXT.__os_log: 0x2a83e
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0
   __DATA_CONST.__auth_ptr: 0x10

   __DATA_CONST.__kalloc_type: 0x16940
   __DATA_CONST.__kalloc_var: 0x82f0
   __DATA_CONST.__assert: 0x1cc
-  __DATA_CONST.__brk_desc: 0x78
+  __DATA_CONST.__kern_brk_desc: 0x78
   __TEXT_EXEC.__hib_text: 0x3ff0
-  __TEXT_EXEC.__text: 0x9137d8
+  __TEXT_EXEC.__text: 0x912d64
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xb0d8
   __PPLTEXT.__text: 0x3155c

   __PLK_DATA_CONST.__data: 0x0
   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
-  __LINKINFO.__symbolsets: 0x4e1ad
-  __CTF.__ctf: 0xe0a46
-  Functions: 21846
-  Symbols:   6760
-  CStrings:  23279
+  __LINKINFO.__symbolsets: 0x4e1df
+  __CTF.__ctf: 0xdf13e
+  Functions: 21845
+  Symbols:   6761
+  CStrings:  23281
 
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
