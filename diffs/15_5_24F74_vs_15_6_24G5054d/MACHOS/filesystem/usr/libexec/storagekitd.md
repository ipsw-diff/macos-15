## storagekitd

> `/usr/libexec/storagekitd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_classname`
- `__TEXT.__objc_methtype`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-934.120.4.0.0
-  __TEXT.__text: 0x194038
+934.140.2.0.0
+  __TEXT.__text: 0x1941f8
   __TEXT.__auth_stubs: 0x2e60
-  __TEXT.__objc_stubs: 0xee60
-  __TEXT.__objc_methlist: 0x805c
+  __TEXT.__objc_stubs: 0xeea0
+  __TEXT.__objc_methlist: 0x8074
   __TEXT.__const: 0xc88
-  __TEXT.__objc_methname: 0x15868
+  __TEXT.__objc_methname: 0x158ae
   __TEXT.__oslogstring: 0x624c
   __TEXT.__objc_classname: 0xd8a
   __TEXT.__objc_methtype: 0x6348

   __DATA_CONST.__objc_arrayobj: 0x948
   __DATA_CONST.__objc_dictobj: 0x5c8
   __DATA_CONST.__objc_intobj: 0x180
-  __DATA.__objc_const: 0xf500
-  __DATA.__objc_selrefs: 0x4600
-  __DATA.__objc_ivar: 0xa14
+  __DATA.__objc_const: 0xf530
+  __DATA.__objc_selrefs: 0x4610
+  __DATA.__objc_ivar: 0xa18
   __DATA.__objc_data: 0x2990
   __DATA.__data: 0x970
   __DATA.__bss: 0x578

   - /usr/lib/libcsfde.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
-  Functions: 3604
+  Functions: 3606
   Symbols:   1112
-  CStrings:  14537
+  CStrings:  14541
 
CStrings:
+ "T@\"NSMutableArray\",&,N,V_mountArgs"
+ "_mountArgs"
+ "mountArgs"
+ "setMountArgs:"
```
