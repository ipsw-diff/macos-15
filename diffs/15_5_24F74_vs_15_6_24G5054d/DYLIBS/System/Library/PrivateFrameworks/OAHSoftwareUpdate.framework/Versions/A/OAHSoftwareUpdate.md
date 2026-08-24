## OAHSoftwareUpdate

> `/System/Library/PrivateFrameworks/OAHSoftwareUpdate.framework/Versions/A/OAHSoftwareUpdate`

```diff

-58.0.0.0.0
-  __TEXT.__text: 0xddec
+58.140.2.0.0
+  __TEXT.__text: 0xdf14
   __TEXT.__auth_stubs: 0x430
   __TEXT.__objc_methlist: 0xa68
-  __TEXT.__const: 0xa8
+  __TEXT.__const: 0xb0
   __TEXT.__gcc_except_tab: 0x2b0
   __TEXT.__cstring: 0x973
   __TEXT.__oslogstring: 0x1035
   __TEXT.__unwind_info: 0x390
   __TEXT.__objc_classname: 0x107
-  __TEXT.__objc_methname: 0x2bc3
+  __TEXT.__objc_methname: 0x2bcb
   __TEXT.__objc_methtype: 0x43b
   __TEXT.__objc_stubs: 0x2540
-  __DATA_CONST.__got: 0x260
+  __DATA_CONST.__got: 0x268
   __DATA_CONST.__const: 0xb0
   __DATA_CONST.__objc_classlist: 0x50
   __DATA_CONST.__objc_protolist: 0x8

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 314
-  Symbols:   901
+  Symbols:   902
   CStrings:  736
 
Symbols:
+ _NSRunLoopCommonModes
+ _objc_msgSend$performInModes:block:
- _objc_msgSend$performBlock:
Functions:
~ _processRosettaConfigurationPropertyList : 1676 -> 1764
~ -[OAHSoftwareUpdateController startUpdateWithOptions:withHostWindow:completion:] : 304 -> 408
~ __58-[OAHSoftwareUpdateWindowController installButtonClicked:]_block_invoke.51 : 396 -> 500
CStrings:
+ "performInModes:block:"
- "performBlock:"
```
