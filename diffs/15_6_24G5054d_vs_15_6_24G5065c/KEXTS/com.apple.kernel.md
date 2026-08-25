## com.apple.kernel

> `com.apple.kernel`

```diff

-11417.140.62.501.1
+11417.140.64.0.1
   __TEXT.__const: 0x366a0
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x995a6
-  __TEXT.__os_log: 0x2a7e5
+  __TEXT.__cstring: 0x995d1
+  __TEXT.__os_log: 0x2a818
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0
   __DATA_CONST.__auth_ptr: 0x10

   __DATA_CONST.__kalloc_type: 0x16940
   __DATA_CONST.__kalloc_var: 0x82f0
   __DATA_CONST.__assert: 0x1cc
-  __DATA_CONST.__brk_desc: 0x78
+  __DATA_CONST.__kern_brk_desc: 0x78
   __TEXT_EXEC.__hib_text: 0x3f88
-  __TEXT_EXEC.__text: 0x9120c4
+  __TEXT_EXEC.__text: 0x911650
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xb0d8
   __PPLTEXT.__text: 0x2bc88

   __PLK_DATA_CONST.__data: 0x0
   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
-  __LINKINFO.__symbolsets: 0x4e1ad
+  __LINKINFO.__symbolsets: 0x4e1df
   __CTF.__ctf: 0x0
-  Functions: 21797
-  Symbols:   6760
-  CStrings:  23118
+  Functions: 21796
+  Symbols:   6761
+  CStrings:  23120
 
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
