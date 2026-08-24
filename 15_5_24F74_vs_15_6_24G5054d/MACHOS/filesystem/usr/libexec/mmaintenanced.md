## mmaintenanced

> `/usr/libexec/mmaintenanced`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_capture`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_proto`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`

```diff

-158.100.15.0.0
-  __TEXT.__text: 0x15868
-  __TEXT.__auth_stubs: 0xc90
+158.140.2.0.0
+  __TEXT.__text: 0x167c4
+  __TEXT.__auth_stubs: 0xcb0
   __TEXT.__init_offsets: 0x8
-  __TEXT.__const: 0x11ea
-  __TEXT.__oslogstring: 0x1243
+  __TEXT.__const: 0x1240
+  __TEXT.__oslogstring: 0x1383
   __TEXT.__gcc_except_tab: 0x564
-  __TEXT.__cstring: 0xd48
-  __TEXT.__objc_methname: 0x1b5
+  __TEXT.__cstring: 0xd98
+  __TEXT.__objc_methname: 0x1a3
   __TEXT.__swift5_typeref: 0x70
   __TEXT.__swift5_capture: 0x78
   __TEXT.__constg_swiftt: 0x44

   __TEXT.__swift_as_ret: 0x14
   __TEXT.__swift5_reflstr: 0x24
   __TEXT.__swift5_proto: 0x8
-  __TEXT.__unwind_info: 0x6d0
+  __TEXT.__unwind_info: 0x6e8
   __TEXT.__eh_frame: 0x208
-  __DATA_CONST.__auth_got: 0x650
+  __DATA_CONST.__auth_got: 0x660
   __DATA_CONST.__got: 0x168
   __DATA_CONST.__auth_ptr: 0x70
   __DATA_CONST.__const: 0xc20
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA.__objc_selrefs: 0xb8
-  __DATA.__data: 0xd20
-  __DATA.__common: 0x28
-  __DATA.__bss: 0x130
+  __DATA.__objc_selrefs: 0xb0
+  __DATA.__data: 0xcd0
+  __DATA.__common: 0x2c
+  __DATA.__bss: 0x140
   - /AppleInternal/Library/Frameworks/TapToRadarKit.framework/Versions/A/TapToRadarKit
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsys_time.dylib
   - /usr/lib/swift/libswiftunistd.dylib
-  Functions: 413
-  Symbols:   337
-  CStrings:  215
+  Functions: 417
+  Symbols:   339
+  CStrings:  222
 
Symbols:
+ _$sSSN
+ _$ss27_stringCompareWithSmolCheck__9expectingSbs11_StringGutsV_ADs01_G16ComparisonResultOtF
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
- _$sSi10FoundationEySiSo8NSNumberChcfC
- _OBJC_CLASS_$_NSNumber
CStrings:
+ "Error: OS updated, but unable to reset OS version data, bailing"
+ "Failed to get UserDefaults database, bailing"
+ "Failed to remove default value for %s, skipping"
+ "MaintenanceTrialOSVersion"
+ "No OS update detected, continuing"
+ "OS has updated, clearing stored default for %s"
+ "OS update has occured, resetting stored OS version"
+ "com.apple.memory-maintenance.vm-trial"
- "initWithLongLong:"
```
