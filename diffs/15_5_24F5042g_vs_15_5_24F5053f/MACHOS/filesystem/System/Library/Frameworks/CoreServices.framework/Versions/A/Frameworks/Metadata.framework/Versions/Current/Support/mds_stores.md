## mds_stores

> `/System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/Metadata.framework/Versions/Current/Support/mds_stores`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2333.41.1.3.0
-  __TEXT.__text: 0x34be4
-  __TEXT.__auth_stubs: 0x1b40
+2333.47.1.0.0
+  __TEXT.__text: 0x34be8
+  __TEXT.__auth_stubs: 0x1b50
   __TEXT.__objc_stubs: 0x21a0
   __TEXT.__init_offsets: 0x4
-  __TEXT.__objc_methlist: 0x151c
+  __TEXT.__objc_methlist: 0x152c
   __TEXT.__const: 0x280
   __TEXT.__cstring: 0x35fe
   __TEXT.__gcc_except_tab: 0x1d8
   __TEXT.__oslogstring: 0x1c81
-  __TEXT.__objc_methname: 0x26a2
+  __TEXT.__objc_methname: 0x26ab
   __TEXT.__objc_classname: 0x209
   __TEXT.__objc_methtype: 0x18ce
-  __TEXT.__unwind_info: 0xda8
-  __DATA_CONST.__auth_got: 0xdb0
+  __TEXT.__unwind_info: 0xdb0
+  __DATA_CONST.__auth_got: 0xdb8
   __DATA_CONST.__got: 0x360
   __DATA_CONST.__auth_ptr: 0x40
   __DATA_CONST.__const: 0x4698

   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x90
-  __DATA.__objc_const: 0x2018
-  __DATA.__objc_selrefs: 0xa28
+  __DATA.__objc_const: 0x2020
+  __DATA.__objc_selrefs: 0xa30
   __DATA.__objc_ivar: 0x1ec
   __DATA.__objc_data: 0x5a0
   __DATA.__data: 0xc90

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1599
+  Functions: 1600
   Symbols:   627
-  CStrings:  1288
+  CStrings:  1289
 
Functions:
~ sub_100021540 : 216 -> 4
+ sub_100021544
CStrings:
+ "indexPid"
```
