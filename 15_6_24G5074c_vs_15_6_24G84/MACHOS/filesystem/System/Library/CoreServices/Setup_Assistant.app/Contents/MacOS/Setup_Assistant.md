## Setup Assistant

> `/System/Library/CoreServices/Setup Assistant.app/Contents/MacOS/Setup Assistant`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 7407.4.15.0.0
-  __TEXT.__text: 0x18085c
+  __TEXT.__text: 0x180868
   __TEXT.__auth_stubs: 0x2470
   __TEXT.__objc_stubs: 0x21400
   __TEXT.__objc_methlist: 0x147dc
   __TEXT.__objc_classname: 0x1e2d
   __TEXT.__objc_methname: 0x3194b
   __TEXT.__objc_methtype: 0x5f13
-  __TEXT.__cstring: 0x31ed9
+  __TEXT.__cstring: 0x31eb9
   __TEXT.__ustring: 0x1ba
   __TEXT.__const: 0x5604
   __TEXT.__gcc_except_tab: 0x15f8

   - /usr/lib/swift/libswiftunistd.dylib
   Functions: 10181
   Symbols:   1300
-  CStrings:  14635
+  CStrings:  14634
 
Functions:
~ sub_100125bac : 924 -> 936
CStrings:
- "macOS Sequoia Beta"
```
