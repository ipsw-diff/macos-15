## rapportd

> `/usr/libexec/rapportd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
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

-660.3.1.0.0
-  __TEXT.__text: 0xf0a50
+660.4.1.0.0
+  __TEXT.__text: 0xf0b30
   __TEXT.__auth_stubs: 0x2930
   __TEXT.__objc_stubs: 0xdec0
-  __TEXT.__objc_methlist: 0x6c3c
+  __TEXT.__objc_methlist: 0x6c54
   __TEXT.__objc_classname: 0x8f8
   __TEXT.__objc_methtype: 0x356f
-  __TEXT.__objc_methname: 0x1392e
-  __TEXT.__cstring: 0x237f1
+  __TEXT.__objc_methname: 0x1395a
+  __TEXT.__cstring: 0x23831
   __TEXT.__const: 0x2ff6
   __TEXT.__gcc_except_tab: 0x1e28
   __TEXT.__oslogstring: 0x105f

   __TEXT.__swift5_assocty: 0x90
   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_acfuncs: 0x3c
-  __TEXT.__unwind_info: 0x3538
+  __TEXT.__unwind_info: 0x3540
   __TEXT.__eh_frame: 0x27e0
   __DATA_CONST.__auth_got: 0x14a8
   __DATA_CONST.__got: 0x670
   __DATA_CONST.__auth_ptr: 0x398
-  __DATA_CONST.__const: 0x5368
-  __DATA_CONST.__cfstring: 0x5420
+  __DATA_CONST.__const: 0x5380
+  __DATA_CONST.__cfstring: 0x5440
   __DATA_CONST.__objc_classlist: 0x268
   __DATA_CONST.__objc_protolist: 0x148
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA_CONST.__objc_dictobj: 0x50
   __DATA_CONST.__objc_doubleobj: 0x10
-  __DATA.__objc_const: 0xc148
-  __DATA.__objc_selrefs: 0x4550
-  __DATA.__objc_ivar: 0xc94
+  __DATA.__objc_const: 0xc178
+  __DATA.__objc_selrefs: 0x4560
+  __DATA.__objc_ivar: 0xc98
   __DATA.__objc_data: 0x1a80
   __DATA.__data: 0x29a0
   __DATA.__bss: 0x23d0

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 5060
+  Functions: 5063
   Symbols:   1005
-  CStrings:  7710
+  CStrings:  7717
 
CStrings:
+ "660.4.1"
+ "First stale connection, creating ABC case\n"
+ "Stale Client Process"
+ "Stale-Client"
+ "TB,N,V_doneABC"
+ "_doneABC"
+ "doneABC"
+ "setDoneABC:"
- "660.3.1"
```
