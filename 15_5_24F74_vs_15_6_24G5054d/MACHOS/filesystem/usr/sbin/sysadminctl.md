## sysadminctl

> `/usr/sbin/sysadminctl`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methname`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_selrefs`

```diff

-948.3.4.0.0
-  __TEXT.__text: 0x3744
+948.5.1.0.0
+  __TEXT.__text: 0x36fc
   __TEXT.__auth_stubs: 0x3a0
   __TEXT.__objc_stubs: 0xfc0
-  __TEXT.__cstring: 0x1905
+  __TEXT.__cstring: 0x18f7
   __TEXT.__const: 0x18
   __TEXT.__ustring: 0x56c
   __TEXT.__objc_methname: 0x9fe

   __DATA_CONST.__auth_got: 0x1d8
   __DATA_CONST.__got: 0xf8
   __DATA_CONST.__const: 0x190
-  __DATA_CONST.__cfstring: 0x1560
+  __DATA_CONST.__cfstring: 0x1540
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_arraydata: 0x118
   __DATA_CONST.__objc_arrayobj: 0x48

   - /usr/lib/libobjc.A.dylib
   Functions: 26
   Symbols:   96
-  CStrings:  306
+  CStrings:  305
 
Functions:
~ sub_10000105c : 8000 -> 7928
CStrings:
+ "isHomeDirValid"
- "/private/var/empty"
- "pathComponents"
```
