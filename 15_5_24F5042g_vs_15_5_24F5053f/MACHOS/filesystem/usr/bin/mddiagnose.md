## mddiagnose

> `/usr/bin/mddiagnose`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2333.41.1.3.0
-  __TEXT.__text: 0xff14
+2333.47.1.0.0
+  __TEXT.__text: 0x1024c
   __TEXT.__auth_stubs: 0xee0
   __TEXT.__objc_stubs: 0x12c0
   __TEXT.__objc_methlist: 0x314
   __TEXT.__const: 0x160
-  __TEXT.__cstring: 0x4682
+  __TEXT.__cstring: 0x46bf
   __TEXT.__objc_methname: 0xd96
   __TEXT.__gcc_except_tab: 0xb4
   __TEXT.__objc_classname: 0x4b
   __TEXT.__objc_methtype: 0x15d
   __TEXT.__oslogstring: 0x1b
-  __TEXT.__unwind_info: 0x3f0
+  __TEXT.__unwind_info: 0x3f8
   __DATA_CONST.__auth_got: 0x780
   __DATA_CONST.__got: 0x1b8
   __DATA_CONST.__auth_ptr: 0x30
   __DATA_CONST.__const: 0x578
-  __DATA_CONST.__cfstring: 0x4860
+  __DATA_CONST.__cfstring: 0x4900
   __DATA_CONST.__objc_classlist: 0x18
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x8

   - /System/Library/PrivateFrameworks/MetadataUtilities.framework/Versions/A/MetadataUtilities
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 327
+  Functions: 329
   Symbols:   305
-  CStrings:  983
+  CStrings:  987
 
CStrings:
+ " HAS-FILE-LEAKS"
+ "IndexPid"
+ "fileleaks"
+ "hasFileLeaks"
+ "mdsPid:%@%@\n%@"
+ "mdsPid:%d%s\n"
+ "status"
+ "store:%@ policy:%s maxPolicy:%s delegate:%s token:%d indexSync:%d indexPid:%d %s %s %@\n"
- "HasLegacyIndex"
- "legacy"
- "store:%@ policy:%s maxPolicy:%s delegate:%s index:%s token:%d indexSync:%d %s %s %@\n"
- "v2"
```
