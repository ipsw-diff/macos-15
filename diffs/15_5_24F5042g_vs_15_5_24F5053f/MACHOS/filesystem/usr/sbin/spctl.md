## spctl

> `/usr/sbin/spctl`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__dof_security_`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_dupclass`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-620.120.1.0.0
+620.120.4.0.0
   __TEXT.__text: 0xc000
   __TEXT.__auth_stubs: 0x940
   __TEXT.__objc_stubs: 0xec0
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x7e8
   __TEXT.__const: 0x4bb
-  __TEXT.__cstring: 0x18c9
+  __TEXT.__cstring: 0x18cb
   __TEXT.__oslogstring: 0x81b
   __TEXT.__objc_classname: 0xf3
   __TEXT.__objc_methname: 0x1698

   __DATA_CONST.__objc_arrayobj: 0x120
   __DATA_CONST.__objc_dupclass: 0x58
   __DATA_CONST.__objc_dictobj: 0x28
+  __DATA_CONST.__objc_intobj: 0x18
   __DATA.__objc_const: 0xdd0
   __DATA.__objc_selrefs: 0x5b0
   __DATA.__objc_ivar: 0x6c

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   Functions: 325
-  Symbols:   244
-  CStrings:  632
+  Symbols:   245
+  CStrings:  633
 
Symbols:
+ _OBJC_CLASS_$_NSConstantIntegerNumber
CStrings:
+ "i"
```
