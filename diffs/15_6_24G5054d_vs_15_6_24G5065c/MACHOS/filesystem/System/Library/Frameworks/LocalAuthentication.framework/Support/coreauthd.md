## coreauthd

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/coreauthd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__oslogstring`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`

```diff

-1656.140.3.0.0
-  __TEXT.__text: 0x4029c
+1656.140.4.0.0
+  __TEXT.__text: 0x400d4
   __TEXT.__auth_stubs: 0xb90
-  __TEXT.__objc_stubs: 0x4420
-  __TEXT.__objc_methlist: 0x224c
+  __TEXT.__objc_stubs: 0x4380
+  __TEXT.__objc_methlist: 0x22a4
   __TEXT.__const: 0x1048
-  __TEXT.__objc_methname: 0x55ac
+  __TEXT.__objc_methname: 0x56b6
   __TEXT.__oslogstring: 0x26ef
-  __TEXT.__cstring: 0x41c4
-  __TEXT.__objc_classname: 0x901
-  __TEXT.__objc_methtype: 0x250f
+  __TEXT.__cstring: 0x419f
+  __TEXT.__objc_classname: 0x954
+  __TEXT.__objc_methtype: 0x25ee
   __TEXT.__gcc_except_tab: 0x578
   __TEXT.__dlopen_cstrs: 0x269
-  __TEXT.__unwind_info: 0xe28
+  __TEXT.__unwind_info: 0xe30
   __DATA_CONST.__auth_got: 0x5d8
-  __DATA_CONST.__got: 0x468
+  __DATA_CONST.__got: 0x460
   __DATA_CONST.__auth_ptr: 0x20
   __DATA_CONST.__const: 0x2ab8
-  __DATA_CONST.__cfstring: 0x1aa0
-  __DATA_CONST.__objc_classlist: 0x168
-  __DATA_CONST.__objc_protolist: 0x1d0
+  __DATA_CONST.__cfstring: 0x1a80
+  __DATA_CONST.__objc_classlist: 0x170
+  __DATA_CONST.__objc_protolist: 0x1e8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_protorefs: 0x68
-  __DATA_CONST.__objc_superrefs: 0xd8
+  __DATA_CONST.__objc_protorefs: 0x80
+  __DATA_CONST.__objc_superrefs: 0xe0
   __DATA_CONST.__objc_intobj: 0x390
   __DATA_CONST.__objc_arraydata: 0x28
   __DATA_CONST.__objc_arrayobj: 0x30
   __DATA_CONST.__objc_dictobj: 0x28
-  __DATA.__objc_const: 0x8c78
-  __DATA.__objc_selrefs: 0x1510
-  __DATA.__objc_ivar: 0x240
-  __DATA.__objc_data: 0xe10
-  __DATA.__data: 0x1c40
+  __DATA.__objc_const: 0x9158
+  __DATA.__objc_selrefs: 0x1528
+  __DATA.__objc_ivar: 0x244
+  __DATA.__objc_data: 0xe60
+  __DATA.__data: 0x1d60
   __DATA.__bss: 0x268
   __DATA.__common: 0x20
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1443
-  Symbols:   342
-  CStrings:  2133
+  Functions: 1441
+  Symbols:   341
+  CStrings:  2146
 
Symbols:
+ _OBJC_CLASS_$_LACAnalyticsServiceXPCHost
+ _OBJC_CLASS_$_LACConcurrencyUtilities
- _LACErrorCodeRequestFailed
- _OBJC_CLASS_$_LACAnalyticsData
- _OBJC_CLASS_$_LACAnalyticsSession
CStrings:
+ "%{public}@ created for %{public}@ uid:%u"
+ "@\"<LACAnalyticsService>\""
+ "@\"<LACAnalyticsServiceXPC>\"16@0:8"
+ "@\"LACAnalyticsServiceXPCHost\""
+ "@\"LACAnalyticsSession\"24@0:8@\"NSUUID\"16"
+ "AnalyticsService"
+ "LACAnalyticsService"
+ "LACAnalyticsServiceXPC"
+ "LACAnalyticsSessionXPC"
+ "T@\"<LACAnalyticsService>\",R,N,V_analytics"
+ "T@\"<LACAnalyticsServiceXPC>\",R,N"
+ "T@\"<LACAnalyticsServiceXPC>\",R,N,V_xpcController"
+ "_analytics"
+ "_analyticsSessionForEvaluationRequest:"
+ "authenticationAction:failing:reply:"
+ "authenticationAttemptFailedForEvent:reply:"
+ "authenticationStartedForEvent:reply:"
+ "authenticationSuccessfulForEvent:reply:"
+ "connectSessionForContext:reply:"
+ "daemonQueue"
+ "finishWithReply:"
+ "initWithAnalyticsSession:"
+ "kLAServiceTypeAnalytics"
+ "serviceLocator"
+ "sessionForContextUUID:"
+ "setInterface:forSelector:argumentIndex:ofReply:"
+ "startSessionForContext:dialogID:bundleID:reply:"
+ "trackEvaluationAnalytics:"
+ "updateContextUUID:reply:"
+ "v32@0:8@\"NSUUID\"16@?<v@?@\"<LACAnalyticsSessionXPC>\"@\"NSError\">24"
+ "v32@0:8@\"NSUUID\"16@?<v@?B@\"NSError\">24"
+ "v48@0:8@\"NSUUID\"16@\"NSString\"24@\"NSString\"32@?<v@?@\"<LACAnalyticsSessionXPC>\"@\"NSError\">40"
- "%{public}@ created for %{public}@ uid:%d"
- "@\"LACAnalyticsSession\""
- "No active analytics session."
- "No analytics session to finish."
- "_analyticsSession"
- "analyticsAction:dismissing:reply:"
- "analyticsMechanism:result:reply:"
- "analyticsMechanism:starting:reply:"
- "analyticsSessionStarting:dialogID:bundleID:reply:"
- "authenticationAction:dismissing:"
- "authenticationResult:event:"
- "authenticationStartedForEvent:"
- "finish"
- "initWithDialogID:bundleID:"
- "setAnalyticsData:"
- "setDirty:"
- "setSession:"
- "v44@0:8B16@\"NSString\"20@\"NSString\"28@?<v@?B@\"NSError\">36"
- "v44@0:8B16@20@28@?36"
```
