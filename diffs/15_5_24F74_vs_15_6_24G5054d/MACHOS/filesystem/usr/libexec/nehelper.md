## nehelper

> `/usr/libexec/nehelper`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2063.120.19.0.0
-  __TEXT.__text: 0x234ec
+2063.140.4.0.0
+  __TEXT.__text: 0x23590
   __TEXT.__auth_stubs: 0xe10
   __TEXT.__delay_helper: 0xc8
   __TEXT.__objc_stubs: 0x2280
   __TEXT.__objc_methlist: 0x43c
   __TEXT.__const: 0x140
-  __TEXT.__gcc_except_tab: 0x900
+  __TEXT.__gcc_except_tab: 0x910
   __TEXT.__objc_methname: 0x1bd9
-  __TEXT.__oslogstring: 0x3e40
+  __TEXT.__oslogstring: 0x3e89
   __TEXT.__cstring: 0x3143
   __TEXT.__objc_classname: 0x1a5
   __TEXT.__objc_methtype: 0x273

   - /usr/lib/libobjc.A.dylib
   Functions: 241
   Symbols:   310
-  CStrings:  1214
+  CStrings:  1215
 
Functions:
~ sub_100012cc8 : 2876 -> 3040
CStrings:
+ "Allowing local network request for bundle ID %@, not found on the device"
```
