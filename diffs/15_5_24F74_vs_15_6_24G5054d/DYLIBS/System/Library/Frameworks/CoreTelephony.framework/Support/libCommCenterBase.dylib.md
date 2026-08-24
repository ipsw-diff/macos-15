## libCommCenterBase.dylib

> `/System/Library/Frameworks/CoreTelephony.framework/Support/libCommCenterBase.dylib`

```diff

-12409.0.0.0.0
-  __TEXT.__text: 0xb9ccc
-  __TEXT.__auth_stubs: 0x1680
+12412.0.0.0.0
+  __TEXT.__text: 0xba380
+  __TEXT.__auth_stubs: 0x1690
   __TEXT.__init_offsets: 0x30
   __TEXT.__objc_methlist: 0xf8
   __TEXT.__const: 0xddde
-  __TEXT.__cstring: 0x121b0
-  __TEXT.__gcc_except_tab: 0x11100
-  __TEXT.__oslogstring: 0x1efb
-  __TEXT.__unwind_info: 0x4838
+  __TEXT.__cstring: 0x1234f
+  __TEXT.__gcc_except_tab: 0x11130
+  __TEXT.__oslogstring: 0x2017
+  __TEXT.__unwind_info: 0x4850
   __TEXT.__objc_classname: 0x2b
   __TEXT.__objc_methname: 0x3bc
   __TEXT.__objc_methtype: 0x344

   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x140
   __DATA_CONST.__objc_superrefs: 0x8
-  __AUTH_CONST.__auth_got: 0xb50
-  __AUTH_CONST.__const: 0x135b0
+  __AUTH_CONST.__auth_got: 0xb58
+  __AUTH_CONST.__const: 0x135f8
   __AUTH_CONST.__cfstring: 0x2b60
   __AUTH_CONST.__objc_const: 0x200
   __DATA.__objc_ivar: 0x8

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 5388
-  Symbols:   9019
-  CStrings:  4192
+  Symbols:   9020
+  CStrings:  4204
 
Symbols:
+ __ZNK3xpc6object9to_stringEv
+ __os_log_debug_impl
- ___TUAssertTrigger
Functions:
~ __Z17getGsm7TableIndexN3sms12TextEncodingE : 64 -> 88
~ __ZN16HelperRestServer17handleRestMessageERKNSt3__110shared_ptrIN3ctu22RestResourceConnectionEEEN3xpc4dictE : 540 -> 688
~ __ZN16HelperRestServer26handleRestMessageWithReplyERKNSt3__110shared_ptrIN3ctu22RestResourceConnectionEEEN3xpc4dictENS0_8functionIFvNS7_6objectEEEE : 616 -> 772
~ __ZN16HelperRestServer23handleDroppedConnectionERKNSt3__110shared_ptrIN3ctu22RestResourceConnectionEEEN3xpc6objectE : 360 -> 440
~ __ZN19SignalStrengthModel11handleInputENSt3__110shared_ptrIK6InputsEE : 248 -> 480
~ __ZNK13DisplayStatus9dumpStateEPKN3ctu11OsLogLoggerE : 4 -> 252
~ __ZN10subscriber12isSimPresentENS_8SimStateE : 64 -> 88
~ __ZN10subscriber21isSimInTransientStateENS_8SimStateE : 60 -> 84
~ __ZN10subscriber11isSimAbsentENS_8SimStateE : 64 -> 88
~ __ZN10subscriber13isSimInsertedENS_8SimStateE : 64 -> 88
~ __ZN10subscriber15isSimUnreadableENS_8SimStateE : 64 -> 88
~ __ZN10subscriber10isSimReadyENS_8SimStateE : 64 -> 88
~ __ZN10subscriber12isSimSettledENS_8SimStateE : 64 -> 88
~ __ZN10subscriber11isSimLockedENS_8SimStateE : 64 -> 88
~ __ZN10subscriber18isSimReadyOrLockedENS_8SimStateE : 64 -> 88
~ __ZN10subscriber9isSimDeadENS_8SimStateE : 64 -> 88
~ __ZN10subscriber23isSimPermanentlyBlockedENS_8SimStateE : 64 -> 88
~ __ZN10subscriber20isSimPresentAndValidENS_8SimStateE : 64 -> 88
~ __ZNK12BasicSimInfo22isEmptyEsimCapableCardEv : 92 -> 116
~ __ZN12OTASPService20sendOTASPSuccessToUIEv : 464 -> 532
~ __Z25PersonalityIdFromSlotIdExRKNSt3__110shared_ptrIK8RegistryEEN10subscriber7SimSlotE : 700 -> 1084
~ __ZN9DataUtils27loadPlistFromBundleResourceEPKN3ctu11OsLogLoggerEPKc : 400 -> 464
CStrings:
+ "#D DisplayStatus [isOn=%s, isLocked=%s, isCoversheetActive=%s, isPasscodeSet=%s]"
+ "#D Getting main bundle"
+ "#D Input(%s) = %f"
+ "#D Personality Info: %s - %s"
+ "#D Sending OTASP success dialogue to UI"
+ "#D ThumperID: %s, info: %p"
+ "#D [conn %p] Connection closed."
+ "#D [conn %p] Got REST message: %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/CoreTelephony/CSI/Source/Common/SmsPduEncoder.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/Sources/CoreTelephony/CommCenter/CommCenterCommandDrivers/Sim/SubscriberDefinitions.cpp"
+ "Assertion failure: ( %s ), in file %s, line: %d"
+ "not active"
```
