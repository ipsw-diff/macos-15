## AuthKit

> `/System/Library/PrivateFrameworks/AuthKit.framework/Versions/A/AuthKit`

```diff

-493.463.1.0.0
-  __TEXT.__text: 0x1f3318
+493.500.0.0.0
+  __TEXT.__text: 0x1f32ec
   __TEXT.__auth_stubs: 0xc00
   __TEXT.__objc_methlist: 0xcebc
   __TEXT.__const: 0x46811
   __TEXT.__cstring: 0xdc44
-  __TEXT.__oslogstring: 0xffb8
+  __TEXT.__oslogstring: 0xff9e
   __TEXT.__gcc_except_tab: 0x54ec
   __TEXT.__ustring: 0x1b8
   __TEXT.__dlopen_cstrs: 0xb4

   __AUTH.__objc_data: 0x3930
   __DATA.__objc_ivar: 0xf28
   __DATA.__data: 0x1868
-  __DATA.__bss: 0x7f8
+  __DATA.__bss: 0x7f0
   __DATA.__common: 0xa18
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 6028
-  Symbols:   11622
-  CStrings:  8443
+  Functions: 6027
+  Symbols:   11621
+  CStrings:  8442
 
Symbols:
- isSeedBuild.isSeedBuild
Functions:
~ -[AKFollowUpFactoryImpl _notificationFromPayload:pushMessageInfo:] : 2192 -> 2248
+ _OUTLINED_FUNCTION_0
- _OUTLINED_FUNCTION_0
~ -[AKDevice isSeedBuild] : 56 -> 52
~ ___23-[AKDevice isSeedBuild]_block_invoke : 16 -> 4
~ -[AKFollowUpFactoryImpl _itemFromPayload:pushMessageInfo:withAltDSID:].cold.1 : 116 -> 108
~ -[AKFollowUpFactoryImpl _itemFromPayload:pushMessageInfo:withAltDSID:].cold.2 : 116 -> 108
~ -[AKFollowUpFactoryImpl _itemFromPayload:pushMessageInfo:withAltDSID:].cold.3 : 64 -> 68
~ -[AKFollowUpFactoryImpl _notificationFromPayload:pushMessageInfo:].cold.1 : 128 -> 120
- -[AKFollowUpFactoryImpl _notificationFromPayload:pushMessageInfo:].cold.2
CStrings:
- "Continuity push detected."
```
