## passd

> `/System/Library/PrivateFrameworks/PassKitCore.framework/passd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA.__data`

```diff

-1591.6.2.2.0
-  __TEXT.__text: 0x551964
+1591.6.3.0.0
+  __TEXT.__text: 0x553320
   __TEXT.__auth_stubs: 0x4f20
-  __TEXT.__objc_stubs: 0x67f40
-  __TEXT.__objc_methlist: 0x3161c
+  __TEXT.__objc_stubs: 0x681c0
+  __TEXT.__objc_methlist: 0x316f4
   __TEXT.__const: 0x1eba
-  __TEXT.__cstring: 0x5bd1b
-  __TEXT.__objc_classname: 0x69a9
+  __TEXT.__cstring: 0x5c40b
+  __TEXT.__objc_classname: 0x69b9
   __TEXT.__objc_methtype: 0x11b91
-  __TEXT.__gcc_except_tab: 0x86c4
-  __TEXT.__objc_methname: 0x943c9
-  __TEXT.__oslogstring: 0x4855c
+  __TEXT.__gcc_except_tab: 0x86f8
+  __TEXT.__objc_methname: 0x94609
+  __TEXT.__oslogstring: 0x4873c
   __TEXT.__ustring: 0x14
   __TEXT.__swift5_typeref: 0x1336
   __TEXT.__constg_swiftt: 0xc4c

   __TEXT.__swift5_mpenum: 0x28
   __TEXT.__swift_as_entry: 0x10
   __TEXT.__swift_as_ret: 0x20
-  __TEXT.__unwind_info: 0x10d78
+  __TEXT.__unwind_info: 0x10db0
   __TEXT.__eh_frame: 0xeb0
   __DATA_CONST.__auth_got: 0x27a0
-  __DATA_CONST.__got: 0x2ee8
-  __DATA_CONST.__auth_ptr: 0x420
-  __DATA_CONST.__const: 0x2a588
-  __DATA_CONST.__cfstring: 0x2e3e0
-  __DATA_CONST.__objc_classlist: 0x1730
+  __DATA_CONST.__got: 0x2ef0
+  __DATA_CONST.__auth_ptr: 0x3e8
+  __DATA_CONST.__const: 0x2a608
+  __DATA_CONST.__cfstring: 0x2e780
+  __DATA_CONST.__objc_classlist: 0x1738
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x538
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0xe40
-  __DATA_CONST.__objc_intobj: 0x10b0
+  __DATA_CONST.__objc_intobj: 0x10e0
   __DATA_CONST.__objc_arraydata: 0x490
   __DATA_CONST.__objc_arrayobj: 0x450
   __DATA_CONST.__objc_dictobj: 0x280
   __DATA_CONST.__objc_doubleobj: 0x10
-  __DATA.__objc_const: 0x3b420
-  __DATA.__objc_selrefs: 0x1cf50
+  __DATA.__objc_const: 0x3b4b0
+  __DATA.__objc_selrefs: 0x1cff0
   __DATA.__objc_ivar: 0x24e8
-  __DATA.__objc_data: 0xf1c0
+  __DATA.__objc_data: 0xf210
   __DATA.__data: 0x4a60
   __DATA.__bss: 0x2140
   __DATA.__common: 0x10

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 24408
-  Symbols:   2910
-  CStrings:  31191
+  Functions: 24434
+  Symbols:   2911
+  CStrings:  31249
 
Symbols:
+ _OBJC_CLASS_$_PKAccountLocation
CStrings:
+ "AccountLocation"
+ "CREATE TABLE IF NOT EXISTS account_location (pid INTEGER, account_feature_descriptor_pid INTEGER, app INTEGER, page INTEGER, PRIMARY KEY (pid));"
+ "CREATE TABLE IF NOT EXISTS elephant (pid INTEGER, a INTEGER, proactive_fetch_period INTEGER, has_fetched_after_udpate BOOL, PRIMARY KEY (pid));"
+ "CREATE TABLE IF NOT EXISTS footer_content_link (pid INTEGER, table_pid INTEGER, link_text TEXT, link_url TEXT, terms_identifier TEXT, analytics_identifier TEXT, behavior INTEGER, type INTEGER, link_range_location INTEGER, link_range_length INTEGER, PRIMARY KEY (pid));"
+ "CREATE TABLE IF NOT EXISTS pass_legal_agreement (pid INTEGER, pass_pid INTEGER, identifier TEXT, type TEXT, agreement_updated BOOL, remove_pass_on_decline BOOL, PRIMARY KEY (pid));"
+ "CREATE TABLE IF NOT EXISTS pass_tile_state (pid INTEGER, action_state_pid INTEGER, state_metadata_pid INTEGER, image_pid INTEGER, type TEXT, enabled INTEGER, selected INTEGER, actions BLOB, PRIMARY KEY (pid));"
+ "CREATE TABLE IF NOT EXISTS payment_offer_confirmation_record (pid INTEGER, payment_hash TEXT, pass_unique_identifier TEXT, type INTEGER, context INTEGER, criteria_identifier TEXT, processed_events INTEGER, backoff_level INTEGER, next_attempt INTEGER, last_attempt INTEGER, fully_processed_date INTEGER, PRIMARY KEY (pid));"
+ "CREATE TABLE IF NOT EXISTS selected_payment_offer (pid INTEGER, type INTEGER, pass_pid INTEGER, confirmation_record_pid INTEGER, selected_offer_pid INTEGER, PRIMARY KEY (pid));"
+ "CREATE TABLE IF NOT EXISTS selected_payment_offer_installment (pid INTEGER, type INTEGER, pass_pid INTEGER, pass_unique_id TEXT, dpan_identifier TEXT, pass_type_identifier TEXT, pass_serial_number TEXT, primary_account_identifier TEXT, selected_offer_identifier TEXT, criteria_identifier TEXT, session_identifier TEXT, selection_type INTEGER, is_preconfigured_offer BOOL, user_entered_amount_amount INTEGER, user_entered_amount_currency TEXT, PRIMARY KEY (pid));"
+ "CREATE TABLE IF NOT EXISTS text_format_item (pid INTEGER, table_pid INTEGER, type INTEGER, format_text TEXT, format_range_location INTEGER, format_range_length INTEGER, strikethrough BOOL, PRIMARY KEY (pid));"
+ "Migrating database from user_version 18030 to 18031"
+ "Migrating database from user_version 18031 to 18032"
+ "Migrating database from user_version 18032 to 18033"
+ "Migrating database from user_version 18033 to 18034"
+ "Migrating database from user_version 18034 to 18035"
+ "Migrating database from user_version 18035 to 18036"
+ "Migrating database from user_version 18036 to 18037"
+ "Migrating database from user_version 18037 to 18038"
+ "Migrating database from user_version 18038 to 18039"
+ "SELECT pid, action, actions FROM pass_tile_state"
+ "SELECT pid, footer_content_pid FROM footer_content_link"
+ "UPDATE footer_content_link SET table_pid = %ld WHERE pid = %ld"
+ "UPDATE pass_tile_state SET actions = ? WHERE pid = ?"
+ "_commonDictionaryForLocation:"
+ "_location"
+ "_migrateFrom18030To18031:context:"
+ "_migrateFrom18031To18032:context:"
+ "_migrateFrom18032To18033:context:"
+ "_migrateFrom18033To18034:context:"
+ "_migrateFrom18034To18035:context:"
+ "_migrateFrom18035To18036:context:"
+ "_migrateFrom18036To18037:context:"
+ "_migrateFrom18037To18038:context:"
+ "_migrateFrom18038To18039:context:"
+ "_predicateForAccountFeatureDescriptorPID:"
+ "accountLocations"
+ "account_feature_descriptor_pid"
+ "account_location"
+ "app"
+ "backoff_level INTEGER"
+ "confirmation_record_pid"
+ "contactless_transaction_record_pid"
+ "criteria_identifier TEXT"
+ "deleteLocationsWithAccountFeatureDescriptorPID:inDatabase:"
+ "fully_processed_date INTEGER"
+ "has_fetched_after_udpate BOOL"
+ "insertOrUpdateFooterContentLinks:withFooterContentPID:inDatabase:"
+ "last_attempt INTEGER"
+ "last_build_version"
+ "last_build_version TEXT"
+ "locationsWithAccountFeatureDescriptorPID:inDatabase:"
+ "next_attempt INTEGER"
+ "page"
+ "payment_offer_confirmation_record"
+ "processed_events INTEGER"
+ "selected_payment_offer"
+ "setAccountLocations:"
+ "setApp:"
+ "setPage:"
+ "text_format_item"
+ "updateLocations:forAccountFeatureDescriptorPID:inDatabase:"
+ "user_entered_amount_amount INTEGER"
+ "user_entered_amount_currency TEXT"
+ "v24@?0@\"PKAccountLocation\"8@16"
- "CREATE TABLE IF NOT EXISTS footer_content_link (pid INTEGER, footer_content_pid INTEGER, dynamic_content_page_pid INTEGER, link_text TEXT, link_url TEXT, terms_identifier TEXT, analytics_identifier TEXT, behavior INTEGER, type INTEGER, link_range_location INTEGER, link_range_length INTEGER, PRIMARY KEY (pid));"
- "CREATE TABLE IF NOT EXISTS pass_tile_state (pid INTEGER, action_state_pid INTEGER, state_metadata_pid INTEGER, image_pid INTEGER, type TEXT, enabled INTEGER, selected INTEGER, action BLOB, actions BLOB, PRIMARY KEY (pid));"
- "CREATE TABLE IF NOT EXISTS payment_offer_contactless_transaction_record (pid INTEGER, payment_hash TEXT, pass_unique_identifier TEXT, PRIMARY KEY (pid));"
- "CREATE TABLE IF NOT EXISTS selected_payment_offer_installment (pid INTEGER, type INTEGER, pass_pid INTEGER, pass_unique_id TEXT, dpan_identifier TEXT, pass_type_identifier TEXT, pass_serial_number TEXT, primary_account_identifier TEXT, selected_offer_identifier TEXT, criteria_identifier TEXT, session_identifier TEXT, selection_type INTEGER, is_preconfigured_offer BOOL, PRIMARY KEY (pid));"
- "initWithFooterContentLink:footerContentPID:inDatabase:"
- "insertFooterContentLinks:withFooterContentPID:inDatabase:"
```
