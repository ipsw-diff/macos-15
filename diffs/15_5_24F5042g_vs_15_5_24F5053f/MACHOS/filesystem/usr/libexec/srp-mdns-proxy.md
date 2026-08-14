## srp-mdns-proxy

> `/usr/libexec/srp-mdns-proxy`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-2600.120.4.0.0
-  __TEXT.__text: 0x756b8
-  __TEXT.__auth_stubs: 0x1220
+2600.120.6.0.0
+  __TEXT.__text: 0x756c4
+  __TEXT.__auth_stubs: 0x1230
   __TEXT.__const: 0x20b
   __TEXT.__cstring: 0x6e73
   __TEXT.__oslogstring: 0xf71a
   __TEXT.__objc_classname: 0x1
   __TEXT.__unwind_info: 0x500
   __TEXT.__eh_frame: 0xb4
-  __DATA_CONST.__auth_got: 0x910
+  __DATA_CONST.__auth_got: 0x918
   __DATA_CONST.__got: 0x1f0
   __DATA_CONST.__auth_ptr: 0x18
   __DATA_CONST.__const: 0x820

   - /usr/lib/libmrc.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 395
-  Symbols:   947
+  Symbols:   948
   CStrings:  2091
 
Symbols:
+ _issetugid
Functions:
~ _ConnectToServer : 1064 -> 1076
CStrings:
+ "18:55:58"
+ "Apr  6 2025"
- "19:39:09"
- "Mar 21 2025"
```
