## com.apple.dock.external.extra.x86_64

> `/System/Library/CoreServices/Dock.app/Contents/XPCServices/com.apple.dock.external.extra.x86_64.xpc/Contents/MacOS/com.apple.dock.external.extra.x86_64`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2341.4.7.0.0
-  __TEXT.__text: 0x1ac7
-  __TEXT.__stubs: 0x1b0
+2341.4.8.0.0
+  __TEXT.__text: 0x1a77
+  __TEXT.__stubs: 0x19e
   __TEXT.__const: 0x80
   __TEXT.__objc_methname: 0x717
-  __TEXT.__cstring: 0x4e6
+  __TEXT.__cstring: 0x497
   __TEXT.__objc_classname: 0x3f
   __TEXT.__objc_methtype: 0x1fc
   __TEXT.__ustring: 0x3e
   __TEXT.__gcc_except_tab: 0x138
   __TEXT.__unwind_info: 0x140
-  __DATA_CONST.__got: 0x2f0
+  __DATA_CONST.__got: 0x2d8
   __DATA_CONST.__const: 0xc0
-  __DATA_CONST.__cfstring: 0x3c0
+  __DATA_CONST.__cfstring: 0x3a0
   __DATA_CONST.__objc_classlist: 0x10
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 46
-  Symbols:   103
-  CStrings:  208
+  Symbols:   100
+  CStrings:  206
 
Symbols:
- ___error
- _sandbox_extension_consume
- _strerror
Functions:
~ sub_1000023d1 : 653 -> 573
CStrings:
- "Error consuming sandbox extension: %d: %s"
- "app_data_container_sandbox_extension"
```
