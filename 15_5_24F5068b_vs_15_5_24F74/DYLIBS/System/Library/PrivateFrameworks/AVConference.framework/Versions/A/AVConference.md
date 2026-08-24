## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/Versions/A/AVConference`

```diff

 2115.6.1.0.0
-  __TEXT.__text: 0x6c0a6c
+  __TEXT.__text: 0x6c0a48
   __TEXT.__auth_stubs: 0x4f00
   __TEXT.__objc_methlist: 0x30800
   __TEXT.__const: 0x138e0
   __TEXT.__cstring: 0x7d831
-  __TEXT.__oslogstring: 0xf3680
+  __TEXT.__oslogstring: 0xf3678
   __TEXT.__gcc_except_tab: 0x2a90
   __TEXT.__ustring: 0x144
   __TEXT.__unwind_info: 0xef98
   __TEXT.__objc_classname: 0x47b9
   __TEXT.__objc_methname: 0x7146a
   __TEXT.__objc_methtype: 0x2449f
-  __TEXT.__objc_stubs: 0x46c00
+  __TEXT.__objc_stubs: 0x46bc0
   __DATA_CONST.__got: 0x1510
   __DATA_CONST.__const: 0x3198
   __DATA_CONST.__objc_classlist: 0x1170

   - /usr/lib/libtailspin.dylib
   - /usr/lib/libz.1.dylib
   Functions: 28448
-  Symbols:   45771
+  Symbols:   45769
   CStrings:  46310
 
Symbols:
- _objc_msgSend$setupLocalABTestSwitches
- _objc_msgSend$setupLocalOnOffSwitches
Functions:
~ -[VCSwitchManager initializeLocalSwitches] : 508 -> 472
CStrings:
+ " [%s] %s:%d SwitchManager: Non-seed build - using master local switch: %08X"
- " [%s] %s:%d SwitchManager: A/B testing turned off - using master local switch: %08X"
```
