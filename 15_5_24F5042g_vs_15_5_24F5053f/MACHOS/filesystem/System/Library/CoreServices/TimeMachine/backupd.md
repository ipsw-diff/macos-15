## backupd

> `/System/Library/CoreServices/TimeMachine/backupd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2432.0.0.0.0
-  __TEXT.__text: 0x1742b4
+2433.0.0.0.0
+  __TEXT.__text: 0x1741c4
   __TEXT.__auth_stubs: 0x3cc0
   __TEXT.__objc_stubs: 0x77a0
   __TEXT.__objc_methlist: 0x38f0
   __TEXT.__const: 0x7e30
   __TEXT.__gcc_except_tab: 0xd10
   __TEXT.__objc_methname: 0xa917
-  __TEXT.__cstring: 0x1364c
+  __TEXT.__cstring: 0x1361c
   __TEXT.__objc_classname: 0x83a
   __TEXT.__objc_methtype: 0x3518
   __TEXT.__constg_swiftt: 0x3060

   __TEXT.__eh_frame: 0xb4fc
   __DATA_CONST.__auth_got: 0x1e78
   __DATA_CONST.__got: 0xf78
-  __DATA_CONST.__auth_ptr: 0xaf8
+  __DATA_CONST.__auth_ptr: 0xb10
   __DATA_CONST.__const: 0x90d8
   __DATA_CONST.__cfstring: 0x5b40
   __DATA_CONST.__objc_classlist: 0x2d0

   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 6096
   Symbols:   1693
-  CStrings:  3953
+  CStrings:  3952
 
Functions:
~ sub_1001092ec : 2024 -> 1784
CStrings:
+ "Completing backup"
- "Finalizing completed backup"
- "Finished finalizing completed backup"
```
