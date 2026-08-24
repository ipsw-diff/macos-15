## AMSFollowUpExtension

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/PlugIns/AMSFollowUpExtension.appex/Contents/MacOS/AMSFollowUpExtension`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`

```diff

-6.5.10.0.0
-  __TEXT.__text: 0x1e50
+6.6.7.0.0
+  __TEXT.__text: 0x2004
   __TEXT.__auth_stubs: 0x190
-  __TEXT.__objc_stubs: 0x6e0
+  __TEXT.__objc_stubs: 0x700
   __TEXT.__objc_methlist: 0x140
   __TEXT.__const: 0x20
   __TEXT.__gcc_except_tab: 0x14
   __TEXT.__cstring: 0xcb
-  __TEXT.__objc_methname: 0x56f
-  __TEXT.__oslogstring: 0x2ac
+  __TEXT.__objc_methname: 0x57b
+  __TEXT.__oslogstring: 0x2fa
   __TEXT.__objc_classname: 0x1c
   __TEXT.__objc_methtype: 0xb6
-  __TEXT.__unwind_info: 0xd0
+  __TEXT.__unwind_info: 0xc8
   __DATA_CONST.__auth_got: 0xd8
   __DATA_CONST.__got: 0x68
   __DATA_CONST.__const: 0x190

   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__objc_dictobj: 0x28
   __DATA.__objc_const: 0x1c0
-  __DATA.__objc_selrefs: 0x1e0
+  __DATA.__objc_selrefs: 0x1e8
   __DATA.__objc_ivar: 0x18
   __DATA.__objc_data: 0x50
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/libobjc.A.dylib
   Functions: 44
   Symbols:   51
-  CStrings:  108
+  CStrings:  110
 
Functions:
~ sub_100002504 : 604 -> 608
~ sub_100002778 -> sub_10000277c : 572 -> 896
~ sub_1000029b4 -> sub_100002afc : 16 -> 72
~ sub_1000029c4 -> sub_100002b44 : 12 -> 64
CStrings:
+ "%{public}@: [%{public}@] Clearing follow up due to shouldClear despite error."
+ "shouldClear"
```
