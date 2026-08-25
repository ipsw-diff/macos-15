## AppSSOUI

> `/System/Library/PrivateFrameworks/AppSSOUI.framework/Versions/A/AppSSOUI`

```diff

-417.140.2.0.0
-  __TEXT.__text: 0x9d74
-  __TEXT.__auth_stubs: 0x360
+417.140.3.0.0
+  __TEXT.__text: 0x9a98
+  __TEXT.__auth_stubs: 0x340
   __TEXT.__objc_methlist: 0xae4
   __TEXT.__const: 0xa8
-  __TEXT.__oslogstring: 0x9bd
+  __TEXT.__oslogstring: 0x877
   __TEXT.__cstring: 0xd13
-  __TEXT.__gcc_except_tab: 0x480
+  __TEXT.__gcc_except_tab: 0x470
   __TEXT.__dlopen_cstrs: 0x1b2
-  __TEXT.__unwind_info: 0x2f8
+  __TEXT.__unwind_info: 0x2f0
   __TEXT.__objc_classname: 0x16b
   __TEXT.__objc_methname: 0x26a8
   __TEXT.__objc_methtype: 0xd9c
   __TEXT.__objc_stubs: 0x1a00
-  __DATA_CONST.__got: 0x128
+  __DATA_CONST.__got: 0x130
   __DATA_CONST.__const: 0xd8
   __DATA_CONST.__objc_classlist: 0x40
   __DATA_CONST.__objc_protolist: 0x48

   __DATA_CONST.__objc_selrefs: 0xaf0
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x28
-  __AUTH_CONST.__auth_got: 0x1c0
+  __AUTH_CONST.__auth_got: 0x1b0
   __AUTH_CONST.__const: 0x380
   __AUTH_CONST.__cfstring: 0x280
   __AUTH_CONST.__objc_const: 0x1970

   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/PrivateFrameworks/AppSSO.framework/Versions/A/AppSSO
-  - /System/Library/PrivateFrameworks/AppSupport.framework/Versions/A/AppSupport
+  - /System/Library/PrivateFrameworks/AppSSOCore.framework/Versions/A/AppSSOCore
   - /System/Library/PrivateFrameworks/AuthKit.framework/Versions/A/AuthKit
   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 171
-  Symbols:   649
-  CStrings:  643
+  Functions: 166
+  Symbols:   648
+  CStrings:  638
 
Symbols:
+ _OBJC_CLASS_$_SOUtils
- _CPCopyBundleIdentifierAndTeamFromAuditToken
- _SecTaskCopySigningIdentifier
CStrings:
- "bundleIdentifier: %{public}@"
- "bundleIdentifier: CPCopyBundleIdentifierAndTeamFromAuditToken() failed, trying SecTaskCopySigningIdentifier()"
- "bundleIdentifier: CPCopyBundleIdentifierAndTeamFromAuditToken(): %{public}@"
- "bundleIdentifier: SecTaskCopySigningIdentifier() failed"
- "bundleIdentifier: SecTaskCreateWithAuditToken() failed"
```
