## syspolicyd

> `/usr/libexec/syspolicyd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__dof_security_`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-620.120.4.0.0
-  __TEXT.__text: 0xb5418
-  __TEXT.__auth_stubs: 0x29d0
+620.120.7.0.0
+  __TEXT.__text: 0xb5688
+  __TEXT.__auth_stubs: 0x29f0
   __TEXT.__objc_stubs: 0x9b60
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x5014

   __TEXT.__swift5_proto: 0x40
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__dof_security_: 0x325
-  __TEXT.__unwind_info: 0x23b8
+  __TEXT.__unwind_info: 0x23c0
   __TEXT.__eh_frame: 0x248
-  __DATA_CONST.__auth_got: 0x1500
+  __DATA_CONST.__auth_got: 0x1510
   __DATA_CONST.__got: 0x830
   __DATA_CONST.__auth_ptr: 0x1d8
   __DATA_CONST.__const: 0x3d28

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 3425
-  Symbols:   1014
+  Functions: 3427
+  Symbols:   1016
   CStrings:  5407
 
Symbols:
+ ___exp10
+ _log10
CStrings:
+ "GkProtectionStatus2"
+ "iTerm.app"
- "GkProtectionStatus"
- "iTerm2.app"
```
