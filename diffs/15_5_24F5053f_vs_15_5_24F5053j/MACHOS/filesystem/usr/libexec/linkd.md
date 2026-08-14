## linkd

> `/usr/libexec/linkd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA.__objc_data`

```diff

-227.18.0.0.0
-  __TEXT.__text: 0x123c10
-  __TEXT.__auth_stubs: 0x2790
+227.19.0.0.0
+  __TEXT.__text: 0x124188
+  __TEXT.__auth_stubs: 0x27c0
   __TEXT.__objc_stubs: 0xa0
   __TEXT.__objc_methlist: 0xddc
   __TEXT.__swift5_entry: 0x8
   __TEXT.__const: 0x46fc
-  __TEXT.__cstring: 0x4994
+  __TEXT.__cstring: 0x49a4
   __TEXT.__constg_swiftt: 0x2054
   __TEXT.__swift5_typeref: 0x3740
   __TEXT.__swift5_builtin: 0x190
   __TEXT.__swift5_reflstr: 0x1a45
-  __TEXT.__swift5_fieldmd: 0x1ccc
+  __TEXT.__swift5_fieldmd: 0x1cd8
   __TEXT.__swift5_assocty: 0x520
-  __TEXT.__objc_methname: 0x3057
-  __TEXT.__swift5_capture: 0x10a0
+  __TEXT.__objc_methname: 0x3071
+  __TEXT.__swift5_capture: 0x1090
   __TEXT.__swift5_proto: 0x418
   __TEXT.__swift5_types: 0x228
   __TEXT.__objc_classname: 0x1b0
   __TEXT.__objc_methtype: 0xea5
-  __TEXT.__oslogstring: 0x2c0f
+  __TEXT.__oslogstring: 0x2caf
   __TEXT.__swift_as_entry: 0x3b8
   __TEXT.__swift5_protos: 0x88
   __TEXT.__swift_as_ret: 0x398
   __TEXT.__swift5_mpenum: 0x20
-  __TEXT.__unwind_info: 0x4f68
-  __TEXT.__eh_frame: 0xcce4
-  __DATA_CONST.__auth_got: 0x13d0
+  __TEXT.__unwind_info: 0x5398
+  __TEXT.__eh_frame: 0xcd24
+  __DATA_CONST.__auth_got: 0x13e8
   __DATA_CONST.__got: 0x908
   __DATA_CONST.__auth_ptr: 0xb08
-  __DATA_CONST.__const: 0x61c0
+  __DATA_CONST.__const: 0x6198
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__objc_classlist: 0xd8
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x88
-  __DATA.__objc_const: 0x2290
-  __DATA.__objc_selrefs: 0xcb0
+  __DATA.__objc_const: 0x22b0
+  __DATA.__objc_selrefs: 0xcb8
   __DATA.__objc_data: 0x940
-  __DATA.__data: 0x5268
+  __DATA.__data: 0x5258
   __DATA.__common: 0xe08
   __DATA.__bss: 0x5270
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 6643
-  Symbols:   1088
-  CStrings:  1179
+  Functions: 6646
+  Symbols:   1091
+  CStrings:  1184
 
Symbols:
+ _$s10Foundation12CharacterSetV22whitespacesAndNewlinesACvgZ
+ _$s10Foundation12CharacterSetVMa
+ _$s12LinkMetadata22AssistantSchemaLibraryC04loadE0ACyKFZ
+ _$sSy10FoundationE18trimmingCharacters2inSSAA12CharacterSetV_tF
- _$s12LinkMetadata22AssistantSchemaLibraryC04loadE06domainACSS_tKFZ
CStrings:
+ "Evaluating stream reference at %s"
+ "Failed to remove file %@"
+ "Invalid identifier detected: path:%s identifier:%s"
+ "Invalid streamURL detected, removing %s"
+ "LinkProgrammaticInterface-227.19"
+ "library"
+ "stringByStandardizingPath"
- "Invalid streamURL detected %s"
- "LinkProgrammaticInterface-227.18"
```
