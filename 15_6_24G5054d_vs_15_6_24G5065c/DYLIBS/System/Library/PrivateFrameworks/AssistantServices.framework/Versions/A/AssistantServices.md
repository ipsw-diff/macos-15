## AssistantServices

> `/System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/AssistantServices`

```diff

-3406.14.1.0.0
-  __TEXT.__text: 0x1ba678
+3406.16.1.0.0
+  __TEXT.__text: 0x1ba604
   __TEXT.__auth_stubs: 0x1280
   __TEXT.__objc_methlist: 0x1d8dc
   __TEXT.__const: 0x440
   __TEXT.__dlopen_cstrs: 0x324
   __TEXT.__gcc_except_tab: 0x284c
-  __TEXT.__cstring: 0x3a8d8
-  __TEXT.__oslogstring: 0x1007c
+  __TEXT.__cstring: 0x3a95b
+  __TEXT.__oslogstring: 0x10127
   __TEXT.__ustring: 0x2ac
   __TEXT.__unwind_info: 0x7798
   __TEXT.__objc_classname: 0x4e8b

   __DATA_CONST.__objc_arraydata: 0x2080
   __AUTH_CONST.__auth_got: 0x950
   __AUTH_CONST.__const: 0x8160
-  __AUTH_CONST.__cfstring: 0x266a0
+  __AUTH_CONST.__cfstring: 0x266c0
   __AUTH_CONST.__objc_const: 0x332a0
   __AUTH_CONST.__objc_intobj: 0x2328
   __AUTH_CONST.__objc_dictobj: 0xb90

   - /usr/lib/libobjc.A.dylib
   Functions: 11550
   Symbols:   25486
-  CStrings:  17755
+  CStrings:  17756
 
Functions:
~ -[AFSystemAssistantExperienceStatusManager fetchGenerativeModelsAvailability] : 1016 -> 620
~ -[AFSystemAssistantExperienceStatusManager init] : 152 -> 284
~ ___57+[AFSystemAssistantExperienceStatusManager sharedManager]_block_invoke : 164 -> 196
~ _HandleSiriCapabilitiesDidChange : 108 -> 252
~ _checkGMStatusWithUseCaseIdentifiers : 820 -> 792
CStrings:
+ "%s #SAEStatus #cacheUpdate Initializing cache"
+ "%s #SAEStatus #cacheUpdate Received notification %@, updating cache"
+ "%s #SAEStatus #cacheUpdate Updating cache:\ndeviceSupportsSAE: %d (%d)\n       saeEnabled: %d (%d)\n     saeAvailable: %d (%d)\n      swaiEnabled: %d (%d)\n        viEnabled: %d (%d)"
+ "%s #gms GMS available = %d (locale = %@, status = %ld, includeRestricted = %d)"
+ "%s #gms Locale is nil, falling back to system language"
+ "%s #gms Locale is nil, returning unavailable"
+ "-[AFSystemAssistantExperienceStatusManager init]"
+ "HandleSiriCapabilitiesDidChange"
+ "com.apple.os-eligibility-domain.change.greymatter"
- "%s #visualIntelligenceStatus:%d"
- "%s Fetched AFDeviceSupportsSAEDeprecated: %@"
- "%s Fetching AFDeviceSupportsSAEDeprecated"
- "%s Loading GMS availability via deprecated SPI"
- "%s Loading GMS availability via locale based SPI"
- "%s Locale is nil, returning unavailable"
- "%s SAE enabled status: %@"
- "%s SWAI status: %@"
```
