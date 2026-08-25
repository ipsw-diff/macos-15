## kernel.release.t8132

> `/System/Library/Kernels/kernel.release.t8132`

### Sections with Same Size but Changed Content

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
- `__DATA.__data`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`

```diff

-11417.140.64.0.1
-  __TEXT.__const: 0x35f50
+11417.140.66.0.0
+  __TEXT.__const: 0x35f40
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x94177
-  __TEXT.__os_log: 0x2a83e
+  __TEXT.__cstring: 0x941be
+  __TEXT.__os_log: 0x2a8ae
   __TEXT.__eh_frame: 0x610
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__mod_init_func: 0x2d8

   __DATA_CONST.__kern_brk_desc: 0x78
   __DATA_SPTM.__const: 0x54000
   __TEXT_EXEC.__hib_text: 0x1720
-  __TEXT_EXEC.__text: 0x901f9c
+  __TEXT_EXEC.__text: 0x902134
   __TEXT_EXEC.__commpage_text: 0x2dc
   __TEXT_BOOT_EXEC.__bootcode: 0x514c
   __KLD.__text: 0xafe8

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4e1df
-  __CTF.__ctf: 0xdf07c
-  Functions: 21535
+  __CTF.__ctf: 0xe0a6e
+  Functions: 21536
   Symbols:   6761
-  CStrings:  22777
+  CStrings:  22781
 
CStrings:
+ "%s: %s: clearing SCF_PROTO_ATTACHED"
+ "%s: %s: proto count %d"
+ "%s: %s: setting SCF_PROTO_ATTACHED"
+ "bridge_interface_attach_protocol"
+ "bridge_interface_proto_attach_changed"
- "%s: ifp %s has address"
```
