## AppSSOCore

> `/System/Library/PrivateFrameworks/AppSSOCore.framework/Versions/A/AppSSOCore`

```diff

-417.140.2.0.0
-  __TEXT.__text: 0x148f4
-  __TEXT.__auth_stubs: 0x5f0
+417.140.3.0.0
+  __TEXT.__text: 0x14a04
+  __TEXT.__auth_stubs: 0x600
   __TEXT.__objc_methlist: 0x121c
   __TEXT.__const: 0x118
-  __TEXT.__cstring: 0x1885
-  __TEXT.__oslogstring: 0x1bf2
+  __TEXT.__cstring: 0x188b
+  __TEXT.__oslogstring: 0x1c06
   __TEXT.__gcc_except_tab: 0x388
   __TEXT.__unwind_info: 0x578
   __TEXT.__objc_classname: 0x223
   __TEXT.__objc_methname: 0x2787
   __TEXT.__objc_methtype: 0x7d5
   __TEXT.__objc_stubs: 0x1bc0
-  __DATA_CONST.__got: 0x1b0
-  __DATA_CONST.__const: 0xc0
+  __DATA_CONST.__got: 0x1a8
+  __DATA_CONST.__const: 0xc8
   __DATA_CONST.__objc_classlist: 0x98
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x78
   __DATA_CONST.__objc_arraydata: 0x108
-  __AUTH_CONST.__auth_got: 0x308
+  __AUTH_CONST.__auth_got: 0x310
   __AUTH_CONST.__const: 0x6d0
-  __AUTH_CONST.__cfstring: 0xfc0
+  __AUTH_CONST.__cfstring: 0xfe0
   __AUTH_CONST.__objc_const: 0x2bf8
   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__objc_arrayobj: 0x30

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 537
-  Symbols:   1164
-  CStrings:  875
+  Functions: 538
+  Symbols:   1165
+  CStrings:  878
 
Symbols:
+ _SecTaskGetCodeSignStatus
+ _kApplePlatformBinaryTeamIdentifier
- _kCFAllocatorDefault
Functions:
~ +[SOUtils bundleIdentifierFromAuditToken:] : 1368 -> 1464
~ +[SOUtils teamIdentifierFromAuditToken:] : 540 -> 664
~ _OUTLINED_FUNCTION_2 : 36 -> 28
~ _OUTLINED_FUNCTION_3 : 28 -> 12
~ _OUTLINED_FUNCTION_4 : 28 -> 36
~ _OUTLINED_FUNCTION_5 : 12 -> 28
+ +[SOUtils bundleIdentifierFromAuditToken:].cold.7
~ +[SOUtils teamIdentifierFromAuditToken:].cold.1 : 64 -> 52
~ +[SOUtils teamIdentifierFromAuditToken:].cold.2 : 52 -> 64
CStrings:
+ "Apple"
+ "bundleIdentifier: CPCopyBundleIdentifierAndTeamFromAuditToken() failed"
+ "bundleIdentifier: The entitlements are not valid."
+ "bundleIdentifier: using SecTaskCopySigningIdentifier()"
+ "teamIdentifier: CPCopyBundleIdentifierAndTeamFromAuditToken() failed"
+ "teamIdentifier: The entitlements are not valid."
+ "teamIdentifier: using SecTaskCopyTeamIdentifier()"
- "bundleIdentifier: CPCopyBundleIdentifierAndTeamFromAuditToken() failed, trying SecTaskCopySigningIdentifier()"
- "bundleIdentifier: SecTaskCreateWithAuditToken() failed"
- "teamIdentifier: CPCopyBundleIdentifierAndTeamFromAuditToken() failed, trying SecTaskCopyTeamIdentifier()"
- "teamIdentifier: SecTaskCreateWithAuditToken() failed"
```
