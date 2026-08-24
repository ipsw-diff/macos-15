## newfs_fskit

> `/sbin/newfs_fskit`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

-737.100.3.0.0
-  __TEXT.__text: 0x1bd0
+737.140.4.0.0
+  __TEXT.__text: 0x1c28
   __TEXT.__auth_stubs: 0x190
-  __TEXT.__objc_stubs: 0x540
+  __TEXT.__objc_stubs: 0x560
   __TEXT.__const: 0x20
-  __TEXT.__gcc_except_tab: 0x1b8
-  __TEXT.__cstring: 0x3fb
+  __TEXT.__gcc_except_tab: 0x1d4
+  __TEXT.__cstring: 0x413
   __TEXT.__oslogstring: 0xc
-  __TEXT.__objc_methname: 0x437
+  __TEXT.__objc_methname: 0x441
   __TEXT.__unwind_info: 0xa0
   __DATA_CONST.__auth_got: 0xd8
   __DATA_CONST.__got: 0x98
   __DATA_CONST.__const: 0x180
   __DATA_CONST.__cfstring: 0x180
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA.__objc_selrefs: 0x150
+  __DATA.__objc_selrefs: 0x158
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/FSKit.framework/Versions/A/FSKit
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libobjc.A.dylib
   Functions: 31
   Symbols:   49
-  CStrings:  79
+  CStrings:  81
 
Functions:
~ sub_100000988 : 4576 -> 4664
CStrings:
+ "Module %s is disabled!\n"
+ "isEnabled"
```
