## nesessionmanager

> `/usr/libexec/nesessionmanager`

### Sections with Same Size but Changed Content

- `__TEXT.__oslogstring`
- `__TEXT.__objc_methtype`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-2063.120.13.0.0
-  __TEXT.__text: 0xa3654
-  __TEXT.__auth_stubs: 0x19b0
-  __TEXT.__objc_stubs: 0x71e0
-  __TEXT.__objc_methlist: 0x2ff4
+2063.120.19.0.0
+  __TEXT.__text: 0xa38fc
+  __TEXT.__auth_stubs: 0x19c0
+  __TEXT.__objc_stubs: 0x7200
+  __TEXT.__objc_methlist: 0x3014
   __TEXT.__const: 0x168
   __TEXT.__gcc_except_tab: 0x1c3c
   __TEXT.__oslogstring: 0xb8fb
-  __TEXT.__objc_methname: 0x7d08
+  __TEXT.__objc_methname: 0x7d26
   __TEXT.__cstring: 0x3eec
   __TEXT.__objc_classname: 0x880
   __TEXT.__objc_methtype: 0x16be
-  __TEXT.__unwind_info: 0x12d8
-  __DATA_CONST.__auth_got: 0xce8
+  __TEXT.__unwind_info: 0x12e0
+  __DATA_CONST.__auth_got: 0xcf0
   __DATA_CONST.__got: 0x658
   __DATA_CONST.__const: 0x1e20
   __DATA_CONST.__cfstring: 0x2400

   __DATA_CONST.__objc_intobj: 0x228
   __DATA_CONST.__objc_dictobj: 0x50
   __DATA.__objc_const: 0x63a8
-  __DATA.__objc_selrefs: 0x1e88
+  __DATA.__objc_selrefs: 0x1e90
   __DATA.__objc_ivar: 0x614
   __DATA.__objc_data: 0x1310
   __DATA.__data: 0xa90

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libnetworkextension.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1594
-  Symbols:   607
-  CStrings:  3285
+  Functions: 1597
+  Symbols:   608
+  CStrings:  3286
 
Symbols:
+ _NEVirtualInterfaceSetHasDefaultRoute
CStrings:
+ "pluginStopReasonStopsSession:"
```
