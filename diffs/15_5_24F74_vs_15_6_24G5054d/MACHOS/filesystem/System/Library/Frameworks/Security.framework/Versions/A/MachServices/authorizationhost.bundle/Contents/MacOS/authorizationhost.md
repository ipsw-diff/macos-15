## authorizationhost

> `/System/Library/Frameworks/Security.framework/Versions/A/MachServices/authorizationhost.bundle/Contents/MacOS/authorizationhost`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__data`

```diff

-55579.100.16.0.0
-  __TEXT.__text: 0x21e70
-  __TEXT.__auth_stubs: 0x12f0
-  __TEXT.__objc_stubs: 0x18a0
-  __TEXT.__objc_methlist: 0x8ac
+55579.140.2.0.0
+  __TEXT.__text: 0x22044
+  __TEXT.__auth_stubs: 0x1320
+  __TEXT.__objc_stubs: 0x18e0
+  __TEXT.__objc_methlist: 0x8dc
   __TEXT.__const: 0x260
-  __TEXT.__cstring: 0x27c1
-  __TEXT.__objc_methname: 0x13ef
-  __TEXT.__objc_classname: 0x1cf
-  __TEXT.__objc_methtype: 0x73f
-  __TEXT.__oslogstring: 0x2d56
-  __TEXT.__gcc_except_tab: 0x27c
+  __TEXT.__cstring: 0x279c
+  __TEXT.__objc_methname: 0x141a
+  __TEXT.__objc_classname: 0x1dc
+  __TEXT.__objc_methtype: 0x75c
+  __TEXT.__oslogstring: 0x2d6e
+  __TEXT.__gcc_except_tab: 0x274
   __TEXT.__dlopen_cstrs: 0x39b
-  __TEXT.__unwind_info: 0x638
-  __DATA_CONST.__auth_got: 0x988
-  __DATA_CONST.__got: 0x240
+  __TEXT.__unwind_info: 0x648
+  __DATA_CONST.__auth_got: 0x9a0
+  __DATA_CONST.__got: 0x260
   __DATA_CONST.__auth_ptr: 0x20
   __DATA_CONST.__const: 0x820
-  __DATA_CONST.__cfstring: 0xdc0
-  __DATA_CONST.__objc_classlist: 0xa8
+  __DATA_CONST.__cfstring: 0xd80
+  __DATA_CONST.__objc_classlist: 0xb0
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x50
   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__objc_arrayobj: 0x18
-  __DATA.__objc_const: 0x1038
-  __DATA.__objc_selrefs: 0x6f8
+  __DATA.__objc_const: 0x10c8
+  __DATA.__objc_selrefs: 0x708
   __DATA.__objc_ivar: 0x7c
-  __DATA.__objc_data: 0x690
+  __DATA.__objc_data: 0x6e0
   __DATA.__data: 0x138
   __DATA.__bss: 0x268
   __DATA.__common: 0x18

   - /usr/lib/libcsfde.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpam.2.dylib
-  Functions: 791
-  Symbols:   515
-  CStrings:  1071
+  Functions: 795
+  Symbols:   524
+  CStrings:  1075
 
Symbols:
+ _OBJC_CLASS_$_XpcSafeTools
+ _OBJC_METACLASS_$_XpcSafeTools
+ __xpc_type_array
+ __xpc_type_data
+ __xpc_type_string
+ __xpc_type_uint64
+ _xpc_data_get_bytes_ptr
+ _xpc_data_get_length
+ _xpc_string_get_string_ptr
+ _xpc_uint64_get_value
- _strcasestr
CStrings:
+ "@32@0:8@16*24"
+ "No memory for %zu bytes"
+ "XpcSafeTools"
+ "getXpcData:name:"
+ "getXpcNSString:name:"
+ "getXpcString:name:"
+ "r*32@0:8@16*24"
- "Item: %s, value -- %@\n"
- "Item: %s, value -- *HIDDEN*\n"
- "appendFormat:"
```
