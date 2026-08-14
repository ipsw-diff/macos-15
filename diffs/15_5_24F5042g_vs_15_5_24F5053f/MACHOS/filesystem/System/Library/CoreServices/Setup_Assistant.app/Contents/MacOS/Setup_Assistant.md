## Setup Assistant

> `/System/Library/CoreServices/Setup Assistant.app/Contents/MacOS/Setup Assistant`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_assocty`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_protos`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_nlclslist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_data`

```diff

-7407.4.12.204.0
-  __TEXT.__text: 0x1801c0
+7407.4.13.0.0
+  __TEXT.__text: 0x18011c
   __TEXT.__auth_stubs: 0x2470
-  __TEXT.__objc_stubs: 0x21420
-  __TEXT.__objc_methlist: 0x147fc
+  __TEXT.__objc_stubs: 0x21400
+  __TEXT.__objc_methlist: 0x147dc
   __TEXT.__objc_classname: 0x1e2d
-  __TEXT.__objc_methname: 0x31999
-  __TEXT.__objc_methtype: 0x5f16
-  __TEXT.__cstring: 0x31f70
+  __TEXT.__objc_methname: 0x3194b
+  __TEXT.__objc_methtype: 0x5f13
+  __TEXT.__cstring: 0x31ec0
   __TEXT.__ustring: 0x1ba
-  __TEXT.__const: 0x48b4
+  __TEXT.__const: 0x4914
   __TEXT.__gcc_except_tab: 0x15f8
   __TEXT.__dlopen_cstrs: 0xb2
   __TEXT.__oslogstring: 0x57

   __TEXT.__swift5_assocty: 0x240
   __TEXT.__constg_swiftt: 0x225c
   __TEXT.__swift5_builtin: 0x17c
-  __TEXT.__swift5_fieldmd: 0x1bc8
-  __TEXT.__swift5_proto: 0x1f0
-  __TEXT.__swift5_types: 0x21c
-  __TEXT.__swift_as_entry: 0x504
+  __TEXT.__swift5_fieldmd: 0x1bec
+  __TEXT.__swift5_proto: 0x208
+  __TEXT.__swift5_types: 0x22c
+  __TEXT.__swift_as_entry: 0x500
   __TEXT.__swift_as_ret: 0x34c
   __TEXT.__swift5_capture: 0x8e8
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__unwind_info: 0x63c0
-  __TEXT.__eh_frame: 0x3db8
+  __TEXT.__unwind_info: 0x63b8
+  __TEXT.__eh_frame: 0x3da0
   __DATA_CONST.__auth_got: 0x1248
   __DATA_CONST.__got: 0x1140
-  __DATA_CONST.__auth_ptr: 0x5d0
-  __DATA_CONST.__const: 0xaa30
-  __DATA_CONST.__cfstring: 0x1d140
+  __DATA_CONST.__auth_ptr: 0x5a0
+  __DATA_CONST.__const: 0xa9f8
+  __DATA_CONST.__cfstring: 0x1d100
   __DATA_CONST.__objc_classlist: 0x900
   __DATA_CONST.__objc_nlclslist: 0x8
   __DATA_CONST.__objc_catlist: 0x40

   __DATA_CONST.__objc_arrayobj: 0x258
   __DATA_CONST.__objc_dictobj: 0x208
   __DATA_CONST.__objc_doubleobj: 0x20
-  __DATA.__objc_const: 0x70b68
-  __DATA.__objc_selrefs: 0xb428
+  __DATA.__objc_const: 0x70af0
+  __DATA.__objc_selrefs: 0xb420
   __DATA.__objc_ivar: 0x159c
   __DATA.__objc_data: 0x5768
-  __DATA.__data: 0x7940
-  __DATA.__bss: 0x2909
+  __DATA.__data: 0x7960
+  __DATA.__bss: 0x2c09
   __DATA.__common: 0x8d8
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/AVKit.framework/Versions/A/AVKit

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 10174
+  Functions: 10181
   Symbols:   1300
-  CStrings:  14638
+  CStrings:  14635
 
CStrings:
+ "Removed terms cookie with success: "
+ "Skipping location services because we are in non-first user minibuddy"
+ "Skipping time zone because automatic time zone setting is already set"
+ "Skipping time zone because we are in non-first user minibuddy"
+ "createTeslaUsersWithInfo:completionBlock:"
+ "mbsaConnection"
+ "v32@0:8@\"NSArray\"16@?<v@?BB>24"
- "-[PreloginTasksManager runPreUserSwitchTasks]_block_invoke_7"
- "Cloud config specifies to skip License, removing TOS cookie."
- "Removed TOS cookie with success: %i"
- "Showing time zone because cloud configuration created the user"
- "Showing time zone because cloud configuration skipped location services"
- "Skipping time zone because automatic time zone setting is already set (1)"
- "Skipping time zone because automatic time zone setting is already set (2)"
- "createTeslaUsersWithInfo:prepareFirstAdminForResume:completionBlock:"
- "shouldPrepareTeslaUserForResumePostUserSessionSwap"
- "v36@0:8@\"NSArray\"16B24@?<v@?BB>28"
```
