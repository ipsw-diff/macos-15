## sandboxd

> `/usr/libexec/sandboxd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__dof_sandboxd`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2401.120.9.0.0
+2401.120.20.0.1
   __TEXT.__text: 0x2b0e8
   __TEXT.__auth_stubs: 0xf00
   __TEXT.__objc_stubs: 0x2480
   __TEXT.__objc_methlist: 0xfc4
   __TEXT.__const: 0x7d40
-  __TEXT.__cstring: 0x13d47
+  __TEXT.__cstring: 0x13d62
   __TEXT.__oslogstring: 0x1c81
   __TEXT.__objc_classname: 0x1b8
   __TEXT.__objc_methname: 0x28fc

   __DATA_CONST.__got: 0x250
   __DATA_CONST.__auth_ptr: 0x30
   __DATA_CONST.__const: 0x2088
-  __DATA_CONST.__cfstring: 0x7ba0
+  __DATA_CONST.__cfstring: 0x7bc0
   __DATA_CONST.__objc_classlist: 0x98
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x28

   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x80
   __DATA_CONST.__objc_intobj: 0xe10
-  __DATA_CONST.__objc_arraydata: 0x1258
+  __DATA_CONST.__objc_arraydata: 0x1260
   __DATA_CONST.__objc_arrayobj: 0xae0
   __DATA.__objc_const: 0x2050
   __DATA.__objc_selrefs: 0xb38

   - /usr/lib/libsandbox.1.dylib
   Functions: 751
   Symbols:   327
-  CStrings:  4562
+  CStrings:  4563
 
CStrings:
+ "AL798K98FX/com.skype.skype"
```
