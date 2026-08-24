## WorkflowResponsiveness

> `/System/Library/PrivateFrameworks/WorkflowResponsiveness.framework/Versions/A/WorkflowResponsiveness`

```diff

-383.8.0.0.0
-  __TEXT.__text: 0x2a284
+383.17.0.0.0
+  __TEXT.__text: 0x2a744
   __TEXT.__auth_stubs: 0x590
   __TEXT.__objc_methlist: 0x790
   __TEXT.__const: 0xf0
   __TEXT.__gcc_except_tab: 0xbac
-  __TEXT.__cstring: 0x1fd1
+  __TEXT.__cstring: 0x203d
   __TEXT.__oslogstring: 0x4014
-  __TEXT.__unwind_info: 0x5b0
+  __TEXT.__unwind_info: 0x5b8
   __TEXT.__objc_classname: 0x11a
-  __TEXT.__objc_methname: 0x241c
+  __TEXT.__objc_methname: 0x2436
   __TEXT.__objc_methtype: 0x26a
-  __TEXT.__objc_stubs: 0x1c60
+  __TEXT.__objc_stubs: 0x1c80
   __DATA_CONST.__got: 0x1b8
   __DATA_CONST.__const: 0x2c0
   __DATA_CONST.__objc_classlist: 0x58
   __DATA_CONST.__objc_protolist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x828
+  __DATA_CONST.__objc_selrefs: 0x830
   __DATA_CONST.__objc_superrefs: 0x58
   __DATA_CONST.__objc_arraydata: 0x18
   __AUTH_CONST.__auth_got: 0x2d8

   __AUTH.__objc_data: 0x370
   __DATA.__objc_ivar: 0x140
   __DATA.__data: 0xc0
-  __DATA.__bss: 0x98
+  __DATA.__bss: 0xa0
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /System/Library/PrivateFrameworks/CoreAnalytics.framework/Versions/A/CoreAnalytics

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libspindump.dylib
   - /usr/lib/libtailspin.dylib
-  Functions: 591
-  Symbols:   1158
-  CStrings:  958
+  Functions: 595
+  Symbols:   1163
+  CStrings:  959
 
Symbols:
+ GCC_except_table192
+ GCC_except_table195
+ GCC_except_table236
+ WRSanitizeForCA.removedCharactersExcludingUnderscore
+ WRSanitizeForCA.removedCharactersIncludingUnderscore
+ _OUTLINED_FUNCTION_106
+ _OUTLINED_FUNCTION_107
+ __WRTaskingDiagnosticRemovedDict
+ _objc_msgSend$removeCharactersInString:
- GCC_except_table190
- GCC_except_table193
- GCC_except_table234
- WRSanitizeForCA.removedCharacters
CStrings:
+ "Cannot report spindump for this dispatch queue, but in a specified process %@ in diagnostic %@"
+ "Cannot report spindump for this thread, but in a specified process %@ in diagnostic %@"
+ "Invalid dispatch queue label regex \"%@\": %@ in diagnostic %@"
+ "Invalid thread name regex \"%@\": %@ in diagnostic %@"
+ "no diagnostics enabled in diagnostic %@"
+ "no threshold for diagnostic %@"
+ "removeCharactersInString:"
+ "reporting multiple spindumps from a single diagnostic %@"
+ "reporting spindump, but not gathering tailspin in diagnostic %@"
- "Cannot report spindump for this dispatch queue, but in a specified process %@"
- "Cannot report spindump for this thread, but in a specified process %@"
- "Invalid dispatch queue label regex \"%@\": %@"
- "Invalid thread name regex \"%@\": %@"
- "no diagnostics enabled"
- "no threshold for diagnostic"
- "reporting multiple spindumps from a single diagnostic"
- "reporting spindump, but not gathering tailspin"
```
