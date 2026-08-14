## uarppersonalizationd

> `/usr/libexec/uarppersonalizationd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-1207.120.16.0.0
-  __TEXT.__text: 0x28fc
+1207.120.19.0.0
+  __TEXT.__text: 0x2a10
   __TEXT.__auth_stubs: 0x310
   __TEXT.__objc_stubs: 0x420
   __TEXT.__objc_methlist: 0x88

   - /usr/lib/libauthinstall.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 64
+  Functions: 65
   Symbols:   79
   CStrings:  137
 
Functions:
~ sub_100002354 : 72 -> 276
+ sub_100002468
+ sub_10000255c
- sub_100002470
```
