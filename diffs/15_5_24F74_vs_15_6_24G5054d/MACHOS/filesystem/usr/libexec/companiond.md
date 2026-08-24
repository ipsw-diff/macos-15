## companiond

> `/usr/libexec/companiond`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__cstring`
- `__TEXT.__oslogstring`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_capture`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_proto`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_ivar`
- `__DATA.__objc_data`

```diff

-156.50.26.0.0
-  __TEXT.__text: 0x21028
+156.60.26.0.0
+  __TEXT.__text: 0x21038
   __TEXT.__auth_stubs: 0xeb0
   __TEXT.__objc_stubs: 0x27e0
   __TEXT.__objc_methlist: 0x21d0
-  __TEXT.__const: 0x224
-  __TEXT.__gcc_except_tab: 0xb80
+  __TEXT.__objc_methname: 0x3d58
   __TEXT.__cstring: 0x1681
-  __TEXT.__oslogstring: 0x173d
   __TEXT.__objc_classname: 0x659
   __TEXT.__objc_methtype: 0xff6
-  __TEXT.__objc_methname: 0x3d58
+  __TEXT.__const: 0x2ac
+  __TEXT.__gcc_except_tab: 0xb80
+  __TEXT.__oslogstring: 0x173d
   __TEXT.__ustring: 0x40
   __TEXT.__swift5_typeref: 0x1c4
-  __TEXT.__swift5_capture: 0xe0
+  __TEXT.__swift5_fieldmd: 0x130
   __TEXT.__constg_swiftt: 0x2bc
   __TEXT.__swift5_reflstr: 0xf6
-  __TEXT.__swift5_fieldmd: 0x130
   __TEXT.__swift5_builtin: 0x14
+  __TEXT.__swift5_capture: 0xe0
+  __TEXT.__swift5_proto: 0xc
   __TEXT.__swift5_types: 0x1c
   __TEXT.__swift_as_entry: 0x20
   __TEXT.__swift_as_ret: 0x20
-  __TEXT.__swift5_proto: 0xc
-  __TEXT.__unwind_info: 0xb18
+  __TEXT.__unwind_info: 0xb20
   __TEXT.__eh_frame: 0x3e0
   __DATA_CONST.__auth_got: 0x768
   __DATA_CONST.__got: 0x460

   __DATA.__objc_selrefs: 0xeb0
   __DATA.__objc_ivar: 0x2f8
   __DATA.__objc_data: 0x1278
-  __DATA.__data: 0x878
+  __DATA.__data: 0x808
   __DATA.__bss: 0x1c0
   __DATA.__common: 0x8
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
```
