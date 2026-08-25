## ASPCarryLog

> `/usr/libexec/ASPCarryLog`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-616.140.4.0.0
-  __TEXT.__text: 0x4f8e0
+616.140.4.0.1
+  __TEXT.__text: 0x4f920
   __TEXT.__auth_stubs: 0xbb0
   __TEXT.__objc_stubs: 0x3040
   __TEXT.__objc_methlist: 0x14e8
   __TEXT.__gcc_except_tab: 0x5a0
-  __TEXT.__cstring: 0x5850d
+  __TEXT.__cstring: 0x5855f
   __TEXT.__const: 0x2c0
   __TEXT.__objc_classname: 0x263
   __TEXT.__objc_methtype: 0x9f6

   __DATA_CONST.__got: 0x1e8
   __DATA_CONST.__auth_ptr: 0x60
   __DATA_CONST.__const: 0x420
-  __DATA_CONST.__cfstring: 0x22560
+  __DATA_CONST.__cfstring: 0x225a0
   __DATA_CONST.__objc_classlist: 0x88
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8

   - /usr/local/lib/libNVMeCTL.dylib
   Functions: 628
   Symbols:   263
-  CStrings:  9550
+  CStrings:  9552
 
Functions:
~ sub_1000434e8 : 452 -> 476
~ sub_1000436ac -> sub_1000436c4 : 548 -> 588
CStrings:
+ "%@: Failed to create properties dictionary"
+ "%@: Failed to create string for key %s"
```
