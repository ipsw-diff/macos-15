## mount

> `/sbin/mount`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

-737.100.3.0.0
-  __TEXT.__text: 0x37a4
+737.140.4.0.0
+  __TEXT.__text: 0x37fc
   __TEXT.__auth_stubs: 0x420
-  __TEXT.__objc_stubs: 0x540
+  __TEXT.__objc_stubs: 0x560
   __TEXT.__const: 0x38
-  __TEXT.__gcc_except_tab: 0x1b8
-  __TEXT.__cstring: 0xa03
+  __TEXT.__gcc_except_tab: 0x1d4
+  __TEXT.__cstring: 0xa1b
   __TEXT.__oslogstring: 0xc
-  __TEXT.__objc_methname: 0x437
+  __TEXT.__objc_methname: 0x441
   __TEXT.__unwind_info: 0xf0
   __DATA_CONST.__auth_got: 0x220
   __DATA_CONST.__got: 0xb0

   __DATA_CONST.__const: 0x3d8
   __DATA_CONST.__cfstring: 0x180
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA.__objc_selrefs: 0x150
+  __DATA.__objc_selrefs: 0x158
   __DATA.__common: 0x14
   __DATA.__bss: 0x1
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libobjc.A.dylib
   Functions: 55
   Symbols:   94
-  CStrings:  170
+  CStrings:  172
 
Functions:
~ sub_100000b40 : 4576 -> 4664
CStrings:
+ "Module %s is disabled!\n"
+ "isEnabled"
```
