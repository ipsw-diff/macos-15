## EmailFoundation

> `/System/Library/PrivateFrameworks/EmailFoundation.framework/Versions/A/EmailFoundation`

```diff

-3826.600.51.1.1
-  __TEXT.__text: 0x6c134
+3826.700.51.0.0
+  __TEXT.__text: 0x6cacc
   __TEXT.__auth_stubs: 0x1170
-  __TEXT.__objc_methlist: 0x64fc
-  __TEXT.__gcc_except_tab: 0xbdcc
+  __TEXT.__objc_methlist: 0x6544
+  __TEXT.__gcc_except_tab: 0xbed4
   __TEXT.__const: 0x1ca
-  __TEXT.__cstring: 0x4207
+  __TEXT.__cstring: 0x4297
   __TEXT.__oslogstring: 0xc9c
   __TEXT.__ustring: 0x58
   __TEXT.__swift5_typeref: 0xda

   __TEXT.__swift5_fieldmd: 0x7c
   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_types: 0x10
-  __TEXT.__unwind_info: 0x4958
+  __TEXT.__unwind_info: 0x4990
   __TEXT.__eh_frame: 0xb8
   __TEXT.__objc_classname: 0xe32
-  __TEXT.__objc_methname: 0xbf7c
-  __TEXT.__objc_methtype: 0x1c07
-  __TEXT.__objc_stubs: 0x8740
+  __TEXT.__objc_methname: 0xbfc2
+  __TEXT.__objc_methtype: 0x1c42
+  __TEXT.__objc_stubs: 0x87a0
   __DATA_CONST.__got: 0x6e8
   __DATA_CONST.__const: 0x7b0
   __DATA_CONST.__objc_classlist: 0x438
   __DATA_CONST.__objc_catlist: 0x100
   __DATA_CONST.__objc_protolist: 0x118
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x33f8
+  __DATA_CONST.__objc_selrefs: 0x3410
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x388
   __DATA_CONST.__objc_arraydata: 0x58
   __AUTH_CONST.__auth_got: 0x8d0
   __AUTH_CONST.__const: 0x2b68
-  __AUTH_CONST.__cfstring: 0x5040
+  __AUTH_CONST.__cfstring: 0x50e0
   __AUTH_CONST.__objc_const: 0xc0c8
   __AUTH_CONST.__objc_intobj: 0x150
   __AUTH_CONST.__objc_arrayobj: 0x30

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 2631
-  Symbols:   6026
-  CStrings:  3518
+  Functions: 2637
+  Symbols:   6035
+  CStrings:  3529
 
Symbols:
+ -[EFInt64Set _appendRange:toString:withSeparator:]
+ -[EFInt64Set _lastRange]
+ -[EFMutableOrderedDictionary removeObjectsAtIndexes:]
+ -[EFMutableOrderedDictionary removeObjectsForKeys:]
+ -[EFOrderedDictionary objectsAtIndexes:]
+ -[EFOrderedDictionary objectsForKeys:notFoundMarker:]
+ _objc_msgSend$_appendRange:toString:withSeparator:
+ _objc_msgSend$_lastRange
+ _objc_msgSend$removeObjectsInArray:
CStrings:
+ "%lld:%lld"
+ "(uint64_t)loc + len <= INT64_MAX"
+ ","
+ ",...(%llu more)..."
+ "EFInt64Range EFMakeInt64Range(int64_t, uint64_t)"
+ "EFInt64Set.h"
+ "INT64_MAX - (int64_t)len >= loc"
+ "_appendRange:toString:withSeparator:"
+ "_lastRange"
+ "len <= INT64_MAX"
+ "removeObjectsInArray:"
+ "v44@0:8{_EFInt64Range=qQ}16@32B40"
+ "{_EFInt64Range=qQ}16@0:8"
- "%lld,"
- "<%@: %p> ["
```
