## trustd

> `/usr/libexec/trustd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-61439.120.15.0.0
-  __TEXT.__text: 0x6375c
-  __TEXT.__auth_stubs: 0x2370
+61439.120.22.0.0
+  __TEXT.__text: 0x635e4
+  __TEXT.__auth_stubs: 0x2380
   __TEXT.__objc_stubs: 0x2d80
   __TEXT.__objc_methlist: 0xbf4
-  __TEXT.__const: 0x4668
+  __TEXT.__const: 0x5877
   __TEXT.__dlopen_cstrs: 0x66
   __TEXT.__gcc_except_tab: 0xd24
-  __TEXT.__cstring: 0x63b7
-  __TEXT.__oslogstring: 0x5993
+  __TEXT.__cstring: 0x63b1
+  __TEXT.__oslogstring: 0x5964
   __TEXT.__objc_classname: 0x194
   __TEXT.__objc_methname: 0x2cf6
   __TEXT.__objc_methtype: 0xae6
-  __TEXT.__unwind_info: 0x10a8
-  __DATA_CONST.__auth_got: 0x11c8
+  __TEXT.__unwind_info: 0x10a0
+  __DATA_CONST.__auth_got: 0x11d0
   __DATA_CONST.__got: 0x758
   __DATA_CONST.__auth_ptr: 0x18
-  __DATA_CONST.__const: 0x5168
+  __DATA_CONST.__const: 0x51a8
   __DATA_CONST.__cfstring: 0x5a80
   __DATA_CONST.__objc_classlist: 0x70
   __DATA_CONST.__objc_catlist: 0x18

   __DATA.__objc_ivar: 0xb4
   __DATA.__objc_data: 0x460
   __DATA.__data: 0x3dc
-  __DATA.__bss: 0x4e8
+  __DATA.__bss: 0x500
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1322
-  Symbols:   817
-  CStrings:  2125
+  Functions: 1324
+  Symbols:   818
+  CStrings:  2122
 
Symbols:
+ _SecCertificateCopyAppleExternalRoots
CStrings:
+ "OTATrust: failed to update from asset: %@"
+ "Using asset trust store %llu instead of system trust store %llu"
+ "Using supplementals asset v%llu instead of system v%llu"
+ "Using system trust store %llu instead of asset trust store %llu"
- "OTATrust: failed to update from asset after notification: %@"
- "OTATrust: failed to update from asset during periodic re-read: %@"
- "Using asset v%llu instead of system v%llu"
- "Using built-in constrained anchors"
- "Using built-in system anchors"
- "Using trust store version %llu from %s"
- "asset"
```
