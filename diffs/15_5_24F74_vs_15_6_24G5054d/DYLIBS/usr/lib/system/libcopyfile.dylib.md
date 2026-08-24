## libcopyfile.dylib

> `/usr/lib/system/libcopyfile.dylib`

```diff

-221.121.1.0.0
-  __TEXT.__text: 0x780c
+224.0.0.0.0
+  __TEXT.__text: 0x789c
   __TEXT.__auth_stubs: 0x710
   __TEXT.__const: 0x1c8
-  __TEXT.__cstring: 0x1a48
+  __TEXT.__cstring: 0x1a95
   __TEXT.__unwind_info: 0xe0
   __DATA_CONST.__got: 0x30
   __DATA_CONST.__const: 0x3b0

   - /usr/lib/system/libxpc.dylib
   Functions: 39
   Symbols:   168
-  CStrings:  190
+  CStrings:  192
 
Functions:
~ _copyfile_open : 3620 -> 3764
CStrings:
+ "file %s changed behind our feet: %m"
+ "fstat on open fd failed for %s\n: %m"
```
