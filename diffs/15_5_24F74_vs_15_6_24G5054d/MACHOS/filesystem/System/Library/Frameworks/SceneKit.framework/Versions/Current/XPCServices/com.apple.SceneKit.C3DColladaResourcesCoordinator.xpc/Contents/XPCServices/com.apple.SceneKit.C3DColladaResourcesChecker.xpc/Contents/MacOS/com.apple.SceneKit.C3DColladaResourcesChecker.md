## com.apple.SceneKit.C3DColladaResourcesChecker

> `/System/Library/Frameworks/SceneKit.framework/Versions/Current/XPCServices/com.apple.SceneKit.C3DColladaResourcesCoordinator.xpc/Contents/XPCServices/com.apple.SceneKit.C3DColladaResourcesChecker.xpc/Contents/MacOS/com.apple.SceneKit.C3DColladaResourcesChecker`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-603.500.0.0.0
-  __TEXT.__text: 0xc74
-  __TEXT.__auth_stubs: 0x290
+603.600.0.0.0
+  __TEXT.__text: 0xcd4
+  __TEXT.__auth_stubs: 0x2b0
   __TEXT.__objc_stubs: 0x80
   __TEXT.__const: 0x80
   __TEXT.__cstring: 0x433
-  __TEXT.__oslogstring: 0x190
+  __TEXT.__oslogstring: 0x194
   __TEXT.__objc_methname: 0x3e
-  __TEXT.__unwind_info: 0xa0
-  __DATA_CONST.__auth_got: 0x150
+  __TEXT.__unwind_info: 0xa8
+  __DATA_CONST.__auth_got: 0x160
   __DATA_CONST.__got: 0x50
   __DATA_CONST.__const: 0xa0
   __DATA_CONST.__cfstring: 0x360

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 23
-  Symbols:   57
+  Symbols:   59
   CStrings:  47
 
Symbols:
+ ___error
+ _sandbox_extension_consume
+ _sandbox_extension_release
+ _strerror
- _sandbox_consume_fs_extension
- _sandbox_release_fs_extension
Functions:
~ sub_100000ba8 : 612 -> 660
~ sub_1000014ec -> sub_10000151c : 64 -> 112
CStrings:
+ "Error: Could not consume extension for the resource (%s)"
+ "Welcome to SceneKit 603.600 (Jun  3 2025 05:59:01)"
- "Error: Could not consume extension for the resource."
- "Welcome to SceneKit 603.500 (Apr 19 2025 03:54:58)"
```
