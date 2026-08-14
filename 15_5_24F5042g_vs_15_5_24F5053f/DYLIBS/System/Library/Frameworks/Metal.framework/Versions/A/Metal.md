## Metal

> `/System/Library/Frameworks/Metal.framework/Versions/A/Metal`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-368.11.4.0.0
-  __TEXT.__text: 0x1a56a4
+368.12.0.0.0
+  __TEXT.__text: 0x1a56bc
   __TEXT.__auth_stubs: 0x1c50
-  __TEXT.__objc_methlist: 0x182d4
+  __TEXT.__objc_methlist: 0x18304
   __TEXT.__gcc_except_tab: 0x92d4
   __TEXT.__cstring: 0x1f813
   __TEXT.__const: 0x1f350

   __TEXT.__unwind_info: 0x6f60
   __TEXT.__eh_frame: 0x78
   __TEXT.__objc_classname: 0x31cc
-  __TEXT.__objc_methname: 0x2ef00
+  __TEXT.__objc_methname: 0x2ef2b
   __TEXT.__objc_methtype: 0x18cda
   __TEXT.__objc_stubs: 0x14240
   __DATA_CONST.__got: 0x870

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x2d0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7b50
+  __DATA_CONST.__objc_selrefs: 0x7b60
   __DATA_CONST.__objc_protorefs: 0x60
   __DATA_CONST.__objc_superrefs: 0x9c0
   __AUTH_CONST.__auth_got: 0xe40
   __AUTH_CONST.__const: 0x6058
   __AUTH_CONST.__cfstring: 0x116c0
-  __AUTH_CONST.__objc_const: 0x36618
+  __AUTH_CONST.__objc_const: 0x36648
   __AUTH_CONST.__objc_intobj: 0x168
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH.__objc_data: 0x6a90

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 10935
-  Symbols:   20802
-  CStrings:  11912
+  Functions: 10937
+  Symbols:   20803
+  CStrings:  11914
 
Symbols:
+ -[_MTLDevice commandQueueLimit]
+ -[_MTLDevice currentCommandQueueCount]
+ GCC_except_table783
+ GCC_except_table786
+ GCC_except_table794
+ GCC_except_table800
- GCC_except_table720
- GCC_except_table721
- GCC_except_table781
- GCC_except_table784
- GCC_except_table792
CStrings:
+ "02:34:00"
+ "Apr  4 2025"
+ "Apr  4 2025 02:34:00"
+ "commandQueueLimit"
+ "currentCommandQueueCount"
- "05:45:04"
- "Mar 18 2025"
- "Mar 18 2025 05:45:04"
```
