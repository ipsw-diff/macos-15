## sharingd

> `/usr/libexec/sharingd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2060.60.31.0.0
-  __TEXT.__text: 0x63cc64
+2060.60.41.1.2
+  __TEXT.__text: 0x63cef8
   __TEXT.__auth_stubs: 0x89d0
-  __TEXT.__objc_stubs: 0x27180
-  __TEXT.__objc_methlist: 0x1a38c
-  __TEXT.__cstring: 0x35b0a
-  __TEXT.__objc_methname: 0x38b7a
+  __TEXT.__objc_stubs: 0x271e0
+  __TEXT.__objc_methlist: 0x1a394
+  __TEXT.__cstring: 0x35bda
+  __TEXT.__objc_methname: 0x38bc3
   __TEXT.__objc_classname: 0x25f7
   __TEXT.__objc_methtype: 0x83e1
   __TEXT.__const: 0x12e35

   __TEXT.__swift5_protos: 0x1f8
   __TEXT.__swift5_capture: 0x3118
   __TEXT.__swift5_mpenum: 0x14
-  __TEXT.__unwind_info: 0x10ec0
+  __TEXT.__unwind_info: 0x10ec8
   __TEXT.__eh_frame: 0x20768
   __DATA_CONST.__auth_got: 0x44f8
   __DATA_CONST.__got: 0x2a78
-  __DATA_CONST.__auth_ptr: 0x1c20
+  __DATA_CONST.__auth_ptr: 0x1ad0
   __DATA_CONST.__const: 0x17548
-  __DATA_CONST.__cfstring: 0x14200
+  __DATA_CONST.__cfstring: 0x14220
   __DATA_CONST.__objc_classlist: 0xd18
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x530

   __DATA_CONST.__objc_arrayobj: 0x318
   __DATA_CONST.__objc_dictobj: 0x15b8
   __DATA_CONST.__objc_doubleobj: 0x20
-  __DATA.__objc_const: 0x32bc8
-  __DATA.__objc_selrefs: 0xd6f0
-  __DATA.__objc_ivar: 0x2484
+  __DATA.__objc_const: 0x32be8
+  __DATA.__objc_selrefs: 0xd708
+  __DATA.__objc_ivar: 0x2488
   __DATA.__objc_data: 0x9588
   __DATA.__data: 0x1770a
   __DATA.__bss: 0x137bd

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 23080
+  Functions: 23082
   Symbols:   3830
-  CStrings:  21669
+  CStrings:  21678
 
CStrings:
+ "-[SDHotspotAgent _discoveryCachedDeviceFor:]"
+ "Found device without hotspot info and without recently cached info: %@"
+ "Found valid cached device: %@"
+ "Handoff active for %@, using cached device: %@"
+ "Stale hotspot info cache seconds overridden: %d -> %d\n"
+ "Using cached device found for %@: %@"
+ "_discoveryCachedDeviceFor:"
+ "_prefStaleCacheInfoSecs"
+ "hsStaleCacheSecs"
+ "lastSeen"
+ "setLastSeen:"
- "Found device without hotspot info: %@"
- "Using cached info for %@ due to handoff advertisement: %@"
```
