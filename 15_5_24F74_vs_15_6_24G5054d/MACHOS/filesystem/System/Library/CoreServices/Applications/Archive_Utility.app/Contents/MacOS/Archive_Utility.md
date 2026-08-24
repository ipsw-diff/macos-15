## Archive Utility

> `/System/Library/CoreServices/Applications/Archive Utility.app/Contents/MacOS/Archive Utility`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-162.0.0.0.0
-  __TEXT.__text: 0x2b4a4
-  __TEXT.__auth_stubs: 0x1080
-  __TEXT.__objc_stubs: 0x3de0
+165.0.0.0.0
+  __TEXT.__text: 0x2b770
+  __TEXT.__auth_stubs: 0x1090
+  __TEXT.__objc_stubs: 0x3e60
   __TEXT.__objc_methlist: 0x1b70
+  __TEXT.__cstring: 0x5448
   __TEXT.__const: 0x14a8
-  __TEXT.__gcc_except_tab: 0x1ec0
-  __TEXT.__cstring: 0x53ec
-  __TEXT.__objc_methname: 0x527b
+  __TEXT.__gcc_except_tab: 0x1f08
+  __TEXT.__objc_methname: 0x52e7
   __TEXT.__objc_classname: 0x50c
   __TEXT.__objc_methtype: 0x1160
-  __TEXT.__unwind_info: 0xb28
-  __DATA_CONST.__auth_got: 0x858
+  __TEXT.__unwind_info: 0xb30
+  __DATA_CONST.__auth_got: 0x860
   __DATA_CONST.__got: 0x288
   __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__const: 0x1550
-  __DATA_CONST.__cfstring: 0x2880
+  __DATA_CONST.__cfstring: 0x28c0
   __DATA_CONST.__objc_classlist: 0xd0
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x50

   __DATA_CONST.__objc_arraydata: 0xb0
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA.__objc_const: 0x2c70
-  __DATA.__objc_selrefs: 0x1658
+  __DATA.__objc_selrefs: 0x1678
   __DATA.__objc_ivar: 0x240
   __DATA.__objc_data: 0x820
   __DATA.__data: 0x4c8

   - /usr/lib/liblzma.5.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 668
-  Symbols:   348
-  CStrings:  2251
+  Functions: 671
+  Symbols:   349
+  CStrings:  2257
 
Symbols:
+ _realpath$DARWIN_EXTSN
CStrings:
+ "_URLByInsertingResolveFlags:"
+ "_URLByRemovingResolveFlags"
+ "_resolveFlags"
+ "group.com.apple.ArchiveUtility.PKSignedContainer"
+ "realpath failed for URL: %@ errno: %d"
+ "setSecureAppGroupContainerIdentifier:"
```
