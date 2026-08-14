## sandboxd

> `/usr/libexec/sandboxd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__dof_sandboxd`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-2401.120.20.0.1
-  __TEXT.__text: 0x2b0e8
+2401.120.23.0.0
+  __TEXT.__text: 0x2b160
   __TEXT.__auth_stubs: 0xf00
-  __TEXT.__objc_stubs: 0x2480
+  __TEXT.__objc_stubs: 0x24a0
   __TEXT.__objc_methlist: 0xfc4
   __TEXT.__const: 0x7d40
-  __TEXT.__cstring: 0x13d62
+  __TEXT.__cstring: 0x13d92
   __TEXT.__oslogstring: 0x1c81
   __TEXT.__objc_classname: 0x1b8
-  __TEXT.__objc_methname: 0x28fc
+  __TEXT.__objc_methname: 0x2907
   __TEXT.__objc_methtype: 0x664
   __TEXT.__gcc_except_tab: 0x2ac
   __TEXT.__dof_sandboxd: 0x2f5

   __DATA_CONST.__got: 0x250
   __DATA_CONST.__auth_ptr: 0x30
   __DATA_CONST.__const: 0x2088
-  __DATA_CONST.__cfstring: 0x7bc0
+  __DATA_CONST.__cfstring: 0x7be0
   __DATA_CONST.__objc_classlist: 0x98
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x28

   __DATA_CONST.__objc_arraydata: 0x1260
   __DATA_CONST.__objc_arrayobj: 0xae0
   __DATA.__objc_const: 0x2050
-  __DATA.__objc_selrefs: 0xb38
+  __DATA.__objc_selrefs: 0xb40
   __DATA.__objc_ivar: 0x158
   __DATA.__objc_data: 0x5f0
-  __DATA.__data: 0x9310
+  __DATA.__data: 0x9320
   __DATA.__crash_info: 0x40
   __DATA.__bss: 0x208
   __DATA.__common: 0x38

   - /usr/lib/libsandbox.1.dylib
   Functions: 751
   Symbols:   327
-  CStrings:  4563
+  CStrings:  4566
 
Functions:
~ sub_100015820 : 160 -> 280
CStrings:
+ "/Users"
+ "allObjects"
+ "mach_vm_update_pointers_with_remote_tags"
```
