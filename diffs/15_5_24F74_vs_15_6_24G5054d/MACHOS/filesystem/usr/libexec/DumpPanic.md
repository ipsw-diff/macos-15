## DumpPanic

> `/usr/libexec/DumpPanic`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 326.100.5.0.0
-  __TEXT.__text: 0x27384
+  __TEXT.__text: 0x272f8
   __TEXT.__auth_stubs: 0xdf0
   __TEXT.__objc_stubs: 0x1e00
   __TEXT.__objc_methlist: 0x640
-  __TEXT.__const: 0x3c2
+  __TEXT.__const: 0x2b2
   __TEXT.__cstring: 0x2a52
   __TEXT.__objc_methname: 0x18e7
   __TEXT.__constg_swiftt: 0x70

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 482
+  Functions: 480
   Symbols:   323
   CStrings:  1222
 
```
