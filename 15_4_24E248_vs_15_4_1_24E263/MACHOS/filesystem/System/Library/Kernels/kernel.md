## kernel

> `/System/Library/Kernels/kernel`

### Sections with Same Size but Changed Content

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

 11417.101.15.0.0
-  __TEXT.__text: 0x86ba90
-  __TEXT.__const: 0x42774
+  __TEXT.__text: 0x86bb20
+  __TEXT.__const: 0x42794
   __TEXT.__cstring: 0x95f3a
   __TEXT.__os_log: 0x3150b
   __TEXT.__eh_frame: 0x118

   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0
   __LINKINFO.__symbolsets: 0x4c491
-  __CTF.__ctf: 0xa7814
+  __CTF.__ctf: 0xa7a7b
   Functions: 26256
   Symbols:   23393
   CStrings:  23394
Functions:
~ _kdp_init : 1520 -> 1584
~ sub_ffffff80008fcbb0 -> sub_ffffff80008fcbf0 : 2784 -> 2864
~ sub_ffffff8000af5a6e -> sub_ffffff8000af5afe : 18446744073699108242 -> 18446744073699108098
```
