## amfid

> `/usr/libexec/amfid`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-938.120.13.0.0
+938.140.13.0.0
   __TEXT.__text: 0x16230
   __TEXT.__auth_stubs: 0x1170
   __TEXT.__objc_stubs: 0x700

   __TEXT.__objc_methlist: 0x35c
   __TEXT.__const: 0x93f
   __TEXT.__oslogstring: 0x1022
-  __TEXT.__cstring: 0x1233
+  __TEXT.__cstring: 0x1283
   __TEXT.__gcc_except_tab: 0x35c
   __TEXT.__objc_classname: 0x57
   __TEXT.__objc_methname: 0x80b

   __DATA.__objc_selrefs: 0x2e0
   __DATA.__objc_ivar: 0x8
   __DATA.__objc_data: 0x220
-  __DATA.__data: 0x678
+  __DATA.__data: 0x698
   __DATA.__bss: 0x838
   __DATA.__common: 0xc0
   __RESTRICT.__restrict: 0x0

   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 496
   Symbols:   446
-  CStrings:  386
+  CStrings:  389
 
CStrings:
+ "64555.39"
+ "com.apple.dt.instruments.dtarbiter.xpc"
+ "com.apple.dt.instruments.dtsecurity.xpc"
```
