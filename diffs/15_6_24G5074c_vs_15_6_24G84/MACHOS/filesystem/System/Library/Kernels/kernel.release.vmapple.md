## kernel.release.vmapple

> `/System/Library/Kernels/kernel.release.vmapple`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__assert`
- `__DATA.__data`
- `__BOOTDATA.__init`
- `__BOOTDATA.__static_ifinit`

```diff

-11417.140.66.0.0
+11417.140.69.0.0
   __TEXT.__const: 0x35cb0
   __TEXT.__copyio_vectors: 0x120
-  __TEXT.__cstring: 0x8cfcb
+  __TEXT.__cstring: 0x8cfa6
   __TEXT.__os_log: 0x2a5a1
   __TEXT.__thread_starts: 0x0
   __TEXT.__eh_frame: 0x4e0

   __DATA_CONST.__kalloc_type: 0x16700
   __DATA_CONST.__kalloc_var: 0x8390
   __DATA_CONST.__assert: 0x1cc
-  __DATA_CONST.__kern_brk_desc: 0x78
+  __DATA_CONST.__kern_brk_desc: 0x60
   __TEXT_EXEC.__hib_text: 0xde8
-  __TEXT_EXEC.__text: 0x8e9ecc
+  __TEXT_EXEC.__text: 0x8e9510
   __TEXT_EXEC.__commpage_text: 0x2dc
   __KLD.__text: 0xb0d8
   __LASTDATA_CONST.__mod_init_func: 0x8
   __LAST.__last: 0x0
   __KLDDATA.__cstring: 0x71f
-  __KLDDATA.__const: 0x8d48
+  __KLDDATA.__const: 0x8db8
   __KLDDATA.__mod_init_func: 0x8
   __KLDDATA.__mod_term_func: 0x8
   __KLDDATA.__bss: 0x1

   __DATA.__bss: 0x3c060
   __BOOTDATA.__data: 0x18000
   __BOOTDATA.__init: 0x5b6f0
-  __BOOTDATA.__init_entry_set: 0x11310
+  __BOOTDATA.__init_entry_set: 0x11340
   __BOOTDATA.__static_ifinit: 0x8
   __BOOTDATA.__static_if: 0x0
   __PRELINK_TEXT.__text: 0x0

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x4dd32
-  __CTF.__ctf: 0xcaaea
-  Functions: 20932
+  __CTF.__ctf: 0xcdfc3
+  Functions: 20929
   Symbols:   6739
   CStrings:  22010
 
CStrings:
+ "unrestricted-subsystem-root"
- "com.apple.private.enable-coredump-on-panic-seed-privacy-approved"
```
