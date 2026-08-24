## LaunchServices

> `/System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/LaunchServices.framework/Versions/A/LaunchServices`

```diff

-1378.17.0.0.0
-  __TEXT.__text: 0x223f10
+1378.19.1.0.0
+  __TEXT.__text: 0x224090
   __TEXT.__auth_stubs: 0x3f00
   __TEXT.__objc_methlist: 0xd11c
   __TEXT.__const: 0x9f0
   __TEXT.__cstring: 0x284e9
-  __TEXT.__oslogstring: 0x1c8cc
-  __TEXT.__gcc_except_tab: 0x2f6c8
+  __TEXT.__oslogstring: 0x1c8e1
+  __TEXT.__gcc_except_tab: 0x2f700
   __TEXT.__ustring: 0x1be
   __TEXT.__dof_LSFSNode: 0x2b6
   __TEXT.__unwind_info: 0xc5d8

   __TEXT.__objc_methname: 0x1d891
   __TEXT.__objc_methtype: 0xa42e
   __TEXT.__objc_stubs: 0x10380
-  __DATA_CONST.__got: 0xcc0
+  __DATA_CONST.__got: 0xcc8
   __DATA_CONST.__const: 0x3960
   __DATA_CONST.__objc_classlist: 0x660
   __DATA_CONST.__objc_catlist: 0x60

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   Functions: 9777
-  Symbols:   17416
-  CStrings:  12051
+  Symbols:   17417
+  CStrings:  12052
 
Symbols:
+ _SANDBOX_EXTENSION_NO_REPORT
Functions:
~ __ZN14LaunchServices17BindingEvaluation25BindingEligibilityChecker23checkBindingIsEligibileERKNS0_5StateERKNS0_15ExtendedBindingE : 1036 -> 980
~ -[_LSRemoteOpenCall invokeWithError:] : 2052 -> 2468
~ __ZL46URLSetSandboxExtensionForRealPathAndAuditTokenP5NSURLRK13audit_token_t : 776 -> 800
CStrings:
+ "LAUNCH: Error %{public}d/%{public}d checking if audit token can perform %{public}s on item %{private}s."
+ "LAUNCH: Not adding sandbox extensions when creating bookmark because audit token does not have access to item %{private}s."
+ "LAUNCH: Only including a read-only extension when creating bookmark because audit token does not have access to item %{private}s."
+ "can't issue extension to %@: %{darwin.errno}d"
- "LAUNCH: Error %{public}d/%{public}d checking if overridden audit token can perform %s on item %{private}s."
- "LAUNCH: Not adding sandbox extensions when creating bookmark because overridden audit token does not have access to item %{private}s."
- "LAUNCH: Only including a read-only extension when creating bookmark because overridden audit token does not have access to item %{private}s."
```
