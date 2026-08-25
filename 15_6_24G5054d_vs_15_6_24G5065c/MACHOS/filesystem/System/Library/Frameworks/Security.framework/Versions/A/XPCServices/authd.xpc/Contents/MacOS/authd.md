## authd

> `/System/Library/Frameworks/Security.framework/Versions/A/XPCServices/authd.xpc/Contents/MacOS/authd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-61439.140.8.0.0
-  __TEXT.__text: 0x2aeb8
+61439.140.10.0.0
+  __TEXT.__text: 0x2b204
   __TEXT.__auth_stubs: 0x1450
   __TEXT.__objc_stubs: 0xa80
   __TEXT.__objc_methlist: 0x2f4
   __TEXT.__const: 0xb20
   __TEXT.__dlopen_cstrs: 0x299
-  __TEXT.__cstring: 0x3015
+  __TEXT.__cstring: 0x30d3
   __TEXT.__gcc_except_tab: 0xa18
   __TEXT.__oslogstring: 0x4c4d
   __TEXT.__objc_classname: 0x40

   - /usr/lib/libsqlite3.dylib
   Functions: 539
   Symbols:   397
-  CStrings:  1120
+  CStrings:  1125
 
Functions:
~ sub_10000a31c : 1704 -> 2548
CStrings:
+ "com.apple.trust-settings.user"
+ "hardcoded-authenticate-session-owner"
+ "hardcoded-entitled-session-owner"
+ "hardcoded-entitled-session-owner-or-authenticate-session-owner"
+ "hardcoded-is-session-owner"
```
