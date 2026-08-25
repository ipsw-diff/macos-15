## nesessionmanager

> `/usr/libexec/nesessionmanager`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2063.140.4.0.0
-  __TEXT.__text: 0xa38fc
+2063.140.6.0.0
+  __TEXT.__text: 0xa3ce8
   __TEXT.__auth_stubs: 0x19c0
   __TEXT.__objc_stubs: 0x7200
   __TEXT.__objc_methlist: 0x3014
   __TEXT.__const: 0x168
   __TEXT.__gcc_except_tab: 0x1c3c
-  __TEXT.__oslogstring: 0xb8fb
+  __TEXT.__oslogstring: 0xb958
   __TEXT.__objc_methname: 0x7d26
   __TEXT.__cstring: 0x3eec
   __TEXT.__objc_classname: 0x880

   - /usr/lib/libobjc.A.dylib
   Functions: 1597
   Symbols:   608
-  CStrings:  3286
+  CStrings:  3288
 
Functions:
~ sub_10004a3dc : 3180 -> 3184
~ sub_10004eb18 -> sub_10004eb1c : 3696 -> 3912
~ sub_100080890 -> sub_10008096c : 472 -> 1256
CStrings:
+ "Relay %@ last recorded error changing from %d to %d"
+ "Relay session ignoring unmapped error %d"
```
