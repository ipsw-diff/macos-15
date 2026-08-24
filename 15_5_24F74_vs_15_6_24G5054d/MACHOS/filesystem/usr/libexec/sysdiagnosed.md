## sysdiagnosed

> `/usr/libexec/sysdiagnosed`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1438.120.9.0.0
-  __TEXT.__text: 0x63a00
+1438.140.5.0.0
+  __TEXT.__text: 0x63bb0
   __TEXT.__auth_stubs: 0x1420
-  __TEXT.__objc_stubs: 0x8160
-  __TEXT.__objc_methlist: 0x3774
+  __TEXT.__objc_stubs: 0x8180
+  __TEXT.__objc_methlist: 0x377c
   __TEXT.__const: 0x1fc
-  __TEXT.__cstring: 0xe6d1
+  __TEXT.__cstring: 0xe6ea
   __TEXT.__oslogstring: 0x7f07
   __TEXT.__objc_classname: 0x336
   __TEXT.__objc_methtype: 0xde1
   __TEXT.__gcc_except_tab: 0x1230
-  __TEXT.__objc_methname: 0x8b33
+  __TEXT.__objc_methname: 0x8b50
   __TEXT.__unwind_info: 0x1020
   __DATA_CONST.__auth_got: 0xa20
   __DATA_CONST.__got: 0x328
   __DATA_CONST.__auth_ptr: 0x60
   __DATA_CONST.__const: 0x1140
-  __DATA_CONST.__cfstring: 0xfb00
+  __DATA_CONST.__cfstring: 0xfb80
   __DATA_CONST.__objc_classlist: 0x128
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x90
-  __DATA_CONST.__objc_arraydata: 0x1248
-  __DATA_CONST.__objc_arrayobj: 0x17b8
+  __DATA_CONST.__objc_arraydata: 0x1260
+  __DATA_CONST.__objc_arrayobj: 0x17e8
   __DATA_CONST.__objc_intobj: 0x228
   __DATA.__objc_const: 0x4990
-  __DATA.__objc_selrefs: 0x2350
+  __DATA.__objc_selrefs: 0x2358
   __DATA.__objc_ivar: 0x3fc
   __DATA.__objc_data: 0xb90
   __DATA.__data: 0x1a0

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsysdiagnose.dylib
   - /usr/lib/libtailspin.dylib
-  Functions: 1581
+  Functions: 1582
   Symbols:   437
-  CStrings:  4284
+  CStrings:  4289
 
CStrings:
+ "/usr/libexec/carkitd"
+ "GMSSelfService"
+ "getDarwinInitStatusContainer"
+ "gms_self_service.json"
+ "gms_self_service.txt"
+ "self-service"
- "/System/Library/PrivateFrameworks/CarKit.framework/Support/carkitd"
```
