## IMDPersistence

> `/System/Library/PrivateFrameworks/IMDPersistence.framework/Versions/A/IMDPersistence`

```diff

-1402.600.22.0.0
-  __TEXT.__text: 0x12b0e0
+1402.600.31.0.0
+  __TEXT.__text: 0x12aecc
   __TEXT.__auth_stubs: 0x2680
   __TEXT.__objc_methlist: 0x46ac
-  __TEXT.__const: 0xba0
-  __TEXT.__gcc_except_tab: 0xe29c
-  __TEXT.__cstring: 0x3a7e1
-  __TEXT.__oslogstring: 0x19d28
+  __TEXT.__const: 0xb90
+  __TEXT.__gcc_except_tab: 0xe228
+  __TEXT.__cstring: 0x3a671
+  __TEXT.__oslogstring: 0x19b38
   __TEXT.__dlopen_cstrs: 0x166
   __TEXT.__ustring: 0x434
   __TEXT.__swift5_typeref: 0x1fb

   __TEXT.__swift5_fieldmd: 0xe4
   __TEXT.__swift5_types: 0x18
   __TEXT.__swift5_capture: 0xe4
-  __TEXT.__unwind_info: 0x4e98
+  __TEXT.__unwind_info: 0x4ea8
   __TEXT.__eh_frame: 0x178
   __TEXT.__objc_classname: 0xbd8
-  __TEXT.__objc_methname: 0x11365
+  __TEXT.__objc_methname: 0x1137a
   __TEXT.__objc_methtype: 0x2784
-  __TEXT.__objc_stubs: 0xdf40
-  __DATA_CONST.__got: 0xfe0
-  __DATA_CONST.__const: 0xe808
+  __TEXT.__objc_stubs: 0xdf60
+  __DATA_CONST.__got: 0xfb8
+  __DATA_CONST.__const: 0xe800
   __DATA_CONST.__objc_classlist: 0x2c8
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x118
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3ef8
+  __DATA_CONST.__objc_selrefs: 0x3f00
   __DATA_CONST.__objc_protorefs: 0x70
   __DATA_CONST.__objc_superrefs: 0x120
-  __DATA_CONST.__objc_arraydata: 0x190
+  __DATA_CONST.__objc_arraydata: 0x230
   __AUTH_CONST.__auth_got: 0x1350
-  __AUTH_CONST.__const: 0x4860
-  __AUTH_CONST.__cfstring: 0x11e80
+  __AUTH_CONST.__const: 0x48f0
+  __AUTH_CONST.__cfstring: 0x11f20
   __AUTH_CONST.__objc_const: 0x6b48
   __AUTH_CONST.__objc_arrayobj: 0x90
   __AUTH_CONST.__objc_intobj: 0x138
+  __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH.__objc_data: 0x1418
   __AUTH.__data: 0xdc0
   __DATA.__objc_ivar: 0x230

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 4823
-  Symbols:   2416
-  CStrings:  7493
+  Functions: 4826
+  Symbols:   2410
+  CStrings:  7495
 
Symbols:
+ _IMDMessageRecordCalculateLocalCloudKitStatisticsAsync
+ _OBJC_CLASS_$_NSConstantDictionary
- _IMDMessageRecordCalculateTotalCounts
- _IMDMessageRecordCloudKitStatisticUnresolvedAttachmentCountKey
- _IMDMessageRecordCloudKitStatisticUnresolvedChatCountKey
- _IMDMessageRecordCloudKitStatisticUnresolvedCountKey
- _IMDMessageRecordCloudKitStatisticUnresolvedMessageCountKey
- _IMDMessageRecordCloudKitStatisticUnresolvedRecoverableMessageCountKey
- ___XPCServerIMDMessageRecordCalculateTotalCounts_IPCAction
- ___syncXPCIMDMessageRecordCalculateTotalCounts_IPCAction
CStrings:
+ "Calculated sync stats in %f seconds. All Records: %lld of %lld, %lld remaining. All Stats: %@"
+ "att"
+ "delAtt"
+ "delChat"
+ "delMsg"
+ "delRecovMsg"
+ "recovMsg"
+ "removeObjectAtIndex:"
+ "updT1"
+ "updT2"
- "Calculated sync stats in %f seconds. All Records: %lld of %lld, %lld remaining, %lld unresolved. Messages : %lld of %lld, %lld remaining, %lld unresolved. Chats : %lld of %lld, %lld remaining, %lld unresolved. Attachments : %lld of %lld, %lld remaining, %lld unresolved."
- "Calculated total counts in %f seconds. All Records: %lld, Messages: %lld, Chats: %lld, Attachments: %lld, RecoverableMessages: %lld"
- "Expected dictionary of record totals is nil"
- "Expecting statistics dictionary to calculate unresolved counts, but found nil, returning 0"
- "IMDMessageRecordCalculateTotalCounts loaded totals: %@"
- "SELECT COUNT(*) FROM attachment;"
- "SELECT COUNT(*) FROM chat;"
- "SELECT SUM(total_count) AS total_count FROM ( SELECT COUNT(*) AS total_count FROM chat_recoverable_message_join AS crmj JOIN chat AS c ON c.ROWID = crmj.chat_id JOIN message AS m ON m.ROWID = crmj.message_id UNION ALL SELECT COUNT(1) AS total_count FROM recoverable_message_part AS rmp JOIN chat AS c ON c.ROWID = rmp.chat_id JOIN message AS m ON m.ROWID = rmp.message_id);"
```
