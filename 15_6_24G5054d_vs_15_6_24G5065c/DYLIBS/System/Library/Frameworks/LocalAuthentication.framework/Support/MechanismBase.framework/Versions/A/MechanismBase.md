## MechanismBase

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/MechanismBase.framework/Versions/A/MechanismBase`

```diff

-1656.140.3.0.0
-  __TEXT.__text: 0x13a98
+1656.140.4.0.0
+  __TEXT.__text: 0x13bcc
   __TEXT.__auth_stubs: 0x390
   __TEXT.__objc_methlist: 0x142c
   __TEXT.__const: 0x118

   __TEXT.__dlopen_cstrs: 0x48
   __TEXT.__unwind_info: 0x5c0
   __TEXT.__objc_classname: 0x282
-  __TEXT.__objc_methname: 0x334b
+  __TEXT.__objc_methname: 0x33b0
   __TEXT.__objc_methtype: 0xa72
-  __TEXT.__objc_stubs: 0x23c0
-  __DATA_CONST.__got: 0x1f8
+  __TEXT.__objc_stubs: 0x2420
+  __DATA_CONST.__got: 0x200
   __DATA_CONST.__const: 0xb8
   __DATA_CONST.__objc_classlist: 0xa0
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc88
+  __DATA_CONST.__objc_selrefs: 0xca0
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x90
   __DATA_CONST.__objc_arraydata: 0x40

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 485
-  Symbols:   1265
-  CStrings:  961
+  Symbols:   1269
+  CStrings:  964
 
Symbols:
+ _LACEventPasscode
+ _objc_msgSend$authenticationAction:failing:
+ _objc_msgSend$authenticationAttemptFailedForEvent:
+ _objc_msgSend$authenticationSuccessfulForEvent:
Functions:
~ -[MechanismUI finishRunWithResult:error:] : 1504 -> 1492
~ -[MechanismUI uiEvent:options:] : 1080 -> 1412
~ -[MechanismBase finishRunWithResult:error:skipReply:] : 1044 -> 1032
CStrings:
+ "authenticationAction:failing:"
+ "authenticationAttemptFailedForEvent:"
+ "authenticationSuccessfulForEvent:"
```
