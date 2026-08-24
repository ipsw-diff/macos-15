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
- `__DATA_CONST.__brk_desc`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__assert`
- `__KLDDATA.__init`
- `__KLDDATA.__init_entry_set`
- `__KLDDATA.__static_ifinit`

```diff

 11417.121.6.0.0
-  __TEXT.__text: 0x86ca30
+  __TEXT.__text: 0x86c8d0
   __TEXT.__const: 0x42774
-  __TEXT.__cstring: 0x95fda
+  __TEXT.__cstring: 0x95f9a
   __TEXT.__os_log: 0x3154b
   __TEXT.__eh_frame: 0x118
   __DATA.__llvm_prf_cnts: 0x0

   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0
   __LINKINFO.__symbolsets: 0x4c4e2
-  __CTF.__ctf: 0xa73b4
+  __CTF.__ctf: 0xa85ec
   Functions: 26272
   Symbols:   23413
-  CStrings:  23401
+  CStrings:  23400
 
Functions:
~ sub_ffffff80002c0750 : 2832 -> 2720
~ _kern_dump_should_enforce_encryption : 240 -> 128
~ _kdp_core_init : 1584 -> 1488
~ sub_ffffff80007fdda0 -> sub_ffffff80007fdc60 : 5376 -> 5344
~ sub_ffffff8000af5a0e -> sub_ffffff8000af58ae : 18446744073699108338 -> 18446744073699108690
CStrings:
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
