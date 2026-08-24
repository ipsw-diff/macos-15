## SCNSceneLoader

> `/System/Library/Frameworks/SceneKit.framework/Versions/Current/XPCServices/SCNSceneLoader.xpc/Contents/MacOS/SCNSceneLoader`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-603.500.0.0.0
-  __TEXT.__text: 0x3f4
-  __TEXT.__auth_stubs: 0xa0
-  __TEXT.__objc_stubs: 0x1a0
-  __TEXT.__objc_methlist: 0x178
+603.600.0.0.0
+  __TEXT.__text: 0x4c0
+  __TEXT.__auth_stubs: 0xc0
+  __TEXT.__objc_stubs: 0x240
+  __TEXT.__objc_methlist: 0x164
   __TEXT.__const: 0x40
   __TEXT.__objc_classname: 0x55
-  __TEXT.__objc_methname: 0x2a7
-  __TEXT.__objc_methtype: 0x159
+  __TEXT.__objc_methname: 0x2ed
+  __TEXT.__objc_methtype: 0x149
   __TEXT.__cstring: 0xb4
-  __TEXT.__unwind_info: 0x70
-  __DATA_CONST.__auth_got: 0x58
-  __DATA_CONST.__got: 0x38
+  __TEXT.__unwind_info: 0x68
+  __DATA_CONST.__auth_got: 0x68
+  __DATA_CONST.__got: 0x48
   __DATA_CONST.__cfstring: 0xa0
   __DATA_CONST.__objc_classlist: 0x10
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA.__objc_const: 0x2b0
-  __DATA.__objc_selrefs: 0x120
+  __DATA.__objc_const: 0x2a8
+  __DATA.__objc_selrefs: 0x140
   __DATA.__objc_data: 0xa0
   __DATA.__data: 0x120
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /System/Library/Frameworks/SceneKit.framework/Versions/A/SceneKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 4
-  Symbols:   24
-  CStrings:  70
+  Functions: 3
+  Symbols:   28
+  CStrings:  72
 
Symbols:
+ _OBJC_CLASS_$_NSMutableArray
+ _OBJC_CLASS_$_NSNumber
+ _objc_alloc
+ _sandbox_extension_consume
+ _sandbox_extension_release
- _sandbox_consume_fs_extension
Functions:
~ sub_100000c14 : 352 -> 948
CStrings:
+ "addObject:"
+ "count"
+ "initWithCapacity:"
+ "loadSceneAtURL:consumingExtensions:options:withReply:"
+ "longLongValue"
+ "numberWithLongLong:"
+ "v48@0:8@\"NSURL\"16@\"NSArray\"24@\"NSDictionary\"32@?<v@?@\"NSData\"@\"NSError\">40"
+ "v48@0:8@16@24@32@?40"
- "consumeExtensions:"
- "loadSceneAtURL:options:withReply:"
- "v24@0:8@\"NSArray\"16"
- "v24@0:8@16"
- "v40@0:8@\"NSURL\"16@\"NSDictionary\"24@?<v@?@\"NSData\"@\"NSError\">32"
- "v40@0:8@16@24@?32"
```
