## diskarbitrationd

> `/usr/libexec/diskarbitrationd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-490.120.2.0.0
-  __TEXT.__text: 0x1b5e0
-  __TEXT.__auth_stubs: 0x16d0
+490.120.6.0.0
+  __TEXT.__text: 0x1b71c
+  __TEXT.__auth_stubs: 0x16e0
   __TEXT.__objc_stubs: 0x520
   __TEXT.__init_offsets: 0x8
   __TEXT.__objc_methlist: 0xc8

   __TEXT.__objc_methname: 0x475
   __TEXT.__objc_methtype: 0x102
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x5f8
-  __DATA_CONST.__auth_got: 0xb78
+  __TEXT.__unwind_info: 0x600
+  __DATA_CONST.__auth_got: 0xb80
   __DATA_CONST.__got: 0x140
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__const: 0xd90

   __DATA.__objc_ivar: 0xc
   __DATA.__objc_data: 0x50
   __DATA.__data: 0x178
-  __DATA.__bss: 0xde8
+  __DATA.__bss: 0xdf0
   __DATA.__common: 0xc8
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/FSKit.framework/Versions/A/FSKit

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
-  Functions: 521
-  Symbols:   416
+  Functions: 524
+  Symbols:   417
   CStrings:  674
 
Symbols:
+ _fstatfs_ext
+ _statfs_ext
- _fstatfs
```
