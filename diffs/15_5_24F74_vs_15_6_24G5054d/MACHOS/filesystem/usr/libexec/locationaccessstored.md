## locationaccessstored

> `/usr/libexec/locationaccessstored`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2964.0.4.0.0
-  __TEXT.__text: 0x3c88
-  __TEXT.__auth_stubs: 0x200
-  __TEXT.__objc_stubs: 0xc80
-  __TEXT.__objc_methlist: 0x26c
-  __TEXT.__const: 0x88
-  __TEXT.__oslogstring: 0x74f
+2964.0.7.0.0
+  __TEXT.__text: 0x3e90
+  __TEXT.__auth_stubs: 0x220
+  __TEXT.__objc_stubs: 0xca0
+  __TEXT.__objc_methlist: 0x274
+  __TEXT.__const: 0x90
+  __TEXT.__oslogstring: 0x867
   __TEXT.__cstring: 0x204
-  __TEXT.__gcc_except_tab: 0x7b8
-  __TEXT.__objc_methname: 0xb4d
+  __TEXT.__gcc_except_tab: 0x7f0
+  __TEXT.__objc_methname: 0xb76
   __TEXT.__objc_classname: 0x65
   __TEXT.__objc_methtype: 0x179
-  __TEXT.__unwind_info: 0x1b0
-  __DATA_CONST.__auth_got: 0x110
+  __TEXT.__unwind_info: 0x1b8
+  __DATA_CONST.__auth_got: 0x120
   __DATA_CONST.__got: 0xd0
   __DATA_CONST.__const: 0x160
   __DATA_CONST.__cfstring: 0x240

   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x8
   __DATA.__objc_const: 0x250
-  __DATA.__objc_selrefs: 0x3f8
+  __DATA.__objc_selrefs: 0x400
   __DATA.__objc_ivar: 0x4
   __DATA.__objc_data: 0x50
   __DATA.__data: 0x140

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 44
-  Symbols:   67
-  CStrings:  222
+  Functions: 45
+  Symbols:   69
+  CStrings:  225
 
Symbols:
+ __os_signpost_emit_with_name_impl
+ _os_signpost_enabled
CStrings:
+ "#CLLA(getLastRecordingTimestampString) setting LastRecordingTime to Now because it was unexpectedly missing"
+ "getOrDefaultLastRecordingTimestampString"
+ "{\"msg%{public}.0s\":\"#CLLA(getLastRecordingTimestampString) setting LastRecordingTime to Now because it was unexpectedly missing\", \"today\":%{public, location:escape_only}@}"
```
