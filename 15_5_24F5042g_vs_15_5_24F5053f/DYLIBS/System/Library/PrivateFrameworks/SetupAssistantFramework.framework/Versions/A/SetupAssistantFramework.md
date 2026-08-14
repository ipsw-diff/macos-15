## SetupAssistantFramework

> `/System/Library/PrivateFrameworks/SetupAssistantFramework.framework/Versions/A/SetupAssistantFramework`

```diff

-7407.4.12.204.0
-  __TEXT.__text: 0x8b34
+7407.4.13.0.0
+  __TEXT.__text: 0x8b2c
   __TEXT.__auth_stubs: 0x350
   __TEXT.__objc_methlist: 0xcc8
   __TEXT.__const: 0x90

   __TEXT.__dlopen_cstrs: 0x4e
   __TEXT.__unwind_info: 0x3f0
   __TEXT.__objc_classname: 0x148
-  __TEXT.__objc_methname: 0x1948
-  __TEXT.__objc_methtype: 0x786
+  __TEXT.__objc_methname: 0x192d
+  __TEXT.__objc_methtype: 0x771
   __TEXT.__objc_stubs: 0x1740
   __DATA_CONST.__got: 0xf0
   __DATA_CONST.__const: 0xa0

   - /usr/lib/libobjc.A.dylib
   Functions: 279
   Symbols:   700
-  CStrings:  468
+  CStrings:  467
 
Symbols:
+ -[MBSAConnection createTeslaUsersWithInfo:completionBlock:]
+ ___59-[MBSAConnection createTeslaUsersWithInfo:completionBlock:]_block_invoke
+ _objc_msgSend$createTeslaUsersWithInfo:completionBlock:
- -[MBSAConnection createTeslaUsersWithInfo:prepareFirstAdminForResume:completionBlock:]
- ___86-[MBSAConnection createTeslaUsersWithInfo:prepareFirstAdminForResume:completionBlock:]_block_invoke
- _objc_msgSend$createTeslaUsersWithInfo:prepareFirstAdminForResume:completionBlock:
Functions:
~ -[MBSAConnection createTeslaUsersWithInfo:prepareFirstAdminForResume:completionBlock:] -> -[MBSAConnection createTeslaUsersWithInfo:completionBlock:] : 228 -> 220
CStrings:
+ "createTeslaUsersWithInfo:completionBlock:"
+ "v32@0:8@\"NSArray\"16@?<v@?BB>24"
- "createTeslaUsersWithInfo:prepareFirstAdminForResume:completionBlock:"
- "v36@0:8@\"NSArray\"16B24@?<v@?BB>28"
- "v36@0:8@16B24@?28"
```
