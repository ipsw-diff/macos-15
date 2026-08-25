## sysinfocachegen

> `/System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Support/sysinfocachegen`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-709.5.2.0.0
-  __TEXT.__text: 0xdf70
+709.6.2.0.0
+  __TEXT.__text: 0xf3b4
   __TEXT.__auth_stubs: 0xdf0
-  __TEXT.__objc_stubs: 0x720
-  __TEXT.__objc_methlist: 0x1f4
-  __TEXT.__cstring: 0x458d
-  __TEXT.__oslogstring: 0x268
-  __TEXT.__const: 0xf0
-  __TEXT.__objc_methname: 0x6d0
+  __TEXT.__objc_stubs: 0x7a0
+  __TEXT.__objc_methlist: 0x224
+  __TEXT.__cstring: 0x4734
+  __TEXT.__oslogstring: 0x46b
+  __TEXT.__const: 0xf8
+  __TEXT.__objc_methname: 0x7cf
   __TEXT.__objc_classname: 0x11
-  __TEXT.__objc_methtype: 0xcb
-  __TEXT.__unwind_info: 0x1c8
+  __TEXT.__objc_methtype: 0xea
+  __TEXT.__unwind_info: 0x1d8
   __DATA_CONST.__auth_got: 0x700
-  __DATA_CONST.__got: 0x148
+  __DATA_CONST.__got: 0x158
   __DATA_CONST.__const: 0x1f0
-  __DATA_CONST.__cfstring: 0x1140
+  __DATA_CONST.__cfstring: 0x1180
   __DATA_CONST.__objc_classlist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x10
   __DATA_CONST.__objc_arraydata: 0x28
   __DATA_CONST.__objc_arrayobj: 0x18
   __DATA.__objc_const: 0x270
-  __DATA.__objc_selrefs: 0x260
+  __DATA.__objc_selrefs: 0x2a0
   __DATA.__objc_ivar: 0x1c
   __DATA.__objc_data: 0xa0
   __DATA.__data: 0xc8

   - /System/Library/PrivateFrameworks/DiagnosticLogCollection.framework/Versions/A/DiagnosticLogCollection
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 127
-  Symbols:   272
-  CStrings:  966
+  Functions: 137
+  Symbols:   274
+  CStrings:  992
 
Symbols:
+ _kODAttributeTypeAllTypes
+ _kODAttributeTypeUniqueID
CStrings:
+ "%u"
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
+ "v40@0:8@16@24@32"
```
