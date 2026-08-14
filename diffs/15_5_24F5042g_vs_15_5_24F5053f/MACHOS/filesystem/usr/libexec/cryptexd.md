## cryptexd

> `/usr/libexec/cryptexd`

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

-493.120.2.0.0
-  __TEXT.__text: 0x5a75c
+493.120.3.0.0
+  __TEXT.__text: 0x5a77c
   __TEXT.__auth_stubs: 0x1de0
   __TEXT.__objc_stubs: 0x2080
   __TEXT.__objc_methlist: 0xafc

   __TEXT.__objc_methname: 0x1e1d
   __TEXT.__objc_classname: 0x132
   __TEXT.__objc_methtype: 0x501
-  __TEXT.__cstring: 0x3dc7
+  __TEXT.__cstring: 0x3dc9
   __TEXT.__oslogstring: 0xb04b
   __TEXT.__unwind_info: 0xdb8
   __DATA_CONST.__auth_got: 0xf00
Functions:
~ sub_1000233b4 : 612 -> 628
~ sub_100025ec4 -> sub_100025ed4 : 296 -> 312
CStrings:
+ "493.120.3"
+ "@(#)VERSION:Darwin Cryptex Manager Version 2.0.0: Sun Apr  6 19:19:23 PDT 2025; root:libcryptex_executables-493.120.3~316/cryptexd/RELEASE_ARM64E"
+ "Darwin Cryptex Manager Version 2.0.0: Sun Apr  6 19:19:23 PDT 2025; root:libcryptex_executables-493.120.3~316/cryptexd/RELEASE_ARM64E"
- "493.120.2"
- "@(#)VERSION:Darwin Cryptex Manager Version 2.0.0: Fri Mar 21 20:12:19 PDT 2025; root:libcryptex_executables-493.120.2~72/cryptexd/RELEASE_ARM64E"
- "Darwin Cryptex Manager Version 2.0.0: Fri Mar 21 20:12:19 PDT 2025; root:libcryptex_executables-493.120.2~72/cryptexd/RELEASE_ARM64E"
```
