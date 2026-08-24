## storeuid

> `/System/Library/PrivateFrameworks/CommerceKit.framework/Versions/Current/Resources/storeuid.app/Contents/MacOS/storeuid`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

 715.5.1.0.0
-  __TEXT.__text: 0xa048
-  __TEXT.__auth_stubs: 0x540
-  __TEXT.__objc_stubs: 0x1f60
+  __TEXT.__text: 0xa724
+  __TEXT.__auth_stubs: 0x560
+  __TEXT.__objc_stubs: 0x1fc0
   __TEXT.__objc_methlist: 0xecc
-  __TEXT.__cstring: 0x187a
-  __TEXT.__objc_methname: 0x32fc
+  __TEXT.__cstring: 0x1a9c
+  __TEXT.__objc_methname: 0x3348
   __TEXT.__objc_classname: 0x2cf
   __TEXT.__objc_methtype: 0x1a5c
-  __TEXT.__const: 0x50
+  __TEXT.__const: 0x58
   __TEXT.__oslogstring: 0x56b
   __TEXT.__gcc_except_tab: 0x1ac
   __TEXT.__unwind_info: 0x2e8
-  __DATA_CONST.__auth_got: 0x2b0
+  __DATA_CONST.__auth_got: 0x2c0
   __DATA_CONST.__got: 0x1d8
   __DATA_CONST.__auth_ptr: 0x8
   __DATA_CONST.__const: 0x7a8
-  __DATA_CONST.__cfstring: 0x1080
+  __DATA_CONST.__cfstring: 0x11e0
   __DATA_CONST.__objc_classlist: 0x60
   __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_superrefs: 0x48
   __DATA_CONST.__objc_doubleobj: 0x10
   __DATA.__objc_const: 0x2c70
-  __DATA.__objc_selrefs: 0xd38
+  __DATA.__objc_selrefs: 0xd50
   __DATA.__objc_ivar: 0x94
   __DATA.__objc_data: 0x3c0
   __DATA.__data: 0x6c0

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   Functions: 201
-  Symbols:   162
-  CStrings:  895
+  Symbols:   164
+  CStrings:  909
 
Symbols:
+ _sqlite3_column_double
+ _sqlite3_column_text
Functions:
~ sub_10000477c : 876 -> 2632
CStrings:
+ "Error fetching app review bag values - %@"
+ "Review request denied for %@. Already reviewed."
+ "Review request denied for %@. Could not validate request - %s"
+ "Review request denied for %@. Primary account: %@."
+ "Review request denied for %@. Too many requests."
+ "Review request denied for %@. Version was reviewed."
+ "SELECT bundle_version, reviewed, timestamp FROM review_request WHERE bundle_id = ? ORDER BY timestamp DESC;"
+ "bagValuesForKeys:error:"
+ "dateWithTimeIntervalSinceNow:"
+ "inAppReviewRequestLimitWindow"
+ "inAppReviewRequestsPerWindow"
+ "inAppReviewRequireNewVersionAfterReview"
+ "inAppReviewRequiredDaysAfterReview"
+ "timeIntervalSince1970"
```
