## screensharingd

> `/System/Library/CoreServices/RemoteManagement/screensharingd.bundle/Contents/MacOS/screensharingd`

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
-  __TEXT.__text: 0x74028
+709.6.2.0.0
+  __TEXT.__text: 0x75460
   __TEXT.__auth_stubs: 0x1dc0
-  __TEXT.__objc_stubs: 0x20a0
-  __TEXT.__objc_methlist: 0xd00
+  __TEXT.__objc_stubs: 0x2120
+  __TEXT.__objc_methlist: 0xd30
   __TEXT.__const: 0x2348
-  __TEXT.__oslogstring: 0xb0db
-  __TEXT.__cstring: 0x13573
+  __TEXT.__oslogstring: 0xb2de
+  __TEXT.__cstring: 0x1370f
   __TEXT.__gcc_except_tab: 0x1e0
-  __TEXT.__objc_methname: 0x2218
+  __TEXT.__objc_methname: 0x2317
   __TEXT.__objc_classname: 0xe5
-  __TEXT.__objc_methtype: 0x6a1
-  __TEXT.__unwind_info: 0x9a0
+  __TEXT.__objc_methtype: 0x6c0
+  __TEXT.__unwind_info: 0x9a8
   __DATA_CONST.__auth_got: 0xef0
-  __DATA_CONST.__got: 0x308
+  __DATA_CONST.__got: 0x310
   __DATA_CONST.__auth_ptr: 0x28
   __DATA_CONST.__const: 0xdb0
-  __DATA_CONST.__cfstring: 0x1440
+  __DATA_CONST.__cfstring: 0x1480
   __DATA_CONST.__objc_classlist: 0x48
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_arraydata: 0x28
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA.__objc_const: 0x1070
-  __DATA.__objc_selrefs: 0xa98
+  __DATA.__objc_selrefs: 0xad8
   __DATA.__objc_ivar: 0xb0
   __DATA.__objc_data: 0x2d0
   __DATA.__data: 0x6b8

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1036
-  Symbols:   584
-  CStrings:  2908
+  Functions: 1045
+  Symbols:   585
+  CStrings:  2932
 
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
+ "v28@0:8I16@20"
+ "v40@0:8@16@24@32"
```
