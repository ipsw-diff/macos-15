## socketfilterfw

> `/usr/libexec/ApplicationFirewall/socketfilterfw`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-309.0.0.0.0
-  __TEXT.__text: 0x1d49c
-  __TEXT.__auth_stubs: 0x1010
+309.140.2.0.0
+  __TEXT.__text: 0x1d4e0
+  __TEXT.__auth_stubs: 0x1020
   __TEXT.__objc_stubs: 0x1b60
   __TEXT.__objc_methlist: 0x7bc
   __TEXT.__const: 0x110
   __TEXT.__oslogstring: 0x265e
-  __TEXT.__cstring: 0x3b37
+  __TEXT.__cstring: 0x3b58
   __TEXT.__objc_classname: 0xaf
   __TEXT.__objc_methname: 0x1d78
   __TEXT.__objc_methtype: 0x3a0
   __TEXT.__gcc_except_tab: 0x1c
   __TEXT.__unwind_info: 0x470
-  __DATA_CONST.__auth_got: 0x818
+  __DATA_CONST.__auth_got: 0x820
   __DATA_CONST.__got: 0x1d8
   __DATA_CONST.__auth_ptr: 0x10
   __DATA_CONST.__const: 0x550

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 447
-  Symbols:   330
-  CStrings:  1101
+  Functions: 448
+  Symbols:   331
+  CStrings:  1102
 
Symbols:
+ _getuid
Functions:
~ sub_100006720 : 3092 -> 48
+ sub_100006750
CStrings:
+ "Must be root to change settings."
```
