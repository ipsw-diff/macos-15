## nsurlsessiond

> `/usr/libexec/nsurlsessiond`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3826.500.131.0.0
-  __TEXT.__text: 0x5475c
+3826.600.31.0.0
+  __TEXT.__text: 0x543d4
   __TEXT.__auth_stubs: 0xd70
   __TEXT.__delay_helper: 0x110
-  __TEXT.__objc_stubs: 0x8220
-  __TEXT.__objc_methlist: 0x25bc
+  __TEXT.__objc_stubs: 0x8200
+  __TEXT.__objc_methlist: 0x25b4
   __TEXT.__const: 0x248
-  __TEXT.__gcc_except_tab: 0xb338
-  __TEXT.__objc_methname: 0x9f36
+  __TEXT.__gcc_except_tab: 0xb2c8
+  __TEXT.__objc_methname: 0x9f0e
   __TEXT.__objc_classname: 0x4d6
   __TEXT.__objc_methtype: 0x1d97
   __TEXT.__cstring: 0x2f4e
-  __TEXT.__oslogstring: 0x9d23
-  __TEXT.__unwind_info: 0x1a70
+  __TEXT.__oslogstring: 0x9c94
+  __TEXT.__unwind_info: 0x1a50
   __DATA_CONST.__auth_got: 0x6d0
   __DATA_CONST.__got: 0x5a8
   __DATA_CONST.__auth_ptr: 0x8

   __DATA_CONST.__objc_dictobj: 0x28
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA.__objc_const: 0x3950
-  __DATA.__objc_selrefs: 0x2578
+  __DATA.__objc_selrefs: 0x2570
   __DATA.__objc_ivar: 0x358
   __DATA.__objc_data: 0x820
   __DATA.__data: 0xa28

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 867
+  Functions: 865
   Symbols:   407
-  CStrings:  2571
+  CStrings:  2568
 
CStrings:
- "Failed to bind _doesSZExtractorConsumeExtractedData (%lu) to the select statement"
- "Failed to bind _hasSZExtractor (%lu) to the select statement"
- "fillInPropertiesForTaskInfo:withTaskID:"
```
