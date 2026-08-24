## iCloud

> `/System/Library/CoreServices/iCloud.app/Contents/MacOS/iCloud`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2260.10.3.0.0
+2270.0.0.0.0
   __TEXT.__text: 0x164c4
   __TEXT.__auth_stubs: 0x3e0
   __TEXT.__objc_stubs: 0x2f00
   __TEXT.__objc_methlist: 0xdc0
   __TEXT.__const: 0xc8
-  __TEXT.__objc_methname: 0x3b3d
-  __TEXT.__cstring: 0x25ef
+  __TEXT.__objc_methname: 0x3b3a
+  __TEXT.__cstring: 0x25c4
   __TEXT.__oslogstring: 0x1704
   __TEXT.__objc_classname: 0xcc
   __TEXT.__objc_methtype: 0x88c

   __DATA_CONST.__auth_got: 0x200
   __DATA_CONST.__got: 0x370
   __DATA_CONST.__const: 0x7f8
-  __DATA_CONST.__cfstring: 0x1de0
+  __DATA_CONST.__cfstring: 0x1d80
   __DATA_CONST.__objc_classlist: 0x30
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x20
-  __DATA_CONST.__objc_arraydata: 0x100
+  __DATA_CONST.__objc_arraydata: 0xd0
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA.__objc_const: 0xf28
   __DATA.__objc_selrefs: 0xe70

   - /usr/lib/libobjc.A.dylib
   Functions: 301
   Symbols:   183
-  CStrings:  1038
+  CStrings:  1035
 
CStrings:
+ "CKBladerunnerShareURLSlugBasedVettingKeySuffix"
+ "Got a nil vettingKeySuffix for URL: %@"
- "CKBladerunnerShareURLSlugBasedApplicationBundleID"
- "Got nil bundle id for URL: %@"
- "com.apple.Keynote"
- "com.apple.Numbers"
- "com.apple.Pages"
```
