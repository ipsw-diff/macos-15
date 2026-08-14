## CascadeSets

> `/System/Library/PrivateFrameworks/CascadeSets.framework/Versions/A/CascadeSets`

```diff

-166.22.1.0.0
-  __TEXT.__text: 0x54d6c
+166.23.0.1.0
+  __TEXT.__text: 0x54f88
   __TEXT.__auth_stubs: 0x7d0
-  __TEXT.__objc_methlist: 0x44cc
+  __TEXT.__objc_methlist: 0x44dc
   __TEXT.__const: 0x1c0
-  __TEXT.__gcc_except_tab: 0x1134
-  __TEXT.__cstring: 0x39e6
-  __TEXT.__oslogstring: 0x4725
+  __TEXT.__gcc_except_tab: 0x1130
+  __TEXT.__cstring: 0x3a21
+  __TEXT.__oslogstring: 0x4765
   __TEXT.__dlopen_cstrs: 0x278
-  __TEXT.__unwind_info: 0x13d0
+  __TEXT.__unwind_info: 0x13d8
   __TEXT.__objc_classname: 0xac2
-  __TEXT.__objc_methname: 0x9af1
+  __TEXT.__objc_methname: 0x9b18
   __TEXT.__objc_methtype: 0x1da1
-  __TEXT.__objc_stubs: 0x6a80
-  __DATA_CONST.__got: 0x480
+  __TEXT.__objc_stubs: 0x6ac0
+  __DATA_CONST.__got: 0x488
   __DATA_CONST.__const: 0x518
   __DATA_CONST.__objc_classlist: 0x338
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0xe8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x22f0
+  __DATA_CONST.__objc_selrefs: 0x2300
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x2b8
   __DATA_CONST.__objc_arraydata: 0x38
   __AUTH_CONST.__auth_got: 0x400
   __AUTH_CONST.__const: 0x10f0
-  __AUTH_CONST.__cfstring: 0x31a0
+  __AUTH_CONST.__cfstring: 0x31e0
   __AUTH_CONST.__objc_const: 0xa9e0
   __AUTH_CONST.__objc_intobj: 0x3c0
   __AUTH_CONST.__objc_arrayobj: 0x48

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   Functions: 1831
-  Symbols:   4043
-  CStrings:  2761
+  Symbols:   4047
+  CStrings:  2766
 
Symbols:
+ +[CCDataResource _databaseExistsAtURL:error:]
+ -[CCDataResource databaseFileExists:]
+ -[CCDataResourceWriter _createDatabaseWithLocalDeviceSite:]
+ _NSLocalizedFailureReasonErrorKey
+ _objc_msgSend$_createDatabaseWithLocalDeviceSite:
+ _objc_msgSend$_databaseExistsAtURL:error:
+ _objc_msgSend$databaseFileExists:
+ _objc_msgSend$localizedFailureReason
- +[CCDataResource databaseExistsAtURL:]
- -[CCDataResourceWriter _createDatabaseIfNotExistsWithLocalDeviceSite:]
- _objc_msgSend$_createDatabaseIfNotExistsWithLocalDeviceSite:
- _objc_msgSend$databaseExistsAtURL:
CStrings:
+ "%@ Could not prepare resource: %@"
+ "%@ Prepared resource: %@"
+ "%@ Resource %@ has not been prepared yet (%@)"
+ "%@ Resource generation counter incremented to %@"
+ "(%@) Database not found: %@"
+ "Database does not exist at path: %s error: %s"
+ "Database: %s"
+ "_createDatabaseWithLocalDeviceSite:"
+ "_databaseExistsAtURL:error:"
+ "databaseFileExists:"
+ "localizedFailureReason"
- "(%@) Database already exists at path: %@"
- "(%@) Database not found"
- "Could not prepare resource: %@"
- "Prepared resource: %@"
- "_createDatabaseIfNotExistsWithLocalDeviceSite:"
- "databaseExistsAtURL:"
```
