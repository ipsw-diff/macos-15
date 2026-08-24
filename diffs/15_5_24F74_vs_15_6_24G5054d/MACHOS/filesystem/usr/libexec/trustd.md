## trustd

> `/usr/libexec/trustd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-61439.120.27.0.0
-  __TEXT.__text: 0x6363c
+61439.140.8.0.0
+  __TEXT.__text: 0x63c78
   __TEXT.__auth_stubs: 0x2380
-  __TEXT.__objc_stubs: 0x2d80
-  __TEXT.__objc_methlist: 0xbf4
+  __TEXT.__objc_stubs: 0x2da0
+  __TEXT.__objc_methlist: 0xc0c
   __TEXT.__const: 0x5877
   __TEXT.__dlopen_cstrs: 0x66
   __TEXT.__gcc_except_tab: 0xd24
-  __TEXT.__cstring: 0x63b1
-  __TEXT.__oslogstring: 0x5964
+  __TEXT.__cstring: 0x63bd
+  __TEXT.__oslogstring: 0x5ac1
   __TEXT.__objc_classname: 0x194
-  __TEXT.__objc_methname: 0x2cf6
+  __TEXT.__objc_methname: 0x2d21
   __TEXT.__objc_methtype: 0xae6
-  __TEXT.__unwind_info: 0x10a8
+  __TEXT.__unwind_info: 0x10b0
   __DATA_CONST.__auth_got: 0x11d0
   __DATA_CONST.__got: 0x758
   __DATA_CONST.__auth_ptr: 0x18

   __DATA_CONST.__objc_arraydata: 0x40
   __DATA_CONST.__objc_arrayobj: 0x48
   __DATA.__objc_const: 0x1450
-  __DATA.__objc_selrefs: 0xd30
+  __DATA.__objc_selrefs: 0xd38
   __DATA.__objc_ivar: 0xb4
   __DATA.__objc_data: 0x460
   __DATA.__data: 0x3dc

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1324
+  Functions: 1327
   Symbols:   818
-  CStrings:  2122
+  CStrings:  2131
 
CStrings:
+ "Malformed anchor record, cert hash not a string: %{public}@"
+ "Malformed anchor record, no cert for hash: %{public}@"
+ "Malformed anchor record, not a dictionary: %{public}@"
+ "Malformed anchor record, oids not an array: %{public}@"
+ "Malformed anchor record, type not a string: %{public}@"
+ "Malformed anchor records, not an array"
+ "anchorCache"
+ "anchorRecordsPermitttedForPolicy:policyId:"
+ "unknown anchor type: %{public}@"
```
