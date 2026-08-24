## thermalmonitord

> `/usr/libexec/thermalmonitord`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2007.120.5.0.0
-  __TEXT.__text: 0xeea8
+2007.140.3.0.0
+  __TEXT.__text: 0xeeec
   __TEXT.__auth_stubs: 0xc70
-  __TEXT.__objc_stubs: 0x1b00
-  __TEXT.__objc_methlist: 0xcfc
+  __TEXT.__objc_stubs: 0x1b20
+  __TEXT.__objc_methlist: 0xd0c
   __TEXT.__const: 0x18e
   __TEXT.__gcc_except_tab: 0x50
-  __TEXT.__objc_methname: 0x2991
+  __TEXT.__objc_methname: 0x29ae
   __TEXT.__cstring: 0x4aa1
   __TEXT.__objc_classname: 0x15c
   __TEXT.__objc_methtype: 0xd9e

   __DATA_CONST.__objc_arrayobj: 0x2ef8
   __DATA_CONST.__objc_doubleobj: 0xa2a0
   __DATA.__objc_const: 0x2710
-  __DATA.__objc_selrefs: 0x8d8
+  __DATA.__objc_selrefs: 0x8e0
   __DATA.__objc_ivar: 0x34c
   __DATA.__objc_data: 0x500
   __DATA.__data: 0x84

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 348
+  Functions: 349
   Symbols:   245
-  CStrings:  1340
+  CStrings:  1341
 
Functions:
~ sub_1000016c8 : 116 -> 132
- sub_100001750
+ sub_1000017e4
+ sub_10000e264
CStrings:
+ "forceSensorExchangeDataToSMC"
```
