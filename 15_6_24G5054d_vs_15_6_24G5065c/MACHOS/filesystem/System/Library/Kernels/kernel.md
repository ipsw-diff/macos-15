## kernel

> `/System/Library/Kernels/kernel`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__assert`
- `__KLDDATA.__init`
- `__KLDDATA.__init_entry_set`
- `__KLDDATA.__static_ifinit`

```diff

-11417.140.62.501.1
-  __TEXT.__text: 0x871090
+11417.140.64.0.1
+  __TEXT.__text: 0x8714c0
   __TEXT.__const: 0x42b04
-  __TEXT.__cstring: 0x96655
-  __TEXT.__os_log: 0x3152b
+  __TEXT.__cstring: 0x96695
+  __TEXT.__os_log: 0x3156b
   __TEXT.__eh_frame: 0x118
   __DATA.__llvm_prf_cnts: 0x0
   __DATA.__llvm_prf_data: 0x0

   __DATA_CONST.__const: 0x9c340
   __DATA_CONST.__kalloc_var: 0x8250
   __DATA_CONST.__kalloc_type: 0x16a80
-  __DATA_CONST.__brk_desc: 0x60
+  __DATA_CONST.__kern_brk_desc: 0x60
   __DATA_CONST.__sdt_cstring: 0x6aed
   __DATA_CONST.__sdt: 0x11040
   __DATA_CONST.__assert: 0x208

   __LAST.__last: 0x0
   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0
-  __LINKINFO.__symbolsets: 0x4c4e2
-  __CTF.__ctf: 0xa61a8
-  Functions: 26272
-  Symbols:   23408
-  CStrings:  23411
+  __LINKINFO.__symbolsets: 0x4c514
+  __CTF.__ctf: 0xa7e1c
+  Functions: 26273
+  Symbols:   23409
+  CStrings:  23413
 
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
