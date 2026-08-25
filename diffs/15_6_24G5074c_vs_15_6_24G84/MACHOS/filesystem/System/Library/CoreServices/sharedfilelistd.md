## sharedfilelistd

> `/System/Library/CoreServices/sharedfilelistd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-302.6.0.0.0
-  __TEXT.__text: 0x198e4
-  __TEXT.__auth_stubs: 0x720
-  __TEXT.__objc_stubs: 0x2c60
+302.7.0.0.0
+  __TEXT.__text: 0x199e4
+  __TEXT.__auth_stubs: 0x730
+  __TEXT.__objc_stubs: 0x2cc0
   __TEXT.__objc_methlist: 0x1704
   __TEXT.__const: 0xa8
   __TEXT.__oslogstring: 0x174f
   __TEXT.__objc_classname: 0x1f8
-  __TEXT.__objc_methname: 0x358b
+  __TEXT.__objc_methname: 0x35c7
   __TEXT.__objc_methtype: 0xad6
-  __TEXT.__cstring: 0xbb1
+  __TEXT.__cstring: 0xbaa
   __TEXT.__gcc_except_tab: 0xf4
   __TEXT.__unwind_info: 0x600
-  __DATA_CONST.__auth_got: 0x3a0
-  __DATA_CONST.__got: 0x3a8
+  __DATA_CONST.__auth_got: 0x3a8
+  __DATA_CONST.__got: 0x3b0
   __DATA_CONST.__const: 0x6a0
-  __DATA_CONST.__cfstring: 0xf80
+  __DATA_CONST.__cfstring: 0xf40
   __DATA_CONST.__objc_classlist: 0x78
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x50

   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA.__objc_const: 0x3778
-  __DATA.__objc_selrefs: 0xf10
+  __DATA.__objc_selrefs: 0xf28
   __DATA.__objc_ivar: 0x104
   __DATA.__objc_data: 0x4b0
   __DATA.__data: 0x3c0

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   Functions: 569
-  Symbols:   245
-  CStrings:  1043
+  Symbols:   247
+  CStrings:  1045
 
Symbols:
+ _OBJC_CLASS_$_NSURLComponents
+ _strcasecmp
Functions:
~ sub_1000031ec : 756 -> 1012
CStrings:
+ "caseInsensitiveCompare:"
+ "componentsWithString:"
+ "fileloc"
+ "pathExtension"
- ".fileloc"
- "file:"
```
