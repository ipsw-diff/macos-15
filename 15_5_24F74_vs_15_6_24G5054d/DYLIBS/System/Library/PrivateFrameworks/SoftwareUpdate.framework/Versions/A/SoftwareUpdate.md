## SoftwareUpdate

> `/System/Library/PrivateFrameworks/SoftwareUpdate.framework/Versions/A/SoftwareUpdate`

```diff

-2078.120.19.0.3
-  __TEXT.__text: 0x83e4c
+2078.140.22.0.0
+  __TEXT.__text: 0x83ed4
   __TEXT.__auth_stubs: 0x1070
   __TEXT.__objc_methlist: 0x65c8
   __TEXT.__const: 0x670
   __TEXT.__gcc_except_tab: 0x1378
-  __TEXT.__cstring: 0x8679
-  __TEXT.__oslogstring: 0xb7f7
+  __TEXT.__cstring: 0x86f4
+  __TEXT.__oslogstring: 0xb813
   __TEXT.__dof_SoftwareU: 0xc9e
-  __TEXT.__unwind_info: 0x2228
+  __TEXT.__unwind_info: 0x2230
   __TEXT.__eh_frame: 0x48
   __TEXT.__objc_classname: 0x886
   __TEXT.__objc_methname: 0x11ac1

   __DATA_CONST.__objc_arraydata: 0x70
   __AUTH_CONST.__auth_got: 0x848
   __AUTH_CONST.__const: 0x2a60
-  __AUTH_CONST.__cfstring: 0x7620
+  __AUTH_CONST.__cfstring: 0x7640
   __AUTH_CONST.__objc_const: 0x8bd0
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_intobj: 0xc0

   - /usr/lib/libpartition2_dynamic.dylib
   Functions: 3222
   Symbols:   6429
-  CStrings:  5011
+  CStrings:  5014
 
Functions:
~ -[SUPreferenceManager automaticallyInstallConfigDataAndSecurityUpdates] : 180 -> 196
~ -[SUBackgroundManager synchronousRefreshAvailableUpdatesIfRequired] : 788 -> 908
CStrings:
+ "%s: Posting %@ notification"
+ "-[SUBackgroundManager synchronousRefreshAvailableUpdatesIfRequired]"
+ "com.apple.softwareupdate.legacyBackgroundScanInitiated"
```
