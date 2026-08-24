## SyncedDefaultsDaemon

> `/System/Library/PrivateFrameworks/SyncedDefaultsDaemon.framework/Versions/A/SyncedDefaultsDaemon`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methtype`

```diff

-2260.11.0.0.0
-  __TEXT.__text: 0x3cc7c
-  __TEXT.__auth_stubs: 0x970
-  __TEXT.__objc_methlist: 0x16b0
+2260.12.0.0.0
+  __TEXT.__text: 0x3ca88
+  __TEXT.__auth_stubs: 0x980
+  __TEXT.__objc_methlist: 0x16c0
   __TEXT.__const: 0x136
-  __TEXT.__gcc_except_tab: 0x1104
-  __TEXT.__cstring: 0x2169
-  __TEXT.__oslogstring: 0x6ce1
+  __TEXT.__gcc_except_tab: 0x10e8
+  __TEXT.__cstring: 0x2199
+  __TEXT.__oslogstring: 0x6c1e
   __TEXT.__dlopen_cstrs: 0xb5
   __TEXT.__swift5_typeref: 0x5
   __TEXT.__unwind_info: 0xbf8
   __TEXT.__objc_classname: 0x1c8
-  __TEXT.__objc_methname: 0x5d03
+  __TEXT.__objc_methname: 0x5d1e
   __TEXT.__objc_methtype: 0xd3b
-  __TEXT.__objc_stubs: 0x4f20
+  __TEXT.__objc_stubs: 0x4f40
   __DATA_CONST.__got: 0x430
   __DATA_CONST.__const: 0x1c0
   __DATA_CONST.__objc_classlist: 0x68
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1700
+  __DATA_CONST.__objc_selrefs: 0x1708
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x38
   __DATA_CONST.__objc_arraydata: 0x1f8
-  __AUTH_CONST.__auth_got: 0x4c8
+  __AUTH_CONST.__auth_got: 0x4d0
   __AUTH_CONST.__const: 0xcd0
   __AUTH_CONST.__cfstring: 0x2180
   __AUTH_CONST.__objc_const: 0x1890

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 1171
-  Symbols:   2019
-  CStrings:  1889
+  Functions: 1167
+  Symbols:   2024
+  CStrings:  1888
 
Symbols:
+ -[SYDKeyValue updateWithServerRecord:]
+ -[SYDSyncManager getSyncEngineStateSerialization:error:]
+ GCC_except_table13
+ GCC_except_table20
+ GCC_except_table26
+ GCC_except_table32
+ GCC_except_table64
+ GCC_except_table68
+ GCC_except_table98
+ _objc_msgSend$getSyncEngineStateSerialization:error:
+ _objc_msgSend$updateWithServerRecord:
+ _os_transaction_create
- -[SYDKeyValue setServerSystemFieldsRecordIfNewer:]
- GCC_except_table12
- GCC_except_table19
- GCC_except_table3
- GCC_except_table36
- GCC_except_table97
- _objc_msgSend$setServerSystemFieldsRecordIfNewer:
CStrings:
+ "B32@0:8^@16^@24"
+ "Mismatched recordIDs. Keeping current record: %@, ignoring new record: %@"
+ "No current record, using new record: %@"
+ "No record provided to compare."
+ "Replacing current system fields record: %@ with new system fields record: %@"
+ "com.apple.kvs.daemon.initializeKnownSyncManagers"
+ "getSyncEngineStateSerialization:error:"
+ "updateWithServerRecord:"
- "B32@0:8^B16^@24"
- "Failed to unarchive state serialization: %@"
- "No current modification date on system fields record for %@"
- "No current system fields record for %@"
- "Not replacing local system fields record for %@: current=%@ other=%@"
- "Replacing local system fields record for %@: current=%@ other=%@"
- "Trying to set server record if newer, but no other record"
- "Trying to set server record using record with a different ID. current=%@ other=%@"
- "setServerSystemFieldsRecordIfNewer:"
```
