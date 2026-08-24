## com.apple.security.pboxd

> `/System/Library/PrivateFrameworks/RemoteViewServices.framework/XPCServices/com.apple.security.pboxd.xpc/Contents/MacOS/com.apple.security.pboxd`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-181.1.0.0.0
-  __TEXT.__text: 0x1ab60
+181.2.0.0.0
+  __TEXT.__text: 0x1a12c
   __TEXT.__auth_stubs: 0xb70
-  __TEXT.__objc_stubs: 0x2b80
-  __TEXT.__objc_methlist: 0xe50
-  __TEXT.__objc_methname: 0x3073
+  __TEXT.__objc_stubs: 0x2b40
+  __TEXT.__objc_methlist: 0xe40
+  __TEXT.__objc_methname: 0x300f
   __TEXT.__cstring: 0x256e
   __TEXT.__objc_classname: 0x224
-  __TEXT.__objc_methtype: 0xa80
+  __TEXT.__objc_methtype: 0xa6e
   __TEXT.__gcc_except_tab: 0x6cc
   __TEXT.__const: 0x8
-  __TEXT.__unwind_info: 0x208
+  __TEXT.__unwind_info: 0x200
   __DATA_CONST.__auth_got: 0x5c8
-  __DATA_CONST.__got: 0x3f8
+  __DATA_CONST.__got: 0x3e0
   __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__const: 0x488
   __DATA_CONST.__cfstring: 0x1900

   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA.__objc_const: 0x1bb0
-  __DATA.__objc_selrefs: 0xee8
+  __DATA.__objc_selrefs: 0xed8
   __DATA.__objc_ivar: 0xf0
   __DATA.__objc_data: 0x460
   __DATA.__data: 0x290

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 280
-  Symbols:   329
-  CStrings:  978
+  Functions: 279
+  Symbols:   326
+  CStrings:  975
 
Symbols:
- _PBOXRelatedItemDuplicateRequestRequestDuplicateItemKey
- _PBOXRelatedItemDuplicateRequestRequestOriginalItemKey
- _SANDBOX_CHECK_NO_REPORT
Functions:
~ sub_10001373c : 2180 -> 132
- sub_100013fc0
CStrings:
- "@40@0:8@16@24^@32"
- "_requestDuplicateDocument:withDuplicateName:error:"
- "_validateDuplicateDocumentName:withOriginalName:"
```
