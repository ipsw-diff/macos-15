## LocalAuthenticationUI

> `/System/Library/PrivateFrameworks/LocalAuthenticationUI.framework/Versions/A/LocalAuthenticationUI`

```diff

-1656.140.3.0.0
-  __TEXT.__text: 0x25e58
+1656.140.4.0.0
+  __TEXT.__text: 0x25e28
   __TEXT.__auth_stubs: 0x6a0
   __TEXT.__objc_methlist: 0x2c70
   __TEXT.__const: 0x9a8

   __TEXT.__oslogstring: 0x133a
   __TEXT.__dlopen_cstrs: 0x73
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0xbe0
-  __TEXT.__objc_classname: 0x5c3
-  __TEXT.__objc_methname: 0x6876
-  __TEXT.__objc_methtype: 0x161a
-  __TEXT.__objc_stubs: 0x5ec0
+  __TEXT.__unwind_info: 0xbd8
+  __TEXT.__objc_classname: 0x5c4
+  __TEXT.__objc_methname: 0x68c8
+  __TEXT.__objc_methtype: 0x1637
+  __TEXT.__objc_stubs: 0x5f00
   __DATA_CONST.__got: 0x448
   __DATA_CONST.__const: 0xd8
   __DATA_CONST.__objc_classlist: 0xd0
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0xb0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1da8
+  __DATA_CONST.__objc_selrefs: 0x1db8
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0xa8
   __DATA_CONST.__objc_arraydata: 0x50
   __AUTH_CONST.__auth_got: 0x368
   __AUTH_CONST.__const: 0xce0
   __AUTH_CONST.__cfstring: 0xee0
-  __AUTH_CONST.__objc_const: 0x6528
-  __AUTH_CONST.__objc_intobj: 0x438
+  __AUTH_CONST.__objc_const: 0x6558
+  __AUTH_CONST.__objc_intobj: 0x420
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH.__objc_data: 0x550
-  __DATA.__objc_ivar: 0x370
+  __DATA.__objc_ivar: 0x374
   __DATA.__data: 0x840
   __DATA.__bss: 0x110
   __DATA_DIRTY.__objc_data: 0x2d0

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 952
-  Symbols:   2583
-  CStrings:  1852
+  Symbols:   2586
+  CStrings:  1857
 
Symbols:
+ -[LAUIAuthenticationSheetController analytics]
+ GCC_except_table217
+ OBJC_IVAR_$_LAUIAuthenticationSheetController._analytics
+ _LACEventPasscode
+ _OBJC_CLASS_$_LACAnalyticsSessionClient
+ _objc_msgSend$analytics
+ _objc_msgSend$authenticationAction:failing:
+ _objc_msgSend$authenticationAttemptFailedForEvent:
+ _objc_msgSend$authenticationStartedForEvent:
+ _objc_msgSend$authenticationSuccessfulForEvent:
+ _objc_msgSend$finishSession
+ _objc_msgSend$initWithContext:
+ _objc_msgSend$startSessionForDialogID:bundleID:
- -[LAUIAuthenticationViewController _analyticsSessionStarting:]
- GCC_except_table216
- _LACBiomeDialogIDViewController
- _LACErrorCodeAuthenticationFailed
- _objc_msgSend$_analyticsSessionStarting:
- _objc_msgSend$analyticsAction:dismissing:
- _objc_msgSend$analyticsMechanism:result:
- _objc_msgSend$analyticsMechanism:starting:
- _objc_msgSend$analyticsSessionStarting:dialogID:bundleID:
- _objc_msgSend$errorWithCode:
CStrings:
+ "@\"LACAnalyticsSessionClient\""
+ "T@\"LACAnalyticsSessionClient\",R,N"
+ "_analytics"
+ "analytics"
+ "authenticationAction:failing:"
+ "authenticationAttemptFailedForEvent:"
+ "authenticationStartedForEvent:"
+ "authenticationSuccessfulForEvent:"
+ "finishSession"
+ "initWithContext:"
+ "startSessionForDialogID:bundleID:"
- "_analyticsSessionStarting:"
- "analyticsAction:dismissing:"
- "analyticsMechanism:result:"
- "analyticsMechanism:starting:"
- "analyticsSessionStarting:dialogID:bundleID:"
- "errorWithCode:"
```
