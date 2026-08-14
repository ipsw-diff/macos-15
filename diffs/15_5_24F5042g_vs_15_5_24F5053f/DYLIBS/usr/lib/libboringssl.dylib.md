## libboringssl.dylib

> `/usr/lib/libboringssl.dylib`

```diff

-486.120.1.0.0
-  __TEXT.__text: 0x9fabc
-  __TEXT.__auth_stubs: 0x1790
+486.120.2.0.0
+  __TEXT.__text: 0x9facc
+  __TEXT.__auth_stubs: 0x17a0
   __TEXT.__objc_methlist: 0x1dc
   __TEXT.__cstring: 0x11dbb
   __TEXT.__const: 0xfed8

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0xc8
   __DATA_CONST.__objc_superrefs: 0x28
-  __AUTH_CONST.__auth_got: 0xbe0
+  __AUTH_CONST.__auth_got: 0xbe8
   __AUTH_CONST.__const: 0x2238
   __AUTH_CONST.__cfstring: 0xc0
   __AUTH_CONST.__objc_const: 0x2168

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
   Functions: 3136
-  Symbols:   3981
+  Symbols:   3982
   CStrings:  3589
 
Symbols:
+ _nw_protocol_boringssl_get_subject_endpoint
+ _objc_retainAutoreleaseReturnValue
- _nw_protocol_boringssl_get_endpoint_name
```
