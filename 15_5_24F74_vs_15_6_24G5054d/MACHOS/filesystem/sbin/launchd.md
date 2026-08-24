## launchd

> `/sbin/launchd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__dof_launchd`
- `__TEXT.__unwind_info`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`
- `__DATA.__os_assumes_log`

```diff

-2894.121.3.0.0
-  __TEXT.__text: 0x51b80
+2894.140.10.0.0
+  __TEXT.__text: 0x51b74
   __TEXT.__auth_stubs: 0x1ed0
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x1f4
   __TEXT.__const: 0x2e0
-  __TEXT.__cstring: 0x156b4
+  __TEXT.__cstring: 0x155d2
   __TEXT.__launchd: 0x1
   __TEXT.__objc_methname: 0x8
   __TEXT.__objc_classname: 0x1ba

   __DATA_CONST.__auth_got: 0xf68
   __DATA_CONST.__got: 0x188
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA_CONST.__const: 0x5260
+  __DATA_CONST.__const: 0x51d0
   __DATA_CONST.__objc_classlist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0xa8

   - /usr/lib/libobjc.A.dylib
   Functions: 1615
   Symbols:   548
-  CStrings:  2669
+  CStrings:  2661
 
Functions:
~ sub_100004fa8 : 1680 -> 1720
~ sub_1000480d0 -> sub_1000480f8 : 308 -> 256
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Tue Jun  3 03:42:14 PDT 2025; root:libxpc_executables-2894.140.10~69/launchd/RELEASE_ARM64E"
+ "Darwin Bootstrapper Version 7.0.0: Tue Jun  3 03:42:14 PDT 2025; root:libxpc_executables-2894.140.10~69/launchd/RELEASE_ARM64E"
+ "Executable not in bundle"
- "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Tue Apr 22 20:04:45 PDT 2025; root:libxpc_executables-2894.121.3~2/launchd/RELEASE_ARM64E"
- "Darwin Bootstrapper Version 7.0.0: Tue Apr 22 20:04:45 PDT 2025; root:libxpc_executables-2894.121.3~2/launchd/RELEASE_ARM64E"
- "kGUARD_EXC_DEALLOC_GAP"
- "kGUARD_EXC_RECLAIM_COPYIO_FAILURE"
- "kGUARD_EXC_RECLAIM_DEALLOCATE_FAILURE"
- "kGUARD_EXC_RECLAIM_INDEX_FAILURE"
- "kGUARD_EXC_SEC_ACCESS_FAULT"
- "kGUARD_EXC_SEC_COPY_DENIED"
- "kGUARD_EXC_SEC_LOOKUP_DENIED"
- "kGUARD_EXC_SEC_RANGE_DENIED"
- "kGUARD_EXC_SEC_SHARING_DENIED"
```
