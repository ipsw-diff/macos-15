## SecurityAgent

> `/System/Library/Frameworks/Security.framework/Versions/A/MachServices/SecurityAgent.bundle/Contents/MacOS/SecurityAgent`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_classrefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA.__data`

```diff

-55579.100.16.0.0
-  __TEXT.__text: 0x2d148
-  __TEXT.__auth_stubs: 0x1240
-  __TEXT.__objc_stubs: 0x50e0
-  __TEXT.__objc_methlist: 0x27dc
+55579.140.2.0.0
+  __TEXT.__text: 0x2d320
+  __TEXT.__auth_stubs: 0x1270
+  __TEXT.__objc_stubs: 0x5140
+  __TEXT.__objc_methlist: 0x280c
   __TEXT.__const: 0x169
-  __TEXT.__cstring: 0x2ebb
-  __TEXT.__gcc_except_tab: 0x440
-  __TEXT.__oslogstring: 0x29be
-  __TEXT.__objc_methname: 0x5531
-  __TEXT.__objc_classname: 0x636
-  __TEXT.__objc_methtype: 0x16d4
+  __TEXT.__cstring: 0x2e96
+  __TEXT.__gcc_except_tab: 0x438
+  __TEXT.__oslogstring: 0x29d6
+  __TEXT.__objc_methname: 0x556a
+  __TEXT.__objc_classname: 0x643
+  __TEXT.__objc_methtype: 0x16f1
   __TEXT.__ustring: 0x156e
   __TEXT.__dlopen_cstrs: 0x10d
-  __TEXT.__unwind_info: 0x9b0
-  __DATA_CONST.__auth_got: 0x930
-  __DATA_CONST.__got: 0x508
+  __TEXT.__unwind_info: 0x9c0
+  __DATA_CONST.__auth_got: 0x948
+  __DATA_CONST.__got: 0x528
   __DATA_CONST.__auth_ptr: 0x18
   __DATA_CONST.__const: 0x970
-  __DATA_CONST.__cfstring: 0x28c0
-  __DATA_CONST.__objc_classlist: 0x1c0
+  __DATA_CONST.__cfstring: 0x2880
+  __DATA_CONST.__objc_classlist: 0x1c8
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arrayobj: 0xc0
   __DATA_CONST.__objc_intobj: 0xc0
   __DATA_CONST.__objc_doubleobj: 0x10
-  __DATA.__objc_const: 0x47e0
-  __DATA.__objc_selrefs: 0x1a50
+  __DATA.__objc_const: 0x4870
+  __DATA.__objc_selrefs: 0x1a68
   __DATA.__objc_ivar: 0x38c
-  __DATA.__objc_data: 0x1180
+  __DATA.__objc_data: 0x11d0
   __DATA.__data: 0x492
   __DATA.__bss: 0x195
   __DATA.__common: 0x28

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1058
-  Symbols:   719
-  CStrings:  2170
+  Functions: 1062
+  Symbols:   728
+  CStrings:  2175
 
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
```
