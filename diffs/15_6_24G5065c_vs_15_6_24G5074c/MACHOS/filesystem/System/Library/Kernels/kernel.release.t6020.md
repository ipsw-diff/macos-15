## kernel.release.t6020

> `/System/Library/Kernels/kernel.release.t6020`

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

-11417.140.64.0.1
+11417.140.66.0.0
   __TEXT.__const: 0x366d0
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x9d9d6
-  __TEXT.__os_log: 0x2a898
+  __TEXT.__cstring: 0x9da1d
+  __TEXT.__os_log: 0x2a908
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0
   __DATA_CONST.__auth_ptr: 0x10

   __DATA_CONST.__assert: 0x1e0
   __DATA_CONST.__kern_brk_desc: 0x78
   __TEXT_EXEC.__hib_text: 0x4048
-  __TEXT_EXEC.__text: 0x8fade8
+  __TEXT_EXEC.__text: 0x8faf80
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xafe8
   __PPLTEXT.__text: 0x315e4

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4e1df
-  __CTF.__ctf: 0xdbd48
-  Functions: 21915
+  __CTF.__ctf: 0xd8f71
+  Functions: 21916
   Symbols:   6761
-  CStrings:  23486
+  CStrings:  23490
 
CStrings:
+ "%s: %s: clearing SCF_PROTO_ATTACHED"
+ "%s: %s: proto count %d"
+ "%s: %s: setting SCF_PROTO_ATTACHED"
+ "bridge_interface_attach_protocol"
+ "bridge_interface_proto_attach_changed"
- "%s: ifp %s has address"
```
