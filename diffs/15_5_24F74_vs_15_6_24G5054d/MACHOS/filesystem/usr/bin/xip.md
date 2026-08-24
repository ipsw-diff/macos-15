## xip

> `/usr/bin/xip`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA.__data`

```diff

-860.0.0.0.0
-  __TEXT.__text: 0xb84
-  __TEXT.__auth_stubs: 0x190
-  __TEXT.__objc_stubs: 0x4e0
-  __TEXT.__const: 0x40
-  __TEXT.__gcc_except_tab: 0x84
-  __TEXT.__cstring: 0x303
-  __TEXT.__objc_methname: 0x35c
+860.140.3.0.0
+  __TEXT.__text: 0xc5c
+  __TEXT.__auth_stubs: 0x1d0
+  __TEXT.__objc_stubs: 0x520
+  __TEXT.__const: 0x48
+  __TEXT.__gcc_except_tab: 0x90
+  __TEXT.__cstring: 0x366
+  __TEXT.__objc_methname: 0x39b
   __TEXT.__unwind_info: 0x78
-  __DATA_CONST.__auth_got: 0xd8
+  __DATA_CONST.__auth_got: 0xf8
   __DATA_CONST.__got: 0x78
   __DATA_CONST.__const: 0x30
-  __DATA_CONST.__cfstring: 0x60
+  __DATA_CONST.__cfstring: 0x80
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA.__objc_selrefs: 0x138
+  __DATA.__objc_selrefs: 0x148
   __DATA.__data: 0xc0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 9
-  Symbols:   45
-  CStrings:  63
+  Symbols:   49
+  CStrings:  70
 
Symbols:
+ _NSHomeDirectory
+ _NSTemporaryDirectory
+ _sandbox_free_error
+ _sandbox_init_with_parameters
Functions:
~ sub_100000998 -> sub_1000009e8 : 2528 -> 2744
CStrings:
+ "Failed to initialize xip sandbox.\n"
+ "HOME"
+ "TMPDIR"
+ "com.apple.xip"
+ "fileSystemRepresentation"
+ "group.com.apple.xip.PKSignedContainer"
+ "setSecureAppGroupContainerIdentifier:"
```
