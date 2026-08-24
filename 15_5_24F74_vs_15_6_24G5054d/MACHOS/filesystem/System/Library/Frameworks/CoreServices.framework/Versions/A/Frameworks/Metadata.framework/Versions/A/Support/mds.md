## mds

> `/System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/Metadata.framework/Versions/A/Support/mds`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__dof_mds`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2333.50.1.0.0
-  __TEXT.__text: 0x160a6c
+2333.55.0.0.0
+  __TEXT.__text: 0x160a78
   __TEXT.__auth_stubs: 0x3c40
   __TEXT.__objc_stubs: 0xc900
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x7e1c
   __TEXT.__const: 0x5ed0
-  __TEXT.__cstring: 0x1827e
+  __TEXT.__cstring: 0x1833f
   __TEXT.__objc_classname: 0xcd1
-  __TEXT.__oslogstring: 0x11122
-  __TEXT.__gcc_except_tab: 0x1ba4
+  __TEXT.__oslogstring: 0x1110f
+  __TEXT.__gcc_except_tab: 0x1ba8
   __TEXT.__objc_methname: 0x10a65
   __TEXT.__objc_methtype: 0x5a18
   __TEXT.__dof_mds: 0x5735

   - /usr/lib/libfakelink.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 9264
+  Functions: 9262
   Symbols:   1301
-  CStrings:  8855
+  CStrings:  8852
 
CStrings:
+ "<DiskArb>END diskUnmountApprovalCallback seconds:%ld mds_stores-pid:%d"
- "<DiskArb>END diskUnmountApprovalCallback seconds:%ld %@ retainCount:%d diskRetainCount:%d"
- "availableLength >= 1"
- "availableLength >= info->inlineLength"
- "parseCommand"
```
