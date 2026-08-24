## systemsettingsagent

> `/System/Applications/System Settings.app/Contents/Resources/systemsettingsagent`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_intobj`

```diff

-644.4.1.0.0
-  __TEXT.__text: 0x1dfe4
-  __TEXT.__auth_stubs: 0xf80
+644.4.2.0.0
+  __TEXT.__text: 0x2b158
+  __TEXT.__auth_stubs: 0xfe0
   __TEXT.__objc_stubs: 0x120
   __TEXT.__objc_methlist: 0x1ac
-  __TEXT.__cstring: 0x1598
-  __TEXT.__const: 0x3e4
-  __TEXT.__oslogstring: 0x45
-  __TEXT.__swift5_typeref: 0x2d4
-  __TEXT.__objc_methname: 0x765
-  __TEXT.__swift5_capture: 0xf4
+  __TEXT.__cstring: 0x1868
+  __TEXT.__const: 0x484
+  __TEXT.__swift5_typeref: 0x2ec
+  __TEXT.__objc_methname: 0x784
+  __TEXT.__swift5_capture: 0xe8
+  __TEXT.__oslogstring: 0x25e
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__constg_swiftt: 0x484
-  __TEXT.__swift5_reflstr: 0x28d
-  __TEXT.__swift5_fieldmd: 0x26c
+  __TEXT.__constg_swiftt: 0x52c
+  __TEXT.__swift5_reflstr: 0x33d
+  __TEXT.__swift5_fieldmd: 0x2e8
   __TEXT.__swift5_proto: 0x10
-  __TEXT.__swift5_types: 0x30
+  __TEXT.__swift5_types: 0x34
   __TEXT.__swift_as_entry: 0x14
   __TEXT.__swift_as_ret: 0x14
   __TEXT.__objc_classname: 0x23
   __TEXT.__objc_methtype: 0x247
-  __TEXT.__unwind_info: 0x3b8
-  __TEXT.__eh_frame: 0x490
-  __DATA_CONST.__auth_got: 0x7c8
-  __DATA_CONST.__got: 0x280
-  __DATA_CONST.__auth_ptr: 0x158
-  __DATA_CONST.__const: 0x780
+  __TEXT.__unwind_info: 0x3c0
+  __TEXT.__eh_frame: 0x468
+  __DATA_CONST.__auth_got: 0x7f8
+  __DATA_CONST.__got: 0x2b0
+  __DATA_CONST.__auth_ptr: 0x170
+  __DATA_CONST.__const: 0x758
   __DATA_CONST.__cfstring: 0x140
-  __DATA_CONST.__objc_classlist: 0x40
+  __DATA_CONST.__objc_classlist: 0x48
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_intobj: 0x18
-  __DATA.__objc_const: 0x8a8
-  __DATA.__objc_selrefs: 0x260
-  __DATA.__objc_data: 0x168
-  __DATA.__data: 0x9f8
+  __DATA.__objc_const: 0xa18
+  __DATA.__objc_selrefs: 0x270
+  __DATA.__objc_data: 0x1b8
+  __DATA.__data: 0xb88
   __DATA.__common: 0x68
   __DATA.__bss: 0x200
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftsimd.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 294
-  Symbols:   392
-  CStrings:  261
+  Functions: 302
+  Symbols:   406
+  CStrings:  296
 
Symbols:
+ _$s10Foundation4DateVACycfC
+ _$s2os6LoggerVACycfC
+ _$s2os6LoggerVMn
+ _$s6Darwin5noErrs5Int32Vvg
+ _$sBi32_WV
+ _$sBi64_WV
+ _$ss5ErrorP10FoundationE20localizedDescriptionSSvg
+ _$ss6UInt64VMn
+ _CFPreferencesCopyValue
+ _CFPreferencesSetValue
+ _CFPreferencesSynchronize
+ _OBJC_CLASS_$_NSDateFormatter
+ __CFCopySystemVersionDictionaryValue
+ __kCFSystemVersionBuildVersionKey
+ _kCFPreferencesCurrentHost
+ _kCFPreferencesCurrentUser
+ _notify_cancel
+ _swift_getErrorValue
- _CFPreferencesAppSynchronize
- _CFPreferencesCopyAppValue
- _CFPreferencesGetAppIntegerValue
- _CFPreferencesSetAppValue
CStrings:
+ "%{public}s"
+ "Added new index items."
+ "Checking user ID: "
+ "Deleted old index items. "
+ "Error adding new index items: "
+ "Error deleting old index items for "
+ "Error deleting old index items: "
+ "INDEXING"
+ "Indexing coordinator cancelled"
+ "Is role account: "
+ "NOT_INDEXING"
+ "No change. Skipped."
+ "Processing (start)..."
+ "Representation indicates that settings are not available."
+ "Running as role account, so do nothing."
+ "_TtC19systemsettingsagent19IndexingCoordinator"
+ "cancel called but not registered"
+ "currentStateKey"
+ "logger"
+ "notifyName"
+ "notify_cancel returned error code %u"
+ "prefsLastIndexedDict is empty"
+ "prefsLastIndexedDict is missing or cannot be converted to Dictionary"
+ "prefsOSVersionString does not match currentOSVersionString"
+ "prefsOSVersionString is missing or cannot be converting to String"
+ "prefsVersion does not match currentVersion"
+ "prefsVersion is missing or cannot be converted to Int"
+ "registered"
+ "setDateFormat:"
+ "shouldReindex returning %{bool}d"
+ "state-indexing completed time"
+ "state-indexing start time"
+ "state-indexing status"
+ "stateIndexingCompleteTimeKey"
+ "stateIndexingDoneKey"
+ "stateIndexingStartTimeKey"
+ "stateIndexingStatusKey"
+ "stringFromDate:"
+ "token"
+ "uidIsRoleAccount(_:)"
+ "yyyy-MM-dd HH:mm:ssXXXXX"
- "%s:%ld %s %{public}s"
- "LastIndexed is empty…"
- "Version is missing…"
- "Version mismatch…"
- "indexingDoneKey"
- "stateDictKey"
```
