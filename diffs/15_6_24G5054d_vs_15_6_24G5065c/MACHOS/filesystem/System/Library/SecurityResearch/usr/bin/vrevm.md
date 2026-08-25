## vrevm

> `/System/Library/SecurityResearch/usr/bin/vrevm`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_capture`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-199.140.7.0.0
-  __TEXT.__text: 0x6526c
-  __TEXT.__auth_stubs: 0x1a90
+199.140.13.0.0
+  __TEXT.__text: 0x65090
+  __TEXT.__auth_stubs: 0x1a80
   __TEXT.__objc_methlist: 0x18c
   __TEXT.__const: 0x3096
-  __TEXT.__cstring: 0x2152
+  __TEXT.__cstring: 0x2042
   __TEXT.__constg_swiftt: 0xac4
   __TEXT.__swift5_typeref: 0xc80
   __TEXT.__swift5_builtin: 0x64
   __TEXT.__swift5_reflstr: 0x958
   __TEXT.__swift5_fieldmd: 0x1018
   __TEXT.__swift5_assocty: 0x138
-  __TEXT.__oslogstring: 0x7b5
+  __TEXT.__oslogstring: 0x7f5
   __TEXT.__objc_methname: 0xab1
   __TEXT.__swift5_proto: 0x31c
   __TEXT.__swift5_types: 0x108

   __TEXT.__swift5_capture: 0xbc
   __TEXT.__objc_classname: 0x22
   __TEXT.__objc_methtype: 0x15a
-  __TEXT.__unwind_info: 0x1270
-  __TEXT.__eh_frame: 0x23b4
-  __DATA_CONST.__auth_got: 0xd48
-  __DATA_CONST.__got: 0x4d8
-  __DATA_CONST.__auth_ptr: 0x5a0
+  __TEXT.__unwind_info: 0x1260
+  __TEXT.__eh_frame: 0x235c
+  __DATA_CONST.__auth_got: 0xd40
+  __DATA_CONST.__got: 0x4d0
+  __DATA_CONST.__auth_ptr: 0x588
   __DATA_CONST.__const: 0x1dc8
   __DATA_CONST.__objc_classlist: 0x30
   __DATA_CONST.__objc_protolist: 0x20

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1370
-  Symbols:   720
-  CStrings:  436
+  Functions: 1368
+  Symbols:   718
+  CStrings:  432
 
Symbols:
- _$ss5Int32Vs23CustomStringConvertiblesWP
- _sysctlbyname
CStrings:
+ "Could not read VM bundle configuration: %{public}@"
- "Failed to call sysctl("
- "Failed to validate hardware requirements - "
- "GB of Unified Memory."
- "GB of unified memory.\nThis device has "
- "This device does not meet hardware requirements for the VRE:\n  a Mac with Apple silicon and at least "
```
