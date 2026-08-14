## appstoreagent

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/Support/appstoreagent`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-11.5.3.0.0
-  __TEXT.__text: 0x3df53c
-  __TEXT.__auth_stubs: 0x3d90
-  __TEXT.__objc_stubs: 0xfc00
+11.5.4.0.0
+  __TEXT.__text: 0x3dff84
+  __TEXT.__auth_stubs: 0x3da0
+  __TEXT.__objc_stubs: 0xfc20
   __TEXT.__objc_methlist: 0xa5f8
   __TEXT.__dlopen_cstrs: 0x11a
   __TEXT.__const: 0x71c68
-  __TEXT.__cstring: 0x19ffe
-  __TEXT.__objc_methname: 0x15fc1
-  __TEXT.__constg_swiftt: 0x1dc4
-  __TEXT.__swift5_typeref: 0x2ff6
-  __TEXT.__swift5_reflstr: 0x1aaa
-  __TEXT.__swift5_fieldmd: 0x2074
+  __TEXT.__cstring: 0x19fcb
+  __TEXT.__objc_methname: 0x15fbe
+  __TEXT.__constg_swiftt: 0x1ddc
+  __TEXT.__swift5_typeref: 0x3008
+  __TEXT.__swift5_reflstr: 0x1aba
+  __TEXT.__swift5_fieldmd: 0x2080
   __TEXT.__swift5_builtin: 0x1f4
   __TEXT.__swift5_assocty: 0x348
   __TEXT.__swift5_capture: 0x1420
-  __TEXT.__oslogstring: 0x28cb1
+  __TEXT.__oslogstring: 0x28f82
   __TEXT.__swift5_proto: 0x324
   __TEXT.__swift5_types: 0x1f4
   __TEXT.__objc_classname: 0x333d

   __TEXT.__swift5_mpenum: 0x34
   __TEXT.__gcc_except_tab: 0x6aa0
   __TEXT.__ustring: 0x194
-  __TEXT.__unwind_info: 0x8298
+  __TEXT.__unwind_info: 0x82a0
   __TEXT.__eh_frame: 0x7738
-  __DATA_CONST.__auth_got: 0x1ed8
+  __DATA_CONST.__auth_got: 0x1ee0
   __DATA_CONST.__got: 0x1658
-  __DATA_CONST.__auth_ptr: 0x890
-  __DATA_CONST.__const: 0x26158
-  __DATA_CONST.__cfstring: 0x15300
+  __DATA_CONST.__auth_ptr: 0x810
+  __DATA_CONST.__const: 0x26130
+  __DATA_CONST.__cfstring: 0x152a0
   __DATA_CONST.__objc_classlist: 0x10d8
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x438

   __DATA_CONST.__objc_arrayobj: 0x348
   __DATA_CONST.__objc_doubleobj: 0x40
   __DATA.__objc_const: 0x29d40
-  __DATA.__objc_selrefs: 0x5190
-  __DATA.__objc_ivar: 0x1d78
+  __DATA.__objc_selrefs: 0x5198
+  __DATA.__objc_ivar: 0x1d74
   __DATA.__objc_data: 0xba60
-  __DATA.__data: 0x6878
+  __DATA.__data: 0x68a0
   __DATA.__bss: 0x69e8
   __DATA.__common: 0x148c
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 10033
-  Symbols:   1885
-  CStrings:  11363
+  Functions: 10029
+  Symbols:   1886
+  CStrings:  11369
 
Symbols:
+ _fstatfs
CStrings:
+ "00:10:58"
+ "Apr 15 2025"
+ "[%@] Encountered fatal verification failure: %{public}@"
+ "[%@] Preallocating %{public}llu"
+ "[%@] Preallocation of %{public}llu bytes failed (%{public}d"
+ "[%@] Preallocation of %{public}llu bytes failed, checking if there is enough space for a partial allocation instead"
+ "[%@] Retry after verification failure was successful!"
+ "[%@] Retrying once after verification failure: %{public}@"
+ "[%@] Second attempt at preallocation also failed (%{public}d"
+ "[%@] Second attempt preallocated %{public}lld bytes"
+ "[%@] Second partial-preallocation attempt succeed but size could not be determined (%{public}d)"
+ "[%@] Skipping second preallocation attempt because free disk space could not be determined (%{public}d)"
+ "[%@] Skipping second preallocation attempt because there really is not enough space available (only %llu bytes available)"
+ "[Device] Marked once per boot complete for: %{public}@"
+ "addDependency:"
+ "failedIndexes"
- "02:10:51"
- "Apr  4 2025"
- "Completed store queue checks on reboot"
- "Failed to complete store queue checks on reboot; will retry next daemon launch"
- "Preallocating %{public}llu"
- "Reboot"
- "[%@] Encountered verification failure: %{public}@"
- "_oncePerBootItems"
- "checkStoreQueues"
- "com.apple.appstored.TaskQueue.barrierBlock"
```
