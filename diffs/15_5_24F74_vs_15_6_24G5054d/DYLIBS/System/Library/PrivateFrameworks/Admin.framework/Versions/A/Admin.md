## Admin

> `/System/Library/PrivateFrameworks/Admin.framework/Versions/A/Admin`

```diff

-948.3.4.0.0
-  __TEXT.__text: 0x10dc8
+948.5.1.0.0
+  __TEXT.__text: 0x10f1c
   __TEXT.__auth_stubs: 0xbc0
-  __TEXT.__objc_methlist: 0x1a50
-  __TEXT.__cstring: 0x2f96
+  __TEXT.__objc_methlist: 0x1a60
+  __TEXT.__cstring: 0x315f
   __TEXT.__const: 0x34
   __TEXT.__gcc_except_tab: 0x30
   __TEXT.__oslogstring: 0x1bd
   __TEXT.__unwind_info: 0x620
   __TEXT.__objc_classname: 0x1a1
-  __TEXT.__objc_methname: 0x3784
+  __TEXT.__objc_methname: 0x37de
   __TEXT.__objc_methtype: 0x5d8
-  __TEXT.__objc_stubs: 0x29c0
+  __TEXT.__objc_stubs: 0x2a40
   __DATA_CONST.__got: 0x1a8
   __DATA_CONST.__const: 0x40
   __DATA_CONST.__objc_classlist: 0xa8
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1330
+  __DATA_CONST.__objc_selrefs: 0x1358
   __DATA_CONST.__objc_superrefs: 0x60
   __AUTH_CONST.__auth_got: 0x5f0
   __AUTH_CONST.__const: 0x1b0
-  __AUTH_CONST.__cfstring: 0x2760
+  __AUTH_CONST.__cfstring: 0x2880
   __AUTH_CONST.__objc_const: 0x11a8
   __AUTH.__objc_data: 0x690
   __DATA.__objc_ivar: 0x8c

   - /usr/lib/libcups.2.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libodfde.dylib
-  Functions: 583
-  Symbols:   1380
-  CStrings:  1163
+  Functions: 584
+  Symbols:   1385
+  CStrings:  1176
 
Symbols:
+ -[User isHomeDirValid]
+ _objc_msgSend$fileOwnerAccountID
+ _objc_msgSend$isAbsolutePath
+ _objc_msgSend$objectAtIndexedSubscript:
+ _objc_msgSend$pathComponents
Functions:
+ -[User isHomeDirValid]
CStrings:
+ "Could not retrieve attributes of home folder (%@)."
+ "Could not retrieve owner attribute of home folder."
+ "Home directory has invalid owner."
+ "Home directory path does not resolve to an absolute path."
+ "Home directory path is not in the expected location (invalid component count)."
+ "Home directory path is not in the expected location (not in /)."
+ "Home directory path is not in the expected location (not in /Users)."
+ "Users"
+ "fileOwnerAccountID"
+ "isAbsolutePath"
+ "isHomeDirValid"
+ "objectAtIndexedSubscript:"
+ "pathComponents"
```
