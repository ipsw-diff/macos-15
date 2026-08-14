## IPConfiguration

> `/System/Library/SystemConfiguration/IPConfiguration.bundle/Contents/MacOS/IPConfiguration`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-494.101.1.0.0
-  __TEXT.__text: 0x5acf0
+494.101.2.0.0
+  __TEXT.__text: 0x5ad50
   __TEXT.__auth_stubs: 0x1060
   __TEXT.__const: 0x2f0
   __TEXT.__cstring: 0x3d3d
   __TEXT.__oslogstring: 0x64d6
-  __TEXT.__unwind_info: 0xb60
+  __TEXT.__unwind_info: 0xb70
   __DATA_CONST.__auth_got: 0x830
   __DATA_CONST.__got: 0x3c8
   __DATA_CONST.__auth_ptr: 0xf8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 999
+  Functions: 1001
   Symbols:   498
   CStrings:  1682
 
CStrings:
+ "IPv6.Prefix=%s/%d;IPv6.RouterHardwareAddress="
- "IPv6.Prefix=%@/%@;IPv6.RouterHardwareAddress="
```
