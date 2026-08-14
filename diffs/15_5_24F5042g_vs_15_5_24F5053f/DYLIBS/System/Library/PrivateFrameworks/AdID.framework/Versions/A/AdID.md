## AdID

> `/System/Library/PrivateFrameworks/AdID.framework/Versions/A/AdID`

```diff

-636.4.0.0.0
-  __TEXT.__text: 0x1b4c0
+636.4.1.0.0
+  __TEXT.__text: 0x1b5ec
   __TEXT.__auth_stubs: 0x470
   __TEXT.__objc_methlist: 0xfdc
   __TEXT.__const: 0x60
   __TEXT.__gcc_except_tab: 0x6d8
-  __TEXT.__cstring: 0x66f1
+  __TEXT.__cstring: 0x674c
   __TEXT.__unwind_info: 0x5a8
   __TEXT.__objc_classname: 0x19f
-  __TEXT.__objc_methname: 0x3c48
+  __TEXT.__objc_methname: 0x3c58
   __TEXT.__objc_methtype: 0x6cc
-  __TEXT.__objc_stubs: 0x3e00
+  __TEXT.__objc_stubs: 0x3e20
   __DATA_CONST.__got: 0x398
   __DATA_CONST.__const: 0xd0
   __DATA_CONST.__objc_classlist: 0x60
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1258
+  __DATA_CONST.__objc_selrefs: 0x1260
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x50
   __DATA_CONST.__objc_arraydata: 0x18
   __AUTH_CONST.__auth_got: 0x248
   __AUTH_CONST.__const: 0xd10
-  __AUTH_CONST.__cfstring: 0x40a0
+  __AUTH_CONST.__cfstring: 0x40c0
   __AUTH_CONST.__objc_const: 0x20f8
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x18

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 431
-  Symbols:   1396
-  CStrings:  1340
+  Symbols:   1397
+  CStrings:  1342
 
Symbols:
+ _objc_msgSend$isProtoU13state
Functions:
~ ___44-[ADIDManager(Private) handleAccountChange:]_block_invoke : 980 -> 1124
~ -[ADAppTrackingService localAdServicesEnabled:] : 324 -> 348
~ -[ADSegmentDataManager retrieveSegmentData:forceSegments:ignoreTimestamps:completionHandler:] : 836 -> 848
~ -[ADSegmentDataManager handleSuccessfulJingleSegmentResponse:dsidRecord:completionHandler:] : 3556 -> 3592
~ -[ADSegmentDataManager shouldSendSegmentDataToAdPlatforms:] : 1836 -> 1880
~ ___43-[ADJingleRequestManager authenticateUser:]_block_invoke : 676 -> 716
CStrings:
+ "[%@ handleAccountChange]: Device is Proto U13 State."
+ "[%@]: Skipping sending segment data to AdPlatforms. Account %@ is a U13 or MAID or EDU or Proto U13 account."
+ "[%@]: Skipping sending segment data to AdPlatforms. Account %@ is a restricted account (U13, U18, MAID, EDU or Proto U13)."
+ "[%@]: The current account is: EDU: %d. Managed: %d. U13: %d. T13: %d. U18: %d. Unknown Age: %d. Proto U13: %d"
+ "isProtoU13state"
- "[%@]: Skipping sending segment data to AdPlatforms. Account %@ is a U13 or MAID or EDU account."
- "[%@]: Skipping sending segment data to AdPlatforms. Account %@ is a restricted account (U13, U18, MAID or EDU)."
- "[%@]: The current account is: EDU: %d. Managed: %d. U13: %d. T13: %d. U18: %d. Unknown Age: %d."
```
