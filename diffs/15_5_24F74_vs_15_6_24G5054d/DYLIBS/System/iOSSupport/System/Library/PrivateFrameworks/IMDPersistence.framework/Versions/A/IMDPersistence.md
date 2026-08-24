## IMDPersistence

> `/System/iOSSupport/System/Library/PrivateFrameworks/IMDPersistence.framework/Versions/A/IMDPersistence`

```diff

-1402.600.41.1.5
-  __TEXT.__text: 0x11a4e4
+1402.700.41.0.0
+  __TEXT.__text: 0x11a7ac
   __TEXT.__auth_stubs: 0x27d0
-  __TEXT.__objc_methlist: 0x416c
+  __TEXT.__objc_methlist: 0x4174
   __TEXT.__const: 0xb70
-  __TEXT.__cstring: 0x39b51
-  __TEXT.__oslogstring: 0x19c55
+  __TEXT.__cstring: 0x39be1
+  __TEXT.__oslogstring: 0x19cd5
   __TEXT.__gcc_except_tab: 0xe15c
   __TEXT.__ustring: 0x434
   __TEXT.__dlopen_cstrs: 0x166

   __TEXT.__swift5_capture: 0xe4
   __TEXT.__swift5_types: 0x18
   __TEXT.__swift5_reflstr: 0x6f
-  __TEXT.__unwind_info: 0x4d90
+  __TEXT.__unwind_info: 0x4da0
   __TEXT.__eh_frame: 0x178
   __TEXT.__objc_classname: 0xb4a
-  __TEXT.__objc_methname: 0x10726
-  __TEXT.__objc_methtype: 0x24a2
-  __TEXT.__objc_stubs: 0xd960
+  __TEXT.__objc_methname: 0x10756
+  __TEXT.__objc_methtype: 0x24ad
+  __TEXT.__objc_stubs: 0xd980
   __DATA_CONST.__got: 0xf00
   __DATA_CONST.__const: 0x10f80
   __DATA_CONST.__objc_classlist: 0x298
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3c28
+  __DATA_CONST.__objc_selrefs: 0x3c30
   __DATA_CONST.__objc_protorefs: 0x70
   __DATA_CONST.__objc_superrefs: 0xf8
   __DATA_CONST.__objc_arraydata: 0x230
   __AUTH_CONST.__auth_got: 0x13f8
-  __AUTH_CONST.__const: 0x1a90
-  __AUTH_CONST.__cfstring: 0x11360
+  __AUTH_CONST.__const: 0x1ab0
+  __AUTH_CONST.__cfstring: 0x11380
   __AUTH_CONST.__objc_const: 0x6028
   __AUTH_CONST.__objc_intobj: 0x138
   __AUTH_CONST.__objc_arrayobj: 0x90

   __AUTH.__data: 0xdc0
   __DATA.__objc_ivar: 0x190
   __DATA.__data: 0xb70
-  __DATA.__bss: 0x6b8
+  __DATA.__bss: 0x6c8
   __DATA.__common: 0x58
   __DATA_DIRTY.__objc_data: 0x870
   __DATA_DIRTY.__data: 0x80

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 4616
+  Functions: 4620
   Symbols:   2363
-  CStrings:  7231
+  CStrings:  7235
 
CStrings:
+ "@20@0:8B16"
+ "IMDDatabaseClient | Early return: Recently Deleted:storeRecoverableMessagePartWithBody given messageGUID: %@ partBody: %@"
+ "Recently Deleted | Bailing:storeRecoverableMessagePartWithBody will not store empty part"
+ "Recently Deleted | Cannot recover: Could not find attributed body for messageGUID: %@, rebuilding from scratch"
+ "SELECT ROWID from message m                 INNER JOIN chat_message_join cm ON cm.chat_id = ? AND cm.message_id = m.ROWID                 WHERE m.item_type == 0                 AND (m.schedule_type == 0                     OR (m.schedule_type == 2 AND (m.schedule_state != 1 AND m.schedule_state != 2)))                 ORDER BY cm.message_date DESC, cm.message_id DESC LIMIT 1"
+ "SELECT m.ROWID, m.guid, m.text, m.replace, m.service_center, m.handle_id, m.subject, m.country, m.attributedBody, m.version, m.type, m.service, m.account, m.account_guid, m.error, m.date, m.date_read, m.date_delivered, m.is_delivered, m.is_finished, m.is_emote, m.is_from_me, m.is_empty, m.is_delayed, m.is_auto_reply, m.is_prepared, m.is_read, m.is_system_message, m.is_sent, m.has_dd_results, m.is_service_message, m.is_forward, m.was_downgraded, m.is_archive, m.cache_has_attachments, m.cache_roomnames, m.was_data_detected, m.was_deduplicated, m.is_audio_message, m.is_played, m.date_played, m.item_type, m.other_handle, m.group_title, m.group_action_type, m.share_status, m.share_direction, m.is_expirable, m.expire_state, m.message_action_type, m.message_source, m.associated_message_guid, m.associated_message_type, m.balloon_bundle_id, m.payload_data, m.expressive_send_style_id, m.associated_message_range_location, m.associated_message_range_length, m.time_expressive_send_played, m.message_summary_info, m.ck_sync_state, m.ck_record_id, m.ck_record_change_tag, m.destination_caller_id, m.is_corrupt, m.reply_to_guid, m.sort_id, m.is_spam, m.has_unseen_mention, m.thread_originator_guid, m.thread_originator_part, m.syndication_ranges, m.synced_syndication_ranges, m.was_delivered_quietly, m.did_notify_recipient, m.date_retracted, m.date_edited, m.date_recovered, m.was_detonated, m.part_count, m.is_stewie, m.is_sos, m.is_critical, m.bia_reference_id, m.is_kt_verified, m.fallback_hash, m.associated_message_emoji, m.is_pending_satellite_send, m.needs_relay, m.schedule_type, m.schedule_state, m.sent_or_received_off_grid FROM message m  INNER JOIN chat_message_join cm ON cm.message_id = m.rowid  INNER JOIN chat c ON c.ROWID = cm.chat_id  WHERE c.guid = ?  AND m.schedule_type == 2  AND (m.schedule_state == 1 OR m.schedule_state == 2)  ORDER BY cm.message_date ASC LIMIT ?"
+ "SELECT m.ROWID, m.guid, m.text, m.replace, m.service_center, m.handle_id, m.subject, m.country, m.attributedBody, m.version, m.type, m.service, m.account, m.account_guid, m.error, m.date, m.date_read, m.date_delivered, m.is_delivered, m.is_finished, m.is_emote, m.is_from_me, m.is_empty, m.is_delayed, m.is_auto_reply, m.is_prepared, m.is_read, m.is_system_message, m.is_sent, m.has_dd_results, m.is_service_message, m.is_forward, m.was_downgraded, m.is_archive, m.cache_has_attachments, m.cache_roomnames, m.was_data_detected, m.was_deduplicated, m.is_audio_message, m.is_played, m.date_played, m.item_type, m.other_handle, m.group_title, m.group_action_type, m.share_status, m.share_direction, m.is_expirable, m.expire_state, m.message_action_type, m.message_source, m.associated_message_guid, m.associated_message_type, m.balloon_bundle_id, m.payload_data, m.expressive_send_style_id, m.associated_message_range_location, m.associated_message_range_length, m.time_expressive_send_played, m.message_summary_info, m.ck_sync_state, m.ck_record_id, m.ck_record_change_tag, m.destination_caller_id, m.is_corrupt, m.reply_to_guid, m.sort_id, m.is_spam, m.has_unseen_mention, m.thread_originator_guid, m.thread_originator_part, m.syndication_ranges, m.synced_syndication_ranges, m.was_delivered_quietly, m.did_notify_recipient, m.date_retracted, m.date_edited, m.date_recovered, m.was_detonated, m.part_count, m.is_stewie, m.is_sos, m.is_critical, m.bia_reference_id, m.is_kt_verified, m.fallback_hash, m.associated_message_emoji, m.is_pending_satellite_send, m.needs_relay, m.schedule_type, m.schedule_state, m.sent_or_received_off_grid FROM message m  INNER JOIN chat_message_join cm ON cm.message_id = m.rowid  INNER JOIN chat c ON c.ROWID = cm.chat_id  WHERE m.schedule_type == 2  AND (m.schedule_state == 1 OR m.schedule_state == 2)  ORDER BY cm.message_date ASC LIMIT ?"
+ "_messageKeyPathsToColumnsQueryingChatJoinTable:"
+ "chat_message_join.message_date"
- "IMDDatabaseClient | Early return: Recently Deleted:storeRecoverableMessagePartWithBody given messageGUID: %@"
- "Recently Deleted | Cannot recover: Could not find attributed body for messageGUID: %@"
- "SELECT ROWID from message m                 WHERE m.item_type == 0                 AND (m.schedule_type == 0                     OR (m.schedule_type == 2 AND (m.schedule_state != 1 AND m.schedule_state != 2)))                 AND m.ROWID in                     (SELECT message_id FROM chat_message_join where chat_id = ?)                 ORDER BY date DESC, ROWID DESC LIMIT 1"
- "SELECT m.ROWID, m.guid, m.text, m.replace, m.service_center, m.handle_id, m.subject, m.country, m.attributedBody, m.version, m.type, m.service, m.account, m.account_guid, m.error, m.date, m.date_read, m.date_delivered, m.is_delivered, m.is_finished, m.is_emote, m.is_from_me, m.is_empty, m.is_delayed, m.is_auto_reply, m.is_prepared, m.is_read, m.is_system_message, m.is_sent, m.has_dd_results, m.is_service_message, m.is_forward, m.was_downgraded, m.is_archive, m.cache_has_attachments, m.cache_roomnames, m.was_data_detected, m.was_deduplicated, m.is_audio_message, m.is_played, m.date_played, m.item_type, m.other_handle, m.group_title, m.group_action_type, m.share_status, m.share_direction, m.is_expirable, m.expire_state, m.message_action_type, m.message_source, m.associated_message_guid, m.associated_message_type, m.balloon_bundle_id, m.payload_data, m.expressive_send_style_id, m.associated_message_range_location, m.associated_message_range_length, m.time_expressive_send_played, m.message_summary_info, m.ck_sync_state, m.ck_record_id, m.ck_record_change_tag, m.destination_caller_id, m.is_corrupt, m.reply_to_guid, m.sort_id, m.is_spam, m.has_unseen_mention, m.thread_originator_guid, m.thread_originator_part, m.syndication_ranges, m.synced_syndication_ranges, m.was_delivered_quietly, m.did_notify_recipient, m.date_retracted, m.date_edited, m.date_recovered, m.was_detonated, m.part_count, m.is_stewie, m.is_sos, m.is_critical, m.bia_reference_id, m.is_kt_verified, m.fallback_hash, m.associated_message_emoji, m.is_pending_satellite_send, m.needs_relay, m.schedule_type, m.schedule_state, m.sent_or_received_off_grid FROM message m  INNER JOIN chat_message_join cm ON cm.message_id = m.rowid  INNER JOIN chat c ON c.ROWID = cm.chat_id  WHERE c.guid = ?  AND m.schedule_type == 2  AND (m.schedule_state == 1 OR m.schedule_state == 2)  ORDER BY m.date ASC LIMIT ?"
- "SELECT m.ROWID, m.guid, m.text, m.replace, m.service_center, m.handle_id, m.subject, m.country, m.attributedBody, m.version, m.type, m.service, m.account, m.account_guid, m.error, m.date, m.date_read, m.date_delivered, m.is_delivered, m.is_finished, m.is_emote, m.is_from_me, m.is_empty, m.is_delayed, m.is_auto_reply, m.is_prepared, m.is_read, m.is_system_message, m.is_sent, m.has_dd_results, m.is_service_message, m.is_forward, m.was_downgraded, m.is_archive, m.cache_has_attachments, m.cache_roomnames, m.was_data_detected, m.was_deduplicated, m.is_audio_message, m.is_played, m.date_played, m.item_type, m.other_handle, m.group_title, m.group_action_type, m.share_status, m.share_direction, m.is_expirable, m.expire_state, m.message_action_type, m.message_source, m.associated_message_guid, m.associated_message_type, m.balloon_bundle_id, m.payload_data, m.expressive_send_style_id, m.associated_message_range_location, m.associated_message_range_length, m.time_expressive_send_played, m.message_summary_info, m.ck_sync_state, m.ck_record_id, m.ck_record_change_tag, m.destination_caller_id, m.is_corrupt, m.reply_to_guid, m.sort_id, m.is_spam, m.has_unseen_mention, m.thread_originator_guid, m.thread_originator_part, m.syndication_ranges, m.synced_syndication_ranges, m.was_delivered_quietly, m.did_notify_recipient, m.date_retracted, m.date_edited, m.date_recovered, m.was_detonated, m.part_count, m.is_stewie, m.is_sos, m.is_critical, m.bia_reference_id, m.is_kt_verified, m.fallback_hash, m.associated_message_emoji, m.is_pending_satellite_send, m.needs_relay, m.schedule_type, m.schedule_state, m.sent_or_received_off_grid FROM message m  INNER JOIN chat_message_join cm ON cm.message_id = m.rowid  INNER JOIN chat c ON c.ROWID = cm.chat_id  WHERE m.schedule_type == 2  AND (m.schedule_state == 1 OR m.schedule_state == 2)  ORDER BY m.date ASC LIMIT ?"
```
