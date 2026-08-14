## pccvre

> `/System/Library/SecurityResearch/usr/bin/pccvre`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_entry`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-199.120.5.0.0
-  __TEXT.__text: 0x1bd5dc
+199.120.6.0.0
+  __TEXT.__text: 0x1bd5e8
   __TEXT.__auth_stubs: 0x2ea0
   __TEXT.__objc_methlist: 0x184
   __TEXT.__const: 0x11078

   __TEXT.__eh_frame: 0xa234
   __DATA_CONST.__auth_got: 0x1750
   __DATA_CONST.__got: 0x8c8
-  __DATA_CONST.__auth_ptr: 0xe08
-  __DATA_CONST.__const: 0x89a0
+  __DATA_CONST.__auth_ptr: 0xf08
+  __DATA_CONST.__const: 0x8998
   __DATA_CONST.__cfstring: 0x19c0
   __DATA_CONST.__objc_classlist: 0xd0
   __DATA_CONST.__objc_protolist: 0x50

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftCore.dylib
   - /usr/lib/swift/libswiftCoreFoundation.dylib
-  - /usr/lib/swift/libswiftCryptoTokenKit.dylib
   - /usr/lib/swift/libswiftDarwin.dylib
   - /usr/lib/swift/libswiftDispatch.dylib
   - /usr/lib/swift/libswiftIOKit.dylib

   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 7077
-  Symbols:   1276
+  Symbols:   1275
   CStrings:  1355
 
Symbols:
- __swift_FORCE_LOAD_$_swiftCryptoTokenKit
Functions:
~ sub_10011cf00 -> sub_10011ceb8 : 6904 -> 6916
```
