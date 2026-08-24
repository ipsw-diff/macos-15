## identityservicesd

> `/System/Library/PrivateFrameworks/IDS.framework/identityservicesd.app/Contents/MacOS/identityservicesd`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`

```diff

-1926.600.41.0.0
-  __TEXT.__text: 0x81668c
+1926.700.31.0.0
+  __TEXT.__text: 0x8169cc
   __TEXT.__auth_stubs: 0x5180
-  __TEXT.__objc_stubs: 0x41040
-  __TEXT.__objc_methlist: 0x27a48
-  __TEXT.__const: 0x76f50
-  __TEXT.__objc_methname: 0x6c831
-  __TEXT.__oslogstring: 0x73c32
-  __TEXT.__objc_classname: 0x40aa
+  __TEXT.__objc_stubs: 0x40f60
+  __TEXT.__objc_methlist: 0x27a00
+  __TEXT.__const: 0x77010
+  __TEXT.__objc_methname: 0x6c711
+  __TEXT.__oslogstring: 0x73b32
+  __TEXT.__objc_classname: 0x4082
   __TEXT.__objc_methtype: 0x106ad
-  __TEXT.__gcc_except_tab: 0x28d2c
-  __TEXT.__cstring: 0x5263f
+  __TEXT.__gcc_except_tab: 0x28d30
+  __TEXT.__cstring: 0x5261f
   __TEXT.__dlopen_cstrs: 0x47
   __TEXT.__ustring: 0x4f6
   __TEXT.__swift5_typeref: 0x3ade

   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift_as_entry: 0x40
   __TEXT.__swift_as_ret: 0x3c
-  __TEXT.__unwind_info: 0xf128
+  __TEXT.__unwind_info: 0xf120
   __TEXT.__eh_frame: 0x3f3c
   __DATA_CONST.__auth_got: 0x28d0
   __DATA_CONST.__got: 0x31b8
-  __DATA_CONST.__auth_ptr: 0x748
+  __DATA_CONST.__auth_ptr: 0x710
   __DATA_CONST.__const: 0x21840
-  __DATA_CONST.__cfstring: 0x30ce0
-  __DATA_CONST.__objc_classlist: 0xe70
+  __DATA_CONST.__cfstring: 0x30ca0
+  __DATA_CONST.__objc_classlist: 0xe68
   __DATA_CONST.__objc_catlist: 0x58
   __DATA_CONST.__objc_protolist: 0x6d0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x110
-  __DATA_CONST.__objc_superrefs: 0xad0
+  __DATA_CONST.__objc_superrefs: 0xac8
   __DATA_CONST.__objc_intobj: 0x18c0
   __DATA_CONST.__objc_arraydata: 0x618
   __DATA_CONST.__objc_arrayobj: 0x318
   __DATA_CONST.__objc_doubleobj: 0x10
   __DATA_CONST.__objc_dictobj: 0x50
-  __DATA.__objc_const: 0x3dc60
-  __DATA.__objc_selrefs: 0x14550
-  __DATA.__objc_ivar: 0x2f3c
-  __DATA.__objc_data: 0xb358
-  __DATA.__data: 0x8f28
+  __DATA.__objc_const: 0x3db38
+  __DATA.__objc_selrefs: 0x14520
+  __DATA.__objc_ivar: 0x2f30
+  __DATA.__objc_data: 0xb308
+  __DATA.__data: 0x8e58
   __DATA.__common: 0xe58
   __DATA.__bss: 0x9250
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 20078
+  Functions: 20072
   Symbols:   2495
-  CStrings:  28804
+  CStrings:  28790
 
CStrings:
+ "23:11:13"
+ "<%@> link:%@ reportNoSessionState:%@"
+ "CREATE INDEX IF NOT EXISTS incoming_message_message_identifier_idx ON incoming_message(message_identifier);"
+ "CREATE INDEX IF NOT EXISTS outgoing_message_similarity_idx ON outgoing_message(account_guid, priority, is_sent);"
+ "Jun  3 2025"
+ "SELECT ROWID, guid, topic, from_id, message_data, date, is_local, message_identifier, expiration_date, control_category FROM incoming_message WHERE message_identifier = ? LIMIT 1"
+ "link:reportNoSessionState:"
+ "provisionPsueudonymForURI -- sentinel alias is an invalid alias -- failing"
- "23:40:40"
- "Apr 18 2025"
- "Finished capturing AutoBugCapture diagnostics for queued query refresh { context: %@, sessionID: %@, error: %@ }"
- "IDSPeerIDQueryHandlerCompletionsForURIs"
- "Query ID %@ queued behind query %@ for URIs: %@, original query start %@"
- "Query with ID %@ has been queued for %f seconds. Allowing next query to skip the queue to try to unblock."
- "SELECT ROWID, guid, topic, from_id, message_data, date, is_local, message_identifier, expiration_date, control_category FROM incoming_message WHERE message_identifier = ? "
- "T@\"NSDate\",&,N,V_queryStart"
- "T@\"NSMutableArray\",R,N,V_completionBlocks"
- "T@\"NSUUID\",&,N,V_queryIdentifier"
- "Triggering AutoBugCapture for queued query refresh, we think a query is stuck!"
- "We think a queued query is blocking the queue!"
- "_queryIdentifier"
- "_queryStart"
- "_triggerAutoBugCaptureForQueuedQueryRefresh"
- "id-query-refresh-queued-query-interval"
- "initWithCompletionArray:queryIdentifier:queryStart:"
- "queryIdentifier"
- "queryStart"
- "setQueryIdentifier:"
- "setQueryStart:"
- "timeToRefreshQueuedQuery"
```
