## kernel

> `/System/Library/Kernels/kernel`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kern_brk_desc`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__assert`
- `__KLDDATA.__init`
- `__KLDDATA.__static_ifinit`

```diff

-11417.140.66.0.0
-  __TEXT.__text: 0x871610
-  __TEXT.__const: 0x42af4
-  __TEXT.__cstring: 0x966c5
+11417.140.69.0.0
+  __TEXT.__text: 0x8711f0
+  __TEXT.__const: 0x42ae4
+  __TEXT.__cstring: 0x966b5
   __TEXT.__os_log: 0x315fb
   __TEXT.__eh_frame: 0x118
   __DATA.__llvm_prf_cnts: 0x0

   __DATA.__bss: 0x76950
   __DATA_CONST.__got: 0x70
   __DATA_CONST.__mod_init_func: 0x2c8
-  __DATA_CONST.__const: 0x9c340
+  __DATA_CONST.__const: 0x9c350
   __DATA_CONST.__kalloc_var: 0x8250
   __DATA_CONST.__kalloc_type: 0x16a80
   __DATA_CONST.__kern_brk_desc: 0x60

   __DATA_CONST.__sdt: 0x11040
   __DATA_CONST.__assert: 0x208
   __KLDDATA.__init: 0x22808
-  __KLDDATA.__init_entry_set: 0x11c70
+  __KLDDATA.__init_entry_set: 0x11ca0
   __KLDDATA.__cstring: 0x79c
-  __KLDDATA.__const: 0x88d0
+  __KLDDATA.__const: 0x8940
   __KLDDATA.__mod_init_func: 0x8
   __KLDDATA.__mod_term_func: 0x8
   __KLDDATA.__static_if: 0x0

   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0
   __LINKINFO.__symbolsets: 0x4c514
-  __CTF.__ctf: 0xa78bf
+  __CTF.__ctf: 0xa7157
   Functions: 26274
-  Symbols:   23409
+  Symbols:   23410
   CStrings:  23417
 
Symbols:
+ _vm_page_deactivate_behind_min_resident_ratio
Functions:
~ sub_ffffff80002bb750 : 2832 -> 2720
~ _kern_dump_should_enforce_encryption : 240 -> 128
~ _kdp_core_init : 1584 -> 1488
~ sub_ffffff80003a4380 -> sub_ffffff80003a4240 : 672 -> 832
~ sub_ffffff8000673100 -> sub_ffffff8000673060 : 7040 -> 6992
~ sub_ffffff80006765c0 -> sub_ffffff80006764f0 : 2512 -> 2464
~ sub_ffffff8000677920 -> sub_ffffff8000677820 : 2128 -> 2096
~ sub_ffffff80007fc330 -> sub_ffffff80007fc210 : 5376 -> 5344
~ sub_ffffff8000805670 -> sub_ffffff8000805530 : 1680 -> 1888
~ sub_ffffff800081b590 -> sub_ffffff800081b520 : 3040 -> 3056
~ _soflow_fill_hash_entry_from_address : 384 -> 432
~ _soflow_fill_hash_entry_from_inp : 464 -> 576
~ sub_ffffff80008c4930 -> sub_ffffff80008c4970 : 1648 -> 1200
~ _soflow_get_flow : 3312 -> 2704
~ sub_ffffff80008c5c90 -> sub_ffffff80008c58b0 : 960 -> 896
~ sub_ffffff8000af55ee -> sub_ffffff8000af51ce : 18446744073699109394 -> 18446744073699110450
CStrings:
+ "unrestricted-subsystem-root"
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
