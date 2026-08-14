## vrevm

> `/System/Library/SecurityResearch/usr/bin/vrevm`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_entry`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-199.120.6.0.0
-  __TEXT.__text: 0x658c0
-  __TEXT.__auth_stubs: 0x1aa0
+199.120.7.0.0
+  __TEXT.__text: 0x641b4
+  __TEXT.__auth_stubs: 0x1a70
   __TEXT.__objc_methlist: 0x18c
-  __TEXT.__const: 0x2fce
-  __TEXT.__cstring: 0x20f2
-  __TEXT.__constg_swiftt: 0xb44
-  __TEXT.__swift5_typeref: 0xcd6
-  __TEXT.__swift5_builtin: 0xb4
-  __TEXT.__swift5_reflstr: 0xa1b
-  __TEXT.__swift5_fieldmd: 0x116c
+  __TEXT.__const: 0x2f8e
+  __TEXT.__cstring: 0x20a2
+  __TEXT.__constg_swiftt: 0xac4
+  __TEXT.__swift5_typeref: 0xc6e
+  __TEXT.__swift5_builtin: 0x64
+  __TEXT.__swift5_reflstr: 0x8fb
+  __TEXT.__swift5_fieldmd: 0xfc4
   __TEXT.__swift5_assocty: 0x138
   __TEXT.__oslogstring: 0x785
   __TEXT.__objc_methname: 0xafe
   __TEXT.__swift5_proto: 0x31c
-  __TEXT.__swift5_types: 0x118
+  __TEXT.__swift5_types: 0x108
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__swift5_capture: 0x1bc
   __TEXT.__swift_as_entry: 0x4c
   __TEXT.__swift_as_ret: 0x2c
   __TEXT.__swift5_entry: 0x8
+  __TEXT.__swift5_capture: 0xbc
   __TEXT.__objc_classname: 0x22
   __TEXT.__objc_methtype: 0x15a
-  __TEXT.__unwind_info: 0x12e0
+  __TEXT.__unwind_info: 0x1268
   __TEXT.__eh_frame: 0x239c
-  __DATA_CONST.__auth_got: 0xd50
+  __DATA_CONST.__auth_got: 0xd38
   __DATA_CONST.__got: 0x4e0
-  __DATA_CONST.__auth_ptr: 0x590
-  __DATA_CONST.__const: 0x2310
+  __DATA_CONST.__auth_ptr: 0x548
+  __DATA_CONST.__const: 0x1d70
   __DATA_CONST.__objc_classlist: 0x30
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA.__objc_const: 0x4b0
   __DATA.__objc_selrefs: 0x460
   __DATA.__objc_data: 0x2a0
-  __DATA.__data: 0x1980
+  __DATA.__data: 0x1960
   __DATA.__common: 0x1e0
   __DATA.__bss: 0x6380
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1421
-  Symbols:   724
-  CStrings:  435
+  Functions: 1369
+  Symbols:   719
+  CStrings:  434
 
Symbols:
- _$sBi8_WV
- _$ss4Int8VMn
- _free
- _os_log_copy_message_string
- _os_log_set_hook
CStrings:
- "v20@?0C8^{os_log_message_s=QQQ**{timeval=qi}{timezone=ii}QQI**Q*Q**ICBQ*CC*}12"
```
