## findmylocateagent

> `/usr/libexec/findmylocateagent`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__linkguard`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-93.25.2.11.15
-  __TEXT.__text: 0x4a5f84
-  __TEXT.__auth_stubs: 0x4ba0
+93.26.4.2.4
+  __TEXT.__text: 0x4a9448
+  __TEXT.__auth_stubs: 0x4c30
   __TEXT.__objc_methlist: 0x99c
-  __TEXT.__const: 0x13880
-  __TEXT.__cstring: 0xc50b
-  __TEXT.__swift5_typeref: 0x5c7d
+  __TEXT.__const: 0x16850
+  __TEXT.__cstring: 0xc56b
+  __TEXT.__swift5_typeref: 0x5c85
   __TEXT.__constg_swiftt: 0x5d48
   __TEXT.__swift5_builtin: 0xdc
   __TEXT.__swift5_reflstr: 0x6a13

   __TEXT.__objc_methtype: 0x6fe
   __TEXT.__swift5_protos: 0x50
   __TEXT.__swift5_mpenum: 0x20
-  __TEXT.__oslogstring: 0x13621
-  __TEXT.__swift_as_entry: 0x109c
-  __TEXT.__swift_as_ret: 0x1b5c
+  __TEXT.__oslogstring: 0x13741
+  __TEXT.__swift_as_entry: 0x10ac
+  __TEXT.__swift_as_ret: 0x1b84
   __TEXT.__swift5_capture: 0x44c4
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__unwind_info: 0x11b88
-  __TEXT.__eh_frame: 0x35f18
-  __DATA_CONST.__auth_got: 0x25d0
-  __DATA_CONST.__got: 0x1880
-  __DATA_CONST.__auth_ptr: 0x1a78
+  __TEXT.__unwind_info: 0x11c40
+  __TEXT.__eh_frame: 0x36288
+  __DATA_CONST.__auth_got: 0x2618
+  __DATA_CONST.__got: 0x18a8
+  __DATA_CONST.__auth_ptr: 0x1a58
   __DATA_CONST.__const: 0x13fe8
   __DATA_CONST.__objc_classlist: 0x1b0
   __DATA_CONST.__objc_protolist: 0xe0

   __DATA.__objc_const: 0x50d8
   __DATA.__objc_selrefs: 0x9a8
   __DATA.__objc_data: 0xae0
-  __DATA.__data: 0xf028
+  __DATA.__data: 0xc168
   __DATA.__bss: 0x26380
   __DATA.__common: 0x1318
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /System/Library/PrivateFrameworks/BiomeLibrary.framework/Versions/A/BiomeLibrary
   - /System/Library/PrivateFrameworks/ChronoServices.framework/Versions/A/ChronoServices
   - /System/Library/PrivateFrameworks/CollectionsInternal.framework/Versions/A/CollectionsInternal
+  - /System/Library/PrivateFrameworks/CommunicationsFilter.framework/Versions/A/CommunicationsFilter
   - /System/Library/PrivateFrameworks/CoreAnalytics.framework/Versions/A/CoreAnalytics
+  - /System/Library/PrivateFrameworks/CorePhoneNumbers.framework/Versions/A/CorePhoneNumbers
   - /System/Library/PrivateFrameworks/CoreTime.framework/Versions/A/CoreTime
   - /System/Library/PrivateFrameworks/FMCore.framework/Versions/A/FMCore
   - /System/Library/PrivateFrameworks/FMNetworking.framework/Versions/A/FMNetworking

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 14648
-  Symbols:   2418
-  CStrings:  3048
+  Functions: 14680
+  Symbols:   2432
+  CStrings:  3057
 
Symbols:
+ _$s10Foundation12NotificationVMn
+ _$s12FindMyLocate17FriendshipRequestV9toHandles12callerHandle7endDate6origin11requestType08responseN011isFromGroupACSayAA0I0VG_ALSg10Foundation0K0VSgAA0E6OriginVAA0deN0OSgAA0d16ResponseToInviteN0OSgSbtcfC
+ _$sScI4next7ElementQzSgyYaKFTj
+ _$sScI4next7ElementQzSgyYaKFTjTu
+ _$sSo20NSNotificationCenterC10FoundationE13NotificationsC17makeAsyncIteratorAE0G0VyF
+ _$sSo20NSNotificationCenterC10FoundationE13NotificationsC8IteratorVMa
+ _$sSo20NSNotificationCenterC10FoundationE13NotificationsC8IteratorVScIACMc
+ _$sSo20NSNotificationCenterC10FoundationE13notifications5named6objectAbCE13NotificationsCSo0A4Namea_yXlSgtF
+ _CFPhoneNumberCreate
+ _CMFBlockListIsItemBlocked
+ _CMFBlockListUpdatedNotification
+ _CMFItemCreateWithEmailAddress
+ _CMFItemCreateWithPhoneNumber
+ _kCFAllocatorDefault
CStrings:
+ "%{public}s - Failed removing %ld followers with error: %@"
+ "%{public}s - List is empty. Nothing to remove."
+ "%{public}s - Notification received."
+ "%{public}s - Removing %s"
+ "%{public}s - Successfully removed %ld followers."
+ "Failed to get DataManager: %@"
+ "monitorBlockListNotifications()"
+ "removeBlockedFollowers()"
+ "removeBlockedFollowers(from:)"
```
