## kernel

> `/System/Library/Kernels/kernel`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kern_brk_desc`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__assert`
- `__KLDDATA.__init`
- `__KLDDATA.__init_entry_set`
- `__KLDDATA.__static_ifinit`

```diff

-11417.140.64.0.1
-  __TEXT.__text: 0x8714c0
-  __TEXT.__const: 0x42b04
-  __TEXT.__cstring: 0x96695
-  __TEXT.__os_log: 0x3156b
+11417.140.66.0.0
+  __TEXT.__text: 0x871610
+  __TEXT.__const: 0x42af4
+  __TEXT.__cstring: 0x966c5
+  __TEXT.__os_log: 0x315fb
   __TEXT.__eh_frame: 0x118
   __DATA.__llvm_prf_cnts: 0x0
   __DATA.__llvm_prf_data: 0x0

   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0
   __LINKINFO.__symbolsets: 0x4c514
-  __CTF.__ctf: 0xa7e1c
-  Functions: 26273
+  __CTF.__ctf: 0xa78bf
+  Functions: 26274
   Symbols:   23409
-  CStrings:  23413
+  CStrings:  23417
 
CStrings:
+ "%s: %s: clearing SCF_PROTO_ATTACHED"
+ "%s: %s: proto count %d"
+ "%s: %s: setting SCF_PROTO_ATTACHED"
+ "bridge_interface_attach_protocol"
+ "bridge_interface_proto_attach_changed"
- "%s: ifp %s has address"
```
