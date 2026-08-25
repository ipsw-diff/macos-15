## AppleVNCServer

> `/System/Library/CoreServices/RemoteManagement/AppleVNCServer.bundle/Contents/MacOS/AppleVNCServer`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-709.5.2.0.0
-  __TEXT.__text: 0x7b090
+709.6.2.0.0
+  __TEXT.__text: 0x7c4c8
   __TEXT.__auth_stubs: 0x2580
-  __TEXT.__objc_stubs: 0x2960
-  __TEXT.__objc_methlist: 0xfb8
-  __TEXT.__cstring: 0x1c537
-  __TEXT.__oslogstring: 0xbc25
+  __TEXT.__objc_stubs: 0x29e0
+  __TEXT.__objc_methlist: 0xfe8
+  __TEXT.__cstring: 0x1c6db
+  __TEXT.__oslogstring: 0xbe28
   __TEXT.__const: 0x2070
   __TEXT.__objc_classname: 0x162
-  __TEXT.__objc_methname: 0x3604
-  __TEXT.__objc_methtype: 0x2599
+  __TEXT.__objc_methname: 0x3703
+  __TEXT.__objc_methtype: 0x25a7
   __TEXT.__gcc_except_tab: 0xc0
-  __TEXT.__unwind_info: 0x9e8
+  __TEXT.__unwind_info: 0x9f8
   __DATA_CONST.__auth_got: 0x12d0
-  __DATA_CONST.__got: 0x410
+  __DATA_CONST.__got: 0x418
   __DATA_CONST.__auth_ptr: 0x28
   __DATA_CONST.__const: 0xa90
-  __DATA_CONST.__cfstring: 0x16c0
+  __DATA_CONST.__cfstring: 0x1700
   __DATA_CONST.__objc_classlist: 0x50
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arraydata: 0x28
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA.__objc_const: 0x15d0
-  __DATA.__objc_selrefs: 0xda0
+  __DATA.__objc_selrefs: 0xde0
   __DATA.__objc_ivar: 0xdc
   __DATA.__objc_data: 0x320
   __DATA.__data: 0x34e8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1017
-  Symbols:   741
-  CStrings:  3304
+  Functions: 1026
+  Symbols:   742
+  CStrings:  3328
 
Symbols:
+ _kODAttributeTypeAllTypes
CStrings:
+ "-[ODHelper localUserRecordByShortName:]"
+ "-[ODHelper localUserUIDs]"
+ "-[ODHelper newLocalUserWithName:attributes:password:]"
+ "-[ODHelper setARDPrivileges:forUserRecord:]"
+ "changePassword error %s"
+ "changePassword:toPassword:error:"
+ "createRecordWithRecordType error %s"
+ "createRecordWithRecordType:name:attributes:error:"
+ "created user %s"
+ "localUserRecordByShortName:"
+ "localUserUIDs"
+ "naprivs"
+ "newLocalUserWithName:attributes:password:"
+ "no record name"
+ "recordWithRecordType error %s"
+ "setARDPrivileges:forUserRecord:"
+ "setValue:forAttribute: error %s"
+ "setValue:forAttribute:error:"
+ "synchronizeAndReturnError %s"
+ "synchronizeAndReturnError:"
+ "unable to create new user"
+ "unable to set new user password"
+ "unknown"
+ "v28@0:8I16@20"
```
